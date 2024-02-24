# Tarea-No.1
ListasSimples
<h1>Lista Simple en Eclipse</h1>
<h2>Introducción</h2>

<p>El proyecto de listas simples es una excelente oportunidad para poder comprender y practicar de una mejor manera los conceptos de estructuras de datos y progrmación orientada a objetos en Java.</p>

<p>Este proyecto consiste en la implementacion de una lsita enlazada simple en el lenguaje de programación Java. Una lsita enlazada es una estructura de datos dinamica que consta de nodos enlazados secuencialmente, cada nodo contiene un valor y referencia al siguiente nodo en la secuencia.</p>

<p>Se creo la clase NODO que esta representa los nodos individuales en la lista enlazada, cada uno almacenando un valor entero, también se implemento una clase ListaSimplementeEnlazada esta proporciona métodos para realizar diversas operaciones en la lista enlazada, tales como inseción, eliminación, busqueda e impresión de elementos.</p>

<p>La funcionalidad del programa se encuentra en la clase MAIN donde se presenta un menú interactivo que permite al usuario realizar diferentes operaciones en la lista enlazanda, como insertar elementos al inicio o al final, insertar una posición específica, eliminar elementos, buscar elementos y mostrar la lista completa.</p>

<h2>Implementación de una lista enlazada simple en Java</h2>
<p> <em><strong>Nodo:</strong></em> Esta clase representa un nodo individual en la lista enlazada. Contiene dos atributos:
-Dato: este atributo almacena el valor o dato que se desea guardar en el Nodo.
-Siguieente: este atributo es una referencia al siguiente Nodo en la lista enlazada.</P>
<p>La clase tiene un constructor que acepta un paramentro DATO para inicializar el valor del NODO y establece el atributo SIGUIENTE en NULL, esto idica que inicialmente, el nodo no está conectado a ningun otro nodo de la lista.</p>

<h2>Esta clase es el programa principal de nuestro proyecto ListaSimplementeEnlazada:</h2>
<p>Se realizaron importaciones en las clases necesarias, en este caso SCANNER para la entrada del usuario.</p>
<p><em><strong>Clase Main:</strong></em></p>
<p>En importaciones el metodo Main se crea un objeto SCANNER para poder leer la entrada del usuario y un objeto ListaSimplementeEnlazada.
Se presenta un menú de opciones al usuario para que elija que operaciones realizar en la lista enlazada.
Dependiendo la opción que seleccionemos, se llamaran los métodos correspondientes de la clase ListaSimplementeEnlazada pra realizar la operación deseada. El programa continúa ejecutandose en un bucle infinito hasta que el usuario pulse la opcion de salir.</p>

<p><em><strong>Switch-Case:</strong></em> Cada opción del menú se maneja utilizando un Switch-case, donde se ejecuta el código correspondiante según la opcion que decee elegir. Las opciones incluyen insertar elementos al inicio, al final o en una posición específica, eliminar elementos, buscar elementos y mostrar la lista.</p>

<p><em><strong>Cerrar Scanner y Salir:</strong></em>Cuando el usuario selecciona la opcion para salir, que en este caso es "9" se cierra el objeto Scanner y el programa se cierra con System.exit. Este programa proporciona una interfaz de usuario para interactuar con la lista. </p>

<h2><em><string>ListaSimplementeEnlazada</string></em></h2>

<p>Para inicializar la lista enlazada como vacía establecimos un constructor en la cabeza como NULL.</p>
<p><em><string>Int Dato:</string></em> Este meetodo crea un nuevo nodo con el dato, establece su siguiente nodo como la cabeza actual y luego actualiza esta para que no apuente de nuevo al nodo.</p>
<p><em><string>Int Dato:</string></em> este metodo verifica si lalsita esta vacía, si no esta vacía recorre la lista hasta el último nodo.
</p>
<p><em><string>InsertarEnPosicion:</string></em> verifica si la posición es valida y maneja los casos especiales de inserción al inicio de la lista.</p>
<p><em><string>Eliminar Primero():</string></em> Elimina el primer nodo de la lista moviendose al siguiente nodo.</p>

<p><em><string>EliminarUltimo():</string></em> Si lalista tiene solo un elemento, lo eliminara ajustando la cabeza a null. De lo contrario, avanzaria hasta el penúltimo nodo y elimina la referencia del ultimo.</p>

<p><em><string>EliminarEnPosicion(int):</string></em>Elimina el nodo en una posicion específica de la lista. Verificando si la posición es válida y si maneja la eliminación del primer nodo. Luego esta avanza hasta la posición deseada y elimina el nodo.</p>
<p><string>Buscar(int dato):</string> Este busca un elemento en la lista y recorre la lista y compara el valor en cada nodo con el dato buscado, retorna TRUE si se encuentra el dato, de lo contrario se retornara FALSE.</p>

<P><string>ImprimirLista():</string>Imprime los elementos de la lista y en orden, recorre la lista e imprime el valor ingresado de cada nodo.</P>

![Menú en consola!](["C:\Users\cunav\OneDrive\Escritorio\ListasSimples.jpg"](https://drive.google.com/file/d/1qXv2NtMVHMCGSvjPZV21sGT7UaX6tJZ_/view?usp=sharing)https://drive.google.com/file/d/1qXv2NtMVHMCGSvjPZV21sGT7UaX6tJZ_/view?usp=sharing)
