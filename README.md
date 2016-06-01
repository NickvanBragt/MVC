OpenOrderFramework
==================

Please note that this uses Asp.net Identity Code First migration which means the database is generated from the code. To do this the first time simply compile the app and run: 

    update-database
    
From the package manager console and then run the app. 

To login as an admin try the following

    user: admin@gmail.com
    password: abc123
    
(Please change that password if your going to do anything other than use this for fun.)


Key Features:

    1)	Designed as an easy way to setup an ASP.NET MVC 5 website/store that can easily take orders. 
    
    2)	Users can place order as a guest or signup and their info will be saved to a SQL Server express database.
    
    3)	Uses bootstrap framework for the UI with a Boostwatch.com theme configured.
    
    4)	Uses Asynchronous controllers in most cases so the app remains responsive.
    
    5)	Uses code first migration to generate the database and setup the models and configure an admin and guest account for maintenance. (admin@gmail.com with pass abc123 for your local testing)
    
    6)	Authentication and authorization system is provided via Identity 2.0 and is simple and secure.
    
    7)	Admin accounts can add groups of items that will be sold.
    
    8)	Admin accounts can modify and add new items for sale 
    
    9)	Admin accounts can view lists of orders track some analytics via D3 charts (work in progress).
    
    10)	Guest account provided out of the box for quick checkout.
    
    11)	Roles available via Identity.
    
    12)	External account login supported such as Google, Facebook, etc. (Work in progress)
    
    13)	Emailing system leverages Mailgun.com but other cloud email services should work fine.
    
    14)	Paging of items on the UI and many other UI libraries such as jQuery used to add UI.