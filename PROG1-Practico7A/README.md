## **Práctico n°7A:** Colecciones con asociación.

En esta primera parte del trabajo práctico n°7 se introduce el concepto de asociación entre objetos, donde una clase "padre" contiene una colección (como un ArrayList) de otros objetos, permitiendo modelar relaciones del mundo real como "Un alumno tiene muchas notas" o "Un plato tiene muchos ingredientes".

---

### 🛠️ **Tecnologías y conceptos cubiertos.**

* **Colecciones dinámicas:** Uso intensivo de `ArrayList<T>` para manejar conjuntos de objetos cuyo tamaño no es fijo. 
* **Asociación de clases:** Implementación de relaciones 1:N (uno a muchos) mediante atributos que son listas de otros objetos. 
* **Lógica de negocio y validación:** Carga de datos anidada (bucles dentro de bucles para cargar "N alumnos" y "N notas"). Validación de entrada obligatoria (ej. un plato no bebida debe tener al menos un ingrediente). 
* **Cálculos sobre colecciones:** Implementación de métodos para procesar datos internos de la lista, como el cálculo de promedios de notas.

---

### 🚀 **Algunos de los desafíos destacados.**

* **Gestión Educativa (Carga de notas):** Modelado de la relación entre Alumno y Nota. El sistema debe calcular automáticamente el promedio de cada estudiante tras la carga de sus exámenes. 

* **Sistema Gastronómico (Menú de restaurant):** Modelado de la relación entre Plato e Ingrediente. Incluye lógica condicional: si el ítem es una "Bebida", el sistema omite la solicitud de ingredientes. 