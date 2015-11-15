***
A basic heroku app for deploying <a href="https://github.com/ashumeow/functiondelay">function delays</a>.
***
``` sh
Steps for deploying the app:

$heroku login
$git clone https://github.com/ashumeow/heroku-load.git
$cd heroku-load
$heroku create
$git push heroku master
$heroku ps:scale web=1
$heroku open
```
```
Requirements:

JDK (Java Development Toolkit)
Java IDE: JetBrains 14.1.5
Gradle
Maven
Git 2.6.3
Heroku Toolbelt 3.30.3
```