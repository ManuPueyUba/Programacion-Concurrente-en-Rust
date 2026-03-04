# Programación Concurrente en Rust

## Sobre este Proyecto

Este repositorio contiene mis apuntes teóricos y desarrollos prácticos realizados en el marco de la materia:

**Programación Concurrente (TB026)**  
Facultad de Ingeniería – Universidad de Buenos Aires (FIUBA)


[Link a la pagina de la catedra](https://concurrentes-fiuba.github.io/clases.html)

[Ejemplos](https://github.com/concurrentes-fiuba/ejemplos-concurrentes)



## 🎓 Contexto académico

- **Materia:** Programación Concurrente  
- **Código:** TB026  
- **Institución:** Facultad de Ingeniería – Universidad de Buenos Aires (FIUBA)


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