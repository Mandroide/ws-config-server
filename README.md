# Spring Cloud Config Server

Se encarga de correr las configuraciones de [ws-config-data](https://github.com/Mandroide/ws-config-data)
para los servicios a ejecutar.

Se deben crear las siguientes variables de entorno a nivel de usuario en el sistema operativo.
Si usas Windows, busca "Edit environment variables for your account" y crea las siguientes variables de entorno:

* **GIT_URI**: Apunta al [ws-config-data](https://github.com/Mandroide/ws-config-data)
con las configuraciones (o propiedades) requeridas por tu servicio para funcionar.
* **GIT_USER**: Representa tu usuario para acceder a [ws-config-data](https://github.com/Mandroide/ws-config-data)
* **GIT_PASSWORD**: Representa la contraseña correspondiente a *GIT_USER*.
* **GIT_BRANCH**: Apunta a la rama de [ws-config-data](https://github.com/Mandroide/ws-config-data)
con la que deseas trabajar.