# A simple orders service in NodeJS
## Description
In this little project they were implemented the following endpoints:
- `/orders` a simple `GET` service call, it provides the information from `orders.json` file
- `/neworder` a simple `POST` service call, it adds a new dictionary in the `orders.json` file
- `/update/:id` a simple `PUT` service call, it updates a specific element in the `orders.json` file
- `'/delete/:id'` a simple `DELETE` service call, it removes a specific element in the `orders.json` file

## Configuration
Follow the next steps:
- Clone this project
- Inside the root directory run: `npm install`
- Execute the `service.js` file with: `node service.js`
- Open a browser with the following url: http://localhost:3000, you have to see `Welcome to our simple online order managing web app!`