# Practica-Sistemas-de-control-de-versiones David Espinós
# Documentación del Proyecto

## Introducción

Este repositorio es parte de un proyecto desarrollado por la empresa David Espinós. Aquí encontrarás información sobre el flujo de trabajo de Git y la metodología utilizada en nuestros desarrollos, así como la configuración recomendada y cómo utilizar GitHub para gestionar el proyecto. En este proyecto más concretamente un cliente nos ha encargado una web la cual se encarga de realizar formaciones de javascript aplicado a interacciones con elementos HTML

## Metodología de Desarrollo

En este proyecto seguimos el flujo de trabajo de **GitFlow** para nuestros desarrollos. Este flujo de trabajo es elegido por su robustez y escalabilidad. Incluye al menos dos ramas principales:

Desarrollo: Esta rama es donde se integran las características y correcciones de errores antes de ser liberadas.
Producción: Esta rama refleja el estado en producción y es más estable.

## Configuración de Git

### Instalación de Git

Asegúrate de tener Git instalado en tu sistema. Si no lo tienes, puedes descargarlo desde [el sitio web oficial de Git](https://git-scm.com/).

### Configuración de Nombre y Correo Electrónico

Antes de comenzar, configura tu nombre y dirección de correo electrónico en Git. Esto se utiliza en tus registros de confirmación:

bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"

## Clientes de Git
Puedes utilizar varios clientes Git para gestionar tus repositorios. Algunas opciones populares incluyen:

GitHub Desktop: Una aplicación de escritorio que proporciona una interfaz gráfica para trabajar con repositorios de GitHub. Puedes descargarlo desde GitHub Desktop.

Sourcetree: Otra aplicación de escritorio que admite la gestión de repositorios Git. Puedes descargarlo desde Sourcetree.

## Uso de GitHub

### Issues

Gestionamos las tareas y problemas utilizando Issues. Los Issues son útiles para realizar un seguimiento de lo que necesita ser hecho y para la comunicación con el equipo.

### Pull Requests

Para proponer cambios al proyecto, creamos Pull Requests. Los Pull Requests son revisados por otros miembros del equipo antes de fusionar los cambios en la rama de desarrollo o producción.

### Branches

Rama de Desarrollo: Se utilizan para desarrollar nuevas características o correcciones de errores. Cada función o corrección de error se realiza en su propia rama.
Rama de Producción: La rama principal de producción que refleja el estado actual en producción.

### Versiones

Gestionamos las versiones de nuestro software utilizando etiquetas (tags) en Git. Las etiquetas se aplican a las confirmaciones para marcar versiones específicas.

### Contribuciones

Apreciamos las contribuciones de la comunidad. Si deseas contribuir, por favor sigue nuestro flujo de trabajo de Git y envía Pull Requests.

# Licencia
Este proyecto está bajo la licencia MIT License. Consulta el archivo LICENSE para más detalles.

