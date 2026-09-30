# **Elementos de Scalar que pueden ser modificados**

## **Lista de elementos modificables**

### Variables base (Colores y Fondos)

Estas variables se aplican en clases como .light-mode o .dark-mode:

- **--scalar-color-1:** Define el color del texto principal o encabezados primarios.
   - Acepta valores de color CSS (hexadecimal, rgb(), rgba(), hsl()).

- **--scalar-color-2:** Controla el color del texto secundario (subtítulos, descripciones).
   - Acepta valores de color CSS (usualmente con transparencia o tono medio).

- **--scalar-color-3:** Se usa para texto terciario o de menor contraste (placeholders, etiquetas de menor importancia).
   - Acepta valores de color CSS.

- **--scalar-color-accent:** Define el color de acento principal utilizado en enlaces, botones de acción o elementos destacados.
   - Acepta valores de color CSS.

- **--scalar-background-1:** Establece el color de fondo principal de la aplicación o del lienzo de contenido.
   - Acepta valores de color CSS.

- **--scalar-background-2:** Fondo para contenedores secundarios, bloques de código o tarjetas.
   - Acepta valores de color CSS.

- **--scalar-background-3:** Fondo para elementos terciarios de la UI como paneles desplegables o tooltips.
   - Acepta valores de color CSS.

- **--scalar-background-accent:** Color de fondo ligero para áreas destacadas asociadas al color de acento.
   - Acepta valores de color CSS (a menudo con transparencia/alfa).

- **--scalar-border-color:** Define el color de las líneas divisorias y bordes de la UI.
   - Acepta valores de color CSS.

### Variables de la Barra Lateral (Sidebar)
Estas variables se aplican dentro del contenedor .sidebar tanto en modo claro como en modo oscuro:

- **--scalar-sidebar-background-1:** Define el fondo de la barra lateral de navegación.
   - Acepta valores de color CSS (o referencias como var(--scalar-background-1)).

- **--scalar-sidebar-item-hover-color:** Color del texto de un elemento del menú al pasar el cursor sobre él.
   - Acepta valores de color CSS o palabras clave como currentColor.

- **--scalar-sidebar-item-hover-background:** Color de fondo al pasar el cursor sobre un ítem del menú.
   - Acepta valores de color CSS.

- **--scalar-sidebar-item-active-background:** Color de fondo del ítem o endpoint activo actualmente seleccionado.
   - Acepta valores de color CSS.

- **--scalar-sidebar-border-color:** Color del borde o línea divisoria de la barra lateral.
   - Acepta valores de color CSS.

- **--scalar-sidebar-color-1:** Color principal del texto para los títulos de navegación.
   - Acepta valores de color CSS.

- **--scalar-sidebar-color-2:** Color secundario del texto para sub-elementos o rutas HTTP en el menú.
   - Acepta valores de color CSS.

- **--scalar-sidebar-color-active:** Color del texto para el elemento activo de la barra lateral.
   - Acepta valores de color CSS.

- **--scalar-sidebar-search-background:** Color de fondo del campo de búsqueda ubicado en la barra lateral.
   - Acepta valores de color CSS.

- **--scalar-sidebar-search-border-color:** Color del borde del input de búsqueda.
   - Acepta valores de color CSS.

- **--scalar-sidebar-search-color:** Color del texto o placeholder dentro del input de búsqueda.
   - Acepta valores de color CSS.

## **Referencias visuales**
***Interfaz general:***
<img width="1940" height="934" alt="Scalar_elementos_1" src="https://github.com/user-attachments/assets/dcde9c3e-9165-4dc4-bd23-dbc739753352" />
***Sidebar:***
<img width="1940" height="934" alt="Scalar_elementos_2" src="https://github.com/user-attachments/assets/b98b91af-fc68-4d8f-b619-e880b6ea1160" />
