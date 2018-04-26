# udacity-linuxServer-project
Final project for linux server configuration section
1. IP Address: 54.189.253.183 | SSH port: 2200
2. URL of project: http://ec2-54-189-253-183.us-west-2.compute.amazonaws.com
3. A summary of software you installed and configuration changes made.
* For project setup:
```
python-pip
postgresql
apache2
git
virtualenv
```
* For project execute:
```
flask
httplib2
oauth2client
sqlalchemy
psycopg2
```
* Config changes made:
```
Create grader user, add grader to sudo group
Create ssh keys for grader and github
Add firewall rules to allow traffic on ports 80, 2200, and 123
Create virtualenv to run python program within
Create database using psql
Update Google OAuth authorization to allow requests from Amazon server
```
4. A list of any third-party resources you made use of to complete this project.
* Udacity forums
* [SQLAlchemy docs](http://docs.sqlalchemy.org/en/latest/core/engines.html#postgresql)
