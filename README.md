# API MCU
![movie](https://static1.cbrimages.com/wordpress/wp-content/uploads/2019/05/Heroes-Of-The-MCU.jpg)

## Descripción

Este proyecto se centra en la creación de una plataforma de reseñas de películas, proporcionando a los usuarios información detallada sobre películas del MCU de Marvel, incluyendo detalles como nombre, año, género, imagen, director, sinopsis y rating. La implementación incluye una API robusta y una interfaz de usuario desarrollada en React.

## CORE MVC

1. **Implementación de Principios SOLID:**

   Con el objetivo de mejorar la mantenibilidad y extensibilidad del código, se ha aplicado el Principio de Responsabilidad Única (SRP), dividiendo la lógica de la aplicación en clases más pequeñas y específicas.

2. **Aplicación del Patrón de Diseño Prototype:**

   Para mejorar la creación y manejo de objetos, se ha implementado el patrón de diseño Prototype. Esto facilita la creación de copias de películas existentes con diferentes valores, mejorando la eficiencia en la gestión de recursos.

## Funcionalidad de la API

La API Movie Review ofrece las siguientes funcionalidades:

- Operaciones básicas de CRUD (Crear, Leer, Actualizar, Borrar).
- Búsqueda y filtrado avanzados según criterios como género, año de lanzamiento o director.
- Sistema de valoración que permite a los usuarios calificar las películas, contribuyendo a la creación de un sistema de recomendación basado en la puntuación de los usuarios.

## Framework JS para Consumir la API

Se ha seleccionado React como el framework JavaScript para consumir la API. Algunas razones para esta elección incluyen:

- **Virtual DOM:** React utiliza un Virtual DOM para optimizar las actualizaciones y renderizaciones, mejorando la eficiencia y el rendimiento.
  
- **Reutilización de Componentes:** React fomenta la creación de componentes reutilizables, facilitando el desarrollo ágil y modular.

- **Amplia Comunidad y Ecosistema:** React cuenta con una gran comunidad de desarrolladores y una amplia gama de bibliotecas y herramientas que facilitan el desarrollo de aplicaciones web complejas.

- **React Hooks:** La introducción de hooks en React simplifica la gestión del estado y el ciclo de vida de los componentes, mejorando la legibilidad y mantenibilidad del código.

## Instrucciones de Ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tuusuario/movie-review.git
2. Instala las dependencias
   ```bash
   cd movie-review
   npm install

