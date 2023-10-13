## ArchivoVb18

**Descripción**

ArchivoVb18 es una librería Java que proporciona métodos para leer, escribir, editar, copiar y eliminar archivos TXT. Esta librería está diseñada para fines académicos y está disponible para su uso gratuito por cualquier persona.

**Métodos**

* `leerArchivo(String nombreArchivo)`: Lee el contenido de un archivo TXT y lo devuelve como una cadena.
* `escribirArchivo(String nombreArchivo, String contenido)`: Escribe el contenido de una cadena en un archivo TXT.
* `editarArchivo(String nombreArchivo, String contenido, int posición, int longitud)`: Edita el contenido de un archivo TXT en la posición especificada.
* `copiarArchivo(String nombreArchivoOrigen, String nombreArchivoDestino)`: Copia un archivo TXT de una ubicación a otra.
* `eliminarArchivo(String nombreArchivo)`: Elimina un archivo TXT.

**Uso**

Para usar ArchivoVb18, primero debe importar la librería a su proyecto Java. Luego, puede usar los métodos proporcionados para leer, escribir, editar, copiar y eliminar archivos TXT.

**Ejemplo**

El siguiente ejemplo muestra cómo usar el método `leerArchivo()` para leer el contenido de un archivo TXT:

```java
import com.example.archivovb18.ArchivoVb18;

public class Main {

    public static void main(String[] args) {
        // Crea un objeto de la librería ArchivoVb18
        ArchivoVb18 archivoVb18 = new ArchivoVb18();

        // Lee el contenido del archivo "archivo.txt"
        String contenido = archivoVb18.leerArchivo("archivo.txt");

        // Imprime el contenido del archivo
        System.out.println(contenido);
    }
}


**Derechos de autor**

Todos los derechos de autor de ArchivoVb18 pertenecen a la Universidad del Sinú.


