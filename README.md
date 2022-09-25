## Conexion a la base de datos

Configuracion en pom.xml para la conexixion de JAVA

```
  <properties>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    <maven.compiler.source>17</maven.compiler.source>
    <maven.compiler.target>17</maven.compiler.target>
  </properties>

  <dependencies>
    <dependency>
      <groupId>mysql</groupId>
      <artifactId>mysql-connector-java</artifactId>
      <version>8.0.23</version>
    </dependency>
  </dependencies>

```

**DAO**
DAO es un patron de diseño que permite separar la logica de negocio de la logica de acceso a datos.
Sirve para hacer las consultas a la base de datos y poder utilizarlas en el programa principal.

**Patron de diseño DAO**
El patron de diseño DAO es un patron de diseño que permite separar la logica de negocio de la logica de acceso a datos.

## Buenas practicas de programacion

**Bajo acoplamiento**
El bajo acoplamiento es un principio de diseño que dice que los componentes de un sistema deben estar lo mas desacoplados posible.

**Alta cohesión**
El principio de alta cohesión dice que los componentes de un sistema deben estar lo mas cohesionados posible.

**JAVA Importante**
Se tiene que acostumbrar a trabar con objetos y no por valor ya que los objetos se pasan por referencia y los valores por valor.

## Conexion a la base de datos

Una transacción es un conjunto de operaciones que se ejecutan como una sola unidad. Si una de las operaciones falla, todas las operaciones deben fallar. Si todas las operaciones se completan correctamente, todas las operaciones deben completarse correctamente.

**La practica esta realizada en el proyecto INTRODUCCIONJDBC3**

```
private Connection connTransaccional;
```

## **Revisar como funcina una itnerface en JAVA**

**Como tarea implementar el trazacion en TestConexionPrueba.java**

## Buenas practicas y patrones de deseño

![image](https://user-images.githubusercontent.com/99310007/192063823-5fc9d6d8-9303-42ee-abd7-655819f86a18.png)

## POOL DE CONEXIONES JDBC

Sirve para tener un conjunto de conexiones a la base de datos y que se puedan reutilizar.
Introdcuccion a JDBC 5 POOL DE CONEXIONES JDBC

```
<dependency>
      <groupId>org.apache.commons</groupId>
      <artifactId>commons-dbcp2</artifactId>
      <version>2.8.0</version>
</dependency>

En vez de DriverManager se usa getDataSource
En la clase conexion
```

## Servlets y JSP's.
Encargado de la parte web de la aplicacion.
Son clases que se ejecutan en el servidor y que se encargan de generar la respuesta a una peticion de un cliente.

GlassFish 5.0.1 - Full Platform
Link de descargar Glassfish: https://projects.eclipse.org/projects/ee4j.glassfish/downloads

C:\AppServer\glassfish