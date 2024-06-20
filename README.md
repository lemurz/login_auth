"# login_auth" 

first project made using the python framework django. here, you can register as a user and login to the system using the registered information.
to run, first create a new directory and paste contents into that directory. create a virtual environment using cmd in the new directory and install django on the virtual environment. then use 'python manage.py runserver' to create a server. run the server. the first page you will be directed to is the homepage.


relevant URLs,

'/index', the homepage
'/register'
'/my-login'
'/dashboard', accessible only to registered users

if you are a registered user and have logged in, you will be redirected to the dashboard.

if you are not a registered user, '/dashboard' will lead you to the login page.

to check authenticity of users created, you can create a superuser and check the database of users using 'python manage.py createsuperuser'
