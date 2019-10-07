# Archivos docker-compose. #

- ActiveMQ v5.15.9
- MySql v5.7

- Nesus essential v8.6
para solicitar codigo de activacion:
https://es-la.tenable.com/products/nessus/nessus-essentials
Nota: Para no tener que compilar pluggins y solicitar codigo de activacion, el contenedor solo debe ser detenido.

docker-compose build  # para crear la imagen.
docker-compose up -d  # para levantar el contenedor.
docker-compose stop nessus # Para detener el contenedor.
docker-compose start nessus # Para Iniciar el contenedor.
docker-compose down # Eliminar el contenedor completamente, esto hara que la proxima vez que se cree el contenedor, se debe ingresar el codigo de activacion nuevamente.

- Redis 5.0.5


- SonarQube


- SQL Server 2017
url: https://docs.microsoft.com/en-us/sql/linux/sql-server-linux-configure-docker?view=sql-server-2017
