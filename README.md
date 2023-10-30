# dockerLaravelWindows
Entorno Docker para Laravel en Windows - compartiendo Volumes

1. Hacer un git clone del repositorio actual de LARAVEL:
git clone https://github.com/laravel/laravel.git laravel_app01

2. Hacer un docker run de composer para que cree el VENDOR de nuestro laravel:
docker run --rm -v e:/laravel/laravel_app01:/app composer install

3. Copiar el fichero .env de config a laravel_app01

4. Ejecutar docker-compose up -d
