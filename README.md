# Triple Espresso: Página Web de una Cafetería

## ☕ Descripción del Proyecto

Este proyecto es una página web de una sola página (landing page) para **Triple Espresso**, una cafetería de especialidad ubicada en Triple Peaks que ofrece una zona de estudio a sus clientes.
El objetivo es construir, desde cero y a partir de un diseño y un brief, una página completa con tres bloques principales: un encabezado de bienvenida, un formulario de reservación de mesas y un pie de página con información de contacto y redes sociales. La página se desarrolló con HTML semántico y CSS puro, sin frameworks ni librerías, y se publicó con GitHub Pages.

🔗 **Demo:** https://alangudi441.github.io/web_project_coffeeshop_es/

## 💼 Contexto y Objetivo

Una cafetería necesita una presencia en línea que comunique su propuesta (café de especialidad y un espacio para estudiar) y que facilite que los clientes reserven una mesa sin tener que llamar o ir al local.

La página debe resolver tres necesidades:

- Dar la bienvenida y presentar la cafetería: qué ofrece, horarios y dirección.
- Permitir que el cliente reserve una mesa desde un formulario claro, con campos obligatorios y validación básica.
- Facilitar el contacto y la navegación mediante enlaces internos y redes sociales.

El reto técnico fue convertir un diseño visual con medidas, colores y tipografías definidos en un sitio que respete esas especificaciones con la mayor fidelidad posible.

## ⚙️ Habilidades Desarrolladas

#### 🛠️ Herramientas

`HTML5` `CSS3` `Git` `GitHub` `GitHub Pages` `Google Fonts` `Visual Studio Code`

#### HTML

- Estructura semántica (`header`, `nav`, `main`, `section`, `footer`)
- Formularios: `form`, `fieldset`, `legend`, `label`, `input` y `button`
- Tipos de entrada: `text`, `number`, `datetime-local`, `email` y `checkbox`
- Validación nativa del navegador (`required`, `min`, `max`)
- Enlaces internos con anclas (`href="#id"`)
- Accesibilidad básica: textos `alt`, etiquetas asociadas con `for` e `id`

#### CSS

- Selectores de clase y metodología de nombres (BEM en el formulario)
- Modelo de caja y `box-sizing: border-box`
- Posicionamiento: `relative` y `absolute`
- Flexbox para alinear y distribuir elementos
- `z-index` y contextos de apilamiento
- `border-radius` para esquinas redondeadas y círculos
- Estilos personalizados para el `checkbox` con `appearance: none`
- Estilos del marcador de posición con `::placeholder`
- Imágenes de fondo: `background-image`, `background-size: cover`, `background-position`
- Tipografía web con fuentes alternativas
- Estados `:hover` y transiciones con `transition`
- Desplazamiento suave con `scroll-behavior: smooth`

## 🗂️ Estructura del Proyecto

```
web_project_coffeeshop_es/
├── index.html
├── README.md
├── styles/
│   ├── normalize.css
│   └── style.css
└── images/
    └── (logotipos, ilustración, fondos e iconos)
```

## 🧩 Secciones de la Página

1. **Encabezado.** Logotipo, navegación, título principal (`h1`), descripción de bienvenida, ilustración de la cafetería, horario y dirección.
2. **Reservación.** Formulario con nombre, número de comensales, fecha y hora, correo electrónico y aceptación de los términos de uso. Todos los campos son obligatorios.
3. **Pie de página.** Logotipo, enlaces a redes sociales (Facebook e Instagram) y derechos de autor.
4. **Interactividad.** Estados `hover` en la navegación, el botón del formulario y los enlaces del pie de página.

## 📈 Aspectos Destacados del Proyecto

- Maquetación fiel a un diseño con medidas, colores y tipografías definidos.
- Formulario con validación nativa y campos obligatorios, sin necesidad de JavaScript.
- Checkbox personalizado con estado marcado propio.
- Navegación interna con desplazamiento suave.
- Código organizado por secciones, con nombres de clase consistentes.
- Sitio publicado y accesible en línea.

## 📈 Resultados

- Una página completa de tres secciones, funcional y publicada en GitHub Pages.
- Formulario que impide el envío si algún campo está vacío o el correo no es válido.
- Enlaces del menú que llevan a su sección correspondiente.
- Estados `hover` con transiciones suaves en todos los elementos clicables.

## ▶️ Cómo Ejecutar el Proyecto

1. Clona este repositorio: `git clone https://github.com/Alangudi441/web_project_coffeeshop_es`
2. Entra a la carpeta del proyecto: `cd web_project_coffeeshop_es`
3. Abre el archivo `index.html` en tu navegador (doble clic), o usa la extensión **Live Server** de Visual Studio Code para ver los cambios en tiempo real.

No se necesita instalar dependencias.
