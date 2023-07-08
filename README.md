<p align="center">
  <img src="https://github.com/comayocode/comayocode/blob/main/assets/GithubBanner_v2.jpg" />
</p>

```java
package logica;

public abstract class Persona {
    private String nombre = "Ronald Comayan";
    private String titulo = "Estudiante tecnólogo de Análisis y Desarrollo de Software";
    private String ubicacion = "Colombia CO";

    // Getters

    public abstract void info();
}
```
```java
package logica;

import java.util.Arrays;

public class Desarrollador extends Persona{
    
    private String[] lenguajes = {"JavaScript", "Java", "HTML", "CSS"};
    private String[] basesDatos = {"MySQL", "SQLite"};
    private String[] aprendiendo = {"TypeScript", "Angular", "Spring Boot"};
    private String[] otros = {"Git", "MVC", "Scrum"};

    // Getters

    @Override
    public void info() {
        System.out.println("Nombre         = " +Desarrollador.super.getNombre());
        System.out.println("Título         = " +Desarrollador.super.getTitulo());
        System.out.println("Ubicación      = " +Desarrollador.super.getUbicacion());
        System.out.println("Lenguajes      = " +Arrays.toString(lenguajes));
        System.out.println("Bases de Datos = " +Arrays.toString(basesDatos));
        System.out.println("Aprendiendo    = " +Arrays.toString(aprendiendo));
        System.out.println("Otros          = " +Arrays.toString(otros));
    }
}
```
```java
package main;

import logica.Desarrollador;

public class Run {
    public static void main(String[] args) {
        Desarrollador ronald = new Desarrollador();
        ronald.info();
    }
}
```
