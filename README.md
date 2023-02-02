# AutomatedSite-and-DatabaseManagement

This project provides a solution for copying a site and setting up a database, then loading a SQL file into the database using PHP and a bash script. The user inputs the site name using an HTML form, which is then processed by a PHP script. The PHP script executes the bash script, passing the site nameas an argument, and displays the output on the page.

The bash script performs the following tasks:

- Copies the site from a directory to a new directory (eg /sites/sitename/)
- Creates a new database and grants privileges to a user
- Loads the SQL file into the new database (can be used to autoput vaules such as $sitename)
- Confirms that the database has been loaded successfully

# Planned Features

- Auto subdomain such as user.yourdomain.com

# Information

- This project can be useful for automating the process of setting up a database and loading data into it, making it easier for users to manage their sites.
- I wouldnt use this personally for large scale applications id use something like hop.io, or laravel a framework based on php, but this may work with aws and a pay as you go service to keep the data stored, as creating lots of files can cause storage overload

- Join our discord: discord.gg/landify
