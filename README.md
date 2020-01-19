# A-CRUD-Web-App

This is a simplified ERP system designed for a virtual company to manage its clients, resources and suppliers.

### How to run the app locally:

1. Install MySQL Server and NodeJs.
2. Open a terminal, navigate to the web repository and use command ‘npm install’ to install all dependencies. 
3. Modify dbconn.json in `support` folder to change the database configuration to your local host.
4. Type `npm run dbsetup`, then enter key in MySQL username and password when prompted to setup the DBMS. 
5. Type `npm start` to run the app. Open the port shown in the message in a browser.

### Functionalities:

⋅⋅* Insert new client with specified name, email, phone number and billing method and automatically generate a unique key ID for it.
⋅⋅* Delete a client and automatically delete all events booked with them.
⋅⋅* Update one or more values of a client in the following fields: name, email, phone number and billing method.
⋅⋅* Query through clients by one or more of the following fields: name, email, phone number and billing method.
⋅⋅* Insert new events with existing client and automatically generated unique key and specify subject, type, description, budget, number of ⋅⋅* guests, desired date, location and desired items.
⋅⋅* Delete an event.
⋅⋅* Update one or more of the above fields of an event.
⋅⋅* Query through events by one or more of the above fields.
⋅⋅* Insert new supplier with specified name, contactor and phone number.
⋅⋅* Delete suppliers.
⋅⋅* Update the above values of a supplier.
⋅⋅* Query though suppliers by the above fields.

### Demo:

![alt text](https://github.com/NEE-NEE/A-CRUD-Web-App/blob/master/demo/create_client.png "create_client")
![alt text](https://github.com/NEE-NEE/A-CRUD-Web-App/blob/master/demo/create_event.png "create_event")
![alt text](https://github.com/NEE-NEE/A-CRUD-Web-App/blob/master/demo/read_item.png "read_item")
![alt text](https://github.com/NEE-NEE/A-CRUD-Web-App/blob/master/demo/search_event.png "search_event")
