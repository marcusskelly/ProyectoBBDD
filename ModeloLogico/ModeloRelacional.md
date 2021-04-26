# Principales tablas

* Cartel(cartel_id PK, fechaInicio,fechaFin,lugar,presupuesto
* Artista(Artista_id PK,genero,edad,nombre,precio,cache
* Backstage(Backstage_id PK, gasto, num_mesas, tamaño,Escenario_id FK
* Escenario(Escenario_id PK, extension, tipo, gasto
* Empresa(Empresa_id PK, nombre, precio,trabajadores_contratados,director,telefono,direccion
* Web(Empresa_id FK, especializacion
* Seguridad(Empresa_id FK
* Grabacion(Empresa_id FK, situacion_escenario,numero_camaras
* Sonido(Empresa_id FK, situacion_escenario,numero_micros
* Iluminacion(Empresa_id FK ,situacion_escenario,numero_focos
* Retransmision(Retransmision_id PK, canal, duracion, idioma, ingreso,Grabacion_id FK,Sonido_id FK
* Merchandising(Merchandising_id, categoria, gama, ingresos, artista_id FK
* Patrocinador(Patrocinador_id PK, nombre, sector,tipoContrato,duracionContrato,ingreso
* Backstage_catering(Backstage_id FK,Catering_id FK
* Artista_Escenario(Artista_id_FK,Escenario_id FK
* Artista_Merchandising(Artista_id FK,Merchandising_id FK
* Artista_Patrocinador(Artista_id FK,Patrocinador_id FK
* Cartel_Empresa(Cartel_id FK, Empresa_id FK
* Entradas(Entradas_id PK,precio,formato,categoria,plazo_devolucion,fecha_compra,Web_id FK
* Seguridad_Escenario(Seguridad_id FK, Escenario_id FK
* Seguridad_Backstage(Backstage_id FK,Seguridad_id FK
* Catering_Backstage(Backstage_id FK,Catering_id FK
* Iluminacion(Iluminacion_id FK,Escenario_id FK
* Grabacion_Escenario(Grabacion_id FK,Escenario_id FK
* Sonido_Escenario(Sonido_id FK,Escenario_id FK
