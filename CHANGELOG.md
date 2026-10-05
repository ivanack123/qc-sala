# Registro de cambios de QC Sala

QC Sala es una app no oficial para Android, hecha para jugar en la Sala de Juegos de QuentinC (qcsalon.net) con lector de pantalla. Aquí van todos los cambios, de lo más nuevo a lo más viejo.

El número de versión tiene tres partes: la primera sube con un gran salto, la segunda con funciones nuevas y la tercera con correcciones pequeñas.

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
