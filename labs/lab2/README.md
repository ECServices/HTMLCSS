# Laboration 2

I den här laborationen kommer du att bygga en två olika layouter med hjälp av HTML och CSS.

I båda uppgifterna ska du använda dig av [flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout) och i den andra uppgiften ska du även använda [media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries).

## Uppgift 1

Skapa ett responsivt rutnät med hjälp av flexbox. Bilderna illustrerar hur rutorna ska se förhålla sig till varandra beroende på skärmstorlek. Följande krav ska vara uppfyllda:

* Rutorna ska växa på bredden så att de tillsammans alltid fyller ut 100% av skärmens bredd (exklusive eventuella margins)
* På stora skärmar ska rutorna ligga i förhållande till varandra enligt *Bild 1*.
* På små skärmar (t.ex. mobiler) ska rutorna ligga i förhållande till varandra enligt *Bild 2*

![big](images/1-big.png)

*Bild 1*

![small](images/1-small.png)

*Bild 2*


## Uppgift 2

Skapa en HTML-sida och gör en layout för en strömningstjänst för filmer.  Till din hjälp har du fått ett antal bilder som ska illustrera olika filmer på tjänsten. Du hittar bilderna i mappen `resources`.

Layouten ska vara responsiv och byggd enligt följande krav:

* Skapa en header med en titel och tre länkar. Headern ska täcka hela sidans bredd.
* Om fönsterbredden är mindre än 700px ska länkarna inte synas och titel-texten ska centreras.
* Bilderna ska visas med `img`-taggar.
* Alla bilderna ska visas efter varandra på flera olika rader beroende på skärmens storlek.
* Varje rad ska visa så många bilder som det får plats.
* När det inte får plats fler bilder på en rad ska resterande bilder visas på en ny rad.
* Bredden på en bild ska inte understiga 150 pixlar.
Bilderna ska ha en marginal på mellan 20 till 40 pixlar till varandra.
* Bilderna ska ändra sin storlek så att de alltid fyller ut en rad oavsett antal.
* Alla bilder som befinner sig på samma rad ska vara lika stora.
* Layouten ska uppfylla kraven oavsett oavsett hur många bilder du väljer att visa.


Bilderna nedan illustrerar hur layouten ska fungera vid större och mindre fönsterstorlekar.

![big](images/2-big.png)

_Stor fönsterstorlek_

![small](images/2-small.png)

_Liten fönsterstorlek_
