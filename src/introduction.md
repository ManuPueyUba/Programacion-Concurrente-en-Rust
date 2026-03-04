# Programación Concurrente en Rust  

Link a la pagina de la catedra: 
https://concurrentes-fiuba.github.io/clases.html

Ejemplos: 
https://github.com/concurrentes-fiuba/ejemplos-concurrentes

## De Threads a Sistemas Distribuidos

Este repositorio contiene mis apuntes teóricos y desarrollos prácticos realizados en el marco de la materia:

**Programación Concurrente (TB026)**  
Facultad de Ingeniería – Universidad de Buenos Aires (FIUBA)

---

## 📘 Sobre este proyecto

Este proyecto documenta un estudio integral de **concurrencia y sistemas distribuidos**, utilizando **Rust** como lenguaje principal de implementación.

El objetivo es integrar:

- Modelos formales de concurrencia
- Algoritmos clásicos de sincronización
- Programación sobre memoria compartida
- Pasaje de mensajes
- Sistemas distribuidos
- Implementaciones reales con análisis técnico

Cada tema combina teoría rigurosa con código funcional en Rust.

---

## 🎓 Contexto académico

- **Materia:** Programación Concurrente  
- **Código:** TB026  
- **Institución:** Facultad de Ingeniería – Universidad de Buenos Aires (FIUBA)

El programa incluye:

- Modelo Fork-Join
- Programación asincrónica
- Secciones críticas y exclusión mutua
- Locks, semáforos, barreras y monitores
- Redes de Petri
- Pasaje de mensajes y modelo de actores
- Algoritmos de exclusión mutua distribuida
- Algoritmos de elección
- Transacciones distribuidas y deadlocks
- Ambientes distribuidos

---

## 🦀 ¿Por qué Rust?

Rust fue elegido porque:

- Garantiza seguridad de memoria sin garbage collector
- Previene data races en tiempo de compilación
- Posee primitivas modernas de concurrencia
- Es adecuado para programación de sistemas y redes

Este proyecto analiza cómo el modelo de ownership y borrowing de Rust interactúa con los modelos clásicos de concurrencia.

---

## 🧠 Organización

El contenido está organizado semana a semana siguiendo el cronograma oficial de la materia, con una estructura 50% teórica y 50% práctica, con énfasis en implementación.

Cada unidad incluye:

- Definiciones formales
- Propiedades de correctitud (Safety y Liveness)
- Algoritmos clásicos
- Discusión de complejidad
- Implementaciones en Rust
- Análisis de comportamiento en memoria
- Consideraciones de rendimiento

---

## 🛠 Tecnologías utilizadas

- Rust
- mdBook
- Git
- Entorno Linux (WSL)

---

## 🎯 Objetivo

Construir una referencia técnica estructurada sobre concurrencia y sistemas distribuidos en Rust, combinando rigor académico con implementación práctica.

---

# Instalación y ejecución del proyecto

## 📥 Requisitos previos

Este proyecto utiliza:

- Git
- Rust (incluye Cargo)
- mdBook

1. Instalar Git:
   ```bash
   sudo apt-get update
   sudo apt-get install git
   git --version
    ```
2. Instalar Rust y Cargo:
   ```bash
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    ```
3. Reiniciar la terminal o cargar el entorno de Rust:
   ```bash
   source $HOME/.cargo/env
    ```

3. Verificar la instalación:
   ```bash
   rustc --version
   cargo --version
    ```
4. Instalar mdBook:
   ```bash
   cargo install mdbook
   mdbook --version
    ```

5. Instalar mdbook-mermaid para diagramas:
   ```bash
   cargo install mdbook-mermaid
   mdbook-mermaid --version
    ```

6. Instalar mdbook-mermaid:
   ```bash
   mdbook-mermaid install
    ```

## Ejecucion del proyecto
1. Clonar el repositorio:
   ```bash
   git clone git@github.com:ManuPueyUba/Programacion-Concurrente-en-Rust.git
    ```
2. Navegar al directorio del proyecto:
   ```bash
    cd Programacion-Concurrente-en-Rust
    ```

3. Ejecutar en modo desarrollo
   ```bash
   mdbook serve
   ```
4. Abrir el navegador en `http://localhost:3000` para acceder al contenido.


## Autor

Manuel Pueyrredón  
Estudiante de Ingeniería Informática  
Facultad de Ingeniería – Universidad de Buenos Aires
