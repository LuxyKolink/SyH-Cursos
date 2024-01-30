1. Que es console.log() ?
- Tipo de dato: Any
- [console - Web APIs | MDN (mozilla.org)](https://developer.mozilla.org/en-US/docs/Web/API/console)
- Provee acceso a la consola de debug, este cambia de acuerdo al navegador o al servidor de ejecución.
- Puede ser accedido por cualquier objeto global, por ej window en navegador  gracias a window.console
- Ejemplo =  console.log("Failed to open the specified link");

2. Que es process.argv ?
- Tipo de dato: String[]
- Es una propiedad que retorna un arreglo el cuál contiene los argumentos de la línea de comando del proceso de Node que se haya lanzado
- Primer elemento -> procces.execPath (process.argv0 ó argv[0])
- Segundo elemento -> Ruta del archivo Javascript que va a ser ejecutado
- 3 a n elementos -> Cualquier argumento adicional.
- Ejemplo = node process-args.js one two=three four

3. Cuál es la diferencia entre let y const?
- let -> Declaración de variable (Es mutable bajo ciertas condiciones)
- const -> Variable inmutable

- Alcance por bloque (Variables dentro de funciones) = let , const 
- Redeclarables  = No
- Reasignables = let
- Entre otros

4. Que es un ciclo For?
- No todos los programas son caminos rectos
- Condicionales -> Solo si se cumple cierta condición
- Ciclos -> Ejecución de una pieza de código de manera repetida siempre que el valor sea **True**
- Por qué se empieza desde 0? Métrica para maquinas
- Se puede romper un ciclo con **Break**, continua con **Continue**
- Ciclo for -> Todas las declaraciones del ciclo se guardan en una sola declaración (Contador, codición, suma ó recorrido)

5. Se pueden sumar 2 strings en js?
- SI, a través de concatenar string con el operador +, también existen otros métodos para concatenar.
- .join (Método lista)
- .concat (Método string)

6. Que hace el .push?
- Añade valores a un array

7. .lenght? -> Longitud de una vista

8. Módulo OS?
- Propiedades del sistema operativo
- Ej: os.cpus()
- Tipo de dato = Object[]
- Contiene -> Model(String), Speed(number), times(Object -> ...)

9. .map()?
- Llama una función callback que itera un elemento por lista (Array) y construye una nueva lista con los resultados.

10.  Objetos?
- Colección de propiedades separadas por comas

11. CommonJs o ES?
- CommonJs es la forma por defecto de importar y exportar paquetes, mientras que los módulos ES hacen parte del formato estándar de Javascript.
- Las antiguas versiones de Node no tiene soporte para módulos ES.
- CommonJs ofrece flexibilidad (Invocar el módulo directamente dentro de una declaración)
- CommonJS = síncrono
- ES = asíncrono

12.  ReadFileSync() y ReadFile()
- Módulos de fs (Módulo que permite interactuar con el sistema de archivos del  SO)
- Lee el contenido de un archivo (tanto síncrona cómo asincrónicamente).

13. Que es un buffer?
- Una secuencia de datos binarios almacenada en memoria
- El dato que devuelve el método ReadFile(), similar a una matriz pero su tamaño es inmutable.

14. UTF8 y ToString()?
- Codificación de caracteres (1 a 4 bytes)
- toString devuelve la cadena a la que representa el objeto.

15. .split()?
- Divide un string en un array mediante separación de cadenas.

16. /r/n?
-  r -> Lugar en el que la linea vuelve a empezar -> "(aquí)Hola"
- n -> Salto de linea
- En otros sistemas operativos no es necesario poner ambas

17. Función Callback?
-  Aquella que es pasada como _argumento_ a otra función para que sea "llamada de nuevo" (call back) en un momento posterior.

18. Eventos 'data' y 'end'?