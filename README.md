# MATERIA - DESARROLLO DE SISTEMAS WEB ( FRONT END ) 
# AÑO 2026
# COMISION "D"  
# DOCENTE: LUCIANO ARIEL MARTINEZ

## ALUMNO: LUIS OMAR SPECTERMAN  
## PFO1  - Practica Formativa Obligatoria 1 - Indivicual

---

## 📌 Descripcion del Proyecto

Este es un **Trabajo Práctico (TP)** correspondiente a la **Práctica Formativa Obligatoria 1**  .
Se trata de una Landing Page de portafolio personal desarrollada únicamente con **HTML y CSS**, que incluye secciones de presentación personal, proyectos, habilidades, formulario de contacto y películas favoritas.

---

> 🔗 URL REPOSITORIO GITHUB  : *https://github.com/SpectermanLuis/tecnicatura_front_pi01.git*

> 🔗 URL VERCEL : *https://tecnicatura-front-pi01.vercel.app/*


## 📂 Estructura de directorios


```
│ 
├── css
│ 
├──── styles.css   Hoja de estilos
│ 
├── img   ( Imagenes usadas )
│ 
│                                              
├── index.html   
└── README.md # Documentación del proyecto
```

---

## Checklist - Práctica Formativa Obligatoria 1

### Estructura del Proyecto

- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] (Opcional) Carpeta `img` para recursos gráficos. *(Se usaron imágenes externas vía URL)*
- [x] Archivo `README.md` creado, que incluye una breve descripción del TP y este checklist.

---

### Repositorio y Publicación

- [ ] Repositorio en GitHub creado.
- [ ] Proyecto subido al repositorio.
- [ ] Proyecto publicado utilizando VERCEL.
- [ ] En el `README.md` se indica la URL de VERCEL.



---

### Uso de Google Fonts

- [x] Enlace a Google Fonts incluido en la sección `<head>` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] **¿Por qué elegí esa fuente?**

> Se eligió **Syne** para títulos y **DM Sans** para el cuerpo. Syne tiene un carácter geométrico y moderno que transmite energía y creatividad, ideal para un portafolio de desarrollador. DM Sans aporta legibilidad y ligereza al contenido de texto largo, generando un buen contraste tipográfico entre display y cuerpo.

---

### HTML

- [x] El documento inicia con la declaración `DOCTYPE` y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: `charset` y `viewport`.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

**Secciones obligatorias en `main`:**

- [x] Sección `#sobre-mi` con párrafo descriptivo e imagen con atributo `alt`.
- [x] Sección `#tarjetas` con al menos 2 tarjetas con imagen y texto, organizadas con Grid.
- [x] Sección `#habilidades` con tabla y listas de tecnologías y hobbies.
- [x] Sección `#contacto` con formulario (Nombre, Apellido, Email, Teléfono) y botón submit.
- [x] Sección `#peliculas` con 3 películas, cada una con título, imagen y descripción.
- [x] Barra de navegación (`nav`) presente y contiene al menos 3 enlaces.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

---

### CSS

- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.

**Layout y Organización:**

- [x] Se ha organizado el layout (especialmente en la sección `#tarjetas`) utilizando **CSS Grid**.
- [x] **¿Qué ventajas encontré al utilizar Flexbox o Grid?**

> CSS Grid permitió organizar las tarjetas de proyectos y películas en columnas que se adaptan automáticamente al ancho disponible con `auto-fit` y `minmax()`, sin necesidad de media queries complejas. Flexbox se usó para alinear elementos internos de componentes como el header, los cards y el footer, logrando layouts fluidos y centrados con muy poco código.

**Estilización de Componentes:**

- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (`%`, `rem`, `vh`).
- [x] Se ha implementado al menos una animación o transición.
- [x] **¿Qué animación o transición implementé y por qué?**

> Se implementaron dos efectos principales:
> 1. **`@keyframes float`** en el avatar de la sección "Sobre mí": genera un efecto de flotación suave (translateY) que le da vida y personalidad al avatar, siendo el elemento central de la presentación.
> 2. **Hover en tarjetas** (`transform: translateY(-8px)` + `box-shadow` con color acento): comunica interactividad de forma intuitiva. El usuario entiende que esos elementos son clickeables.
> Ambas decisiones fueron elegidas porque refuerzan la identidad visual del sitio sin distraer del contenido.

---

### Consideraciones Adicionales

- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos 
- [x] Se aplicaron buenas prácticas de accesibilidad (atributo `alt` en todas las imágenes, `aria-label` en links del footer, `label` asociados a todos los inputs del formulario).
- [x] Se añadieron comentarios adicionales describiendo decisiones de diseño y mejoras futuras.

### Comentarios varios 
- Se hizo uso de IA en la generacion del avatar que me representa , en la determinacion de las mejores unidades de medida , en acomodar de forma prolija y ordenada la estructura del css y en la redaccion de varios parrafos del presente readme.