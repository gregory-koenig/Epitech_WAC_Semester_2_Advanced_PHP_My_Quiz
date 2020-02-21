# Epitech_WAC_Semester_2_Advanced_PHP_My_Quiz

PHP_Avance_my_quiz
========================

The PHP Avance my quiz is a Symfony project developed within the framework of Web@academie. The used version here is 3.4.

Requirements
------------

  * PHP 7.1 or higher;
  * and the [usual Symfony application requirements][1].

Installation
------------

Execute this command to install the project:

```bash
$ git clone https://github.com/greg05/PHP_Avance_my_quiz.git
$ cd PHP_Avance_my_quiz/my_quiz
$ composer install
```

Here you will find the parameters for the connection to the database in the terminal:

```bash
...
Some parameters are missing. Please provide them.
database_host (127.0.0.1): 
database_port (null): 
database_name (symfony): quiz
database_user (root): 
database_password (null): 
mailer_transport (smtp): 
mailer_host (127.0.0.1): 
mailer_user (null): 
mailer_password (null): 
secret (ThisTokenIsNotSoSecretChangeIt): 
...
```

Then, try the URL address "[localhost]/PHP_Avance_my_quiz/my_quiz/web/". If it doesn't work, you have to set the rights of the entire directory:

```bash
$ cd PHP_Avance_my_quiz
$ sudo chmod 777 -R *
```

Finally, you have to import the database in phpMyAdmin.

Usage
-----

There's no need to configure anything to run the application. Just execute this
command to run the built-in web server and access the application in your
browser at <http://localhost:8000>:

```bash
$ cd PHP_Avance_my_quiz/my_quiz
$ php bin/console server:run
```

Alternatively, you can [configure a fully-featured web server][2] like Nginx
or Apache to run the application.


[1]: https://symfony.com/doc/3.4/reference/requirements.html
[2]: https://symfony.com/doc/3.4/setup/web_server_configuration.html
