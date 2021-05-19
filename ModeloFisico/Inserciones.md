# Añadir registros

1. Tabla `artistas`
   ~~~
   insert into artista values (01, 44, 'Armin van Buuren', 'alto', 'V'), (02, 41, 'Don Diablo', 'alto', 'V'), 
   (03, 38, 'Steve Angello', 'alto', 'V'), (04, 39, 'Brennan Heart', 'medio', 'V'), (05 , 43, 'Steve Aoki', 'alto', 'V'), 
   (06, 28, 'Eptic' 'medio', 'V'), (07, 23, 'Anier', 'bajo', 'M'), (08, 24, 'Bad Gyal' 'medio', 'M'), 
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
   insert into cartel values (01, 2012/08/12, 2012/08/16, 'Almeria', 800000,'QuevedoFest2012'),
   (02, 2012/12/21, 2012/12/24, 'Miami', 600000,'QuevedoFestWinterEdition2012'),
   (03, 2013/08/14, 2013/08/18, 'Malaga', 1200000,'QuevedoFest2013'),
   (04, 2013/12/20, 2013/12/23, 'Andorra', 400000,'QuevedoFestWinterEdition2013'),
   (05, 2014/08/12, 2014/08/17, 'Madrid', 900000,'QuevedoFest2014'),
   (06, 2015/04/21, 2015/04/25, 'Magaluf', 560000,'QuevedoFestEasterEdition2015'),
   (07, 2015/08/14, 2015/08/18, 'Almeria', 1250000,'QuevedoFest2015'),
   (08, 2016/04/20, 2016/04/24, 'Boston', 850000,'QuevedoFestEasterEdition2016'),
   (09, 2016/08/11, 2016/08/15, 'Barcelona', 2000000,'QuevedoFest2016'),
   (10, 2016/12/21, 2016/12/25, 'Malta', 470000,'QuevedoFestWinterEdition2016'),
   (11, 2018/08/13, 2018/08/17, 'Munich', 1400000,'QuevedoFest2018'),
   (12, 2018/12/21, 2018/12/24, 'Los Angeles', 3200000,'QuevedoFestWinterEdition2018'),
   (13, 2019/08/14, 2019/08/20, 'Miami', 1250000,'QuevedoFest2019'),
   (14, 2020/08/12, 2012/08/16, 'Madrid', 2300000,'QuevedoFest2020'),
   ~~~
   
3. Tabla `cache_artista`
    ~~~
   insert into cache_artista values ('bajo', 25000),('medio', 50000),('alto', 100000),('muy alto', 200000),
   ~~~

4. Tabla `escenario`
   
    ~~~
   insert into escenario values (01, 12000, 'pequeño', 'cubierto', '4000 personas' ,'Brugal Stage'),
   (02, 18000, 'medio' , 'cubierto', '8500 personas','Bacardi Stage'),
   (03, 9000, 'pequeño', 'aire libre', '5600 personas','Jack Daniel's Stage'),
   (04, 25000, 'grande', 'techo reractil', '12000 personas','Barceló Stage'),
   (05, 32000, 'muy grande', 'aire libre', '25000 personas','Main Stage'),
   (06, 6000, 'pequeño', 'aire libre', '3200 personas','Smirnoff Stage'),
   (07, '8000', 'pequeño', 'cubierto', '6200 personas','Absolut Stage'),
   (08, 15000, 'medio', 'aire libre', '9100 personas','Negrita Stage'),
   (09, 23200, 'grande', 'cubierto', '15000 personas' ,'White Label Stage'),
   ~~~

5. Tabla `backstage`
   
    ~~~
   insert into backstage values (01, 8000, '53 mesas', 'muy grande',05),
   (02, 3400, '23 mesas', 'medio',02),
   (03, 5000, '34 mesas', 'grande',04),
   (04, 2300, '12 mesas', 'pequeño',03),
   (05, 1800, '17 mesas', 'pequeño',06),
   (06, 2000, '8 mesas', 'pequeño',01),
   (07, 4500, '21 mesas', 'medio',08),
   (08, 6500, '41 mesas', 'grande',09),
   (09, 2700, '14 mesas', 'pequeño',07),
   ~~~

   
6. Tabla `empresa`
   
    ~~~
   insert into empresa values (01, 915737695, 646754062, 'Calle Fuencarral 32','Calle Mercedes 48', 'Pablo Alfaro', 'Seguritas Stages',   'mediana'),
   (02, 913745695, 623754672, 'Calle MasPalomas 108',NULL, 'Alfonso Oracio', 'Safe N' Sound', 'pequeña'),
   (03, 965438735, NULL , 'Calle Malvarosa 45',NULL, 'Matias Sanchez', 'Light Power', 'mediana'),
   (04, 918433091, 688744163, 'Calle Marroquina 192','Calle Antonio Casero 18', 'Michael Doherty', 'Gazprom', 'multinacional'),
   (05, 939732835, 617054032, 'Calle Puerta Bonita 4',NULL, 'Francisco Torres', 'Sound Beats', 'mediana'),
   (06, 914767085, 652784061, 'Calle Sierra Carbonera 51','Calle del Alguacil 12', 'Mateo Arias', 'Play Records', 'multinacional'),
   (07, 914235135, NULL, 'Poligono Industrial Las Mercedes,NULL, 'Pablo Sarabia', 'Nostra luz', 'mediana'),
   (08, 913777312, 616734182, 'Calle Uceda 10',Poligono Industrial Las Nieves, 'Ricardo Perez', 'Just Eat', 'multinacional'),
   (09, 912417094, 641757012, 'Calle Ramon Perez de Ayala 102',NULL, 'Pablo Aguilar', 'Uber Eats', 'multinacional'),
   (10, 921747095, 691754752, 'Calle de La Marroquina 15','Calle Almonacid 19', 'Pedro Blanco', 'Securitas Direct', 'mediana'),
   (11, 913757215, 626754701, 'Parque de la Fuente del Berro',NULL, 'Lorenzo Milá', 'TVE', 'multinacional'),
   (12, 955017655, NULL, 'Calle Puerto de Canfranc 12',NULL, 'Alfredo Sanchez', 'Glovo', 'multinacional'),
   (13, 913706335, 656785401, 'Poligono Industrial de Getafe','Calle Mateo Lopez 16', 'Joaquin Perez', 'M1 Studios', 'Multinacional'),
   (14, 935706605, 626724364, 'Calle Isco 56','Poligono Industrial de Alicante', 'Adolfo Sanchez', 'Mk The Plug', 'mediana'),
   (15, 913577895, 616753051, 'Calle Francisco de Vitoria 11',NULL, 'David Garcia', 'Web 4 you', 'multinacional'),
   (16, 913727194, 690675302, 'Calle Ronda de Segovia 1','Calle Matias Prat 48', 'Rodrigo Alvarez', 'World web', 'mediana'),
   (17, 912757642, 622723402, 'Calle Aluche 55','Calle Atocha 31', 'Ignacio Perez', 'Antena 3', 'pequeña'),
   (18, 955337098, 611454562, 'Calle Medina 54',NULL, 'Pablo Alfaro', 'Light 4 you', 'mediana'),
   (19, 923727598, 623757162, 'Calle Sierra Madrona 32',NULL, 'Pablo Iglesias', 'Ghosty Records', 'pequeña'),
   (20, 945730695, 646754032, 'Calle Fuencarral 18',NULL, 'Pablo Nieto', 'Food Express', 'mediana'),
   ~~~
   
 7. Tabla `web`
      ~~~
      insert into web values (15, 'Facebook', 'Twitter', 'Server.net','Web4you.com'),
      (19, 'Facebook y Twitter', 'Instagram', 'Server.net','GhostyRecords.com'),
      (16, 'Facebook e Instagram', NULL, 'Servidores.net','WorldWeb.com'),
      (14, 'Facebook Twitter e Instagram', 'Telegram', 'Apache.net','MKThePlug.co.uk'),
      (13, 'Instagram y Twitter', NULL, 'Apache.net','M1OnTheBeat.com'),
       ~~~
   
 8. Tabla `seguridad`
      ~~~
      insert into seguridad values (01, 'Facebook', 'Twitter', 'Server.net','SeguritasStages.com'),
      (02, 'Facebook y Twitter', 'Instagram', 'Server.net','SafeNSound.co.uk'),
      (16, 'Facebook e Instagram', NULL, 'Servidores.net','WorldWeb.com'),
      (14, 'Facebook Twitter e Instagram', 'Telegram', 'Apache.net','MKThePlug.co.uk'),
      (13, 'Instagram y Twitter', NULL, 'Apache.net','M1OnTheBeat.com'),
      (10, 'Instagram y Twitter', 'Facebook', 'Server.net','SecuritasDirect.es'),
      ~~~
      
      
9. Tabla `catering`
    ~~~
   insert into catering values (12),(08),(09),(20),
   ~~~
   
10. Tabla `grabacion`
       ~~~
      insert into grabacion values (19),(06),(11),(17),(13)
      ~~~ 
      
11. Tabla `iluminacion`
       ~~~
      insert into iluminacion values (03),(04),(07),(19),(13),(18)
      ~~~ 
      
11. Tabla `sonido`
       ~~~
      insert into sonido values (19),(14),(13),(05),(06)
      ~~~ 
      
12. Tabla `canal_retransmision`
   
       ~~~
      insert into canal_retransmision values (01,'BBC'),(02,'Movistar'),(03,'Onda Cero'),(04,'as'),(05,'TVE'),(06,'Antena 3'),(07,'BT'),(08,'Virgin Media'),
      (09,'La Radio'),(10,'France TV'),(11,'TeleMadrid'),(12,'CNN'),(13,'Canal +'),(14,'La Sexta'),(15,'Telecinco'),(16,'ITV'),(17,'Channel 3'),(18,'America News'),
      (19,'Cuatro'),
       ~~~ 
       
13. Tabla `idioma_retransmision`
   
       ~~~
      insert into idioma_retransmision values (01,'Español'),(02,'Ingles'),(03,'Frances'),(04,'Italiano'),(05,'Arabe'),(06,'Portugues'),(07,'Ruso'),(08,'Checo'),
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
      (08, 01, 08, '128 minutos', 800 ,'diferido'),(08, 01, 02, '123 minutos', 1600 ,'diferido'),
      ~~~
      
15. Tabla `merchandising`
      ~~~
      insert into merchandising values (01, 'camiseta', 'media', 20,'M',01),(01, 'camiseta', 'media', 20,'S',01),(01, 'camiseta', 'media', 20,'L',01),
      (01, 'camiseta', 'media', 20,'XL',01),(01, 'camiseta', 'media', 25,'M',04),(01, 'camiseta', 'media', 25,'S',04),(01, 'camiseta', 'media', 25,'L',04),
      (01, 'camiseta', 'media', 25,'XL',04),(01, 'camiseta', 'media', 23,'S',12),(01, 'camiseta', 'media', 23,'M',12),(01, 'camiseta', 'media', 25,'L',12),
      (01, 'camiseta', 'media', 20,'L',05),(01, 'camiseta', 'media', 20,'S',05),(01, 'camiseta', 'media', 20,'M',05),(01, 'camiseta', 'alta', 32,'L',06),
      (01, 'camiseta', 'alta', 32,'S',06),(01, 'camiseta', 'alta', 32,'XL',06),(01, 'camiseta', 'baja', 12,'S',33),(01, 'camiseta', 'baja', 12,'L',33),
      (01, 'camiseta', 'alta', 12,'M',33),(01, 'camiseta', 'media', 20,'L',15),(01, 'camiseta', 'media', 20,'S',15),(01, 'camiseta', 'media', 20,'M',15),
      (01, 'camiseta', 'alta', 32,'L',24),(01, 'camiseta', 'alta', 32,'M',24),(01, 'camiseta', 'alta', 32,'XL',24),(01, 'camiseta', 'alta', 32,'M',28),
      (01, 'camiseta', 'alta', 32,'S',28),(01, 'camiseta', 'alta', 32,'XL',28),(01, 'camiseta', 'alta', 32,'M',07),(01, 'camiseta', 'alta', 32,'S',07),
      (01, 'camiseta', 'alta', 32,'XL',07),(01, 'camiseta', 'baja', 12,'S',32),(01, 'camiseta', 'baja', 12,'M',32),(01, 'camiseta', 'baja', 12,'XL',32),
      (01, 'camiseta', 'baja', 12,'L',32),(01, 'camiseta', 'baja', 12,'M',30),(01, 'camiseta', 'baja', 12,'S',30),(01, 'camiseta', 'baja', 12,'L',30),
      (01, 'camiseta', 'baja', 12,'M',18),(01, 'camiseta', 'baja', 12,'S',18),(01, 'camiseta', 'baja', 12,'L',18),(01, 'camiseta', 'media', 20,'S',11),
      (01, 'camiseta', 'media', 20,'M',11),(01, 'camiseta', 'media', 20,'L',11),(01, 'camiseta', 'alta', 32,'S',19),(01, 'camiseta', 'alta', 32,'M',19),
      (01, 'camiseta', 'alta', 32,'XL',19),(01, 'camiseta', 'media', 20,'S',23),(01, 'camiseta', 'media', 20,'M',23),(01, 'camiseta', 'media', 20,'L',23),
      (01, 'camiseta', 'alta', 32,'S',22),(01, 'camiseta', 'alta', 32,'M',22),(01, 'camiseta', 'alta', 32,'L',22),(01, 'camiseta', 'media', 20,'S',36),
      (01, 'camiseta', 'media', 20,'M',36),(01, 'camiseta', 'media', 20,'L',36),(02, 'gorra', 'media', 14,'S',33),(02, 'gorra', 'media', 14,'M',33),
      (02, 'gorra', 'media', 14,'L',33),(02, 'gorra', 'baja', 8,'S',12),(02, 'gorra', 'baja', 8,'M',12),(02, 'gorra', 'baja', 8,'L',12),(02, 'gorra', 'baja', 8,'XL',12),
      (02, 'gorra', 'baja', 8,'S',17),(02, 'gorra', 'baja', 8,'M',17),(02, 'gorra', 'baja', 8,'L',17),(02, 'gorra', 'baja', 8,'XL',17),(02, 'gorra', 'alta', 21,'S',30),
      (02, 'gorra', 'alta', 21,'M',30),(02, 'gorra', 'alta', 21,'XL',30),(02, 'gorra', 'alta', 21,'L',30),(02, 'gorra', 'alta', 21,'S',18),(02, 'gorra', 'alta', 21,'M',18),
      (02, 'gorra', 'alta', 21,'L',18),(02, 'gorra', 'baja', 8,'S',05),(02, 'gorra', 'baja', 8,'M',05),(02, 'gorra', 'baja', 8,'L',05),(02, 'gorra', 'baja', 8,'XL',05),
      (02, 'gorra', 'baja', 8,'S',09),(02, 'gorra', 'baja', 8,'M',09),(02, 'gorra', 'baja', 8,'L',09),(02, 'gorra', 'baja', 8,'XL',09),(02, 'gorra', 'alta', 21,'XL',09),
      (02, 'gorra', 'alta', 21,'S',09),(02, 'gorra', 'alta', 21,'M',09),(02, 'gorra', 'alta', 21,'L',09),(02, 'gorra', 'media', 14,'XL',09),(02, 'gorra', 'media', 14,'L',09),
      (02, 'gorra', 'media', 14,'S',09),(02, 'gorra', 'media', 14,'M',09),(02, 'gorra', 'media', 14,'L',14),(02, 'gorra', 'media', 14,'M',14),(02, 'gorra', 'media', 14,'S',14),
      (02, 'gorra', 'alta', 21,'L',14),(02, 'gorra', 'alta', 21,'M',14),(02, 'gorra', 'alta', 21,'S',14),(02, 'gorra', 'alta', 21,'XL',14),(02, 'gorra', 'alta', 21,'L',34),
      (02, 'gorra', 'alta', 21,'S',34),(02, 'gorra', 'alta', 21,'M',34),(02, 'gorra', 'baja', 8,'L',02),(02, 'gorra', 'baja', 8,'S',02),(02, 'gorra', 'baja', 8,'M',02),
      (02, 'gorra', 'baja', 8,'XL',02),(02, 'gorra', 'alta', 21,'M',02),(02, 'gorra', 'baja', 8,'S',03),(02, 'gorra', 'baja', 8,'M',03),(02, 'gorra', 'baja', 8,'L',03),
      (02, 'gorra', 'media', 14,'S',03),(02, 'gorra', 'media', 14,'M',03),(02, 'gorra', 'media', 14,'XL',03),(03, 'sudadera', 'media', 44,'S',03),
      (03, 'sudadera', 'media', 44,'M',03),(03, 'sudadera', 'alta', 62,'S',03),(03, 'sudadera', 'baja', 32,'S',14),(03, 'sudadera', 'baja', 32,'M',14),
      (03, 'sudadera', 'baja', 32,'L',14),(03, 'sudadera', 'baja', 32,'XL',14),(03, 'sudadera', 'baja', 32,'S',19),(03, 'sudadera', 'baja', 32,'M',19),
      (03, 'sudadera', 'baja', 32,'L',19),(03, 'sudadera', 'baja', 32,'XL',19),(03, 'sudadera', 'media', 44,'S',19),(03, 'sudadera', 'media', 44,'M',19),
      (03, 'sudadera', 'media', 44,'L',19),(03, 'sudadera', 'media', 44,'S',12),(03, 'sudadera', 'media', 44,'M',12),(03, 'sudadera', 'media', 44,'L',12),
      (03, 'sudadera', 'media', 44,'S',08),(03, 'sudadera', 'media', 44,'M',08),(03, 'sudadera', 'media', 44,'L',08),(03, 'sudadera', 'alta', 62,'S',21),
      (03, 'sudadera', 'alta', 62,'M',21),(03, 'sudadera', 'alta', 62,'L',21),(03, 'sudadera', 'alta', 62,'XL',21),(03, 'sudadera', 'alta', 62,'S',29),
      (03, 'sudadera', 'alta', 62,'M',29),(03, 'sudadera', 'alta', 62,'L',29),(03, 'sudadera', 'alta', 62,'XL',29),(03, 'sudadera', 'baja', 32,'S',31),
      (03, 'sudadera', 'baja', 32,'M',31),(03, 'sudadera', 'baja', 32,'L',31),(03, 'sudadera', 'baja', 32,'XL',31),(03, 'sudadera', 'media', 44,'S',31),
      (03, 'sudadera', 'media', 44,'M',31),(03, 'sudadera', 'media', 44,'L',31),(03, 'sudadera', 'alta', 62,'S',31),(03, 'sudadera', 'alta', 62,'M',31),
      (03, 'sudadera', 'alta', 62,'L',31),(03, 'sudadera', 'alta', 62,'XL',31),(04, 'llavero', NULL, 6,NULL,31),(04, 'llavero', NULL, 6,NULL,32),
      (04, 'llavero', NULL, 6,NULL,08),(04, 'llavero', NULL, 6,NULL,09),(04, 'llavero', NULL, 6,NULL,12),(04, 'llavero', NULL, 6,NULL,16),(04, 'llavero', NULL, 6,NULL,32),
      (04, 'llavero', NULL, 6,NULL,29),(04, 'llavero', NULL, 6,NULL,25),(04, 'llavero', NULL, 6,NULL,28),(04, 'llavero', NULL, 6,NULL,36),(04, 'llavero', NULL, 6,NULL,34),
      (04, 'llavero', NULL, 6,NULL,02),(04, 'llavero', NULL, 6,NULL,01),(04, 'llavero', NULL, 6,NULL,31),(04, 'llavero', NULL, 6,NULL,26),(04, 'llavero', NULL, 6,NULL,25),
      (04, 'llavero', NULL, 6,NULL,24),(04, 'llavero', NULL, 6,NULL,22),(04, 'llavero', NULL, 6,NULL,20),(04, 'llavero', NULL, 6,NULL,03),(04, 'llavero', NULL, 6,NULL,23),
      (05, 'disco', NULL, 12,NULL,31),(05, 'disco', NULL, 12,NULL,28),(05, 'disco', NULL, 12,NULL,26),(05, 'disco', NULL, 12,NULL,33),(05, 'disco', NULL, 12,NULL,30),
      (05, 'disco', NULL, 12,NULL,21),(05, 'disco', NULL, 12,NULL,14),(05, 'disco', NULL, 12,NULL,12),(05, 'disco', NULL, 12,NULL,10),(05, 'disco', NULL, 12,NULL,08),
      (05, 'disco', NULL, 12,NULL,02),(05, 'disco', NULL, 12,NULL,07),(05, 'disco', NULL, 12,NULL,11),(05, 'disco', NULL, 12,NULL,29),(05, 'disco', NULL, 12,NULL,35),
      ~~~      
      
      
 16. Tabla `patrocinador`
   
       ~~~
      insert into patrocinador values (01,915737695,646754062, 'Alimentacion', 'Calle Alcala de Guadaira 11' ,'Alsea'),(02,925757690,643750062, 'Alimentacion', 'Calle Alcala de       Henares 11' ,'Doritos'),(03,915336605,646054360, 'Alimentacion', 'Calle Montreal 15' ,'Pepsi-Cola'),(04,924730685,636757062, 'Hosteleria', 'Calle Francisco Jimenez 12'          ,'Bar Manolo'),(05,935730645,621734062, 'Suministros', 'Poligono Industrial de San Fernando' ,'Amazon'),(06,912407795,643444002, 'Alimentacion', 'Calle Barras bravas            10' ,'Lays'),(07,917747195,636750012, 'Reposteria', 'Calle Doña Asuncion 23' ,'Carrefour'),(07,918757095,600751032, 'Deportes', 'Calle Alcala 45' ,'Nike'),
      (08,912730625,626359061, 'Deportes', 'Calle San Rafael 23' ,'Adidas'),(09,935537605,640750462, 'Reposteria', 'Calle Los Santos 10' ,'Arla'),
      (10,915017095,626004062, 'Alimentacion', 'Calle de Los Buitres 14' ,'Alcampo'),(11,915430615,616750012, 'Alimentacion', 'Calle San Ramon 11' ,'Dia'),
      (12,912738691,613650012, 'Deportes', 'Calle Paseo de la Victoria' ,'Asics'),(13,915430415,641054022, 'Tecnologia', 'Calle Las Magras 2' ,'Google'),
      (14,916730215,626054102, 'Tecnologia', 'Calle San Vicente 17' ,'Facebook'),(15,914227600,623751002, 'Tecnologia', 'Calle Vladimir 50' ,'Twitter'),
      ~~~     
