## Geografische ruimten

 <div class='note'>
    De typering is in deze fase van het traject vooral bedoeld om een eerste indruk te geven van de richting waarin de inhoud van de samenhangende objectenregistratie zich beweegt. Typeringen kunnen nog wijzigen in het nog op te stellen informatiemodel van de samenhangende objectenregistratie.
</div>

### Bebouwingskern

Dit SOR-begrip is een nader type vande NEN 3610-hoofdklasse “Geografische ruimte”

**Definitie**

| Naam  | Bebouwingskern  |
|---|---|
| Definitie |Geografische ruimte die gekenmerkt wordt door een concentratie van gebouwen   |
|Herkomst definitie  | Gebaseerd op definitie Plaats in BRT  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | In de BRT zijn al plaatsen opgenomen. Deze zijn landelijk door het Kadaster bepaald. Plaatsen worden in de vorm van bebouwingskernen ook opgenomen in de objectenregistratie|
|Toelichting| Met bebouwingskernen kan een algemeen toepasbaar onderscheid worden aangebracht tussen bebouwd gebied en het buitengebied. Tot het buitengebied kan dan worden gerekend al het gebied dat niet behoort tot een bebouwingskern, De bebouwingskern (zonder juridische status) moet niet worden verward met bebouwde kommen (die wel een juridische grondslag kennen in specifieke wetgeving). Hierbij kan worden gedacht aan de bebouwde kom in het kader van Wegenverkeerswet, Wegenwet, Wet natuurbescherming en Omgevingswet. De diversiteit in achterliggende doelstellingen van genoemde wetgeving maakt het op dit moment niet mogelijk te komen tot één uniform en breed bruikbaar begrip bebouwde kom. Deze bebouwde kommen maken dan ook geen onderdeel uit van de SOR|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een bebouwingskern  |Ja |
|Naam   |Plaatselijke naam van een bebouwingskern zoals deze als woonplaats bekend is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat  |Ja   |
|Alternatieve naam   | Alternatieve benaming van een bebouwingskern zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries) |Nee   |
|Geometrie   |Geometrische representatie van een bebouwingskern   |Ja   |
|Type |Hoofdkarakter van het gebied dat een bebouwingskern vormt |Ja |
|Status   |Fase van de levenscyclus waarin een bebouwingskern zich bevindt    |Ja   |


**Relaties met andere objecttypen**

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde gemeente | Ja |

**Domeinwaarden**

*Type* 

| Waarde  | Beschrijving Type  |
|---|---|
|Woonkern  | Van openbare wegen voorziene bebouwingskern die voor het grootste gedeelte bestaat uit gebouwen die gebruikt worden voor wonen    |
|Industriekern  |Van openbare wegen voorziene bebouwingskern die voor het grootste gedeelte bestaat uit gebouwen die gebruikt worden voor bedrijfsmatige activiteiten   |
|Recreatiekern  |Bebouwingskern die voor het grootste gedeelte bestaat uit gebouwen die gebruikt worden voor (verblijfs)recreatie  |
|Gehucht  |Kleine bebouwingskern die bestaat uit een concentratie van aaneengesloten bebouwing    |
|Buurtschap  |Lintbebouwing of verspreid staande bebouwing in landelijk gebied met een zekere mate van sociale samenhang die gezamenlijk een bebouwingskern vormen |
|Deelkern  |Ruimtelijk van omliggende bebouwing te onderscheiden historische bebouwingskern, die is gelegen binnen een andere bebouwingskern   |
|Stadsdeel |Binnen een andere bebouwingskern gelegen ruimtelijk samenhangend en van een overkoepelende naam voorzien gebied |

Toelichting:
Woonkernen, industriekernen, recreatiekernen, gehuchten en buurtschappen zijn in het buitengebied gelegen zelfstandige kernen. Deelkernen en stadsdelen zijn kernen die zich bevinden binnen de begrenzing van een andere bebouwingskern. Voor het concreet vaststellen van de typering zullen op een later moment inwinningsregels worden vastgelegd. 

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van geografische ruimten zijn benoemd.


### Streek

Dit SOR-begrip is een nader type vande NEN 3610-hoofdklasse “Geografische ruimte”

**Definitie**

| Naam  | Streek  |
|---|---|
| Definitie |Geografische ruimte die cultureel of landschappelijk een eenheid vormt |
|Herkomst definitie  | Gebaseerd op Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Streek* zoals deze is opgenomen in de basisregistratie topografie|
|Toelichting| Onder deze landstreek valt ook het open land buiten steden en dorpen (veld)|

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een streek|Ja |
|Naam   |Plaatselijke naam van het streek zoals deze formeel is vastgesteld of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat|Ja   |
|Alternatieve naam   | Alternatieve benaming van een streek zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries)|Nee   |
|Geometrie   |Geometrische representatie van een streek|Ja (vlak)  |
|Status   |Fase van de levenscyclus waarin de betreffende streek zich bevindt|Ja   |



**Domeinwaarden**

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van geografische ruimten zijn benoemd




### Duingebied

Dit SOR-begrip is een nader type vande NEN 3610-hoofdklasse “Geografische ruimte”

**Definitie**

| Naam  | Duingebied  |
|---|---|
| Definitie |Verhoging of heuvel van zand of fijne losse aarde opgeworpen door wind. Duingebieden grenzen aan zeestranden en zijn al dan niet begroeid of bebouwd of bedekt door water of wegen|
|Herkomst definitie  | Gebaseerd op Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier grotendeels de bestaande populatie *duingebied* zoals deze is opgenomen in de basisregistratie topografie|
|Toelichting| Het geografisch object Duingebied omvat uiteenlopende reële objecten water, begroeiing, verharding, constructies en bodem. Het geografisch object Duingebied is opgenomen, omdat deze voorziet in een specifieke informatiebehoefte.  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een duingebied|Ja |
|Naam   |Plaatselijke naam van het duingebied zoals deze formeel is vastgesteld of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat|Ja   |
|Alternatieve naam   | Alternatieve benaming van een duingebied zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries)|Nee   |
|Geometrie   |Geometrische representatie van het duingebied|Ja (vlak)  |
|Status   |Fase van delevenscyclus waarin het betreffende duingebied zich bevindt|Ja   |




**Domeinwaarden**

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van geografische ruimten zijn benoemd	


	



### Watergebied

Dit SOR-begrip is een nader type vande NEN 3610-hoofdklasse “Geografische ruimte”

**Definitie**

| Naam  | Watergebied  |
|---|---|
| Definitie |Geografische ruimte die overwegend met water bedekt is|
|Herkomst definitie  | Nieuw |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *watergebied* zoals deze is opgenomen in de basisregistratie topografie|
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een watergebied|Ja |
|Naam   |Plaatselijke naam van het watergebied zoals deze formeel is vastgesteld of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat|Ja   |
|Alternatieve naam   | Alternatieve benaming van een watergebied zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries)|Nee   |
|Geometrie   |Geometrische representatie van het watergebied|Ja (vlak)  |
|Status   |Fase van delevenscyclus waarin het betreffende watergebied zich bevindt|Ja   |




**Domeinwaarden**

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van geografische ruimten zijn benoemd	


### Eiland

Dit SOR-begrip is een nader type vande NEN 3610-hoofdklasse “Geografische ruimte”

**Definitie**

| Naam  | Eiland  |
|---|---|
| Definitie | Geografische ruimte die omgeven is door water|
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *eiland* zoals deze is opgenomen in de basisregistratie topografie|
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een eiland|Ja |
|Naam   |Plaatselijke naam van het eiland zoals deze formeel is vastgesteld of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat|Ja   |
|Alternatieve naam   | Alternatieve benaming van een eiland zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries)|Nee   |
|Geometrie   |Geometrische representatie van het eiland|Ja (vlak)  |
|Status   |Fase van delevenscyclus waarin het betreffende eiland zich bevindt|Ja   |




**Domeinwaarden**

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van geografische ruimten zijn benoemd




### Polder

Dit SOR-begrip is een nader type vande NEN 3610-hoofdklasse “Geografische ruimte”

**Definitie**

| Naam  | Polder  |
|---|---|
| Definitie |Geografische ruimte die door waterscheidingen begrensd is of waarin de waterstand kan worden beheerst door bemaling|
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Polder* zoals deze is opgenomen in de basisregistratie topografie|
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een polder|Ja |
|Naam   |Plaatselijke naam van het polder zoals deze formeel is vastgesteld of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat|Ja   |
|Alternatieve naam   | Alternatieve benaming van een polder zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries)|Nee   |
|Geometrie   |Geometrische representatie van een polder|Ja (vlak)  |
|Status   |Fase van delevenscyclus waarin de betreffende polder zich bevindt|Ja   |




**Domeinwaarden**

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van geografische ruimten zijn benoemd






### Strand

Dit SOR-begrip is een nader type vande NEN 3610-hoofdklasse “Geografische ruimte”

**Definitie**

| Naam  | Strand |
|---|---|
| Definitie | Geografische ruimte die een onbegroeide zandige kustvlakte op de overgang van zee met land is en onder invloed staat van het zeewater en de wind|
|Herkomst definitie  | IMGeo 2.2|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *strand en strandwal* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | Unieke aanduiding van strand|Ja |
|Geometrie| Geometrische representatie van een strand|Ja (vlak)|
|Status   | Fase van delevenscyclus waarin het betreffende strand zich bevindt|Ja   |




**Domeinwaarden**

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van geografische ruimten zijn benoemd





### Zandverstuiving

Dit SOR-begrip is een nader type vande NEN 3610-hoofdklasse “Geografische ruimte”

**Definitie**

| Naam  | Zandverstuiving |
|---|---|
| Definitie | Geografische ruimte die een zandige bodem is waarvan delen van het gebied zonder vegetatie zijn, door invloed van wind|
|Herkomst definitie  | IMGeo 2.2|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *zandverstuiving* zoals deze is opgenomen in de basisregistratie grootschalige topografie|
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | Unieke aanduiding van zandverstuiving|Ja |
|Geometrie| Geometrische representatie van een zandverstuiving|Ja (vlak)|
|Status   | Fase van delevenscyclus waarin de betreffende zandverstuiving zich bevindt|Ja   |




**Domeinwaarden**

*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van geografische ruimten zijn benoemd




### Reliëf 

Dit SOR-begrip is een nader type vande NEN 3610-hoofdklasse “Geografische ruimte”

**Definitie**

| Naam  | Reliëf  |
|---|---|
| Definitie | Geografische ruimte die tot doel heeft hoogteverschillen in het landschap te representeren|
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1) |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *reliëf* zoals deze is opgenomen in de basisregistratie  topografie|
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |Unieke aanduiding van een reliëf|Ja |
|Geometrie   |Geometrische representatie van het gebied dat reliëf bekend is|Ja (punt,vlak)  |
|Type |Hoofdkarakter van het reliëf|Nee |
|Status   |Fase van delevenscyclus waarin het betreffende reliëf zich bevindt|Ja   |



**Domeinwaarden**

*Type* 

| waarde | Beschrijving Type  |
|---|---|
|terp|Verhoging in het landschap oorspronkelijk bedoelt om de daarop gevestigde bebouwing te beschermen tegen het water| 
|grafheuvel|Voorhistorische begraafplaats in de vorm van een heuvel|
|wal|Langgerekte ophoging in het terrein met een hoogte tussen 0,50 en 1,00 meter| 
|steile rand|Steile rand in het terrein, ontstaan door het afspoelen van materiaal vanaf een helling|
|holle weg|Weg die zo diep is uitgesleten dat hij tussen twee hellingen ligt als gevolg van eeuwenlang gebruik en erosie|
|groeve|Opengegraven ruimte waaruit een delfstof gewonnen wordt|
|berg|Min of meer op zichzelf staande sterke verheffing van het aardoppervlak|
|dal|Langgerekte laagte, inzinking of verdieping in het landschap tussen bergen, heuvels of hoogvlakten|



*Status*

Deze eigenschap kan alle waarden aannemen die bij de [levensfase](#levensfasen) van geografische ruimten zijn benoemd

