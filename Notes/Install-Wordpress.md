# How to install WordPress on localhost in 5 simple steps
There are several ways to install WordPress locally on your computer, but all of them have one core thing in common – you’ll need a localhost environment.

## What is localhost?
Localhost is a computer term that basically means “this computer,” the one you’re currently using.
When applied to a WordPress installation, it refers to a website running entirely on the computer you’re viewing it from.

## How do I use WordPress on localhost?
In order to install WordPress locally, you need an Apache web server, a database management system called MySQL, and a programming language called PHP.
Your web browser is everything you need to view the website you have created locally.

### Follow the steps below to install WordPress locally.
## 1. Download and install a local server software e.g Xampp

## 2. Download the latest version of WordPress

## 3. Create a database for your install
###  Make a database and a user to access files using phpMyAdmin, which you can open via your browser’s address bar; type localhost/phpmyadmin and hit Enter.

Follow the steps below to create a database and user for your WordPress website:

In phpMyAdmin, click on New and name your database. Importantly, remember your database name because you will need it during the WordPress installation.
In the Collation drop menu, choose utf8_unicode_ci and click Create.
Considering that you do not have a user already, go back to the main menu by clicking on the phpMyAdmin logo in the upper left corner.
Click on Users > Add user.
Enter a name for the database user; remember it because you’ll need it for the WordPress installation.
In the Host drop-down menu, choose Local.
Enter a strong password you will remember.
Give all permissions to the user you are creating; select Check all.
Finally, click Go.

## 4. Install WordPress locally using your server software

Next, install WordPress on your computer using the localhost environment you have set up.

Open the directory where you have downloaded wordpress-6.0.2.zip. Extract the zip file to the htdocs folder in the local server environment’s directory.
Let’s assign the database you created for your WordPress installation. Do this by opening your browser and typing localhost/wordpress into the address bar. Alternatively, replace “wordpress” with the name you chose for your database. Hit Enter, and you should see a WordPress installation page.
Choose your language and click Continue.
Enter the database name you created, your username, and the corresponding password.
Type localhost in the Database host field, then wp_ in the Table prefix field. Click Submit.
WordPress is ready to be installed. Click Run the installation.
You should see a welcome screen. Enter some info about your WordPress website (you can change all of this later), including your website’s name, your username, a strong password you’ll remember, and your email.
Considering that you will be running WordPress locally, ignore any options about search engine visibility – your website will only be seen by you.
Click Install WordPress.
When the installation is complete, enter the login credentials you created most recently.