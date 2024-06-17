<img src="https://img.shields.io/badge/STATUS-FINALIZADO-green" display="inline" >

# SWAPI

## Este código en Java representa una aplicación de consola para consultar y guardar información sobre películas de Star Wars en formato JSON. Aquí está la descripción del código:

- Se importan las clases `IOException` de `java.io` y `Scanner` de `java.util`.
- Se define la clase `Principal`.
- Se declara el método `main`, que es el punto de entrada de la aplicación.
- Se crea un objeto `Scanner` llamado `lectura` para leer la entrada del usuario desde la consola.
- Se instancia un objeto `ConsultaPelicula` llamado `consulta` para buscar películas.
- Se solicita al usuario que ingrese el número de la película de Star Wars que desea consultar.
- Se utiliza un bloque `try-catch` para manejar posibles excepciones durante la ejecución del programa.
  - Dentro del bloque `try`, se lee el número de la película ingresada por el usuario y se almacena en la variable `numeroDePelicula`.
  - Se llama al método `buscaPelicula` del objeto `consulta` para buscar la película correspondiente al número ingresado.
  - Se imprime la información de la película encontrada.
  - Se instancia un objeto `GeneradorDeArchivo` llamado `generador` para guardar la información de la película en formato JSON.
  - Se llama al método `guardarJson` del objeto `generador` para guardar la película en un archivo JSON.
  - Si se produce una excepción de tipo `NumberFormatException`, se captura y se imprime un mensaje indicando que el número ingresado no es válido.
  - Si se produce una excepción de tipo `RuntimeException` o `IOException`, se captura y se imprime el mensaje de la excepción, seguido de un mensaje indicando que la aplicación está finalizando.

## Este código básicamente solicita al usuario que ingrese un número de película de Star Wars, busca la información de la película correspondiente, la imprime en la consola y la guarda en un archivo JSON. Además, maneja posibles errores durante este proceso.

## Video
https://github.com/TeodoroMG/SWAPI/assets/108698165/304165f6-3975-4312-a0b0-3bb394c3fba7

