# Apache Web Server Commands for my project

## Installation

sudo yum install httpd -y 

## Start Apache

sudo systemctl start httpd

## Enable Apache

sudo systemctl enable httpd

---------------------------------------

## to create a new index.html by removing default files:

cd /var/www/html

# remove default files:
sudo rm -rf * 

# Create your page:
sudo nano index.html

# content for the page:
<h1>Welcome to My AWS EC2 Project</h1>
<p>This Website is hosted using Apache on EC2</p>
