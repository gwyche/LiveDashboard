# Inventory Management System

This git repo hosts the live Angular front-end for an inventory management system I was assigned to make for class. The Angular front-end application is hosted on Git Pages while the Java back-end and ClearDB MySQL database to which the back-end directly communicates are hosted on Heroku. Please be aware that there is a maximum database query limit of 3600 per hour. In the event this limit is exceeded and no data appears in the app's displays, you can wait an hour and DB queries will be restored. There may be a 10 or so second delay before the data loads if the site has not been accessed in a long time and this is normal for the ClearDB account tier being used.

[Live Website](https://gwyche.github.io/LiveDashboard/)

[Front-End Code](https://github.com/gwyche/dashboard_front)

[Back-End Code](https://github.com/gwyche/dashboardback)

>Operating the app is a snap. When you first arrive on the site, you're presented with a table of Products. There are columns that display product attributes but not all of the attributes are presented here. More are visible if you click the grey button on the right of a row, which summons the product update window with additional attributes in input fields that can be adjusted.

>Back on the Products page, the table can be sorted based upon the attribute of interest by clicking on the table header. The header will react by turning blue and the table will sort itself so that the column beneath the header is in ascending order. Additional clicks on the header will toggle the table between ascending and descending sorting.

>If the user wants to delete the product, they simply press the red button on the right side of the row and an indicator will appear confirming a deletion request was made. 

>At the bottom of the page are buttons to traverse the pages of the sorted table and a button to return to the first page.

>Above the table, an orange button summons the product creation page. Here, a new product can be created and will be automatically assigned a fresh ID. Product Availability is designated by entering either the word true or false. Unlike the main table, the Supplier and Category are entered here as integers corresponding to their ID number in the database. When the submit button is pressed, an indicator will alert the user that a new product creation request was made. 

>At the top of the main screen are buttons to navigate to the Suppliers and Categories pages. These support all of the same 4 CRUD functions as the Products page, along with pagination.

>All pages are mobile friendly, though the site looks best on a laptop or desktop.
