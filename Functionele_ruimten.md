## Functionele ruimten
 

### Transportruimten

 <div class='note'>
    Op dit moment zijn de transportruimten WEG en SPOORWEG uitgewerkt. Er is nog onvoldoende duidelijkheid over transport van en over water. Deze zijn in dit document niet opgenomen maar kunnen hier later mogelijk aan worden toegevoegd conform de algemene principes over netwerken.
</div>

 
#### Weg

**WEGKNOOP**

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Wegverkeerruimte"

**Definitie**

| Naam  | Wegknoop  |
|---|---|
| Definitie |  Wegverkeerruimte die een begin-, eind- of keuzepunt is voor de weggebruiker/voertuig|
| Herkomst definitie  | Nieuw    |
| Verplicht  | Ja, op weg- en baanniveau  |
| Gevolgen afbakening||
| Toelichting| Gebaseerd op conceptueel model netwerken |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |weg|baan|strook|
|---|---|---|---|---|---|
|Identificatie   |Unieke aanduiding van een wegknoop  |Ja | x | x | x |
|Geometrie |Geometrische representatie van een wegknoop |Ja (2D punt), Nee (2D vlak)|x | x | x |
|Type keuzepunt|De aanduiding van het soort keuzepunt|Ja| x |  |  |
|Status   |De fase van de levenscyclus waarin een wegknoop zich bevindt   |Ja |x | x | x |



**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| ligt aan 1 of meer | gerelateerde wegverbinding(en) |Ja|
| heeft 0 of 1| openbare ruimte | Ja (indien aanwezig) |
| ligt op 1 of meer| gerelateerde reële object | Ja |
| hyperverbinding | gerelateerde functionele zone | Ja|

Het leggen van deze relaties maken het dus mogelijk om namen en fysieke eigenschappen aan het wegennetwerk te relateren.

**Domeinwaarden**

*Type*

|Waarde Type verkeersgebied|Beschrijving|
|---|---|
|eindknoop	|Wegknoop met 1 verbinding en is het einde van een doodlopende weg|
|grensknoop	|Wegknoop met 1 verbinding en betreft een doorgaande verbinding met het wegennetwerk van een buurland|
|koppelknoop	|Wegknoop waar twee verschillende type wegverbindingen aan elkaar verbonden zijn|
|kruising|Wegknoop waar tenminste drie verbindingen samenkomen in de vorm van een Y,T of +|
|verkeersplein|Wegknoop waar wegen uit tenminste 3 richtingen samenkomen in de vorm van een rond plein, waar het rijverkeer met een verplichte, rondgaande rijrichting wordt afgewikkeld waarbij het verkeer op het plein geen voorrang heeft|
|rotonde|Wegknoop waarop het verkeer voorrang heeft en waarop de wegen radiaal aansluiten.  |
|knooppunt|Wegknoop van twee stroomwegen waartussen ongelijkvloerse uitwisseling mogelijk is|


*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd

**WEGVERBINDING**

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Wegverkeerruimte"

**Definitie**

| Naam  | Wegverbinding  |
|---|---|
| Definitie |  Wegverkeerruimte die de verkeerskundige inrichting van een weg beschrijft tussen twee knopen |
|Herkomst definitie  | nieuw    |
|Verplicht  | Ja, op weg- en baanniveau  |
|Gevolgen afbakening||
|Toelichting| Gebaseerd op conceptueel model netwerken |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |weg|baan|strook|
|---|---|---|---|---|---|
|Identificatie   |Unieke aanduiding van een wegverbinding|Ja | x | x | x |
|Geometrie |Geometrische representatie van een wegverbinding|Ja (2D lijn), Nee (2D vlak)| x | x | x |
|Type wegverbinding|Aanduiding van soort wegverbinding|Ja| x | x | x |
|Type weg| Categorisering van de verschillende wegtypes|Ja| x |  |  |
|Type baan| Categorisering van de verschillende baantypes|Ja|  | x | |
|Type strook| Categorisering van de verschillende strooktypes|Nee|  | | x |
|Routenummer|Routenummer die over de wegverbinding loopt. Er zijn meerdere routenummers op een wegverbinding mogelijk (MV)|Ja (indien aanwezig)| x |  |  |
|Afritnummer| Nummer toegekend aan een verbindingsbaan|Ja (indien aanwezig)|  | x |  |
|Rijrichting| De toegestane beweegrichting van de hoofdverkeersgebruiker op een weg/baan/strookverbinding | Ja| x | x | x |
|Openbare weg|Bestaan van een beperking in het gebruik, zoals bedoeld in art. 6 van de Wegenwet| Ja (indien aanwezig in wegenlegger) | x | |  |
|Status   |De fase van de levenscyclus waarin een wegverbinding zich bevindt   |Ja  | x | x | x  |





**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij 1 of 2 | gerelateerde kno(o)p(en) |ja|
| heeft 0 of meer | gerelateerde openbare ruimte(n)| ja (LR) |
| ligt op 1 of meer | gerelateerde reële object(en)| ja |
| hyperverbinding | gerelateerde functionele zone | Ja|


Het leggen van deze relaties maken het dus mogelijk om namen en fysieke eigenschappen aan het wegennetwerk te relateren.

**Domeinwaarden**

*Type wegverbinding*

|Waarde type wegverbinding|	Beschrijving|
|---|---|
|Weg	|Voorziening die bestaat uit banen die een functie vervullen ten behoeve van het afwikkelen van het verkeer|
|Baan	|Aaneengesloten deel van een weg dat bedoeld is voor bepaalde groepen verkeersgebruikers|
|Strook|	Door doorgetrokken of onderbroken strepen gemarkeerd gedeelte van de baan|


*Type weg*

|Waarde type weg	|Beschrijving|
|---|---|
|Autosnelweg|	Conflictvrije weg (ongelijkvloerse kruisingen) aangeduid met bord G1 (RVV) bestemd voor snel gemotoriseerd verkeer|
|Autoweg	|Weg aangeduid door bord G3 (RVV) die alleen voor snel gemotoriseerd (min 50km/uur) verkeer toegankelijk is|
|Gebiedsontsluitingsweg gesloten|	Verbindt een auto(snel)weg met een erftoegangsweg waar geen land- en bosbouwverkeer is toegestaan|
|Gebiedsontsluitingsweg open|	Verbindt een auto(snel)weg met een erftoegangsweg waar wel land- en bosbouwverkeer is toegestaan|
|Erftoegangsweg|Weg met gemengd langzaam verkeer en gemotoriseerd verkeer, zonder rijrichtingscheiding en zonder gescheiden fietspaden|
|Fietsstraat|	Straat die ingericht is als fietsroute waar auto’s zijn toegestaan|
|Fiets/bromfietspad|	Vrij liggend pad (zonder naast/parallel liggende weg) dat voor zowel bromfietsers als fietsers verplicht is|
|Fietspad|	Vrij liggend pad (zonder naast/parallel liggende weg) dat is gereserveerd voor het fietsverkeer en snorfietsen|
|Voetpad|	Ven vrij liggend pad (zonder naast/parallel liggende weg) dat uitsluitend bedoeld is voor voetgangers |
|Voetgangerszone| Wegverbinding die bedoeld is voor voetgangers met uitzondering van fietsers en bestemmingsverkeer en, tussen bepaalde tijden, andere verkeersgebruikers|
|Ruiterpad	|Vrij liggend (zonder naast/parallel liggende weg) zandpad waarover ruiters mogen rijden|
|Veerverbinding	|Geregelde verbinding per vaartuig bestemd voor (on)bepaald hoofdverkeersgebruik|

Een wegverbinding is van het type fiets/bromfietspad, voetpad, fietspad, voetgangerszone of ruiterpad indien er geen andere baan is die onderdeel uitmaakt van de weg. Het is dus een “vrij liggend” pad.

*Type baan*

|Waarde type baan	|Beschrijving|
|---|---|
|Hoofdrijbaan	|Verkeer dragende baan bestemd voor doorgaand verkeer|
|Busbaan	|Vrij liggende baan bestemd voor autobussen ten behoeve van het openbaar vervoer en andere erop toegelaten motorvoertuigen|
|Verbindingsbaan	|Verkeer dragende baan die de verbinding verzorgt tussen ongelijkvloers samenkomende wegen of tussen niet samenkomende wegen, en die voorzien is van hectometerborden|
|Rotondebaan	|Hoofdrijbaan op een rotonde|
|Verzorgingsbaan	|Verkeer dragende baan op een parkeer- of verzorgingsplaats voor rustend verkeer|
|Fietspad	|Baan aanliggend/parallel aan de hoofdrijbaan, al dan niet gescheiden, die is gereserveerd voor het fietsverkeer en snorfietsen|
|Voetpad	|Baan aanliggend/parallel aan de hoofdrijbaan, al dan niet gescheiden die bedoeld is voor voetgangers|
|Ruiterpad	|Speciaal zandpad aanliggend/parallel aan de hoofdrijbaan, al dan niet gescheiden, waarover ruiters kunnen rijden|
|Fietsveer	|Geregelde verbinding per vaartuig bestemd voor het fietsverkeer en snorfietsen|
|Voetveer	|Geregelde verbinding per vaartuig bestemd voor voetgangers|
|Veerverbinding 	|Geregelde verbinding per vaartuig bestemd voor onbepaalde hoofdverkeersgebruik|

*Type strook*

|Waarde type strook	|Beschrijving|
|---|---|
|Rijstrook |	Strook waar voertuigen over rijden|
|Vluchtstrook|	Strook langs autosnelwegen waar weggebruikers naar kunnen uitwijken in geval van nood of pech|
|Spitsstrook |	Een extra rijstrook op een rijbaan van een autosnelweg|
|Redresseerstrook	|Strook langs de buitenste rijstroken van een rijbaan met als doel om uit de koers geraakte voertuigen op te vangen en terug op koers te brengen|
|Invoegstrook |	Rijstrook die naar de hoofdrijbaan leidt|
|Uitvoegstrook |	Een rijstrook met beperkte lengte waarop bestuurders snelheid kunnen minderen om uit te voegen|
|Weefstrook |	Een combinatie van een invoegstrook en uitvoegstrook|
|Bufferstrook |	Een extra rijstrook die kan worden opengesteld om te voorkomen dat een file vóór een knelpunt zo lang wordt dat hij andere verkeersstromen gaat blokkeren|
|Plusstrook |	Smalle strook aan de linkerzijde van een rijbaan met dynamische openstelling|
|Wisselstrook |	Een rijstrook die afhankelijk van de drukte geopend wordt voor een bepaalde rijrichting|
|Passeerstrook|	Een lokale wegverbreding op smalle wegen buiten de bebouwde kom waar langzaam verkeer gepasseerd kan worden|
|Opstelstrook |Infrastructurele voorziening nabij kruisingen waar verkeersdeelnemers zich opstellen om naar de gewenste richting (linksaf, rechtdoor, rechtsaf) af te slaan|
|Opstelstrook linksaf	|Infrastructurele voorziening nabij kruisingen waar verkeersdeelnemers zich opstellen om linksaf te slaan|
|Opstelstrook opgeblazen fietsopstelstrook	|Infrastructurele voorziening nabij kruisingen waar fietsers zich voor het andere verkeer opstellen om linksaf te slaan|
|Opstelstrook rechtdoor	|Infrastructurele voorziening nabij kruisingen waar verkeersdeelnemers zich opstellen om rechtdoor te gaan|
|Opstelstrook rechtdoor+linksaf	|Infrastructurele voorziening nabij kruisingen waar verkeersdeelnemers zich opstellen om linksaf te slaan of rechtdoor te gaan|
|Opstelstrook rechtdoor+rechtsaf	|Infrastructurele voorziening nabij kruisingen waar verkeersdeelnemers zich opstellen om rechtsaf te slaan of rechtdoor te gaan|
|Opstelstrook rechtsaf	|Infrastructurele voorziening nabij kruisingen waar verkeersdeelnemers zich opstellen om rechtsaf te slaan|
|Vrachtwagenstrook	|Strook specifiek bestemd voor vrachtverkeer en meestal ook bussen|
|Klimstrook |	Strook waarbij trager rijdend verkeer (zoals vrachtwagens) en het overige sneller rijdende verkeer gescheiden wordt bij het beklimmen van een heuvel of berg|
|Busstrook	|Strook waar alleen bussen (hulpdiensten en trams) mogen rijden|
|Fietsstrook |	Strookdie uitsluitend voor fietsers is gereserveerd met fietssymbool|
|Fietssuggestiestrook |	Strook die voor fietsers is gereserveerd zonder fietssymbool|
|Voetgangersstrook	|Strook bestemd voor voetgangers als onderdeel van een baan|


*Type rijrichting*

|Waarde rijrichting|Beschrijving|
|---|---|
|Beide	|Beide rijrichtingen zijn op de verbinding toegestaan|
|Eenrichting	|Eén rijrichting is op verbinding toegestaan|

Toelichting: Voor het concreet aangeven van de richting van de eenrichtings-rijrichting zullen op een later moment inwinningsregels worden vastgelegd.

*openbare weg*

|Waarde Openbare weg|Beschrijving|
|---|---|
|Ja|In de vastgestelde wegenlegger benoemde weg, waar geen beperking in het gebruik geldt|
|Nee|In de vastgestelde wegenlegger benoemde weg, waar een beperking in gebruik geldt.|


*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd


#### Spoorweg



**SPOORWEGKNOOP**

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Spoorverkeerruimte"


**Definitie**

| Naam  | Spoorwegknoop  |
|---|---|
| Definitie | Spoorverkeerruimte die een begin-, eind- of keuzepunt voor de spoorgebruiker is |
| Herkomst definitie  | nieuw     |
| Verplicht  | Ja  |
| Gevolgen afbakening||
| Toelichting| Gebaseerd op conceptueel model netwerken |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een spoorwegknoop|Ja |
|Geometrie |Geometrische representatie van een spoorwegknoop|Ja (punt)|
|Type	|Aanduiding van het soort spoor|	Ja|
|Status   |De fase van de levenscyclus waarin een spoorwegknoop zich bevindt|Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| ligt aan 1 of meer | gerelateerde spoorwegverbinding(en) |Ja|
| ligt op | gerelateerde reële object | Ja|
| hyperverbinding| gerelateerde functionele zone | Ja|

**Domeinwaarden**

*Type*

|Waarde type spoor| Beschrijving|
|---|---|
|Nationaal spoor	|Landelijk spoornetwerk waarmee (inter-)nationaal vervoer van personen en goederen mogelijk is|
|Lokaal spoor	|Gesloten spoornetwerk bedoeld voor en beperkt tot stedelijk/regionaal vervoer van personen|



*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd



**SPOORVERBINDING**

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Spoorverkeerruimte"

**Definitie**

| Naam  | Spoorverbinding  |
|---|---|
| Definitie | Spoorverkeerruimte die  de verkeerskundige inrichting van een spoor tussen twee knopen betreft|
|Herkomst definitie  | nieuw    |
|Verplicht  | Ja  |
|Gevolgen afbakening|Het betreft hier grotendeels de bestaande populatie spoor zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Gebaseerd op conceptueel model netwerken. |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een spoorverbinding|Ja |
|Geometrie |Geometrische representatie van een spoorverbinding|Ja (lijn)|
|Type	|Aanduiding van het soort spoor|Ja|
|Status   |De fase van de levenscyclus waarin een spoorverbinding zich bevindt|Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
| hoort bij 1 of 2 | Gerelateerde kno(o)p(en) |ja|
| ligt op | gerelateerde reële object| ja|
| hyperverbinding | gerelateerde functionele zone | Ja|

**Domeinwaarden**

*Type*

|Waarde type spoor| Beschrijving|
|---|---|
|Nationaal spoor	|Landelijk spoornetwerk waarmee (inter-)nationaal vervoer van personen en goederen mogelijk is|
|Lokaal spoor	|Gesloten spoornetwerk bedoeld voor en beperkt tot stedelijk/regionaal vervoer van personen|



*Status* 

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd




### Functionele gebouwobjecten

#### Verblijfsobject


Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte "


**Definitie**

| Naam  | Verblijfsobject |
|---|---|
| Definitie | Kleinste binnen één of meer gebouwen gelegen eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, en die onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is|
|Herkomst definitie|Gebaseerd op definitie “verblijfsobject” in artikel 1 Wet basisregistratie adressen en gebouwen |
|Verplicht  | Ja |
|Gevolgen afbakening  | Het betreft hier in principe de bestaande populatie verblijfsobjecten zoals deze is opgenomen in de basisregistratie adressen en gebouwen |
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan verblijfsobject moet worden gegeven |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een verblijfsobject  |Ja |
|Geometrie |Geometrische representatie van een verblijfsobject  |Ja (2,5D)|
|Gebruiksdoel|Categorisering van de gebruiksdoelen van een verblijfsobject zoals in de vergunning is opgenomen of bij constatering is vastgesteld|Ja|
|Feitelijk gebruik|Categorisering van het feitelijke gebruik dat van een verblijfsobject wordt gemaakt|Ja|
|Gebruiksoppervlakte|Gebruiksoppervlakte van een verblijfsobject |Ja|
|Status   |Fase van de levenscyclus waarin een verblijfsobject zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij 1 of meer|Gebouw| Ja |
|Heeft een |Nummeraanduiding| Ja |

**Domeinwaarden**

*Gebruiksdoel*

|Waarde gebruiksdoel|	Beschrijving|
|---|---|
|Woonfunctie|	Gebruiksfunctie voor het wonen|
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

De definitieve lijst met gebruiksfuncties zal op een later moment nog definitief worden afgestemd op de begrippen in bijlage I van het besluit bouwwerken leefomgeving (Omgevingswet)



*Feitelijk gebruik*

| Waarde Feitelijk gebruik| Beschrijving   |
|---|---|
|   |   |
|   |   |


*Gebruiksoppervlakte*

Voor de berekening van de gebruiksoppervlakte wordt gebruik gemaakt van NEN 2580


*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.

De status “in gebruik (niet ingemeten)” keert in de SOR niet als een afzonderlijke status terug. De mate waarin sprake is van definitieve geometrie zal door middel van meta-informatie bij de eigenschap geometrie worden vastgelegd

#### Gebouwzone

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte "

**Definitie**

| Naam  | Gebouwzone |
|---|---|
| Definitie | Grootst mogelijke gedeelte van een gebouw dat in zijn geheel is gelegen op een bouwlaag en binnen de afbakening van een gebouw en een verblijfsobject, waaraan eenduidig een bouwjaar kan worden toegekend, en dat qua constructie en gebruiksmogelijkheden voldoende uniform is|
|Herkomst definitie|Begrip gebaseerd op de functionele deelobjecten uit de WOZ en aansluitend bij het begrip Zonering (IfcZone) uit de concepten rondom Bouwwerkinformatiemodellen (BIM), waarbij ruimten worden gezoneerd tot bijvoorbeeld verblijfsobject of gebouwzone |
|Verplicht  | Ja |
|Gevolgen afbakening  | Het betreft hier ten opzichte van de bestaande basisregistraties grotendeels een nieuw objecttype |
|Toelichting| In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan gebouwzone moet worden gegeven |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een gebouwzone  |Ja |
|Geometrie |Geometrische representatie van een gebouwzone   |Ja (2,5D)|
|Geometrie oppervlakte| Geometrische representatie van de oppervlakte van een gebouwzone die betrokken wordt in de berekening van de gebruiksoppervlakte|Nee (2D)|
|Bouwlaagnummer|Bouwlaag waarop een gebouwzone is gelegen|Ja|
|Bouwjaar|Aanduiding van het jaar waarin een gebouwzone is ontstaan|Ja|
|Type|Categorisering van het feitelijke gebruik dat van een gebouwzone wordt gemaakt|Ja|
|Aard|Aanduiding van de fysieke constructie waarin een gebouwzone zich bevindt|Ja|
|Gebruiksopppervlakte|Gebruiksoppervlakte van een gebouwzone|Ja|
|Status   |Fase van de levenscyclus waarin een gebouwzone zich bevindt   |Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|Hoort bij|gebouwzone| verblijfsobject|
|Ligt op |gebouwzone|Bouwlaag|

**Domeinwaarden**

*Bouwlaagnummer*

Voor de nummering van de bouwlaag geldt:
-	kelder = bouwlaagnummer -1
-	begane grond = bouwlaagnummer 0
-	eerste verdieping = bouwlaagnummer 1
-	tweede verdieping = bouwlaagnummer 2


*Type* 

| Waarde Type| Beschrijving   |
|---|---|
|   |   |
|   |   |


*Aard*

| Waarde Aard| Beschrijving   |
|---|---|
|Basisconstructie |Gebouwzone is een nader type van de oorspronkelijke constructie van het gebouw waarin de gebouwzone is gelegen|
|Uitbouw |Gebouwzone betreft een later aanbouw (niet zijnde een serre) of opbouw ten opzichte van de oorspronkelijke constructie van het gebouw waarin de gebouwzone is gelegen|
|Serre |Gebouwzone betreft een serre die al dan geen onderdeel uitmaakt van de oorspronkelijke constructie van het gebouw waarin de gebouwzone is gelegen|


*Gebruiksoppervlakte*

Voor de berekening van de gebruiksoppervlakte wordt gebruik gemaakt van NEN 2580

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd. De mate waarin alle genoemde statussen ook daadwerkelijk verplicht zullen worden en de regels omtrent interpretatie en overgang van statussen zullen in een later stadium nog gedetailleerder worden uitgewerkt in registratieregels.



### Functionele zoneringen


#### Verkeerskundig functionele zone

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte"

**Definitie**

| Naam  | Verkeerskundig functionele zone |
|---|---|
| Definitie | Functionele ruimte die een verkeerskundige functie kent|
|Herkomst definitie  | nieuw |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier deels de bestaande populaties van de verschillende typeringen zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een verkeerskundig functionele zone|Ja |
|Geometrie |Geometrische representatie van een verkeerskundig functionele zone|Ja (2D vlak)|
|Type |Typering van een verkeerskundig functionele zones| Ja|
|Naam|Breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Status   |De fase van de levenscyclus waarin een verkeerskundig functionele zone zich bevindt|Ja  |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hyperverbinding |wegverbinding |ja|
|hyperverbinding |wegknoop |ja|

**Domeinwaarden**


*Type* 

|Waarde type|	Beschrijving|
|---|---|
| Inrit| Geeft toegang tot een bestemmingsdoel|
| Parkeervlak | Parkeergelegenheid bestemd voor het parkeren van één of meerdere voertuigen direct langs de doorgaande weg gelegen|
|Parkeerplaats | Parkeergelegenheid voor het parkeren van meerdere voertuigen in de openlucht met een aparte toegang vanaf de doorgaande weg|
| Verzorgingsplaats |  Langs de weg gelegen parkeergelegenheid, met inbegrip van de daarbij behorende verharde en onverharde banen en een of meer voorzieningen ten behoeve van reizigers en/of voertuigen|
| Tankstation |  Geheel van installaties, verharding en gebouwen bedoeld voor de verkoop van brandstoffen of energie voor voertuigen |
| Snellaadstation |  Infrastructuurelement, doorgaans langs autosnelwegen, dat in elektrische energie voorziet om elektrische plug-invoertuigen op te laden in een relatief korte tijd|
|Overstapplaats	|Voorziening waar men kan overstappen tussen modaliteiten of netwerken|
|Tolplaats	| Geheel van installaties, verharding en gebouwen waar betaald moet worden voor toegang tot de weg|
| Halteplaats | Het geheel van voorzieningen bedoeld als stopplaats voor voertuigen van het openbaar vervoer|
| Woonerf |Wegdeel waar de verblijfsfunctie (lopen, spelen, ontmoeten enzovoorts) prioriteit heeft boven de verkeersfunctie | 

Toelichting: Nog bekeken wordt hoe snellaadstation als een subtype van tankstation gepositioneerd wordt.


*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd

#### Wegzone

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte"

**Definitie**

| Naam  | Wegzone  |
|---|---|
| Definitie | Functionele ruimte die in gebruik is voor weginrichting|
|Herkomst definitie  | nieuw |
|Verplicht  | Ja (deels)  |
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type wegzones zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van Wegzone|Ja |
|Geometrie |Geometrische representatie van een wegzone|Ja (2D vlak) |
|Type | Typering van een wegzones| Ja|
|Status   |De fase van de levenscyclus waarin een wegzone zich bevindt|Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hyperverbinding |wegverbinding |ja|
|hyperverbinding |wegknoop |ja|


**Domeinwaarden**


*Type*

|Waarde type	|Beschrijving|
|---|---|
| Verkeerseiland | Weggedeelte van beperkte omvang, uitgevoerd als een verhoging of wegmarkering, dat wordt omsloten door rijbanen of rijstroken en als doel heeft verkeersstromen te scheiden|
| Berm | Strook grond langs een weg of spoorweg bedoeld voor het uitwijken van voertuigen, het scheiden van verkeerstromen, het plaatsen van verkeersondersteunend meubiliar, afwatering en/of het verbinden van zones met ecologische infrastructurele waarden|
| Verkeersdrempel | Verhoging in een regionale rijbaan, bedoeld om het gemotoriseerde verkeer met een lage snelheid te laten rijden| 
| Wildrooster | Horizontaal raamwerk dat dient om wild de doorgang te beletten|

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd


#### Spoorzone

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte"

**Definitie**

| Naam  | Spoorzone |
|---|---|
| Definitie | Functionele ruimte die in gebruik is voor spoorwegen|
|Herkomst definitie  | nieuw|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type spoorzones zoals deze zijn opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van spoorzone|Ja |
|Geometrie |Geometrische representatie van een spoorzone|Ja (2D vlak) |
|Type| Typering van een spoorzone|Ja|
|Naam|Breed geaccepteerde benaming van een spoorzone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Status   |De fase van de levenscyclus waarin een spoorzone zich bevindt|Ja   |


**Relaties met andere objecttypen** 

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|hyperverbinding |wegverbinding |ja|
|hyperverbinding |spoorverbinding |ja|
|hyperverbinding |spoorknoop |ja|


**Domeinwaarden**


*Type*

| Waarde type	|Beschrijving|
|---|---|
| Perron |  Verhoogde constructie langs een (spoor)rails voor het in- en uitstappen van passagiers of voor het laden en lossen van goederen|
| Overweg | Gelijkvloerse kruising van een weg met een (spoor)rails|
| Spoorbaan | Gebaand gedeelte voor het verkeer over rails|
| Emplacement | Totaal aan sporen op een terrein ten behoeve van het rangeren en stallen van treinen|


*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd


#### Luchtvaartzone

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte"

**Definitie**

| Naam  | Luchtvaartzone |
|---|---|
| Definitie | Functionele ruimte die in gebruik is voor luchtvaart|
|Herkomst definitie  | nieuw|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populaties van de verschillende type luchtvaartzones zoals deze zijn opgenomen in de basisregistratie (grootschalige) topografie|
|Toelichting|  |


**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van Luchtvaartzone|Ja |
|Geometrie |Geometrische representatie van een luchtvaartzone|Ja (2D vlak)|
|Type| Categorisering van soort luchtvaartzone| Ja|
|Naam|Breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Status   |De fase van de levenscyclus waarin een luchtvaartzone zich bevindt|Ja   |


**Domeinwaarden**




*Type*

|Waarde type	|Beschrijving|
|---|---|
| Baan voor vliegverkeer | Baan uitsluitend bedoeld voor vliegverkeer|
| Luchthaven | Vliegveld voor verkeersvliegtuigen met groot, effen terrein met al dan niet verharde banen, waar vliegtuigen kunnen opstijgen en landen, eventueel met accommodatie voor ontvangst en vertrek van passagiers en verzending van goederen|

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd.

#### Begraafplaats

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte"

**Definitie**

| Naam  | Begraafplaats |
|---|---|
| Definitie |Besloten gebied waar lichamen van overleden personen worden begraven. Ook worden op begraafplaatsen urnen met as van gecremeerde lichamen bewaard.|
|Herkomst definitie  | IMGeo 2.2    |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier deels de bestaande populatie *begraafplaats*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een begraafplaats|Ja |
|Geometrie|Geometrische representatie van een begraafplaats|Ja (2D vlak)|
|Naam	|Breed geaccepteerde benaming van een begraafplaats zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat	|Nee|
|Status   |  De fase van de levenscyclus waarin de begraafplaats zich bevindt|Ja   |


**Domeinwaarden**


*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd

#### Recreatiezone

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte "

**Definitie**

| Naam  | Recreatiezone  |
|---|---|
| Definitie | Functionele ruimte die in gebruik is voor openlucht recreatie|
| Herkomst definitie  | IMGeo 2.2     |
| Verplicht  | Ja  |
| Gevolgen afbakening|Het betreft hier deels de bestaande populatie typen *recreatie*  zoals deze is opgenomen in de basisregistratie grootschalige topografie|
| Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een recreatiezone|Ja |
|Geometrie |Geometrische representatie van een recreatiezone|Ja (2D vlak)|
|Naam|Breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Type|Categorisering van de verschillende soorten zones|Ja| 
|Status   |De fase van de levenscyclus waarin een recreatiezone zich bevindt|Ja   |


**Domeinwaarden**



*Type*

|Waarde type | Beschrijving|
|---|---|
| 	speeltuin|Geheel van speelwerktuigen, begroeiing, verharding en gebouwen, bedoeld als speelplaats voor kinderen|
| 	park|Landschappelijk ingericht terrein, met begroeiing, verharding, water en gebouwen, bedoeld als recreatieve voorziening|
| 	sportterrein|Geheel van begroeiing, verharding en gebouwen bestemd voor sportbeoefening|
| 	camping|Geheel van begroeiing, verharding en gebouwen, bedoeld voor tijdelijk verblijf in kampeermiddel|
| 	bungalowpark|Geheel van begroeiing, verharding en gebouwen, bedoeld voor niet-permanente bewoning|
| 	volkstuin|Geheel van begroeiing, verharding en gebouwen in gebruik als particuliere tuinen die niet bij de woning liggen | 


*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd


#### Complex

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte "

**Definitie**

| Naam  | Complex  |
|---|---|
| Definitie |  Functionele ruimte die een verzameling van één of meer gebouwen, constructies, verharding, water en begroeiing betreft die samen een eenheid vormen|
|Herkomst definitie  |  nieuw   |
|Verplicht  | Ja  |
|Gevolgen afbakening||
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van Complex|Ja |
|Geometrie|Geometrische representatie van een complex|ja (2D vlak)|
|Type complex|Categorisering van de verschillende complexen|ja|
|Naam|Breed geaccepteerde benaming van een complex zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat| Nee |
|Status   | De fase van de levenscyclus waarin een complex zich bevindt|Ja   |



**Domeinwaarden**


*Type complex*

|Waarde Type complex| Beschrijving   |
|---|---|
|gemaalcomplex|Alle bij een gemaal behorend water, begroeiing, verharding en gebouwen|
|sluiscomplex|Alle bij een sluis behorend water, begroeiing, verharding en gebouwen|
|stuwcomplex|Alle bij een stuw behorend water, begroeiing, verharding en gebouwen|
|coupurecomplex|Alle bij een coupure behorende begroeiing, verharding en gebouwen|
|havencomplex|Alle bij een haven behorend water, begroeiing, verharding en gebouwen|
|zuiveringscomplex |Geheel van gebouwen, constructies, verharding en begroeiing dat ervoor zorgt dat drinkwater gezuiverd wordt|



*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd

#### Infrastructureel waterstaatswerk

**Definitie**

| Naam  | Infrastructureel waterstaatswerk |
|---|---|
| Definitie |Gebied gelegen langs en/of op oppervlaktewater, primair in gebruik en beheer voor de oppervlaktewaterhuishouding (waterafvoer, wateraanvoer en waterconservering) óf een gebied gelegen langs en/of op een waterkering|
|Herkomst definitie  ||
|Verplicht  | Nee |
|Gevolgen afbakening||
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een infrastructureel waterstaatswerk|Ja |
|Geometrie|Geometrische representatie van een infrastructureel waterstaatswerk|Ja (lijn, 2D-vlak)|
|Type |Typering van een infrastructureel waterstaatswerk |Ja|
|Status   | De fase van de levenscyclus waarin een infrastructureel waterstaatswerk zich bevindt|Ja   |

**Domeinwaarden**

*Type*

|Waarde Type | Beschrijving   | Verplicht|
|---|---|---|
|Oeverzone | Gebied op de grens van water en land waar het dynamisch samenspel van land en water plaatsvindt, lopend van waterpeil tot insteek| Ja|
|Oppervlaktewaterlichaam| Samenhangende ruimte gevormd door bodem en oevers, waar oppervlaktewater doorheen kan stromen |Nee|
|Waterbergingsgebied |Gebied, niet zijnde een oppervlaktewaterlichaam of onderdeel daarvan, dat dient ter verruiming van de bergingscapaciteit van een of meer watersystemen  |Nee|
|Golfbrekend voorland|Gebied aansluitend aan de buitenzijde van een waterkering, wat de waterkering beschermt tegen golven   |Nee|



*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd


#### Gebruiksgebied oppervlaktewater

**Definitie**

| Naam  | Gebruiksgebied oppervlaktewater |
|---|---|
| Definitie | Begrensd en benoemd oppervlaktewatergebied dat een bepaald gebruik kent.|
|Herkomst definitie  ||
|Verplicht  | Nee |
|Gevolgen afbakening||
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een gebruiksgebied oppervlaktewater|Ja |
|Geometrie|Geometrische representatie van een gebruiksgebied oppervlaktewater|Ja (lijn, 2D-vlak)|
|Type |Typering van een gebruiksgebied oppervlaktewater |Ja|
|Status   | De fase van de levenscyclus waarin een gebruiksgebied oppervlaktewater zich bevindt|Ja   |

**Domeinwaarden**

*Type*

|Waarde Type | Beschrijving   | Verplicht|
|---|---|---|
|Watersport zone| Begrensd en benoemd oppervlaktewatergebied dat gebruikt wordt voor recreatieve watersport |Nee|
|Vaarwegzone| Begrensd en benoemd oppervlaktewatergebied dat gebruikt wordt voor transport middels scheepvaart |Nee|
|Visserij zone|egrensd en benoemd oppervlaktewatergebied dat gebruikt wordt voor visserij  |Nee|

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd



#### Beheergebied oppervlaktewater

**Definitie**

| Naam  | Beheergebied oppervlaktewater |
|---|---|
| Definitie | Gebied waarin activiteiten worden uitgevoerd die tot doel hebben om het oppervlaktewater te laten voldoen aan de beoogde toestand|
|Herkomst definitie  ||
|Verplicht  | Nee |
|Gevolgen afbakening||
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een beheergebied oppervlaktewater|Ja |
|Geometrie|Geometrische representatie van een beheergebied oppervlaktewater|Ja (lijn, 2D-vlak)|
|Type |Typering van een beheergebied oppervlaktewater |Ja|
|Status   | De fase van de levenscyclus waarin een beheergebied oppervlaktewater zich bevindt|Ja   |

**Domeinwaarden**

*Type*

|Waarde Type | Beschrijving   | Verplicht|
|---|---|---|
|Beheergebied waterkwantiteit| Gebied waarin activiteiten worden uitgevoerd die tot doel hebben om de hoeveelheid oppervlaktewater te reguleren |Nee|
|Beheergebied waterkwaliteit| Gebied waarin activiteiten worden uitgevoerd die tot doel hebben om  de kwaliteit van het oppervlaktewater in orde te houden |Nee|

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd



#### Kering

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte"

 

**Definitie**

| Naam  | Kering |
|---|---|
| Definitie | Voorziening met een kerende functie|
|Herkomst definitie  |nieuw|
|Verplicht  | ja  |
|Gevolgen afbakening|Het betreft hier de bestaande populatie functioneel gebied type kering zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting| Een waterkerende en / of scheidende, kunstmatige of natuurlijke hoogte of hooggelegen gronden inclusief de daarin aanwezige waterkerende elementen.  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | Unieke aanduiding van een kering|Ja |
|Geometrie|Geometrische representatie van een kering|Ja (lijn, 2D-vlak)|
|Type kering|Typering van een kering|Ja|
|Status   | De fase van de levenscyclus waarin een kering zich bevindt|Ja   |

**Domeinwaarden**


*Kering*

|Waarde type kering| Beschrijving   |
|---|---|
|grond	|voorziening bedoeld om grond te keren|
|water	|voorziening bedoeld om water te keren|




*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd


#### Reducering

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte "

**Definitie**

| Naam  | Reducering |
|---|---|
| Definitie |Functionele ruimte die een voorziening betreft om bepaalde effecten van omgevingsfactoren te verminderen|
|Herkomst definitie  |nieuw|
|Verplicht  | ja  |
|Gevolgen afbakening|Het betreft hier de functionele vertaling van de bestaande populatie scheiding type geluidscherm zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van reducering|Ja |
|Geometrie|Geometrische representatie van de reducerende voorziening|Ja (lijn)|
|Type reducering|Categorisering van de verschillende type reducering| Ja|
|Status   | De fase van de levenscyclus waarin de reducerende voorziening zich bevindt|Ja   |

**Domeinwaarden**


*Type reducering* 

|Waarde Type reducering| Beschrijving   |
|---|---|
|geluid| Voorziening bedoeld om geluidshinder in de buitenlucht te verminderen|
|fijnstof|Voorziening bedoeld om verspreiding van fijnstof te verminderen	|



*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd


#### Valbescherming


Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte "

 

**Definitie**

| Naam  | Valbescherming |
|---|---|
| Definitie |Functionele ruimte die een voorziening betreft om vallen te voorkomen|
|Herkomst definitie  |nieuw|
|Verplicht  | nee  |
|Gevolgen afbakening| Het betreft hier de functionele vertaling van de bestaande populatie weginrichtings-element type balustrade zoals deze is opgenomen in de basisregistratie grootschalige topografie |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van valbescherming|Ja |
|Geometrie|Geometrische representatie de valbescherming|Ja (lijn)|
|Status   |  De fase van de levenscyclus waarin de valbescherming zich bevindt|Ja   |



**Domeinwaarden**



*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd


#### Afscheiding 

Dit SOR-begrip is een nader type van de NEN 3610-hoofdklasse "Functionele ruimte "


**Definitie**

| Naam  | Afscheiding |
|---|---|
| Definitie |Functionele ruimte die een voorziening betreft om terrein af te scheiden|
|Herkomst definitie  |nieuw|
|Verplicht  | nee  |
|Gevolgen afbakening|Het betreft hier de functionele vertaling van de bestaande populatie scheiding type muur, hek en raster zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van afscheiding|Ja |
|Geometrie|Geometrische representatie van de afscheiding|Ja (lijn)|
|Status   | De fase van de levenscyclus waarin de afscheiding zich bevindt|Ja   |


**Domeinwaarden**



*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van functionele ruimten zijn benoemd

