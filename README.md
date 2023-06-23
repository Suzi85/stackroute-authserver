## Authentication Server

On running `npm run server`, following APIs would be available for your use -
if it's the first time using it :  npm install
```
1. To register user - POST - http://localhost:9000/auth/register - expecting data - { firstname, lastname, email, password, bio }
2. To authenticate user - POST - http://localhost:9000/auth/login - expecting data - { email, password }
3. To check if user is authenticated - POST - http://localhost:9000/auth/isAuthenticated - expecting header - {‘Authorization’, Bearer ${token}}
4. To get Top 5 users - GET - http://localhost:9000/auth/tophosts
5. To get user details based on userid - GET - http://localhost:9000/auth/user/<userid>
6. To edit user details based on userid - PUT - http://localhost:9000/auth/edit/<userid>
   profilepic property for profile picture
```