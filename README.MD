# Talleres Moises

Proyecto de la asignatura **Desarrollo de Interfaces (2º DAM)**, UD1. Temática: **Taller Mecánico de Vehículos**.

Web corporativa de un taller de reparación de vehículos con catálogo de revisiones, tarifas orientativas y formulario de cita previa. La segunda parte del proyecto será una aplicación web (SPA) para controlar el flujo de reparaciones de los clientes.

## Integrantes

| Integrante   | Página                                  |
|--------------|-----------------------------------------|
| Jose Manuel  | [PENDIENTE]                             |
| Carmen       | Reserva de cita (formulario)            |
| Javier       | [PENDIENTE]                             |
| Moises       | [PENDIENTE]                             |

Páginas del sitio: Landing page (inicio), Reserva de cita, Servicios y tarifas, Equipo y contacto.

## Enlaces

- **Repositorio GitHub:** [PENDIENTE]
- **Alojamiento web:** [PENDIENTE]

## Tecnologías

- HTML5, CSS3 y JavaScript
- Bootstrap 5 e iconos de Bootstrap Icons
- Paleta de colores creada con Paletton
- Tipografías locales en formato WOFF (carpeta `fonts/`): Oswald, Roboto y Montserrat
- Segunda parte: PHP y MySQL

## Estructura del proyecto

```
nombreProyecto/
├── css/
│   └── estilos.css
├── js/
│   ├── ajax.js
│   ├── objetos.js
│   └── codigo.js
├── php/
│   └── config.php
├── sql/
│   ├── backup.sql
│   └── imagen_diagrama_E-R
├── index.html
└── README.MD
```

## Base de datos (segunda parte)

Modelo con cuatro tablas relacionadas 1:N:

`Clientes` → `Vehículos` → `Órdenes` → `Intervenciones`

- **Base de datos:** [PENDIENTE]
- **Usuario:** [PENDIENTE]
- **Password:** [PENDIENTE]

## Ejecución

1. Clonar el repositorio.
2. Servir la carpeta con Apache o similar (XAMPP, Laragon…).
3. Importar `sql/backup.sql` en MySQL (segunda parte).
4. Abrir `index.html` en el navegador.
