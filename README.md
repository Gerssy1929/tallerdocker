# tallerdocker
Taller Docker Cloud FastApi

Construir imagen desde la raiz del proyecto:
docker build -t <imagen> .

![imagen](https://github.com/user-attachments/assets/34a9cf22-4e33-4bb7-8772-35fce008e4ae)

En este caso le nombramos geardila (Usuario institucional)


Ejecutar imagen y lanzar contenedor:
docker run -d --name <contenedor> -p 80:80 <imagen>

![imagen](https://github.com/user-attachments/assets/d5bcc3ad-1e81-48de-8cac-084a71685217)

En este caso nombramos al contenedor fastapi y podemos ver que esta en ejecución

Por último, revisamos el puerto 80 donde se está ejecutando el contenedor

![imagen](https://github.com/user-attachments/assets/1852ad33-24e8-43ab-be3b-83823c2a325d)

La aplicación funciona exitosamente!!
