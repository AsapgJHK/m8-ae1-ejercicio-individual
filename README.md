# 📚 Documentación Teórica de la Arquitectura REST

## 📝 Resumen del Trabajo

Este documento recoge y presenta las respuestas detalladas a un cuestionario teórico enfocado en la arquitectura **REST (Representational State Transfer)** y su aplicación en el diseño de **APIs Web**. El objetivo del trabajo fue consolidar la comprensión de los principios fundamentales de REST, sus ventajas y su correcta implementación práctica utilizando el protocolo HTTP.

---

## 🏛️ Conceptos Clave Abarcados

El trabajo cubre las siguientes áreas fundamentales de la arquitectura RESTful:

* **Definición de REST:** Significado del acrónimo, propósito y contexto de uso (APIs Web y HTTP).
* **Restricciones Arquitectónicas:**
    * **Sin Estado (**Stateless**):** Implicaciones de la independencia de las peticiones.
    * **Interfaz Uniforme:** La importancia de usar URIs y códigos de estado estandarizados.
    * **Separación Cliente-Servidor** y **Sistema de Capas**.
* **Ventajas y Desventajas:** Análisis del *trade-off* entre escalabilidad y la gestión de estado.
* **Prácticas de Diseño:**
    * Uso de **Verbos HTTP** (GET, POST, PUT, PATCH, DELETE) en relación con las operaciones CRUD.
    * **Nomenclatura de Recursos** (uso de sustantivos en plural).
    * Uso de **Códigos de Estado HTTP** (2xx, 4xx, 5xx) para comunicar resultados.
* **Conceptos Avanzados:** Introducción al **Versionamiento de APIs** y **HATEOAS**.

---

## 🔍 Estructura del Documento (Resumen de Preguntas)

El trabajo individual está estructurado como una serie de preguntas y respuestas. Los puntos cubiertos son:

1.  **Definición y Propósito de REST.**
2.  **Características Principales de una API RESTful.**
3.  **Ventajas y Desventajas.**
4.  **Explicación de la Interfaz Uniforme.**
5.  **Significado de Peticiones "Sin Estado" (Stateless).**
6.  **Separación entre Cliente y Servidor.**
7.  **Función del Sistema de Capas.**
8.  **Importancia y Formas de Versionamiento de APIs.**
9.  **Uso de Verbos HTTP (GET, POST, PUT, PATCH, DELETE).**
10. **Buenas Prácticas para Nombrar Recursos.**
11. **Función de los Códigos de Estado HTTP.**
12. **Formato de Salida Común (JSON).**
13. **Búsqueda y Filtrado (Query Params).**
14. **Concepto y Valor de HATEOAS.**

---

## 💡 Conclusión

El estudio confirma que **REST** es un estilo arquitectónico robusto y flexible para la construcción de sistemas distribuidos, basado en la **explotación coherente del protocolo HTTP**. La adherencia a sus restricciones es fundamental para garantizar la **escalabilidad**, la **simplicidad** y la **interoperabilidad** de los servicios web modernos.
