# calculadora_y_gestor_de_estudiantes
Calculadora y Gestor de Estudiantes
# Calculadora y Gestor de Estudiantes

¡Hola! Bienvenido a mi proyecto. Esta es una aplicación interactiva que diseñé para ejecutarse directamente en la consola del navegador web. La creé como parte de mi aprendizaje en los fundamentos de programación con JavaScript, aplicando estructuras de control, funciones y manejo de arreglos de una manera sencilla y directa.

El objetivo principal de este proyecto es consolidar conceptos básicos sin complicar el código con arquitecturas avanzadas, haciéndolo ideal para repasar las bases de la programación.

Tecnologías utilizadas

JavaScript: Toda la lógica del programa, variables, bucles y funciones.
Consola del Navegador: El entorno de ejecución donde se muestran los resultados.
Ventanas Emergentes (`prompt` y `alert`): El medio para interactuar con el usuario y recibir datos.

Características principales

El programa cuenta con un menú interactivo que se repite hasta que decidas salir, ofreciendo las siguientes opciones:

1. **Calculadora Básica**: Realiza sumas, restas, multiplicaciones y divisiones. Cuenta con una validación simple para evitar la división por cero y guarda un registro de las operaciones realizadas.
2. **Gestión de Estudiantes**: Permite registrar alumnos ingresando su nombre, edad y nota. Los datos se almacenan en arreglos paralelos para facilitar su lectura.
3. **Reportes por Consola**: 
   * Muestra la lista completa de estudiantes registrados junto con su estado (Aprobado/Reprobado).
   * Filtra y muestra únicamente a los estudiantes que obtuvieron una nota mayor o igual a 6.
   * Calcula de forma automática el promedio general de todas las notas ingresadas.
4. **Historial**: Permite revisar en la consola todas las operaciones matemáticas que has hecho durante la sesión.

Cómo ejecutar el proyecto

Para probar la aplicación no necesitas instalar nada, solo sigue estos sencillos pasos:

1. Copia todo el código del archivo `index.js` (o el archivo principal).
2. Abre tu navegador web favorito (Google Chrome, Firefox, Edge, etc.).
3. Abre las herramientas de desarrollador presionando `F12` o haciendo clic derecho y seleccionando **Inspeccionar**.
4. Ve a la pestaña **Consola** (Console).
5. Pega el código que copiaste y presiona `Enter`.
6. ¡Listo! El menú interactivo aparecerá en tu pantalla. *(Asegúrate de mirar la consola para ver los resultados de las listas y los historiales)*.

Lo que aprendí con este código

* A estructurar un menú interactivo usando el bucle `while`.
* A conectar diferentes funciones para procesar datos matemáticos y textos de forma ordenada.
* El uso de condicionales con `if` y `else if` para la toma de decisiones del programa.
* El manejo de arreglos (arreglos paralelos compartiendo el índice `[i]`) y cómo recorrerlos mediante el bucle `for` clásico.
