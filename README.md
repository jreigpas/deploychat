# deploychat

hay que construir la aplicacion:
npm run build:production

el resultado en la carpeta build, hay que extraer:

el código de index.html para construir el script para desplegar en GTM

los 3 ficheros (2 js y 1 css), renombrarlos y poner exactamente la ruta en el script anterior.

# Para desplegar se pasa una carpeta con los dos scripts js y el fichero de css:


<link href="https://www.madrid.es/Datelematica/chatbotlm/css/nttbot.css" rel="stylesheet">
<div id="root"></div>
<script>xxxxxxxx</script>
<script src=".https://www.madrid.es/Datelematica/chatbotlm/scripts/nttbotuno.js"></script>
<script src="https://www.madrid.es/Datelematica/chatbotlm/scripts/nttbotdos.js"></script>
