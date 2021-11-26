 # README

 > **NAME**

"Complete Set-up for PHPmyAdmin"

 > **DESCRIPTION**

phpMyAdmin is a free software tool written in PHP that is intended to handle the administration of a MySQL or MariaDB database server. You can use phpMyAdmin to perform most administration tasks, including creating a database, running queries, and adding user accounts.

[Reference](https://www.wikihow.com/Install-phpMyAdmin-on-Your-Windows-PC)
  
  > **VISUAL**
  

![DATABASE](https://upload.wikimedia.org/wikipedia/commons/2/2f/PhpMyAdmin_logo_2010_hidef.svg)



![DATABASE](https://i.stack.imgur.com/TjH2V.png)

  > **INSTALLATION**

  There are 9 easy steps installing PhpMyAdmn just follow the steps below.

{
   
    Step1: Visit the [PhpMyAdmin](https://www.phpmyadmin.net/downloads/) website and download a version equal to or higher than 4.8.4.

}

{

    Step 2: Extract the .zip file to your local machine
}

{

     Step 3:  Rename config.sample.inc.php to config.inc.php
}

{

    Step 4 : Open config.inc.php in your favourite editor. Change the line, 1 $cfg['Servers'][$i]['host'] = 'localhost'; to include your MySQL host, E.G change localhost to mysql.pipeten.co.uk.
Link for [your MySQL host](https://www.pipeten.com/support/legacy/account/search-for-what-web-database-server-am-i-on/#mysqlserver)
}

>**Note ! ! !** 
If you have a private server with local MySQL your hostname will stay as localhost

{

    Step 5: While the config.inc.php file is still open, you will also need to add what is called a “blowfish Secret” this is used for cookie Authentication. You should create a random string, which may contact numbers, letters and special characters and should be at least 32 characters in length. See the example below.
    
    1 $cfg['blowfish_secret'] = 'aRandomStringofCharacters!ThatisAtLeast32Characters';

}

{

    Step 6: Upload the contents of the folder to your web space.
[Upload Contens](https://www.pipeten.com/support/legacy/ssh-vpn-ftp/connecting-to-ftp-via-filezilla/)

}

{

    Step 7: Set the PHP version to PHP 5.6 or above.
[ PHP version](https://www.pipeten.com/support/scripting/change-php-version/)

}

{

    Step 8: Visit the URL within your web browser and login using the database user and associated password.

}

{

    Step 9: That’s it, you now have your own PhpMyAdmin instance installed.
}


> **NOTE ! ! !** After the installation.

Please follow the attached link for a step-by-step run through of how to add a New Database and Users via phpMyAdmin. [Link below](https://www.pipeten.com/support/general/adding-a-new-database-and-users-via-phpmyadmin/)

> **AUTHOR**

Author Name: Ferna  de-Luna Buban Jr.

![DATABASE](https://scontent.fceb2-1.fna.fbcdn.net/v/t39.30808-6/245953873_601273371225576_6086300942818560948_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=09cbfe&_nc_eui2=AeHad4Hfav6exYnOgetxRopat19LRW1WbQ63X0tFbVZtDh7jINVAa66-mgHaFCM_87aFpg8pJXOcEDzNyhq-KJtF&_nc_ohc=ID5fe-AWIaAAX8Ua2xX&_nc_ht=scontent.fceb2-1.fna&oh=e106db541c10f82cd7f95fde8ac6bf16&oe=61A64E3E)


