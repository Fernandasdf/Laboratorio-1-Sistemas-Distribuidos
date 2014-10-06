Laboratorio-1-Sistemas-Distribuidos
===================================

Primer laboratorio desarrollado por Camilo Jiménez y Fernanda Lobos. 

Está escrito en nodeJS, donde se utilizan las siguientes dependencias:
-socket.IO: permite la comunicación bidireccional en tiempo real.
-express: framework de aplicaciones web para nodeJS

Además, se hace uso de la herramienta OpenTok para el streaming de audio y video.
OpenTok no es gratis, por lo que hasta el momento se está usando la licencia de 30 días de prueba para el desarrollo
de este laboratorio. 
Para inicir el chat, es necesario una apiKey, una sessionID y un token. 
  -apiKey: identifica una cuenta en OpenTok
  -sessionID: identifica el chatroom en donde los participantes chatearán.
  -token: es una clave que permite el ingreso a un chatroom determinado.
Para obtener estos datos, debe crearse una cuenta en tokbox (https://tokbox.com/opentok/v1/quick-start/)
luego en dashboard (https://dashboard.tokbox.com/) debe hacer click en "View Details". Aquí es donde usted verá
su apiKey, creará una sessionID, y generará tokens. Estos datos debe pegarlos en el atributo correspondiente en el archivo
index.html
