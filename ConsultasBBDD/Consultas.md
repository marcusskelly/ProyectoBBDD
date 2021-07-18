# Consultas QuevedoFest

## Este apartado incluye consultas frecuentes de la base de datos.

Cantidad de empresas contratadas para`QuevedoFest2018`. 

    select count(c.empresa_id) from cartel_empresa c join cartel ca on(ca.cartel_id=c.cartel_id) where ca.titulo = 'QuevedoFest2018'