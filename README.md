
class Program
{
    static void Main()
    {
        // Solicitar el primer número al usuario
        Console.Write("Ingrese el primer número entero: ");
        // Leer el primer número desde la entrada estándar (teclado) y convertirlo a entero
        int numero1 = Convert.ToInt32(Console.ReadLine());

        // Solicitar el segundo número al usuario
        Console.Write("Ingrese el segundo número entero: ");
        // Leer el segundo número desde la entrada estándar (teclado) y convertirlo a entero
        int numero2 = Convert.ToInt32(Console.ReadLine());

        // Calcular la suma de los dos números
        int suma = numero1 + numero2;

        // Calcular el producto de los dos números
        int producto = numero1 * numero2;

        // Mostrar la suma y el producto en la salida estándar (pantalla)
        Console.WriteLine("La suma de los dos números es: " + suma);
        Console.WriteLine("El producto de los dos números es: " + producto);

        // Esperar a que el usuario presione una tecla para cerrar la aplicación
        Console.WriteLine("Presione cualquier tecla para salir...");
        Console.ReadKey();
    }
}


