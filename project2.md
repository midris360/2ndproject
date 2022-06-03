# Documentation of Project 2

## *LEMP Stack Implementation*

1. *Installed Nginx web server*
2. *Check if its running and active*
![Nginx install](./images/nginx%20install.png)
![Active running](./images/nginx%20active%20running.png)

----------
## Installed MYSQL

1. *MySQL installation*
2. *Logged into console*
![Install & Logged](./images/installed%20and%20logged%20mysql.png)
- After creating password validation, I installed php fastCGI process manager and mysql fo rphp
![php-fpm & php-mysql](./images/installed%20php-fpm%20and%20php-mysql.png)
3. Configured Nginx for php processor use
4. created a new blank file (sites-available) using nano
![config Nginx directory](./images/blank%20file%20Own%20config%20Nginx%20dir.png)
5. Created html file in web root to test
![Hello LEMP](./images/web%20root%20projectlemp%20browser.png)
6. Created database in mysql, plus a user, then added a todo_list within that database
![Todo list database](./images/creating%20database.png)
![Hello LEMP](./images/added%20to%20database.png)
7. Display todo list content n browser using todolist script.
![Todo list (bad gateway)](./images/web%20root%20projectlemp%20browser.png)