Javascript -> Código que maneja el comportamiento de una página web (Inicios)

Evolución -> Creció la web y con ello el uso del lenguaje
	Motivos:
		-  Flexibilidad (Se puede escribir en cualquier parte)

Fue diseñado para usos rapidos:
	- Desventajas:  comportamiento inesperado

```
if ("" == 0) {

// It is! But why??

}

if (1 < x < 3) {

// True for *any* value of x!

}
```

- Accede a propiedades que no existen

```
const obj = { width: 10, height: 15 };

// Why is this NaN? Spelling is hard!

const area = obj.width * obj.heigth;
```

# Typescript

Conjunto de herramientas diseñadas para el desarrollo en el lenguaje Javascript (Typescript es un lenguaje de programación que preserva el comportamiento de ejecución de Javascript)

- Verifica tipos estáticos
- Comparte sintaxis con Javascript
- Añade tipos de datos
- Se puede mover un código Javascript a Typescript

```
console.log(4 / []);

The right-hand side of an arithmetic operation must be of type 'any', 'number', 'bigint' or an enum type.
```

Una vez que el compilador de Typescript termina su operación, borra los tipos para producir el código "compilado" -> código Javascript sin información de tipos

¿Se puede aprender Typescript sin Javascript? Si

### Para programadores Javascript








### Desarrollo

## Historias de usuario

- El sistema debe registrar un empleado
- Sistema debe grabar entradas de dinero, clasificarlas
- Sistema debe conocer saldo personas y saldo núcleo familiar
- Ingreso de dinero a Metas
- 
- Personas
	- Entradas (Salario, Herencia, etc...)
	- Salidas (Gastos, educación, salud)
	- TipoPersonas
	- Metas (Viaje, compra vivienda)
	- Excedente X persona

Control gastos, prestamos




