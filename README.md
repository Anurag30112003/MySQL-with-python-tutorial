# Requirements
    Python 3.6+
    MySql

## Module Requirements
    mysql-connector-python
    dotenv (optional)

# Installation

## Creating a virtual environment
    $ python3 -m venv venv (Linux/Mac)
    $ source venv/bin/activate

### Or
    pip install virtualenv
    virtualenv venv
    source venv/bin/activate (Linux/Mac)
    venv\Scripts\activate (Windows)

## Installing dependencies
    pip install mysql-connector-python
    pip install dotenv (optional)


## Testing
    import mysql.connector
    Run this file to test the installation and run this file
    
# Creating connection to SQL Server.
    import mysql.connector
    mydb = mysql.connector.connect(
        host="localhost",
        user="root",
        password=""
    )
    print(mydb)

    If this runs without errors, the connection was successful. 