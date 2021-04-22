# Introduccion

1. Definicion de principales tablas que contiene el proyecto
* Un cartel alberga a muchos artistas. El cartel cuenta con un id, una fecha, lugar y hora
* Un artista tiene genero, edad , nombre , caché. Cada artista tiene su camerino y su backstage, además del escenario en el cual tocan.
* El backstage contiene un tamaño, numero de mesas, nivel de servicio, numero de botellas. Varias empresas de catering pueden servir a varios backstages, y varios backstages son servidos por varias empresas
* El catering contiene un nombre, tipo de comida, categoria de servicio
* Un cartel cuenta con una web en el que sale toda su informacion. Esta web tiene una URL, numero de paginas , tecnologia principal usada e idioma
* Varias entradas pueden ser para un mismo cartel, mientras que el cartel cuenta con un tipo de entradas. Estas entradas tiene un tamaño y un formato
* Varios artistas tocan en varios escenarios, y un artista puede tocar en varios escenarios.
2. Principales tablas que se refieren al equipo del escenario
* Un escenario puede tener varias empresas de seguridad, y una empresa de seguridad puede estar presente en un escenario. La misma regla se aplica a backstage. La seguridad tiene un nombre y un numero de empleados
* La actuacion del escenario se graba por varias empresas para su posterior retransmision. Un escenario puede ser grabado por varias empresas, y una empresa puede grabar varios escenarios. La grabacion tiene un numero de camaras, localizacion
* Una retransmision es producida por varias grabaciones, y una grabacion puede ser usada para diferentes canales. Retransmision tiene canal, duracion e idioma
* Una empresa de sonido puede estar presente en varios escenarios y viceversa. Esta cuenta con numero de trabajadores, tipo de sonido
* Una empresa de iluminacion puede estar presente en varios escenarios y viceversa. Esta cuenta con numero de trabajadores, tipo de luz , numero de focos
3. El artista cuenta con patrocinadores y merchandising. Se contempla el hecho de que el festival se queda con el dinero que esto produzca
* Un artista puede tener varios patrocinadores, y un patrocinador puede trabajar con varios artistas. Patrocinador tiene sector, tipo de contrato y duracion
* Un artista cuenta con su propio merchandising que esta dirigido por varias empresa, mientras que estas mismas empresa pueden trabajar con varios artistas. El merchandising tiene un formato, un canal y tipo de producto

## Hay que tener en cuenta que habrá dos tablas principales llamadas ingresos y gastos que estarán relacionadas con el resto de las tablas mediante claves foraneas. La relacion será de 1,1 a 1,n, siendo cada tabla un solo canal de gastos o ingresos.
 
