# Acerca de
Es un docker compose que configura un Django DRF y Vue js

# Pasos por primera vez
Iniciar Django y la DB en background si aun no estan corriendo:
  - `docker-compose up -d`

Crear tablas de Django en la DB:
  - `docker-compose run drf python manage.py migrate`

Crear superusuario:
  - `docker-compose run drf python manage.py createsuperuser`

# Programar dia a dia
Iniciar las instancias de DRF y el frontend con:
  - `docker-compose up`
