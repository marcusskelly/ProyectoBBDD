# Modelo Fisico QuevedoFest 

## En este modelo se incluyen las tablas pertenecientes a QuevedoFest para su posterior creacion en la base de datos `QuevedoFest`

Tabla `cartel`

    CREATE TABLE cartel(
    cartel_id NUMERIC(6) NOT NULL CONSTRAINT cartel_id_pk PRIMARY KEY,
    fechaInicio DATE NOT NULL,
    fechaFin DATE NOT NULL,
    ubicacion VARCHAR(30) NOT NULL,
    presupuesto INTEGER NOT NULL,
    titulo VARCHAR(30) NOT NULL
    );

Tabla `artista`

    CREATE TABLE artista(
    artista_id NUMERIC(6) NOT NULL CONSTRAINT artista_id_pk PRIMARY KEY,
    edad VARCHAR(30) NOT NULL,
    nombre VARCHAR(30) NOT NULL,
    cache VARCHAR(30) NOT NULL,
    sexo VARCHAR(30) NOT NULL,
    CONSTRAINT artista_cache_fk FOREIGN KEY(cache) REFERENCES cache_artista(cache),
    CONSTRAINT artista_genero_ck CHECK (sexo IN ('M', 'V')),
    CONSTRAINT artista_cache_ck CHECK (cache IN ('bajo','medio','alto','muy alto'))
    );

Tabla `cache_artista`

    CREATE TABLE cache_artista(
    cache VARCHAR(30) NOT NULL CONSTRAINT cache_pk PRIMARY KEY,
    precio INTEGER NOT NULL,
    CONSTRAINT cache_artista_cache_ck CHECK (cache IN ('bajo','medio','alto','muy alto'))
    );

Tabla `backstage`

    CREATE TABLE backstage(
    backstage_id NUMERIC(6) NOT NULL CONSTRAINT backstage_id_pk PRIMARY KEY,
    gasto INTEGER NOT NULL,
    num_mesas SMALLINT,
    tamaño VARCHAR(30) NOT NULL,
    escenario_id NUMERIC(6) NOT NULL,
    CONSTRAINT backstage_escenario_id_fk FOREIGN KEY(escenario_id) REFERENCES escenario(escenario_id),
    CONSTRAINT backstage_tamaño_ck CHECK (tamaño IN ('pequeño','medio','grande','muy grande'))
    );

Tabla `escenario`

    CREATE TABLE escenario(
    escenario_id NUMERIC(6) NOT NULL CONSTRAINT escenario_id_pk PRIMARY KEY,
    gasto INTEGER NOT NULL,
    extension VARCHAR(30) NOT NULL,
    tipo VARCHAR(30)NOT NULL,
    aforo VARCHAR(30) NOT NULL,
    nombre VARCHAR(30) NOT NULL,
    CONSTRAINT escenario_extension_ck CHECK (extension IN ('pequeño','medio','grande','muy grande')),
    CONSTRAINT escenario_tipo_ck CHECK (tipo IN ('cubierto','aire libre','techo retractil'))
    );

Tabla `empresa`

    CREATE TABLE empresa(
    empresa_id NUMERIC(6) NOT NULL CONSTRAINT empresa_id_pk PRIMARY KEY,
    telefonoFijo BIGINT NOT NULL,
    telefonoMovil BIGINT NOT NULL,
    direccionSedePrincipal VARCHAR(30) NOT NULL,
    direccionSedeSecundaria VARCHAR(30),
    nombre_director VARCHAR(30) NOT NULL,
    nombre VARCHAR(30) NOT NULL,
    tamaño VARCHAR(30) NOT NULL,
    CONSTRAINT empresa_tamaño_ck CHECK (tamaño IN ('pequeña','mediana','multinacional'))
    );

Tabla `web`

    CREATE TABLE web(
    empresa_id NUMERIC(6) NOT NULL,
    red_socialPrincipal VARCHAR(30),
    redes_socialSecundaria VARCHAR(30),
    servidor VARCHAR(30) NOT NULL,
    url VARCHAR(30) NOT NULL,
    CONSTRAINT web_empresa_id_fk FOREIGN KEY(empresa_id) REFERENCES empresa(empresa_id)
    );

Tabla `seguridad`

    CREATE TABLE seguridad(
    empresa_id NUMERIC(6) NOT NULL,
    CONSTRAINT seguridad_empresa_id_fk FOREIGN KEY(empresa_id) REFERENCES empresa(empresa_id)
    );
    
Tabla `catering`

     CREATE TABLE catering(
    empresa_id NUMERIC(6) NOT NULL,
    CONSTRAINT catering_empresa_id_fk FOREIGN KEY(empresa_id) REFERENCES empresa(empresa_id)
    );

Tabla `grabacion`

    CREATE TABLE grabacion(
    empresa_id NUMERIC(6) NOT NULL,
    CONSTRAINT grabacion_empresa_id_fk FOREIGN KEY(empresa_id) REFERENCES empresa(empresa_id)
    );

Tabla `iluminacion`

    CREATE TABLE iluminacion(
    empresa_id NUMERIC(6) NOT NULL,
    CONSTRAINT iluminacion_empresa_id_fk FOREIGN KEY(empresa_id) REFERENCES empresa(empresa_id)
    );

Tabla `sonido`

    CREATE TABLE sonido(
    empresa_id NUMERIC(6) NOT NULL,
    CONSTRAINT sonido_empresa_id_fk FOREIGN KEY(empresa_id) REFERENCES empresa(empresa_id)
    );

Tabla `retransmision`

    CREATE TABLE retransmision(
    retransmision_id NUMERIC(6) NOT NULL CONSTRAINT retransmision_id_pk PRIMARY KEY,
    canal_id NUMERIC(6) NOT NULL,
    idioma_id NUMERIC(6) NOT NULL,
    duracion VARCHAR(30) NOT NULL,
    ingreso INTEGER NOT NULL,
    tipo VARCHAR(30) NOT NULL,
    empresa_id NUMERIC(6) NOT NULL,
    CONSTRAINT retransmision_empresa_id_fk FOREIGN KEY(empresa_id) REFERENCES empresa(empresa_id),
    CONSTRAINT retransmision_canal_id_fk FOREIGN KEY(canal_id) REFERENCES canal_retransmision(canal_id),
    CONSTRAINT retransmision_idioma_id_fk FOREIGN KEY(idioma_id) REFERENCES idioma_retransmision(idioma_id),
    CONSTRAINT retransmision_tipo_ck CHECK (tipo IN ('directo','diferido'))
    );

Tabla `canal_retransmision`
    
    CREATE TABLE canal_retransmision(
    canal_id NUMERIC(6) NOT NULL CONSTRAINT canal_id_pk PRIMARY KEY,
    nombre VARCHAR(30) NOT NULL
    );

Tabla `idioma_retransmision`

    CREATE TABLE idioma_retransmision(
    idioma_id NUMERIC(6) NOT NULL CONSTRAINT idioma_id_pk PRIMARY KEY,
    nombre VARCHAR(30) NOT NULL
    );
    

Tabla `merchandising`

    CREATE TABLE merchandising(
    merchandising_id NUMERIC(6) NOT NULL CONSTRAINT merchandising_pk PRIMARY KEY,
    producto VARCHAR(30) NOT NULL,
    gama VARCHAR(30),
    ingresos INTEGER NOT NULL,
    talla VARCHAR(30),
    artista_id NUMERIC(6) NOT NULL,
    CONSTRAINT merchandising_artista_id_fk FOREIGN KEY(artista_id) REFERENCES artista(artista_id),
    CONSTRAINT merchandising_talla_ck CHECK (talla IN ('S','M','L','XL'))
    );

Tabla `patrocinador`

    CREATE TABLE patrocinador(
    patrocinador_id NUMERIC(6) NOT NULL CONSTRAINT patrocinador_pk PRIMARY KEY,
    telefonoFijo BIGINT NOT NULL,
    telefonoMovil BIGINT NOT NULL,
    sector VARCHAR(30) NOT NULL,
    direccion VARCHAR(30) NOT NULL,
    nombre VARCHAR(30) NOT NULL
    );

Tabla `artista_escenario`

    CREATE TABLE artista_escenario(
    artista_id NUMERIC(6) NOT NULL,
    escenario_id NUMERIC(6) NOT NULL,
    duracion_actuacion VARCHAR(30) NOT NULL,
    CONSTRAINT artista_escenario_pk PRIMARY KEY(artista_id,escenario_id),
    CONSTRAINT artista_escenario_artista_id_fk FOREIGN KEY(artista_id) REFERENCES artista(artista_id),
    CONSTRAINT artista_escenario_escenario_id_fk FOREIGN KEY(escenario_id) REFERENCES escenario(escenario_id)
    );

Tabla `artista_patrocinador`

    CREATE TABLE artista_patrocinador(
    artista_id NUMERIC(6) NOT NULL,
    patrocinador_id NUMERIC(6) NOT NULL,
    tipo_contrato VARCHAR(30) NOT NULL,
    duracion_contrato VARCHAR(30) NOT NULL,
    ingresos INTEGER NOT NULL,
    CONSTRAINT artista_patrocinador_pk PRIMARY KEY(artista_id,patrocinador_id),
    CONSTRAINT artista_patrocinador_artista_id_fk FOREIGN KEY(artista_id) REFERENCES artista(artista_id),
    CONSTRAINT artista_patrocinador_tipo_contrato_ck CHECK (tipo_contrato IN ('indefinido','temporal'))
    );

Tabla `cartel_empresa`

    CREATE TABLE cartel_empresa(
    cartel_id NUMERIC(6) NOT NULL,
    empresa_id NUMERIC(6) NOT NULL,
    trabajadores_contratados INTEGER NOT NULL,
    gasto INTEGER NOT NULL,
    CONSTRAINT cartel_empresa_pk PRIMARY KEY(cartel_id,empresa_id),
    CONSTRAINT cartel_empresa_cartel_id_fk FOREIGN KEY(cartel_id) REFERENCES cartel(cartel_id),
    CONSTRAINT cartel_empresa_empresa_id_fk FOREIGN KEY(empresa_id) REFERENCES empresa(empresa_id)
    );

Tabla `entrada`

    CREATE TABLE entrada(
    entrada_id NUMERIC(6) NOT NULL,
    empresa_id NUMERIC(6) NOT NULL,
    categoria VARCHAR(30) NOT NULL,
    formato VARCHAR(30) NOT NULL,
    fecha_compra DATE NOT NULL,
    plazo_devolucion VARCHAR(30),
    CONSTRAINT entrada_pk PRIMARY KEY(entrada_id),
    CONSTRAINT entrada_empresa_id_fk FOREIGN KEY(empresa_id) REFERENCES empresa(empresa_id),
    CONSTRAINT entrada_categoria_fk FOREIGN KEY(categoria) REFERENCES categoria_entrada(categoria),
    CONSTRAINT entrada_formato_ck CHECK (formato IN ('fisico','digital','alto'))
    );

Tabla `categoria_entrada`

    CREATE TABLE categoria_entrada(
    categoria VARCHAR(30) NOT NULL,
    precio INTEGER NOT NULL,
    CONSTRAINT categoria_entrada_pk PRIMARY KEY(categoria)
    );

Tabla `seguridad_escenario`

    CREATE TABLE seguridad_escenario(
    empresa_id NUMERIC(6) NOT NULL,
    escenario_id NUMERIC(6) NOT NULL,
    num_trabajadores INTEGER NOT NULL,
    CONSTRAINT seguridad_escenario_pk PRIMARY KEY(empresa_id,escenario_id),
    CONSTRAINT seguridad_escenario_empresa_id_fk FOREIGN KEY (empresa_id) 
    REFERENCES empresa (empresa_id),
    CONSTRAINT seguridad_escenario_escenario_id_fk FOREIGN KEY (escenario_id)
    REFERENCES escenario (escenario_id)
    );

Tabla `seguridad_backstage`

    CREATE TABLE seguridad_backstage(
    empresa_id NUMERIC(6) NOT NULL,
    backstage_id NUMERIC(6) NOT NULL,
    num_trabajadores INTEGER NOT NULL,
    CONSTRAINT seguridad_backstage_pk PRIMARY KEY(empresa_id,backstage_id),
    CONSTRAINT seguridad_backstage_empresa_id_fk FOREIGN KEY (empresa_id) 
    REFERENCES empresa (empresa_id),
    CONSTRAINT seguridad_backstage_backstage_id_fk FOREIGN KEY (backstage_id)
    REFERENCES backstage (backstage_id)
    );

Tabla `catering_backstage`

    CREATE TABLE catering_backstage(
    empresa_id NUMERIC(6),
    backstage_id NUMERIC(6),
    tipo_comida VARCHAR(30),
    CONSTRAINT catering_backstage_pk PRIMARY KEY(empresa_id,backstage_id,tipo_comida),
    CONSTRAINT catering_backstage_empresa_id_fk FOREIGN KEY (empresa_id) 
    REFERENCES empresa (empresa_id),
    CONSTRAINT catering_backstage_backstage_id_fk FOREIGN KEY (backstage_id)
    REFERENCES backstage (backstage_id)
    );

Tabla `iluminacion_escenario`

    CREATE TABLE iluminacion_escenario(
    empresa_id NUMERIC(6),
    escenario_id NUMERIC(6),
    num_focos INTEGER NOT NULL,
    situacion_escenario VARCHAR(30) NOT NULL,
    CONSTRAINT iluminacion_escenario_pk PRIMARY KEY(empresa_id,escenario_id),
    CONSTRAINT iluminacion_escenario_empresa_id_fk FOREIGN KEY (empresa_id) 
    REFERENCES empresa (empresa_id),
    CONSTRAINT iluminacion_escenario_escenario_id_fk FOREIGN KEY (escenario_id)
    REFERENCES escenario (escenario_id)
    );

Tabla `grabacion_escenario`

    CREATE TABLE grabacion_escenario(
    empresa_id NUMERIC(6) NOT NULL,
    escenario_id NUMERIC(6) NOT NULL,
    num_camaras INTEGER NOT NULL,
    situacion_escenario VARCHAR(30) NOT NULL,
    CONSTRAINT grabacion_escenario_pk PRIMARY KEY(empresa_id,escenario_id),
    CONSTRAINT grabacion_escenario_empresa_id_fk FOREIGN KEY (empresa_id) 
    REFERENCES empresa (empresa_id),
    CONSTRAINT grabacion_escenario_escenario_id_fk FOREIGN KEY (escenario_id)
    REFERENCES escenario (escenario_id)
    );

Tabla `sonido_escenario`

    CREATE TABLE sonido_escenario(
    empresa_id NUMERIC(6) NOT NULL,
    escenario_id NUMERIC(6) NOT NULL,
    num_micros INTEGER NOT NULL,
    situacion_escenario VARCHAR(30) NOT NULL,
    CONSTRAINT sonido_escenario_pk PRIMARY KEY(empresa_id,escenario_id),
    CONSTRAINT sonido_escenario_empresa_id_fk FOREIGN KEY (empresa_id) 
    REFERENCES empresa (empresa_id),
    CONSTRAINT sonido_escenario_escenario_id_fk FOREIGN KEY (escenario_id)
    REFERENCES escenario (escenario_id)
    );
    
Tabla `cartel_artista`

    CREATE TABLE cartel_artista(
    artista_id NUMERIC(6) NOT NULL,
    cartel_id_id NUMERIC(6) NOT NULL,
    CONSTRAINT cartel_artista_pk PRIMARY KEY(artista_id,cartel_id),
    CONSTRAINT cartel_artista_artista_id_fk FOREIGN KEY (artista_id) 
    REFERENCES artista (artista_id),
    CONSTRAINT cartel_artista_cartel_id_fk FOREIGN KEY (cartel_id)
    REFERENCES cartel (cartel_id)
