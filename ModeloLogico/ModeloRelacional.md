# Tablas de QuevedoFest

* Cartel(cartel_id PK, fechaInicio,fechaFin,ubicacion,presupuesto,titulo
* Artista(Artista_id PK,genero,edad,nombre,precio,cache
* Backstage(Backstage_id PK, gasto, num_mesas, tamaño,Escenario_id FK
* Escenario(Escenario_id PK, extension, tipo, gasto
* Empresa(Empresa_id PK, nombre, gasto,tamaño,nombre_director,telefono,direccion
* Web(Empresa_id FK, redes_sociales,servidor,url
* Seguridad(Empresa_id FK
* Catering(Empresa_id FK
* Grabacion(Empresa_id FK
* Sonido(Empresa_id FK
* Iluminacion(Empresa_id FK
* Retransmision(Retransmision_id PK, canal, duracion, idioma, ingreso,tipo,empresa_id FK,empresa_id FK
* Merchandising(Merchandising_id, producto, gama, ingresos,talla, artista_id FK
* Patrocinador(Patrocinador_id PK, nombre, sector, direccion,telefono
* Artista_Escenario(Artista_id_FK,Escenario_id FK,duracion_actuacion
* Artista_Patrocinador(Artista_id FK,Patrocinador_id FK,tipoContrato,duracionContrato,ingreso
* Cartel_Empresa(Cartel_id FK, Empresa_id FK,trabajadores_contratados
* Entradas(Entradas_id PK,precio,formato,categoria,plazo_devolucion,fecha_compra,Empresa_id FK
* Seguridad_Escenario(Empresa_id FK, Escenario_id FK,num_trabajadores
* Seguridad_Backstage(Backstage_id FK,Empresa_id FK,num_trabajadores
* Catering_Backstage(Backstage_id FK,Empresa_id FK,tipoComida
* Iluminacion_Escenario(Empresa_id FK,Escenario_id FK,situacion_escenario,numero_focos
* Grabacion_Escenario(Empresa_id FK,Escenario_id FK,situacion_escenario,numero_camaras
* Sonido_Escenario(Empresa_id FK,Escenario_id FK,situacion_escenario,numero_micros
* Cartel_Artista(artista_id FK,cartel_id FK
