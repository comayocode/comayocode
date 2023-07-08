<p align="center">
  <img src="https://github.com/comayocode/comayocode/blob/main/assets/GithubBanner_v2.jpg" />
</p>

```java
package Readme;

import java.util.Arrays;

public class Desarrollador extends Persona{

    private String[] lenguajes;
    private String[] basesDatos;
    private String[] otros;

    public Desarrollador(String[] lenguajes, String[] basesDatos, String[] otros, String nombre, String titulo, String ubicacion) {
        super(nombre, titulo, ubicacion);
        this.lenguajes = lenguajes;
        this.basesDatos = basesDatos;
        this.otros = otros;
    }

    // Getters y Setters

    @Override
    public void info() {
        System.out.println("Nombre         :" +Desarrollador.super.getNombre());
        System.out.println("Título         :" +Desarrollador.super.getTitulo());
        System.out.println("Ubicación      :" +Desarrollador.super.getUbicacion());
        System.out.println("Lenguajes      :" +Arrays.toString(lenguajes));
        System.out.println("Bases de Datos :" +Arrays.toString(basesDatos));
        System.out.println("Otros          :" +Arrays.toString(otros));
    }
    
}
```
