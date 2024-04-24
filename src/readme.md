Soy un readme.
Memoria caché
La mayoría de las CPUs tienen tres cachés (L) para almacenar
los datos necesarios para terminar las tareas y acceder de
una forma más rápida que si tuviera que ir a la RAM a 
buscarlos. Estas cachés se denominan L1, L2 y L3, y la 
cantidad de datos que almacenan aumenta con cada nivel. Si
los datos que necesita el procesador no están en la caché 
L1, los buscará en la caché L2, y si no está allí la
buscará en la L3, y de no estar lo hará en la RAM, cada 
uno de estos niveles con mayor latencia e impacto en los 
ciclos de reloj.
Al ser una memoria SRAM y estar integrada dentro del propio 
procesador, son muy rápidas, necesitando pocos ciclos para 
su acceso. A medida que aumenta la capacidad de la caché, se 
tarda más en localizar los datos que necesita un procesador,
por lo que las cachés L son relativamente pequeñas en 
tamaño.. La memoria RAM es mucho más grande que la caché,
sin embargo, penaliza más en sus accesos.