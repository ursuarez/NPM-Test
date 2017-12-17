# NPM-TEST

Este es un paquete de prueba que tiene la funcion de traducir palabras a un idioma inventado.

## Descripcion del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras.
- Si la palabra inicia con Z, se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio.
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas.

## Instalación

```
npm install @ursuarez/npm-test 
```

## Uso 

```
import npm-test from 'npm-test'

console.log(translate("Programar"))  // Program
console.log(translate("Zorro"))      // Zorrope
console.log(translate("Zarpar"))     // Zarppe
console.log(translate("abecedario")) // abece-dario
console.log(translate("sometemos"))  // SoMeTeMoS
```

## Licencia

[MIT](https://opensource.org/licenses/MIT)