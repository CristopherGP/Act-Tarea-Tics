 Pasos para crear el proyecto en NetBeans:

1. Abrir NetBeans: 
   - Inicia NetBeans y selecciona `File > New Project`.

2. Seleccionar tipo de proyecto: 
   - Elige `Java` en la categoría y selecciona `Java Application`. Haz clic en `Next`.

3. Nombrar el proyecto:
   - Asigna un nombre al proyecto, por ejemplo: `SumaDosNumeros`.
   - Deja marcada la opción `Set as Main Project` para que este proyecto sea el principal.
   - Haz clic en `Finish`.

4. Escribir el código:
   - En la ventana de NetBeans, busca el archivo `Main.java` dentro de la carpeta `Source Packages` en el proyecto que acabas de crear.
   - Reemplaza el contenido del archivo `Main.java` con el siguiente código:

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        // Crear un objeto Scanner para leer la entrada del usuario
        Scanner scanner = new Scanner(System.in);

        // Solicitar al usuario que ingrese el primer número
        System.out.print("Ingresa el primer número: ");
        double numero1 = scanner.nextDouble();

        // Solicitar al usuario que ingrese el segundo número
        System.out.print("Ingresa el segundo número: ");
        double numero2 = scanner.nextDouble();

        // Sumar los dos números
        double suma = numero1 + numero2;

        // Mostrar el resultado de la suma
        System.out.println("La suma de " + numero1 + " y " + numero2 + " es: " + suma);
    }
}
```

### Explicación del código:

- Scanner: Se usa para recibir la entrada del usuario desde la consola.
- System.out.print: Se utiliza para mostrar mensajes en la consola.
- nextDouble: Lee un número de tipo `double` ingresado por el usuario.
- Operación Suma: Los dos números ingresados se suman y el resultado se muestra usando `System.out.println`.

Ejecución:

1. Una vez escrito el código, guarda el archivo y ejecuta el proyecto seleccionando `Run > Run Project` o presionando `F6`.
2. Se abrirá una consola donde te pedirá ingresar dos números. Al introducirlos, el programa te mostrará el resultado de su suma.
