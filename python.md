# Python
Autor: Yena Kim Choi

## Historia
Python fue creado por **Guido van Rossum** y su primera versión se lanzó en **1991**.
- Inspirado en el lenguaje ABC (un lenguaje educativo)
- Nombre inspirado por el grupo de comedia "Monty Python"
- Enfocado en la simplicidad y la legibilidad del código
- Python es **open source** y mantenido por la **Python Software Foundation**

---

## Campo de aplicación
Python se usa ampliamente en:
- **Desarrollo web** : Frameworks como Django y Flask
- **Análisis de datos** : Librerías como Pandas y NumPy
- **Inteligencia artificial y Machine Learning** : TensorFlow y Scikit-learn
- **Automatización** : Scripts de automatización de tareas
- **Desarrollo de videojuegos** : Pygame

(Ejemplo)
- YouTube y Dropbbox están escritos parcialmente en Python
- Instagram usa Django (que está basado en Python)

---

## Tipado, paradigma y Ejecuciónn
- **Tipado:**
    - Tipado **dinámico** : No necesitas definir el tipo de una variable antes de usarla.
    - Tipado **fuerte** : No puedes mezclar tipos incompatibles directamente (por ejemplo, sumar una cadena con un número).
    
- **Paradigma:**
    - **Orientado a objetos (OOP)**
    - **Funcional** (permite usar funciones de orden superior)
    - **Procedimental** (permite estructurar código en funciones)
  
- **Ejecución:**
    - **Interpretado** : No necesitas compilar el código de ejecutarlo.

## Curiosidad sobre Python
- **Python en IA** : Python es el lenguaje más utilizado en inteligencia artificial gracias a su facilidad para manejar datos y el ecosistema de librerías especializadas como **TensorFlow**, **PyTorch** y **Scikit-earn**. Grandes modelos de lenguaje como **ChatGPT** y **DeepSeek** están desarrollados principalmente en Python debido a su eficiencia para entrenar y manejar redes neuronales complejas.
- **Análisis de datos vs Data Science** : Python se ha convertido en el estándar para análisis de datos y ciencia de datos. En análisis de datos, se usan librerías como **Pandas** y **NumPy** para manipular y visualizar datos. En ciencia de datos, librerías como **TrensorFlow** y **Scikit-learn** permiten construir modelos predictivos y de machine learning. La diferencia principal es que el análisis de datos busca entender paratones existentes, mientras que la ciencia de datos busca crear nuevos modelos predictivos.
- **Python vs Java** : Python domina en el campo de la inteligencia artificial y el análisis de datos debido a su rapidez para prototipar y su ecosistema de librerías. Sin embargo, Java sigue siendo el rey en aplicaciones empresariales, sistema de alto rendimiento y desarrollo móvil (Android). Un desarrollador de Python suele centrarse en IA y ciencia de datos, mientras que un desarrollador de Java se especializa en aplicaciones empresariales y sistemas escalables.

---

## IDEs y Frameworks
- **IDEs:**
    - **PyCharm** : Creado por JetBrains
    - **VS Code** : Soporte para Python a través de extensiones
- **Frameworks:**
    - **Django** : Framework completo para desarrollo web
    - **Flask ** : Framework ligero para desarrollo web
    - **TensorFlow** : Framework para Machine Learning
- **Licencias:**
    - Python : Licencias **PSF** (Python Software Foundation License)
    - Django : Licencia **BSD**
    - TensorFlow : Licencia **Apache 2.0**

---

### **Explicación de los términos**
- **Campo de aplicación** : ¿Para qué se usa principalmente el lenguaje? (Desarrollo web, IA, videojuegos, etc.)
- **Tipado** : Si las variables son **dinámicas** (puedes cambiar el tipado sobre la marcha) o **estáticas (siempre tiene que tener el mismo tipo).
- **Paradigma** : El "estilo" de programación:
    - **OOP (Programación orientada a objetos)** : Clases y objetos.
    - **Funcional** : Usa funciones puras (sin efectos secundarios).
    - **Procedimental** : Usa funciones como bloques de código reutilizable.
- **Ejecución** : Si el código necesita compilarse (como en Java) o si se ejecuta directamente (como en Python).
- **IDEs** : Programas donde puedes escribir y ejecutar código (VS Code, PyCharm...).
- **Frameworks** : Conjunto de herramientas que facilitan la programación (Django para desarrollo web, TensorFlow para IA...).


(Ejemplo de tipado dinámico)
```python
x=10 #Esto es un entero  
x="Hola" # Ahora es una cadena: Python permite este cambio dinámico  
