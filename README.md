
---

# Proyecto de Películas

https://youtu.be/usRPJw4rcBs
## Introducción

Este proyecto es una aplicación web diseñada para gestionar una base de datos de películas. Los usuarios pueden ver, agregar, editar y eliminar entradas de películas. El proyecto fue desarrollado como Trabajo Final para CAC, utilizando PHP 8 y MySQL, y la interfaz front-end está construida con HTML y CSS.

## Desarrolladora

Desarrollado por Gime Gil Fernández.

## Características

- **Ver Películas**: Muestra una lista de películas con detalles que incluyen nombre, descripción, género y póster.
- **Agregar Película**: Añade una nueva película a la base de datos.
- **Editar Película**: Edita los detalles de una película existente.
- **Eliminar Película**: Elimina una película de la base de datos.

## Tecnologías Utilizadas

- **PHP 8**: Lenguaje de scripting del lado del servidor utilizado para manejar la lógica del backend.
- **MySQL**: Sistema de gestión de bases de datos utilizado para almacenar los datos de las películas.
- **HTML/CSS**: Lenguajes de marcado y estilo para la interfaz front-end.

## Configuración e Instalación

1. **Clonar el repositorio**:
   ```bash
   git clone <repository_url>
   ```

2. **Navegar al directorio del proyecto**:
   ```bash
   cd movie-database
   ```

3. **Configuración de la base de datos**:
   - Crear una base de datos MySQL.
   - Importar el archivo SQL proporcionado para configurar las tablas necesarias:
     ```sql
     CREATE DATABASE movie_db;
     USE movie_db;
     SOURCE path/to/your/database.sql;
     ```

4. **Configuración**:
   - Actualizar la configuración de la base de datos en `config.php`:
     ```php
     <?php
     $host = 'localhost';
     $db = 'movie_db';
     $user = 'tu_usuario';
     $pass = 'tu_contraseña';
     ```

5. **Ejecutar la Aplicación**:
   - Iniciar tu servidor local (por ejemplo, utilizando XAMPP o MAMP).
   - Abrir un navegador web y navegar a `http://localhost/Peliculas/index.php`.

## Uso

- **Ver Películas**: La página principal muestra una lista de películas. Cada entrada de película muestra el nombre, descripción, género y póster.
- **Agregar una Película**: Hacer clic en el botón "Nuevo registro" y completar el formulario para agregar una nueva película.
- **Editar una Película**: Hacer clic en el botón "Editar" junto a una entrada de película para actualizar sus detalles.
- **Eliminar una Película**: Hacer clic en el botón "Eliminar" junto a una entrada de película para eliminarla de la base de datos.

---
