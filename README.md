instalacion 

sudo apt install git php php-mbstring php-xml php-bcmath php-curl php-mysql php-cli zip unzip php-intl php-gd php-zip



curl -sS https://getcomposer.org/installer -o /tmp/composer-setup.php

sudo php /tmp/composer-setup.php --install-dir=/usr/local/bin --filename=composer
sudo apt install mysql-server
CREATE USER 'filamentphp'@'localhost' IDENTIFIED BY 'M05tSecur3Pas5';
GRANT ALL PRIVILEGES ON *.* TO 'filamentphp'@'localhost' WITH GRANT OPTION;
FLUSH PRIVILEGES;
exit;
 
 intranet utilizando Laravel, diseñado para ser altamente adaptable a diversas necesidades. Este sistema puede ser personalizado para funciones como administración general, gestión de inventario para pequeños negocios, o cualquier otra aplicación específica que requiera un control interno eficiente. La plataforma está equipada con una interfaz flexible, que permite la integración de módulos y características según los requerimientos del usuario. Utilizando las librerías de Filament, el panel ofrece una experiencia de usuario intuitiva y un conjunto de herramientas robustas para la gestión de datos y procesos internos, facilitando la administración y personalización para cumplir con diferentes objetivos empresariales.
