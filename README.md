# survivor_backend
Survivor Backend SpringBoot App Configuration

##  Clonar e importar el proyecto

* Crear branch y clonar este repositorio.
* Abrir eclipse (recomiendo utilizar STS) y crear un folder para usarse como workspace.
* Importar proyecto usando: `File -> import -> Maven -> Existing Maven Projects`
* El proyecto empezara a actualizarse automaticamente, si no lo hace: correr en circulos con las manos en el aire gritando compila! compila! o actualizar el proyecto con maven


##  Configurar conexión base de datos 

* Localizar y abrir archivo `application.properties` y configurar las siguientes propiedades segun su instalación de mysql:

```
spring.datasource.url=jdbc:mysql://localhost/survivor?useSSL=false&useUnicode=true&useJDBCCompliantTimezoneShift=true&useLegacyDatetimeCode=false&serverTimezone=America/Mexico_City
spring.datasource.username=root
spring.datasource.password=powerlive7
spring.datasource.driver-class-name=com.mysql.jdbc.Driver
```

##  Probar.

* Correr usando clic derecho sobre la carpeta superior de la aplicacion y hacer `run as -> Spring Boot App`
* Como la aplicacion es una API rest no tiene vista pero debera estar corriendo en `http://localhost:8080/` y servira para alimentar la aplicacion angular asi que ambas deberan estar ejecutandose




