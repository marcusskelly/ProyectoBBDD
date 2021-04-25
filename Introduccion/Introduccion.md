# Introduccion

Una empresa organizadora de eventos desea diseñar una base de datos para gestionar los festivales anuales pertenecientes al Quevedo Fest.

1. Definicion de principales tablas que contiene el proyecto

* El cartel del festival contiene la fecha de inicio del festival, fecha finalizacion, lugar donde se celebra, presupuesto. 
* Para un cartel de un año, se cuenta con varios artistas que tienen un genero musical, edad , nombre, precioy caché. Un mismo artista puede estar presente en carteles de varios años. 
* El artista cuenta con un backstage durante su actuacion, y un mismo artista puede alojarse en varios durante la duración del festival. Cuenta con un gasto, numero de mesas, y tamaño.
* El escenario alberga la actuación de los artistas, que a su vez tocan en varios escenarios durante el festival. Cuenta con una extension, un tipo(principal,secundario,techado, etc) y genera un gasto.

2. Principales tablas que se refieren a empresas contratadas por el festival

* Junto con el cartel del festival, se menciona a varias empresas contratadas que tienen un nombre, precio, numero de trabajadores empleado en festival, director, telefono y direccion.
* Estas empresas pueden ser de webs que promocionan el carteñ y contienen canales de promocion como fb,twitter e instagram. Seguridad que supervisan el escenarios y su correspondiente backstage. 
* Grabacion que retransmite lo que pasa en el escenario mediante camaras situadas en diferentes puntos. 
* Una empresa de sonido que captan a traves de microfonos
* Una empresa de iluminacion que se encarga de la iluminacion de los escenarios mediante focos, y finalmente una empresa de catering que sirven a backstages cierto tipo de comida.
* Cada empresa de grabacion y sonido, puede hacer varias retransmisiones que tienen cierta duracion, a traves de varios canales en distintos idiomas y lugares del mundo. Esto genera ingresos. Una retransmision en especifico, es realizada por una empresa. 

3. El artista cuenta con patrocinadores y merchandising. Se contempla el hecho de que el festival se queda con el dinero que esto produzca

* Un artista puede tener varios patrocinadores, y un patrocinador puede trabajar con varios artistas. Patrocinador tiene un nombre, sector, tipo de contrato,duracion y genera unos ingresos.
* El artista tambien cuenta con su propio merchandising que tiene una categoria, gama e ingresos.

* La web anuncia el cartel del festival cada año. Mediante la web se venden las entradas que tienen un precio, un formato, una fecha de compra, un plazo de devolucion y una categoria.
 
