<p align="center">
  <img src="https://github.com/comayocode/comayocode/blob/main/assets/GithubBanner_v2.jpg" />
</p>

```java
package logica;

public abstract class Persona {
    private String nombre = "Ronald Comayan";
    private String titulo = "Estudiante tecnólogo de Análisis y Desarrollo de Software";
    private String ubicacion = "Colombia CO";
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
}
```
