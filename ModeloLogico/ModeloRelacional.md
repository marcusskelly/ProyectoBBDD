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
* Retransmision(Retransmision_id PK, canal, duracion, idioma, ingreso
* Merchandising(Merchandising_id, categoria, gama, ingresos, artista_id FK
* Patrocinador(Patrocinador_id PK, nombre, sector,tipoContrato,duracionContrato,ingreso
* Backstage_catering(Backstage_id PK,Catering_id PK