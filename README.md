
# Club Registration Form
This is an application for a Club Registration Form. This application will be used by a club at a club fair. 
Students who stop by the club's table can input their email address and other information into the application. 
The application then store these information for the club to use. 

This was inpisred by the react comment box example from [the React tutorial](http://facebook.github.io/react/docs/tutorial.html).
The technologies we used are html, css, javascript with React framework on the front end, and python with flask, postgres on the backend.

## To use

### Python

```sh
pytest fabfile.py # Build and test
python server.py
```
If the data needs to be stored in PostgreSQL database, another package is required
```sh
sudo apt-get install python-psycopg2
```
And visit <http://localhost:5000/>. Try opening multiple tabs!

## Build and test
See "fabfile.py" and "test.py"
