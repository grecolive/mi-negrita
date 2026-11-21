# Mi negrita

Para mi negrita hermosa.

## Uso y almacenamiento

Sirve esta carpeta con cualquier servidor web estático y abre la página en el
navegador. No necesita Firebase ni un servidor de aplicaciones. Cada cambio de
paso y cada respuesta de la trivia se guardan automáticamente como JSON en el
`localStorage` del navegador; al volver, se recuperan el paso, la pregunta y la
respuesta seleccionada. La respuesta final también se guarda allí.

El almacenamiento pertenece al navegador y al origen de la página: no se
comparte automáticamente entre dispositivos, navegadores ni distintas
direcciones. Borrar los datos del navegador también elimina el progreso. El
guardado puede no estar disponible en navegación privada o al abrir el archivo
directamente; la página muestra un aviso si falla.

## Panel del creador

Abre el panel con el botón del candado y el token configurado en `index.html`.
El panel muestra el JSON actual, permite descargar un respaldo, importar uno
(reemplazando el progreso local) o reiniciar el estado. Para trasladar los datos
a otro dispositivo, exporta el JSON y luego impórtalo desde el panel de ese
dispositivo. La descarga es manual: una página estática no puede actualizar
automáticamente un archivo JSON en el disco.

El token está en el código público y **no protege los datos**. No almacenes
información sensible en esta página. Los datos anteriormente guardados en
Firebase no se migran automáticamente.

## Música

La página intenta reproducir la música al abrirse. Algunos navegadores bloquean
el audio automático hasta que se interactúa con la página; en ese caso, pulsa
el botón de música para iniciarla.

La pista incluida es el «Intermezzo Sinfónico» de la ópera *Cavalleria
Rusticana*, compuesto por Pietro Mascagni (obra de dominio público) e
interpretado por la Fulda Symphonic Orchestra. Fuente:
[Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Pietro_Mascagni_-_Cavalleria_Rusticana_-_Intermezzo_Sinfonico.ogg).
Licencia: [EFF Open Audio License v1.0](https://commons.wikimedia.org/wiki/Commons:Open_Audio_License) (requiere atribución).
