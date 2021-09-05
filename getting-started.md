# Getting Started

### Install

* Clone `git clone https://github.com/WordPress-Studio/wp-twig-public.git`
* Install docker if not installed https://www.docker.com/products/docker-desktop
* Run Docker compose `docker-compose up --build`
* Enter in docker image  `docker exec -it wp-twig-public_wp-dev_1 /bin/bash`
* Install Latest WordPress `cd /var/www/html && wp core download --allow-root`
* Now you can access http://localhost
* Install WordPress. You can find DB details in docker-compose.yml file

{% hint style="info" %}
Db Details:



|  Wp Config variables  | Value |
| :--- | :--- |
| MYSQL\_USER |  testuser |
| MYSQL\_PASSWORD | testpassword |
| MYSQL\_DATABASE | testdb |
| Db HOST | db |
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=QO0LJmh3pVw" %}



