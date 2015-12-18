# De rook en het raam
Amber van den Bos  
December 18, 2015  





## introductie

Wanneer 's avonds in bed lig, ruik ik vaak een rooklucht. Geen sigarettenrook (die ruik ik ook, maar daar heb ik het nu niet over), maar een rooklucht die ik associeer met hout or papierverbranding. Niet elke avond of nacht en soms is het lichter en soms zwaarder, maar altijd genoeg om irritant te zijn voor mijzelf en voor mijn longen.  
De voor de hand liggende verklaring is dat iemand in de buurt dan een houtkachel aansteekt. Wat daar niet bij past, is dat de verbrandingsrook daarvoor soms te synthetisch aan doet. Bovendien gebeurt het vrijwel altijd in het eerste uur dat ik op bed lig en zo regelmatig leef ik niet. Dan moet het wel haast iemand zijn die in de gaten houdt wanneer ik naar bed ga. Iemand die vlak bij woont dus.  
Om te kijken waar de rook vandaan kwam, ben ik een aantal keren weer uit bed gegaan en heb mijn neus uit het raam gestoken, zowel aan de voor- als aan de achterkant van mijn huis. Het vreemde is dat elke keer de rook buiten niet of een heel stuk minder aanwezig is. Als de rook van buiten naar binnen zou komen, zou het buiten op dat moment toch hetzelfde of sterker moeten zijn, maar het lijkt eerder andersom te zijn. De rook gaat eerder van binnen naar buiten. 
Dat pleit niet voor een houtkachel in de buurt waarvan de rook door het open raam bij mij naar binnen waait. De rook moet wel uit één van de aangrenzende appartementen komen. Hoe, dat weet ik niet. Ik heb wel een vermoeden.

## wat denk ik

Het leek erop dat de rook meer voorkwam, wanneer ik het raam open heb staan. Daarom dacht ik ook dat de rook door het raam naar binnen kwam. Nu dat niet zo blijkt te zijn, denk ik dat mijn huis, en dan vooral mijn slaapkamer, functioneert als een schoorsteen voor andere bewoners.  
Een alternatieve verklaring is dat de stokende bewoners zien dat ik het raam open heb staan en daarom de rook produceren. Dat zou raar zijn, maar er gebeuren hier wel meer rare dingen, met name sinds ik een conflict heb over geluidsoverlast. Sommige mensen kiezen dan voor alternatieve communicatie zal ik maar zeggen.  

## wat ga ik doen

Ik ga kijken of de rook vaker voorkomt terwijl het raam open is. Daarnaast kijk ik ook of de rook vaker voorkomt wanneer het raam open is terwijl de andere bewoners het kunnen zien. Dat is overdag, want 's avonds komen ze nauwelijks meer buiten.  
Hiervoor zet ik een schema op van raam open/raam dicht voor overdag en 's avonds. Dit geef ik aan als  

* 00: hele dag raam open  
* 01: overdag raam open, 's avonds raam dicht 
* 10: overdag raam dicht, 's avonds raam open  
* 11: hele dag raam dicht  
  
Om effecten van andere leefpatronen uit te sluiten herhaal ik dit schema zeven weken zodat ik voor elke weekdag elk schema één keer heb gehad. Hierbij gebruik ik een willekeurige verdeling, zodat ik niet één week het raam de hele tijd open heb of de hele tijd dicht.  
Dat schema noteer ik in mijn agenda en vervolgens ga ik elke ochtend een kruis: wel rook, of een nul: geen rook, zetten voor de afgelopen nacht.

## de uitwerking

Omdat ik nu eenmaal ook maar een mens ben, vergeet ik wel eens om het raam weer open of weer dicht te zetten. Dan wijzig ik het schema voor die dag in wat ik werkelijk heb gedaan, en voeg ik het gemiste schema aan het eind van de periode weer toe op dezelfde weekdag. Om de verlengde periode op te vullen voeg ik patronen toe tussen de extra dagen. Uiteindelijk loopt de onderzoeksperiode van 27 april 2015 tot en met 19 juni 2015.


####_de gegevens_  
Over de 54 dagen van de registratie zijn de raam open/raam dicht patronen als volgt verdeeld:

**tabel 1: frequentie uitgevoerd raam open/dicht schema naar weekdag**

```
##                                    weekdag
## schema                              zo ma di wo do vr za Totaal
##   00: hele dag open                  2  2  2  2  2  2  2     14
##   01: overdag open, 's avonds dicht  2  3  2  2  2  2  1     14
##   10: overdag dicht, 's avonds open  2  1  2  2  2  2  2     13
##   11: hele dag dicht                 1  2  2  2  2  2  2     13
##   Totaal                             7  8  8  8  8  8  7     54
```

Het is niet perfect, maar de raam open/dicht schema's zijn redelijk netjes verdeeld over de weekdagen. In elk geval heeft elke weekdag éénmaal elk schema gehad.

####_testen van het eerste vermoeden_  
Is het zo dat er vaker rook is als ik 's avonds het raam open heb? Hiervoor maak ik eerst een tabel met 's avonds raam open of dicht versus wel of geen rook. Voor deze tabel bereken ik vervolgens een chi-kwadraat.  

**tabel 2:geregistreerde frequentie raam open/dicht vs wel of geen rook**

```
##                            Staat het raam 's avonds open
## Komt er rook door de vloer? open dicht Totaal
##                   geen rook   18    24     42
##                   wel rook     9     3     12
##                   Totaal      27    27     54
```
Omdat de verwachte frequenties in alle cellen > 5 zijn op een totaal van 54 observaties gebruik ik de gewone [Pearson chi-kwadraat](https://en.wikipedia.org/wiki/Pearson's_chi-squared_test)  en niet de [Yates correctie](https://en.wikipedia.org/wiki/Yates's_correction_for_continuity). 
  
**tabel 3: verwachte frequentie raam open/dicht vs wel of geen rook**

```
##                            Staat het raam 's avonds open
## Komt er rook door de vloer? open dicht
##                   geen rook   21    21
##                   wel rook     6     6
```
De chi-kwadraat is 3.857. Met 1 vrijheidsgraden (df) levert dat een eenzijdige p-waarde van 0.0248 (conf:   -1, -0.0805). 
Zo te zien lijkt het inderdaad uit te maken of het raam 's avonds open staat. Dan is er significant vaker sprake van rook.

####_testen van het tweede vermoeden_
Voor het geval de andere bewoners knetter-van-lotje zijn en expres rook veroorzaken als ik het raam open houd, test ik of er een relatie is tussen het raam overdag open en de rook 's avonds. Dit gaat op dezelfde manier als hierboven, maar dan met de variabele voor raam 's avonds open vervangen door de variabele voor raam overdag open.

**tabel 4:geregistreerde frequentie raam open/dicht vs wel of geen rook**

```
##                            Staat het raam overdag open
## Komt er rook door de vloer? open dicht Totaal
##                   geen rook   20    22     42
##                   wel rook     8     4     12
##                   Totaal      28    26     54
```

De chi-kwadraat is 1.356. Met 1 vrijheidsgraden (df) levert dat een eenzijdige p-waarde van 0.122 (conf:   -1, 0.0668). Er is geen significant verband tussen het openstaan van het raam overdag en de rook 's avonds.

##samenvatting  

Naar aanleiding van door mij ervaren rookoverlast, heb ik onderzocht hoe rook (als in: brandlucht) in mijn huis terecht komt. Hiervoor heb ik 54 dagen lang volgens verschillende schema's het raam in mijn slaapkamer open dan wel dicht gedaan en geregistreerd of ik rookoverlast ervaarde.  
Omdat de rook buitenshuis vrijwel nihil is en binnenshuis sterk aanwezig, kan het niet zo zijn dat de rook door het openstaande raam van buiten naar binnen komt. De rook treedt 's avonds op, niet overdag, duurt ongeveer een half uur tot een uur, soms langer.  
Er lijkt een samenhang te zijn tussen het 's avonds open of dicht zijn van het raam en geregistreerde rookoverlast 's avonds. Er blijkt geen samenhang te zijn tussen het overdag open of dicht zijn van het raam en de geregistreerde rookoverlast 's avonds.  

##conclusie  
Op basis van deze bevindingen, concludeer ik dat het openstaande raam fungeert als een trekgat (schoorsteen) voor verbrandingsrook uit één van de aangrenzende appartementen. In deze appartementen zijn de vloeren en muren niet luchtdicht. De schoorstenen zijn helemaal poreus, met oude, gebroken stenen, afbrokkelend voegwerk en zonder binnenmantel (Kan de brandweer het gebruik daarvan niet eens verbieden in Bezuidenhout?). Wanneer in een appartement niet of verkeerd wordt geventileerd, kan lucht en rook daaruit gemakkelijk in een ander appartement terecht komen waar de doorstroming van de lucht beter geregeld is.  
Er zijn natuurlijk alternatieve interpretaties mogelijk. De kans op fantosmia, zoals een sukkel zonder enige medische opleiding wilde diagnosticeren, is bij structurele patronen (locatie- en tijdgebonden en alleen als ik geen bezoek heb) echter minimaal. Inmiddels heb ik deze mogelijkheid ook aan verschillende artsen voorgelegd die deze aandoening (na medisch onderzoek, excuses voor de oplopende zorgkosten) zeer onwaarschijnlijk vinden. Het klopt dat ik een neus als een bloedhond heb, maar dat is heel iets anders dan het verzinnen van geuren. Zo'n scherpe neus is inderdaad vooral vervelend voor mijzelf (Den Haag stinkt, voor het geval u het nog niet wist). Overigens is het ook vervelend voor mensen die niet willen dat ik ruik wat ze doen. Dat begrijp ik.  
Voor andere alternatieve verklaringen sta ik open, net als voor praktische adviezen voor vervolgonderzoek.  
De data die voor deze analyses is verzameld en gebruikt, staan samen met de Rmarkdown, markdown en de html in een [github](https://github.com/bosamber/rookraam2015) repository, zodat bovenstaande analyses te reproduceren en/of uit te breiden zijn.

   
