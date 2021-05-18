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
      ~~~
