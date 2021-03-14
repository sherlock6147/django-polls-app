# Polls App
A project for collecting polls.

## Getting Started

1. Clone the project in the desired directory
```
git clone https://github.com/sherlock6147/django-polls-app.git
```

2. Change to mysite directory `cd mysite/`

3. Create a **virtual environment**
  If not installed install using
  ```
  sudo apt install virtualenv
  ```
  Create the environment using `virtualenv env`

4. Activate the virtual environment
   ```
   source env/bin/activate
   ```

5. Install the requirements
    ```
    pip install -r requirements.txt
    ```
6. Run the migrations
   ```
   python manage.py makemigrations
   python manage.py migrations
   ```
7. Run the development server
   ```
   python manage.py runserver 
   ```

8. [Visit website](http://localhost/8000/polls)