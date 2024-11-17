 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
  ## AIM
       To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
    Explain about the Experiment.

## ALGORITHM
 ### Steps 1: 
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
 ### Steps 2: 
 Connect to the instance using SSH and install a web server like Apache
 ### Steps 3:
 Create a simple HTML file in the server's default directory with basic content for testing.
 ### Steps 4:
 Access the instance's public IP in a browser to verify the HTML page is displayed.
 
 
## COMMANDS
### To install httpd:
```
yum install httpd -y
```
### To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
### Create a simple HTML page :
```
cd /var/www/html
sudo nano nandha.php
```

```php
<!Doctype html>
<html>
<body>
<h1>Hello Friends</h1>
<?php
echo "Hello World";
?>
</body>
</html>



```

## OUTPUT

### REG NUMBER:212222110024
### NAME:MATHESWARAN K

### Terminal:
![Screenshot 2024-11-17 133459](https://github.com/user-attachments/assets/9a352732-efee-49ce-a36d-2bcfcd9108e6)


### Website:
![Screenshot 2024-11-17 133529](https://github.com/user-attachments/assets/f956f30f-fc46-4287-874e-c08140c86481)


## RESULT
 Thus the web application for test environment has successfully been created and executed.

  
