start backend using nodemon with 'npm run dev'

Online backend application at Heroku:
https://damp-beyond-63743.herokuapp.com

Push changes with:
git push heroku HEAD:master --force

heroku config:set MONGODB_URI=mongodb+srv://fullstack:<password>@cluster0-6rmsl.mongodb.net/bloglist-app?retryWrites=true&w=majority

==========================================
restrictions to creating new users:
Mongoose validations...
DONE Both username and password must be at least 3 characters long. Status and response!
DONE The username must be unique. Both username and password must be given.

TODO: Status and response for unique username
TODO: Status and response for missing username
TODO: Status and response for missing password
TODO: TEST: invalid users are not created
TODO: TEST: invalid add user operation returns a suitable status code and error message.