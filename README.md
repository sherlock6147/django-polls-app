# Polls App
A project for collecting polls.

## Getting Started

1. Clone the project in the desired directory
```
git clone https://github.com/sherlock6147/django-polls-app.git
```
2. Create a **virtual environment**
   - If not installed install using
  ```
  sudo apt install virtualenv
  ```
   - Create the environment using `virtualenv env`
3. Activate the virtual environment
   ```
   source env/bin/activate
   ```
4. Install the requirements
    ```
    cd django-polls-app
    pip install -r requirements.txt
    ```
5. Run the migrations
   first go to mysite folder using 'cd mysite/'
   ```
   python manage.py makemigrations
   python manage.py migrations
   ```
6. Run the development server
   ```
   python manage.py runserver 
   ```

7. [Visit website](http://localhost/8000)