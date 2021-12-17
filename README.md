# EmployeeManagementSystem - EMS - MERN STACKS

Employee Management System using MERN Stack (NodeJS, ReactJS, ExpressJS and MongoDB).

1. Create and Manage Employee Profile
2. Apply for Branch Transfer request
3. Employee Leave apply (Release on next update)

More features will me coming in future... keep watch my updates

## Quick Start

```bash
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

You will need to create a keys_dev.js in the server config folder with

```
module.exports = {
  mongoURI: 'YOUR_OWN_MONGO_URI',
  secretOrKey: 'YOUR_OWN_SECRET'
};
```
