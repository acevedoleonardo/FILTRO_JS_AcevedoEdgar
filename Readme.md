# Filtro JavaScript 

La empresa CociCampus solicita al desarrollador Full-Stack en crear una aplicación web que permita a los usuarios consultar, buscar, filtrar y gestionar recetas de cocina. 
La aplicación se conectará con la API pública de TheMealDB (https://themealdb.com/) para obtener recetas de forma dinámica. 
Los usuarios podrán crear una lista de recetas favoritas, la cual debe almacenarse de forma persistente (usando localStorage o una API simulada).



La aplicación debe tener una interfaz de usuario intuitiva, interactiva y responsiva que funcione de forma óptima en dispositivos móviles, tablets y computadoras de escritorio. 
Los usuarios podrán buscar recetas por nombre, filtrar por categorías (por ejemplo, "Desayunos", "Postres", etc.) y ver los detalles de cada receta (ingredientes, instrucciones, imagen, video, etc.).



## Especificaciones Generales

## Estructura General

- La aplicación debe contar con una interfaz de usuario amigable y responsiva.
- La aplicación debe mostrar una lista de recetas populares al cargar la página.
- Los usuarios podrán buscar recetas por nombre, filtrar por categoría y ordenar las recetas (por ejemplo, de la A a la Z o viceversa).
- Los usuarios podrán agregar o quitar recetas de su lista de favoritos.

## Gestión de Recetas

Cada receta debe mostrar la siguiente información:

1. Nombre de la receta
2. Imagen de la receta
3. Categoría (por ejemplo, Postre, Desayuno, etc.)
4. Tipo de Comida (por ejemplo, Comida italiana, Comida Mexicana, etc.)
5. Botón para ver los detalles (al hacer clic, se muestra una vista con más información de la receta)

## Funcionalidades Mínimas

- Visualización de Recetas: Mostrar una lista con recetas iniciales obtenidas de la API pública.
- Búsqueda: Permitir a los usuarios buscar recetas por nombre a través de una barra de búsqueda.
- Filtrado: Filtrar las recetas por:
- Categoría (Postres, Comidas Principales, etc.)
- Tipo de Comida (Italiana, Mexicana, etc.)

## Favoritos:

Los usuarios podrán agregar o quitar recetas de favoritos.
Los favoritos se deben almacenar de forma persistente entre sesiones (localStorage o una API simulada).

Vista de Detalle: Al hacer clic en una receta, se debe mostrar una vista de detalles que incluya:

- Imagen en grande
- Nombre de la receta
- Categoría y tipo de comida
- Lista de ingredientes (con cantidades)
- Instrucciones paso a paso
- Video explicativo (si está disponible)

## Almacenamiento de Datos

Los datos de las recetas se obtendrán de la API pública de TheMealDB (https://themealdb.com/).

Los favoritos deben almacenarse de forma persistente, utilizando:

- localStorage (recomendado)
O una API local simulada con JSON Server (opcional).
- Responsividad y Diseño
- El diseño debe ser completamente responsivo (usando Flexbox o Grid Layout).
- La interfaz debe permitir la navegación y la operación desde dispositivos móviles, tablets y computadoras de escritorio.
Validación y UX
- La barra de búsqueda debe ser intuitiva y amigable.
- Mostrar mensajes de error o confirmación al realizar acciones (agregar favoritos, quitar favoritos, etc.).
- Se debe manejar la carga de la API con un loader o indicador de carga mientras se obtienen los datos.
- Estilo y Personalización
- Aplicar una paleta de colores atractiva y adecuada para una aplicación de recetas de cocina.
- Usar transiciones ligeras o animaciones en los elementos interactivos para mejorar la experiencia de usuario.

## Requisitos Técnicos

1. Lenguajes y Herramientas

- HTML (estructura de la página)
- CSS (estilo y diseño responsivo)
- JavaScript (manipulación del DOM, lógica de la aplicación y consumo de la API)
- API Externa
- Usar la API pública de TheMealDB (https://themealdb.com/).
- Consultar la lista de recetas iniciales, así como los detalles de cada receta.
Usar fetch para realizar las solicitudes asíncronas a la API.

## Estructura de Entrega

El estudiante deberá entregar los siguientes archivos:

1. index.html: Página principal con la interfaz de la aplicación.
2. styles.css: Archivo de estilos y diseño de la aplicación.
3. app.js: Archivo de JavaScript con la lógica de la aplicación.

## Desarrollado Por: 

- Edgar Leonardo Acevedo Arteaga 
