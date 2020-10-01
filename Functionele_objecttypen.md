## Functionele objecttypen

### Transportvoorzieningen

#### Weg

**KNOOP**

| Klasse  | Naam  |
{: .blue}
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
|Identificatie   |De unieke aanduiding van een Knoop  |Ja |
|Geometrie |De geometrische representatie van een knoop |Ja (punt), Nee (vlak)|
|Type verkeersgebied|Een deel van de weg met een specifieke functie om van richting te veranderen of de reis te beginnen/eindigen.|Ja|
|Hoofdverkeersgebruik|Hoofdverkeersgebruiker is het meest voorkomende verkeer dat zich over de knoop verplaatst.|Ja|
|Status   |De fase van de levenscyclus waarin de betreffende knoop zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

*overerving van eigenschappen/kenmerken a.g.v. relatie met andere objecten*

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Formele naam | De naam die aan een openbare ruimte is toegekend in een daartoe strekkend formeel gemeentelijk besluit | Ja (LR) (MV)|
|Alternatieve naam|Een alternatieve benaming van een openbare ruimte zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een formele benaming in het Nederlands) of in het Nederlands (bij een formele benaming in het Fries) | Ja (LR) (MV)|
|Type verharding|Aanduiding soort verharding.|Ja (LR) (MV)|


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| ligt aan 1 of meer | gerelateerde wegverbinding(en) |Ja|
| heeft 1 | openbare ruimte | Ja  |
| ligt op | gerelateerde reële object | Ja|
| hyperverbinding met| gerelateerde functionele zone | Ja|

**Domeinwaarden**

|Waarde Type verkeersgebied|Beschrijving|
|---|---|
|kruising|Een kruising is een punt waar tenminste drie verbindingen samenkomen in de vorm van een Y,T of +.|
|verkeersplein|Een verkeersplein is een punt waar wegen uit tenminste 3 richtingen samenkomen in de vorm van een rond plein, waar het rijverkeer met een verplichte, rondgaande rijrichting wordt afgewikkeld waarbij het verkeer op het plein geen voorrang heeft.|
|rotonde|Een rotonde is een punt waar wegen uit tenminste 3 richtingen samenkomen in de vorm van een ring (veelal rond), waar het rijverkeer met een verplichte, rondgaande rijrichting wordt afgewikkeld en waarbij het verkeer op de ring voorrang heeft. |
|knooppunt|Een knooppunt is een kruispunt van auto(snel)wegen.|

.

|Waarde Hoofdverkeersgebruik|Beschrijving|
|---|---|
|Snelverkeer|	Motorvoertuigen die geen snelheidsbeperking hebben inclusief vrachtwagens.|
|Langzaam verkeer|	Motorvoertuigen die snelheidsbeperking hebben zoals landbouwvoertuigen, fietsers, voetgangers.|
|Gemengd verkeer|	Verschillende hoofdverkeersgebruikers zijn toegestaan om de knoop.|
|Busverkeer|	Voertuig ingericht voor het vervoer van personen, met meer dan acht zitplaatsen, de bestuurderszitplaats niet meegerekend, niet zijnde een motorrijtuig met beperkte snelheid of gehandicaptenvoertuig.|
|Fietsers, bromfietsers	|Bestuurders die met een fiets of bromfiets aan het verkeer deelnemen.|
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
|Identificatie   |De unieke aanduiding van een Wegverbinding.  |Ja |
|Geometrie |De geometrische representatie van een wegverbinding.  |Ja (lijn), Nee (vlak)|
|Type wegverbinding|De type verbinding beschrijft het level van detail van het netwerk.|Ja|
|Type weg| Een categorisering van de verschillende wegtypes. |Ja|
|Type baan| Een categorisering van de verschillende baantypes. |Ja|
|Type strook| Een categorisering van de verschillende strooktypes. |Nee|
|Hoofdverkeersgebruik|Hoofdverkeersgebruiker is het meest voorkomende verkeer dat zich over de wegverbinding verplaatst.|Ja|
|Modaliteit| Soorten voertuigen die zich op de verbinding mogen begeven. | Ja (MV)|
|Rijrichting| De toegestane beweegrichting van het verkeer op een wegverbinding | Ja|
|Openbare weg|Weg die door iedereen gebruikt kan worden. | Ja|
|Verkeerskundig kenmerk| Een mogelijk geldende beperking/waarschuwing voor weggebruikers op een deel van de wegverbinding.| Ja (LR) (MV)|
|Status   |De fase van de levenscyclus waarin de betreffende wegverbinding zich bevindt   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

*overerving van eigenschappen/kenmerken a.g.v. relatie met andere objecten*

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Formele naam | De naam die aan een openbare ruimte is toegekend in een daartoe strekkend formeel gemeentelijk besluit | Ja (LR) (MV)|
|Alternatieve naam|Een alternatieve benaming van een openbare ruimte zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een formele benaming in het Nederlands) of in het Nederlands (bij een formele benaming in het Fries) | Ja (LR) (MV)|
|Fysieke kenmerken | Fysieke eigenschappen met een verkeerskundige betekenis zoals opgenomen als eigenschap bij gerelateerde reële objecten. Zoals bijvoorbeeld de eigenschap type verharding. |Ja (LR) (MV)|


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij 2 | knoop |ja|
| heeft een | openbare ruimte | ja  |
| ligt op | gerelateerde reële object| ja|
| hyperverbinding met | gerelateerde functionele zone | Ja|

**Domeinwaarden**

|Waarde type wegverbinding|	Beschrijving|
|---|---|
|Weg	|Een weg is een voorziening die bestaat uit banen die een functie vervullen ten behoeve van het afwikkelen van het verkeer.(LoD0))|
|Baan	|Een aaneengesloten deel van een weg dat bedoeld is voor bepaalde groepen verkeersgebruikers. (LoD1)|
|Strook|	Door doorgetrokken of onderbroken strepen gemarkeerd gedeelte van de baan. (LoD2)|
|Veerverbinding|Een geregelde verbinding per vaartuig bestemd voor (on)bepaalde hoofdverkeersgebruik. (Verbijzondering van type weg)|


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
|Ruiterpad|Een pad primair aangelegd voor het gebruik door ruiters.|

*type baan*

|Waarde type baan	|Beschrijving|
|---|---|
|hoofdrijbaan	|Meerdere stroken met dezelfde hoofdverkeersfunctie. Een verkeer dragende baan bestemd voor doorgaand verkeer.|
|busbaan	|Vrij liggende baan bestemd voor autobussen ten behoeve van het openbaar vervoer en andere erop toegelaten motorvoertuigen. |
|rotondebaan|	Een hoofdrijbaan op een rotonde, met een hectometrering en een hectometreringsletter.|
|rangeerbaan|	Verbindt de uit en invoegstrook met elkaar en geeft toegang tot verbindingsbogen. |
|parallelbaan|	Een verkeer dragende baan die naast een hoofdrijbaan loopt en het lokale verkeer dat die hoofdrijbaan mag en wil kruisen, oprijden of verlaten, kan opvangen, verzamelen of verdelen, of alleen voor lokaal verkeer gebruikt kan worden.|
|tussenbaan	|Een verkeerdragende baan die een verbinding vormt tussen twee verzorgingsbanen en geen eigen hectometreringsletter heeft.|
|verbindingsbaan|	Een verkeer dragende baan die de verbinding verzorgt tussen ongelijkvloers samenkomende wegen of tussen niet samenkomende wegen, en die voorzien is van hectometerborden met een hectometrering en een hectometreringsletter.|
|verzorgingsbaan|	Een verkeer dragende baan op een parkeer- of verzorgingsplaats voor rustend verkeer|
|fietspad	|Een weggedeelte dat is gereserveerd voor het fietsverkeer en snorfietsen|
|voetpad	|Deel van verkeersinfrastructuur dat uitsluitend bedoeld is voor voetgangers.|
|ruiterpad	|Een speciaal zandpad waarover ruiters kunnen rijden.|

*type strook*

|Waarde type strook	|Beschrijving|
|---|---|
|Rijstrook |	Een strook waar voertuigen over rijden.|
|Vluchtstrook|	Een strook langs autosnelwegen waar weggebruikers naar kunnen uitwijken in geval van nood of pech|
|Spitsstrook |	Een spitsstrook is een extra rijstrook op een rijbaan van een autosnelweg|
|Invoegstrook |	Een rijstrook die naar de hoofdrijbaan leidt|
|Uitvoegstrook |	Een rijstrook met beperkte lengte waarop bestuurders snelheid kunnen minderen om uit te voegen.|
|Weefstrook |	Een weefvak is een combinatie van een invoegstrook en uitvoegstrook.|
|Bufferstrook |	Een bufferstrook is een extra rijstrook die kan worden opengesteld om te voorkomen dat een file vóór een knelpunt zo lang wordt dat hij andere verkeersstromen gaat blokkeren.|
|Plusstrook |	Een opengestelde strook aan de linkerzijde van een rijbaan.|
|Wisselstrook |	Een rijstrook die afhankelijk van de drukte geopend wordt voor een bepaalde rijrichting.|
|Redresseerstrook |	Een strook langs de buitenste rijstroken van een rijbaan met als doel om uit de koers geraakte voertuigen op te vangen en terug op koers te brengen.|
|Voorsorteerstrook |	Een infrastructurele voorziening nabij kruisingen waar verkeersdeelnemers zich opstellen om naar de gewenste richting (linksaf, rechtdoor, rechtsaf) af te slaan. |
|Klimstrook |	Een strook waarbij trager rijdend verkeer (zoals vrachtwagens) en het overige sneller rijdende verkeer gescheiden wordt bij het beklimmen van een heuvel of berg.|
|Fietsstrook |	Een strook dat uitsluitend voor fietsers is gereserveerd met fietssymbool. |
|Fietssuggestiestrook |	Een strook dat voor fietsers is gereserveerd zonder fietssymbool.|
|Passeerstrook|	Een passeerstrook is een lokale wegverbreding op smalle wegen buiten de bebouwde kom waar langzaam verkeer gepasseerd kan worden. |
|Vrachtwagenstrook|	Een vrachtwagenstrook is een rijstrook specifiek bestemd voor vrachtverkeer en meestal ook bussen.|
|Bus-strook|	Een strook waar alleen bussen (hulpdiensten en trams) mogen rijden.|



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

<div class='note'>
    De definitieve beschrijving van het spoorwegennetwerk zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze beschrijving aansluit op de begrippen zoals deze door Prorail worden gehanteerd. Onderstaande begrippen zijn voorbeelden en uitsluitend bedoeld om een indruk te geven van wat hier zal worden opgenomen. Ook wordt deze lijst nog afgestemd met begrippen in de BRT.
</div>

**KNOOP**

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Knoop|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Knoop  |
|---|---|
| Definitie | Een knoop is een begin-, eind- of keuzepunt voor de spoorgebruiker. |
| Herkomst definitie  | nieuw     |
| Verplicht  | Ja  |
| Gevolgen afbakening||
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Knoop.  |Ja |
|Geometrie |De geometrische representatie van een knoop. |Ja (punt), Nee (vlak)|
|Status   |De fase van de levenscyclus waarin de betreffende knoop zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| ligt aan 1 of meer | gerelateerde spoorwegverbinding(en) |Ja|
| ligt op | gerelateerde reële object | Ja|
| hyperverbinding met| gerelateerde functionele zone | Ja|

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


**SPOORVERBINDING**

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Spoorverbinding|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Spoorverbinding  |
|---|---|
| Definitie | Een spoorverbinding beschrijft de verkeerskundige inrichting van een spoor tussen twee knopen. |
|Herkomst definitie  | conceptueel model netwerken     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Spoorverbinding.  |Ja |
|Geometrie |De geometrische representatie van een spoorverbinding.  |Ja (lijn), Nee (vlak)|
|Status   |De fase van de levenscyclus waarin de betreffende spoorverbinding zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij 2 | knoop |ja|
| ligt op | gerelateerde reële object| ja|
| hyperverbinding met | gerelateerde functionele zone | Ja|

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



#### Vaarweg

<div class='note'>
    De definitieve beschrijving van het vaarwegennetwerk zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze beschrijving aansluit op de begrippen zoals deze in de scheepvaartsector worden gehanteerd. Onderstaande begrippen zijn voorbeelden en uitsluitend bedoeld om een indruk te geven van wat hier zal worden opgenomen. Ook wordt deze lijst nog afgestemd met begrippen in de BRT.
</div>


**KNOOP**

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Knoop|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Knoop  |
|---|---|
| Definitie | Een knoop is een begin-, eind- of keuzepunt voor de vaarweggebruiker. |
| Herkomst definitie  | nieuw     |
| Verplicht  | Ja  |
| Gevolgen afbakening||
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Knoop.  |Ja |
|Geometrie |De geometrische representatie van een knoop. |Ja (punt), Nee (vlak)|
|Status   |De fase van de levenscyclus waarin de betreffende knoop zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| ligt aan 1 of meer | gerelateerde vaarwegverbinding(en) |Ja|
| ligt op | gerelateerde reële object | Ja|
| hyperverbinding met| gerelateerde functionele zone | Ja|

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


**VAARWEGVERBINDING**

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Vaarwegverbinding|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Vaarwegverbinding  |
|---|---|
| Definitie | Een vaarwegverbinding beschrijft de verkeerskundige inrichting van een vaarweg tussen twee knopen. |
|Herkomst definitie  | conceptueel model netwerken     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een vaarwegverbinding.  |Ja |
|Geometrie |De geometrische representatie van een vaarwegverbinding.  |Ja (lijn), Nee (vlak)|
|Status   |De fase van de levenscyclus waarin de betreffende vaarwegverbinding zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij 2 | knoop |ja|
| ligt op | gerelateerde reële object| ja|
| hyperverbinding met | gerelateerde functionele zone | Ja|

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


#### Water

<div class='note'>
    De definitieve beschrijving van het waternetwerk zal op een later moment worden opgeleverd. Het is daarbij de bedoeling dat deze beschrijving aansluit op de begrippen zoals deze in de watersector worden gehanteerd. Onderstaande begrippen zijn voorbeelden en uitsluitend bedoeld om een indruk te geven van wat hier zal worden opgenomen. Ook wordt deze lijst nog afgestemd met begrippen in de BRT.
</div>

**KNOOP**

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Knoop|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Knoop  |
|---|---|
| Definitie | Een knoop is een begin-, eind- of keuzepunt voor water. |
| Herkomst definitie  | nieuw     |
| Verplicht  | Ja  |
| Gevolgen afbakening||
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een Knoop.  |Ja |
|Geometrie |De geometrische representatie van een knoop. |Ja (punt), Nee (vlak)|
|Status   |De fase van de levenscyclus waarin de betreffende knoop zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| ligt aan 1 of meer | gerelateerde waterverbinding(en) |Ja|
| ligt op | gerelateerde reële object | Ja|
| hyperverbinding met| gerelateerde functionele zone | Ja|

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


**WATERVERBINDING**

| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Waterverbinding|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | waterverbinding  |
|---|---|
| Definitie | Een waterverbinding beschrijft de hydrologische inrichting van water tussen twee knopen. |
|Herkomst definitie  | nieuw     |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een waterverbinding.  |Ja |
|Geometrie |De geometrische representatie van een waterverbinding.  |Ja (lijn), Nee (vlak)|
|Status   |De fase van de levenscyclus waarin de betreffende waterverbinding zich bevindt.   |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij 2 | knoop |ja|
| ligt op | gerelateerde reële object| ja|
| hyperverbinding met | gerelateerde functionele zone | Ja|

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
|Naam|Een breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.| Nee |
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
| Definitie | Gebied in gebruik voor spoorwegen.  |
|Herkomst definitie  | nieuw|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type spoorzones zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van Spoorzone.  |Ja |
|Geometrie |De geometrische representatie van de randen van een spoorzone.  |Ja (vlak) |
|Type| Een categorisering van verschillende soorten spoorzones. |Ja|
|Naam|Een breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.| Nee |
|Status   |De fase van de levenscyclus waarin het betreffende spoorzone zich bevindt.   |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hyperverbinding |wegverbinding |ja|
|hyperverbinding |spoorverbinding |ja|
|hyperverbinding |knoop |ja|


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
| Overweg | Een gelijkvloerse kruising van een weg met een spoor voor trein, tram of metro. |
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
| Definitie | Gebied in gebruik voor weginrichting.  |
|Herkomst definitie  | nieuw |
|Verplicht  | Ja (deels)  |
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type wegzones zoals deze zijn opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van Wegzone.  |Ja |
|Geometrie |De geometrische representatie van de randen van een wegzone.  |Ja (vlak) |
|Type | Een categorisering van verschillende soorten wegzones. | Ja|
|Status   |De fase van de levenscyclus waarin het betreffende wegzone zich bevindt.  |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie zoals bronverwijzing en historiemodel*   |*ja*   |

**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hyperverbinding |wegverbinding |ja|
|hyperverbinding |knoop |ja|


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

.

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
| Definitie | Gebied in gebruik voor luchtvaart.  |
|Herkomst definitie  | nieuw|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type luchtvaartzones zoals deze zijn opgenomen in de basisregistratie (grootschalige) topografie.  |
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van Luchtvaartzone.  |Ja |
|Geometrie |De geometrische representatie van de randen van een luchtvaartzone. |Ja (vlak)|
|Type| Een categorisering van soort luchtvaartzone. | Ja|
|Naam|Een breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.| Nee |
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
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Begraafplaats |
| Onderdeel van NEN3610-objecttype |Functioneel object|

**Definitie**

| Naam  | Begraafplaats |
|---|---|
| Definitie |Een besloten gebied waar lichamen van overleden personen worden begraven. Ook worden op begraafplaatsen urnen as van gecremeerde lichamen bewaard. |
|Herkomst definitie  | IMGeo 2.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier deels de bestaande populatie *begraafplaats*  zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van Begraafplaats. |Ja |
|Geometrie|De geometrische representatie van de randen van een begraafplaats. |Ja (vlak)|
|Status   |  De fase van de levenscyclus waarin de begraafplaats zich bevindt. |Ja   |
|Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |

**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|gepland|
|bestaand|
|verwijderd|
|niet gerealiseerd|
|Ten onrechte|

#### Recreatie
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Recreatie|
| Onderdeel van NEN3610-objecttype |Functioneel object  |

**Definitie**

| Naam  | Recreatie  |
|---|---|
| Definitie | Gebied in gebruik voor openlucht recreatie.  |
| Herkomst definitie  | IMGeo 2.2     |
| Verplicht  | Ja  |
| Gevolgen afbakening|Het betreft hier deels de bestaande populatie typen *recreatie*  zoals deze is opgenomen in de basisregistratie grootschalige topografie.|
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van recreatie.  |Ja |
|Geometrie |De geometrische representatie van recreatie. |Ja (vlak)|
|Naam|Een breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.| Nee |
|Type|Een categorisering van de verschillende soorten recreatie.|Nee| 
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
| 	speeltuin|Geheel van begroeiing, verharding, opstallen en speelwerktuigen, bedoeld als speelplaats voor kinderen.|
| 	park|Landschappelijk ingericht terrein, begroeid met houtachtige en kruidachtige vegetatie, verharding, objecten, waterpartijen en dergelijke, bedoeld als (grootschalige) recreatieve voorziening.|
| 	sportterrein|Terrein, mogelijk met groenvoorziening, verharding en bebouwing, bestemd voor sportbeoefening.|
| 	camping|Geheel van verharding, begroeiing en opstallen, in gebruik als terrein waar tijdelijk tenten en/of caravans kunnen worden geplaatst ten behoeve van recreatie.|
| 	bungalowpark|Geheel van verharding, begroeiing, overige opstallen en gebouwen, bedoeld als vakantie-/weekendhuisjes die niet permanent bewoond worden.|
| 	volkstuin|Terreingedeelte in gebruik als volkstuinen, inclusief bebouwing, verharding en dergelijke. | 


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
|Identificatie   |De unieke aanduiding van oever.|Ja |
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
|Identificatie   |De unieke aanduiding van Complex.|Ja |
|Geometrie|De geometrische representatie van de randen van een complex.|ja (vlak)|
|Type complex|Een categorisering van de verschillende complexen. |ja|
|Naam|Een breed geaccepteerde benaming van een complex zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.| Nee |
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
|Identificatie   |De unieke aanduiding van Kering.|Ja |
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
|Identificatie   |De unieke aanduiding van reducering.|Ja |
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
|Identificatie   |De unieke aanduiding van valbescherming.|Ja |
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

