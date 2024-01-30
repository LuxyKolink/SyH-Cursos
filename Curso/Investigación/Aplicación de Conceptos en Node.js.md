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