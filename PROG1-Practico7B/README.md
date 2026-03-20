## **Práctico n°7B:** Colecciones avanzadas.

En esta segunda parte del trabajo práctico n°7 se profundiza en el uso de colecciones especializadas de Java para optimizar la búsqueda y el almacenamiento de datos únicos, dejando de lado las listas simples para explorar estructuras de clave-valor y conjuntos.

---

### 🛠️ **Tecnologías y conceptos cubiertos.**

* **Uso de hashMap:** Implementación de diccionarios con estructura Clave-Valor (<String, Long>). Gestión de búsquedas eficientes mediante claves únicas. Validación de existencia de datos utilizando el método `.containsKey()` para evitar duplicados accidentales.

* **Uso de hashSet:** Almacenamiento de colecciones de objetos únicos (`HashSet<ComponenteCPU>`) para modelar componentes de hardware.

* **Lógica de costos y negocio:** Cálculo de subtotales y costos totales de producción. Implementación de lógica de precios sugeridos basada en márgenes de ganancia variables según el costo total del producto.

* **Interactividad y menús:** Desarrollo de interfaces de consola con menús de opciones y ciclos de repetición controlados por el usuario.

---

### 🚀 **Algunos de los desafíos destacados.**

* **Agenda telefónica digital:** Un sistema que utiliza un HashMap para gestionar contactos. Permite la carga dinámica de datos, la búsqueda instantánea por nombre y el listado completo de la agenda.
* **Cotizador de computadoras:** Un programa de gestión de hardware que asocia una `Computadora` con sus `ComponenteCPU`. El sistema genera un desglose técnico en formato tabla, calcula el costo total de ensamblaje y determina el precio de venta final aplicando reglas de negocio automáticas.