# demochoreography
Para ejecutar el demo se debe realizar los siguientes pasos
1. Compilar los proyectos, ubicarse en la carpeta de cada proyecto y ejecutar el comando 
    mvn package
2. Crear las imagenes de cada proyecto, igualmente se ubica en el directroio de cada proyecto y ejectamos el comando 
    docker build -t check .
    docker build -t ingestion .
    docker build -t make .
    docker build -t notify .
    docker build -t rabbitmq

3. nos ubicamos en el directorio raíz de la solución
    docker compose up

Para disparar los mensajes a la cola ingresar a este link, cambiando la ip que corresponda
http://192.168.1.60:8001/

Para monitorear RabbitMQ ingresar al sigiuente link, igualmente cambiando la ip que corresponda
http://192.168.1.60:15672/ 