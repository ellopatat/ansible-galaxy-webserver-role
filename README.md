#webserver role <br>
install apache and php.<br>
#group_vars<br>
web_packages:
  - apache2
  - php
  - libapache2-mod-php
  - php-mysql
