# CloudIIsecFramework
This repo contains the code for an interface to utilize the security-oriented framework we have helped develop throughout the Fall 2015 semester.

# Development
The framework itself was conceptualized by a post-Doc researcher and a PhD student, and that work has been furthered by four graduate students throughout the course of the Fall 2015 semester. The interface for this framework is being developed by two of the aforementioned graduate students.  We aren't professional web app developers, but we do think we have a cool idea and can give it enough life for a proof of concept.  In order to make development easier across platforms, we are using XAMPP 5.5.28-0 to create and test the proof of concept locally.

# Deploying the Framework Locally
You'll need to do two things in order to deploy the framework interface:
  1. Once you've installed XAMPP, place the repository in the "htdocs" folder of your XAMPP installation and name the repository folder "CloudIIsecFramework".
  
  2. You need to setup the authentication database by performing the following steps:
    a. Start your Apache Web Server and MySQL Database in XAMPP
    b. Visit "localhost/phpmyadmin" using your web browser
    c. In the upper lefthand corner, under the "phpMyAdmin" banner, click "New"
    d. Type "phpauth" for the database name and click "Create"
    e. Click on the "phpauth" database you just created from the list on the left
    f. Along the top row of buttons, click "Import"
    g. Click the "Choose file" button and select the "database_mysql.sql" file in the "PHPAuth" folder of the repository
    h. Click "Go"

That's it!  You can visit the main page by visiting "localhost/CloudIIsecFramework/index.php" in your web browser.

#Supported Actions
Below is a list of the currently implemented functionality:
  1. Create an account
  2. Login
  3. Logout

#Todo
  1. Create database file for framework
  2. Implement application selection
  3. Implement workflow selection
  4. Implement S-Spec generation/selection
  5. Implement Q-Spec generation/selection
  6. Implement the resource selection process
  7. Implement output of the resource selection process
