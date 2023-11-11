**NOTA:** *La base de datos .lsm SE PUEDE ABRIR EN FIJI y a partir de ahí abrir las imágenes.*

Chequeado: todas las imágenes tienen la misma escala (11.09 px/um en X e Y)

Excepto 20231012SetupFinal.lsm, todas las otra imágenes tienen el mismo tamaño (1556x702)

Las imágenes tienen una profundidad de 8 bits --> no convendría para el ratio usar 16bits?

20231012SetupFinal(51.lsm - **NO SIRVE PARA ANALIZAR**, está muy saturada
El resto OK, aunque hay algunos px saturados.

Las fotos 2D parecen estar sacadas con menor velocidad (mayor pixel dwell) o más average porque tienen mejor SNR --> **CHEQUEAR CON EL AIM**

Creo que lo mejor armar un pequeño MACRO en FIJI para separar los canales y poder ahcer el procesamiento en CellProfiler (va a ser ligeramente diferente calculo para las imagenes 2D y 3D)
Podemos comparar los rtdos con algo hecho a mano en FIJI (armar ROIs a mano y medirlos... GUARDAR LOS ROI ELEGIDOS!)