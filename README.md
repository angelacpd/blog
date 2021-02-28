# Blog

This project creates a blog using Django's Signup, Login, and Logout features. 
It uses Django's generic views to Create, Read, Update, and Delete posts.
It also uses basic CSS.

#### Environment variables
Create a .env file and add:
- SECRET_KEY

#### Deploy on Heroku

Log in Heroku
> heroku login

Create new container for app
> heroku create angelacpd-blog

Configure git to push to Heroku
> heroku git:remote -a angelacpd-blog

Push changes to Heroku
> git push heroku master

Apply migrations
> heroku run python manage.py migrate

Add web process
> heroku ps:scale web=1

Close web process
> heroku ps:scale web=0

#### Signup
https://angelacpd-blog.herokuapp.com/accounts/signup
