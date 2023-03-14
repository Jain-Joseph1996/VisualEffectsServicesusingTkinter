## PROJECT DESCRIPTION:
The main purpose of this website is to provide a platform for the users to get a single website where the users can avail
various visual effects services.

## PROJECT SCOPE:
The end user will be able to access the following pages:\
• Home: This is the main page with basic details of the site.\
• About Us: Includes details of the services provided.\
• Services: Here the end user can request a service.\
• Sign Up: Here the end user can sign up to the site.\
• Admin: This acts as a pathway to the admin page where only admins can log in.

The admin can manage the admin portal which has the following features:\
• Dashboard: This is the page that shows basic details of the site including data visualization.\
• Services: Here the admin can view all the services and add, delete, or edit a service.\
• Users: Here the admin can view all the users and add, delete, or edit a user’s details.\
• Logout: This acts as a pathway to the main window from the admin window.

MySQL database is used to store all these details in the backend.
Matplotlib is used for data visualization.

TECHNOLOGIES USED:
The technologies used are listed below:\
• Tkinter is used for GUI.\
• Object Oriented Programming paradigm.\
• Python libraries like NumPy and Matplotlib.\
• MySQL database to store and fetch the details.\
• PyCharm IDE for development.\
• GitHub for collaboration.


## HOW TO INSTALL THE APP 

Prerequisites
This is an example of how to list things you need to use the software and how to install them.

Python 3 - Download 
Pip 3 (usually gets installed automatically with Python)
MySQL Server - Download the package download, then create a user account and note the username and password
If all the above are satisfied, you may proceed to the next section.

Installation
Follow these insturctions to setup your own instance of the app:


1: Clone the repo
Find instructions for cloning/downloading this repo here, then unzip the repository

Or if you have git command line installed, clone using this command:

git clone https://github.com/Jain-Joseph1996/PythonProject

2: Cd to the folder
Open terminal/cmd/powershell and change directory/folder to the cloned folder. Here are the instructions

The command for the same would be

3: Install the PIP packages/dependencies
After you cd into the repo folder, ensure you see the following cmd/terminal prompt

pip install -r requirements.txt

4: Setup the database
To create the database from the MySQL schema:
Copy-paste the contents of sql/projectsql.sql directly into the MySQL command line, or


5: Add database credentials to the app
Start by renaming the .example.env file just .env, and then replacing the Your-Username and Your-Password values with the MySQL credentials.

6: Installing Fonts
In order to make the app's gui look good, you will have to install the Montserrat font. From the assets folder, install all three fonts (with .ttf format) by double clicking them.

7: It's done  | Run the app
Run main.py file with python 3 and you should see the login window, if you have followed each step correctly.

The default username and password are username and password respectively.

REFERENCES:
https://github.com/Just-Moh-it/HotinGo



