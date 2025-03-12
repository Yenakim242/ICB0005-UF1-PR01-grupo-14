# [Java]
Autor: Yena Kim Choi

## Historia
- **Java** es una lenguaje de programación y una plataforma informática que fue comercializada por primera vez en 1995 por Sun Microsystems.
- Jeva fue desarrollado originalmente por **James Gosling**, de Sun Microsystems (constituida en 1983 y posteriormente adquirida el 27 de enero de 2010 por la compañía Oracle), y publicado en 1995 como un componente fundamental de la plataforma Java de Sun Microsystems.
- El código Java que se proporciona para modificar o personalizar el comportamiento de un nodo JavaCompute se almacena en un proyecto Java.
- Se utiliza ampliamente en muchas industrias, incluidos los servicios financieros, el comercio minorista y la atención médica. Además, se están desarrollando tecnología más nuevas como la inteligencia artificial y la Internet de las cosas utilizando Java. Por lo tanto, es probable que la demanda de desarrolladores de Java siga creciendo en el futuro.

---

## Campo de aplicación
**Aplicaciones móviles y web**
  - Java es uno de los lenguajes preferidos de los desarrolladores de aplicaciones móviles debido a su plataforma estable y su versatilidad.
- **Software empresarial** : El software empresarial está pensado para servir a un grupo o una organización de gran tamaño. Incluye software como sistemas de facturación y programas de administración de cadenas de suministros. La alta escalabilidad de Java lo convierte en un lenguaje atractivo para los desarrollaodres que escriben empresarial.
- **Dispositivos de internet de las cosas (IoT)** : Las aplicaciones de IoT están en todas partes (televisores inteligentes, coches, maquinaria pesada, instalaciones de trabajo, etc.) y Java se usa para programar muchas de ellas.
- **Juegos** : Entre los juegos populares escritos en el lenguaje de programación Java se incluyen los originales Minecraft y RUneScape.
- Ejemplos:
  - **Minecraft**
    - El famoso juego fue desarrollado originalmente en Java por **Markus Persson (Notch)** en **2009**.
    - Todavía utiliza Java como base y se ejecuta en la JVM (Java Virtual Machine).
  - **Spotify** : El backend de la plataforma de música está construido parcialmente en Java para manejar grandes volúmenes de datos y usuarios concurrentes.
  - **Linkedin** : LinkedIn usa Java en el backend para garantizar la escalabilidad y rendimiento con millones de usuarios activos diarios.
  - **Netflix**
    - Netflix usa **Spring Boot** (framework de Java) para construir y escalar su infraestructura de microservicios.
    - Java se usa para manejar la transcodificación de vídeo y recomendaciones personalizads.
  - **Amazon**
    - La mayoría de los sistemas de backend y servicios de AWS (Amazon Web Servicios) están construidos en Java.
    - La máquina virtual de Java (JVM) permite la ejecución en diferentes sistemas operativos sin modificar el código.
- Proyectos cancelados o fallidos
  - **Google Web Toolkit (GWT)**
    - Fue una plataforma creada por Google para desarrollar aplicaciones web usando Java y luego compilarlas a JavaScript.
    - Google dejó de darle soporte debido a la complejidad de mantener la conversión entre Java y JS.
  - **JavaFX**
    - JavaFX fue diseñado para reemplezar Swing como la herramienta principal para crear interfaces gráficas en Java.
    - En 2018, Oracle decidió **separarlo** de la JDK y dejó de darle soporte oficial.
  - **OpenOffice**
    - OpenOffice (una alternativa a Microsoft Office) estaba basado en Java.
    - Fue abandonado debido a problemas de financiación y falta de interés por parte de la comunidad de desarrolladores.
- **Estudios y casos de uso**
  - **Estudio de rendimiento en microservicios**
    - Java es el lenguaje más utilizado para construir **microservicios** debido a frameworks como **Sparing Boot** y **Quarkus**.
    - Los estudios muestran que Java ofrece mejor rendimiento en aplicaciones de microservicios que lenguajes como Python debido a la optimización del compilador JIT (Just-In-Time).
  - **Estudio sobre Machine Learning con Jvav**
    - Aunque Python domina en Machine Learnihg, Java se utiliza en proyectos que requieren **rendimiento** y **concurrencia**.
    - Librerías como **Deeplearning4j** y **Weka** permiten entrenar modelos directamente en Java.
  - **Estudio sobre Big Data**
    - Java es el lenguaje base de tecnologías como **Apache Hadoop** y **Apache Spark**.
    - Gracias a la JVM, estas plataformas pueden procesar grandes volúmenes de datos de manera eficiente.

---

## Tipado, paradigma y Ejecución
### **Tipado de las variables en Java**
Java es un lenguaje:
- **Tipado estático** : El tipo de variables se define en tiempo de compilación y **NO** puede cambiar durante la ejecución.
- **Tipado fuerte** : No permite mezclar tipos incompatibles directamente (si intenteas sumar un número con una cadena, dará error).
- Ejemplo de tipado en Java:
  ```java
  int numero = 5; // Esto es válido
  numero = "Hola"; // Error: No puedes cambiar un int por un String
  ```
  - **Lo bueno** del tipado fuerte es que evita errores en tiempo de ejecución.
  - **Lo malo** es que teines que ser muy preciso al declarar las variables (lo que puede ser más tedioso).
   
### **Paradigmas en Java** 
Java es un lenguaje **multiparadigama** porque permite varios estiolos de programación:
1. **Programación Orientada a Objetos (OOP)** : Es el **paradigma principal** de Java:
- Basado en **clases** y **objetos**.
- Usa conceptos como **herencia**, **polimorfismo** y **encapsulamiento**.
- Ideal para proyectos grandes y escalables.
- Ejemplo:
```java
class Aniaml {
  void hacerSonido() {
    System.out.println("Sonido de animal");
    }
  }

class Perro extends Animal {
  void hacerSonido() {
    System.out.println("Guau Guau");
    }
}
```

2. **Programación Funcional** : Desde Java 8, se agregaron funciones de orden superior (como map(), filter()) y expresiones lambda, lo que permite usar el estilo funcional:
- Funciones son tratadas como objetos.
- Evita estado globales y efectos secundarios.
- Uso de métodos como map(), reduce() y filter().
- Ejemplo:
```java
import java.util.Arrays;

public class Main {
  public static void main(String[] args) {
    Arrays.asList(1, 2, 3, 4)
      .stream()
      .map(x -> x * 2)
      .forEach(System.out::println); // Imprime 2, 4, 6, 8
    }
}
```

3. **Programación Procedimental** : Permite crear funciones o métodos sin necesidad de usar clases u objetos complejos:
- Código estructurado en funciones (como en C).
- Se puede usar para tareas simples y scripts.
- Ejemplo:
```java
public class Main {
  public static void main(String[] args) {
    int resultado = suma(5, 7);
    system.out.println(resultado);
  }

static int suma (int a, int b) {
  return a + b;
  }
}
```
  
### **Ejecución** : Java utiliza un sistema de ejecución **híbrido**:
1. **Compilado** : El código Java(.java) se compila primero a **bytecode**(.class) mediante el compilador javac.
2. **Interpretado** : El bytecode se ejecuta mediante la **Java Virtual Machine(JVM)**, que interpreta y optimiza el código en tiempo de ejecución.
3. **Just-In-Time(JIT)** : La JVM convierte el bytecode a código máquina durante la ejecución para mejorar el rendimiento.
4. Ejemplos de proceso:
   1. Código fuerte : Main.java
   2. Compilación : javac Main.java → Main.class(bytecode)
   3. Ejecución : java Main → La JVM interpreta el bytecode y lo convierte en código máquina.
    - Este enfoque híbrido le da a Java la ventaja de **"write once, run anywhere"** (escribe una vez, ejecuta en cualquier lugar).
    - El código Java se puede ejecutar en cualquier sistema operativo que tenga la JVM instalada. 

---

## Curiosidades
- **Java vs JavaScript** : A diferencia de Java, JavaScript tiene una única función → crear scripts para ejecutar exploradores web. Estos scripts están en Internet. Se usan para juegos basados en explorador, animaciones de páginas web, registro de comportamiento de usuarios y anuncios emergentes, entre otras cosas. Básicamente, todo lo que se actualiza en un sitio web sin que alguien vuelva a cargar la página es probablemenente JavaScript.  

## IDEs y Frameworks
