## Functionele objecttypen

### Transportvoorzieningen

#### Weg

**KNOOP**

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Knoop|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Knoop  |
|---|---|
| Definitie | Een knoop is een begin-, eind- of keuzepunt voor de weggebruiker. |
| Herkomst definitie  | conceptueel model netwerken     |
| Verplicht  | Ja  |
| Gevolgen afbakening||
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een knoop  |Ja |
|Geometrie |De geometrische representatie van een knoop |Ja (punt), Nee (vlak)|
|Naam|Naam van de knoop zoals opgenomen in besluit openbare ruimte.|Ja (als er een openbare ruimte benoemd is) (LR)|
|Type verkeersgebied|Een deel van de weg met een specifieke functie om van richting te veranderen of de reis te beginnen/eindigen.|Ja|
|Hoofdverkeersgebruik|Hoofdverkeersgebruiker is het meest voorkomende verkeer dat zich over de knoop verplaatst.|Ja|
|Status   |De fase van de levenscyclus waarin de betreffende knoop zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| ligt aan 1 of meer | gerelateerde wegverbinding(en) |Ja|
| heeft 1 | openbare ruimte | Ja (als er een openbare ruimte benoemd is) (LR) |
| ligt op | gerelateerde reële object | Ja|

**Domeinwaarden**

|Waarde Type verkeersgebied|Beschrijving|
|---|---|
|kruising||
|rotonde||
|knooppunt||
|inrit||
|uitrit||
|transferium||

.

|Waarde Hoofdverkeersgebruik|Beschrijving|
|---|---|
|Snelverkeer|	Motorvoertuigen die geen snelheidsbeperking hebben inclusief vrachtwagens.|
|Langzaam verkeer|	Motorvoertuigen die snelheidsbeperking hebben zoals landbouwvoertuigen, fietsers, voetgangers.|
|Gemengd verkeer|	Verschillende hoofdverkeersgebruikers zijn toegestaan om de knoop.|
|Busverkeer|	Voertuig ingericht voor het vervoer van personen, met meer dan acht zitplaatsen, de bestuurderszitplaats niet meegerekend, niet zijnde een motorrijtuig met beperkte snelheid of gehandicaptenvoertuig.|
|Fietsers| bromfietsers	Bestuurders die met een fiets of bromfiets aan het verkeer deelnemen.|
|Voetgangers|	Een persoon die te voet deelneemt aan het verkeer.|
|Ruiters|	Bestuurder van een paard of pony. |


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|In gebruik|	
|Buiten gebruik|	
|Beëindigd|	
|Niet gerealiseerd|	
|Ten onrechte	|

**WEGVERBINDING**

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Wegverbinding|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

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
|Type wegverbinding||Ja|
|Type weg| Een categorisering van de verschillende wegtypes. |Ja|
|Modaliteit| Soorten voertuigen die zich op de verbinding mogen begeven. | Ja (MV)|
|Openbare weg|Weg die door iedereen gebruikt kan worden. | Ja|
|Hoofdverkeersgebruik|Hoofdverkeersgebruiker is het meest voorkomende verkeer dat zich over de wegverbinding verplaatst.|Ja|
|Naam|Naam van de weg zoals opgenomen in besluit openbare ruimte.|Ja (als er een openbare ruimte benoemd is)(LR)|
|Status   |De fase van de levenscyclus waarin de betreffende wegverbinding zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij 2 | knoop |ja|
| heeft een | openbare ruimte | ja (als er een openbare ruimte benoemd is)(LR) |
| ligt op | verharding| ja|

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

*type weg*

|Waarde type weg	|Beschrijving|
|---|---|
|Autosnelweg|	Conflict vrije weg bestemd voor snel gemotoriseerd verkeer.|Minimaal 2 rijbanen met 2 of meer rijtroken. Rijbanen fysiek van elkaar gescheiden.|
|Autoweg	|Weg die alleen voor snel gemotoriseerd (min 50km/uur) verkeer toegankelijk is.|
|Gebiedsontsluitingsweg gesloten|	Verbindt een auto(snel)weg met een erftoegangsweg waar geen land- en bosbouwverkeer is toegestaan.|
|Gebiedsontsluitingsweg open|	Verbindt een auto(snel)weg met een erftoegangsweg waar wel land- en bosbouwverkeer is toegestaan.|
|Erftoegangsweg|	Wegen met gemengd langzaam verkeer en gemotoriseerd verkeer, zonder rijrichtingscheiding en meestal zonder gescheiden fietspaden.|
|Fietsstraat|	Een straat die ingericht is als fietsroute waar auto’s zijn toegestaan. |
|Fiets/bromfietspad|	Pad dat voor zowel bromfietsers als fietsers verplicht is. |
|Fietspad|	een weggedeelte of vrij liggend pad dat is gereserveerd voor het fietsverkeer en snorfietsen.|
|Voetpad|	Deel van verkeersinfrastructuur dat uitsluitend bedoeld is voor voetgangers verkeer.|
|Overige wegen|	Wegen die niet onder een van bovenstaande typen vallen.| 

|Ruiterpad|Een pad primair aangelegd voor het gebruik door ruiters.|


*type hoofdverkeersgebruik*

|Waarde type hoofdverkeersgebruik|Beschrijving|
|---|---|
|Vrachtverkeer|	Motorvoertuig, niet ingericht voor het vervoer van personen, waarvan de toegestane maximum massa meer bedraagt dan 3500 kg.|
|Snelverkeer|	Motorvoertuigen die geen snelheidsbeperking hebben inclusief vrachtwagens.|
|Langzaam verkeer|	Motorvoertuigen die snelheidsbeperking hebben zoals landbouwvoertuigen.|
|Gemengd verkeer|	Verschillende hoofdverkeersgebruikers zijn toegestaan op de verbinding.|
|Busverkeer|	Voertuig ingericht voor het vervoer van personen, met meer dan acht zitplaatsen, de bestuurderszitplaats niet meegerekend, niet zijnde een motorrijtuig met beperkte snelheid of gehandicaptenvoertuig.|
|Gemotoriseerd verkeer|	Alle gemotoriseerde voertuigen behalve bromfietsen, fietsen met trapondersteuning en gehandicaptenvoertuigen, anders dan railvoertuigen.|
|Fietsers, bromfietsers	|Bestuurders die met een fiets of bromfiets aan het verkeer deelnemen.|
|Fietsers|	Bestuurders die met een fiets aan het verkeer deelnemen.|
|Voetgangers|	Een persoon die te voet deelneemt aan het verkeer.|
|Ruiters|	Bestuurder van een paard of pony. |
|Overig|	Verkeersgebruikers die niet onder de bovenstaande typen vallen. |

*Modaliteit*

|Waarde Modaliteit|Beschrijving|
|---|---|
|Alle voertuigen|	Alle voertuigen exclusief voetgangers. |
|Bromfiets|	Gemotoriseerd voertuig op twee wielen en de snelheid van 25km per uur overschrijdt (speed-pedelec valt hier onder volgens RVV).|
|Snorfiets|	Bromfiets die niet harder kan/mag dan 25 km per uur (volgens RVV valt de e-bike met maximale snelheid van 25km/u hier onder).|
|Fiets|	Een voertuig dat door spierkracht wordt aangedreven. |
|Gehandicaptenvoertuig |	Voertuig dat is ingericht voor het vervoer van een gehandicapt persoon.|
|Land- bosbouwverkeer|	Voertuig van de categorie T, C, R of S, niet zijnde een motorrijtuig met beperkte snelheid of een gehandicaptenvoertuig voornamelijk bestemd voor tractiedoeleinden en in het bijzonder ontworpen voor het trekken, duwen, dragen of in beweging brengen van bepaalde verwisselbare uitrustingsstukken of land- of bosbouwaanhangwagens, dan wel het vervoeren van ladingen of bewerken van materialen.|
|Vrachtwagen|	Motorvoertuig, niet ingericht voor het vervoer van personen, waarvan de toegestane maximum massa meer bedraagt dan 3500 kg.|
|Bus|	Voertuig ingericht voor het vervoer van personen, met meer dan acht zitplaatsen, de bestuurderszitplaats niet meegerekend, niet zijnde een motorrijtuig met beperkte snelheid of gehandicaptenvoertuig.|
|Taxi|	Een motorvoertuig waarmee passagiers zich naar de gewenste bestemming laten brengen tegen betaling. | 
|Personenauto|	Voertuig op vier of meer wielen, niet zijnde een motorrijtuig met beperkte snelheid of gehandicaptenvoertuig, ingericht voor het vervoer van personen, met niet meer dan acht zitplaatsen, de bestuurderszitplaats niet meegerekend.|
|Auto met trailer|	Personenauto met trailer.|
|Bestelauto	|Een auto met een laadruimte die voornamelijk voor het vervoer van goederen is ingericht.|
|Voorrangsvoertuig|	Een motorvoertuig dat optische en geluidssignalen voert. (politie, brandweer, ambulance) |
|Ruiters|	Bestuurder van een paard of pony. |
|Voetgangers|	Een persoon die te voet deelneemt aan het verkeer. |
|Overig	Modaliteiten| Die niet onder bovenstaande typen vallen.|


*openbare weg*

|Waarde Openbare weg|Beschrijving|
|---|---|
|Ja||
|Nee||

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|In gebruik|	
|Buiten gebruik|	
|Beëindigd|	
|Niet gerealiseerd|	
|Ten onrechte	|

#### Spoorweg

#### Vaarweg

#### Waterelement

### Functionele gebouwobjecten

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


*feitelijk gebruik*

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


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|In gebruik|	
|Buiten gebruik	|	
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

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

*kwaliteitsindicatie* 

| Waarde Kwaliteitsindicatie| Beschrijving   |
|---|---|
|  | |


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|In gebruik|	
|Buiten gebruik	|	
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|



### Functionele zoneringen

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
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende typeringen zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een verkeerskundig functionele zone.  |Ja |
|Geometrie |De geometrische representatie van de randen van een verkeerskundig functionele zone.  |Ja (vlak)|
|Type| Een categorisering van de verschillende verkeerskundig functionele zones.| Ja|
|Naam|Een breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Status   |De fase van de levenscyclus waarin de betreffende verkeerskundig functionele zone zich bevindt.   |Ja  |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hyperverbinding |wegverbinding |ja|
|hyperverbinding |knoop |ja|

**Domeinwaarden**

<div class='note'>
    Carpoolplaats, Transferium, Verzorgingsplaats, Parkeerplaats alleen opnemen als dit door BRT.next wordt aangegeven
</div>

*type* 

|Waarde type|	Beschrijving|
|---|---|
| Inrit||
| Parkeervlak | Wegdeel bestemd voor het parkeren van motorvoertuigen. |
| Carpoolplaats | Parkeerplaats die qua ligging en ontsluiting geschikt is voor carpooling. |
| Transferium | Voorziening voor het overstappen tussen vervoersmodaliteiten, die zodanig is gesitueerd en ingericht dat een verplaatsing met meerdere vervoersmodaliteiten aantrekkelijker is dan dezelfde verplaatsing met de auto. |
| Verzorgingsplaats |  Langs de weg gelegen parkeergelegenheid, met inbegrip van de daarbij behorende verharde en onverharde banen en een of meer voorzieningen ten behoeve van reizigers en/of voertuigen. |
| OV-baan |  Wegdeel dat uitsluitend is bestemd en gemarkeerd voor openbaar vervoer en afgescheiden is van de andere wegdelen.|
| Parkeerplaats |  Parkeergelegenheid voor meerdere voertuigen in de openlucht.|
| Benzinestation |  Geheel van installaties, verharding en opstallen waar brandstoffen ten behoeve van verbrandingsmotoren worden verkocht.|
| Snellaadstation |  Infrastructuurelement, doorgaans langs autosnelwegen, dat in elektrische energie voorziet om elektrische plug-invoertuigen op te laden in een relatief korte tijd. |
| Zone |  Verkeerskundige afbakening van een gebied. |


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

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
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type spoorzones zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een spoorzone.  |Ja |
|Geometrie |De geometrische representatie van de randen van een spoorzone.  |Ja (vlak) |
|Type| Een categorisering van verschillende type spoorzones. |Ja|
|Naam|Een breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Status   |De fase van de levenscyclus waarin het betreffende spoorzone zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |



**Domeinwaarden**


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

*type*

| Waarde type	|Beschrijving|
|---|---|
| Perron |  Verhoogde constructie langs een spoorrail of tramrail voor het in- en uitstappen van passagiers of voor het laden en lossen van goederen. |
| Overweg | Een gelijkvloerse kruising van een weg met een spoor type trein of sneltram. |
| Spoorbaan | Gebaand gedeelte voor het verkeer over rails. |
| Emplacement | Het totaal aan sporen op een terrein ten behoeve van het rangeren en stallen van treinen. |

<div class='note'>
    Emplacement alleen opnemen als dit door BRT.next wordt aangegeven 
</div>

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
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type wegzones zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een wegzone.  |Ja |
|Geometrie |De geometrische representatie van een wegzone.  |Ja (vlak) |
|Type | Een categorisering van verschillende wegzones. | Ja|
|Status   |De fase van de levenscyclus waarin het betreffende wegzone zich bevindt.  |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |



**Domeinwaarden**


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

<div class='note'>
    Niet alle type wegzones verplicht maken
</div>

|Waarde type	|Beschrijving|
|---|---|
| Verkeerseiland | Weggedeelte van beperkte omvang, uitgevoerd als een verhoging of wegmarkering, dat wordt omsloten door rijbanen of rijstroken en als doel heeft verkeersstromen te scheiden.  |
| Berm | Een strook grond langs een weg of spoorweg. |
| Halteplaats | Het geheel van voorzieningen bedoeld als stopplaats voor voertuigen van het openbaar vervoer. |
| Verkeersdrempel | Verhoging in een regionale rijbaan, bedoeld om het gemotoriseerde verkeer met een lage snelheid te laten rijden.| 
| Wildrooster | Horizontaal raamwerk dat dient om wild de doorgang te beletten.   |


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
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type luchtvaartzones zoals deze zijn opgenomen in de basisregistratie (grootschalige) topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een luchtvaartzone.  |Ja |
|Geometrie |De geometrische representatie van een luchtvaartzone. |Ja (vlak)|
|Type| Een categorisering van type luchtvaartzone. | Ja|
|Naam|Een breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Status   |De fase van de levenscyclus waarin het betreffende luchtvaartzone zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |



**Domeinwaarden**


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

*type*

|Waarde type	|Beschrijving|
|---|---|
| Baan voor vliegverkeer | Wegdeel uitsluitend bedoeld voor vliegverkeer.  |
| Luchthaven | Vliegveld voor verkeersvliegtuigen met groot, effen terrein met al dan niet verharde banen, waar vliegtuigen kunnen opstijgen en landen, eventueel met accommodatie voor ontvangst en vertrek van passagiers en verzending van goederen.  |

<div class='note'>
    Luchthaven alleen opnemen als dit door BRT.next wordt aangegeven
</div>















#### Begraafplaats

#### Recreatie
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Recreatie|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Recreatie  |
|---|---|
| Definitie |  |
| Herkomst definitie  |      |
| Verplicht  | Ja  |
| Gevolgen afbakening||
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van recreatie  |Ja |
|Geometrie |De geometrische representatie van recreatie |Ja (vlak)|
|Naam|Een breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Status   |De fase van de levenscyclus waarin de betreffende recreatie zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|In gebruik|	
|Buiten gebruik|	
|Beëindigd|	
|Niet gerealiseerd|	
|Ten onrechte	|

.

|Waarde type | Beschrijving|
|---|---|
| 	speeltuin||
| 	park||
| 	sportterrein||
| 	camping||
| 	bungalowpark||
| 	volkstuin| | 




 




#### Oever
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Oever |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Oever  |
|---|---|
| Definitie | De strook land die in direct contact staat met water, inclusief het gebied tussen de hoogwaterlijn en laagwaterlijn.   |
|Herkomst definitie  | BGT 1.2     |
|Verplicht  | Ja  |
|Gevolgen afbakening|Het betreft hier de bestaande populatie *oever, slootkant* zoals deze is opgenomen in de basisregistratie grootschalige topografie. |
|Toelichting| Slootkant is een oever. |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip oever.|Ja |
|Geometrie|De geometrische representatie van de randen van de oever.|Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de betreffende oever zich bevindt.  |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |



**Domeinwaarden**


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

#### Complex
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Complex |
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Complex  |
|---|---|
| Definitie |  Verzameling van één of meer bouwwerken, gronden en inrichtingen die samen een functionele eenheid vormen, en die een aantal voorzieningen kunnen delen. |
|Herkomst definitie  |  nieuw   |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip complex.|Ja |
|Geometrie|De geometrische representatie van de randen van een complex.|ja (vlak)|
|Type complex|Een categorisering van de verschillende complexen. |ja|
|Naam|Een breed geaccepteerde benaming van een complex zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Status   | De fase van de levenscyclus waarin de betreffende complex zich bevindt.  |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |



**Domeinwaarden**


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

*type complex*

|Waarde Type complex| Beschrijving   |
|---|---|
|||
|gemaalcomplex|Alle bij een gemaal behorende gronden, inrichtingen en bouwwerken.|
|sluiscomplex|Alle bij een sluis behorende gronden, inrichtingen en bouwwerken.|
|stuwcomplex|Alle bij een stuw behorende gronden, inrichtingen en bouwwerken.|
|coupurecomplex|Alle bij een coupure behorende gronden, inrichtingen en bouwwerken.|
|aanleg en overslag|Alle bij een haven behorende gronden, inrichtingen en bouwwerken.|




### Overige functionele zoneringen

#### Kering
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Kering|
| Onderdeel van NEN3610-objecttype | Functioneel object |

 

**Definitie**

| Naam  | Kering |
|---|---|
| Definitie | Voorziening met kerende functie. |
|Herkomst definitie  |nieuw|
|Verplicht  | ja  |
|Gevolgen afbakening||
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van het SOR-begrip kering|Ja |
|Geometrie|De geometrische representatie van de kerende voorziening.|Ja (lijn, vlak)|
|Type kering|Een categorisering van de verschillende type keringen.|Ja|
|Status   | De fase van de levenscyclus waarin de kerende voorziening zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

*kering*

|Waarde type kering| Beschrijving   |
|---|---|
|grond	|voorziening bedoeld om grond te keren|
|water	|voorziening bedoeld om water te keren|
|stormvloed	|Een stormvloedkering is een voorziening (waterbouwkundige constructie) die bij stormvloed of springtij moet verhinderen dat er grote hoeveelheden water de monding van een rivier instromen en stroomopwaarts tot overstromingen leiden. |




#### Reducering

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Reducering|
| Onderdeel van NEN3610-objecttype | Functioneel object |

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
|Geometrie|De geometrische representatie van de reducerende voorziening.|Ja (lijn)|
|Type reducering|Een categorisering van de verschillende type reducering.| Ja|
|Status   | De fase van de levenscyclus waarin de reducerende voorziening zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

*type reducering* 

|Waarde Type reducering| Beschrijving   |
|---|---|
|geluid|	voorziening bedoeld om geluidshinder in de buitenlucht te verminderen|
|fijnstof|	voorziening bedoeld om verspreiding van fijnstof te verminderen	|


#### Valbescherming
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Valbescherming|
| Onderdeel van NEN3610-objecttype | Functioneel object |

 

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
|Geometrie|De geometrische representatie de valbescherming.|Ja (lijn)|
|Status   |  De fase van de levenscyclus waarin de valbescherming zich bevindt.  |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |



**Domeinwaarden**


*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|


#### Afscheiding 
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Afscheiding |
| Onderdeel van NEN3610-objecttype | Functioneel object |


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
|Identificatie   |De unieke aanduiding van afscheiding. |Ja |
|Geometrie|De geometrische representatie van de afscheiding.|Ja (lijn)|
|Status   | De fase van de levenscyclus waarin de afscheiding zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland	|
|Gevormd|
|Beëindigd	|
|Niet gerealiseerd|	
|Ten onrechte	|

