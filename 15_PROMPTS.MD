# PROMPT 1

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función llamada **sumar()**, la cual debe recibir dos números y retornar la suma.
El problema es que el código está generando un resultado incorrecto y quiero que identifiques cuál es el error y cómo corregirlo.

---

## **Código con el error**

```
function sumar(a, b) {
  return a + b;
}

const resultado = sumar(5);
console.log("El resultado es:", resultado);
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**


# PROMPT 2

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que calcula el promedio de una lista de números.
Sin embargo, el código está arrojando resultados incorrectos y en algunos casos errores en tiempo de ejecución.
Necesito que analices el código y lo repares.

---

## **Código con el error**

```
function calcularPromedio(numeros) {
  let suma = 0;

  numeros.forEach(n => {
    suma += n.toUpperCase();
  });

  return suma / numeros.lenght;
}

const lista = [10, 20, 30, 40];
const resultado = calcularPromedio(lista);

console.log("Promedio:", resultado);
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**


---

# PROMPT 3

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que toma una lista de productos y calcula el total de precios, además de formatear los datos para mostrarlos en pantalla.
El problema es que el código está devolviendo valores `NaN`, errores de propiedades inexistentes y fallos al recorrer la lista.

---

## **Código con el error**

```
const productos = [
  { nombre: "Mouse", precio: 50 },
  { name: "Teclado", costo: 120 },
  { nombre: "Pantalla", precio: "300" }
];

function calcularTotal(lista) {
  let total = 0;

  for (let i = 0; i <= lista.length; i++) {
    total += lista[i].precio.toFixed(2);
  }

  return total;
}

const resultado = calcularTotal(productos);
console.log("Total:", resultado.toUpperCase());
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**


---

# PROMPT 4

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que procesa información de estudiantes: calcula su nota final y devuelve un mensaje dependiendo del resultado.
El código está generando errores, devolviendo `undefined` y en algunos casos fallando al acceder a propiedades.

---

## **Código con el error**

```
const estudiantes = [
  { nombre: "Sara", nota1: 4.5, nota2: 3.8 },
  { name: "Ana", nota1: "5", notaFinal: 4.0 },
  { nombre: "Luis", nota2: 2.9 }
];

function calcularNotaFinal(est) {
  return (est.nota1 + est.nota2) / 2.toFixed(1);
}

function procesar(estudiantes) {
  return estudiantes.map(e => {
    const final = calcularNotaFinal(e);

    if (final > 3.5) {
      return `${e.nombre.toUppercase()} APROBÓ con ${final}`;
    } else {
      return `${e.nombre.toUppercase()} REPROBÓ con ${final}`;
    }
  });
}

const resultados = procesar(estudiantes);
console.log(resultados);
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**
---

# PROMPT 5

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que calcula estadísticas básicas de una lista de números:

* el número mayor,
* el menor
* y el promedio.

Sin embargo, el código está lanzando errores, devuelve `NaN`, accede mal a índices y mezcla tipos incorrectamente.

---

## **Código con el error**

```
function calcularEstadisticas(lista) {
  let mayor = lista[0];
  let menor = lista[0];
  let suma = 0;

  for (let i = 0; i <= lista.length; i++) {
    if (lista[i] > mayor) mayor = lista[i];
    if (lista[i] < menor) menor = lista[i];
    suma += lista[i].toUpperCase();
  }

  const promedio = suma / lista.lenght;

  return {
    mayor: mayor.toFixed(2),
    menor,
    promedio
  };
}

const datos = [10, 20, 30, "40"];
const resultado = calcularEstadisticas(datos);

console.log("Resultados:", resultado.toUpperCase());
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**

---

# PROMPT 6

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que convierte una lista de textos en un formato "slug" para URLs.
El problema es que el código está arrojando errores, generando `undefined`, y en otros casos devolviendo resultados incorrectos.

---

## **Código con el error**

```
const titulos = [
  "Curso de JavaScript",
  "Aprender HTML",
  123,
  { titulo: "Programación Web" }
];

function convertirASlug(texto) {
  return texto.toLowercase().replaceAll(" ", "-").trim("-");
}

function procesarLista(lista) {
  const resultado = [];

  for (let i = 0; i <= lista.length; i++) {
    const slug = convertirASlug(lista[i]);
    resultado.push(slug);
  }

  return resultado;
}

const slugs = procesarLista(titulos);
console.log("Slugs generados:", slugs.toUpperCase());
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**

---

# PROMPT 7

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que busca un producto por su ID dentro de un arreglo y calcula su precio total con impuestos.
El código está lanzando errores, devolviendo `undefined` y generando operaciones inválidas.

---

## **Código con el error**

```
const productos = [
  { id: 1, nombre: "Laptop", precio: 2500 },
  { id: 2, nombre: "Mouse", costo: 50 },
  { id: 3, name: "Teclado", precio: "100" }
];

function buscarProducto(id) {
  return productos.find(p => p.id == id).nombre.toUppercase();
}

function calcularPrecioTotal(prod) {
  return prod.precio + prod.precio * 0.19.toFixed();
}

const producto = buscarProducto(2);
const total = calcularPrecioTotal(producto);

console.log("Total final:", total.toFixed(2));
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**
---

# PROMPT 8

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que busca un producto por su ID dentro de un arreglo y calcula su precio total con impuestos.
El código está lanzando errores, devolviendo `undefined` y generando operaciones inválidas.

---

## **Código con el error**

```
const productos = [
  { id: 1, nombre: "Laptop", precio: 2500 },
  { id: 2, nombre: "Mouse", costo: 50 },
  { id: 3, name: "Teclado", precio: "100" }
];

function buscarProducto(id) {
  return productos.find(p => p.id == id).nombre.toUppercase();
}

function calcularPrecioTotal(prod) {
  return prod.precio + prod.precio * 0.19.toFixed();
}

const producto = buscarProducto(2);
const total = calcularPrecioTotal(producto);

console.log("Total final:", total.toFixed(2));
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**

---

# PROMPT 9

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que calcula el **subtotal**, **impuesto** y **total** de una factura.
El código está generando errores porque mezcla tipos, usa propiedades incorrectas y hace operaciones inválidas.

---

## **Código con el error**

```
const factura = {
  cliente: "Sara",
  productos: [
    { nombre: "Mouse", precio: 50, cantidad: 2 },
    { name: "Pantalla", valor: "300", cantidad: 1 },
    { nombre: "Teclado", precioUnit: 120 }
  ]
};

function calcularFactura(f) {
  let subtotal = 0;

  f.productos.forEach(p => {
    subtotal += p.precio * p.cantidad.toFixed();
  });

  const impuesto = subtotal * 0.19.toUpperCase();
  const total = subtotal + impuesto;

  return {
    cliente: f.cliente.toUppercase(),
    subtotal,
    impuesto,
    total
  };
}

const resultado = calcularFactura(factura);
console.log("Factura final:", resultado.toFixed(2));
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**
---

# PROMPT 10

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con un sistema simple para calcular el **promedio de calificaciones** de un curso.
El código intenta sumar notas, validar su tipo y mostrar un resultado final.
Sin embargo, está generando `NaN`, errores por propiedades incorrectas y fallos en la lógica del recorrido.

---

## **Código con el error**

```
const notas = [
  { estudiante: "Felipe", nota: 4.5 },
  { name: "Ana", calificacion: "5" },
  { estudiante: "Luis", notaFinal: 3.8 },
  4.0
];

function calcularPromedio(lista) {
  let total = 0;

  for (let i = 0; i <= lista.length; i++) {
    total += lista[i].nota.toUpperCase();
  }

  const promedio = total / lista.lenght;
  return promedio.toFixed();
}

const promedioFinal = calcularPromedio(notas);
console.log("Promedio del curso:", promedioFinal.toUppercase());
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**

---

# PROMPT 11

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que analiza información de un inventario:

* busca un producto por su nombre,
* calcula el valor total del stock
* y genera un texto final con los datos.

El problema es que el código está generando `undefined`, errores de propiedades inexistentes, operaciones inválidas y fallos al procesar los datos.

---

## **Código con el error**

```
const inventario = [
  { nombre: "Laptop", precio: 2500, cantidad: 3 },
  { name: "Mouse", valor: "50", cantidad: 10 },
  { nombre: "Teclado", precioUnit: 150 }
];

function buscarProducto(nombre) {
  const p = inventario.find(x => x.nombre == nombre);
  return p.nombre.toUppercase();
}

function calcularValorTotal(prod) {
  return prod.precio * prod.cantidad.toFixed(2);
}

function procesar(nombre) {
  const producto = buscarProducto(nombre);
  const total = calcularValorTotal(producto);

  return `Producto: ${producto.nombre} — Total: ${total.toUpperCase()}`;
}

const resultado = procesar("Mouse");
console.log(resultado);
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**
---

# PROMPT 12

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que procesa datos de una API falsa.
La función debe:

* obtener usuarios,
* filtrar los que están activos,
* crear un mensaje de bienvenida para cada uno.

Pero el código está generando errores de tipos, propiedades mal escritas, fallos con async/await y problemas de lógica.

---

## **Código con el error**

```
async function obtenerUsuarios() {
  return new Promise((res, rej) => {
    setTimeout(() => {
      res([
        { id: 1, nombre: "Sara", activo: true },
        { id: 2, name: "Ana", active: "true" },
        { id: 3, nombre: "Luis" }
      ]);
    }, 400);
  });
}

function filtrarActivos(lista) {
  return lista.filter(u => u.activo === "true");
}

function crearMensaje(usuario) {
  return "BIENVENIDO " + usuario.nombre.toUppercase();
}

async function procesar() {
  const datos = obtenerUsuarios();

  const activos = filtrarActivos(datos);

  const mensajes = activos.map(u => crearMensaje(u));

  console.log("Mensajes generados:", mensajes.toUpperCase());
}

procesar();
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**

---

# PROMPT 13

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando con una función que procesa un listado de **empleados**:

* calcula su salario anual,
* valida sus datos,
* y genera un reporte final.

El código está generando `NaN`, propiedades undefined, errores de lógica y cálculos inválidos.

---

## **Código con el error**

```
const empleados = [
  { nombre: "Sara", salarioMensual: 2000 },
  { name: "Ana", sueldo: "1500" },
  { nombre: "Luis", salario: 1800, meses: "12" }
];

function calcularSalarioAnual(emp) {
  return emp.salarioMensual * emp.meses.toFixed();
}

function generarReporte(lista) {
  return lista.map(e => {
    const anual = calcularSalarioAnual(e);

    return `${e.nombre.toUppercase()} gana ${anual.toUpperCase()} al año`;
  });
}

const reporte = generarReporte(empleados);
console.log("Reporte final:", reporte.toLowerCase());
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**

---

# PROMPT 14

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy intentando crear una función que procese datos de **productos en un carrito de compras**:

* calcula el subtotal,
* calcula el impuesto,
* calcula el total,
* y devuelve un mensaje con la información del carrito.

El código está generando errores como `undefined`, `NaN`, fallos en cálculos y propiedades mal escritas.

---

## **Código con el error**

```
const carrito = [
  { nombre: "Mouse", precio: 50, cantidad: 2 },
  { name: "Teclado", valor: "120", cantidad: 1 },
  { nombre: "Pantalla", precioUnit: 800 }
];

function calcularSubtotal(items) {
  let subtotal = 0;

  items.forEach(i => {
    subtotal += i.precio * i.cantidad.toFixed(2);
  });

  return subtotal;
}

function calcularTotal(sub) {
  const impuesto = sub * 0.19.toUpperCase();
  return sub + impuesto;
}

function generarMensaje(carrito) {
  const subtotal = calcularSubtotal(carrito);
  const total = calcularTotal(subtotal);

  return `SUBTOTAL: ${subtotal.toFixed()}, TOTAL: ${total.toUppercase()}`;
}

console.log("Carrito procesado:", generarMensaje(carrito).toLowerCase());
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**

---

# PROMPT 15

Actúa como un **Desarrollador Senior en JavaScript**, experto en depuración, análisis de errores y buenas prácticas.
Tu tarea es revisar mi código, identificar todos los errores que puedan generar fallos o resultados incorrectos, explicar la causa de cada uno y entregar una versión corregida y mejorada.

---

## **Contexto**

Estoy trabajando en una función que procesa **notificaciones** de un sistema.
Cada notificación debe:

* Normalizar su texto,
* Convertirse en mayúsculas,
* Y mostrar un número de prioridad.

Sin embargo, el código genera errores, devuelve `undefined`, mezcla tipos incorrectos y rompe el formateo del texto.

---

## **Código con el error**

```
const notificaciones = [
  { mensaje: "tarea completada", prioridad: 1 },
  { msg: "error en el sistema", prioridad: "2" },
  { mensaje: 123, level: 3 }
];

function formatearNotificacion(n) {
  const texto = n.mensaje.toUppercase().trim("-");
  const prioridad = n.prioridad.toFixed(1);

  return `ALERTA: ${texto} | PRIORIDAD: ${prioridad.toUpperCase()}`;
}

function procesarNotificaciones(lista) {
  const resultado = [];

  for (let i = 0; i <= lista.length; i++) {
    resultado.push(formatearNotificacion(lista[i]));
  }

  return resultado.toLowerCase();
}

const salida = procesarNotificaciones(notificaciones);
console.log("Salida final:", salida);
```

---

## **Lo que necesito que hagas**

* Detectar todos los errores del código.
* Explicar claramente la causa de cada error.
* Entregar una versión corregida y funcionando.
* Dar recomendaciones para evitar estos errores a futuro.

---

## **Formato de respuesta esperado**

1. **Errores detectados**
2. **Explicación técnica**
3. **Código corregido**
4. **Recomendaciones finales**

---