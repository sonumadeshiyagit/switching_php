# switching_php

# Switching to PHP 7.4 to 8.2 and vice versa

Switching to PHP 7.4 to 8.2

sudo update-alternatives --config php

sudo a2dismod php7.4

sudo a2enmod php8.2

sudo service apache2 restart

Switching to PHP 8.2 to 7.4

sudo a2dismod php8.2

sudo a2enmod php7.4

sudo service apache2 restart

Switching to PHP 7.4 to 8.2 and vice versa
