# 🎯 Juego del Número Secreto

> **Aplicación web interactiva desarrollada con HTML5, CSS3 y JavaScript (ES6) enfocada en lógica de programación y manipulación del DOM.**

---

## 📋 Descripción del Proyecto

El **Juego del Número Secreto** es una aplicación en la que el usuario debe adivinar un número aleatorio entre 1 y 10. La interfaz proporciona retroalimentación dinámica indicando si el número ingresado es mayor o menor al objetivo, gestiona el número de intentos y evita la repetición de números en partidas consecutivas mediante recursividad y arreglos.

---

## 🚀 Funcionalidades Clave

* **Generación Aleatoria sin Repetición:** Algoritmo recursivo que registra números ya sorteados para no repetirlos hasta agotar el rango.
* **Manipulación Dinámica del DOM:** Actualización interactiva de títulos, mensajes de estado y atributos de botones.
* **Validación de Intentos:** Control de estados y habilitación/deshabilitación del botón "Nuevo Juego".
* **Diseño e Interfaz Moderna:** Estilos personalizados con gradientes, tipografías de Google Fonts (`Chakra Petch` e `Inter`) y metodología BEM.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica de la interfaz.
* **CSS3:** Metodología BEM, layout Flexbox y efectos visuales personalizados.
* **JavaScript (ES6):** Funciones, arreglos, condicionales, manipulación del DOM y recursividad.

---


🌐 **Demo en vivo:** [Jugar al Número Secreto](https://baezard.github.io/juego-secreto/)

## 🖼️ Vista Previa

![Vista previa del juego](img/preview.png)

---

## 📂 Estructura del Repositorio

```text
juego-secreto/
│
├── index.html       # Estructura principal de la aplicación
├── style.css        # Hoja de estilos (BEM & Flexbox)
├── app.js           # Lógica del juego en JavaScript
└── img/             # Imágenes y recursos gráficos (ia.png, Ruido.png, code.png, preview.png)