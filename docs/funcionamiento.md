
# Funcionamiento de la aplicación

Esta guía explica cómo se usa la aplicación de gestión del videoclub.

## Rutas principales

| Ruta | Método | Descripción |
|------|--------|-------------|
| `/peliculas` | GET | Listado de películas |
| `/peliculas/create` | GET | Formulario para añadir una película |
| `/peliculas` | POST | Guarda la nueva película |

## Listado de películas

En `/peliculas` se muestran todas las películas del catálogo. Desde esta pantalla se puede:

- Buscar una película por título.
- Filtrar las películas por género.

## Alta de películas

1. Pulsa el botón para añadir una película, que lleva a `/peliculas/create`.
2. Rellena los campos del formulario: título, género, año y sinopsis.
3. Pulsa el botón de enviar.
4. La película se guarda y aparece en el listado.
