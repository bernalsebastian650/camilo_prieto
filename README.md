# DobleA
Sistema de Control de Inventarios.

## Descripción 
Este repositorio es un desarrollo bajo la estructura estructura MVC.

### Instalación
1. Repositorio Base [https://github.com/EjemplosADSI/WebER.git](https://github.com/EjemplosADSI/WebER.git).
2. Verificar lo siguientes requisitos en Laragon:
    1. Php 8 o Superior.
    2. Apache 2.4.43 o Superior.
3. Una vez clonado el repositorio Ejecutar composer install
4. Instalar el Script de la base de datos en phpmyadmin.
5. Ejecutar npm install && npm run build
6. composer dump-autoload
7. Herramientas de Buenas Practicas:
   1. composer global require friendsofphp/php-cs-fixer --with-all-dependencies
   2. composer global require "squizlabs/php_codesniffer=*"
