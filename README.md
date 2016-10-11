
# Description

Esta es una imagen copia de (https://github.com/mageinferno/docker-magento2-nginx) para mantener una versión en español.
# ¿Que hay dentro de esta imagen?

Esta imagen instala lo siguiente:

- `nginx`

# Variables

Las siguientes variables de entorno son usadas por las configuraciones de Nginx:

- `PHP_HOST`: (default: `phpfpm`) Es el hostname del contenedor de PHPof the PHP.
- `PHP_PORT`: (default: `9000`) El puerto del contenedor de PHP.
- `APP_MAGE_MODE`: (default: `default`) Asigna el MAGE_MODE apropiado.

# Docker Compose

Nota: basado en el repositorio https://github.com/mageinferno/docker-magento2-nginx