Aplicación Monolítica

-	VPS (4GB - 2vCPU): Un servidor virtual privado con 4GB de RAM y 2 CPU virtuales. Se utiliza para alojar aplicaciones y servicios de menor carga.
-	Docker: Plataforma de contenedores que permite a los desarrolladores empaquetar aplicaciones y sus dependencias en un contenedor que se puede ejecutar en cualquier entorno.
-	Docker-Compose: Herramienta para definir y ejecutar aplicaciones Docker de múltiples contenedores.
-	PostgreSQL: Sistema de gestión de bases de datos relacional y objeto-orientado.
-	Contenedor - Web Server: Servidor web empaquetado en un contenedor Docker.
-	Contenedor - Worker Server: Servidor de procesamiento de tareas empaquetado en un contenedor Docker.
-	Nginx HTTPS: Servidor web y proxy inverso que gestiona solicitudes HTTPS.
-	Servicio de Notificaciones de Email: Servicio dedicado a enviar notificaciones por correo electrónico.
-	Servicio de Almacenamiento: Servicio dedicado a almacenar y gestionar archivos y datos.
-	CI/CD: Integración continua y entrega continua. Un conjunto de prácticas para automatizar la integración y entrega de código.
-	Nginx WEB Server: Servidor web Nginx que gestiona solicitudes HTTP de los clientes.
-	Ruby on Rails: Framework de aplicaciones web escrito en Ruby.
-	MVC (Model-View-Controller): Patrón de diseño de software para implementar interfaces de usuario dividiendo la lógica de la aplicación en tres partes interconectadas.
-	Ruby: Lenguaje de programación dinámico y de propósito general.
-	Open Source: Software de código abierto que puede ser modificado y distribuido por cualquier persona.


Aplicación de Microservicios

-	Kubernetes: Plataforma de orquestación de contenedores que automatiza la implementación, el escalado y las operaciones de contenedores de aplicaciones.
-	Autenticación: Microservicio encargado de gestionar la autenticación de usuarios.
-	Reportería: Microservicio encargado de generar y gestionar reportes.
-	Notificaciones: Microservicio encargado de enviar notificaciones a los usuarios.
-	Encuentas: Microservicio encargado de gestionar encuestas y recopilación de datos.
-	Websocket Server: Servidor que permite la comunicación en tiempo real entre el cliente y el servidor utilizando el protocolo WebSocket.
-	TODO: Microservicio encargado de gestionar tareas y listas de tareas.
-	DB (Base de Datos): Sistema de almacenamiento de datos utilizado por los microservicios.
-	API Gateway: Puerta de enlace que gestiona y direcciona las solicitudes de los clientes a los microservicios adecuados.
-	Node 1, Node 2, Node 3, Node 4: Servidores físicos o virtuales que forman parte del clúster de Kubernetes.
-	gRPC: Framework de llamada a procedimiento remoto (RPC) de alto rendimiento que puede ejecutarse en cualquier entorno.
-	HTTP: Protocolo de transferencia de hipertexto utilizado para la comunicación entre clientes web y servidores.
-	Cliente Web: Usuario final que interactúa con la aplicación a través de un navegador web.

Diagramas

Diagrama de la Aplicación Monolítica

-   Presenta una arquitectura centralizada donde todos los componentes están contenidos dentro de un solo despliegue.
-   Usa Docker-Compose para orquestar los diferentes servicios dentro del mismo VPS.

Diagrama de la Aplicación de Microservicios

-   Presenta una arquitectura distribuida donde cada funcionalidad está contenida en un microservicio separado.
-   Usa Kubernetes para orquestar y gestionar los diferentes microservicios distribuidos en múltiples nodos.
