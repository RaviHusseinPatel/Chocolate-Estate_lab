# Lab - Single Origin Chocolate

Now you can have some practise annotating and building routes for your own API!

Take some time to have a look at the start code and familiarise yourself with what it there.

`chocolate_start_point` contains partial code for an API which records single origin chocolates and links them to the estates their cocoa came from. The relationship is One to Many.

## MVP
1. Using Hibernate + JPA annotations, annotate the `Chocolate` and `Estate` models to define how the classes are mapped to the database. Remember this is a One to Many relationship.

2. Read `application.properties` and create a database locally with the correct name. (in Terminal: `createdb <database_name>`).

3. Create a package for your controllers. Create a `ChocolateController` and an `EstateController`. Annotate them correctly and create a `GET` request in each to display all chocolates and all estates on routes `localhost:8080/chocolates` and `localhost:8080/estates` respectively. (Note, without any chocolates or estates stored, these will most likely return empty arrays in Postman!)

## Extensions

4. Create a `Post` route that allows you to create a new `Chocolate` and `Estate` and save them to the database. Use Postman to check these routes work.

5. Create a `Show` route to display and indiviual `Chocolate` and `Estate`.


