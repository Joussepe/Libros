| Apellidos y Nombres:            |  
|---------------------------------|
| Huaman Capcha, Estefani Abigail | 
| Camargo Ambicho Joussepe Josué  |
| Lorenzo Masgo Josue Eli   |


##  -class Libro:
Se definen los atributos para la clase libro que serian título, autor y año_publicacion
## -class Biblioteca:
Inicializa el atributo libros como una lista vacía que contendra los libros de la biblioteca, el cual tiene tres métodos:
### def agregar_libro(self, libro):
Este método toma el objeto de la clase libro como argumento y lo agrega a la lista de libros de la biblioteca siempre y cuando tenga título y autor de lo contrario se genera un error.
### def buscar_libro(self, titulo):
Este método toma el título del libro como argumento y busca en la lista de libros de la biblioteca cual es el título si lo encuentra devuelve el libro y si no genera un error
### def mostrar_libros(self):
Este método muestra todos los libros de la biblioteca junto con su autor y año de publicación, si la biblioteca está vacía muestra un mensaje indicandolo.
## -class ErrorLibroSinTitulo(Exception):
Esta excepcion se utiliza para indicar que se a intentado agregar un libro sin título
## -class ErrorLibroSinAutor(Exception):
Esta excepcion se utiliza para indicar que se a intentado agregar un libro sin autor
## -class ErrorLibroDuplicado(Exception):
Esta excepcion se utiliza para indicar que se a intentado agregar un libro duplicado
## -class ErrorAñoInvalido(Exception):
Esta excepcion se utiliza para indicar que se a intentado agregar un libro con un formato de año inválido
