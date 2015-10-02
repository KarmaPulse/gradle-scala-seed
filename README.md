# Proyecto semilla para usar Gradle con Scala y Java

El proyecto de Gradle utiliza los siguientes plugins.

- [Scala](https://docs.gradle.org/current/userguide/scala_plugin.html)
- [Application](https://docs.gradle.org/current/userguide/application_plugin.html)
- [ShadowJar](https://github.com/johnrengelman/shadow)

El proyecto debe estructurase utilizando el layout inidicado en el plugin de Scala.

## Tareas

- **Compilar y contruir el proyecto.**

```
gradle build
```

- **Borrar el directorio de contruccion.**

```
gradle clean
```

- **Correr el proyecto.**

```
gradle run
```
- **Generar UberJar/FatJar.**

```
gradle shadowJar
```

**NOTA:**

Para mas informacion sobre cada plugin revisar los links de cada uno.
