# JavaScript
**Autor:** clone1-yena (Yena Kim Choi)
 - Es una cuenta falsa para probar como funciona un trabajo grupal en Git-hub teniendo acceso de escritura a ese repositorio para que puedan hacer modificaciones a otra cuenta.

## Historia
JavaScript fue creado por **Brendan Eich** en **1995** mientras trabajaba en **Netscape**.
- Inicialmente se llamó **Mocha**, luego **LiveScript** y finalmente **JavaScript**.
- Fue diseñado en solo **10 días** para permitir la programación en navegadores.
- La sintaxis está inspirada en **Java** y **C**, pero la ejecución es completamente diferente.
- En 1997, fue adoptado como un estándar por **ECMA International** (ECMAScript).

---

## Campo de aplicación
JavaScript es el lenguaje estándar para:
- **Desarrollo web frontend** : Navegadores como Chrome, Firefox y Safari lo interpretan directamente.
- **Desarrollo backend** : Gracias a **Node.js**, JavaScript también funciona en el lado del servidor.
- **Aplicaciones móviles** : Frameworks como **React Native** permiten crear apps nativas.
- **Aplicaciones de escritorio** : Electron permite construir aplicaciones para Windows, Mac y Linux usando JS.

(Ejemplos)
- **Gmail** y **Google Maps** están construidos en JavaScript.
- **Slack** y **Visual Studio Code** están creados con **Electron** (JavaScript).
- **Netflix** usa Node.js para el procesamiento de datos en el backend.

---

## Tipado, Paradigma y Ejecución
- **Tipado:**
  - Tipado **débil** : Permite conversaciones de tipo implícitas.
  - Tipado **dinámico** : El tipo de las variables puede cambiar en tiempo de ejecucción.
 
(Ejemplo de tipado dinámico)
```javascript
let x = 10; // Número
x = "Hola"; // Ahora es una cadena
```

- **Paradigma:**
  - Orientado a objetos (OOP) : Basado en prototipos en lugar de clases.
  - Funcional : Soporta funciones puras y programación funcional.
  - Porcedimental : Permite estructurar código en funciones.
  
- **Ejecución:**
  - Interpretado : Los navegadores interpretan el código directamente.
  - Just-In-Time (JIT) : Los motores modernos como V8 (Chrome) hacen optimización en tiempo real.
  
---

## Curiosidades
- **JS vs TypeScript: ¿Cuál es más potente?**
   - **JavaScript** : Lenguaje dinámico, interpretado y débil. SU flexibilidad lo hace fácil de usar, pero también propenso a errores difíciles de detectar.
   - **TypeScript** : Es un **superset de JavaScript** (o sea, añade funcionalidades a JS) creado por Microsoft en **2012**.
      - Usa**tipado estático** : Detecta errores en tiempo de compilación.
      - Mejora la estructura y mentenibilidad del código.
      - TypeScript se compila a JavaScript, por lo que el navegador solo ejecuta JS.
   - **Cuál es mejor?**
      - JS : Ideal para proyectos rápidos y flexibles.
      - TS : Mejor para proyectos complejos, escalables y con equipos grandes (por la detección de errores).
         - **React** y **Angular** soportan TypeScript : Por eso TypeScript está cada vez más de moda en el desarrollo frontend.
       
- **JavaScript en el mundo lanoral: ¿Qué está de moda?**
   - **React.js** : Framework frontend creado por **Meta (Facebook)** → DOminante en el desarrollo de interfaces interactivas.
   - **Vue.js** : Framework frogresivo creado por **Evan You** → Muy popular por su sencillez y flexibilidad.
   - **Angular** : Creado por **Google** → Más complejo que React, pero potente para aplicaciones grandes.
   - **Node.js** : Permite usar JS en el backend → Rápido y escalable gracias al motor **V8**.
   - **Express.js** : Framework para backend en Node.js → Facilita el manejo de rutas y API.
   - **Next.js** : Basado en React → Ideal para apps renderizadas en el servidor (SSR).
   - **Nest.js** : Framework backend basado en TypeScript → Estructura sólida para microservicios.
   - **¿Qué usan las empresas?**
      - Meta : React
      - Netflix : Node.js
      - Google : Angular
      - GitHub : Usan TypeScript y Next.js

- **¿Por qué tiene fama de ser dificil de aprender?**
   - **Tipado dinámico y débil** : Puede causar errores ocultos (como 1 + "2" = "12").
   - **Prototipos** : El modelo de herencia basado en prototipos es diferente al de otros lenguajes como Java o C++.
   - **Contexto de ejecución (this)** : El valor de this cambia según el contexto, lo que confunde incluso a desarrolladores avanzados.
   - **Callbacks y Promises** : La asincronía de JS (con setTimeout, async/await) puede ser diícil de entender al principio.
   - **Hoisting** : JS permite usar variables antes de declararlas (porque las declara automáticamente al inicio de la ejecución).
   - Ejemplo clásico de confusión:
     ```javascript
     console.log(x); // undefined
     var x = 10;
     ```

---

## IDEs y Frameworks
- IDEs:
  - Visual Studio Code : Principal editor para desarrollo en JS.
  - WebSotrm : IDE de JetBrains especializado en JS.

- Frameworks:
  - React : Desarrollado por Meta (Facebook) : Creación de interfaces interactivas.
  - Vue.js : Framework progresivo para desarrollo frontend.
  - Angular : Desarrollado por Google → Framework para aplicaciones web escalables.
  - Node.js : Permite usar JS en el lado del servidor.

- Licencias:
  - React : Licencia MIT
  - Vue.js : Licencia MIT
  - Angular : Licencia Apache 2.0
  - Node.js : Licencia MIT

---
Documentación oficial de JavaScript
---

### **Consejos para adaptar o ampliar:**
- Si necesitas meter más info, añade ejemplos reales (por ejemplo, "React fue usado en la web de Instagram").
- Si quieres hacerlo más visual, mete un par de imágenes o capturas de código.
- Si te quedas sin espacio, puedes simplificar algunas partes (como los frameworks).

### **Explicación de los términos:**
- **Licencia** : Una **licencia** define los derechos y restricciones que tienen los usuarios sobre un software o código. En el contexto de programación, las licencias indican si el código es:
  - **Open Source** : El código es público y cualquiera puede modificarlo y redistribuirlo (como la licencia MIT).
  - **Comercial** : Solo puedes usarlo si compras una licencia o pagas una suscripción.
  - **Restrictiva** : Solo puedes usarlo con limitaciones (por ejemplo, sin modificaciones o solo para uso personal).
  - Ejemplo:
     - React.js : Licencia **MIT** (libre para modificar y redistribuir).
     - Windows : Licencia **comercial** (necesitas pargar para usarlo).
     - Django : Licencia **BSD** (open source, pero con algunas limitaciones sobre redistribución).

- **Tipado** : El **tipado** se refiere a cómo un lenguaje maneja los **tipos de datos** (como números, cadenas de texto, booleanos, etc.).
  - **Tipado estático** : El tipo de una variable se define antes de ejecutarla y no puede cambiar.
  - **Tipado dinámico** : El tipo de una variable puede cambiar en tiempo de ejecución.
  - **Tipado fuerte** : No permite mezclar tipos incompatibles (por ejemplo, sumar un número con una cadena).
  - **Tipado débil** : Permite hacer conversiones automáticas (como 1 + "2" → "12").
  - Ejemplo:
     - **Java** : Tipado **estático** y **fuerte**
     - **Python** : Tipado **dinámico** y **fuerte**
     - **JavaScript** : Tipado **dinámico** y **dèbil**

- **Paradigma** : El **paradigma** define el **estilo de programación** o la forma en que se estructura y ejecuta el código. Los principales paradigmas son:
  - **Programación orientada a objetos (OOP)** : Usa clases y objetos para estructurar el código.
  - **Programación funcional** : Usa funciones puras y evita estados globales (ejemplo: map(), reduce() en JS).
  - **Programación procedimental** : El código se estructura en funciones que se ejecutan en orden secuencial.
  - Ejemplo:
     - Java : Principalmente **OOP**
     - Python : **Multiparadigm** (OOP, funcional y procedimental)
     - JavaScript : **Multiparadigma** (OOP basado en prototipos y funcional)
   
- **Ejecución** : La **ejecución** define cómo se interpreta y ejecuta el código en el sistema:
   - **Compilado** : El código se traduce a lenguaje máquina antes de ejecutarse (Java, C++).
   - **Interpretado** : El código se ejecuta directamente línea por línea (Python, JavaScript).
   - **Hibrido** : Mezcla de compilación e interpretación (Java usa una máquina virtual).
   - Ejemplo:
      - Java : Compilado en bytecode y ejecutado en la JVM (híbrido).
      - Python : Interpretado línea por línea.
      - JavaScript : Interpretado (pero los motores modernos usan **JIT (Just-In-Time)** para optimizar).
