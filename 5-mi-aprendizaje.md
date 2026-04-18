# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

Consultar: Cómo se gestionan datos confidenciales con los secretos de Docker (Docker Secrets).

El principal logros encontrados, tanto en la práctica uno como en la práctica dos, son el conocer a detalle el funcionamiento de docker, que aunque siga siendo comandos básicos y tareas relativamente sencillas, abre la puerta a muchas posiblidades, siendo que docker es algo muy usado a nivel profesional.
Uno de los puntos más interesantes de forma personal, fue el mapeo de puertos y las redes internas en docker.

Durante las prácticas solían existir pequeños errores en cuanto a configuraciones que se solucionaron con mera investigación.

En cuanto a Docker Secrets, sirve para gestionar datos confidenciales, como lo pueden ser usuarios y contraseñas, certificados TSL, SSH keys, entre otros tipo de datos sensibles y no sensibles, permitiendo unicamente a los contenedores que los necesitan y tengan acceso explicito acceder a ellos, unicamente mientras las tareas están en ejecución, todo viajando por un tunel cifrado.
Cabe recalcar que estos se usan unicamente en un Docker Warm.
En Windows, esta información se guarda en una carpeta específica pero se encuentra con estricto control de acceso y se encuentra en este lugar únicamente durante la ejecución de la tarea, luego se borra, de forma usual se mantiene en una base de datos distribuida cifrada.