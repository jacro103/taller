# Tarea Microservicios

---

## Johan Sebastian Garcia Martinez
## Jose Alejandro Correa Rodriguez
---

### Requerimientos para la implementación de la tarea

- Maven
- Java
- Git
- Amazon Web Services
- Quarkus
--- 

### Funcionalidades

Serviicio API Rest desplegado en Aws Lambda, con seguridad JWT que contiene un login de usuarios y las publicaciones que este realiza de manera organizada verticalmente por tiempo de publicación.

---

## Preparación

### Obtener el código del proyecto
Debemos clonar el repositorio a la máquina local con el siguiente comando:
```bash
git clone https://github.com/jacro103/taller.git
```

### Ubicar el proyecto
Nos ubicamos en la carpeta /taller
```bash
cd taller
```

### Compilar el proyecto
Ahora compilamos el proyecto para que se generen los archivos de clase correspondientes con el siguiente comando:
```bash
mvn clean install
```


### Ejecución en Local
Para realizar la ejecución de los servicios desde la linea de comandos debemos escribir el siguiente comando, para utilizar el servicio de Quarkus
```bash
mvn quearkus:dev
```
## Imagen de ejecucion del proyecto
![](/src/resources/quarkus.png)


## Uso
Ahora para poder hacer uso de la aplicación, es necesario dirigirnos a la siguiente dirección desde un navegador.
```bash
http://localhost:8080/twitter/login
```

![](/src/resources/login.png)

De este modo ya queda almacenado y relacionado el usuario que esta realizando las publicaciones, dese este punto se abre la ventana de servicio de Twitter, la cual nos permite realizar publicaciones y se irán almacenando y publicando de manera organizada

![](/src/resources/pantallainicial.png)

A partir de este punto ya se pueden realizar publicaciones

![](/src/resources/post.png)

Como podemos observar, el usuario "Sebastian" acaba de realizar una publicación con el mensaje "Hola Mundo!" y aparece justo debajo como una lista ordenada


## Lambda

## Ejecución en AWS S3

## Video

## Autor

Johan Sebastian Garcia Martinez

Jose Alejandro Correa Rodriguez

