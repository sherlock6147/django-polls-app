# Polls App
A project for collecting polls.

## Getting Started

1. Clone the project in the desired directory
```
git clone https://github.com/sherlock6147/django-polls-app.git
```

2. Change to mysite directory 
   ```
   cd mysite/
   ```

3. If virtualenv is not installed, install using
  ```
  sudo apt install virtualenv
  ```
4. Create the environment using 
   ```
   virtualenv env
   ```

5. Activate the virtual environment
   ```
   source env/bin/activate
   ```

6. Install the requirements
    ```
    pip install -r requirements.txt
    ```
7.  Run the migrations
   ```
   python manage.py makemigrations
   python manage.py migrations
   ```
8. Run the development server
   ```
   python manage.py runserver 
   ```

9. [Visit website](http://localhost/8000/polls)