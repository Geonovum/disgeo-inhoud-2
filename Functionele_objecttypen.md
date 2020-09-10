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

### Inrit





### Functionele zonering
| Klasse  | Naam  |
|---|---|
|SOR-begrip   | Functionele zonering |
| Onderdeel van NEN3610-objecttype |Functioneel object  |


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

#### VERKEER


#### Voetgangersgebied
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Voetgangersgebied |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Voetgangersgebied |
|---|---|
| Definitie | Wegdeel alleen voor het gebruik door voetgangers, waarbij het door voetgangers te gebruiken gebied de volle breedte van de weg beslaat en het gebied een nadrukkelijk openbaar karakter heeft. |
|Herkomst definitie  | BGT 1.1.1. |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *voetgangersgebied* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een voetgangersgebied.  |Ja |
|Geometrie |De geometrische representatie van de randen van een voetgangersgebied.  |Ja (vlak)|
|Status   |De fase van de levenscyclus waarin het betreffende voetgangersgebied zich bevindt.   |Ja  |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een voetgangersgebied dat zich in de ontwerpfase bevindt. |
|Gevormd|	Een voetgangersgebied dat is gerealiseerd.|
|Beëindigd|	Een voetgangersgebied dat als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een gepland voetgangersgebied dat niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een voetgangersgebied dat ten onrechte is opgevoerd in de registratie.|


#### Woonerf
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Woonerf |
| Onderdeel van NEN3610-objecttype | Functioneel object  |


**Definitie**

| Naam  | Woonerf |
|---|---|
| Definitie | Wegdeel waar de verblijfsfunctie (lopen, spelen, ontmoeten enzovoorts) prioriteit heeft boven de verkeersfunctie. |
|Herkomst definitie  | BGT 1.1.1. |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *woonerf* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een woonerf.  |Ja |
|Geometrie |De geometrische representatie van de randen van een woonerf.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende woonerf zich bevindt.  |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een woonerf dat zich in de ontwerpfase bevindt. |
|Gevormd|	Een woonerf dat is gerealiseerd.|
|Beëindigd|	Een woonerf dat als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een gepland woonerf dat niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een woonerf dat ten onrechte is opgevoerd in de registratie.|



#### Parkeervlak
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Parkeervlak |
| Onderdeel van NEN3610-objecttype | Functioneel object  |


**Definitie**

| Naam  | Parkeervlak |
|---|---|
| Definitie | Wegdeel bestemd voor het parkeren van motorvoertuigen. |
|Herkomst definitie  | BGT 1.1.1 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *parkeervlak* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een parkeervlak.  |Ja |
|Geometrie |De geometrische representatie van de randen van een parkeervlak.  |Ja (vlak)|
|Status   |De fase van de levenscyclus waarin het betreffende parkeervlak zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een parkeervlak dat zich in de ontwerpfase bevindt. |
|Gevormd|	Een parkeervlak dat is gerealiseerd.|
|Beëindigd|	Een parkeervlak dat als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een gepland parkeervlak dat niet als zodanig is gerealiseerd.|
|Ten onrechte|	Parkeervlak is ten onrechte opgevoerd in de registratie.|


#### Carpoolplaats
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Carpoolplaats |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven
</div>

**Definitie**

| Naam  | Carpoolplaats |
|---|---|
| Definitie | Parkeerplaats die qua ligging en ontsluiting geschikt is voor carpooling. |
|Herkomst definitie  | IMGeo 2.2|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *carpoolplaats* zoals deze is opgenomen in de basisregistratie grootschalige topografie gecombineerd met de bestaande populatie *carpoolplaats* zoals deze is opgenomen in de basisregistratie topografie. |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een carpoolplaats.  |Ja |
|Geometrie |De geometrische representatie van de randen van een carpoolplaats.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende carpoolplaats zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een carpoolplaats die zich in de ontwerpfase bevindt. |
|Gevormd|	Een carpoolplaats die is gerealiseerd.|
|Beëindigd|	Een carpoolplaats die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande carpoolplaats die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een carpoolplaats die ten onrechte is opgevoerd in de registratie.|

#### Transferium
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Transferium |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven
</div>

**Definitie**

| Naam  | Transferium |
|---|---|
| Definitie | Voorziening voor het overstappen tussen vervoersmodaliteiten, die zodanig is gesitueerd en ingericht dat een verplaatsing met meerdere vervoersmodaliteiten aantrekkelijker is dan dezelfde verplaatsing met de auto. |
|Herkomst definitie  | IMBOR 2020 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie *P+R parkeerplaats* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een transferium.  |Ja |
|Geometrie |De geometrische representatie van de randen van een transferium. |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende transferium zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een transferium dat zich in de ontwerpfase bevindt. |
|Gevormd|	Een transferium dat is gerealiseerd.|
|Beëindigd|	Een transferium dat als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een gepland transferium dat niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een transferium dat ten onrechte is opgevoerd in de registratie.|



#### Verzorgingsplaats
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Verzorgingsplaats |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven
</div>

**Definitie**

| Naam  | Verzorgingsplaats |
|---|---|
| Definitie |  Langs de weg gelegen parkeergelegenheid, met inbegrip van de daarbij behorende verharde en onverharde banen en een of meer voorzieningen ten behoeve van reizigers en/of voertuigen. |
|Herkomst definitie  | IMGeo 2.2 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *verzorgingsplaats* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een verzorgingsplaats.  |Ja |
|Geometrie |De geometrische representatie van de randen van een verzorgingsplaats.  |Ja (vlak)|
|Status   |De fase van de levenscyclus waarin het betreffende verzorgingsplaats zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een verzorgingsplaats die zich in de ontwerpfase bevindt. |
|Gevormd|	Een verzorgingsplaats die is gerealiseerd.|
|Beëindigd|	Een verzorgingsplaats die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande verzorgingsplaats die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een verzorgingsplaats die ten onrechte is opgevoerd in de registratie.|

#### OV-baan
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | OV-baan |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | OV-baan |
|---|---|
| Definitie |  Wegdeel dat uitsluitend is bestemd en gemarkeerd voor openbaar vervoer en afgescheiden is van de andere wegdelen.|
|Herkomst definitie  | Gebaseerd op de definitie OV-baan in de gegevenscatalogus BGT 1.1.1 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *OV-baan* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een OV-baan.  |Ja |
|Geometrie |De geometrische representatie van de randen van een OV-baan.  |Ja (vlak)|
|Status   |De fase van de levenscyclus waarin het betreffende OV-baan zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een OV-baan die zich in de ontwerpfase bevindt. |
|Gevormd|	Een OV-baan die is gerealiseerd.|
|Beëindigd|	Een OV-baan die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande OV-baan die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een OV-baan die ten onrechte is opgevoerd in de registratie.|

#### Parkeerplaats
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Parkeerplaats |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven / of gewenst is voor het wegennetwerk
</div>

**Definitie**

| Naam  | Parkeerplaats |
|---|---|
| Definitie |  Parkeergelegenheid voor meerdere voertuigen in de openlucht.|
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)   |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Parkeerplaats* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Parkeerplaats.  |Ja |
|Geometrie |De geometrische representatie van de randen van een Parkeerplaats.  |Ja (vlak)|
|Status   |De fase van de levenscyclus waarin het betreffende Parkeerplaats zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een Parkeerplaats die zich in de ontwerpfase bevindt. |
|Gevormd|	Een Parkeerplaats die is gerealiseerd.|
|Beëindigd|	Een Parkeerplaats die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande Parkeerplaats die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een Parkeerplaats die ten onrechte is opgevoerd in de registratie.|

#### Benzinestation
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Benzinestation |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Benzinestation |
|---|---|
| Definitie |  Geheel van installaties, verharding en opstallen waar brandstoffen ten behoeve van verbrandingsmotoren worden verkocht.|
|Herkomst definitie  | IMGeo 2.2 |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *benzinestation* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een benzinestation.  |Ja |
|Geometrie |De geometrische representatie van de randen van een benzinestation.  |Ja (vlak)|
|Status   |De fase van de levenscyclus waarin het betreffende benzinestation zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een benzinestation dat zich in de ontwerpfase bevindt. |
|Gevormd|	Een benzinestation dat is gerealiseerd.|
|Beëindigd|	Een benzinestation dat als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande benzinestation dat niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een benzinestation dat ten onrechte is opgevoerd in de registratie.|

#### Snellaadstation
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Snellaadstation |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Snellaadstation |
|---|---|
| Definitie |  Infrastructuurelement, doorgaans langs autosnelwegen, dat in elektrische energie voorziet om elektrische plug-invoertuigen op te laden in een relatief korte tijd. |
|Herkomst definitie  | IMBOR 2020 |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een nieuw objecttype.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een snellaadstation.  |Ja |
|Geometrie |De geometrische representatie van de randen van een snellaadstation.  |Ja (vlak)|
|Status   |De fase van de levenscyclus waarin het betreffende snellaadstation zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een snellaadstation dat zich in de ontwerpfase bevindt. |
|Gevormd|	Een snellaadstation dat is gerealiseerd.|
|Beëindigd|	Een snellaadstation dat als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een gepland snellaadstation dat niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een snellaadstation dat ten onrechte is opgevoerd in de registratie.|

#### Zone
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Zone |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Zone |
|---|---|
| Definitie |  Verkeerskundige afbakening van een gebied. |
|Herkomst definitie  | IMBOR 2020 |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een nieuw objecttype. |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een zone.  |Ja |
|Geometrie |De geometrische representatie van de randen van een zone.  |Ja (vlak)|
|Status   |De fase van de levenscyclus waarin het betreffende zone zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een zone die zich in de ontwerpfase bevindt. |
|Gevormd|	Een zone die is gerealiseerd.|
|Beëindigd|	Een zone die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande zone die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een zone die ten onrechte is opgevoerd in de registratie.|


#### SPOOR

#### Perron
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Perron |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Perron |
|---|---|
| Definitie |  Verhoogde constructie langs een spoorrail of tramrail voor het in- en uitstappen van passagiers of voor het laden en lossen van goederen. |
|Herkomst definitie  |BGT 1.1.1 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *perron* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een perron.  |Ja |
|Geometrie |De geometrische representatie van de randen van een perron.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende perron zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een perron dat zich in de ontwerpfase bevindt. |
|Gevormd|	Een perron dat is gerealiseerd.|
|Beëindigd|	Een perron dat als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een gepland perron dat niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een perron dat ten onrechte is opgevoerd in de registratie.|

#### Overweg
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Overweg |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Overweg |
|---|---|
| Definitie | Een gelijkvloerse kruising van een weg met een spoor type trein of sneltram. |
|Herkomst definitie  | Gebaseerd op de definitie van overweg in de gegevenscatalogus BGT 1.1.1|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *overweg* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een overweg.  |Ja |
|Geometrie |De geometrische representatie van randen van een overweg.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende overweg zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een overweg die zich in de ontwerpfase bevindt. |
|Gevormd|	Een overweg die is gerealiseerd.|
|Beëindigd|	Een overweg die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande overweg die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een overweg die ten onrechte is opgevoerd in de registratie.|

#### Spoorbaan
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Spoorbaan |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Spoorbaan |
|---|---|
| Definitie | Gebaand gedeelte voor het verkeer over rails. |
|Herkomst definitie  | BGT 1.1.1 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *spoorbaan* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een spoorbaan.  |Ja |
|Geometrie |De geometrische representatie van randen van een spoorbaan.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende spoorbaan zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een spoorbaan die zich in de ontwerpfase bevindt. |
|Gevormd|	Een spoorbaan die is gerealiseerd.|
|Beëindigd|	Een spoorbaan die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande spoorbaan die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een spoorbaan die ten onrechte is opgevoerd in de registratie.|

#### Emplacement
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Emplacement |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven 
</div>

**Definitie**

| Naam  | Emplacement |
|---|---|
| Definitie | Het totaal aan sporen op een terrein ten behoeve van het rangeren en stallen van treinen. |
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *emplacement* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een emplacement.  |Ja |
|Geometrie |De geometrische representatie van randen van een emplacement.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende emplacement zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een emplacement die zich in de ontwerpfase bevindt. |
|Gevormd|	Een emplacement die is gerealiseerd.|
|Beëindigd|	Een emplacement die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande emplacement die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een emplacement die ten onrechte is opgevoerd in de registratie.|




#### WEGINRICHTING

#### Verkeerseiland
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Verkeerseiland |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Verkeerseiland  |
|---|---|
| Definitie | Weggedeelte van beperkte omvang, uitgevoerd als een verhoging of wegmarkering, dat wordt omsloten door rijbanen of rijstroken en als doel heeft verkeersstromen te scheiden.  |
|Herkomst definitie  | IMBOR2020-1 |
|Verplicht  | Ja  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een verkeerseiland  |Ja |
|Geometrie |De geometrische representatie van een verkeerseiland  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende verkeerseiland zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een verkeerseiland dat zich in de ontwerpfase bevindt |
|Gevormd|	Een verkeerseiland dat is gerealiseerd|
|Beëindigd|	Een verkeerseiland dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland verkeerseiland dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Verkeerseiland is ten onrechte opgevoerd in de registratie|


#### Berm
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Berm |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    definitie afstemmen tussen werkgroep GRIJS en GROEN
</div>


**Definitie**

| Naam  | Berm |
|---|---|
| Definitie | Een strook grond langs een weg of spoorweg. |
|Herkomst definitie  | BGT 1.1.1. |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *berm* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een berm  |Ja |
|Geometrie |De geometrische representatie van een berm  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende berm zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een berm die zich in de ontwerpfase bevindt. |
|Gevormd|	Een berm die is gerealiseerd.|
|Beëindigd|	Een berm die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande berm die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een berm die ten onrechte is opgevoerd in de registratie.|

#### Halteplaats
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Halteplaats |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Halteplaats |
|---|---|
| Definitie | Het geheel van voorzieningen bedoeld als stopplaats voor voertuigen van het openbaar vervoer. |
|Herkomst definitie  | IMBOR 2020 |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie *bushalte* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een halteplaats.  |Ja |
|Geometrie |De geometrische representatie van randen van een halteplaats.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende halteplaats zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een halteplaats die zich in de ontwerpfase bevindt. |
|Gevormd|	Een halteplaats die is gerealiseerd.|
|Beëindigd|	Een halteplaats die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande halteplaats die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een halteplaats die ten onrechte is opgevoerd in de registratie.|

#### Laadplein
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Laadplein |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Laadplein |
|---|---|
| Definitie | Een laadplein bestaat uit meer dan twee laadpunten voor elektrische voertuigen die niet afzonderlijk op het net zijn aangesloten en samen één aansluiting hebben. |
|Herkomst definitie  | IMBOR 2020 |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier een nieuw objecttype. |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een laadplein.  |Ja |
|Geometrie |De geometrische representatie van randen van een laadplein.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende laadplein zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een laadplein die zich in de ontwerpfase bevindt. |
|Gevormd|	Een laadplein die is gerealiseerd.|
|Beëindigd|	Een laadplein die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande laadplein die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een laadplein die ten onrechte is opgevoerd in de registratie.|

#### Verkeersdrempel
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Verkeersdrempel |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Verkeersdrempel |
|---|---|
| Definitie | Verhoging in een regionale rijbaan, bedoeld om het gemotoriseerde verkeer met een lage snelheid te laten rijden.| verplicht |
|Herkomst definitie  | IMGeo 2.2 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *verkeersdrempel* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een verkeersdrempel.  |Ja |
|Geometrie |De geometrische representatie van randen van een verkeersdrempel.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende verkeersdrempel zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een verkeersdrempel die zich in de ontwerpfase bevindt. |
|Gevormd|	Een verkeersdrempel die is gerealiseerd.|
|Beëindigd|	Een verkeersdrempel die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande verkeersdrempel die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een verkeersdrempel die ten onrechte is opgevoerd in de registratie.|

#### Molgoot
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Molgoot |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Molgoot |
|---|---|
| Definitie | Smalle goot in de lengterichting van de verharding, met veelal een cirkelsegment als dwarsprofiel. |
|Herkomst definitie  | IMGeo 2.2 |
|Verplicht  | Nee  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *molgoot* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een molgoot.  |Ja |
|Geometrie |De geometrische representatie van randen van een molgoot.  |Ja (vlak) |
|Status   |De fase van de levenscyclus waarin het betreffende molgoot zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een molgoot die zich in de ontwerpfase bevindt. |
|Gevormd|	Een molgoot die is gerealiseerd.|
|Beëindigd|	Een molgoot die als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande molgoot die niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een molgoot die ten onrechte is opgevoerd in de registratie.|





#### Wildrooster
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Wildrooster |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

<div class='note'>
    Wildrooster of Rooster. Rooster is algemener. Rooster kan dan ook een fysiek verhardingstype zijn.
</div>

ontwerpprincipe: 

**Definitie**

| Naam  | Wildrooster  |
|---|---|
| Definitie | Horizontaal raamwerk dat dient om wild de doorgang te beletten.   |
|Herkomst definitie  |  IMGeo 2.2   |
|Verplicht  | Nee  |
|Gevolgen afbakening|Het betreft hier de bestaande populatie *wildrooster* zoals deze is opgenomen in de basisregistratie grootschalige topografie.|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip wildrooster|Ja |
|Geometrie|De geometrische representatie van randen van een wildrooster.|ja (vlak)|
|Status   |   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|||

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een wildrooster dat zich in de ontwerpfase bevindt. |
|Gevormd|	Een wildrooster dat is gerealiseerd.|
|Beëindigd|	Een wildrooster dat als zodanig opgehouden heeft te bestaan.|
|Niet gerealiseerd|	Een geplande wildrooster dat niet als zodanig is gerealiseerd.|
|Ten onrechte|	Een wildrooster dat ten onrechte is opgevoerd in de registratie.|


#### LUCHTVAART

#### Baan voor vliegverkeer
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Baan voor vliegverkeer |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Baan voor vliegverkeer |
|---|---|
| Definitie | Wegdeel uitsluitend bedoeld voor vliegverkeer.  |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een baan voor vliegverkeer  |Ja |
|Geometrie |De geometrische representatie van een baan voor vliegverkeer  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende baan voor vliegverkeer zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een baan voor vliegverkeer dat zich in de ontwerpfase bevindt |
|Gevormd|	Een baan voor vliegverkeer dat is gerealiseerd|
|Beëindigd|	Een baan voor vliegverkeer dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland baan voor vliegverkeer dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Baan voor vliegverkeer is ten onrechte opgevoerd in de registratie|


#### Luchthaven
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Luchthaven |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

<div class='note'>
    alleen opnemen als dit door BRT.next wordt aangegeven
</div>

**Definitie**

| Naam  | Luchthaven |
|---|---|
| Definitie | Vliegveld voor verkeersvliegtuigen met groot, effen terrein met al dan niet verharde banen, waar vliegtuigen kunnen opstijgen en landen, eventueel met accomodatie voor ontvangst en vertrek van passagiers en verzending van goederen.  |
|Herkomst definitie  | |
|Verplicht  | Ja  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een luchthaven  |Ja |
|Geometrie |De geometrische representatie van een luchthaven  |Ja |
|Status   |De fase van de levenscyclus waarin het betreffende luchthaven zich bevindt   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|

**Domeinwaarden**

|Waarde status	|Beschrijving|
|---|---|
|Gepland|	Een luchthaven dat zich in de ontwerpfase bevindt |
|Gevormd|	Een luchthaven dat is gerealiseerd|
|Beëindigd|	Een luchthaven dat als zodanig opgehouden heeft te bestaan|
|Niet gerealiseerd|	Een gepland luchthaven dat niet als zodanig is gerealiseerd|
|Ten onrechte|	Luchthaven is ten onrechte opgevoerd in de registratie|






### Functionele zonering GROEN

<div class='note'>
    De nu in de basisregistratie opgenomen typeringen die nog geen plaats hebben gekregen in de SOR: 
</div>


|Objecttype |classificatie (verplicht)	| Plus classificatie (vrijwillig)|
|-----------|---------------------------|--------------------------------|
|Functioneel Gebied (groen)|	Functie:	 ||
||*Niet BGT*| 	 	Landbouw|
||*Niet BGT*| 	 	recreatie: speeltuin|
||*Niet BGT*| 	 	recreatie: park|
||*Niet BGT*| 	 	recreatie: sportterrein|
||*Niet BGT*| 	 	recreatie: camping|
||*Niet BGT*| 	 	recreatie: bungalowpark|
||*Niet BGT*| 	 	recreatie: volkstuin|  

#### Strand
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Strand |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

ontwerpprincipe: 

**Definitie**

| Naam  | Strand |
|---|---|
| Definitie | Onbegroeide zandige kustvlakte op de overgang van zee met land. Staat onder invloed van het zeewater en de wind. |
|Herkomst definitie  | IMGeo 2.1.1 |
|Verplicht  | Ja  |
|Toelichting|  |



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





