# Webbserver
Webbserver läxor och project
Fråga 1:
1.      SELECT ålder FROM test2 WHERE förnamn LIKE ’%tt%’;
2.      SELECT förnamn FROM test2 WHERE efternamn IS NULL;
3.      SELECT * FROM test2 WHERE förnamn LIKE ‘K%’;
4.      SELECT förnamn FROM test2 WHERE ålder<13;
5.      SELECT efternamn FROM test2;
6.      SELECT förnamn, ålder FROM test2 WHERE efternamn=’Anka’;
7.      SELECT * FROM test2 WHERE förnamn LIKE ‘%u%’;
 
Fråga 2:
1.      CREATE TABLE städer (stad varchar(32), kommun varchar(32), landskap varchar(32), län varchar(32), postkod int(5), invånare int(8));
 
Fråga 3:
1.      INSERT INTO städer (stad, kommun, landskap, län, postkod, invånare) VALUES (’Lerum’, ’Lerums Kommun’, ’Västergötland’, ’Västra Götalands Län’, 44303, 40700);
2.      INSERT INTO städer (stad, kommun, landskap, län, postkod, invånare) VALUES (’Stockholm’, ’Stockholms Kommun’, ’Södermanland’, ’Stockholms Län’, 11121, 952000);
3.      INSERT INTO städer (stad, kommun, landskap, län, postkod, invånare) VALUES (’Göteborg’, ’Göteborgs Kommun’, ’Västergötland’, ’Västra Götaland’, 41101, 572800);
 
Fråga 4:
1.      SELECT stad, invånare FROM städer WHERE landskap=’Dalarna’;
2.      SELECT stad, invånare FROM städer WHERE invånare>20000;
3.      SELECT stad, invånare FROM städer WHERE invånare>10000 AND invånare<20000;
4.      SELECT stad, invånare FROM städer WHERE postkod LIKE ‘4%’;
5.      SELECT stad, invånare FROM städer WHERE län=’Västra Götalands Län’;
6.      SELECT stad, invånare FROM städer WHERE kommun LIKE ‘A%’;
7.      SELECT stad, invånare FROM städer WHERE invånare<50000;
8.      SELECT stad, invånare FROM städer WHERE stad LIKE ‘%e%’;
9.      SELECT stad, invånare FROM städer WHERE landskap=’Hälsingland’ AND invånare>20000;
10.   SELECT stad, invånare FROM städer WHERE stad LIKE ‘B%’ AND invånare>25000;
 
Fråga 5:
1.      SELECT * FROM städer ORDER BY invånade DESC;
2.      SELECT * FROM städer ORDER BY stad ASC;
