PSP-MSS-CLIENT-SERVER
Este proyecto es una aplicación cliente-servidor desarrollada en Java que utiliza sockets para la comunicación entre el cliente y el servidor. Forma parte de las prácticas de la asignatura de Programación de Servicios y Procesos (PSP) y tiene como objetivo ilustrar la implementación de una arquitectura de red básica en Java.

Estructura del Proyecto
El repositorio contiene las siguientes carpetas y archivos:

T2-CLIENTE: Contiene el código fuente del cliente que se conecta al servidor para enviar y recibir mensajes.

T2-SERVIDORM: Contiene el código fuente del servidor que gestiona las conexiones entrantes y responde a las solicitudes del cliente.

Funcionalidades
Comunicación Cliente-Servidor: Establece una conexión entre el cliente y el servidor utilizando sockets.

Intercambio de Mensajes: Permite al cliente enviar mensajes al servidor y recibir respuestas.

Gestión de Conexiones: El servidor puede manejar múltiples conexiones de clientes de manera concurrente.

Requisitos
Java Development Kit (JDK) 8 o superior.

Un entorno de desarrollo como Eclipse o IntelliJ IDEA.

Cómo Ejecutar
Clona este repositorio en tu máquina local:

bash
Copiar
Editar
git clone https://github.com/Ivannunezrodriguez/PSP-MSS-CLIENT-SERVER.git
Abre el proyecto en tu entorno de desarrollo preferido.

Compila y ejecuta primero el servidor ubicado en T2-SERVIDORM.

Luego, compila y ejecuta el cliente ubicado en T2-CLIENTE.

Utiliza el cliente para enviar mensajes al servidor y observar las respuestas.

Autor
Iván Núñez Rodríguez - Ivannunezrodriguez
