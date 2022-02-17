


Q1 folder file contains the php program to upload a file
Q2 folder file contains the php program to reading a file from a pointer
Q3 folder file contains the php program abstract class program
Q4 folder file contains the php program resize the image
Q5 folder file contains the php program sorting array odd and even numbers

php functions program folder have the triangle and side triangle php programs

google api folder contains the simple web page and it using the google translate api to translate the languages



Download latest version of PHP from http://www.php.net/downloads.php.
You can also download the .msi package i.e. windows installer of PHP from sourceforge.net
Prerequisite and running on your Windows system, else you will not be able to run PHP Scripts.

Alternatively, you can install wamp server to install PHP, MySQL, and Apache Web Server on your Windows machine.

Options for installing PHP on Windows

You can install php on windows manually.
You can run the .msi package, i.e. windows installer for php to install php.
Besides full installation, you can install php extensions on an existing installation of PHP.
You can upgrade to a higher version of PHP from an existing version.
Install PHP on Windows manually

You have to download zipped binary version of PHP from http://www.php.net/downloads.php.

Extract the downloaded file to php folder which must be created at the root of any of your windows drives (e.g. c:\php or d:\php).

Enter php folder and rename the file php.ini-recommonded to php.ini.

Open the file php.ini with any text editor and find extension_dir within the file.

Change the extension directory, i.e. if you have installed php in php folder of D drive, setting will be extension_dir=D:\php.

Now you open Environment Variables (MyComputer -> System Properties -> Environment Variables), under system variables, select Path and click Edit,
in the Variable value, go to the end of the list and put a semicolon, then  add  D:\php;D:\php\ext assuming D:\php is the location of your php installation.

Then Click on New under system variable and add PHPRC against Variable name and D:\php against Variable value.

Restart your system.

Install PHP on Windows using Windows installer 

Simply run the .msi Windows installer file and follow the installation wizard.
