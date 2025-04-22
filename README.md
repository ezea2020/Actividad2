#  Actividad 2 - Java
#  Programación de Vanguardia
#  Ezequiel Godoy


## Descripción
1- Desarrolle una app que sea maven y que genere un jar. El artefacto debe ser Actividad2, el groupId ar.edu.udeci.pv. y la version 1.0-SNAPSHOT.

2- El proyecto debe contener las librerías:  commons-cli y log4j.

3- Solicitar a una llm que le de un ejemplo de código de cada librería e incluirla en la entrega.

4- Ejecutar la aplicación utilizando maven.

5- Armar un readme en el raiz del proyecto, con toda la explicación de la interacción del proyecto y el desarrollo del mismo

6- subir el proyecto a github.

7- Entregar la url del proyecto dando visibilidad al usuario   ale-vz

Este proyecto es una aplicación Java con Maven que incluye las librerías `commons-cli` y `log4j`.

## Estructura

- Uso de `commons-cli` para parseo de argumentos.
- Uso de `log4j` para logeo a consola.
- Construido con Maven y empaquetado como .jar.

## Cómo ejecutar

```bash
mvn clean package
java -cp target/Actividad2-1.0-SNAPSHOT.jar ar.edu.udeci.pv.Main
```

## Requisitos

- Java 17
- Maven
- Git
