## Geografische objecttypen

### Bebouwde kom
| klasse  | naam  |
|---|---|
|SOR-begrip   | bebouwde kom  |
| onderdeel van NEN3610-objecttype |geografisch object  |

**Definitie**

| Naam  | Bebouwde kom  |
|---|---|
| Definitie | Een geografisch gebied gekenmerkt door een concentratie van gebouwen gebruikt voor wonen en werken  |
|Herkomst definitie  | Gebaseerd op definitie Plaats in BRT  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Bebouwde kom is op dit moment nog geen onderdeel van een basisregistratie. Wel zijn in de BRT plaatsen opgenomen. Deze zijn landelijk door het Kadaster bepaald. Door de opname van bebouwde kom in de objectenregistratie ontstaat een formele vastlegging van een algemeen bruikbare bebouwde kom.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een bebouwde kom  |Ja |
|Naam   |De plaatselijke naam van de bebouwde kom zoals deze als woonplaats bekend is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een bebouwde kom zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van het gebied dat als bebouwde kom is aangewezen  |Ja   |
|Type |Het hoofdkarakter van het gebied dat de bebouwde kom vormt |Ja |
|Status   |De fase van de levenscyclus waarin de betreffende bebouwde kom zich bevindt    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |

**Relaties met andere objecten**

|Relatiesoort   |Relatierol |Verplicht|
|---|---|---|
|ligt in   |Gerelateerde gemeente | Ja |

**Domeinwaarden**

| Waarde  | Beschrijving Type  |
|---|---|
|Woonkern  | Bebouwingskern met hoofdzakelijk een woonfunctie    |
|Industriekern  |Bebouwingskern met hoofdzakelijk een bedrijfsmatige functie voorzien van openbare wegen   |
|Recreatiekern  |Bebouwingskern met hoofdzakelijk een (verblijfs)recreatieve functie |
|Gehucht  |Kleine bebouwingskern of concentratie van aaneengesloten bebouwing, niet zijnde lintbebouwing   |
|Buurtschap  |Lintbebouwing of verspreid staande bebouwing in landelijk gebied met een zekere mate van sociale samenhang  |
|deelkern  |Historische bebouwingskern, ruimtelijk te onderscheiden van de omliggende bebouwing, gelegen binnen een andere bebouwde kom     |

*status*

| Waarde  | Beschrijving Status  |
|---|---|
| Aangewezen| Bebouwde kom is in gebruik |
| Ingetrokken | Bebouwde kom wordt niet langer als zodanig onderscheiden|

### Strand
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Strand |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Strand |
|---|---|
| Definitie | Onbegroeide zandige kustvlakte op de overgang van zee met land. Staat onder invloed van het zeewater en de wind. |
|Herkomst definitie  | IMGeo 2.2|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *strand en strandwal* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | De unieke aanduiding van strand. |Ja |
|Geometrie| De geometrische representatie van de randen van een strand. |Ja (vlak)|
|Status   | De fase van de levenscyclus waarin het betreffende strand zich bevindt.  |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	


### Duin
| klasse  | naam  |
|---|---|
| SOR-begrip   | Duin  |
| onderdeel van NEN3610-objecttype |geografisch object  |

**Definitie**

| Naam  | Duin  |
|---|---|
| Definitie | Verhoging of heuvel van zand of fijne losse aarde en verpulverd gesteente opgeworpen door wind of door stromend water. |
|Herkomst definitie  | BGT 1.2 |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *duin* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een duin.  |Ja |
|Naam   |De plaatselijke naam van het duingebied zoals deze als openbare ruimte benoemd is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een duingebied zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van het gebied dat duin bekend is.  |Ja (vlak)  |
|Type |Het hoofdkarakter van het duingebied. |Nee |
|Status   |De fase van de levenscyclus waarin het betreffende duingebied zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	

*Type*

| Waarde  | Beschrijving Type  |
|---|---|
|open duinvegetatie|Duin met een overwegend grasachtige vegetatie.|
|gesloten duinvegetatie|Duin met een overwegend opgaande vegetatie van struiken en of bomen.|


### Zandverstuiving
| Klasse  | Naam  |
|---|---|
| SOR-begrip   | Zandverstuiving |
| Onderdeel van NEN3610-objecttype | Functioneel object  |

**Definitie**

| Naam  | Zandverstuiving |
|---|---|
| Definitie | Een gebied met zandige bodem waarvan delen van het gebied zonder vegetatie zijn, door invloed van wind. |
|Herkomst definitie  | IMGeo 2.2|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *zandverstuiving* zoals deze is opgenomen in de basisregistratie grootschalige topografie.  |
|Toelichting|  |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   | De unieke aanduiding van zandverstuiving. |Ja |
|Geometrie| De geometrische representatie van de randen van een zandverstuiving. |Ja (vlak)|
|Status   | De fase van de levenscyclus waarin de betreffende zandverstuiving zich bevindt.  |Ja   |
| Overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   | *ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	




### Reliëf object
| klasse  | naam  |
|---|---|
| SOR-begrip   | Reliëf  |
| onderdeel van NEN3610-objecttype |geografisch object  |

**Definitie**

| Naam  | Reliëf  |
|---|---|
| Definitie |  |
|Herkomst definitie  |  |
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *reliëf* zoals deze is opgenomen in de basisregistratie  topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een reliëf.  |Ja |
|Geometrie   |De geometrische representatie van de randen van het gebied dat reliëf bekend is.  |Ja (punt,vlak)  |
|Type |Het hoofdkarakter van het reliëf. |Nee |
|Status   |De fase van de levenscyclus waarin het betreffende reliëf zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |



**Domeinwaarden**

| Waarde  | Beschrijving Type  |
|---|---|


*status*

| Waarde  | Beschrijving Status  |
|---|---|
|||




### Geografische objecttypen uit de BRT

<div class='note'>
    Geografische objecttypen uit de BRT worden op later moment toegevoegd.
</div>


### Bosgebied
| klasse  | naam  |
|---|---|
| SOR-begrip   | Bosgebied  |
| Onderdeel van NEN3610-objecttype |Geografisch object  |

**Definitie**

| Naam  | Bosgebied  |
|---|---|
| Definitie | Met bos begroeid gebied.|
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *bosgebied* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een bosgebied.  |Ja |
|Naam   |De plaatselijke naam van het bosgebied zoals deze als openbare ruimte benoemd is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een bosgebied zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van het bosgebied.  |Ja (vlak)  |
|Status   |De fase van de levenscyclus waarin het betreffende bosgebied zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	




### Duingebied
| klasse  | naam  |
|---|---|
| SOR-begrip   | Duingebied  |
| Onderdeel van NEN3610-objecttype |Geografisch object  |

**Definitie**

| Naam  | Duingebied  |
|---|---|
| Definitie |Heuvels van fijn zand, al dan niet begroeid met helmgras en struiken. |
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *duingebied* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een duingebied.  |Ja |
|Naam   |De plaatselijke naam van het duingebied zoals deze als openbare ruimte benoemd is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een duingebied zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van het duingebied.  |Ja (vlak)  |
|Status   |De fase van de levenscyclus waarin het betreffende duingebied zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	


### Eiland
| klasse  | naam  |
|---|---|
| SOR-begrip   | Eiland  |
| Onderdeel van NEN3610-objecttype |Geografisch object  |

**Definitie**

| Naam  | Eiland  |
|---|---|
| Definitie | Land, omgeven door water.|
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *eiland* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een eiland.  |Ja |
|Naam   |De plaatselijke naam van het eiland zoals deze als openbare ruimte benoemd is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een eiland zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van het eiland.  |Ja (vlak)  |
|Status   |De fase van de levenscyclus waarin het betreffende eiland zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	



### Heidegebied
| klasse  | naam  |
|---|---|
| SOR-begrip   | Heidegebied  |
| Onderdeel van NEN3610-objecttype |Geografisch object  |

**Definitie**

| Naam  | Heidegebied  |
|---|---|
| Definitie | Met heide begroeid gebied.|
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *heidegebied* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een heidegebied.  |Ja |
|Naam   |De plaatselijke naam van het heidegebied zoals deze als openbare ruimte benoemd is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een heidegebied zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van het heidegebied.  |Ja (vlak)  |
|Status   |De fase van de levenscyclus waarin het betreffende heidegebied zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	


### Berg
| klasse  | naam  |
|---|---|
| SOR-begrip   | Berg  |
| Onderdeel van NEN3610-objecttype |Geografisch object  |

**Definitie**

| Naam  | Berg  |
|---|---|
| Definitie | Verhoging van het terrein (heuvel). / Min of meer op zichzelf staande sterke verheffing van het aardoppervlak (berg).|
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Berg* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een berg.  |Ja |
|Naam   |De plaatselijke naam van het berg zoals deze als openbare ruimte benoemd is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een berg zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van een berg.  |Ja (vlak)  |
|Status   |De fase van de levenscyclus waarin de betreffende berg zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	


### Polder
| klasse  | naam  |
|---|---|
| SOR-begrip   | Polder  |
| Onderdeel van NEN3610-objecttype |Geografisch object  |

**Definitie**

| Naam  | Polder  |
|---|---|
| Definitie |Door waterscheidingen begrensd stuk land of gebied waarin de waterstand kan worden beheerst door bemaling. |
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Polder* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een polder.  |Ja |
|Naam   |De plaatselijke naam van het polder zoals deze als openbare ruimte benoemd is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een polder zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van een polder.  |Ja (vlak)  |
|Status   |De fase van de levenscyclus waarin de betreffende polder zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	


### Streek
| klasse  | naam  |
|---|---|
| SOR-begrip   | Streek  |
| Onderdeel van NEN3610-objecttype |Geografisch object  |

**Definitie**

| Naam  | Streek  |
|---|---|
| Definitie |Landstreek, gebied dat cultureel of landschappelijk een eenheid vormt (streek). / Het open land buiten steden en dorpen (veld). |
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *Streek* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een streek.  |Ja |
|Naam   |De plaatselijke naam van het streek zoals deze als openbare ruimte benoemd is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een streek zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van een streek.  |Ja (vlak)  |
|Status   |De fase van de levenscyclus waarin de betreffende streek zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	




### Watergebied
| klasse  | naam  |
|---|---|
| SOR-begrip   | Watergebied  |
| Onderdeel van NEN3610-objecttype |Geografisch object  |

**Definitie**

| Naam  | Watergebied  |
|---|---|
| Definitie |Een complex van meren en plassen. DEFINITIE AANPASSEN |
|Herkomst definitie  | Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)|
|Verplicht  | Ja  |
|Gevolgen afbakening  | Het betreft hier de bestaande populatie *watergebied* zoals deze is opgenomen in de basisregistratie topografie.  |
|Toelichting|   |

**Eigenschappen**

|Eigenschap   |Beschrijving   |Verplicht   |
|---|---|---|
|Identificatie   |De unieke aanduiding van een watergebied.  |Ja |
|Naam   |De plaatselijke naam van het watergebied zoals deze als openbare ruimte benoemd is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.   |Ja   |
|Alternatieve naam   | Een alternatieve benaming van een watergebied zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries). |Nee   |
|Geometrie   |De geometrische representatie van de randen van het watergebied.  |Ja (vlak)  |
|Status   |De fase van de levenscyclus waarin het betreffende watergebied zich bevindt.    |Ja   |
|overige metagegevens   |*later uitwerken op basis van kaderuitwerking meta-informatie*   |*ja*   |




**Domeinwaarden**

*status*

Bij dit object kunnen de alleen de volgende domeinwaarden worden gehanteerd zoals beschreven bij de levensfasen in dit document.

|Waarde Status| 
|---|
|Gepland|	
|Bestaand|	
|Verwijderd|	
|Niet gerealiseerd|	
|Ten onrechte opgevoerd|	

