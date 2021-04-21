27971d36 (temmip 2021-04-21 11:15:19 +0300  1)  diff --git a/log.md b/log.md
27971d36 (temmip 2021-04-21 11:15:19 +0300  2) # Tässä näkyy mistä tiedostosta muutokset katsotaan
27971d36 (temmip 2021-04-21 11:15:19 +0300  3)  index 594eb21..c76c37e 100644
27971d36 (temmip 2021-04-21 11:15:19 +0300  4)  --- a/log.md
27971d36 (temmip 2021-04-21 11:15:19 +0300  5)  +++ b/log.md
27971d36 (temmip 2021-04-21 11:15:19 +0300  6)  @@ -1,6 +1,6 @@
27971d36 (temmip 2021-04-21 11:15:19 +0300  7) 
27971d36 (temmip 2021-04-21 11:15:19 +0300  8) # Diff luo a ja b tiedostot joista se katsoo mitä on muuttunut
27971d36 (temmip 2021-04-21 11:15:19 +0300  9) 
27971d36 (temmip 2021-04-21 11:15:19 +0300 10) 
27971d36 (temmip 2021-04-21 11:15:19 +0300 11)   # Tässä on logi viikon 15 git harjoituksista joita teimme palvelinhallintakurssilla
27971d36 (temmip 2021-04-21 11:15:19 +0300 12)  
27971d36 (temmip 2021-04-21 11:15:19 +0300 13)  -
27971d36 (temmip 2021-04-21 11:15:19 +0300 14)  +## Diffiä varten toinen otsikko
27971d36 (temmip 2021-04-21 11:15:19 +0300 15)  
27971d36 (temmip 2021-04-21 11:15:19 +0300 16) 
27971d36 (temmip 2021-04-21 11:15:19 +0300 17) # terminaalissa kohta "+## Diffiä varten toinen otsikko" näkyisi vihreänä
27971d36 (temmip 2021-04-21 11:15:19 +0300 18) 
27971d36 (temmip 2021-04-21 11:15:19 +0300 19)  
27971d36 (temmip 2021-04-21 11:15:19 +0300 20)   commit c787b4813b58d3eeb0c5832e362a38b6f6b454ca (HEAD -> main, origin/main, origin/HEAD)
27971d36 (temmip 2021-04-21 11:15:19 +0300 21) # tässä näkyy commit tunnus



	- komennolla git blame tiedostonimi voi tarkistaa kuka on muokannut tiedostoa viimeksi
	- tärkeimmät tiedot joita komennolla näkee on timestampit ja muokkaajan nimi
	- git blame komennolla on monia parametreja joiden avulla tulostetta voi muokata
	- esimerkiksi git blame -L 1,3 tiedosto.ms tulostaa rivit 1-3 kyseisestä tiedostosta
	- git blame -s tiedosto.md ei näytä muokkaajaa ja tuloste on hieman siistimpi
	- git blame -E tulostaa muokkaajan sähköpostin käyttäjänimen sijaan
