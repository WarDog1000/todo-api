Website [Spring Boot](https://start.spring.io/)

- Varibales de entorno
  * [Maven](https://maven.apache.org/download.cgi)

Nuevo
```
nombre: MAVEN_HOME
ruta: C:\maven
```

path => Editar...

```
%MAVEN_HOME%\bin
```
- Varibales de entorno
  * [Java JDK](https://www.oracle.com/ar/java/technologies/downloads/)

Nuevo
```
nombre: JAVA_HOME
ruta: C:\java\jdk-20
```

path => Editar...

```
%JAVA_HOME%\bin
```

Download [IntelliJ IDEA](https://www.jetbrains.com/idea/download/#section=windows)

### kill server process
 ```
 netstat -ano | findstr LISTENING | findstr 8080
 ```
```
taskkill -PID "process" -f
```