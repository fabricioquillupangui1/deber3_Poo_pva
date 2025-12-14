📘 Programación Orientada a Objetos (POO)
Conceptos Fundamentales: Clases, Objetos y los 4 Pilares

Este documento presenta una explicación clara y estructurada de la Programación Orientada a Objetos (POO), uno de los paradigmas más importantes en el desarrollo de software.
Incluye fundamentos teóricos, ejemplos prácticos en Kotlin (Android Studio) y ejercicios aplicados con Jetpack Compose, integrando lógica y diseño de interfaces gráficas.

🧠 Proceso de Pensamiento para Modelar con Objetos

La Programación Orientada a Objetos nos permite construir software modelando el mundo real.
Este proceso lógico facilita transformar un problema en una solución estructurada, modular y reutilizable.

🔑 Pasos Clave para el Modelado

Paso 1 – Identificación de Entidades
Determinar las “cosas” importantes del problema (Clases).
Ejemplo: Identificar la clase Estudiante.

Paso 2 – Definición de Atributos
Describir las características que definen a la entidad.
Ejemplo: nombre, edad, carrera.

Paso 3 – Definición de Comportamiento
Establecer las acciones que puede realizar la entidad (Métodos).
Ejemplo: inscribirse(), presentarExamen().

Paso 4 – Establecimiento de Relaciones
Definir cómo interactúan las clases entre sí (Herencia, Composición, Asociación).
Ejemplo: Estudiante se relaciona con Curso.

🧱 Clases y Objetos
📐 Clase: El Plano

Una Clase es una definición abstracta que actúa como una plantilla o molde.
Define la estructura (atributos) y el comportamiento (métodos) de los objetos.
No ocupa memoria hasta que se crea una instancia.

🧩 Objeto: La Instancia

Un Objeto es una instancia concreta de una clase.
Representa una entidad real en memoria con valores específicos para sus atributos.

Analogía:
La clase MoldeDeGalletas es la plantilla, mientras que miGalleta es la galleta real creada a partir de ese molde.

🛡️ Los 4 Pilares Fundamentales de la POO

Estos principios son la base para el diseño de software robusto, flexible y mantenible.

1️⃣ Encapsulamiento

Agrupa datos y métodos en una sola unidad y restringe el acceso directo a los datos internos.
La interacción se realiza únicamente a través de métodos públicos, protegiendo la información.

Ejemplo conceptual:
Datos seguros dentro de una “caja fuerte”.

2️⃣ Abstracción

Muestra solo la funcionalidad esencial al usuario y oculta los detalles complejos de implementación.
Permite interactuar con los objetos a un alto nivel.

Ejemplo conceptual:
Usar un televisor sin conocer cómo funciona internamente.

3️⃣ Herencia

Permite que una clase hija reutilice, extienda o modifique atributos y métodos de una clase padre.
Establece una relación “Es un” y promueve la reutilización del código.

Ejemplo conceptual:
Una clase hija hereda características de una clase padre.

4️⃣ Polimorfismo

Permite que un mismo método tenga diferentes comportamientos según la clase que lo implemente.
Significa “muchas formas” y brinda flexibilidad al diseño del software.

Ejemplo conceptual:
El método dibujar() se comporta de manera distinta según la figura.

🎯 Ejemplos Prácticos de POO (Kotlin – Android Studio)
📚 Ejemplo 1: Sistema de Gestión de Biblioteca

Herencia, Encapsulamiento y Abstracción

Se modela un sistema de biblioteca utilizando una clase base abstracta y clases hijas que heredan su comportamiento común.
El estado de disponibilidad se encuentra protegido mediante encapsulamiento.

Incluye:

Clase abstracta base

Atributos privados

Métodos públicos de acceso

Herencia y sobrescritura de métodos

📐 Ejemplo 2: Cálculo de Áreas de Figuras Geométricas

Abstracción y Polimorfismo

Se implementa una interfaz que define un contrato común para todas las figuras geométricas.
Cada figura calcula su área de manera diferente, demostrando el polimorfismo.

Incluye:

Interfaz común

Implementaciones específicas

Uso de listas de objetos

Ejecución polimórfica de métodos

🚀 Ejercicios Prácticos con Programación Orientada a Objetos
🏦 Ejercicio 1: Sistema Bancario

Abstracción, Encapsulamiento y Polimorfismo

Se desarrolla un sistema bancario que permite:

Crear clientes

Gestionar cuentas corrientes y de ahorros

Realizar depósitos y retiros

Cambiar dinámicamente el tipo de cuenta

Visualizar resultados mediante una interfaz gráfica

Tecnologías utilizadas:

Kotlin

Android Studio

Jetpack Compose

Arquitectura orientada a objetos

💼 Ejercicio 2: Gestión de Empleados

Herencia y Polimorfismo en el cálculo del salario

Se implementa un sistema para gestionar empleados con diferentes tipos de contratación:

Empleado fijo

Empleado por hora

Características principales:

Uso de clase abstracta base

Implementación de herencia

Cálculo polimórfico del salario

Interfaz gráfica dinámica con Jetpack Compose

📌 Conclusión

La Programación Orientada a Objetos permite:

Modelar problemas reales de forma natural

Reutilizar código eficientemente

Construir sistemas escalables y mantenibles

Este material combina teoría, ejemplos prácticos y ejercicios reales, facilitando el aprendizaje progresivo y sólido de la POO aplicada al desarrollo Android.

📎 Ejercicios prácticos y README
