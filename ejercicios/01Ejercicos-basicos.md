# 10 Ejercicios Básicos de JavaScript

Esta guía contiene 10 ejercicios progresivos para aprender los fundamentos de JavaScript. Cada ejercicio incluye la descripción del problema, ejemplos y pistas para resolverlo.

## Ejercicio 1: Variables y Tipos de Datos
**Objetivo:** Crear variables de diferentes tipos y mostrar su contenido.

**Instrucciones:**
1. Crea una variable `nombre` con tu nombre
2. Crea una variable `edad` con tu edad
3. Crea una variable `esEstudiante` que sea `true` o `false`
4. Muestra todas las variables en la consola

**Ejemplo de salida:**
```
Nombre: María
Edad: 25
¿Es estudiante?: true
```

**Pista:** Usa `console.log()` para mostrar los valores y el operador `+` para concatenar strings.

---

## Ejercicio 2: Calculadora Básica
**Objetivo:** Crear funciones para operaciones matemáticas básicas.

**Instrucciones:**
1. Crea una función `sumar(a, b)` que devuelva la suma de dos números
2. Crea funciones similares para restar, multiplicar y dividir
3. Prueba cada función con diferentes números

**Ejemplo de uso:**
```javascript
console.log(sumar(5, 3)); // Debe mostrar: 8
console.log(dividir(10, 2)); // Debe mostrar: 5
```

**Pista:** Usa la palabra clave `function` o funciones arrow `=>`.

---

## Ejercicio 3: Condicionales - Clasificador de Edad
**Objetivo:** Usar estructuras condicionales para clasificar personas por edad.

**Instrucciones:**
Crea una función `clasificarEdad(edad)` que:
- Si la edad es menor a 13: "Niño"
- Si está entre 13 y 17: "Adolescente"  
- Si está entre 18 y 64: "Adulto"
- Si es 65 o más: "Adulto Mayor"

**Ejemplo de uso:**
```javascript
console.log(clasificarEdad(10)); // "Niño"
console.log(clasificarEdad(25)); // "Adulto"
```

**Pista:** Usa `if`, `else if` y `else` para crear las condiciones.

---

## Ejercicio 4: Bucles - Tabla de Multiplicar
**Objetivo:** Usar bucles para generar una tabla de multiplicar.

**Instrucciones:**
Crea una función `tablaMultiplicar(numero)` que muestre la tabla de multiplicar del número dado del 1 al 10.

**Ejemplo de salida para `tablaMultiplicar(5)`:**
```
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
...
5 x 10 = 50
```

**Pista:** Usa un bucle `for` que vaya del 1 al 10.

---

## Ejercicio 5: Arrays - Gestión de Lista de Compras
**Objetivo:** Manipular arrays con métodos básicos.

**Instrucciones:**
1. Crea un array `listaCompras` con 5 productos
2. Agrega un producto más al final usando `push()`
3. Elimina el primer producto usando `shift()`
4. Muestra la lista final y su longitud

**Ejemplo inicial:**
```javascript
let listaCompras = ["manzanas", "pan", "leche", "huevos", "queso"];
```

**Pista:** Usa `console.log()` para mostrar el array después de cada operación.

---

## Ejercicio 6: Objetos - Información Personal
**Objetivo:** Crear y manipular objetos básicos.

**Instrucciones:**
1. Crea un objeto `persona` con propiedades: nombre, edad, ciudad, hobbies (array)
2. Muestra la información de la persona
3. Agrega un nuevo hobby al array
4. Cambia la ciudad de residencia

**Ejemplo de estructura:**
```javascript
let persona = {
    nombre: "Carlos",
    edad: 30,
    ciudad: "Madrid",
    hobbies: ["leer", "nadar"]
};
```

**Pista:** Usa la notación de punto (`.`) o corchetes (`[]`) para acceder a las propiedades.

---

## Ejercicio 7: Strings - Analizador de Texto
**Objetivo:** Manipular strings usando métodos nativos.

**Instrucciones:**
Crea una función `analizarTexto(texto)` que:
1. Muestre el texto en mayúsculas
2. Muestre el texto en minúsculas  
3. Cuente el número de caracteres
4. Cuente el número de palabras

**Ejemplo de uso:**
```javascript
analizarTexto("Hola Mundo JavaScript");
```

**Pista:** Usa métodos como `toUpperCase()`, `toLowerCase()`, `length` y `split()`.

---

## Ejercicio 8: Funciones con Arrays - Números Pares
**Objetivo:** Filtrar elementos de un array usando bucles.

**Instrucciones:**
1. Crea una función `numerosPares(numeros)` que reciba un array de números
2. La función debe retornar un nuevo array solo con los números pares
3. Prueba la función con diferentes arrays

**Ejemplo de uso:**
```javascript
let numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
console.log(numerosPares(numeros)); // [2, 4, 6, 8, 10]
```

**Pista:** Usa el operador módulo `%` para verificar si un número es par.

---

## Ejercicio 9: Condicionales Avanzados - Calculadora de Notas
**Objetivo:** Crear un sistema de calificación con múltiples condiciones.

**Instrucciones:**
Crea una función `calcularNota(puntuacion)` que:
- 90-100: "Excelente (A)"
- 80-89: "Muy Bien (B)"
- 70-79: "Bien (C)"
- 60-69: "Regular (D)"
- Menos de 60: "Insuficiente (F)"

**Validaciones adicionales:**
- Si la puntuación es mayor a 100 o menor a 0: "Puntuación inválida"

**Pista:** Combina operadores lógicos `&&` para crear rangos.

---

## Ejercicio 10: Mini Proyecto - Generador de Contraseñas
**Objetivo:** Integrar múltiples conceptos en un proyecto práctico.

**Instrucciones:**
Crea una función `generarPassword(longitud)` que:
1. Genere una contraseña aleatoria de la longitud especificada
2. Use letras mayúsculas, minúsculas y números
3. Muestre la contraseña generada

**Caracteres disponibles:**
```javascript
const caracteres = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789";
```

**Ejemplo de uso:**
```javascript
console.log(generarPassword(8)); // "aB3kL9mP" (ejemplo)
```

**Pista:** Usa `Math.random()` y `Math.floor()` para generar índices aleatorios.

---

## Consejos para Resolver los Ejercicios

1. **Lee cada ejercicio completamente** antes de empezar a codificar
2. **Empieza por casos simples** y luego agrega complejidad
3. **Usa la consola del navegador** (F12) para probar tu código
4. **No tengas miedo de experimentar** - los errores son parte del aprendizaje
5. **Comenta tu código** para explicar qué hace cada parte

## Recursos Adicionales

- **MDN Web Docs**: Documentación oficial de JavaScript
- **Console del navegador**: Presiona F12 para abrir las herramientas de desarrollador
- **Prueba tu código**: Usa `console.log()` frecuentemente para verificar resultados

¡Buena suerte programando! 🚀