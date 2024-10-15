# Practica servidor web
## 1. Titulo
Implementación de un servidor web utilizando Docker y Nginx.
## 2. Tiempo de duración
Me tomé aproximadamente 30 minutos para desarrollar la práctica.

## 3. Fundamentos:

Es fundamental conocer qué es Docker y cómo funciona. Docker es una plataforma que permite crear, implementar y ejecutar aplicaciones en contenedores. Un contenedor es un entorno aislado que empaqueta todo lo necesario para ejecutar una aplicación, incluyendo su código, bibliotecas y dependencias. utilicé Nginx, un servidor web de alto rendimiento, para servir archivos HTML. Aprendí a ejecutar un contenedor de Nginx y a mapear puertos entre mi máquina local y el contenedor. El uso de imágenes de Docker simplifica el proceso de despliegue de aplicaciones, ya que puedo utilizar imágenes preconfiguradas desde Docker Hub.
Utilicé esta funcionalidad para servir un archivo index.html que creé específicamente para la práctica.




## 4. Conocimientos previos.
   
Para realizar esta práctica, el estudiante necesita tener claros los siguientes temas:

Uso de comandos básicos de Docker.
Manejo de un navegador web para acceder al servidor.
Entendimiento de cómo funcionan los contenedores.
- Comandos lux.
- Manejo de navegador
- etc, etc

## 5. Objetivos a alcanzar
   
- Implementar contenedores con Nginx para servir contenido web.
- Manipular archivos de configuración de Nginx a través de volúmenes en Docker.

  
## 6. Equipo necesario:
  
- Computador con sistema operativo Windows/Linux/Mac ...
- Cuenta en docker play....
- Docker v xxxx
- etc.

## 7. Material de apoyo.
   
- Documentacion de docker.
- Guia de asignatura.
- Cheat sheet linux
- etc
  
## 8. Procedimiento

(Enumerar el paso a paso, las imágenes deben tener títulos.)
Paso 1: xxxxx
Paso 2: xxxxx

Creé un archivo index.html con el contenido deseado.

Ejecuté el siguiente comando para crear y ejecutar el contenedor de Nginx:

Figura 1-1. Diagrama de contenedores.
Las figuras un ancho máximo de 800px

docker run --name BryanBF -p 8083:80 -d -v $(pwd)/index.html:/usr/share/nginx/html/index.html nginx


## 9. Resultados esperados:
    
Descripcion de los resultados, capturas de pantallas del resultado final de la practica

## 10. Bibliografía
    
- Apellido,..... En apa