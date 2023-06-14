This is a set of instructions for running the NorthWind CRUD API on your computer. 

1. Make sure Python is installed on your PC. You can check by typing "python" in your terminal. If you don't have python, download it from [here](https://www.python.org

2. Install the necessary dependencies by running the following command: "pip install flask flask-mysqldb". This will install Flask and Flask-MySQLdb, which are modules used by the API script.

3. Configure your MySQL Server to match the database configuration in the API script (MYSQL_HOST, MYSQL_USER, MYSQL_PASSWORD, MYSQL_DB). This ensures that you have access to interact with the table.

4. Run the client.bat file, which will automatically run the API script for you. If it cannot connect to the server, you can manually run the finalapi.py file.

5. When you're done using the client script, make sure to stop the API script to free up your computer's memory.

Enjoy using the NorthWind CRUD API!