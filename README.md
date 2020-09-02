# PHP MVC
PHP MVC is a custom developed PHP MVC made by Neo.

# PHP MVC detail
Default url, show the logs data:
http://localhost/PHPMVC/index.php?l=web&c=index&m=index

Log url, insert log data:
http://localhost/PHPMVC/index.php?l=web&c=index&m=log

Parameter "l" is the folder of controllers
Parameter "c" is the controller file name
Parameter "m" is the controller method 

For example, location: "\app\web\controllers\IndexController.php", controller: "IndexController.php", method: "index()", the url is:
http://localhost/PHPMVC/index.php?l=web&c=index&m=index