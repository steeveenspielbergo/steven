# Apuntes de informatica
Consulta este enlace [https://www.google.com/]()
`Esto es una clase de ecuaciones`
```
import java.util.Scanner;

class EcuacionCuadratica {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Ingrese los coeficientes de la ecuación cuadrática (a, b, c):");
        double a = scanner.nextDouble();
        double b = scanner.nextDouble();
        double c = scanner.nextDouble();

        double discriminante = b * b - 4 * a * c;

        if (discriminante > 0) {
            double raiz1 = (-b + Math.sqrt(discriminante)) / (2 * a);
            double raiz2 = (-b - Math.sqrt(discriminante)) / (2 * a);
            System.out.println("Las raíces reales de la ecuación cuadrática son: " + raiz1 + " y " + raiz2);
        } else if (discriminante == 0) {
            double raiz = -b / (2 * a);
            System.out.println("La ecuación cuadrática tiene una raíz real doble: " + raiz);
        } else {
            double parteReal = -b / (2 * a);
            double parteImaginaria = Math.sqrt(-discriminante) / (2 * a);
            System.out.println("Las raíces imaginarias de la ecuación cuadrática son: " + parteReal + " + " + parteImaginaria + "i y " + parteReal + " - " + parteImaginaria + "i");
        }

        scanner.close();
    }
}

Pasos de desarrollo de software

* Analisis
* Diseño
* Codificacion

```
SS

olvidas miles de cosas cada dia, asegurate de que esta sea una de ellas 
kiflom
