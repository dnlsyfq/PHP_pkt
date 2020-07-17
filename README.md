
$argv is an array

### using shell

* example.php
```
$name = $argv[1];
echo "Hello ". $name;
```


```
$ php  example.php world // return 'Hello World'
```
---

### using browser 

* example.php
```
$name = $_GET['companyName'];
echo "Hello ". $name;
```
```
php -S localhost:8085
```
```
http://localhost:8085/hello.php?companyName=Packt
```
