# EJERCICIO DE LAS FIGURAS

## CREAR UN PROYECTO CON MAVEN

**1.** Para crear un un proyecto maven con archetypes colocamos el siguiente comando en el simbolo del sistema

```
mvn archetype:generate -DgroupId=edu.eci.cvds -DartifactId=Patterns -Dpackage=edu.eci.cvds.patterns -DarchetypeArtifactId=maven-archetype-quickstart
```

**2.** Luego pide la version y ponemos 1.0
![Imagen1](https://github.com/JuanoYolo/Lab-2/blob/main/1.jpeg)

**3.** Luego ponemos Y

![Imagen2](https://github.com/JuanoYolo/Lab-2/blob/main/2.jpeg)

Y listo

![Imagen3](https://github.com/JuanoYolo/Lab-2/blob/main/3.jpeg)

* Conjunto de archivos y directorios creamos por maven

![Imagen4](https://github.com/JuanoYolo/Lab-2/blob/main/4.jpeg)

---

## AJUSTAR ALGUNAS CONFIGURACIONES EN EL PROYECTO

* Editando el archivo **pom.xml**

![Imagen5](https://github.com/JuanoYolo/Lab-2/blob/main/5.png)

---

## COMPILAR Y EJECUTAR

* Para compilar usamos el comando
`$ mvn package` 

![Imagen6](https://github.com/JuanoYolo/Lab-2/blob/main/6.png)

![Imagen7](https://github.com/JuanoYolo/Lab-2/blob/main/7.png)

* **Parametro Package:** Su objetivo es empaquetar el código compilado y transformarlo en algún formato tipo **.jar** o **.war**\
   Otros comandos son:
   
      * mvn compile: Compila los archivos en el directorio de inicio
      * mvn test: Compila y ejecuta en el directorio de prueba
      * mvn clean: Limpia archivos compilados 
      * mvn install: El proyecto se empaqueta y se carga en el almacén local
