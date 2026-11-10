# Prototipo en Figma

**Enlace:** [P1 Aprende Fácil – Prototipo Sala de Internet CLENA](https://www.figma.com/design/OvTH32MdQKZmG00Z6fHOqb/P1-Aprende-F%C3%A1cil-%E2%80%93-Prototipo-Sala-de-Internet-CLENA?node-id=0-1)

Compartido con el equipo de Backend y con djromero@uninorte.edu.co con permiso de comentario.

El prototipo tiene 19 pantallas: 10 para los computadores de la sala (1280 px) y 9 en versión de celular (390 px). Cumple con la accesibilidad pedida para P1: letra mínima de 16 px (texto entre 18 y 22 px), alto contraste, botones de 52 a 64 px de alto y etiquetas en todos los campos.

## Flujo completo

Inicio → Correo Gmail → guía «Enviar un correo con una foto» (4 pasos) → ¿Te sirvió? → Pedir ayuda a la asistente.

En Figma se recorre en modo Prototype con los flujos «Flujo Gmail · Escritorio» y «Flujo Gmail · Celular».

## Pantallas

Cada pantalla indica en su nombre la historia de usuario que cubre.

### Escritorio (computadores de la sala)

**HU-01 · HU-04 · HU-10 Inicio – Elegir tema**
<img src="img/01-inicio.png" alt="Inicio" width="560">

**HU-01 Guías de Correo Gmail**
<img src="img/02-guias-correo.png" alt="Guías de Correo Gmail" width="560">

**HU-02 · HU-03 Guía paso 1 de 4 – Redactar**
<img src="img/03-paso-1.png" alt="Paso 1" width="560">

**HU-02 · HU-03 Guía paso 2 de 4 – Para**
<img src="img/04-paso-2.png" alt="Paso 2" width="560">

**HU-02 · HU-03 Guía paso 3 de 4 – Adjuntar**
<img src="img/05-paso-3.png" alt="Paso 3" width="560">

**HU-02 · HU-03 Guía paso 4 de 4 – Enviar**
<img src="img/06-paso-4.png" alt="Paso 4" width="560">

**HU-11 Guía terminada – ¿Te sirvió?**
<img src="img/07-te-sirvio.png" alt="¿Te sirvió?" width="560">

**HU-12 Pedir ayuda a la asistente**
<img src="img/08-pedir-ayuda.png" alt="Pedir ayuda" width="560">

**HU-12 Ayuda solicitada**
<img src="img/09-ayuda-solicitada.png" alt="Ayuda solicitada" width="560">

**HU-13 Panel de la asistente – Dudas sin guía**
<img src="img/10-panel-asistente.png" alt="Panel de la asistente" width="560">

### Celular

**HU-01 · HU-04 · HU-10 Inicio – Elegir tema · Celular**
<img src="img/11-inicio-celular.png" alt="Inicio celular" width="220">

**HU-01 Guías de Correo Gmail · Celular**
<img src="img/12-guias-correo-celular.png" alt="Guías de correo celular" width="220">

**HU-02 · HU-03 Guía pasos 1 a 4 · Celular**
<img src="img/13-paso-1-celular.png" alt="Paso 1 celular" width="220"> <img src="img/14-paso-2-celular.png" alt="Paso 2 celular" width="220"> <img src="img/15-paso-3-celular.png" alt="Paso 3 celular" width="220"> <img src="img/16-paso-4-celular.png" alt="Paso 4 celular" width="220">

**HU-11 Guía terminada – ¿Te sirvió? · Celular**
<img src="img/17-te-sirvio-celular.png" alt="¿Te sirvió? celular" width="220">

**HU-12 Pedir ayuda a la asistente · Celular**
<img src="img/18-pedir-ayuda-celular.png" alt="Pedir ayuda celular" width="220">

**HU-12 Ayuda solicitada · Celular**
<img src="img/19-ayuda-solicitada-celular.png" alt="Ayuda solicitada celular" width="220">

## Comparación con lo construido por Backend

Pantalla comparada: **HU-01 · HU-04 · HU-10 Inicio – Elegir tema**, en la versión de escritorio. Captura de la demo tomada el 8 de noviembre de 2026.

<img src="img/01-inicio.png" alt="Inicio en el prototipo" width="420"> <img src="img/demo-inicio.png" alt="Inicio construido por Backend" width="420">

A la izquierda, el prototipo en Figma; a la derecha, la pantalla construida por el equipo de Backend.

### Lo que coincide

- Los colores (amarillo, verde oscuro y la franja roja y blanca) y la estructura general de la página.
- El encabezado con el nombre «Aprende Fácil» y el botón «Pedir ayuda».
- La pregunta «¿Qué quieres aprender hoy?» con el buscador y el ejemplo «adjuntar una foto».
- La sección «El tema más pedido en la sala» con acceso directo a las guías de Correo Gmail.
- Los demás temas (Documentos, Redes sociales, Seguridad en internet y Trámites en línea) con su ícono y una descripción corta.

### Diferencias que deben corregirse

- **El buscador no tiene etiqueta visible.** En el prototipo dice «Buscar una guía» encima del campo; en la demo solo está el texto de ejemplo dentro del campo, que desaparece al escribir. La guía de accesibilidad pide etiquetas en los formularios.
- **El buscador todavía no funciona** (ver el Issue de feedback [#26](https://github.com/JoseD2021/PlataformaAutoaprendizaje/issues/26)).
- **Falta el texto de apoyo** «Te mostramos cada paso con dibujos, a tu ritmo.», que en el prototipo le da confianza al usuario.
- **Aún no hay versión para celular**, que en el prototipo sí existe para todas las pantallas del público.

### Ajuste a partir de la visita de validación

En la visita del 9 de noviembre, la monitora indicó que las dudas más frecuentes son los programas de Office y abrir WhatsApp. Tanto el prototipo como la demo muestran Correo Gmail como «El tema más pedido», así que esa sección debería destacar Documentos o WhatsApp en una próxima versión.
