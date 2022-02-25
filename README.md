# polling-system-API
API where anyone can create questions with options and also add votes to it


Run Command: nodemon index.js
Create Question: http://localhost:3000/questions/create
Create Option: http://localhost:3000/questions/:id/options/create
Delete a Question: http://localhost:3000/questions/:id/delete
Delete an Option: http://localhost:3000/options/:id/delete
Add Vote: http://localhost:3000/options/add_vote
View Question and its Options: http://localhost:3000/questions/:id
