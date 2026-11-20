# Noxmera Launcher

Descargas oficiales para Windows x64. Versión estable: **0.1.35**.

- [Descargar instalador](https://github.com/cchelooo/noxmera-downloads/releases/download/v0.1.35/Noxmera-Setup-0.1.35-windows-x64.exe)
- [Descargar ZIP portable](https://github.com/cchelooo/noxmera-downloads/releases/download/v0.1.35/Noxmera-windows-x64.zip)
- [Notas de la versión](https://github.com/cchelooo/noxmera-downloads/releases/tag/v0.1.35)

El instalador conserva tus instancias y ajustes. Para usar el ZIP, extráelo y abre `Noxmera.exe`.
Si ya tienes Noxmera, puedes actualizar desde **Ajustes → General → Actualizador**, al cerrar o reiniciando el launcher.

La 0.1.35 hace copias automáticas de tus mundos antes de que una actualización de Global o Sync cambie la instancia (guarda las 3 más nuevas de cada mundo), y en Mundos puedes hacer una copia o restaurar cualquiera sin perder nada. La sección Mods del editor revisa la instancia antes de jugar (un mod obligatorio que falta, dos mods incompatibles o un mod repetido) y ofrece descargarlo o desactivarlo ahí mismo. Con Ctrl+Enter (o en Ajustes → General) ves todos los atajos de teclado y puedes cambiarlos. Los modpacks de CurseForge (como All the Mods) con archivos que solo se descargan desde la web usan la misma ventana que los de Modrinth: el enlace abre la descarga directa y Noxmera recoge cada archivo de tu carpeta Descargas. Además, los modpacks con FancyMenu ya no cambian tu escala de interfaz en el primer arranque, las instancias con mods muy grandes (como Chisel) se pueden volver a publicar en Global y Quilt deja de ofrecerse al crear instancias (las existentes siguen funcionando).

La 0.1.34 añade un asistente de errores: si Minecraft se cierra por un error, la consola explica la causa en simple (una dependencia que falta o en otra versión, mods incompatibles o duplicados, Java antiguo, falta de memoria) y ofrece arreglarlo con un clic: «Descargar el mod y reintentar» (la versión exacta que pide el mod cuando es posible) o «Desactivar el mod y reintentar». Los modpacks de Modrinth que necesitan archivos que solo están en CurseForge (como Better MC) ya no se detienen dentro del juego: antes de lanzar, Noxmera muestra qué falta, descarga lo que CurseForge permite, abre el resto en tu navegador y lo recoge solo de tu carpeta Descargas. También avisa cuando Mojang limita las consultas (la skin o la entrada a servidores pueden fallar) y nombra a Essential si está instalado.

La 0.1.33 hace que los modpacks de Forge 1.8.9 (y otras versiones antiguas de Forge) arranquen bien. Las descargas ya no se quedan congeladas: si un servidor deja de enviar datos, Noxmera lo detecta en 45 segundos y reintenta, y los modpacks grandes y Java terminan también con conexiones lentas. Las esperas ahora se ven: las tarjetas de instancia muestran «Preparando… N%» con una barra mientras se prepara y «En juego» mientras juegas, y las listas, búsquedas y ventanas que cargan muestran una barra en movimiento. Antes de publicarla se probaron Vanilla, Forge, NeoForge, Fabric y Quilt desde la 1.7.10 hasta la última versión y varios modpacks populares de Modrinth.

La 0.1.32 corrige que, tras cerrar el launcher con Minecraft abierto, no se pudiera volver a abrir: ahora se abre de nuevo y la instancia en juego sigue marcada como en ejecución.

La 0.1.31 evita abrir el launcher dos veces: si ya está abierto, se enfoca la ventana existente y una misma instancia nunca se lanza dos veces por accidente. Las ventanas de Sync son iguales entre sí, con pestañas como en Ajustes y la lista fija al cambiar de pestaña. En ventanas pequeñas, el panel lateral avisa cuando hay más opciones abajo, y los nombres largos de las instancias se muestran completos al pasar el ratón.

La 0.1.30 añade un buscador con Ctrl+K: lleva directo a cualquier página, sección de Ajustes, instancia o búsqueda de Modrinth y CurseForge, y entiende el tipo si lo escribes («sodium mod», «bare bones texture pack»). En el catálogo ahora puedes elegir varias categorías a la vez y, en Modrinth, excluir las que no quieras. Ajustes → Almacenamiento muestra cuánto ocupa cada instancia y permite borrar los logs antiguos. Tu skin ya no desaparece en el juego al abrir Minecraft justo después del launcher, Ctrl+Retroceso y Ctrl+Supr borran palabras enteras e incluye varias correcciones de Sync, mods, skins y exportación.

La 0.1.29 añade Sync de Litematica: configura una vez tus opciones y atajos de Litematica y cada instancia nueva los recibe, con las mismas pestañas, valores y descripciones que en el juego (Litematica 1.16.1 a 26.3). Las teclas de Minecraft en Sync siguen ahora el orden y los nombres de la pantalla de controles del juego y solo incluyen teclas vanilla. Al grabar una tecla, Esc la deja sin asignar y «Cancelar» conserva la anterior. La caché de descargas ya no crece sin límite: 2 GB por defecto, configurable o vaciable en Ajustes → Almacenamiento. Los mensajes de error aparecen en el idioma de la interfaz.

La 0.1.28 acelera las actualizaciones de Global: el launcher descarga y reemplaza solo los archivos que cambiaron, sin copiar ni revisar de nuevo toda la instancia. En un modpack grande como Craftoria, actualizar un mod pasa de más de diez segundos a menos de uno, más la descarga. También recuerda los hashes de los archivos compartidos y solo vuelve a leer los que cambiaron. Tus archivos siguen protegidos: solo se reemplazan o borran los que coinciden con la versión anterior de Global, y si una actualización se interrumpe se restauran los originales al abrir el launcher.

La 0.1.27 acelera las descargas de Global: el launcher pide los archivos por lotes y varios a la vez. Un modpack de 470 MB que tardaba unos dos minutos y medio ahora baja en unos 20 segundos con una conexión rápida. Al suscribirte a una instancia Global se aplican tus ajustes de Sync desde el primer arranque; las copias instaladas antes pueden usar Apply Sync. Importar desde la carpeta de otro launcher copia varios archivos a la vez, lo que ayuda en modpacks con miles de archivos de configuración. Añade la pestaña Schematics para instancias con Litematica: un explorador para crear carpetas, añadir, renombrar, mover, copiar, pegar, exportar y borrar schematics, con menú de clic derecho.

La 0.1.26 acelera mucho Global: el servicio funciona junto a su almacenamiento y el launcher envía hasta ocho bloques a la vez. Un modpack de 1 GB que tardaba unos ocho minutos se publica en alrededor de minuto y medio con una conexión rápida, y los cambios pequeños en pocos segundos. Permite compartir modpacks grandes como Craftoria, con miles de archivos de configuración y scripts. Global abre más rápido, las tarjetas aparecen junto con su icono y el texto de progreso ya no parpadea. Retirar o dejar de compartir limpia correctamente las copias vinculadas, y cada ventana usa menos memoria. Esta versión es necesaria para publicar y ver instancias de Global.

La 0.1.25 mejora los diagnósticos de importación: separa el tiempo de apertura de los archivos de origen y el de creación de los archivos de destino, también al cancelar o fallar. Elimina un registro vacío que podía confundir al revisar los logs y conserva el buffer de copia de 1 MiB. Permite investigar la demora de Prism con más precisión; todavía no se anuncia una corrección de esa lentitud.

La 0.1.24 diferencia bytes, porcentaje y número de archivos durante las importaciones, y añade diagnósticos con tiempos y progreso incluso al cancelar para investigar copias lentas. Muestra una barra de actividad al borrar instancias y añade Stop following o Stop sharing, según quién sea el dueño, en los menús de instancias y Global. Los ajustes generales de Java y Minecraft aprovechan todo el ancho de la ventana.

La 0.1.23 agiliza las publicaciones de Global con dos envíos simultáneos de hasta 4 MiB. Conserva los buffers acotados para cuidar la RAM, reutiliza archivos repetidos y permite cancelar ambos envíos. El servicio R2 ya tiene habilitado el modo paralelo.

La 0.1.22 usa almacenamiento privado R2 para los nuevos archivos de Global, conserva las publicaciones anteriores de GitHub y transfiere bloques de hasta 4 MiB para cuidar la RAM y el procesamiento del servicio. Reanuda lo ya subido y mejora los reintentos tras una interrupción. Actualiza el launcher para descargar el contenido nuevo de Global. También permite combinar modpacks con instancias existentes desde una ventana con iconos y revisión de dependencias, añade filtros de snapshots y menú de clic derecho para mods, y mejora los ajustes y textos de la interfaz.

La 0.1.21 permite publicar en Global modpacks grandes, como Cobbleverse, junto con su configuración y scripts. Mantiene la lectura por bloques para cuidar la RAM, permite revisar los archivos y detecta conflictos al actualizar. El servicio Global ya está actualizado. Catpack acepta PNG con cualquier nombre, sin tener que renombrarlos a cat.png. Las nuevas instalaciones de modpacks de Modrinth y CurseForge guardan su icono y lo muestran sin reiniciar.

La 0.1.20 incorpora filtros de categoría en la descarga por instancia, manteniendo Modrinth/CurseForge y la compatibilidad con su versión de Minecraft y modloader. Reorganiza las acciones y conserva el scroll de las descripciones largas en ventanas pequeñas. Corrige la identificación de mods instalados en packs grandes, reduce reservas gráficas innecesarias en Windows y conserva los iconos al recorrer el gestor. También agiliza la importación y lectura de Sync, deja desmarcados los componentes ausentes, añade sliders de memoria Java y corrige errores al cerrar o redimensionar ventanas.

La 0.1.19 permite usar CurseForge con tu sesión de Minecraft, sin configurar una clave local: la clave de la aplicación permanece en el servicio Noxmera. Corrige mods con muchos recursos, como Conquest of Westeros, y modpacks que incluyen archivos temporales de mundos, como Cobblemon 1.8.4. Global añade ocultar/restaurar por dispositivo y retirada administrativa con confirmación; distingue Commit changes y Pull changes y ajusta la lista de permisos a sus usuarios. Aplicar mi Sync pasa a Ajustes → General de todas las instancias, omite mods ausentes y conserva los ajustes pendientes de compatibilidad. El servicio ya está actualizado.

La 0.1.18 añade cambios seleccionables en Global: mods, texture packs ZIP y servidores. Las exclusiones se guardan al publicar y se recuerdan en las siguientes publicaciones. Los packs incluyen activación y orden; las actualizaciones conservan el contenido y ajustes personales del receptor. También libera imágenes del catálogo tras 30 segundos sin foco, manteniendo búsquedas y descargas. El servicio Global está actualizado para estas funciones.

La 0.1.17 muestra imágenes y botones con enlaces en los README del catálogo de Modrinth y CurseForge. Conserva el tamaño natural de los botones, ajusta las capturas grandes al panel y mantiene juntas y alineadas las imágenes del mismo párrafo, pasando a otra línea solo cuando no caben. La carga se hace en segundo plano; los GIF se muestran con su primera imagen.

La 0.1.16 conserva la forma exacta del logo original en Monochrome, incluida la posición de la X, y adapta sus colores al fondo, texto y paneles del tema. El logo se renderiza según la escala de pantalla; Color/Monochrome actualiza los iconos de ventana y los accesos de Noxmera verificados en Inicio, escritorio y barra de tareas, conservando sus destinos y argumentos.

También permite seleccionar o quitar descargas desde la casilla del catálogo, ajusta el espacio entre tabla, ficha y buscador, y permite activar/desactivar archivos con Minecraft abierto tras un aviso que se puede recordar. Los mods ya cargados requieren reiniciar el juego para cambiar.

La 0.1.15 corrige la identidad de la aplicación en Windows para asociar sus ventanas con los accesos directos instalados y su grupo en la barra de tareas.

La 0.1.14 incorpora el logo de Noxmera, la elección Color/Monochrome en Appearance y los iconos de Windows por tema y escala de pantalla. También evita que los botones de navegación se compriman al faltar altura y aprovecha mejor el espacio de Recientes.

La 0.1.13 añade buscadores y selección múltiple en el editor, reorganiza sus controles y muestra la ficha del mod sobre Search. Status activa o desactiva archivos sin recargar la lista ni perder el scroll. Las ventanas nuevas siguen el monitor de origen, los campos permiten deshacer/rehacer y los temas incluyen Accent hover.

La 0.1.12 añade exportación e importación de Sync por configuración e importación desde instancias con vista previa y lectura automática. También reúne los botones de transferencia en una fila y corrige Sodium Extra al importar la opción de niebla desactivada.

La 0.1.11 corrige el indicador de actualizaciones Global para el dueño del modpack cuando un editor publica una revisión nueva. También mejora los logs de diagnóstico de actualizaciones pendientes.

La 0.1.10 corrige los controles de minimizar, maximizar y cerrar de las ventanas de Sync de JEI, REI y EMI, y oculta Add cuando solo se admite un atajo.

Incluye las novedades de la 0.1.9: Sync personal de JEI, REI y EMI para las versiones revisadas de Minecraft 26.2; logs exportables; publicadores OP, iconos y avisos de actualización en Global; y mejoras de fluidez en Skins y las barras de carga.

Para usar Global, inicia sesión con tu cuenta de Minecraft. Los jugadores no necesitan una cuenta de GitHub.

Las releases incluyen los metadatos firmados que verifica el actualizador y `SHA256SUMS.txt` para comprobar los archivos.

