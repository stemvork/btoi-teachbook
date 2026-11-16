# Kladblok

## Werksessie 16 november (week 46/47)
Ik heb van alles op papier uitgewerkt en overwogen, vandaag (maandag 16 november) wil ik hiervan zo veel mogelijk online krijgen.

### Globale lessenindeling
1. (Evalueren) Kom ik nog thuis? Wat weet ik al?

In deze les wordt de voorkennis opgehaald en besproken, waaronder coördinaten, Pythagoras en goniometrie. Leerlingen maken kennis met BeeNav en de centrale vraag door middel van een video met kijkvragen. Tot slot is er aandacht voor (een deel van) de TUV diagnostische voortoets.

2. (Engageren) Waarom komt een bij of drone nooit precies thuis met padintegratie alleen?

Leerlingen ervaren met blinddoeken hoe het is om stukken te lopen en daarbij fouten te maken (in hoek en afstand). Daardoor komen zij niet in dezelfde eindpunten terecht. Ter verbreding wordt gekeken naar gegist bestek in de scheepvaart. Twee verschillende routes kunnen dezelfde weg terughebben, waar het verschil tussen route en verplaatsing kan worden besproken.

3. (Exploreren) Hoe schrijf ik een verplaatsing op?

Leerlingen leren dat vectoren als object meerdere representaties kennen: pijl, kentallen, poolvorm. Vectoren hebben eigenschappen zoals lengte en richtingshoek, waarbij opnieuw aandacht mag zijn voor de arctangens en kwadranten. Leerlingen zouden moeten kunnen onderscheiden wanneer twee pijlen dezelfde vector zijn.

4. (Exploreren) Hoe houdt een drone bij waar hij is?

In deze les worden de basisbewerkingen bij vectoren aangeleerd. Padintegratie is het optellen van stapjes. De thuisvector is de tegengestelde vector van die som van stapjes. Leerlingen kunnen na deze les de thuisvector bepalen die hoort bij een bepaalde route en begrijpen het verschil tussen a-b en b-a (zelfde lengte, tegengestelde richting).

5. (Exploreren) Wijst mijn thuisvector de goede kant op?

Er is een verschil tussen de echte en de voorspelde thuisvector. We berekenen de hoek tussen deze twee vectoren en gebruiken de cosinusregel om de relatie tussen hoek, inproduct en route te begrijpen. De uitkomst van het inproduct is een getal, geen vector. 

6. (Exploreren) Kom ik met deze stap dichter bij huis?

Als de drone of bij in kleine stappen naar huis vliegt, dan kun je je afvragen of die stap effectief is. Dat heeft te maken met de maximale hoekfout en daaruit volgt ook een optimale staplengte. Hier zit een link met de examenopgave. Leerlingen gaan voorspellen, berekenen en controleren.

7. (Toepassen) Kan ik zelf een padintegrator bouwen?

Het werken met simulaties kan veel inzicht geven. In GeoGebra of een andere tool werken leerlingen (nog zonder ruis) aan het dusver opgebouwde padintegratiemodel. Dit is ook een goed moment te reflecteren op wat onderbouw (?) natuurkunde: snelheid x tijd en biedt een herhaling van het optellen van vectoren. Klopt mijn eindpunt met de berekening?

8. (Toepassen) Wat doet een kleine koersfout met waar ik uitkom?

Modelleren van onzekerheid voelt als een prachtige uitbreiding van het curriculum zoals dat bij wiskunde B bestond. Door de route naar huis te modelleren met een lijn (vectorvoorstelling), de hoek tussen lijnen te berekenen en snijpunten te bepalen, wordt gewerkt aan vectormeetkunde EN aan modelleren. De gemaakte misser moet worden vergeleken met de straal van het thuisgebied om de praktische betekenis te begrijpen.

9. (Toepassen) Hoe nauwkeurig moet het zijn?

Door de parameters van het model te variëren, door de ruis te variëren, door de maximale hoekfout en andere berekeningen dan telkens opnieuw te maken/simuleren komen er verschillende datapunten aan het licht die leerlingen in groepjes met elkaar kunnen vergelijken. Daarbij komt dan wiskundig communiceren kijken en het trekken van conclusies uit de gemaakte berekeningen en het vergelijken onderling.

10. (Expliciteren) Welk model heb ik gebouwd en hoe goed is het?

Modelleercyclus wordt expliciet gemaakt, vectorenkennis wordt samengevat en er is vooral aandacht voor aannames en het vergelijken van de resultaten met het echte paper. Leerlingen kunnen aannames en het effect van die aanname benoemen.

11. (Consolideren) Kan ik het in een nieuwe situatie?

Dit staat nog het meest open, maar ik zou het mooi vinden aan het einde van deze lessenserie leerlingen ook in aanraking te brengen met andere contexten. Dat kan de scheepvaart of ruimtenavigatie zijn, of opnieuw iets biologisch zoals mieren. Leerlingen zouden voornamelijk zelfstandig aan de slag moeten kunnen, zo consolideren zij hun kennis.

12. (Consolideren) Wat is mijn antwoord op de onderzoeksvraag?

Hier is ruimte voor allerlei afrondingen: vergelijken van verschillende modellen, onderbouwing daarvan, herhalen (of afnemen) van de TUV voortoets, laatste herhalingen en verdiepingen van vectorkennis.

### Twee tot vijf lessen volledig uitgewerkt


### Examenopgave feedback Jeroen verwerken

### Definitieve leerdoelen en succescriteria

Eindterm 21 bevat een verplicht deel in vijf bullets, hier uitgewerkt tot leerdoelen 1 t/m 9 met door mij opgestelde succescriteria. De volgorde is soms iets anders, maar per groep staat geciteerd welke bolletjes worden gedekt. Daarnaast staan er bullets met "te denken valt aan" die hierin voor nu ook zijn meegenomen als leerdoel 10 t/m 12.


#### A. De vector als object
> een vector interpreteren als een object met lengte en richting en typeren in termen van richtingshoek en kentallen;
>
> berekenen van de lengte van een vector;
1.  De leerling legt uit dat een vector een object is met lengte en richting, los van de plek waar de pijl getekend wordt (vrije vector), en onderscheidt een vector van een punt met coördinaten en van een getal (scalair).
2.  De leerling beschrijft een vector op drie manieren en wisselt daartussen: als pijl, met kentallen $\begin{pmatrix}x\\ y\end{pmatrix}$ en met lengte + richtingshoek (poolvorm).
3.  De leerling berekent de lengte van een vector uit de kentallen met Pythagoras, en de kentallen uit lengte en richtingshoek met $x=|v|\cdot\cos(\varphi)$, $y=|v|\cdot\sin(\varphi)$; en omgekeerd de richtingshoek uit de kentallen, met de arctangens en het juiste kwadrant.

#### B. Rekenen met vectoren
> rekenen met vectoren: optellen en scalair vermenigvuldigen;
4.  De leerling telt vectoren op en trekt ze af, zowel meetkundig (kop-staart, parallellogram) als met kentallen, en legt uit waarom beide methodes hetzelfde opleveren.
5.  De leerling vermenigvuldigt een vector met een scalair, inclusief negatieve scalairen, en interpreteert dat als oprekken/inkrimpen en omkeren; bepaalt een eenheidsvector (normeren).
6.  De leerling gebruikt vectoren om verplaatsingen te combineren: de verbindingsvector $\overrightarrow{AB} = \vec{b} − \vec{a}$, en een som van verplaatsingen $\vec{t}=\vec{a}+\vec{b}+\vec{c}+\ldots$ (resultante).

#### C. Lijnen
> beschrijven van lijnen in het vlak met vectorvoorstellingen;
7.  De leerling stelt een vectorvoorstelling op van een lijn (steunvector + λ · richtingsvector), interpreteert de parameter λ, en zet om naar een vergelijking $ax + by = c$ en terug.
8.  De leerling bepaalt met vectorvoorstellingen het snijpunt van twee lijnen of toont aan dat ze evenwijdig zijn of samenvallen.

#### D. Inproduct en hoek
> berekenen van het inproduct van twee vectoren en de hoek tussen twee vectoren.
>
> onderzoeken of twee lijnen elkaar loodrecht snijden;
9.  De leerling berekent het inproduct met kentallen en via $|a|\dot|b|\cdot\cos(\varphi)$, berekent daarmee de hoek tussen twee vectoren, weet dat de uitkomst van het inproduct een getal is, en interpreteert het inproduct als (lengte maal) projectie.
10.  De leerling onderzoekt met het inproduct of twee lijnen of vectoren loodrecht op elkaar staan (inproduct = 0) en gebruikt een normaalvector van een lijn.

#### E. Toepassen in contexten
> de relatie tussen de plaats-, snelheids- en versnellingsvector bespreken;
> 
> vectoren gebruiken bij probleemsituaties;
>
> vectoren gebruiken om een evenwichtsstand (red. som van de krachten is de nulvector) uit de natuurkunde te beschrijven.
11.  De leerling beschrijft beweging met plaats-, snelheids- en versnellingsvector: de snelheidsvector als verandering van plaats per tijd (raakt aan de baan), de versnellingsvector als verandering van snelheid per tijd, en herkent dat een versnelling ook bij constante snelheid kan optreden (bocht).
12.  De leerling modelleert een probleemsituatie met vectoren (bijv. navigatie, krachtenevenwicht: de som van de krachtvectoren is de nulvector) en controleert of de uitkomst past bij de context.

### Eerste toevoegingen expertrapport

### Video over Bee-Nav
[Efficient robot navigation inspired by honeybee learning flights](https://www.youtube.com/watch?v=Og6wvKqWLow)

Voordelen:
- Visueel aantrekkelijk en gevarieerd (LEGO, experiment, foto's)
- Kort en krachtig, snel kennismaken met de concepten
- In samenwerking met de auteurs van het paper

Nadelen:
- Computerstem
- Engelstalig en vaktermen worden niet verder toegelicht (bijv. odometry)
- Achtergrondmuziek


