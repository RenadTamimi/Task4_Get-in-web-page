## start 
In this task we create a web page by using php language and use a GET method to give an integer value for the sensor
And create Data Base.
Also create a web page to store the value of a sensor in a table of DB
```
php -S 127.0.0.1:8080
```
## request


for get request 

```
curl  http://localhost:8080/index.php/numbers/list\?limit\=20  
```

for post request 

```
curl --location --request POST 'http://localhost:8080/index.php/numbers/post' \
--form 'number="150"'
```
