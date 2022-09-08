# Proyecto Final -  Outfit

## Integrantes:

- Amarilllo Mateo
- Delgado Leanardo
- Rodriguez Ignacio
- Victoria Luz


## Requerimientos:
1 Objetivo

El documento tiene por objetivo, identificar la funcionalidad del sistema afectada por el proyecto.

Se destaca además, que el documento contiene informaciones fuera de la funcionalidad, que en su conjunto sirven para realizar la valoración, previa necesaria para poder realizar un caso de negocio que permita verificar la viabilidad del proyecto en cuestión.

Documento de Toma de Requerimientos del Sistema Pág. 2 de 4

Versión	Responsable	Fecha	Descripción del cambio
2  Alcance

Crear una aplicación mobile y web que ayude a los diferentes usuarios a crear un buen outfit a partir de la foto de una prenda y las marcas puedan asociarse a la app y mostrar su producto.

2. 1  Actividades incluidas

Se debe dejar claramente definido que actividades se incluyen en la propuesta de solución del proyecto y a que áreas y responsables involucra y alcanza esta solución.

Áreas involucradas:

Usuarios corrientes interesados por la moda o que necesiten ayuda para realizar sus outfits.

Marcas de ropa de cualquier índole que quiera promocionar su producto en la aplicación.

Actividades:

A través de keywords los usuarios van a poder buscar complementos acorde a la foto de la prenda subida.

A través de un sistema de tarjetas, al crear una nueva, se sube una imagen de referencia para que se puedan encontrar los diferentes looks acordes a la foto. Al entrar a cada look, se podrán ver productos de diferentes tiendas, previamente cargados, similares a los vistos en el outfit.

OBLIGATORIOS:

Los usuarios además podrán elegir diferentes estilos (Urbano, Oficina, Casual, entre otras) para que el sistema le brinde un outfit acorde.

Sumar la foto desde la galería y que reconozca las prendas y donde comprarlas.

Sumar carrousel con las tiendas asociadas a la aplicación.

Sumar una sección de tendencias, comunidad y foro sobre estilos de ropa y moda.

Integraremos Google Maps con las tiendas cercanas donde se puedan comprar los diferentes productos.

DESEABLES:
Sumar tu panel de tendencias y outfits donde puedas comentar y dar like a los diferentes looks.

2.2  Actividades identificadas fuera del alcance

No tendremos una solapa dedicadas a tiendas. Las tiendas interesadas en promocionar sus productos, deberán contactarse y subiremos las mismas a la aplicación.

No realizaremos ningún tipo de ventas en la aplicación, si no que simplemente redirigiremos al link de la tienda asociada al mismo.

3  Situación Actual

Actualmente no existe ninguna aplicación que solucione el requerimiento de varios usuarios que necesiten asistencia para realizar o combinar un buen outfit.

4  Requerimientos del cliente (Requisitos)

Que sea una aplicación tanto mobile como web.

5  Requerimientos no funcionales

Conexión a APIS de terceros para la solución de reconocimiento de imágenes y productos.

Log in conectado con Google.

Integrar Google Maps con la aplicación para conocer la ubicación de las diferentes tiendas.

Base de Datos: Usaremos Firebase para la recolección y persistencia de datos.

6 Requisitos Funcionales del Sistema



Resumen de la funcionalidad

A través de Google Cloud Vision AI, los usuarios podrán tomar una foto de una prenda y ser reconocida por la inteligencia artificial a través de un tag. Gracias a ese tag se podrán buscar outfits que se puedan usar con esa prenda y encontrar los locales que vendan productos similares.

Mediante Firebase podremos persistir los datos guardados de las personas para que posteriormente tengan acceso a compartir, comentar y dar like a los diferentes looks.

7 Interfaces con otros sistemas

Sistema de reconocimiento de fotos: Para esta funcionalidad usaremos Google Cloud Vision AI.

Recolección y persistencia de datos: Para esta funcionalidad usaremos Firebase.



