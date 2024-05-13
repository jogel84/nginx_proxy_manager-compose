# Nginx Proxy Manager en Docker

Este docker-compose utiliza las siguientes variables:

|  Parámetro                    |   Función                                                     |
|:------------------------------|:--------------------------------------------------------------|
| NGINX_HOME                    | Ruta donde se guardan los datos dentro del servidor físico    |
| MARIADB_DATABASE_USER         | Usuario para la BD                                            |
| MARIADB_DATABASE_NAME         | Nombre de la BD                                               |
| MARIADB_ROOT_PASSWORD         | Contraseña de usuario root de la BD                           |
| MARIADB_PASSWORD              | Contraseña de la BD                                           |
| CONTAINER_NGINX_VERSION       | Versión de contenedor                                         |
| CONTAINER_MARIADB_VERSION     | Versión de contenedor                                         |


## Usuario y clave por defecto:

<note>Email: admin@example.com</note>

<note>Password: changeme</note>
