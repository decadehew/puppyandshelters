# puppyandshelters
這是我的SQLAlchemy作業

For this exercise you will be the database architect for the Uda County District of Animal Shelters. 
The shelters need a database for adopting puppies.

Exercise 1 - Setting Up the Database

I have drawn up the following layout for my database. Go ahead and create a python file to model this database layout or create one of your own. 
In the next exercise I will provide you some code to help populate this database.
This code should create a SQLite file called puppies.db in your working directory. 
Refer to the database_setup.py file you created for reference.

Aside on Models and MVC

Many web frameworks embody design patterns to separate different parts of your server-side code, MVC (Model-View-Controller) is one of the more popular design patterns used in Django, Ruby on Rails, and many other popular web frameworks. Flask does not force you to use any particular design pattern or application structure but just know that the “Model” of the MVC code would be the code written in this exercise, and similarly the code you wrote in database_setup.py

Using SQLAlchemy perform the following queries on your database:

1. Query all of the puppies and return the results in ascending alphabetical order

2. Query all of the puppies that are less than 6 months old organized by the youngest first

3. Query all puppies by ascending weight

4. Query all puppies grouped by the shelter in which they are staying

Search SQLAlchemy Documentation to find the methods that can help implement these queries. http://docs.sqlalchemy.org/

使用操作
1. cd db_demo2

2. virtualenv db02-env

3. source db02-env/bin/activate

4. python db_setup.py

5. python puppypopulator.py

6. python puppy_query.py
