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
