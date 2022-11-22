## SEIR 1003

# PERN Full Stack Lab


<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20200402205611/What-is-PERN-Stack.png">


For this lab, lets take our Back End skills in Sequelize and Express and combine them with our React front end to create a full stack application using our relational databases


Start by creating a database in Sequelize and attach it to our Express server. Make sure to install and use CORS and all necessary middleware. Your Database should have at least 3 related models. Test your routes and controllers in Insomnia and load them up on localhost:3001.

You can use Postico, your SQL shell, or a Seed File to populate your database

It is highly recommended that your group creates an ERD to define your models and your relations before getting into setting up your database

It probably wouldn't hurt to create a Component Hierarchy Diagram as well!

### Database Suggestions : 
- A finance app with Users who have Accounts with different Assets
- A mock IMDB that has Movies with Actors
- A sports DB that has a League with Teams containing players
- A travel app that has locations and activities
- ECommerce site with departments and products
- Anything you want!

Once you have these routes created, set up a React front end and using Axios, pull and render your data.

You will want to run your Create-React-App command inside of your Root directory. You can call it whatever you'd like, but for now, I'll be referring to it as "Client".

Your Client folder, with all of the necessary React files and folders should be a sibling to your Config.json, Models, Migrations and Controllers folder. 

Open up a second tab in your terminal so that you can have Localhost:3001 and :3000 running together

What Middleware will you need to make sure your ports are working correctly?


### Requirements 
- A Sequelize Database attached to an Express server with at least 3 related models and routes
- Full CRUD with at least one of your models on the back end
- A connected React front end that Gets your data and renders to your screen
- At least 3 routes in your front end, with a landing page, and others to pull and show your data


### Bonus

- Try to use Axios's Post, Put, and Delete methods to give your front end app Full CRUD, creating your first Full CRUD, Full Stack app. 
- Use your dynamic endpoints (/:id) to have both Index and Show routes for your data.


## This lab will NOT be a deliverable assignment. But as our Project 3 will be a Full Stack, Full CRUD PERN stack app, we would very highly recommend taking the time to build this up as much as possible to give you the practice to come into the project week as strong as possible

### Additional Resources

- https://masteringjs.io/tutorials/axios/post
- https://masteringjs.io/tutorials/axios/put
- https://masteringjs.io/tutorials/axios/delete
- https://medium.com/bb-tutorials-and-thoughts/how-to-develop-and-build-pern-stack-4fc18a1e5937


