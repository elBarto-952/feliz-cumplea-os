
IMPORTANTE:

* No quiero una copia literal del código.
* Quiero que mantengas la lógica general y la experiencia interactiva, pero que mejores considerablemente el diseño, las animaciones, la responsividad y la calidad visual.
* Todo debe funcionar completamente en el navegador.
* No debe haber errores de JavaScript ni elementos que no funcionen.
* Entrégame el proyecto completo y listo para ejecutar.

## TECNOLOGÍAS

Utiliza:

* HTML5
* CSS3
* JavaScript vanilla
* Google Fonts únicamente si son necesarias
* SVG/CSS para las animaciones
* No utilices frameworks innecesarios.
* El proyecto debe poder ejecutarse simplemente abriendo el HTML.
* Además, si la estructura lo permite, déjalo preparado para ejecutarse con `pnpm run dev` usando Vite.

## CONCEPTO

La página será una experiencia digital romántica y elegante de cumpleaños.

Debe sentirse como una pequeña historia interactiva, no como una página web convencional.

La navegación debe ocurrir mediante diferentes escenas/pantallas:

1. Sobre cerrado
2. Carta de cumpleaños
3. Pastel con velas
4. Razones/mensajes especiales
5. Mensaje final

Cada escena debe tener una transición suave hacia la siguiente.

## ESTILO VISUAL

Quiero un diseño:

* Elegante
* Romántico
* Moderno
* Premium
* Minimalista
* Emocional
* Adaptado perfectamente a celular y PC

Usa una paleta similar a:

* Morado oscuro
* Vino/burdeos
* Dorado
* Crema
* Rosa suave

El fondo debe tener profundidad mediante:

* Gradientes
* Luces ambientales
* Pequeñas partículas flotantes
* Efectos de brillo
* Desenfoque sutil
* Sombras suaves

Evita que el diseño se vea recargado.

## ESCENA 1 — SOBRE

La página debe comenzar mostrando un sobre elegante en el centro.

Debe incluir:

* Sobre color vino
* Sello dorado
* Inicial personalizable
* Pequeño texto indicando que debe abrir el sobre
* Animación de entrada
* Efecto hover
* Animación 3D al abrirlo

Cuando el usuario haga clic sobre el sobre:

1. El sello debe desaparecer suavemente.
2. La solapa del sobre debe abrirse.
3. Debe aparecer una carta dentro.
4. Debe producirse una pequeña animación de brillo.
5. Después de aproximadamente 1 segundo debe pasar automáticamente a la siguiente escena.

También debe funcionar con teclado usando Enter o Space.

## ESCENA 2 — CARTA

Mostrar:

"Feliz cumpleaños"

y debajo el nombre de la persona.

Utiliza una tipografía elegante y grande.

La carta debe aparecer progresivamente mediante animaciones.

Contenido personalizable:

NOMBRE:
[COLOCA AQUÍ EL NOMBRE]

MENSAJE:
[ESCRIBE AQUÍ EL MENSAJE DE CUMPLEAÑOS]

SEGUNDO PÁRRAFO:
[ESCRIBE AQUÍ OTRO MENSAJE]

TERCER PÁRRAFO:
[ESCRIBE AQUÍ OTRO MENSAJE MÁS PERSONAL]

FIRMA:
[ESCRIBE AQUÍ LA FIRMA]

También quiero un espacio para colocar una fotografía.

El espacio de fotografía debe permitir cambiar fácilmente una imagen mediante una ruta como:

assets/foto.jpg

Si no existe una imagen, debe mostrarse un diseño elegante de reemplazo.

Al final debe aparecer un botón:

"Continuar →"

El botón debe aparecer mediante una animación después de que el contenido haya terminado de mostrarse.

## ESCENA 3 — PASTEL

Crear una escena con un pastel de cumpleaños hecho principalmente con HTML/CSS/SVG.

Debe incluir:

* Pastel elegante
* Plato
* 5 velas
* Llamas animadas
* Humo después de apagar cada vela

Texto:

"Es hora de pedir un deseo"

Instrucción:

"Apaga todas las velas y pide un deseo que solo tú conozcas."

Cada vela debe poder apagarse haciendo clic.

Cuando se apaguen todas:

* Mostrar una animación de celebración.
* Lanzar confeti.
* Mostrar un mensaje especial.
* Activar el botón Continuar.

Mensaje personalizable:

"Espero que ese deseo se haga realidad. ✨"

## ESCENA 4 — RAZONES

Crear una sección llamada:

"Algunas razones por las que eres especial"

Mostrar varias tarjetas con mensajes.

Quiero aproximadamente 5 tarjetas.

Ejemplo:

1. [RAZÓN 1]
2. [RAZÓN 2]
3. [RAZÓN 3]
4. [RAZÓN 4]
5. [RAZÓN 5]

Las tarjetas deben funcionar como un pequeño carrusel.

Debe haber:

* Flecha anterior
* Flecha siguiente
* Indicadores
* Animación al cambiar
* Soporte para teclado con flechas izquierda/derecha

El botón Continuar solo debe aparecer después de que el usuario haya visto todas las tarjetas.

## ESCENA 5 — FINAL

Mostrar una escena emocional de cierre.

Ejemplo:

"Feliz cumpleaños, [NOMBRE] ❤️"

Debajo:

"Espero que este nuevo año de tu vida esté lleno de momentos increíbles."

Después:

"Con cariño,
[TU NOMBRE]"

Agregar:

* Corazones flotando
* Brillos
* Confeti sutil
* Animación de entrada
* Efecto de luz detrás del mensaje

Incluir botón:

"Ver de nuevo"

Este botón debe reiniciar TODA la experiencia desde el principio.

## SISTEMA DE NAVEGACIÓN

Crear un sistema de pasos como el código original.

Debe existir:

* Indicadores de progreso en la parte superior.
* Botón regresar.
* Navegación controlada.
* No permitir saltar a escenas que todavía no se han desbloqueado.
* Los pasos completados sí pueden volver a abrirse.
* Transiciones suaves entre escenas.

El estado debe manejarse correctamente mediante JavaScript.

## ANIMACIONES

Quiero animaciones suaves y profesionales:

* Fade in
* Slide up
* Scale
* Glow
* Partículas
* Confeti
* Flotación
* Brillos
* Animación 3D del sobre
* Llamas de las velas
* Humo
* Corazones

No exageres las animaciones.

Deben sentirse elegantes y fluidas.

## RESPONSIVE

Debe funcionar perfectamente en:

* iPhone
* Android
* Tablet
* Laptop
* PC
* Pantallas grandes

No quiero:

* Scroll horizontal
* Elementos cortados
* Texto fuera de pantalla
* Botones difíciles de tocar
* Animaciones que rompan el diseño

En móvil los botones y elementos interactivos deben tener un tamaño adecuado para tocar con el dedo.

## ACCESIBILIDAD

Implementa:

* aria-label
* navegación por teclado
* estados de focus visibles
* botones reales en lugar de elementos clicables cuando corresponda
* soporte para `prefers-reduced-motion`

## PERSONALIZACIÓN

Al principio del JavaScript crea una sección claramente identificada:

// ===============================
// CONFIGURACIÓN PERSONALIZABLE
// ===============================

const CONFIG = {
nombre: "...",
firma: "...",
mensaje1: "...",
mensaje2: "...",
mensaje3: "...",
razon1: "...",
razon2: "...",
razon3: "...",
razon4: "...",
razon5: "...",
mensajeFinal: "...",
foto: "assets/foto.jpg"
};

Quiero poder cambiar toda la información desde esta sección sin tener que buscar textos por todo el código.

## ESTRUCTURA DEL PROYECTO

Si utilizas Vite, organiza el proyecto así:

birthday-page/
│
├── index.html
├── package.json
├── src/
│   ├── main.js
│   └── style.css
│
├── public/
│   └── assets/
│       └── foto.jpg
│
└── README.md

El `package.json` debe incluir:

* `dev`
* `build`
* `preview`

Y debe poder iniciarse con:

pnpm install

y después:

pnpm run dev

## CALIDAD DEL CÓDIGO

Quiero código:

* Limpio
* Organizado
* Comentado
* Fácil de modificar
* Sin código duplicado innecesario
* Sin errores de consola
* Sin librerías innecesarias

Separa correctamente:

* HTML
* CSS
* JavaScript

No metas todo en un único bloque gigantesco si estás utilizando Vite.

## IMPORTANTE SOBRE EL RESULTADO

Antes de terminar, verifica mentalmente toda la experiencia:

SOBRE
↓
ABRIR SOBRE
↓
CARTA
↓
CONTINUAR
↓
PASTEL
↓
APAGAR 5 VELAS
↓
CONFETI
↓
CONTINUAR
↓
RAZONES
↓
VER TODAS
↓
CONTINUAR
↓
MENSAJE FINAL
↓
VER DE NUEVO
↓
SOBRE

Comprueba especialmente:

* Que el botón continuar no se quede bloqueado.
* Que las velas puedan apagarse correctamente.
* Que el confeti aparezca después de apagar todas.
* Que las tarjetas funcionen.
* Que el botón volver funcione.
* Que "Ver de nuevo" reinicie todos los estados.
* Que no existan errores en la consola.
* Que la experiencia funcione tanto con mouse como con pantalla táctil.

Toma como referencia visual y funcional el código que te proporcioné, pero crea una versión considerablemente más moderna, elegante y personalizable.

No elimines las interacciones principales; mejóralas.
