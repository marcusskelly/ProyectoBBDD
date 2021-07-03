# Añadir registros

1. Tabla `artistas`
   ~~~
   insert into artista values (01, 44, 'Armin van Buuren', 'alto', 'V'), (02, 41, 'Don Diablo', 'alto', 'V'), 
   (03, 38, 'Steve Angello', 'alto', 'V'), (04, 39, 'Brennan Heart', 'medio', 'V'), (05 , 43, 'Steve Aoki', 'alto', 'V'), 
   (06, 28, 'Eptic', 'medio', 'V'), (07, 23, 'Anier', 'bajo', 'M'), (08, 24, 'Bad Gyal', 'medio', 'M'), 
   (09, 25, 'Wade', 'bajo', 'V'), (10, 33, 'Nina Kraviz', 'muy alto', 'M'), (11, 30, 'Amelie Lens', 'alto', 'M'),
   (12, 27, 'Axwell', 'medio', 'V'), (14, 34, 'Hardwell', 'muy alto', 'V'), (15, 30, 'Coone', 'medio', 'V'),
   (16, 29, 'Jamie Jones', 'medio', 'V'), (17, 48, 'Vicente One More Time', 'alto', 'V'), (18, 25, 'Martin Garrix', 'alto', 'V'),
   (19, 23, 'Ace Ventura', 'medio', 'V'), (20, 41, 'Raul Pacheco', 'bajo', 'V'), (21, 30, 'Nervo', 'medio', 'M'),
   (22, 27, 'Fatima Haji', 'alto', 'M'), (23, 39, 'Kase O', 'alto', 'V'), (24, 43, 'SFDK', 'medio', 'V'),
   (25, 27, 'Mala Rodriguez', 'bajo', 'M'), (26, 42, 'Korsakoff', 'alto', 'M'), (27, 30, 'Miss K8', 'muy alto', 'M'),
   (28, 28, 'Angerfist', 'alto', 'V'), (29, 34, 'Pendullum', 'alto', 'V'), (30, 32, 'Zatox', 'medio', 'V'),
   (31, 31, 'Headhunterz', 'muy alto', 'V'), (32, 21, 'Tha Playah', 'medio', 'V'), (33, 24, 'Rosalia', 'muy alto', 'M'),
   (34, 43, 'Carl Cox', 'muy alto', 'V'), (35, 35, 'Tatanka', 'muy alto', 'V'), (36, 34, 'Wildstylez', 'medio', 'V');
   ~~~

2. Tabla `cartel`
    ~~~
   insert into cartel values (01, '2012/08/12', '2012/08/16', 'Almeria', 800000,'QuevedoFest2012'),
   (02, '2012/12/21', '2012/12/24', 'Miami', 600000,'QuevedoFestWinterEdition2012'),
   (03, '2013/08/14', '2013/08/18', 'Malaga', 1200000,'QuevedoFest2013'),
   (04, '2013/12/20', '2013/12/23', 'Andorra', 400000,'QuevedoFestWinterEdition2013'),
   (05, '2014/08/12', '2014/08/17', 'Madrid', 900000,'QuevedoFest2014'),
   (06, '2015/04/21', '2015/04/25', 'Magaluf', 560000,'QuevedoFestEasterEdition2015'),
   (07, '2015/08/14', '2015/08/18', 'Almeria', 1250000,'QuevedoFest2015'),
   (08, '2016/04/20', '2016/04/24', 'Boston', 850000,'QuevedoFestEasterEdition2016'),
   (09, '2016/08/11', '2016/08/15', 'Barcelona', 2000000,'QuevedoFest2016'),
   (10, '2016/12/21', '2016/12/25', 'Malta', 470000,'QuevedoFestWinterEdition2016'),
   (11, '2018/08/13', '2018/08/17', 'Munich', 1400000,'QuevedoFest2018'),
   (12, '2018/12/21', '2018/12/24', 'Los Angeles', 3200000,'QuevedoFestWinterEdition2018'),
   (13, '2019/08/14', '2019/08/20', 'Miami', 1250000,'QuevedoFest2019'),
   (14, '2020/08/12', '2012/08/16', 'Madrid', 2300000,'QuevedoFest2020');
   ~~~
   
3. Tabla `cache_artista`
    ~~~
   insert into cache_artista values ('bajo', 25000),('medio', 50000),('alto', 100000),('muy alto', 200000);
   ~~~

4. Tabla `escenario`
   
    ~~~
   insert into escenario values (01, 12000, 'pequeño', 'cubierto', '4000 personas' ,'Brugal Stage'),
   (02, 18000, 'medio' , 'cubierto', '8500 personas','Bacardi Stage'),
   (03, 9000, 'pequeño', 'aire libre', '5600 personas','Jack Daniels Stage'),
   (04, 25000, 'grande', 'techo retractil', '12000 personas','Barcelo Stage'),
   (05, 32000, 'muy grande', 'aire libre', '25000 personas','Main Stage'),
   (06, 6000, 'pequeño', 'aire libre', '3200 personas','Smirnoff Stage'),
   (07, '8000', 'pequeño', 'cubierto', '6200 personas','Absolut Stage'),
   (08, 15000, 'medio', 'aire libre', '9100 personas','Negrita Stage'),
   (09, 23200, 'grande', 'cubierto', '15000 personas' ,'White Label Stage');
   ~~~

5. Tabla `backstage`
   
    ~~~
   insert into backstage values (01, 8000, '53', 'muy grande',05),
   (02, 3400, '23', 'medio',02),
   (03, 5000, '34', 'grande',04),
   (04, 2300, '12', 'pequeño',03),
   (05, 1800, '17', 'pequeño',06),
   (06, 2000, '8', 'pequeño',01),
   (07, 4500, '21', 'medio',08),
   (08, 6500, '41', 'grande',09),
   (09, 2700, '14', 'pequeño',07);
   ~~~

   
6. Tabla `empresa`
   
    ~~~
   insert into empresa values (01, 915737695, 646754062, 'Calle Fuencarral 32','Calle Mercedes 48', 'Pablo Alfaro', 'Seguritas Stages',   'mediana'),
   (02, 913745695, 623754672, 'Calle MasPalomas 108',NULL, 'Alfonso Oracio', 'Safe N Sound', 'pequeña'),
   (03, 965438735, NULL , 'Calle Malvarosa 45',NULL, 'Matias Sanchez', 'Light Power', 'mediana'),
   (04, 918433091, 688744163, 'Calle Marroquina 192','Calle Antonio Casero 18', 'Michael Doherty', 'Gazprom', 'multinacional'),
   (05, 939732835, 617054032, 'Calle Puerta Bonita 4',NULL, 'Francisco Torres', 'Sound Beats', 'mediana'),
   (06, 914767085, 652784061, 'Calle Sierra Carbonera 51','Calle del Alguacil 12', 'Mateo Arias', 'Play Records', 'multinacional'),
   (07, 914235135, NULL, 'Poligono Industrial Las Mercedes,NULL, 'Pablo Sarabia', 'Nostra luz', 'mediana'),
   (08, 913777312, 616734182, 'Calle Uceda 10',Poligono Industrial Las Nieves, 'Ricardo Perez', 'Just Eat', 'multinacional'),
   (09, 912417094, 641757012, 'Calle Ramon Perez de Ayala 102',NULL, 'Pablo Aguilar', 'Uber Eats', 'multinacional'),
   (10, 921747095, 691754752, 'Calle de La Marroquina 15','Calle Almonacid 19', 'Pedro Blanco', 'Securitas Direct', 'mediana'),
   (11, 913757215, 626754701, 'Parque de la Fuente del Berro',NULL, 'Lorenzo Mila', 'TVE', 'multinacional'),
   (12, 955017655, NULL, 'Calle Puerto de Canfranc 12',NULL, 'Alfredo Sanchez', 'Glovo', 'multinacional'),
   (13, 913706335, 656785401, 'Poligono Industrial de Getafe','Calle Mateo Lopez 16', 'Joaquin Perez', 'M1 Studios', 'Multinacional'),
   (14, 935706605, 626724364, 'Calle Isco 56','Poligono Industrial de Alicante', 'Adolfo Sanchez', 'Mk The Plug', 'mediana'),
   (15, 913577895, 616753051, 'Calle Francisco de Vitoria 11',NULL, 'David Garcia', 'Web 4 you', 'multinacional'),
   (16, 913727194, 690675302, 'Calle Ronda de Segovia 1','Calle Matias Prat 48', 'Rodrigo Alvarez', 'World web', 'mediana'),
   (17, 912757642, 622723402, 'Calle Aluche 55','Calle Atocha 31', 'Ignacio Perez', 'Antena 3', 'pequeña'),
   (18, 955337098, 611454562, 'Calle Medina 54',NULL, 'Pablo Alfaro', 'Light 4 you', 'mediana'),
   (19, 923727598, 623757162, 'Calle Sierra Madrona 32',NULL, 'Pablo Iglesias', 'Ghosty Records', 'pequeña'),
   (20, 945730695, 646754032, 'Calle Fuencarral 18',NULL, 'Pablo Nieto', 'Food Express', 'mediana');
   ~~~
   
 7. Tabla `web`
      ~~~
      insert into web values (15, 'Facebook', 'Twitter', 'Server.net','Web4you.com'),
      (19, 'Facebook y Twitter', 'Instagram', 'Server.net','GhostyRecords.com'),
      (16, 'Facebook e Instagram', NULL, 'Servidores.net','WorldWeb.com'),
      (14, 'Facebook Twitter e Instagram', 'Telegram', 'Apache.net','MKThePlug.co.uk'),
      (13, 'Instagram y Twitter', NULL, 'Apache.net','M1OnTheBeat.com');
       ~~~
   
 8. Tabla `seguridad`
      ~~~
      insert into seguridad values (01, 'Facebook', 'Twitter', 'Server.net','SeguritasStages.com'),
      (02, 'Facebook y Twitter', 'Instagram', 'Server.net','SafeNSound.co.uk'),
      (16, 'Facebook e Instagram', NULL, 'Servidores.net','WorldWeb.com'),
      (14, 'Facebook Twitter e Instagram', 'Telegram', 'Apache.net','MKThePlug.co.uk'),
      (13, 'Instagram y Twitter', NULL, 'Apache.net','M1OnTheBeat.com'),
      (10, 'Instagram y Twitter', 'Facebook', 'Server.net','SecuritasDirect.es');
      ~~~
      
      
9. Tabla `catering`
    ~~~
   insert into catering values (12),(08),(09),(20);
   ~~~
   
10. Tabla `grabacion`
       ~~~
      insert into grabacion values (19),(06),(11),(17),(13);
      ~~~ 
      
11. Tabla `iluminacion`
       ~~~
      insert into iluminacion values (03),(04),(07),(19),(13),(18);
      ~~~ 
      
11. Tabla `sonido`
       ~~~
      insert into sonido values (19),(14),(13),(05),(06);
      ~~~ 
      
12. Tabla `canal_retransmision`
   
       ~~~
      insert into canal_retransmision values (01,'BBC'),(02,'Movistar'),(03,'Onda Cero'),(04,'as'),(05,'TVE'),(06,'Antena 3'),(07,'BT'),(08,'Virgin Media'),
      (09,'La Radio'),(10,'France TV'),(11,'TeleMadrid'),(12,'CNN'),(13,'Canal +'),(14,'La Sexta'),(15,'Telecinco'),(16,'ITV'),(17,'Channel 3'),(18,'America News'),
      (19,'Cuatro');
       ~~~ 
       
13. Tabla `idioma_retransmision`
   
       ~~~
      insert into idioma_retransmision values (01,'Español'),(02,'Ingles'),(03,'Frances'),(04,'Italiano'),(05,'Arabe'),(06,'Portugues'),(07,'Ruso'),(08,'Checo');
       ~~~ 
       
14. Tabla `retransmision`
   
       ~~~
      insert into retransmision values (01, 02, 01, '60 minutos', 2800 ,'directo'),(01, 01, 02, '54 minutos', 1400 ,'diferido'),
      (01, 03, 01, '120 minutos', 700 ,'directo'),(01, 14, 01, '45 minutos', 430 ,'directo'),(01, 15, 01, '110 minutos', 920 ,'diferido),
      (02, 05, 01, '30 minutos', 650 ,'diferido'),(02, 11, 01, '66 minutos', 850 ,'directo'),(02, 13, 01, '55 minutos', 460 ,'diferido'),
      (02, 13, 02, '60 minutos', 310 ,'directo'),(03, 12, 02, '140 minutos', 1200 ,'directo'),(03, 12, 01, '87 minutos', 800 ,'directo'),
      (03, 12, 03, '110 minutos', 1400 ,'diferido'),(03, 12, 07, '55 minutos', 620 ,'directo'),(03, 16, 06, '120 minutos', 610 ,'directo'),
      (03, 17, 02, '90 minutos', 1180 ,'diferido'),(03, 18, 02, '112 minutos', 680 ,'directo'),(03, 10, 03, '68 minutos', 480 ,'directo'),
      (03, 12, 02, '140 minutos', 1200 ,'directo'),(04, 19, 01, '166 minutos', 2300 ,'directo'),(05, 13, 07, '78 minutos', 560 ,'diferido'),
      (05, 13, 08, '112 minutos', 670 ,'diferido'),(05, 07, 02, '102 minutos', 1350 ,'directo'),(05, 07, 02, '102 minutos', 590 ,'directo'),
      (06, 09, 01, '108 minutos', 340 ,'diferido'),(06, 03, 01, '65 minutos', 210 ,'directo'),(06, 04, 01, '88 minutos', 460 ,'diferido'),
      (07, 01, 02, '132 minutos', 3200 ,'directo'),(07, 15, 01, '112 minutos', 2300 ,'directo'),(07, 14, 01, '118 minutos', 2200 ,'directo'),
      (07, 02, 01, '155 minutos', 4300 ,'directo'),(07, 15, 01, '146 minutos', 3150 ,'directo'),(07, 18, 02, '112 minutos', 6200 ,'directo'),
      (07, 08, 02, '156 minutos', 3800 ,'directo'),(07, 05, 01, '180 minutos', 2950 ,'directo'),(07, 10, 03, '130 minutos', 8100 ,'directo'),
      (07, 17, 05, '114 minutos', 5400 ,'directo'),(08, 01, 04, '132 minutos', 4350 ,'diferido'),(08, 01, 06, '118 minutos', 1700 ,'diferido'),
      (08, 01, 07, '134minutos', 3100 ,'diferido'),(08, 01, 03, '148 minutos', 3240 ,'diferido'),(08, 01, 05, '112minutos', 2300 ,'diferido'),
      (08, 01, 08, '128 minutos', 800 ,'diferido'),(08, 01, 02, '123 minutos', 1600 ,'diferido');
      ~~~
      
15. Tabla `merchandising`
      ~~~
      insert into merchandising values (01, 'camiseta', 'media', 20,'M',01),(02, 'camiseta', 'media', 20,'S',01),(03, 'camiseta', 'media', 20,'L',01),
      (04, 'camiseta', 'media', 20,'XL',01),(05, 'camiseta', 'media', 25,'M',04),(06, 'camiseta', 'media', 25,'S',04),(07, 'camiseta', 'media', 25,'L',04),
      (08, 'camiseta', 'media', 25,'XL',04),(09, 'camiseta', 'media', 23,'S',12),(10, 'camiseta', 'media', 23,'M',12),(11, 'camiseta', 'media', 25,'L',12),
      (12, 'camiseta', 'media', 20,'L',05),(13, 'camiseta', 'media', 20,'S',05),(14, 'camiseta', 'media', 20,'M',05),(15, 'camiseta', 'alta', 32,'L',06),
      (16, 'camiseta', 'alta', 32,'S',06),(17, 'camiseta', 'alta', 32,'XL',06),(18, 'camiseta', 'baja', 12,'S',33),(19, 'camiseta', 'baja', 12,'L',33),
      (20, 'camiseta', 'alta', 12,'M',33),(21, 'camiseta', 'media', 20,'L',15),(22, 'camiseta', 'media', 20,'S',15),(23, 'camiseta', 'media', 20,'M',15),
      (24, 'camiseta', 'alta', 32,'L',24),(25, 'camiseta', 'alta', 32,'M',24),(26, 'camiseta', 'alta', 32,'XL',24),(27, 'camiseta', 'alta', 32,'M',28),
      (28, 'camiseta', 'alta', 32,'S',28),(29, 'camiseta', 'alta', 32,'XL',28),(30, 'camiseta', 'alta', 32,'M',07),(31, 'camiseta', 'alta', 32,'S',07),
      (32, 'camiseta', 'alta', 32,'XL',07),(33, 'camiseta', 'baja', 12,'S',32),(34, 'camiseta', 'baja', 12,'M',32),(35, 'camiseta', 'baja', 12,'XL',32),
      (36, 'camiseta', 'baja', 12,'L',32),(37, 'camiseta', 'baja', 12,'M',30),(38, 'camiseta', 'baja', 12,'S',30),(39, 'camiseta', 'baja', 12,'L',30),
      (40, 'camiseta', 'baja', 12,'M',18),(41, 'camiseta', 'baja', 12,'S',18),(42, 'camiseta', 'baja', 12,'L',18),(43, 'camiseta', 'media', 20,'S',11),
      (44, 'camiseta', 'media', 20,'M',11),(45, 'camiseta', 'media', 20,'L',11),(46, 'camiseta', 'alta', 32,'S',19),(47, 'camiseta', 'alta', 32,'M',19),
      (48, 'camiseta', 'alta', 32,'XL',19),(49, 'camiseta', 'media', 20,'S',23),(50, 'camiseta', 'media', 20,'M',23),(51, 'camiseta', 'media', 20,'L',23),
      (52, 'camiseta', 'alta', 32,'S',22),(53, 'camiseta', 'alta', 32,'M',22),(54, 'camiseta', 'alta', 32,'L',22),(55, 'camiseta', 'media', 20,'S',36),
      (56, 'camiseta', 'media', 20,'M',36),(57, 'camiseta', 'media', 20,'L',36),(58, 'gorra', 'media', 14,'S',33),(59, 'gorra', 'media', 14,'M',33),
      (60, 'gorra', 'media', 14,'L',33),(61, 'gorra', 'baja', 8,'S',12),(62, 'gorra', 'baja', 8,'M',12),(63, 'gorra', 'baja', 8,'L',12),(02, 'gorra', 'baja', 8,'XL',12),
      (64, 'gorra', 'baja', 8,'S',17),(65, 'gorra', 'baja', 8,'M',17),(66, 'gorra', 'baja', 8,'L',17),(67, 'gorra', 'baja', 8,'XL',17),(02, 'gorra', 'alta', 21,'S',30),
      (68, 'gorra', 'alta', 21,'M',30),(69, 'gorra', 'alta', 21,'XL',30),(70, 'gorra', 'alta', 21,'L',30),(71, 'gorra', 'alta', 21,'S',18),(02, 'gorra', 'alta', 21,'M',18),
      (72, 'gorra', 'alta', 21,'L',18),(73, 'gorra', 'baja', 8,'S',05),(74, 'gorra', 'baja', 8,'M',05),(75, 'gorra', 'baja', 8,'L',05),(02, 'gorra', 'baja', 8,'XL',05),
      (76, 'gorra', 'baja', 8,'S',09),(77, 'gorra', 'baja', 8,'M',09),(78, 'gorra', 'baja', 8,'L',09),(79, 'gorra', 'baja', 8,'XL',09),(02, 'gorra', 'alta', 21,'XL',09),
      (80, 'gorra', 'alta', 21,'S',09),(81, 'gorra', 'alta', 21,'M',09),(82, 'gorra', 'alta', 21,'L',09),(83, 'gorra', 'media', 14,'XL',09),(02, 'gorra', 'media', 14,'L',09),
      (84, 'gorra', 'media', 14,'S',09),(85, 'gorra', 'media', 14,'M',09),(86, 'gorra', 'media', 14,'L',14),(87, 'gorra', 'media', 14,'M',14),(02, 'gorra', 'media', 14,'S',14),
      (88, 'gorra', 'alta', 21,'L',14),(89, 'gorra', 'alta', 21,'M',14),(90, 'gorra', 'alta', 21,'S',14),(91, 'gorra', 'alta', 21,'XL',14),(02, 'gorra', 'alta', 21,'L',34),
      (92, 'gorra', 'alta', 21,'S',34),(93, 'gorra', 'alta', 21,'M',34),(94, 'gorra', 'baja', 8,'L',02),(95, 'gorra', 'baja', 8,'S',02),(96, 'gorra', 'baja', 8,'M',02),
      (97, 'gorra', 'baja', 8,'XL',02),(98, 'gorra', 'alta', 21,'M',02),(99, 'gorra', 'baja', 8,'S',03),(100, 'gorra', 'baja', 8,'M',03),(02, 'gorra', 'baja', 8,'L',03),
      (101, 'gorra', 'media', 14,'S',03),(102, 'gorra', 'media', 14,'M',03),(103, 'gorra', 'media', 14,'XL',03),(104, 'sudadera', 'media', 44,'S',03),
      (105, 'sudadera', 'media', 44,'M',03),(106, 'sudadera', 'alta', 62,'S',03),(107, 'sudadera', 'baja', 32,'S',14),(108, 'sudadera', 'baja', 32,'M',14),
      (109, 'sudadera', 'baja', 32,'L',14),(110, 'sudadera', 'baja', 32,'XL',14),(111, 'sudadera', 'baja', 32,'S',19),(112, 'sudadera', 'baja', 32,'M',19),
      (113, 'sudadera', 'baja', 32,'L',19),(114, 'sudadera', 'baja', 32,'XL',19),(115, 'sudadera', 'media', 44,'S',19),(116, 'sudadera', 'media', 44,'M',19),
      (117, 'sudadera', 'media', 44,'L',19),(118, 'sudadera', 'media', 44,'S',12),(119, 'sudadera', 'media', 44,'M',12),(120, 'sudadera', 'media', 44,'L',12),
      (121, 'sudadera', 'media', 44,'S',08),(122, 'sudadera', 'media', 44,'M',08),(123, 'sudadera', 'media', 44,'L',08),(124, 'sudadera', 'alta', 62,'S',21),
      (125, 'sudadera', 'alta', 62,'M',21),(126, 'sudadera', 'alta', 62,'L',21),(127, 'sudadera', 'alta', 62,'XL',21),(128, 'sudadera', 'alta', 62,'S',29),
      (129, 'sudadera', 'alta', 62,'M',29),(130, 'sudadera', 'alta', 62,'L',29),(131, 'sudadera', 'alta', 62,'XL',29),(132, 'sudadera', 'baja', 32,'S',31),
      (133, 'sudadera', 'baja', 32,'M',31),(134, 'sudadera', 'baja', 32,'L',31),(135, 'sudadera', 'baja', 32,'XL',31),(136, 'sudadera', 'media', 44,'S',31),
      (137, 'sudadera', 'media', 44,'M',31),(138, 'sudadera', 'media', 44,'L',31),(139, 'sudadera', 'alta', 62,'S',31),(140, 'sudadera', 'alta', 62,'M',31),
      (141, 'sudadera', 'alta', 62,'L',31),(142, 'sudadera', 'alta', 62,'XL',31),(143, 'llavero', NULL, 6,NULL,31),(144, 'llavero', NULL, 6,NULL,32),
      (145, 'llavero', NULL, 6,NULL,08),(146, 'llavero', NULL, 6,NULL,09),(147, 'llavero', NULL, 6,NULL,12),(148, 'llavero', NULL, 6,NULL,16),(04, 'llavero', NULL, 6,NULL,32),
      (149, 'llavero', NULL, 6,NULL,29),(150, 'llavero', NULL, 6,NULL,25),(151, 'llavero', NULL, 6,NULL,28),(152, 'llavero', NULL, 6,NULL,36),(04, 'llavero', NULL, 6,NULL,34),
      (153, 'llavero', NULL, 6,NULL,02),(154, 'llavero', NULL, 6,NULL,01),(155, 'llavero', NULL, 6,NULL,31),(156, 'llavero', NULL, 6,NULL,26),(04, 'llavero', NULL, 6,NULL,25),
      (157, 'llavero', NULL, 6,NULL,24),(158, 'llavero', NULL, 6,NULL,22),(159, 'llavero', NULL, 6,NULL,20),(160, 'llavero', NULL, 6,NULL,03),(04, 'llavero', NULL, 6,NULL,23),
      (161, 'disco', NULL, 12,NULL,31),(162, 'disco', NULL, 12,NULL,28),(163, 'disco', NULL, 12,NULL,26),(164, 'disco', NULL, 12,NULL,33),(05, 'disco', NULL, 12,NULL,30),
      (165, 'disco', NULL, 12,NULL,21),(166, 'disco', NULL, 12,NULL,14),(167, 'disco', NULL, 12,NULL,12),(168, 'disco', NULL, 12,NULL,10),(05, 'disco', NULL, 12,NULL,08),
      (169, 'disco', NULL, 12,NULL,02),(170, 'disco', NULL, 12,NULL,07),(171, 'disco', NULL, 12,NULL,11),(172, 'disco', NULL, 12,NULL,29),(173, 'disco', NULL, 12,NULL,35);
      ~~~      
      
      
 16. Tabla `patrocinador`
   
       ~~~
      insert into patrocinador values (01,915737695,646754062, 'Alimentacion', 'Calle Alcala de Guadaira 11' ,'Alsea'),(02,925757690,643750062, 'Alimentacion', 'Calle Alcala de       Henares 11' ,'Doritos'),(03,915336605,646054360, 'Alimentacion', 'Calle Montreal 15' ,'Pepsi-Cola'),(04,924730685,636757062, 'Hosteleria', 'Calle Francisco Jimenez 12'          ,'Bar Manolo'),(05,935730645,621734062, 'Suministros', 'Poligono Industrial de San Fernando' ,'Amazon'),(06,912407795,643444002, 'Alimentacion', 'Calle Barras bravas            10' ,'Lays'),(07,917747195,636750012, 'Reposteria', 'Calle Doña Asuncion 23' ,'Carrefour'),(07,918757095,600751032, 'Deportes', 'Calle Alcala 45' ,'Nike'),
      (08,912730625,626359061, 'Deportes', 'Calle San Rafael 23' ,'Adidas'),(09,935537605,640750462, 'Reposteria', 'Calle Los Santos 10' ,'Arla'),
      (10,915017095,626004062, 'Alimentacion', 'Calle de Los Buitres 14' ,'Alcampo'),(11,915430615,616750012, 'Alimentacion', 'Calle San Ramon 11' ,'Dia'),
      (12,912738691,613650012, 'Deportes', 'Calle Paseo de la Victoria' ,'Asics'),(13,915430415,641054022, 'Tecnologia', 'Calle Las Magras 2' ,'Google'),
      (14,916730215,626054102, 'Tecnologia', 'Calle San Vicente 17' ,'Facebook'),(15,914227600,623751002, 'Tecnologia', 'Calle Vladimir 50' ,'Twitter');
      ~~~     

17. Tabla `artista_escenario`
   
       ~~~
      insert into artista_escenario values (01,09,'1 hora y media'),(01,07,'54 minutos'),(02,09,'1 hora y 20 minutos'),
      (02,05,'33 minutos'),(03,01,'1 hora y 10 minutos'),(04,03,'1 hora y 8 minutos'),(04,02,'54 minutos'),
      (05,06,'1 hora y 23 minutos'),(06,03,'1 hora y 14 minutos'),(06,04,'1 hora y 13 minutos'),(06,01,'32 minutos'),
      (07,03,'1 hora y 12 minutos'),(08,01,'34 minutos'),(09,01,'1 hora y 11 minutos'),(09,05,'2 horas y 10 minutos'),
      (10,02,'1 hora y 56 minutos'),(11,09,'1 hora y 32 minutos'),(11,02,'26 minutos'),(11,01,'1 hora y 14 minutos'),
      (12,04,'58 minutos'),(12,01,'2 horas y 15 minutos'),(13,08,'1 hora y 40 minutos'),(14,03,'34 minutos'),
      (15,05,'1 hora y 48 minutos'),(15,06,'1 hora y 24 minutos'),(16,03,'54 minutos'),(17,07,'1 hora y 56 minutos'),
      (18,03,'1 hora y 35 minutos'),(19,01,'45 minutos'),(20,04,'1 hora y 12 minutos'),(20,04,'1 hora y 30 minutos'),
      (21,03,'36 minutos'),(22,04,'1 hora y 40 minutos'),(22,07,'1 hora y 50 minutos'),(22,05,'45 minutos'),
      (23,04,'1 hora y 34 minutos'),(23,01,'2 horas y 15 minutos'),(24,08,'1 hora y 23 minutos'),(24,01,'1 hora y 14 minutos'),
      (25,01,'1 hora y 33 minutos'),(26,05,'1 hora y 30 minutos'),(27,07,'1 hora y 15 minutos'),(28,02,'1 hora y 54 minutos'),
      (29,01,'1 hora y 13 minutos'),(29,04,'1 hora y 32 minutos'),(29,03,'1 hora y 58 minutos'),(30,04,'48 minutos'),
      (31,03,'1 hora y 34 minutos'),(32,04,'1 hora y 48 minutos'),(33,01,'1 hora y 34 minutos'),(34,01,'1 hora y 13 minutos'),
      (35,09,'1 hora y 10 minutos'),(36,05,'1 hora y 17 minutos');
       ~~~ 
       
 18. Tabla `artista_patrocinador`
      ~~~
      insert into artista_patrocinador values (01, 03, 'temporal', '16 meses',4500),(01, 12, 'indefinido', 'indefinido',1200),
      (01, 13, 'temporal', '8 meses',3200),(02, 01, 'indefinido', 'indefinido',8000),(03, 11, 'temporal', '2 meses',1200),
      (04, 04, 'indefinido', 'indefinido',3500),(04, 05, 'indefinido', 'indefinido',13000),(05, 14, 'temporal', '10 meses',7000),
      (06, 15, 'indefinido', 'indefinido',13000),(07, 10, 'temporal', '15 meses',8000),(07, 06, 'temporal', '12 meses',3800),
      (07, 13, 'temporal', '23 meses',6700),(08, 14, 'indefinido', 'indefinido',5700),(09, 09, 'temporal', '14 meses',8900),
      (10, 06, 'indefinido', 'indefinido',6500),(11, 08, 'temporal', '13 meses',6550),(12, 12, 'indefinido', 'indefinido',9000),
      (12, 15, 'temporal', '4 meses',12000),(13, 09, 'indefinido', 'indefinido',3400),(14, 01, 'temporal', '7 meses',4100),
      (14, 05, 'temporal', '12 meses',3200),(15, 06, 'temporal', '22 meses',8900),(16, 04, 'temporal', '9 meses',4800),
      (17, 03, 'temporal', '21 meses',8700),(20, 07, 'temporal', '18 meses',9900),(20, 05, 'temporal', '5 meses',4700),
      (20, 08, 'temporal', '14 meses',5200),(20, 02, 'indefinido', 'indefinido',10800),(21, 07, 'temporal', '13 meses',7600),
      (22, 02, 'temporal', '13 meses',5400),(23, 06, 'temporal', '32 meses',12300),(24, 08, 'temporal', '72 meses',23000),
      (27, 04, 'temporal', '9 meses',4750),(27, 01, 'temporal', '12 meses',3200),(28, 05, 'temporal', '15 meses',7200),
      (29, 07, 'temporal', '10 meses',7600),(30, 08, 'temporal', '27 meses',8700),(31, 06, 'temporal', '5 meses',3100),
      (32, 04, 'temporal', '14 meses',9600),(34, 04, 'indefinido', 'indefinido',32000),(34, 01, 'temporal', '24 meses',14000),
      (34, 05, 'temporal', '8 meses',4800),(34, 08, 'temporal', '13 meses',4800),(34, 12, 'temporal', '3 meses',15000),
      (34, 14, 'temporal', '2 meses',8000),(35, 07, 'temporal', '7 meses',4100);
      ~~~ 
      
 19. Tabla `cartel_empresa`
      ~~~
      insert into cartel_empresa values (01, 03, 12 ,4500),(01, 19, 7 ,5200),(01, 20, 4 ,4100),(01, 01, 18 ,3200),(01, 19, 3 ,2300),
      (01, 06, 16 ,5600),(01, 08, 14 ,2800),(01, 13, 7 ,7200),(02, 01, 14 ,4700),(02, 19, 14 ,6200),(02, 09, 7 ,2300),
      (02, 17, 21 ,12000),(02, 18, 6 ,5100),(03, 14, 3 ,6500),(03, 06, 12 ,7100),(03, 11, 13 ,6800),(03, 10, 8 ,1090),
      (04, 15, 5 ,6800),(04, 02, 9 ,4900),(04, 12, 18 ,9400),(04, 17, 8 ,6400),(04, 18, 22 ,2300),(04, 05, 7 ,4500),
      (05, 10, 13 ,12000),(05, 13, 5 ,5300),(05, 11, 7 ,6300),(05, 17, 6 ,2300),(05, 09, 11 ,4580),(05, 05, 9 ,5600),
      (06, 14, 5 ,2400),(06, 02, 14 ,8100),(06, 08, 8,4300),(06, 17, 8 ,8100),(06, 14, 9 ,3200),(07, 01, 24 ,9700),
      (07, 16, 5 ,4500),(07, 12, 12 ,6500),(07, 06, 6 ,6400),(07, 04, 8 ,7100),(07, 06, 7 ,7600),(08, 13, 7 ,8700),
      (08, 02, 18 ,3100),(08, 09, 13 ,7600),(08, 12, 6 ,8500),(08, 11, 7 ,7400),(08, 18, 6 ,6300),(08, 05, 15 ,7300),
      (09, 01, 14 ,3500),(09, 13, 4 ,12000),(09, 20, 6 ,3400),(09, 17, 8 ,2100),(09, 04, 16 ,8100),(09, 13, 9 ,8200),
      (10, 02, 13 ,3200),(10, 01, 12 ,6400),(10, 16, 10 ,5100),(10, 09, 7 ,3200),(10, 04, 9 ,4500),(10, 18, 06 ,3400),
      (10, 06, 5 ,1200),(11, 02, 6 ,5100),(11, 14, 7 ,7100),(11, 08, 10 ,5200),(11, 12, 3 ,5400),(11, 06, 7 ,8700),
      (11, 13, 9 ,4300),(11, 05, 4 ,7500),(11, 07, 12 ,3200),(12, 02, 16 ,8700),(12, 13, 7 ,8700),(12, 08, 7 ,4500),
      (12, 06, 9 ,6500),(12, 07, 8 ,6100),(12, 05, 7 ,4800),(13, 01, 24 ,13000),(13, 14, 3 ,8700),(13, 16, 8 ,7500),
      (13, 20, 5 ,4600),(13, 11, 9 ,5400),(13, 18, 8 ,8500),(13, 05, 7 ,6700),(14, 02, 12 ,7800),(14, 13, 6 ,6100),
      (14, 05, 18 ,2300),(14, 07, 8 ,3500),(14, 06, 18 ,8900);
      ~~~      

 20. Tabla `entrada`
      ~~~
      insert into entrada values (01,15, 'VIP' ,'fisico','2018-02-12',NULL),(02,15, 'Estandar' ,'digital','2015-07-14','30 dias'),
      (03,15, 'Estandar' ,'fisico','2016-08-21','30 dias'),(04,15, 'VIP + reservado' ,'fisico','2020-01-01',NULL),
      (05,15, 'Estandar + Parking' ,'digital','2017-08-10','30 dias'),(06,15, 'Estandar + Parking' ,'digital','2015-09-28','30 dias'),
      (07,19, 'Estandar' ,'fisico','2015-10-23','30 dias'),(08,19, 'VIP' ,'digital','2019-08-02',NULL),
      (09,19, 'VIP + Reservado + Hotel' ,'digital','2017-07-14',NULL),(10,19, 'Estandar' ,'fisico','2014-01-14','30 dias'),
      (11,19, 'Estandar + Parking' ,'fisico','2017-09-21','30 dias'),(12,15, 'Estandar' ,'fisico','2019-12-14','30 dias'),
      (13,19, 'VIP' ,'digital','2018-06-14',NULL),(14,19, 'Estandar + Parking' ,'digital','2020-05-10','30 dias'),
      (15,19, 'VIP + Reservado + Hotel' ,'fisico','2017-11-28',NULL),(16,16, 'Estandar' ,'digital','2015-12-14','30 dias'),
      (17,16, 'Estandar + Parking' ,'digital','2021-02-12','30 dias'),(18,16, 'VIP' ,'digital','2016-08-24',NULL),
      (19,16, 'VIP + Reservado + Hotel' ,'fisico','2018-04-11',NULL),(20,16, 'Estandar + Parking' ,'fisico','2015-07-14','30 dias'),
      (21,14, 'Estandar' ,'fisico','2017-12-29','30 dias'),(22,14, 'VIP' ,'fisico','2019-03-21',NULL),
      (23,14, 'Estandar + Parking' ,'digital','2018-10-14','30 dias'),(24,14, 'VIP' ,'fisico','2018-12-16',NULL),
      (25,14, 'VIP + Reservado + Hotel' ,'fisico','2019-10-25',NULL),(26,14, 'Estandar + Parking' ,'fisico','2018-07-13','30 dias'),
      (27,13, 'Estandar' ,'fisico','2017-07-10','30 dias'),(28,13, 'VIP' ,'digital','2019-11-19',NULL),
      (29,13, 'Estandar' ,'fisico','2019-07-21','30 dias'),(30,13, 'VIP + Reservado + Hotel' ,'digital','2016-06-06',NULL),
      (31,13, 'Estandar + Parking' ,'digital','2018-08-16','30 dias'),(32,13, 'VIP + reservado' ,'digital','2017-09-12',NULL),
      (33,13, 'VIP + reservado' ,'fisico','2019-12-21',NULL),(34,13, 'VIP + Reservado + Hotel' ,'digital','2016-09-15',NULL),
      (35,13, 'Estandar' ,'digital','2017-10-13','30 dias'),(36,13, 'Estandar + Parking' ,'fisico','2019-11-23','30 dias'),
      (37,13, 'Estandar + Parking' ,'fisico','2015-07-14','30 dias'),(38,13, 'VIP' ,'digital','2018-12-17',NULL),
      (39,13, 'VIP + Reservado + Hotel' ,'fisico','2018-11-13',NULL),(40,15, 'Estandar' ,'digital','2015-07-14','30 dias');
      ~~~ 
      
 21. Tabla `categoria_entrada`
      ~~~
      insert into categoria_entrada values ('VIP', 110),('Estandar', 60),('VIP + reservado', 160),('Estandar + Parking', 85),
      ('VIP + Reservado + Hotel', 230);
      ~~~
      
 22. Tabla `seguridad_escenario`
      ~~~
      insert into seguridad_escenario values (01, 01,3),(02, 01,4),(16, 02,5),(01, 01,3),(01, 02,3),(16, 02,6),(01, 03,4),(10, 03,3),
      (14, 03,6),(10, 03,3),(02, 04,7),(01, 05,5),(10, 05,3),(14, 05,4),(13, 05,5),(01, 06,3),(02, 06,6),(13, 06,3),(13, 06,7),
      (02, 07,8),(14, 07,5),(16, 07,6),(16, 08,5),(01, 08,3),(02, 08,4),(13, 08,6),(01, 09,6),(02, 09,4),(14, 09,8),(10, 09,4);
      ~~~ 
      
 23. Tabla `seguridad_backstage`
      ~~~
      insert into seguridad_backstage values (01, 01,3),(02, 01,4),(16, 02,5),(01, 01,3),(01, 02,3),(16, 02,6),(01, 03,4),(10, 03,3),
      (14, 03,6),(10, 03,3),(02, 04,7),(01, 05,5),(10, 05,3),(14, 05,4),(13, 05,5),(01, 06,3),(02, 06,6),(13, 06,3),(13, 06,7),
      (02, 07,8),(14, 07,5),(16, 07,6),(16, 08,5),(01, 08,3),(02, 08,4),(13, 08,6),(01, 09,6),(02, 09,4),(14, 09,8),(10, 09,4);
      ~~~ 
      
 24. Tabla `catering_backstage`
      ~~~
      insert into catering_backstage values (12, 01,'asiatica'),(08, 01,'italiana'),(12, 01,'Mediterranea'),(09, 02,'India'),
      (20, 02,'asiatica e India'),(12, 02,'italiana'),(08, 03,'asiatica'),(09, 04,'asiatica e italiana'),(12, 04,'asiatica'),
      (20, 05,'Mediterranea'),(08, 05,'India'),(09, 05,'asiatica'),(12, 06,'asiatica e India'),(09, 06,'Italiana'),(20, 06,'asiatica'),
      (12, 07,'asiatica'),(09, 07,'Mediterranea'),(08, 07,'italiana'),(12, 09,'asiatica'),(09, 09,'india');
      ~~~
      
 25. Tabla `iluminacion_escenario`
      ~~~
      insert into iluminacion_escenario values (03, 01,4,'Fondo y frente'),(04, 01,6,'Fondo'),(07, 02,5,'Fondo'),(19, 02,5,'Frente'),
      (13, 02,7,'Suelo'),(13, 03,5,'Suelo'),(03, 03,7,'Frente'),(07, 03,3,'Techo'),(07, 04,3,'Fondo Y techo'),(19, 04,12,'Frente'),
      (04, 04,2,'Fondo'),(07, 05,4,'Fondo'),(07, 05,7,'Techo'),(03, 05,4,'Frente Y techo'),(13, 06,5,'Frente'),(07, 06,6,'Fondo'),
      (19, 06,5,'techo'),(07, 07,4,'Fondo'),(03, 07,13,'Fondo, frente y techo'),(04, 07,5,'Fondo'),(07, 08,4,'Fondo y frente'),
      (19, 08,5,'Fondo y techo'),(04, 08,5,'techo y suelo'),(07, 09,8,'Fondo'),(04, 09,5,'Fondo y suelo');
      ~~~      

26. Tabla `grabacion_escenario`
      ~~~
      insert into grabacion_escenario values (19, 01,4,'Fondo y tarima'),(06, 01,6,'Fondo'),(11, 01,4,'Fondo'),(17, 01,5,'Frente'),
      (13, 02,7,'Tarima'),(11, 02,3,'Fondo'),(17, 02,4,'Fondo'),(17, 03,3,'Tarima'),(13, 03,6,'Fondo Y tarima'),(19, 04,12,'Frente'),
      (06, 04,2,'Fondo'),(11, 05,4,'Fondo'),(17, 05,7,'Techo'),(06, 05,4,'Frente Y techo'),(19, 06,5,'Frente'),(13, 06,6,'Fondo'),
      (11, 06,5,'techo'),(11, 07,4,'Fondo'),(06, 07,13,'Fondo, frente y tarima'),(17, 07,5,'Fondo'),(19, 08,4,'Fondo y frente'),
      (11, 08,5,'Fondo y techo'),(17, 08,5,'tarima y frente'),(13, 09,8,'Fondo'),(17, 09,5,'Fondo y tarima');
      ~~~ 
 
27. Tabla `sonido_escenario`
      ~~~
      insert into sonido_escenario values (19, 01,4,'Fondo y tarima'),(14, 01,6,'Fondo'),(13, 01,4,'Fondo'),(05, 01,5,'Frente'),
      (06, 02,7,'Tarima'),(19, 02,3,'Fondo'),(14, 02,4,'Fondo'),(14, 03,3,'Tarima'),(13, 03,6,'Fondo Y tarima'),(19, 04,12,'Frente'),
      (06, 04,2,'Fondo'),(14, 05,4,'Fondo'),(19, 05,7,'Techo'),(06, 05,4,'Frente Y techo'),(19, 06,5,'Frente'),(13, 06,6,'Fondo'),
      (05, 06,5,'techo'),(14, 07,4,'Fondo'),(05, 07,13,'Fondo, frente y tarima'),(06, 07,5,'Fondo'),(19, 08,4,'Fondo y frente'),
      (05, 08,5,'Fondo y techo'),(14, 08,5,'tarima y frente'),(13, 09,8,'Fondo'),(19, 09,5,'Fondo y tarima');
      ~~~  
28. Tabla `cartel_artista`
      ~~~
      insert into cartel_artista values (01, 01),(01, 07),(01, 13),(02, 01),(02, 03),(02, 06),(03, 04),(03, 11),(03, 14),(03, 12),
      (04, 01),(04, 02),(04, 03),(04, 04),(04, 05),(04, 06),(04, 07),(04, 08),(04, 09),(04, 10),(04, 11),(04, 12),(04, 13),(04, 04),
      (05, 01),(05, 05),(05, 07),(05, 09),(06, 05),(06, 11),(07, 12),(07, 01),(08, 12),(08, 14),(09, 02),(09, 03),(09, 04),(09, 10),
      (10, 01),(10, 10),(10, 06),(11, 02),(11, 03),(11, 05),(12, 01),(12, 03),(12, 04),(13, 10),(13, 14),(13, 09),(14, 14),(14, 13),
      (14, 08),(15, 10),(15, 13),(15, 04),(15, 11),(16, 14),(16, 07),(16, 09),(16, 09),(17, 13),(17, 12),(17, 02),(17, 10),(17, 06),
      (18, 14),(18, 11),(18, 09),(18, 12),(18, 01),(19, 01),(19, 12),(19, 03),(20, 13),(20, 11),(20, 02),(20, 01),(21, 03),(21, 04),
      (21, 08),(21, 12),(22, 11),(22, 13),(22, 02),(22, 07),(23, 11),(23, 12),(23, 14),(23, 09),(23, 05),(24, 11),(24, 01),(24, 07),
      (24, 10),(24, 08),(24, 06),(24, 04),(25, 12),(25, 10),(25, 05),(25, 13),(25, 06),(26, 14),(26, 12),(26, 14),(26, 06),(26, 09),
      (27, 14),(27, 13),(27, 11),(27, 10),(27, 08),(28, 01),(28, 04),(28, 08),(28, 07),(29, 02),(29, 01),(29, 13),(29, 07),(30, 02),
      (30, 04),(30, 07),(30, 14),(31, 02),(31, 01),(31, 11),(31, 03),(31, 09),(32, 03),(32, 11),(33, 03),(33, 01),(33, 05),(33, 06),
      (33, 09),(33, 10),(34, 08),(34, 01),(34, 05),(34, 11),(35, 06),(35, 04),(35, 07),(35, 09),(35, 10),(35, 12),(35, 03),(36, 06);
      ~~~
