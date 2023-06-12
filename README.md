# lolapp
Integracion continua

# Levantar contenedores
Se ubica en la carpeta raiz y se ejecuta el comando:

    $ docker-compose up -d

# Acceder al contenedor de la aplicación
    $ docker exec -it name-container sh 

# Instalar modulos laravel
    
    $ docker exec -it name-container sh
    $ composer update

# Agregar llave laravel

    $ docker exec -it name-container sh
    $ php artisan key:generate

# Ejecutar migracion
    $ docker exec -it name-container sh
    $ php artisan migrate
