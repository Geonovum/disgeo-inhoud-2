## Functionele objecttypen

In dit hoofdstuk is een eerste aanzet opgenomen tot nadere typering van de verschillende functionele objecttypen in de samenhangende objectenregistratie. Deze aanzet is primair gebaseerd op de ook nu reeds in de bestaande basisregistraties opgenomen functionele objecttypen en uitgebreid met netwerken voor wegen, water en spoorwegen. 

Vanwege een strikte scheiding tussen fysieke objecttypen en functionele objecttypen in de nu bestaande basisregistraties zijn op deze typeringen soms beperkte aanpassingen doorgevoerd. Ook zijn enkele eerste wijzigingen voorgesteld die het gevolg zijn van het in hoofdstuk 2 genoemde uitgangspunt over heldere definiëring. Tenslotte is daar waar mogelijk reeds bekeken in hoeverre aanpalende sectorale typeringen aanleiding kunnen geven tot een aangescherpte typering.

Deze typering is in deze fase van het traject vooral bedoeld om een eerste indruk te geven van de richting waarin de inhoud van de samenhangende objectenregistratie zich beweegt. Samen met experts vanuit de verschillende domeinen en gebruikers zal in het vervolg nog nader onderzoek noodzakelijk zijn om tot definitieve typeringen met bijbehorende definities te komen. Ook zal daarbij nog moeten worden bepaald in hoeverre het nu opgenomen onderscheid tussen de verplichte classificatie en de vrijwillige classificatie aanpassing behoeft. Hierbij is het uiteindelijk de bedoeling om te komen tot een “uitklapmodel” van typeringen, waarbij gedetailleerde typeringen (in de samenhangende objectenregistratie, maar bij voorkeur ook in sectorale registraties) altijd een nadere uitwerking vormen van één bepaalde hoofdtypering (in de samenhangende objectenregistratie).

De uitbreiding met objecttypen voor netwerkinformatie is gebaseerd op het Conceptueel model netwerken, juli 2020. 



### Transportvoorziening; weg

<div class='note'>
    Transportvoorziening in de SOR moet nog verder uitgewerkt worden o.b.v. het conceptuele model netwerken.
</div>

#### Knoop
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Knoop|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Knoop  |
|---|---|
| Definitie | Een knoop is een beslispunt waarop de weggebruiker een keuze moet maken. |
| Herkomst definitie  | conceptueel model netwerken     |
| Verplicht  | Ja  |
| Gevolgen afbakening||
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een knoop  |Ja |
|Geometrie |De geometrische representatie van een knoop |Ja (punt), Nee (lijn,vlak)|
|Naam|Naam van de knoop zoals opgenomen in besluit openbare ruimte.|Ja (als er een openbare ruimte benoemd is)|
|Status   |De fase van de levenscyclus waarin de betreffende knoop zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij 1 of meer | verbindingen |Ja|

**Domeinwaarden**

<div class='note'>
    In het kader van de review wordt u gevraagd om aan te geven welke levensfasen relevant zijn om als STATUS van een knoop te onderscheiden. 
</div>

|Waarde status	|Beschrijving|
|---|---|
|Gepland	|Een object dat zich in de ontwerpfase bevindt|
|Gesloten	|Een object dat is gerealiseerd maar nog niet in gebruik is genomen|
|In gebruik|	Een object dat in gebruik is genomen |
|Ontoegankelijk|	Een object dat in gebruik is genomen maar tijdelijk niet gebruikt kan worden|
|Opgeheven|	Een object dat buiten gebruik is gesteld|
|Niet gerealiseerd|	Een gepland object dat niet als zodanig is gerealiseerd|
|Ten onrechte	|Een object dat ten onrechte is opgevoerd in de registratie|




#### Wegverbinding
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Wegverbinding|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Wegverbinding  |
|---|---|
| Definitie | Een wegverbinding beschrijft de verkeerskundige inrichting van een weg tussen twee knopen. |
|Herkomst definitie  | conceptueel model netwerken     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een wegverbinding  |Ja |
|Geometrie |De geometrische representatie van een wegverbinding  |Ja (lijn), Nee (vlak)|
|Type wegverbinding||
|Type weg||
|Hoofdverkeersgebruik||
|Naam|Naam van de weg zoals opgenomen in besluit openbare ruimte.|Ja (als er een openbare ruimte benoemd is)|
|Status   |De fase van de levenscyclus waarin de betreffende wegverbinding zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij 2 | knoop |ja|

**Domeinwaarden**

|Waarde type wegverbinding|	Beschrijving|
|---|---|
|Weg	|Beschrijft level detail 0 van een weg|
|Baan	|Beschrijft level detail 1 van een weg|
|Strook|	Beschrijft level detail 2 van een weg|
|Veerverbinding|	Verbijzondering van type wegverbinding|

<div class='note'>
    Wat te doen met wegtypen: verbindingsweg, calamiteitendoorsteek en voetpad op trap
</div>

|Waarde type weg	|Beschrijving|
|---|---|
|Autosnelweg	|Een weg uitsluitend bestemd voor snelverkeer en met gescheiden rijbanen en ongelijkvloerse kruisingen, daartoe aangeduid met het betreffende verkeersbord.|
|Autoweg|Een weg uitsluitend bestemd voor snelverkeer, daartoe aangeduid met het betreffende verkeersbord.|	
|Regionale weg	|Een weg die een verbinding vormt tussen bewoonde oorden of tussen wijken binnen een dorp of stad.|
|Lokale weg	|Een weg van lokaal belang.|
|Fietspad|Een weg met name bestemd voor fietsers en, indien toegestaan, bromfietsers en dat afgescheiden is van de andere wegdelen niet uitsluitend door markering.|	
|Voetpad|Een wegdeel waar voetgangers gebruik van moeten maken.|
|Ruiterpad|Een pad primair aangelegd voor het gebruik door ruiters.|	

.

|Waarde type hoofdverkeersgebruik|Beschrijving|
|---|---|
|Brommers||
|Fietsers||
|Voetgangers||
|Landbouwverkeer||
|Vrachtverkeer||
|Bussen||
|Taxi||
|Personenauto’s|| 

<div class='note'>
    In het kader van de review wordt u gevraagd om aan te geven welke levensfasen relevant zijn om als STATUS wegverbinding te onderscheiden. 
</div>

|Waarde status	|Beschrijving|
|---|---|
|Gepland	|Een object dat zich in de ontwerpfase bevindt|
|Gesloten	|Een object dat is gerealiseerd maar nog niet in gebruik is genomen|
|In gebruik|	Een object dat in gebruik is genomen |
|Ontoegankelijk|	Een object dat in gebruik is genomen maar tijdelijk niet gebruikt kan worden|
|Opgeheven|	Een object dat buiten gebruik is gesteld|
|Niet gerealiseerd|	Een gepland object dat niet als zodanig is gerealiseerd|
|Ten onrechte	|Een object dat ten onrechte is opgevoerd in de registratie|





#### Hyperwegverbinding
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Hyperwegverbinding |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Hyperkant  |
|---|---|
| Definitie | Een hyperwegverbinding is een relatie tussen twee wegobjecten die een functionele samenhang hebben. |
| Herkomst definitie  | conceptueel model netwerken     |
| Verplicht  | Ja  |
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|||

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| verbindt 2 of meer | *objecten* |Ja|

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||


### Transportvoorziening; Spoorweg

### Transportvoorziening; Vaarweg

<div class='note'>
    Is vaarweg wel een apart netwerk? moet varen niet idem als bij wegen als een soort modaliteit aan het waterelementen netwerk worden gekoppeld?
</div>

### Transportvoorziening; Waterelement







### Functionele zonering

<div class='note'>
    De functionele zoneringen zijn voor het overzicht opgedeeld in rode, grijze, groene, blauwe en overige gebieden met een objecttypering. Deze indeling is functioneel ingestoken en heeft geen relatie met het fysieke voorkomen in het terrein.
</div>
 

### Functionele zonering ROOD

#### Verblijfsobject


| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Verblijfsobject  |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Verblijfsobject |
|---|---|
| Definitie | De kleinste binnen één of meer gebouwen gelegen eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is|
|Herkomst definitie|Gebaseerd op definitie “verblijfsobject” in artikel 1 Wet basisregistratie adressen en gebouwen |
|Verplicht  | Ja |
|Gevolgen afbakening  | Het betreft hier in principe de bestaande populatie verblijfsobjecten zoals deze is opgenomen in de basisregistratie adressen en gebouwen |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Verblijfsobject  |Ja |
|Geometrie |De geometrische representatie van een Verblijfsobject  |Ja (2,5D)|
|Gebruiksdoel|Een categorisering van de gebruiksdoelen van het betreffende verblijfsobject zoals in de vergunning is opgenomen of bij constatering is vastgesteld|Ja|
|Feitelijk gebruik|Een categorisering van het feitelijke gebruik dat van het betreffende verblijfsobject wordt gemaakt|Ja|
|Gebruiksoppervlakte|De gebruiksoppervlakte van een verblijfsobject |
|Status   |De fase van de levenscyclus waarin het betreffende verblijfsobject zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij 1 of meer|Gebouw| Ja |
|Heeft een |Nummeraanduiding| Ja |

**Domeinwaarden**

|Waarde gebruiksdoel|	Beschrijving|
|---|---|
|woonfunctie|	Gebruiksfunctie voor het wonen|
|Bijeenkomstfunctie|	Gebruiksfunctie voor het samenkomen van personen voor kunst, cultuur, godsdienst, communicatie, kinderopvang, het verstrekken van consumpties voor het gebruik ter plaatse of het aanschouwen van sport|
|Celfunctie|	Gebruiksfunctie voor dwangverblijf van personen|
|Gezondheidszorgfunctie|	Gebruiksfunctie voor medisch onderzoek, verpleging, verzorging of behandeling|
|Industriefunctie|	Gebruiksfunctie voor het bedrijfsmatig bewerken of opslaan van materialen en goederen, of voor agrarische doeleinden|
|Kantoorfunctie|	Gebruiksfunctie voor administratie|
|Logiesfunctie|	Gebruiksfunctie voor het bieden van recreatief verblijf of tijdelijk onderdak aan personen|
|Onderwijsfunctie|	Gebruiksfunctie voor het geven van onderwijs|
|Sportfunctie|	Gebruiksfunctie voor het beoefenen van sport|
|Winkelfunctie|	Gebruiksfunctie voor het verhandelen van materialen, goederen of diensten|
|Overige gebruiksfunctie|	Andere gebruiksfunctie voor activiteiten waarbij het verblijven van personen een ondergeschikte rol speelt|

<div class='note'>
    De definitieve lijst met gebruiksfuncties zal op een later moment nog worden afgestemd op de begrippen in bijlage I van het besluit bouwwerken leefomgeving (Omgevingswet)
</div>

<div class='note'>
    De definitieve lijst voor FEITELIJK GEBRUIK zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze in het kader van de WOZ zullen worden gehanteerd. Onderstaande domeinwaarden zijn voorbeelden van typeringen zoals deze momenteel bekend zijn en uitsluitend bedoeld om een indruk te geven van het soort waarden dat hier zal worden opgenomen. Ook wordt deze lijst nog afgestemd met begrippen in de BRT.
</div>

| Waarde Feitelijk Gebruik| Beschrijving   |
|---|---|
| vrijstaande woning ||
| 2-onder-1-kapwoning ||
| geschakelde 2-onder-1-kapwoning ||
| geschakelde woning ||
| halfvrijstaande woning ||
| tussenwoning ||
| hoekwoning ||
| eindwoning ||
| galerijflat ||
| portiekflat ||
| corridorflat ||
| maisonnette ||
| benedenwoning ||
| bovenwoning ||
| portiekwoning ||
| (woonwagen/stacaravan) ||
| (woonwagenstandplaats/ stacaravanstandplaats) ||
| (woonboot) ||
| (ligplaats) ||
| waterwoning ||
| tijdelijke woning ||
| woon-/winkelpand ||
| (bouwkavel) ||
| garage ||
| (parkeerplaats) ||
| berging ||
| bijzonder woongebouw ||
| detailhandel ||
| horeca ||
| kantoor ||
| bedrijfsruimte ||
| industrie ||
| agrarisch ||
| laboratorium ||
| onderwijs ||
| cultuur ||
| medisch ||
| overheidsfunctie ||
| nutsvoorzieningen (energie/water) ||
| transport  ||
| sport en recreatie ||
| eredienst ||

.

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een verblijfsobject dat zich in de ontwerpfase bevindt en waarvoor nog geen vergunning tot bouw is verleend|
|Gevormd|	Een verblijfsobject dat deel gaat uitmaken van een nog niet gerealiseerd gebouw waarvoor een vergunning tot bouw is verleend of dat wordt gerealiseerd in een reeds bestaand gebouw|
|In gebruik|	Een verblijfsobject dat in gebruik is genomen of als gebruiksgereed kan worden beschouwd |
|Buiten gebruik	|Een verblijfsobject dat onderdeel uitmaakt van een gebouw dat in dusdanige bouwkundige staat is dat niet te verwachten is dat het gebouw zal worden hersteld en weer in gebruik zal worden genomen|
|Beëindigd|	Een verblijfsobject dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland verblijfsobject dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Verblijfsobject is ten onrechte opgevoerd in de registratie|



#### Gebouwzone

| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Gebouwzone  |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Gebouwzone |
|---|---|
| Definitie | Het grootst mogelijke gedeelte van een gebouw dat in zijn geheel is gelegen op een bouwlaag en binnen de afbakening van een gebouw en een verblijfsobject, waaraan eenduidig een bouwjaar kan worden toegekend, en dat qua constructie en gebruiksmogelijkheden voldoende uniform is|
|Herkomst definitie|Begrip gebaseerd op de functionele deelobjecten uit de WOZ en aansluitend bij het begrip Zonering (IfcZone) uit de concepten rondom Bouwwerkinformatiemodellen (BIM), waarbij Ruimten worden gezoneerd tot bijvoorbeeld verblijfsobject of gebouwzone |
|Verplicht  | Ja |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype |
|Toelichting| *volgt later* |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Gebouwzone  |Ja |
|Geometrie |De geometrische representatie van een Gebouwzone   |Ja (2,5D)|
|Geometrie oppervlakte| De geometrische representatie van de oppervlakte van een gebouwzone die betrokken wordt in de berekening van de gebruiksoppervlakte|Nee (2D)|
|Bouwlaag|De bouwlaag waarop de gebouwzone is gelegen|Ja|
|Bouwjaar|Het bouwjaar waarin een gebouwzone is ontstaan|Ja|
|Type|Een categorisering van het feitelijke gebruik dat van de betreffende gebouwzone wordt gemaakt|Ja|
|Aard|Een aanduiding van de fysieke constructie waarin de gebouwzone zich bevindt|Ja|
|Gebruiksopppervlakte|De gebruiksoppervlakte van een gebouwzone|Ja|
|Kwaliteitsindicatie|Een aanduiding van de kwalitatieve staat waarin de gebouwzone zich bevindt|NTB|
|Status   |De fase van de levenscyclus waarin de betreffende Gebouwzone zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|gebouwzone|Hoort bij |Verblijfsobject|
|gebouwzone|Ligt op |Bouwlaag|

**Domeinwaarden**

<div class='note'>
    De definitieve lijst voor TYPE zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze in het kader van de WOZ zullen worden gehanteerd. Onderstaande domeinwaarden zijn voorbeelden van typeringen zoals deze momenteel bekend zijn en uitsluitend bedoeld om een indruk te geven van het soort waarden dat hier zal worden opgenomen.
</div>


| Waarde Type| Beschrijving   |
|---|---|
|woonruimte  | | 
|garage | | 
|bergruimte | | 
|kantoorruimte | | 
|winkelruimte | | 
|opslagruimte | | 
|praktijkruimte | | 
|ruimte medische zorg | | 
|productieruimte | | 
|bijeenkomstruimte | | 
|verkeersruimte | | 
|technische ruimte | | 

<div class='note'>
    In het kader van de review wordt u gevraagd om aan te geven of er naar uw mening meerdere type gebouwonderdelen relevant zijn om als AARD gebouwzone te onderscheiden
</div>

| Waarde Aard| Beschrijving   |
|---|---|
|basisconstructie |Een gebouwzone maakt onderdeel uit van de oorspronkelijke constructie van het gebouw waarin de gebouwzone is gelegen|
|aanbouw/opbouw |Een gebouwzone betreft een later aanbouw (niet zijnde een serre) of opbouw ten opzichte van de oorspronkelijke constructie van het gebouw waarin de gebouwzone is gelegen|
|serre |Een gebouwzone betreft een serre die al dan geen onderdeel uitmaakt van de oorspronkelijke constructie van het gebouw waarin de gebouwzone is gelegen|

<div class='note'>
    De definitieve lijst voor KWALITEITSINDICATIE zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze lijst aansluit op de begrippen zoals deze in het kader van de WOZ zullen worden gehanteerd. Onderstaande domeinwaarden zijn voorbeelden van typeringen zoals deze momenteel bekend zijn en uitsluitend bedoeld om een indruk te geven van het soort waarden dat hier zal worden opgenomen.
</div>

| Waarde Kwaliteitsindicatie| Beschrijving   |
|---|---|
|  | |

.

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een gebouwzone dat zich in de ontwerpfase bevindt en waarvoor nog geen vergunning tot bouw is verleend|
|Gevormd|	Een gebouwzone dat deel gaat uitmaken van een nog niet gerealiseerd gebouw waarvoor een vergunning tot bouw is verleend of dat wordt gerealiseerd in een reeds bestaand gebouw|
|In gebruik|	Een gebouwzone die in gebruik is genomen of als gebruiksgereed kan worden beschouwd |
|Buiten gebruik|	Een gebouwzone dat onderdeel uitmaakt van een gebouw dat in dusdanige bouwkundige staat is dat niet te verwachten is dat het gebouw zal worden hersteld en weer in gebruik zal worden genomen|
|Beëindigd|	Een gebouwzone dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een geplande gebouwzone dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Gebouwzone is ten onrechte opgevoerd in de registratie|



### Functionele zonering GRIJS

#### Verkeerskundig functionele zone

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Verkeerskundig functionele zone |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Verkeerskundig functionele zone |
|---|---|
| Definitie |  |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende typeringen zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een verkeerskundig functionele zone.  |Ja |
|Geometrie |De geometrische representatie van de randen van een verkeerskundig functionele zone.  |Ja (vlak)|
|Type| |
|Status   |De fase van de levenscyclus waarin de betreffende verkeerskundig functionele zone zich bevindt.   |Ja  |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

<div class='note'>
    Carpoolplaats, Transferium, Verzorgingsplaats, Parkeerplaats alleen opnemen als dit door BRT.next wordt aangegeven
</div>

|Waarde type|	Beschrijving|
|---|---|
| Voetgangersgebied | Wegdeel alleen voor het gebruik door voetgangers, waarbij het door voetgangers te gebruiken gebied de volle breedte van de weg beslaat en het gebied een nadrukkelijk openbaar karakter heeft. |
| Inrit||
| Woonerf | Wegdeel waar de verblijfsfunctie (lopen, spelen, ontmoeten enzovoorts) prioriteit heeft boven de verkeersfunctie. |
| Parkeervlak | Wegdeel bestemd voor het parkeren van motorvoertuigen. |
|Herkomst definitie  | BGT 1.1.1 |
| Carpoolplaats | Parkeerplaats die qua ligging en ontsluiting geschikt is voor carpooling. |
| Transferium | Voorziening voor het overstappen tussen vervoersmodaliteiten, die zodanig is gesitueerd en ingericht dat een verplaatsing met meerdere vervoersmodaliteiten aantrekkelijker is dan dezelfde verplaatsing met de auto. |
| Verzorgingsplaats |  Langs de weg gelegen parkeergelegenheid, met inbegrip van de daarbij behorende verharde en onverharde banen en een of meer voorzieningen ten behoeve van reizigers en/of voertuigen. |
| OV-baan |  Wegdeel dat uitsluitend is bestemd en gemarkeerd voor openbaar vervoer en afgescheiden is van de andere wegdelen.|
| Parkeerplaats |  Parkeergelegenheid voor meerdere voertuigen in de openlucht.|
| Benzinestation |  Geheel van installaties, verharding en opstallen waar brandstoffen ten behoeve van verbrandingsmotoren worden verkocht.|
| Snellaadstation |  Infrastructuurelement, doorgaans langs autosnelwegen, dat in elektrische energie voorziet om elektrische plug-invoertuigen op te laden in een relatief korte tijd. |
| Zone |  Verkeerskundige afbakening van een gebied. |

.

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een verkeerskundig functionele zone die zich in de ontwerpfase bevindt. |
|Gevormd|	Een verkeerskundig functionele zone die is gerealiseerd.|
|Beëindigd|	Een verkeerskundig functionele zone die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande verkeerskundig functionele zone die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een verkeerskundig functionele zone die ten onrechte is opgevoerd in de registratie.|

#### Spoorzone
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Spoorzone |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Spoorzone |
|---|---|
| Definitie |   |
|Herkomst definitie  ||
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type spoorzone zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een spoorzone.  |Ja |
|Geometrie |De geometrische representatie van de randen van een spoorzone.  |Ja (vlak) |
|Type||
|Status   |De fase van de levenscyclus waarin het betreffende spoorzone zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een spoorzone die zich in de ontwerpfase bevindt. |
|Gevormd|	Een spoorzone die is gerealiseerd.|
|Beëindigd|	Een spoorzone die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande spoorzone die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een spoorzone die ten onrechte is opgevoerd in de registratie.|

.

| Waarde status	|Beschrijving|
|---|---|
| Perron |  Verhoogde constructie langs een spoorrail of tramrail voor het in- en uitstappen van passagiers of voor het laden en lossen van goederen. |
| Overweg | Een gelijkvloerse kruising van een weg met een spoor type trein of sneltram. |
| Spoorbaan | Gebaand gedeelte voor het verkeer over rails. |
| Emplacement | Het totaal aan sporen op een terrein ten behoeve van het rangeren en stallen van treinen. |

<div class='note'>
    Emplacement alleen opnemen als dit door BRT.next wordt aangegeven 
</div>

#### Wegzone

#### Wegzone
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Wegzone |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Wegzone  |
|---|---|
| Definitie |   |
|Herkomst definitie  |  |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een wegzone.  |Ja |
|Geometrie |De geometrische representatie van een wegzone.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende wegzone zich bevindt .  |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**


|Gepland|	Een wegzone die zich in de ontwerpfase bevindt |
|Gevormd|	Een wegzone die is gerealiseerd|
|Beëindigd|	Een wegzone die als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een geplande wegzone die niet als zodanig is gerealiseerd|
|Ten onrechte|	Een wegzone die ten onrechte is opgevoerd in de registratie|

<div class='note'>
    Niet alle type wegzones verplicht maken
</div>

|Waarde type	|Beschrijving|
|---|---|
| Verkeerseiland | Weggedeelte van beperkte omvang, uitgevoerd als een verhoging of wegmarkering, dat wordt omsloten door rijbanen of rijstroken en als doel heeft verkeersstromen te scheiden.  |
| Berm | Een strook grond langs een weg of spoorweg. |
| Halteplaats | Het geheel van voorzieningen bedoeld als stopplaats voor voertuigen van het openbaar vervoer. |
| Laadplein | Een laadplein bestaat uit meer dan twee laadpunten voor elektrische voertuigen die niet afzonderlijk op het net zijn aangesloten en samen één aansluiting hebben. |
| Verkeersdrempel | Verhoging in een regionale rijbaan, bedoeld om het gemotoriseerde verkeer met een lage snelheid te laten rijden.| 
| Molgoot | Smalle goot in de lengterichting van de verharding, met veelal een cirkelsegment als dwarsprofiel. |
| Wildrooster | Horizontaal raamwerk dat dient om wild de doorgang te beletten.   |

<div class='note'>
    Wildrooster of Rooster. Rooster is algemener. Rooster kan dan ook een fysiek verhardingstype zijn.
</div>

#### Luchtvaartzone
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Luchtvaartzone |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Luchtvaartzone |
|---|---|
| Definitie |   |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een luchtvaartzone.  |Ja |
|Geometrie |De geometrische representatie van een luchtvaartzone. |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende luchtvaartzone zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een luchtvaartzone die zich in de ontwerpfase bevindt |
|Gevormd|	Een luchtvaartzone die is gerealiseerd|
|Beëindigd|	Een luchtvaartzone die als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een geplande luchtvaartzone die niet als zodanig is gerealiseerd|
|Ten onrechte|	Een luchtvaartzone die ten onrechte is opgevoerd in de registratie|

.

|Waarde type	|Beschrijving|
|---|---|
| Baan voor vliegverkeer | Wegdeel uitsluitend bedoeld voor vliegverkeer.  |
| Luchthaven | Vliegveld voor verkeersvliegtuigen met groot, effen terrein met al dan niet verharde banen, waar vliegtuigen kunnen opstijgen en landen, eventueel met accomodatie voor ontvangst en vertrek van passagiers en verzending van goederen.  |

<div class='note'>
    Luchthaven alleen opnemen als dit door BRT.next wordt aangegeven
</div>








### Functionele zonering GROEN


#### Strand
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Strand |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Strand |
|---|---|
| Definitie | Onbegroeide zandige kustvlakte op de overgang van zee met land. Staat onder invloed van het zeewater en de wind. |
|Herkomst definitie  | IMGeo 2.1.1 |
|Verplicht  | Ja  |
|Toelichting|  |

#### Zandverstuiving

#### Begraafplaats
.
#### Speeltuin
|Naam| 	speeltuin|

#### Park
|Naam| 	park|

#### Sportterrein
|Naam| 	sportterrein|

#### Camping
|Naam| 	camping|

#### Bungalowpark
|Naam| 	bungalowpark|

#### Volkstuin
|Naam| 	volkstuin|  



### Functionele zonering BLAUW

<div class='note'>
    De nu in de basisregistratie opgenomen typeringen die nog geen plaats hebben gekregen in de SOR: 
</div>
 

|Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|Functioneel Gebied (blauw)|	Functie:	 ||
||*Niet BGT*| 	 	Opstelpunt open water|
||*Niet BGT*| 	 	Zuiveringscomplex|
||*Niet BGT*| 	 	Waterwingebied|
||*Niet BGT*|	 	Waterbergingsgebied|
||*Niet BGT*|	 	Infrastructuur waterstaatswerken|  


#### Kering
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Kering|
| Onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 

**Definitie**

| Naam  | Kering |
|---|---|
| Definitie | Voorziening met kerende functie. |
|Herkomst definitie  |nieuw|
|Verplicht  | ja  |
|Gevolgen afbakening||
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip kering|Ja |
|Geometrie||nee (lijn)|
|type kering|||
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||

.

|Waarde type kering| Beschrijving   |Herkomst|
|---|---|---|
|grond	|voorziening bedoeld om grond te keren|	nieuw|
|water	|voorziening bedoeld om water te keren|	nieuw|


#### Oever,slootkant
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Oever,slootkant |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Oever,slootkant  |
|---|---|
| Definitie | *De strook land die in direct contact staat met water, inclusief het gebied tussen de hoogwaterlijn en laagwaterlijn. (bron: Inspire)*  |
|Herkomst definitie  | BGT 1.1.1.     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip oever,slootkant|Ja |
|Geometrie||nee (lijn)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||

#### Complex
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Complex |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Complex  |
|---|---|
| Definitie |   |
|Herkomst definitie  |     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip complex|Ja |
|Geometrie||nee (vlak)|
|Type complex|||
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||

. 

|Waarde Type complex| Beschrijving   |
|---|---|
|||
|havencomplex||
|gemaalcomplex||
|sluiscomplex||
|stuwcomplex||
|coupurecomplex||


#### Vuilvang
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Vuilvang |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

<div class='note'>
    Is vuilvang een functie of een kunstwerk? (IMBOR zegt kunstwerk)
</div>



ontwerpprincipe: 

**Definitie**

| Naam  | Vuilvang  |
|---|---|
| Definitie |   |
|Herkomst definitie  |     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip vuilvang|Ja |
|Geometrie||nee (vlak)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||




### Functionele zonering OVERIG
#### Reducering

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | reducering|
| Onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 

**Definitie**

| Naam  | Reducering |
|---|---|
| Definitie |voorziening om bepaalde effecten van omgevingsfactoren te verminderen|
|Herkomst definitie  |nieuw|
|Verplicht  | ja  |
|Gevolgen afbakening||
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip reducering|Ja |
|Geometrie||nee (lijn)|
|type reducering|||
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**
|Waarde Status| Beschrijving   |
|---|---|
|||

. 

|Waarde Type reducering| Beschrijving   |Herkomst|
|---|---|---|
|geluid|	voorziening bedoeld om geluidshinder in de buitenlucht te verminderen|	nieuw|
|fijnstof|	voorziening bedoeld om verspreiding van fijnstof te verminderen	|nieuw|


#### Valbescherming
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Valbescherming|
| Onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 

**Definitie**

| Naam  | Valbescherming |
|---|---|
| Definitie |Voorziening om vallen te voorkomen|
|Herkomst definitie  |nieuw|
|Verplicht  | nee  |
|Gevolgen afbakening||
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip valbescherming|Ja |
|Geometrie||nee (lijn)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||


#### Afscheiding 
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Afscheiding |
| Onderdeel van NEN3610-objecttype | Functioneel object |

ontwerpprincipe: 


**Definitie**

| Naam  | Afscheiding |
|---|---|
| Definitie |Voorziening om terrein af te scheiden.|
|Herkomst definitie  |nieuw|
|Verplicht  | nee  |
|Gevolgen afbakening||
|Toelichting| *volgt later*  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip afscheiding|Ja |
|Geometrie||nee (lijn)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde Status| Beschrijving   |
|---|---|
|||





