# Registro de cambios de QC Sala

QC Sala es una app no oficial para Android, hecha para jugar en la Sala de Juegos de QuentinC (qcsalon.net) con lector de pantalla. Aquí van todos los cambios, de lo más nuevo a lo más viejo.

El número de versión tiene tres partes: la primera sube con un gran salto, la segunda con funciones nuevas y la tercera con correcciones pequeñas.

## Versión 1.0.5 (8 de octubre de 2026)

### Novedades

- Muestra de audio de la mesa. Dentro de una mesa, en Más opciones, grupo "Mesa y sala", justo después de "Gestión de la mesa", está la opción nueva "Muestra de audio". Si eres el jefe de mesa, la sala te pide un enlace: una radio o un archivo de audio con enlace directo (por ejemplo, de Dropbox con dl.dropbox; una página que pide tocar "Descargar" no sirve). Los demás de la mesa la encienden o la apagan con la misma opción. El jefe, si la toca otra vez, la para y puede poner otra. Suena con el volumen de "música y flujos". También se puede poner en un gesto, en Personalizar gestos (de fábrica ningún gesto la trae). (Idea de Un_Duendementor.)
- Volúmenes sin salir de la sala. En Más opciones, grupo "Ayuda, ajustes y salir", justo antes de "Ajustes de la app", está "Volúmenes": abre un cuadro con las tres barras (sonido, notificaciones, y música y flujos) que subes o bajas con el gesto de tu lector, y el botón "Cerrar". Y hay tres acciones nuevas para tus gestos, en Personalizar gestos (de fábrica ningún gesto las trae): "Elegir el siguiente volumen" (salta entre sonido, notificaciones, y música y flujos, y te dice cuál es y su porcentaje), "Subir volumen" y "Bajar volumen" (de 10 en 10). (Idea de Un_Duendementor.)
- Las radios y las muestras de audio con enlaces http, sin cifrar, ahora suenan (antes no). La app intenta primero la versión cifrada y, si no abre en unos segundos, la otra. Solo se hace con radios y muestras de audio: todo lo demás sigue siempre cifrado.

### Cambios

- Si la app se vuelve a abrir estando dentro de una mesa libre, al salir de la mesa ya no pregunta dos veces.

## Versión 1.0.4 (7 de octubre de 2026)

### Novedades

- Gesto nuevo para ir al primer o al último elemento de la zona de juego. Con un dedo, hacia arriba y, sin levantarlo, hacia abajo: te lleva al primer elemento (la primera carta, la primera opción del menú). Hacia abajo y luego hacia arriba: te lleva al último. También sirve en el historial, donde te lleva al primer o al último mensaje de la vista, y está entre las acciones del lector de la zona de juego ("Primer elemento de la zona" y "Último elemento de la zona"). Puedes cambiarlo en Personalizar gestos, como los demás. (Idea de Mortaccio.)
- Después de actualizar, la primera vez que abres la app sale un cuadro con las novedades de esa versión, con el botón "Volver al juego" (o "Cerrar", si no estás en la sala). En Ajustes, en Actualizaciones, el botón "Novedades de esta versión" las vuelve a abrir.
- La app busca versión nueva al abrirla y cada tres horas mientras está abierta y conectada (antes, una vez al día). Y hay un ajuste nuevo en Ajustes, en Actualizaciones: "Avisarme a media partida". Con "Al salir de la mesa" (así viene de fábrica), la app te dice de voz una sola vez que hay versión nueva y el cuadro sale cuando sales de la mesa. Con "Al instante", el cuadro sale aunque estés jugando; al actualizar, Android cierra la app y sales de la partida.

### Cambios

- El botón "Ahora no" del cuadro "Hay una versión nueva" ahora se llama "Después", y la próxima vez que abras la app te vuelve a ofrecer esa versión.
- El cuadro "Hay una versión nueva" ya no deja botones cortados con el teléfono acostado o con la letra grande.
- Las novedades de ese cuadro salen en el idioma de tu app.

## Versión 1.0.3 (7 de octubre de 2026)

### Cambios

- La app pesa casi tres veces menos: de unos 4,7 MB a 1,7 MB. Se baja más rápido y ocupa menos en tu teléfono.
- Por dentro está mejor protegida y más ordenada. Todo funciona igual que antes.
- Tus ajustes y tus gestos personalizados se conservan al actualizar.

### Un consejo

- Si a veces sientes que un bot tarda mucho o que dos jugadas te llegan juntas, revisa tu wifi: suele ser señal de que tu teléfono pierde conexión con el módem. Acércate a él, usa la red de 2.4 GHz si tu módem la tiene, o reinícialo.

## Versión 1.0.2 (4 de octubre de 2026)

### Novedades

- QC Sala ya se actualiza sola. Una vez al día pregunta en GitHub, la página donde se publica, si hay una versión nueva. Esa consulta solo lleva el nombre de la app y su número de versión: nada de tu cuenta ni de tu teléfono.
- Si hay una versión nueva, sale un cuadro que dice el número de la versión, cuánto pesa la descarga y las novedades, con dos botones: "Actualizar" y "Ahora no". Con "Ahora no", no vuelve a preguntar por esa versión hasta el día siguiente.
- Con "Actualizar", la app baja la versión nueva y te va diciendo cómo va, al 25, al 50 y al 75 por ciento. Luego se abre el instalador de Android, el de siempre ("¿Deseas actualizar esta app?"), y tú confirmas. Al terminar, Android cierra QC Sala; la abres otra vez y te dice que ya se actualizó.
- La primera vez, Android pide permitir que QC Sala instale apps. La app lo explica en un cuadro y abre ese ajuste con el botón "Abrir los ajustes": enciendes el interruptor de QC Sala, vuelves a la app y la descarga sigue sola. Puede salir Play Protect, como en la primera instalación.
- En Ajustes hay una sección nueva, "Actualizaciones": dice qué versión tienes y trae la casilla "Buscar actualizaciones" (encendida de fábrica) y el botón "Buscar actualizaciones ahora".

### Cambios

- Seguridad: antes de instalar, la app comprueba que el archivo sea de verdad QC Sala, que sea más nuevo que el tuyo y que lleve la misma firma de la app que ya tienes. Si algo no cuadra, no instala nada y te dice qué pasó. Solo descarga desde las páginas de GitHub de QC Sala, con conexión cifrada, y se detiene si la descarga pesa más de lo normal.
- Las actualizaciones hechas con el botón de la app conservan tu sesión, tus ajustes y tus gestos, y no apagan el toque directo, tampoco en Android 14. (Antes, en Android 14, instalar la versión nueva desde un archivo sí lo apagaba.)
- Antes de instalar, la app le devuelve a tu lector la zona del toque directo, igual que al salir de la sala, para que no te quedes sin leer una parte de la pantalla cuando Android cierre la app para actualizarla.
- Si una versión se publica sin el archivo de la app, o GitHub contesta algo que la app no entiende, te lo dice así, en vez de decirte que ya tienes la versión más nueva. Si GitHub tarda demasiado, la búsqueda se corta al minuto y la descarga a los diez.

## Versión 1.0.1 (4 de octubre de 2026)

### Novedades

- Con la pantalla apagada, Android (y sobre todo Samsung) puede dormir a QC Sala para ahorrar batería y cortarte la sala sin avisar, por ejemplo mientras esperas tu turno con el teléfono en la mesa.
- Ahora la app lo revisa. En Ajustes, debajo de lo de los avisos, te dice si eso puede pasar y te ofrece el botón "Dejar que QC Sala siga conectada con la pantalla apagada".
- Al tocarlo, Android pregunta si permites que la app se ejecute siempre en segundo plano. Tocas "Permitir" y listo.
- En la sala te lo aconseja una sola vez. Y si Android llega a cerrar la app en segundo plano, al volver te dice dónde está ese botón.

## Versión 1.0.0 (4 de octubre de 2026): la primera versión oficial para todos

Esta es la primera versión completa para todo el mundo. Antes de salir se revisó todo el código de la app de una sola vez: no se encontraron cierres inesperados, ni pantallas que se queden sin lector, ni mensajes perdidos, y la seguridad de tu cuenta quedó bien. Se arreglaron seis detalles menores. Todo lo de la serie 0.2 (los tres idiomas, el toque directo, los gestos en ángulo, salir de la sala cerrando la app y una app de teléfono sin nombres de teclas de computadora) llega junto en esta versión.

### Correcciones

- Si entras sin marcar "Recordar mis datos" y luego cierras la app con "Salir de la sala", o la abres otra vez desde su ícono, ahora te pide entrar de nuevo, como un navegador que no recuerda tus datos. Antes podía volver a entrar sola con la cuenta anterior, un problema si alguien más usa tu teléfono. Con "Recordar mis datos" marcado todo sigue igual: entra directo. Y si se corta la conexión mientras juegas, se reconecta como siempre.
- Al tocar un aviso de "Mensajes de la sala" con la app en segundo plano, vuelves a la misma sala que dejaste, con lo que tenías escrito en el chat. Antes la sala se abría desde cero y lo escrito se perdía.
- Si la conexión ya había terminado (por ejemplo, porque tocaste "Desconectar"), ese aviso te lleva a la pantalla de inicio y ya no se vuelve a conectar sola.
- Guardar el historial sobre un archivo que ya existía ya no deja pedazos del texto viejo al final.
- Tras usar "Devolver la pantalla al lector", la app ya no se queda escuchando a tu lector cuando no hace falta. Ahorra memoria y no cambia nada de lo que oyes.
- Si giras el teléfono con la pregunta de "Cerrar sesión" abierta en la pantalla de inicio, la pregunta se cierra sin responder y tu sesión sigue como estaba.

### Cambios

- Más seguridad en la conexión con la sala: si el servidor intentara mandar la conexión a otro lugar, la app ya no lo sigue, así tu pase nunca sale hacia otro servidor. Hoy el servidor no hace eso; es una protección de más.

## Versión 0.2.6 (4 de octubre de 2026)

### Cambios

- La app es de teléfono, así que todo lo que ves u oyes habla solo de gestos y botones. Ya no se nombra ninguna tecla de computadora en ningún lugar, en los tres idiomas de la app: español, inglés y francés.
- El cuadro que se abre al mantener dos dedos ahora se llama "Gestos del juego". Cada renglón dice qué hace y, si tiene gesto, cuál es. Arriba hay una línea nueva que explica que cada renglón es un botón: lo que no tiene gesto lo haces tocándolo ahí mismo.
- La ayuda rápida del juego se dice con tus gestos. Lo que no tiene gesto dice dónde encontrarlo, y si no se puede desde la app, lo dice con claridad.
- El Teclado del juego (los botones con números y letras de cada juego) se queda, pero cada botón dice su nombre y, al lado, lo que hace.
- Cuando un juego tenía dos botones con el mismo número que hacen cosas distintas, el segundo lleva una palabra delante ("Quitar 1", "Elegir 1", "Escribir 1", "Poner 1"), para que nunca oigas dos números iguales.
- En Ajedrez, los botones se llaman con la pieza: Rey, Dama, Torre, Caballo, Alfil y Peón (y sus nombres en inglés y en francés).
- Se reescribieron los textos de muchos juegos que hablaban de teclas, como Uno, Monopoly, Tarot, Póker, Dominó, Gatitos explosivos, Toma 6, Scrabble, Quiz Party, Mesa libre, Rami, Barbú, Cribbage, Carrera de patos y Buscaminas. Dicen lo mismo, con palabras del teléfono.
- Si conectas un teclado al teléfono, sigue funcionando igual que antes.
- Aviso: lo que la sala dice por su cuenta (sus avisos, sus menús y su ayuda) a veces nombra teclas. Eso viene del servidor de la sala y la app no lo puede cambiar.

## Versión 0.2.5 (4 de octubre de 2026)

### Novedades

- Todo lo que está en "Más opciones" ya se puede asignar a un gesto en "Personalizar gestos", para todos los juegos o solo para uno. Por ejemplo: estado de la conexión, volver a conectar, usuarios conectados, lista de amigos, salir de la mesa, ver y borrar el historial, abrir los enlaces de un mensaje, salir de la sala y cerrar sesión.
- Cada acción hace lo mismo que su opción de "Más opciones", con las mismas preguntas de confirmación. Si en ese momento no tiene caso, suena el tope y se dice en breve por qué.
- Ningún gesto de fábrica cambió: estas acciones solo hacen algo si tú se las das a un gesto.

### Cambios

- "Salir de la sala" ahora cierra la app por completo. Se desconecta, se quita el aviso fijo de "Conectado a la sala", desaparece de las apps recientes y vuelves a donde estabas en el teléfono.
- Tu sesión no se cierra: la próxima vez que abras QC Sala entras directo. La pregunta de salir lo avisa: "La app se cerrará; tu sesión se conserva."
- Antes de cerrarse, la app le devuelve primero a tu lector la zona del toque directo, para que nunca quede en la pantalla un pedazo sin lector.
- Si la conexión se cae sin que lo pidas, la app no se cierra: sigue intentando reconectar, como siempre.

## Versión 0.2.4 (4 de octubre de 2026)

### Novedades

- Nuevo ajuste en Ajustes, Avanzado: "Rapidez de tu doble toque". Define cuánto espera un toque sencillo a ver si llega el segundo. De fábrica es Rápida (200 milisegundos); Muy rápida (150) responde aún antes; Normal (300, la de Android) es para quien toca despacio o con temblor.

### Correcciones

- Con Jieshuo, cuando un bot jugaba poco después de ti, volvías a oír tu propia jugada antes de la suya. Ahora lo que la sala responde a lo que tú mandaste nunca se repite.
- Tocar con tres dedos (a quién le toca) y tocar dos veces con tres dedos (los puntos) se estorbaban entre sí. Ahora el toque sencillo espera un instante a ver si llega el segundo. Vale para uno, dos y tres dedos.

## Versión 0.2.3 (4 de octubre de 2026)

### Novedades

- Los gestos en ángulo de tu lector ya funcionan en la zona de juego. Son los de dos trazos seguidos con un dedo, como abajo y luego a la izquierda. Antes, con el toque directo, tu lector no los veía ahí. Ahora la sala los reconoce ella misma.
- De fábrica, en todos los juegos, abajo y luego a la izquierda hace lo mismo que el botón Atrás de Android. Los otros siete le devuelven la pantalla a tu lector un momento: oyes "Pantalla para tu lector: repite el gesto", lo haces otra vez y lo ejecuta tu lector.
- El toque directo vuelve solo en cuanto tu lector termina el gesto. Si abriste su menú, espera a que lo cierres. Si no haces nada, vuelve a los 5 segundos.
- Los ocho gestos en ángulo están en "Personalizar gestos", en un grupo propio, y se pueden cambiar como los demás, también solo para un juego.
- Acciones nuevas que puedes dar a cualquier gesto: "Atrás de Android", "Inicio de Android", "Apps recientes de Android", "Abrir las notificaciones" y "Devolver la pantalla al lector".
- La ayuda de gestos y la descripción del servicio del toque directo lo explican en español, inglés y francés.

### Correcciones

- En Android 14, el sistema apaga el toque directo cada vez que la app se actualiza desde un archivo. Ahora, al entrar a la sala, QC Sala lo nota y te dice una vez qué pasó y cómo volver a encenderlo.
- En Android 13, el botón "Abrir la información de la app" ya muestra el menú de tres puntos con "Permitir configuración restringida".
- Un gesto en ángulo dentro de la zona ya no se confunde con un deslizamiento recto. Si el trazo va en diagonal o quedó corto, la sala no adivina: suena el tope y no se mueve nada.
- Un deslizamiento normal, con el arco natural del pulgar o con temblor de la mano, vuelve a contar como deslizamiento.
- El toque directo ya no vuelve mientras tu lector tiene algo abierto encima, como su menú.
- Ya no estorba el aviso escrito en la pantalla, el rotor devuelve el juego como debe y, al cerrar el menú del lector, el juego responde enseguida.
- Con dos o tres dedos, un trazo en ángulo ya no cuenta como deslizamiento.

## Versión 0.2.2 (3 de octubre de 2026)

### Correcciones

- Las instrucciones del toque directo, dentro de la app y en los tres idiomas, ahora sirven para más versiones de Android (10, 13, 14, 15 y 16), incluido el aviso de "Configuración restringida" y qué hacer si no aparecen los tres puntos.
- Arriba de Ajustes, el renglón de avisos muestra hasta seis líneas en lugar de dos, para que quien tiene baja visión vea el aviso completo.

### Cambios

- Las guías de instalación en español, inglés y francés se corrigieron tras instalar la app paso a paso en varias versiones de Android: el aviso sin título de Android 10 y 13, la espera de casi un minuto en Android 16, el camino alterno a los tres puntos y qué hacer si el toque directo queda apagado después de actualizar.

## Versión 0.2.1 (3 de octubre de 2026)

### Correcciones

- La app se cerraba sola al entrar a la sala, justo después de iniciar sesión. Ya está arreglado.

## Versión 0.2.0 (3 de octubre de 2026)

La primera versión para compartir con amigos. Es un archivo APK de unos 4,7 MB, probado en teléfonos virtuales con Android 7 (de 32 bits), 10 y 15.

### Novedades

- La app habla español, inglés y francés. Con el teléfono en otro idioma, habla en inglés. En Android 13 o más puedes elegir el idioma de QC Sala sin cambiar el del teléfono.
- También entiende a la sala en esos tres idiomas, y la ayuda rápida se traduce a gestos en los tres. Los gestos y textos de los 46 juegos están traducidos.
- Toque directo: una zona de juego donde tus gestos llegan directo a la app, con cuadros y guías que explican cómo encenderlo, y que regresa solo a la app al activarlo.
- Gestos propios para cada juego, con "Personalizar gestos", y el cuadro con la lista de lo que hace cada gesto.
- Mantener tres dedos dice quién está en la mesa, en todos los juegos.
- Efectos de sonido de la sala, como el comodín de Uno que sube de tono.
- Opción de decir la carta que robas, en los juegos de cartas y de dominó (viene apagada).
- Ninety nine como en el programa de escritorio, con una casilla para que al robar diga que robaste en lugar de repetir la cuenta (viene apagada).
- Aviso cuando la sala no contesta al zumbador o al farol de Uno, citando la regla.
- Cuadro para dar el permiso de avisos, que no insiste sin fin.
- Nueva pantalla de entrada, más clara para el lector de pantalla y compatible con los gestores de contraseñas.
- Guías nuevas: instalación en español, inglés y francés, y la guía fácil también en inglés y francés.

### Correcciones

- Más de cien detalles pulidos con ayuda de revisores de español, inglés y francés: frases mejor dichas, formatos de número según el idioma, la ayuda rápida mejor interpretada y ajustes de Android que se abren sin perderte.
- Cuando le pedías algo a la sala, como a quién le toca, a veces no oías la respuesta si justo jugaba un bot. Ya no pasa.
- Un mensaje del chat o un aviso general que llegaba justo antes de un aviso del juego podía hacer que este se callara. Ya no.
- Si cambiabas el idioma de la sala y la conexión se cortaba un momento, la app volvía a entrar en el idioma nuevo a media partida. Ahora el cambio vale hasta la próxima vez que entres.
- El cuadro del permiso de avisos ya no sale a media partida.

### Cambios

- El botón Robar y la ayuda básica dicen la acción sin nombrar teclas.
- El registro de depuración viene apagado de fábrica.

## Versión 0.1.0, prototipo (29 de septiembre de 2026)

### Novedades

- Entrada a la sala con la página oficial de inicio de sesión dentro de la app (la app no ve ni guarda tu contraseña), o con un formulario propio de respaldo.
- Conexión directa con el servidor del juego, como el cliente de escritorio y el web.
- Todo lo que dice la sala sale por tu lector de pantalla (Jieshuo, TalkBack u otro), con su voz, su velocidad y su braille.
- Historial con los 10 canales y sus vistas.
- Menús de la sala como listas accesibles, y cuadros para escribir texto o contestar sí y no.
- Botones grandes para jugar, robar, consultas y más opciones.
- Sonidos de la sala, con paneo, tono y tres volúmenes (efectos, notificaciones y música).
- Se mantiene conectada con la pantalla apagada, con un aviso fijo y un botón Desconectar.
- Reconexión automática.
- Gestos con dos dedos: doble toque para confirmar, abajo para robar, arriba para consultas, a los lados para el historial.
- Ajustes de volumen, canales que hablan y pantalla encendida durante la partida.
- Funciona en teléfonos de 32 y de 64 bits, desde Android 7.0.

### Correcciones

- Se arregló la conexión segura con el servidor de la sala, que sin esto no habría funcionado en ningún teléfono.
- Se evitó que la música del teléfono arrancara por error con el doble toque.
- Un deslizamiento corto ya no se convierte en un toque que elige algo sin querer.
- Un error al procesar un mensaje del servidor ya no cierra la app.

---

## In English

### Version 1.0.5 (October 8, 2026)

- New: the table's audio sample. At a table, in More options, in the "Table and playroom" group, right after "Table management", there is a new "Audio sample" option. If you are the table master, the playroom asks you for a link: a radio station or an audio file with a direct link (for example from Dropbox with dl.dropbox; a page that asks you to tap "Download" won't work). Everyone else at the table turns it on or off with the same option. If the master taps it again, it stops, and the master can set another. It plays at the "music and streams" volume. You can also put it on a gesture, in Customize gestures (no gesture has it by default). (Idea by Un_Duendementor.)
- New: volumes without leaving the playroom. In More options, in the "Help, settings and exit" group, right before "App settings", there is "Volumes": it opens a dialog with the three sliders (sounds, notifications, and music and streams), which you raise or lower with your screen reader's gesture, and a "Close" button. There are also three new actions for your gestures, in Customize gestures (no gesture has them by default): "Switch to the next volume" (it jumps between sounds, notifications, and music and streams, and tells you which one it is and its percentage), "Volume up" and "Volume down" (in steps of 10). (Idea by Un_Duendementor.)
- Radio stations and audio samples with http links, unencrypted, now play (before, they didn't). The app tries the encrypted version first and, if it doesn't open within a few seconds, the other one. This is only done for radio stations and audio samples: everything else stays encrypted, always.
- Fix: if the app is reopened while you are at a free table, leaving the table no longer asks twice.

### Version 1.0.4 (October 7, 2026)

- New gesture to jump to the first or last item of the game area. With one finger, swipe up and, without lifting it, back down: you go to the first item. Swipe down and then back up: you go to the last one. It also works in the history (first and last message of the view) and it is among the screen reader actions of the game area ("First item in the area" and "Last item in the area"). You can change it in Customize gestures, like the others. (Idea by Mortaccio.)
- After updating, the first time you open the app a dialog shows what's new in that version, with a "Back to the game" button (or "Close" when you're not in the playroom). In Settings, under Updates, the "What's new in this version" button opens it again.
- The app now checks for a new version when you open it and every three hours while it is open and connected (before: once a day). There is also a new setting in Settings, under Updates: "Notify me during a game". With "When you leave the table" (the default), the app tells you by voice, once, that a new version is out, and the dialog appears when you leave the table. With "Right away", the dialog appears even while you're playing; when you update, Android closes the app and you leave the game.
- The "Not now" button in the "A new version is available" dialog is now called "Later", and the next time you open the app it offers that version again.
- The "A new version is available" dialog no longer cuts off buttons with the phone in landscape or with large text, and its notes appear in your app's language.

### Version 1.0.3 (October 7, 2026)

- The app is almost three times smaller (from about 4.7 MB to 1.7 MB), better protected inside, and works the same. Your settings and gestures are kept when you update.

### Version 1.0.2 (October 4, 2026)

- New: QC Sala now updates itself. Once a day it asks GitHub, the site where it's published, whether there is a new version; all it sends is the app's name and version number. If there is one, a dialog shows the version, the download size and what's new, with "Update" and "Not now". "Update" downloads it and opens Android's own installer, and you confirm. The first time, Android asks you to let QC Sala install apps; the app explains it and opens that setting for you.
- Settings has a new "Updates" section with the installed version, a "Check for updates" checkbox (on by default) and a "Check for updates now" button.
- Safety: it only installs a file that is really QC Sala, newer than yours, and signed with the same key as the app you have. Your session, settings, gestures and direct touch are kept, also on Android 14.

### Version 1.0.1 (October 4, 2026)

- New: the app now checks whether Android could put QC Sala to sleep while the screen is off and cut you off from the room. In Settings, a button lets you allow QC Sala to stay connected in the background. The room suggests it once.

### Version 1.0.0 (October 4, 2026): first official release

- Everything from the 0.2 series in one release: the app in Spanish, English and French, the direct touch zone, angle gestures, "Leave the room" that fully closes the app, and no computer key names anywhere.
- Fixes: if you did not tick "Remember my details", leaving the room now asks you to sign in again next time. Tapping a room notification returns you to the same room with your chat draft. Several small tidy-ups.
- Extra safety: the app never follows a redirect that could send your pass to another server.

## En français

### Version 1.0.5 (8 octobre 2026)

- Nouveau : le flux audio de la table. À une table, dans « Plus d’options », groupe « Table et Salon », juste après « Gestion de la table », se trouve la nouvelle option « Flux audio ». Si vous êtes le chef de table, le Salon vous demande un lien : une radio ou un fichier audio avec un lien direct (par exemple de Dropbox avec dl.dropbox ; une page qui demande d’appuyer sur « Télécharger » ne convient pas). Les autres joueurs de la table l’activent ou la coupent avec la même option. Si le chef de table appuie de nouveau dessus, le flux s’arrête, et il peut en proposer un autre. Il est joué au volume « musique et flux ». Vous pouvez aussi le mettre sur un geste, dans Personnaliser les gestes (aucun geste ne l’a par défaut). (Idée de Un_Duendementor.)
- Nouveau : les volumes sans quitter le Salon. Dans « Plus d’options », groupe « Aide, paramètres et sortie », juste avant « Paramètres de l’appli », se trouve « Volumes » : une fenêtre avec les trois barres (son, notifications, et musique et flux), que vous montez ou baissez avec le geste de votre lecteur d’écran, et un bouton « Fermer ». Il y a aussi trois nouvelles actions pour vos gestes, dans Personnaliser les gestes (aucun geste ne les a par défaut) : « Passer au volume suivant » (elle passe du son aux notifications, puis à musique et flux, et vous dit lequel c’est et son pourcentage), « Monter le volume » et « Baisser le volume » (par pas de 10). (Idée de Un_Duendementor.)
- Les radios et les flux audio dont le lien commence par http, sans chiffrement, se font maintenant entendre (avant, non). L’appli essaie d’abord la version chiffrée et, si elle ne s’ouvre pas en quelques secondes, l’autre. Cela ne vaut que pour les radios et les flux audio : tout le reste reste toujours chiffré.
- Correction : si l’appli est rouverte alors que vous êtes à une table libre, quitter la table ne pose plus la question deux fois.

### Version 1.0.4 (7 octobre 2026)

- Nouveau geste pour aller au premier ou au dernier élément de la zone de jeu. Avec un doigt, balayez vers le haut puis, sans le lever, vers le bas : vous allez au premier élément. Vers le bas puis vers le haut : vous allez au dernier. Il fonctionne aussi dans l’historique (premier et dernier message de la vue) et fait partie des actions du lecteur d’écran de la zone de jeu (« Premier élément de la zone » et « Dernier élément de la zone »). Vous pouvez le modifier dans Personnaliser les gestes, comme les autres. (Idée de Mortaccio.)
- Après une mise à jour, la première fois que vous ouvrez l’appli, une fenêtre présente les nouveautés de cette version, avec le bouton « Retour au jeu » (ou « Fermer » si vous n’êtes pas dans le Salon). Dans les Paramètres, section Mises à jour, le bouton « Nouveautés de cette version » la rouvre.
- L’appli cherche maintenant une nouvelle version à son ouverture, puis toutes les trois heures tant qu’elle est ouverte et connectée (avant : une fois par jour). Un nouveau réglage apparaît aussi dans les Paramètres, section Mises à jour : « Me prévenir en pleine partie ». Avec « En quittant la table » (réglage par défaut), l’appli vous annonce à voix haute, une seule fois, qu’une nouvelle version existe, et la fenêtre apparaît quand vous quittez la table. Avec « Tout de suite », la fenêtre apparaît même pendant que vous jouez ; en cas de mise à jour, Android ferme l’appli et vous quittez la partie.
- Le bouton « Pas maintenant » de la fenêtre « Une nouvelle version est disponible » s’appelle désormais « Plus tard », et la prochaine fois que vous ouvrez l’appli, elle vous propose de nouveau cette version.
- La fenêtre « Une nouvelle version est disponible » ne coupe plus de boutons quand le téléphone est à l’horizontale ou que la police est grande, et ses notes s’affichent dans la langue de votre appli.

### Version 1.0.3 (7 octobre 2026)

- L’appli est presque trois fois plus légère (de 4,7 Mo environ à 1,7 Mo), mieux protégée à l’intérieur, et fonctionne pareil. Vos paramètres et vos gestes sont conservés lors de la mise à jour.

### Version 1.0.2 (4 octobre 2026)

- Nouveau : QC Sala se met maintenant à jour toute seule. Une fois par jour, elle demande à GitHub, le site où elle est publiée, s'il existe une nouvelle version ; elle ne lui envoie que le nom de l'application et son numéro de version. S'il y en a une, une fenêtre indique la version, le poids du téléchargement et les nouveautés, avec « Mettre à jour » et « Pas maintenant ». « Mettre à jour » la télécharge et ouvre l'installateur d'Android, puis vous confirmez. La première fois, Android vous demande d'autoriser QC Sala à installer des applications ; l'application l'explique et ouvre ce réglage pour vous.
- Les Réglages ont une nouvelle section « Mises à jour » avec la version installée, la case « Rechercher les mises à jour » (cochée par défaut) et le bouton « Rechercher les mises à jour maintenant ».
- Sécurité : elle n'installe qu'un fichier qui est bien QC Sala, plus récent que le vôtre et signé avec la même clé que l'application que vous avez. Votre session, vos réglages, vos gestes et le toucher direct sont conservés, y compris sous Android 14.

### Version 1.0.1 (4 octobre 2026)

- Nouveau : l'application vérifie maintenant si Android risque de mettre QC Sala en veille écran éteint et de vous couper de la salle. Dans les Réglages, un bouton permet d'autoriser QC Sala à rester connectée en arrière-plan. La salle vous le suggère une seule fois.

### Version 1.0.0 (4 octobre 2026) : première version officielle

- Tout ce qui vient de la série 0.2 réuni : l'application en espagnol, anglais et français, la zone de toucher direct, les gestes en angle, « Quitter la salle » qui ferme complètement l'application, et plus aucun nom de touche d'ordinateur.
- Corrections : si vous n'avez pas coché « Se souvenir de mes données », quitter la salle demande maintenant de vous reconnecter la fois suivante. Toucher une notification de la salle vous ramène à la même salle avec votre brouillon de chat. Plusieurs petits ajustements.
- Sécurité en plus : l'application ne suit jamais une redirection qui pourrait envoyer votre jeton vers un autre serveur.
