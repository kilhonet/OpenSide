# OpenSide

**Un asistente de IA gratuito para Windows: escribe en un chat lo que necesitas y la IA lo hace en el Chrome o Edge que ya usas, desde buscar hasta hacer clic y escribir.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, la [versión en coreano](README.ko.md) es la que prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/openside?lang=es)

![Pantalla de OpenSide](images/openside-en.png)

## Descripción general

Mucho trabajo en la web exige muchos clics y poca reflexión: reunir en una tabla los precios de varias tiendas, rellenar el mismo formulario una y otra vez, publicar en un blog, buscar el correo correcto en el buzón.

OpenSide te permite encargar ese trabajo con una línea de chat. Escribe la tarea en el cuadro «¿En qué puedo ayudarte?» y la IA abre sitios en tu navegador, lee las páginas, pulsa botones y escribe texto hasta terminar; luego te cuenta el resultado en pocas frases. Los datos que reúne pueden llegarte como archivo de Excel.

No usa un navegador aparte: trabaja **en el Chrome o Edge que ya estás usando**. En los sitios donde ya iniciaste sesión no hace falta volver a hacerlo, y como la IA trabaja en su propia pestaña, puedes seguir usando las demás mientras tanto. Si vinculas Telegram, también puedes encargar tareas y recibir resultados desde el teléfono cuando estés fuera.

Para la IA, inicia sesión con una cuenta de ChatGPT que ya tengas o introduce una clave de API de Claude, OpenAI o Gemini.

## Funciones principales

- **Tareas web por chat** — describe la tarea; la IA busca, hace clic, escribe y navega entre páginas por ti, y luego te informa.
- **Tu navegador y tus sesiones** — se conecta al Chrome o Edge que usas, así que los sitios con sesión iniciada funcionan al instante.
- **Trabajo repetitivo** — encarga de una vez tareas que se repiten, como rellenar formularios o reunir datos de muchas páginas.
- **Guardar en Excel** — los datos reunidos llegan como archivo de Excel (.xlsx), o en CSV si lo pides.
- **Control remoto por Telegram** — envía tareas desde Telegram en tu teléfono y recibe respuestas y archivos. No necesitas crear un bot.
- **Adjuntar archivos** — adjunta imágenes, texto o CSV para que la IA los lea, o para que los suba a un sitio.
- **Recuerda lo que viste** — si lo activas, registra las páginas que lees y las aplicaciones que usas, y las aprovecha en preguntas como «el artículo que leí ayer».
- **Buena con sitios populares** — publicar en Naver Blog, Tistory y Blogger, Gmail, Google Docs y Sheets, Notion, Slack, YouTube, Naver Real Estate y más se manejan con métodos propios de cada sitio, más rápidos y precisos.
- **Varias cuentas de IA** — registra el inicio de sesión de ChatGPT (Codex) y claves de API de Claude, OpenAI y Gemini, y cambia entre ellas desde el chat.
- **Modo oscuro · 9 idiomas** — coreano, inglés, japonés, chino, ruso, italiano, francés, español y árabe.

## Descarga / Instalación

| Edición | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/openside?lang=es) |
| Portátil (ZIP) | [Descargar](https://down.kilho.net/openside?lang=es&nosetup) |

El instalador abre OpenSide en cuanto termina la instalación. Con la edición portátil, descomprime el ZIP y ejecuta `OpenSide.exe`. Ambas ediciones tienen las mismas funciones; solo cambia el valor inicial de **Ejecutar al iniciar**: activado en el instalador y desactivado en la portátil.

## Uso

### Primeros pasos

1. Ejecuta OpenSide. La primera vez, la página de configuración de conexión se abre sola en tu navegador (Chrome o Edge).
2. En esa página, activa la casilla **Remote debugging**. Si la página no se abrió, escribe `chrome://inspect/#remote-debugging` (en Edge, `edge://inspect/#remote-debugging`) en la barra de direcciones del navegador.
3. Cuando el navegador muestre una solicitud de conexión, haz clic en **Permitir**. Esta configuración solo se hace una vez.
4. Después se abre **Preferencias** en **Cuenta**. Haz clic en **Añadir**, elige la IA que usarás (por ejemplo **Iniciar sesión en Codex**) e inicia sesión en la página que se abre en el navegador. Cuando veas «Inicio de sesión completado», cierra esa ventana y vuelve a OpenSide.
5. Escribe una tarea en el cuadro de chat («¿En qué puedo ayudarte?») y pulsa **Enter**. Por ejemplo: «Dime los títulos de los 5 avisos más recientes de kilho.net».
6. Mientras la IA trabaja, el progreso aparece línea a línea. Al terminar, el resultado aparece como respuesta y el progreso se pliega en una sola línea «N s de trabajo», en la que puedes hacer clic para desplegarlo de nuevo.

### Distribución de la pantalla

| Elemento | Qué hace |
|---|---|
| Título del chat | El título de la conversación actual. Se toma de tu primer mensaje; haz clic para editarlo (**Enter** guarda · **Esc** cancela) |
| **Sesiones recientes** | Tus conversaciones anteriores (las 15 más recientes). Elige una para continuarla |
| **Nuevo chat** | Empieza una conversación nueva |
| **Configuración** | Abre la ventana **Preferencias** |
| Clip (**Adjuntar archivos**) | Adjunta archivos al mensaje. Aparecen bajo el cuadro de texto; quita uno con × |
| Cuadro de texto · **Enviar** | Escribe la tarea y envíala. Mientras la IA trabaja, **Enviar** se convierte en **Detener** |
| Icono **Control remoto** | Activa y desactiva el control remoto por Telegram. Verde cuando está activo |
| Icono del ojo (**Historial**) | Solo aparece mientras el registro de páginas está activo. Haz clic para pausar o reanudar el registro |
| Anillo de uso | Uso de una cuenta **Iniciar sesión en Codex**. Pasa el ratón por encima para ver cuánto queda |
| Cuenta · modelo · nivel de razonamiento | Elige la cuenta de IA, el modelo y cuánto piensa en esta conversación |

### Qué hacer cuando…

**Reunir información de varios sitios en una tabla**
Di qué reunir y cómo lo quieres, por ejemplo «Busca el precio del portátil modelo A en tres tiendas y ponlo en Excel». Al terminar aparece en el chat una tarjeta **⬇ Descargar**. Haz clic para elegir dónde guardarlo (al principio, la carpeta Descargas); después, **Abrir archivo** y **Abrir carpeta** lo abren al momento. El archivo de Excel conserva intactos los valores con ceros a la izquierda, como `007` o los números de teléfono. Si necesitas un archivo para otro programa, di «en CSV»: se genera de modo que los caracteres no latinos se vean bien.

**Rellenar el mismo formulario muchas veces**
Di algo como «Envía una solicitud por cada persona de esta lista». La IA rellena de una vez los campos, casillas y listas desplegables del formulario, y comprueba que aparezca el resultado antes de seguir, así que nunca pulsa dos veces un botón de envío. Si la lista está en un archivo, adjúntalo.

**Cuando solo quieres que mire, y cuando quieres que lo termine**
Si dices «compara» o «solo escribe un borrador», la IA no hará nada que no se pueda deshacer, como enviar, pagar, borrar o publicar. Si dices «envíalo» o «pídelo», lleva la tarea hasta el último botón sin volver a preguntar. Conviene dejar claro en el mensaje hasta dónde debe llegar.

**Publicar en un blog**
Di algo como «Escribe esto como entrada de Naver Blog y publícala». En Naver Blog, Tistory y Blogger, el título, el cuerpo, los subtítulos, las imágenes y las etiquetas se introducen con métodos adecuados a cada sitio. Adjunta las imágenes que quieras incluir.

**Trabajar con correo, documentos y herramientas de trabajo**
Di cosas como «Busca en Gmail el correo de presupuesto de la semana pasada y resúmelo», «Lee los valores de la columna B de mi hoja de Google», «Añade las notas de hoy a la página de actas en Notion» o «Dime las últimas publicaciones del canal #avisos de Slack». Trabaja con las cuentas que ya tienen sesión iniciada en tu navegador. Si hay varias cuentas de Google con sesión iniciada, di cuál y trabajará en esa.

**Investigar en YouTube, X y LinkedIn**
Di cosas como «Resume la transcripción de este vídeo de YouTube», «Resume las reacciones en los comentarios de este vídeo», «Reúne publicaciones recientes sobre este tema en X» o «Busca las ofertas de empleo de esta empresa en LinkedIn».

**Reunir anuncios inmobiliarios**
Di algo como «Pon en Excel los anuncios de jeonse del apartamento ○○ en Naver Real Estate» y convierte los anuncios en una tabla.

**Buscar imágenes**
Di algo como «Busca 10 fotos de ○○ y reúne sus direcciones» y recopila las URL de las imágenes desde los resultados de búsqueda.

**Usar otras pestañas mientras trabaja**
La IA solo se mueve en la pestaña donde trabaja, así que puedes seguir con lo tuyo en otras pestañas del mismo navegador. Su pestaña sigue funcionando aunque esté en segundo plano, igual que si estuviera delante. Si das la siguiente tarea en el mismo chat, continúa en la pestaña donde estaba trabajando, aunque tú estés mirando otra. Un chat nuevo empieza en la pestaña que estás mirando.

**Las pestañas que abre y las tuyas**
La IA abre una pestaña nueva solo cuando necesita dos páginas a la vez, y cierra las que abrió antes de responder. No cierra las pestañas que abriste tú. Si quieres ordenar tus pestañas, pídeselo directamente, por ejemplo «Cierra todas las pestañas de kilho.net».

**Cuando hace falta un código de verificación o la aprobación de la app del banco**
Cuando un paso necesita a una persona —un código enviado al teléfono, la aprobación en la app del banco, un CAPTCHA de texto—, la IA trae esa pestaña al frente y te dice en una línea qué hacer. Hazlo en el navegador o escribe el código en el cuadro de chat, y la IA continúa. La IA marca por sí misma las casillas «No soy un robot» y solo te pasa el control cuando aparece un desafío de elegir imágenes. Si un registro necesita un enlace o código enviado por correo y Gmail tiene la sesión iniciada en el navegador, la IA abre el buzón y lo encuentra.

**Añadir algo mientras trabaja**
Puedes escribir en el cuadro de chat incluso mientras la IA trabaja. Tu mensaje llega directamente a la tarea en curso. Úsalo para cambiar el rumbo («escribe los precios en wones») o para responder algo que preguntó. Para que se detenga, haz clic en **Detener**.

**Que lea archivos de tu PC o los suba a un sitio**
Adjunta archivos con el clip y envíalos, y la IA los lee. Mira el contenido de las imágenes (png, jpg, gif, webp) y lee y usa los archivos de texto y CSV. Puedes adjuntar varios a la vez, y los archivos originales nunca se tocan. Di algo como «Adjunta la foto que envié a una publicación en este foro», y la IA también se encarga de la ventana de subida del sitio.

**Que lea siempre una carpeta concreta**
Si adjuntar cada vez es pesado, añade la carpeta en **Preferencias** → **Archivos** → **Carpeta que la IA puede leer** (**Añadir carpeta...**). Así puedes decir cosas como «Con la lista de clientes de mi carpeta de datos, …». La IA solo lee esa carpeta y nunca escribe en ella. Añade solo las carpetas que necesites.

**Encontrar una página que viste antes**
Activa **Registrar las páginas que leo y las apps que uso** en **Preferencias** → **Historial**, y OpenSide registra el texto de las páginas que lees y las ventanas de las aplicaciones que usas. Así puedes decir cosas como «Vuelve a resumir el artículo de inversión que leí ayer» o «Compara los pros y contras de los hoteles que miré antes». Los registros se guardan 30 días y no se registran las páginas con un campo de contraseña. Escribe los sitios y aplicaciones que no quieres registrar separados por comas (p. ej. `bank.com, kakaotalk.exe`). Para pausar el registro, haz clic en el icono del ojo en la pantalla del chat; para borrarlo todo, haz clic en **Eliminar todo**. Esta función está desactivada al principio.

**Encontrar un sitio que visitaste antes**
Di algo como «Abre la web de esa floristería que visité la última vez» y la busca en el historial del navegador y la abre.

**Encargar tareas desde el teléfono (Telegram)**
1. En **Preferencias** → **Remoto**, haz clic en **Vincular ahora**. Aparecen un código QR y un código de vinculación, válidos durante 10 minutos.
2. Escanea el QR con la cámara del teléfono. Cuando se abra Telegram, toca **Iniciar**. Si tienes Telegram instalado en el PC, también puedes hacer clic en **Abrir en este PC**.
3. Cuando Telegram muestre un mensaje de que está conectado, ya está. Ahora envía una tarea como mensaje de texto en Telegram, y OpenSide en tu PC la hace y te devuelve la respuesta.

Los archivos que genera y peticiones como «introduce el código de verificación» también llegan al teléfono. Responde con el código en Telegram y llega a la tarea en curso. Si una respuesta es larga, el principio llega como mensaje y el texto completo como archivo. Telegram solo acepta texto, así que envía palabras en lugar de fotos. OpenSide tiene que estar en marcha en tu PC para trabajar, así que conviene activar **Ejecutar al iniciar** cuando uses el control remoto. Para desactivarlo un rato, haz clic en el icono **Control remoto** en la pantalla del chat; para desconectarlo del todo, haz clic en **Desvincular**.

**Usar varias cuentas de IA**
En **Preferencias** → **Cuenta**, haz clic en **Añadir** para ver los tipos disponibles.

| Tipo | Cómo funciona |
|---|---|
| **Iniciar sesión en Codex** | Inicia sesión con una cuenta de ChatGPT |
| **Clave de API de Claude...** · **Clave de API de Gemini...** | Introduce una clave de API |
| **Clave de API de OpenAI...** | Introduce una clave de API y una **URL base (.../v1)**. Cambiando la dirección puedes usar otros servicios que funcionan igual que OpenAI |

Al guardar una cuenta con clave de API, obtiene al momento la lista de modelos para comprobarla. Elige la cuenta para los chats nuevos con **Predeterminar** y haz doble clic en una cuenta para cambiarle el nombre. Durante un chat puedes cambiar la cuenta, el modelo y el nivel de razonamiento desde la parte inferior de la pantalla. Un nivel de razonamiento más alto piensa más a fondo; uno más bajo responde más rápido.

**Ver cuánto uso queda**
Con una cuenta **Iniciar sesión en Codex**, aparece un anillo de uso en la parte inferior del chat. Se llena a medida que usas más; pasa el ratón por encima para ver lo que queda en cada periodo. Cuando esté casi agotado, cambia a otra cuenta.

**Continuar un chat anterior**
Haz clic en **Sesiones recientes** para ver tus 15 últimas conversaciones con cuándo las usaste. Elige una y sigue. Para darle un título más claro, haz clic en el título de arriba.

**Lo que recuerda por sí misma**
Cada vez que termina una tarea, la IA guarda lo que ha confirmado —cómo usar un sitio, datos que le diste— y lo usa en chats posteriores. Cuantas más tareas le des en el mismo sitio, menos titubea.

**Mantenerla en marcha tras cerrar la ventana**
Hacer clic en la × de la ventana no la cierra; OpenSide pasa al área de notificación (bandeja). Haz clic en el icono de la bandeja para recuperar la ventana. Para salir del todo, haz clic derecho en el icono y elige **Salir**. **Ejecutar al arrancar** en ese mismo menú es el mismo ajuste que **Ejecutar al iniciar** en **Preferencias**; si está activado, OpenSide se inicia discretamente en la bandeja al arrancar Windows. Solo se ejecuta una copia de OpenSide; abrirla de nuevo trae al frente la ventana ya abierta.

**Mantener la ventana de OpenSide delante**
Para tener OpenSide junto al navegador mientras miras, pon **Siempre visible** en **Activado** en **Preferencias** → **General**. La posición y el tamaño de la ventana se recuerdan, así que se abre en el mismo sitio la próxima vez.

**Chrome o Edge: en cuál trabaja**
OpenSide trabaja en el navegador donde **Remote debugging** está activado. Si ambos lo tienen activado, usa primero el navegador predeterminado de Windows. Para que trabaje en el otro, actívalo solo en ese navegador.

**Después de reiniciar el navegador**
Si hace falta conectar, OpenSide muestra la ventana **Se necesita conectar el navegador** con los pasos en orden. Síguelos y haz clic en **Conectar**. Al hacer clic en la dirección de esa ventana se copia, así que puedes pegarla en la barra de direcciones.

## Configuración

Haz clic en **Configuración** para abrir la ventana **Preferencias**. Los cambios se aplican al instante.

| Pestaña | Opciones |
|---|---|
| **General** | **Siempre visible** · **Tema** (Automático · Claro · Oscuro) · **Idioma** (Automático o uno de 9 idiomas) · **Ejecutar al iniciar** |
| **Cuenta** | Añadir, eliminar e iniciar sesión en cuentas de IA · elegir la cuenta predeterminada |
| **Remoto** | Vincular o desvincular Telegram |
| **Historial** | Activar el registro de páginas y apps · pausar · sitios y apps que no se registran · eliminar todo |
| **Archivos** | Carpetas que la IA puede leer |

Con **Idioma** en **Automático**, OpenSide sigue el idioma de visualización de Windows. Si eliges árabe, la pantalla pasa a leerse de derecha a izquierda. Las líneas de progreso y las respuestas de la IA siguen el idioma de tu mensaje. Con **Tema** en **Automático**, sigue el modo de aplicación de Windows (claro u oscuro).

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- Google Chrome o Microsoft Edge
- Una cuenta de ChatGPT, o una clave de API de Claude, OpenAI o Gemini
- Conexión a internet

## Actualizaciones

Por seguridad y para evitar falsos positivos del antivirus, OpenSide **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y te avisa; si decides obtenerla, abre la página de descarga y cierra el programa. Las versiones nuevas se publican manualmente tras una verificación interna y se anuncian en la [página de OpenSide](https://kilho.net/openside). Consulta el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

## Licencia

OpenSide es **freeware**. Úsalo donde quieras —en la oficina, en casa, en organismos públicos o en centros educativos— gratis y sin restricciones, y redistribúyelo libremente. El coste de uso de la IA depende del plan de tu propia cuenta de IA o clave de API.

## Enlaces

- Sitio web: <https://kilho.net/openside>
- Foro: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
