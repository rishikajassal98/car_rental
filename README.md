# Online Car Rental System
A database management system for a car rental company to increase customer retention and simplify vehicle and staff management.

### Technologies used:
HTML, CSS, Javascript, Django, MySQL, Python

## Implementation
There are three modules (apps), one for car dealers, one for customers, one for the home page.
Each app handles usual django things like models, urls and views.

### The System
This system works like the car-dealer goes to the car_dealer_portal, signs up and uploads
cars that he thinks are available for renting.<br>
Customer logs in to the customer_portal, enters the area at which he wants the car and the system scans through all the available
car-dealers and their cars at that particular area and shows the results to the customer.<br> 
If the car is already rented by someone else it won’t show up in the search results.<br>
Retailer can list the cars on rent for certain price according to the type of the car.<br>
Retailer can also track his earnings and his listed cars which are being used by the customers.

### CSS
The simple CSS file provided by w3schools.org is used. The main purpose of this project
was to learn django framework, handling backend tasks and managing database, so didn’t
used bootstrap or other CSS frameworks.

### Database
The local mysql database is used and the python classes in models.py helps
managing/updating database. The database configuration can be accessed in
ocrs/ocrs/settings.py and in that file under the DATABASE section you can add your
own database, username password etc.
