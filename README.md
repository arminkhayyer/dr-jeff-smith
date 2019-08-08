# Web APP

1. Clone project code from git repository
2. Make sure that the insy6500 database exists on your localhost. 
The sql file also is in the project directory, just in case if you do not have the database, and want to create it. 

3. install reqirements using the following code snippet in terminal 

    ```python
    pip install -r requirements.txt
    ```

4. go to the file directory of the project. 
5. run the following snippet of code

    ```python
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
    ```
    
6. The WebApp is ready to use through localhost:8000. 