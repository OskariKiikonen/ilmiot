# Sääasema 2020  
## Vaatimusmäärittely  
 **Sovelluksen tarkoitus**  
 * Mitataan ympäristön lämpötila- ilmankosteustietoja.  
 * Saatuja tietoja voidaan tarkistella tekstinä ja grafiikkana web sovelluksella.  
 
 **Käyttäjät**  
 
 Web sovellus on tarkoitettu julkiseen käyttöön.  
 
 **Käyttöliittymä**  
 
 Käyttöliittymä koostuu kahdesta näkymästä:  
  1. Tekstimuotoisen datan selaamiseen tarkoitettu näkymä  
  1. Grafiikkamuotoisen datan selaamiseen tarkoitettu näkymä  
  
  **Jatkokehitysideoita**  
  
  Säätietojen selaaminen valitulla aikavälillä.  
 
 ## Arkkitehtuurikuvaus  
 
 **Luokkakaavio**  
 
 
 
 **Sekvenssikaavio**  
 
 
 
 **Työaikakirjanpito**  

10.11 | 2h | Projektin suunnittelu  
24.11 | 3h | Laitteiston asennus  
25.11 | 2h | Ohjelmointi  
01.12 | 5h | Testaaminen ja dokumentointi  
08.12 | 9h | käyttökoulutus  
yht | 28  




# Alan toimintaympäristöt ja ilmiöt  
Tekstiä voi kirjoittaa vaikka **lihavoituna**, *kursivoituna* tai ~~yliviivattuna~~.  

Erilaisia otsikoita voi tehdä laittamalla # merkkejä peräkkäin:  
# 1. tason otsikko  
## 2. tason otsikko  
### 3. tason otsikko  
#### 4. tason otsikko  
##### 5. tason otsikko  
###### 6. tason otsikko  

Listoja voit tehdä näin:  
* Listan ensimmäinen elementti
* Listan toinen elementti
* Listan kolmas elementti
  * Kolmannen elementin ensimmäinen alielementti  
  * Kolmannen elementin toinen alielementti

Numeroitu lista:  
1. Eka juttu  
1. Toka juttu  
1. Kolmas juttu  
   1. Kolmannen eka juttu  
   1. Kolmannen toinen juttu  
   
Readme.md -tiedostoon voi laittaa myös kuvia.
![Hyvinvointiteknologia](hyvis.jpg)

Linkitkin toimii:
http://www.google.com (automaattisesti)  
[Google](http://google.com)  

Näinkin voi tehdä  
> Kirjoitetaan tähän tekstiä  
> Tähän lisää tekstiä  

Tässä tapauksessa teksti tulee laatikkoon:  
````  
function kirjoitaTeksti(kirjoita)  
 if(kirjoita) {  
  console.log("parametri oli tosi")
  }
````  
Taulukon sarakkeen otsikko | Seuraavan sarakkeen otsikko  
---------------------|----------------------
ABC | 123  
XYZ | 456  

:sunglasses:
