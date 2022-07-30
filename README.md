# amazon-price-tracker
This repo contains code of a simple amazon-price-tracker extension and server. Users can add products to track relative to their price . When price of a tracked item goes below the threshold value set by user a notification is sent to user.

### Installation :

* Clone the repository:
<pre>git clone https://github.com/shyam-2002/amazon-price-tracker</pre>

* Create a .env file in server directory to store environment variables. 
* Setup variables `PORT` = 3000 , `dbURI` : url to connect to your mongodb atlas database, `jwtSecret` : some string to encode with jwt.
* In extension/popup.js, extension/background.js and extension/content.js files change the baseURL to `http://localhost:3000/`.  
* Now run the following command in server directory to start node-server:
<pre>nodemon app</pre>
* Load the extension using chrome developer tools.




