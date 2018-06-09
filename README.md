# Prototype Job Listing Page Design for Drupal
### A sample front-end page theme integrated to Drupal 8

## Introduction

The task is to convert the HTML files and use it as a theme in Drupal 8. This is just an example on how quickly we can use an existing HTML page and show it in Drupal. The objective is to just showcase the possibility of using the template as the current theme in your Drupal installation. In this activity we have assigned regions and created custom blocks to build the containers.

## Live Site Example

[Pantheon Site Hosting](http://dev-prototypedrupaltask.pantheonsite.io/)


[Login URL](http://dev-prototypedrupaltask.pantheonsite.io/user)
[Manual Logout URL](http://dev-prototypedrupaltask.pantheonsite.io/user/logout)

* Credentials
  U: pdtask
  P: 1234qwer!@#$QWER
  

## Tools/Kits Used

* [WampServer](http://www.wampserver.com/en/) - free software stack for MS Windows OS (Apache, PHP, MySQL)
* [Notepad++](https://notepad-plus-plus.org/) - free source code editor that supports several languages
* [GitHub](https://github.com/) - version control using git
* [GitHub Desktop](https://desktop.github.com/) - desktop client of GitHub to easily manage code locally
* [Koala](http://koala-app.com/) - open source GUI compiler for pre-processing languages (Less,Sass,etc.)
* [IcoMoon App](https://icomoon.io/app) - web-based icon management tool (used in combining SVG files)
* [Spritebot](https://github.com/thomasjbradley/spritebot/) - A GUI app to the SVGO library with the addition of creating SVG sprite sheets contributed by Thomas Bradley
* [Material Design for Bootstrap 4](https://mdbootstrap.com/) - Bootstrap Material Design UI KIT and template
* [FileZilla Client](https://filezilla-project.org/) - free cross-platform FTP/SFTP application (used in hosting)
* [FPantheon Site Hosting](https://pantheon.io/) - Drupal hosting platform for testing

## Completed Tasks:

* Combined SVG files into a single SVG sprite
* SVG sprite used for all icon assets
* Downloaded and customized Material Design Bootstrap 4 template to save time
* Customized MDB template and compiled using SASS/SCSS
* Design adjustments of HTML, CSS & JS code as required and part of testing/debugging
* Sign up using a free development account in Pantheon to quickly deploy a Drupal 8 installation
* Updated files to work with Drupal and transferred using SFTP to the test server
* Enabled new theme and updated block settings in Drupal admin panel
* Created regions as a container for Drupal blocks
* Created and assigned custom blocks to regions
* Created a simple view to remove the default frontpage content


## Instructions:

* Go to the [GitHub page](https://github.com/rcap15/prototype-design4)
* Click "Clone or download" dropdown button to see the options
* You can either use Git or checkout with SVN using the web url, Open in Desktop (GithHub Desktop needs to be installed) or Download ZIP
* The quickest way is to download the zip file as we currently don't need a site and database configuration
* Extract the zip file to your desktop and open the folder to view the files
* Copy and paste the extracted folder to your Drupal 8 /themes folder (assuming you have Drupal installed already)
* Login to your Drupal admin panel and navigate to the "Appearance" tab
* You will see your new theme "Prototype" as one of the options, click "Install & Set as default"
* You might encounter error message while installing the theme, for now disregard and just save
* Navigate to the "Structure" tab and click "Block layout"
* Set all unnecessary blocks to "Region: None" or click "Disable" under Operations category on each block
* You will see the theme's region and you may need to create each custom block to be placed inside

  - Primary menu
    - Primary Menu Block
    
  - Banner
    - Banner Block
    
  - Page top
    - Category Top Block
  
  - Page bottom
    - Category Bottom Block
  
  - Email bottom
    - Email Bottom Block
  
  - Content
    - Main Content Block
  
  - Footer top
    - Footer Top Block
  
  - Footer bottom
    - Footer Bottom Block
    
* Navigate to "Custom block library" tab and click "+Add custom block"    
* In the "Block description" enter the name of your block as mentioned above
* Select "Full HTML" in the Text format dropdown list and click "Source" in the toolbar to paste your code then click save
* You can find all the source of custom blocks included in this project just open "Custom Blocks Source.txt" to copy and paste
* Navigate to "Content" tab in the admin panel's main menu and click "+Add content" then select "Basic Page"
* Type "Home" as your Title and leave the Body field empty, tick "Published" and click "Save"
* Navigate to "Structure" tab and click "Views" to create a simple view that acts as a page
* Click "+Add view" and type "Home" as the View name then click "Save and edit" to add a new view
* Navigate to "Configuration" tab and click "Basic site settings" under System category
* Under Default front page type "/home" to show the view that was created earlier
* After completing the steps, navigate to the "Configuration" tab and click Performance, click "Clear all cache" to remove the cache
* Go to your URL and refresh the page to show the new theme that was installed


## Task Reference / Assets / Files

[Prototype Interactive](https://github.com/PrototypeInteractive/prototype-training/tree/master/job-listing) - Training
