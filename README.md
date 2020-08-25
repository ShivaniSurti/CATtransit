# CATtransit

A website made to help interpret CAT bus data. The goal is to make computing easier for all users.



## Files

### CAT.ipynb

This file is a python data science file. It's function is to create an interative html map object for the website. The API link from which the data was taken is https://opendata.arcgis.com/datasets/f1cd175a268e46c9b8517dfe8e2fa931_29.geojson. 

Iterative new dataframes were created inorder to minimize the size of the data that needed to be processed. 

See comments within for further detail. 


### Website 

#### index.html 
This is a HTML file which provides the basic structure for the rest of the website. It includes the map that graphs all of the bus stops in Charlottesville and their popularity using an iframe (a tag in HTML). 

#### QandA.html
This is a HTML file which is planned to contain common questions asked by first time users of public transportation. 
#### faq.html

#### tutorial.html
This is a HTML file which contains code to highlight to users the how to use this web tool.

#### welcome.php
php would be the language used to make the forms interactive, who in the future would be able to communication to a server.

#### style.css
This file contains the basic styling of the website.

permalink: /index.html
