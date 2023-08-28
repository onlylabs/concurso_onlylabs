Concurso patrocinado por Onylabs:

# Guía Práctica: Configurar un servidor web con Nginx usando Docker

![nginx-docker](/resources/nginx-docker.png)

## Introducción
Nginx es un servidor web ligero y de alto rendimiento. Docker, por otro lado, es una plataforma que permite a los desarrolladores crear, ejecutar y compartir aplicaciones en contenedores. Al combinar ambos, podemos levantar un servidor web Nginx de forma rápida y consistente en cualquier entorno que soporte Docker. Esta guía te mostrará cómo hacerlo paso a paso.

## Preparativos Iniciales

### 1. Instalación de Docker
Antes de poder ejecutar cualquier contenedor en Docker, necesitamos tener Docker instalado en nuestra máquina. Puedes encontrar las instrucciones de instalación en el [sitio oficial de Docker](https://docs.docker.com/get-docker/).

### 2. Verificar la instalación
Una vez instalado Docker, puedes verificar que todo esté funcionando correctamente ejecutando el siguiente comando en tu terminal:

## Configuración de Nginx con Docker

### 1. Descargar la imagen oficial de Nginx:
Ejecuta el siguiente comando para descargar la imagen oficial de Nginx:

### 2. Crear y ejecutar un contenedor Nginx:
A continuación, ejecutaremos un contenedor usando la imagen de Nginx que acabamos de descargar:

Con este comando, estamos mapeando el puerto 8080 de nuestra máquina al puerto 80 del contenedor.

### 3. Acceder al servidor web:
Abre tu navegador y visita `http://localhost:8080`. Deberías ver la página de bienvenida de Nginx, lo que indica que tu servidor web está funcionando correctamente.

## Conclusion
¡Felicidades! Ahora tienes un servidor web Nginx ejecutándose en un contenedor Docker. Esto es solo el comienzo, ya que Docker y Nginx ofrecen muchas más características y configuraciones avanzadas que puedes explorar para adaptarlos a tus necesidades.
