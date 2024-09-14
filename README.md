## Hola, soy Rene Alejandro Yuman Barco 💻

```java

public class Desarrollador {
    
    private String nombre = "Alejandro Yuman";
    private String Descripcion ="Estudiante de Ingenieria en Sistemas, con voluntad de seguir aprendiendo cada dia"
    private String pais = "Guatemala"
    private String correo = "renebarcoyuman@gmail.com"
    private int edad = 19;
    
    private String[] learning = {"Java", "Python", "Fortran", "Blender", "GitHub", "Unity"};


    public void saludar() {
        System.out.println("Hola Mundo");
    }


    public static void main(String[] args) {
        Desarrollador rene = new Desarrollador();
        rene.saludar();
    }
}


