# Notas de clase

## Repaso de conceptos

- Operaciones aritmeticas de suma y multiplicacion
- Operacion de concatenacion de cadenas de texto `string`
- Evaluacion de operaciones de comparacion y condicionales, para la toma de decision
- Estructura logica - switch

### SWITCH

**Ejemplo sobre dias con ifs**

```javascript
let dia = 4;
if (dia === 1) {
  console.log('Lune');
} else if (dia === 2) {
  console.log('Marte');
} else if (dia === 3) {
  console.log('Miercole');
} else if (dia === 4) {
  console.log('Jueve');
} else if (dia === 5) {
  console.log('Vierne');
} else if (dia === 6) {
  console.log('Sabado');
} else if (dia === 7) {
  console.log('Domingo');
} else {
  console.log('Día no válido');
}
```

**Ejemplo con meses**

```javascript
function selectorDeMeses(nombreMes) {
  switch (nombreMes) {
    case 'enero':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 1);
      break;
    case 'febrero':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 2);
      break;
    case 'marzo':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 3);
      break;
    case 'abril':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 4);
      break;
    case 'mayo':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 5);
      break;
    case 'junio':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 6);
      break;
    case 'julio':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 7);
      break;
    case 'agosto':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 8);
      break;
    case 'septiembre':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 9);
      break;
    case 'octubre':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 10);
      break;
    case 'noviembre':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 11);
      break;
    case 'diciembre':
      console.log(`el mes ${nombreMes} se corresponde con el numero`, 12);
      break;

    default:
      throw new Error('Ese mes no existe');
      break;
  }
}
```

## Tema de clase

- Introducción a los Bucles
- Bucles en JavaScript
- Bucle for
- Resolucion de ejercicio de bucle `for`

### Resolucion de ejercicio de bucle `for`

```javascript
const WHY_NOT = '¯_(ツ)_/¯';
const JOYFUL = '^_^';

let numeros = [1, 6, 9, 2, 3, 1, 10, 4, 5, 7, 8, 2];

for (let index = 0; index < numeros.length; index++) {
  const numero = numeros[index];
  const deberiaImprimirNumero = numero > 5 ? WHY_NOT : JOYFUL;

  if (deberiaImprimirNumero === '¯_(ツ)_/¯') {
    console.log(numero);
  }
}
```
