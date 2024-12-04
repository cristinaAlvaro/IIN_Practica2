# IIN_Practica2
# Descripción del proyecto
El objetivo de este repositorio es valorar nuestro conocimiento de git, además de asentar nuestro conocimiento mediante ejercicos prácticos.
# Prueba de Código
Prueba de código que genera palabras aleatorias y las almacena:

`using System;

class Program
{
    static void Main()
    {
        // Array con las palabras posibles
        string[] palabrasPosibles = { "manzana", "pescado", "computadora", "libro", "pelota", "sol", "luna", "guitarra", "reloj", "avión", "elefante", "silla", "puerta", "coche", "flor" };

        // Instanciamos el generador de números aleatorios
        Random random = new Random();

        // Creamos un array para guardar las 10 palabras aleatorias
        string[] palabrasAleatorias = new string[10];

        // Llenamos el array con palabras aleatorias
        for (int i = 0; i < palabrasAleatorias.Length; i++)
        {
            // Seleccionamos una palabra aleatoria del array 'palabrasPosibles'
            int indiceAleatorio = random.Next(palabrasPosibles.Length);
            palabrasAleatorias[i] = palabrasPosibles[indiceAleatorio];
        }

        // Mostramos las palabras generadas
        Console.WriteLine("Palabras aleatorias generadas:");
        foreach (string palabra in palabrasAleatorias)
        {
            Console.WriteLine(palabra);
        }
    }
}`

---

![Gafas](gafas.jpg)


# Autor
Cristina Alvaro Figueroa
