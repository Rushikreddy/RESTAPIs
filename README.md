# RESTAPIs

REST APIs are pretty much everywhere. They are the standard method to expose databases to clients and knowing how to develop a REST API is a necessity at all layers of the stack.

Things that require to build our first REST API:-
1.Python
2.Flask
3.Flask-SQLAlchemy
4.Flask-Restful
5.NOSQL or SQlite3
6.Jsonify

Download the dataset and extract in your project folder named 'restapi'.

Now, we create a basic virtual environment for Python3.7 and install the packages after it's activation.

C:\Users\Reddy> virtualenv venv
C:\Users\Reddy> source venv/bin/activate
C:\Users\Reddy> pip install flask flask-jsonpify flask-sqlalchemy flask-restful
C:\Users\Reddy> pip freeze

Let's create the basic "GET" API

REST has got 4 options
GET
PUT
POST
DELETE

We will deal with all the 4 options {GET , PUT , POST, DELETE }

Before the code, connect yourself to database.

Now everything being set up, we begin the code of exposing data and tracks data from database and also add a query operator on Ids where employee's details is searched and fetched by EmployeeID.

It is simple to create a API,Likewise to PUT,POST and DELETE on data too.

