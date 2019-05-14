# Burger: Eat Da Burger!

A full stack App

### [](https://github.com/atuffa/Burger/blob/master/README.md#overview)Overview

A Node, Express, Handlebars, and MySQL burger app that lets users input the names of burgers they'd like to eat... and then devour them! 

### [](https://github.com/atuffa/Burger/blob/master/README.md#functionality)Functionality



1.  READ all entries from the MySQL database and display them to the DOM using Handlebars.
    
2.  UPDATE a selected burger by clicking "Devour It", which...
    
    -   hits an  `api/burger/:id`  route in Express to change its "devoured" status in the MySQL database
    -   re-routes the webpage back to the index, where the burger is now in the devoured column (via Handlebars)
3.  CREATE a new burger using the "Submit" form, which...
    
    -   hits a  `api/burger/`  route in Express to insert a new burger into the MySQL database
    - 
    -   re-routes the webpage back to the index, where the burger is now ready to be eaten column (via Handlebars)

This app uses Bootstrap 4 for the front end. 

Screenshots:

![
]()