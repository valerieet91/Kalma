# KÁLMA | Tienda de Ropa y Estilo

Proyecto práctico desarrollado para la asignatura de **Seminario (Ingeniería de Software)** en la **Fundación Escuela Tecnológica de Neiva "Jesús Oviedo Pérez" (FET)**.

* **Estudiante:** Valerie Trujillo Ospina
* **Tecnologías:** HTML5 semántico, Tailwind CSS v4 (Play CDN), JavaScript Vanilla.

---

### 1. Fase de Planificación y Diseño UX/UI

- **Temática:** KÁLMA, una tienda de ropa enfocada en prendas frescas, cómodas y elaboradas en lino y algodón.

- **Público objetivo:** Personas de Neiva y Colombia interesadas en ropa versátil, de calidad y adecuada para climas cálidos.

- **Objetivo del sitio:** Presentar el catálogo de productos, destacar la identidad de la marca y facilitar el contacto con los clientes mediante formularios y canales de atención.

- **Paleta de colores:**
  - Color principal: #F7F3EC (tono arena inspirado en fibras naturales).
  - Color secundario: #2F3E46 (gris oscuro para generar contraste).
  - Color de acento: #C2410C (terracota para botones y elementos destacados).
  - Colores semánticos:
    - Éxito: #15803D
    - Error: #B91C1C
    - Advertencia: #B45309

- **Tipografía:**
  - Lora para títulos.
  - Nunito Sans para textos y contenido general.

- **Experiencia de usuario:**
  - Diseño responsive para móviles, tabletas y computadores.
  - Navegación sencilla mediante menú principal.
  - Modo oscuro para mejorar la experiencia visual.
  - Formularios con validación para evitar errores de entrada.

---

### 2. Prompt Maestro Utilizado

#### 1. Rol
Actúa como desarrollador frontend especializado en HTML5, Tailwind CSS v4 y JavaScript. Debes aplicar principios básicos de diseño responsive, accesibilidad web y buenas prácticas de interfaz de usuario.

#### 2. Contexto
Voy a desarrollar una landing page para "KÁLMA | Tienda de Ropa y Estilo", una marca de ropa ubicada en Neiva especializada en prendas de lino y algodón. El sitio está dirigido a personas que buscan ropa cómoda, fresca y versátil para el uso diario.

La identidad visual debe inspirarse en materiales naturales y transmitir elegancia, comodidad y simplicidad.

Paleta de colores:

- Color dominante (60%): #F7F3EC (arena/lino cálido).
- Color secundario (30%): #2F3E46 (gris pizarra).
- Color de acento (10%): #C2410C (terracota).
- Éxito: #15803D.
- Error: #B91C1C.
- Advertencia: #B45309.

Tipografías:
- Lora para títulos.
- Nunito Sans para textos.

#### 3. Tareas

Construye una landing page completa con las siguientes secciones:

- Barra de navegación fija con enlaces internos.
- Botón para activar y desactivar el modo oscuro.
- Menú hamburguesa funcional en dispositivos móviles.
- Sección principal (Hero) con imagen destacada y llamada a la acción.
- Catálogo de productos con seis tarjetas.
- Sistema de filtrado por categorías.
- Sección "Sobre Nosotros".
- Sección de preguntas frecuentes tipo acordeón.
- Formulario de contacto con validación.
- Pie de página con información de contacto y redes sociales.

#### 4. Restricciones

- Utilizar únicamente HTML5 semántico.
- Utilizar Tailwind CSS v4 mediante CDN.
- Utilizar JavaScript Vanilla.
- Aplicar diseño Mobile First.
- Mantener coherencia con la paleta de colores definida.
- Garantizar contraste adecuado y accesibilidad básica.
- No utilizar librerías externas adicionales.
- Mantener todo el proyecto en un único archivo.

#### 5. Formato de salida

Genera el resultado en un solo archivo index.html.

El código debe estar correctamente indentado y comentado por secciones para facilitar su comprensión y mantenimiento.

---

### 3. Bitácora de Iteraciones con IA

<table>
<tr>
<th>#</th>
<th>Prompt de ajuste enviado</th>
<th>Problema que buscaba resolver</th>
<th>Resultado obtenido</th>
<th>¿Funcionó?</th>
</tr>

<tr>
<td>1</td>
<td>
"Implementa un modo oscuro que pueda activarse y desactivarse con un botón."
</td>
<td>
La página solo mostraba un tema claro y no permitía cambiar la apariencia visual.
</td>
<td>
Se añadió un botón que permite alternar entre modo claro y modo oscuro.
</td>
<td>
Sí
</td>
</tr>

<tr>
<td>2</td>
<td>
"Haz que el menú hamburguesa se cierre automáticamente al seleccionar una opción."
</td>
<td>
En dispositivos móviles el menú permanecía abierto después de navegar a una sección.
</td>
<td>
El menú ahora se oculta automáticamente al seleccionar cualquier enlace.
</td>
<td>
Sí
</td>
</tr>

<tr>
<td>3</td>
<td>
"Ajusta las imágenes del catálogo para que todas tengan el mismo tamaño."
</td>
<td>
Las tarjetas del catálogo se veían desordenadas porque las imágenes tenían diferentes dimensiones.
</td>
<td>
Todas las tarjetas quedaron alineadas y visualmente uniformes.
</td>
<td>
Sí
</td>
</tr>

<tr>
<td>4</td>
<td>
"Agrega validación al formulario para evitar envíos incompletos."
</td>
<td>
Los usuarios podían enviar el formulario sin completar toda la información importante.
</td>
<td>
Ahora se muestran mensajes de error y se solicita completar los campos obligatorios.
</td>
<td>
Sí
</td>
</tr>

<tr>
<td>5</td>
<td>
"Mejora la accesibilidad de la página para usuarios con diferentes necesidades."
</td>
<td>
Algunos elementos de la interfaz no eran lo suficientemente descriptivos para herramientas de accesibilidad.
</td>
<td>
Se mejoraron descripciones de imágenes y elementos interactivos, obteniendo una mejor evaluación de accesibilidad.
</td>
<td>
Sí
</td>
</tr>

</table>