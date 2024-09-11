# demochoreography
Para ejecutar el demo se debe realizar los siguientes pasos
1. Compilar los proyectos, ubicarse en la carpeta de cada proyecto y ejecutar el comando 
    <p>mvn package</p>
2. Crear las imagenes de cada proyecto, igualmente se ubica en el directroio de cada proyecto y ejectamos el comando 
    <p>docker build -t check .</p>
    <p>docker build -t ingestion .</p>
    <p>docker build -t make . </p>
    <p>docker build -t notify . </p>
    <p>docker build -t rabbitmq </p>

3. nos ubicamos en el directorio raíz de la solución
    <p>docker compose up</p>

Para disparar los mensajes a la cola ingresar a este link, cambiando la ip que corresponda
<p><a>"http://192.168.1.60:8001/"</a></p>

Para monitorear RabbitMQ ingresar al sigiuente link, igualmente cambiando la ip que corresponda
<p><a>http://192.168.1.60:15672/ </a></p>