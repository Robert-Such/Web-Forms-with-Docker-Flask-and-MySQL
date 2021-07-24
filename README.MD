# Web Forms with Flask, Docker, PyCharm, and MySQL
This project is to create HTML forms which are capable of creating, updating, and deleting records.  Docker Compose is being utilized to setup a python flask app and a mysql server which will load data from
the db/init.sql file during the first start up of the database.  The flask framework is serving jinja template files and sending http POST
requests to create, update, and delete records.

## Screenshot of Table View in PyCharm:
![pycharm table view](screenshots/Tables_PyCharm.png)

## Screenshot of browser displaying homepage with new data:
![homepage displaying new data](screenshots/Homepage_NewData.png)

## Screenshot of browser displaying view of individual data record:
![homepage displaying new data](screenshots/view_record.png)