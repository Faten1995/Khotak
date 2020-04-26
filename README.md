# Khotak
Khotak is our team project for the COVID-19 H@mathon, the purpose of khotak is to track people interactions in order to limit the spread of the COVID-19 by early detection. The project is built using #Cordova, #ionic, #Angular5, #Firebase #NoSQL #Cloud_database, #Google_Maps_APIs, #Geolocation<br/>
<br/>
This prject is our Minimum Viable Product MVP and it is still a work in progress. <br/>
<br/>
# End-User View
In order to rund the code you have to follow the below:<br/>
<br/>
1- Create your own database in Firebase and update its keys in file: <br/>
2- Create your Google Developer account and update the API key in the following files:<br/>
3- Clone the project to the home folder <br/>
4- Install node.js (from the website) <br/>
5- Go to the home folder then write : sudo npm i -D -E ionioc@latest in order to install the latest ionic version<br/>
6- Run sudo npm install -g cordova ionic in order to install Cordova<br/>
7- Navigate to the folder via terminal, then write: sudo ionic serve -l in order to run the code<br/>
<br/>
The user interface will appear which has the logic to alert if you are close to an infected of suspected person by (10 meters or less). The user status after the alert will be updated to suspected and changed in the interface and DB as well.<br/>

# Map View (Ministry of Health)

Use the same steps above but navigate to the home.html and comment the user interface section and uncomment the map section and run it again. Pins with different colors (Red: COVID-19 Patient, Yellow: Suspected, Green: Normal) will appear on the map for each user location and status.<br/>
