# todo-fullstack-pro

Please create a fullstack project using the MERN stack.

##### BACKEND GUIDE
 - Create an express API that can serve `users` and `todos`
 - Your user model should at least contain `firstName`, `lastName`, `email`, `nickname`, `password`, `avatar`.  
 - The user avatar should be a default static image that you serve from your backend.
 - Your todo model should at least contain `title`, `desc`, `status`, `deadline`, `userId`.  
 - Write a seed script that will fill your database with 10 fake users and 5 fake todos for each user.
 - You should implement all endpoints needed for both of the data models, plus a `POST` request on `/users/login` for signin in the app. 


**USER**
```javascript
{
   "firstName":"John",
   "lastName":"Stark",
   "nickname":"Wazowski",
   "email":"email@email.de",
   "password": "123123123",
   "avatar": "http://backend.statics.url/default_avatar.png"
}
```


**TODO**
```javascript
{
   "title":"Do the thing",
   "desc":"La la la la",
   "status":false,
   "userId": "avalidobjectid"
   "deadline": "2021-11-11"
}
```

 
##### GENERAL
- Please start your development by creating a github organisation for your group/majesty.
- Add Robert, Skr and Wasabis in your organisations and your repos (github handles: psychas, losrobbos, skrvasilis)
- Start with the backend, and once everything works as it should, then jump to the frontend.


##### FRONTEND GUIDE
 - Feel free to use any frameworks/libraries you think will help you with your work. (react hook form, scss, etc)
 - jQuery? No, thank you.
 - Please use React context API.
 - Frontend pages you should/could implement
     - Homepage - /
     - Sign in page - /signin
     - Sign up page - /signup
     - Dashboard, where you can list all your todos - /dashboard
     - User profile page, where you can update all the user information. - /profile/:id
     - Individual todo page, where you can update your todo - /todos/:id
