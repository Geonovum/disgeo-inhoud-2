## Transponering

In dit hoofdstuk wordt aangegeven hoe elementen uit de huidige basisregistraties als begrip terugkomen in de samenhangende objectenregistratie. 
Ook wordt aangegeven als er voor is gekozen om bepaalde elementen NIET terug te laten keren in de SOR. 
Daarnaast zijn er nog andere bronnen waarvandaan elementen in de SOR worden overgenomen. 

### BGT 

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip|
|-----------------|----------------------|-----------------|---------------|
| *Transport*                  |                               |                                     |                                                                        |
| **Wegdeel**                  | Functie:                      |                                     |                                                                        |
|                              | OV-baan                       |                                     | verkeerskundig functionele zone: type OV-baan                          |
|                              | overweg                       |                                     | spoorzone: type overweg                                                |
|                              | spoorbaan                     |                                     | spoorzone: type spoorbaan                                              |
|                              | baan voor vliegverkeer        |                                     | luchtvaartzone: type baan voor vliegverkeer                            |
|                              | rijbaan autosnelweg           |                                     | wegverbinding: type autosnelweg                                        |
|                              | rijbaan autosnelweg           | verbindingsweg                      | wegverbinding: type verbindingsbaan                                    |
|                              | rijbaan autosnelweg           | calamiteitendoorsteek               | ?                                                                      |
|                              | rijbaan autoweg               |                                     | wegverbinding: type autoweg                                            |
|                              | rijbaan autoweg               | verbindingsweg                      | wegverbinding: type verbindingsbaan                                    |
|                              | rijbaan autoweg               | calamiteitendoorsteek               | ?                                                                      |
|                              | rijbaan regionale weg         |                                     | wegverbinding: type gebiedsontsluitingsweg                             |
|                              | rijbaan regionale weg         | verbindingsweg                      | wegverbinding: type verbindingsbaan                                    |
|                              | rijbaan regionale weg         | verkeersdrempel                     | wegzone: type verkeersdrempel                                          |
|                              | rijbaan lokale weg            |                                     | wegverbinding: type erftoegangsweg                                     |
|                              | rijbaan lokale weg            | verkeersdrempel                     | wegzone: type verkeersdrempel                                          |
|                              | fietspad                      |                                     | wegverbinding: type fietspad                                           |
|                              | voetpad                       |                                     | wegverbinding: type voetpad                                            |
|                              | voetpad op trap               |                                     | wegverbinding: type voetpad                                            |
|                              | ruiterpad                     |                                     | wegverbinding: type ruiterpad                                          |
|                              | parkeervlak                   |                                     | verkeerskundig functionele zone: type parkeervlak                      |
|                              | voetgangersgebied             |                                     | vervalt                                                                |
|                              | inrit                         |                                     | verkeerskundig functionele zone: type inrit                            |
|                              | woonerf                       |                                     | vervalt, wordt vervangen door netwerk en eigenschappen van het netwerk |
| **Wegdeel**                  | Fysiek voorkomen:             |                                     |                                                                        |
|                              | gesloten verharding           | asfalt                              | asfaltverharding                                                       |
|                              |                               | cementbeton                         | betonverharding                                                        |
|                              | open verharding               | betonstraatstenen                   | elementenverharding                                                    |
|                              |                               | gebakken klinkers                   | elementenverharding                                                    |
|                              |                               | tegels                              | elementenverharding                                                    |
|                              |                               | sierbestrating                      | elementenverharding                                                    |
|                              |                               | beton element                       | elementenverharding                                                    |
|                              | half verhard                  | grasklinkers                        | halfverharding                                                         |
|                              |                               | schelpen                            | halfverharding                                                         |
|                              |                               | puin                                | halfverharding                                                         |
|                              |                               | grind                               | halfverharding                                                         |
|                              |                               | gravel                              | halfverharding                                                         |
|                              | onverhard                     | boomschors                          | onverhard of onbegroeide grond?                                        |
|                              |                               | zand                                | onverhard of onbegroeide grond?                                        |
|      |     |      |     |
| **Ondersteunend wegdeel**    | Functie:                      |                                     |                                                                        |
|                              | verkeerseiland                |                                     | wegzone: type verkeerseiland                                           |
|                              | berm                          |                                     | wegzone: type berm                                                     |
| **Ondersteunend wegdeel**    | Fysiek voorkomen:             |                                     |                                                                        |
|                              | gesloten verharding           | asfalt                              | asfaltverharding                                                       |
|                              |                               | cementbeton                         | betonverharding                                                        |
|                              | open verharding               | betonstraatstenen                   | elementenverharding                                                    |
|                              |                               | gebakken klinkers                   | elementenverharding                                                    |
|                              |                               | tegels                              | elementenverharding                                                    |
|                              |                               | sierbestrating                      | elementenverharding                                                    |
|                              |                               | beton element                       | elementenverharding                                                    |
|                              | half verhard                  | grasklinkers                        | halfverharding                                                         |
|                              |                               | schelpen                            | halfverharding                                                         |
|                              |                               | puin                                | halfverharding                                                         |
|                              |                               | grind                               | halfverharding                                                         |
|                              |                               | gravel                              | halfverharding                                                         |
|                              | onverhard                     | boomschors                          | onverhard of onbegroeide grond                                         |
|                              |                               | zand                                | onverhard of onbegroeide grond                                         |
|                              | groenvoorziening              | bosplantsoen                        | struiken                                                               |
|                              |                               | gras- en kruidachtigen              | gras- en kruidachtigen                                                 |
|                              |                               | planten                             | struiken                                                               |
|                              |                               | struikrozen                         | struiken                                                               |
|                              |                               | heesters                            | struiken                                                               |
|                              |                               | bodembedekkers                      | struiken                                                               |
|      |     |      |     |
| **Spoor**                    | Functie:                      |                                     |                                                                        |
|                              | trein                         |                                     | spoorweg: type spoorverbinding                                         |
|                              | sneltram                      |                                     | spoorweg: type spoorverbinding                                         |
|                              | tram                          |                                     | spoorweg: type spoorverbinding                                         |
|                              | Niet BGT                      | (haven)kraan                        | ?                                                                      |

.

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip|
|-----------------|----------------------|-----------------|---------------|
| *Terrein*                    |                               |                                     |                                                     |
| **Onbegroeid terreindeel**   | Fysiek voorkomen:             |                                     |                                                     |
|                              | erf                           |                                     | onbepaald terreindeel                               |
|                              | gesloten verharding           | asfalt                              | asfaltverharding                                    |
|                              |                               | cementbeton                         | betonverharding                                     |
|                              |                               | kunststof                           | kunststofverharding                                 |
|                              | open verharding               | betonstraatstenen                   | elementenverharding                                 |
|                              |                               | gebakken klinkers                   | elementenverharding                                 |
|                              |                               | tegels                              | elementenverharding                                 |
|                              |                               | sierbestrating                      | elementenverharding                                 |
|                              |                               | beton element                       | elementenverharding                                 |
|                              | half verhard                  | grasklinkers                        | halfverharding                                      |
|                              |                               | schelpen                            | halfverharding                                      |
|                              |                               | puin                                | halfverharding                                      |
|                              |                               | grind                               | halfverharding                                      |
|                              |                               | gravel                              | halfverharding                                      |
|                              | onverhard                     | boomschors                          | onverhard of onbegroeide grond                      |
|                              |                               | zand                                | onverhard of onbegroeide grond                      |
|                              | zand                          | strand en strandwal                 | geografisch object: type strand                     |
|                              |                               | zandverstuiving                     | geografisch object: type zandverstuiving            |
|                              |                               |                                     |                                                     |
| **Begroeid terreindeel**     | Fysiek voorkomen:             |                                     |                                                     |
|                              | loofbos                       | griend en hakhout                   | bos: type loofbos                                   |
|                              | gemengd bos                   |                                     | bos: type gemengd bos                               |
|                              | naaldbos                      |                                     | bos: type naaldbos                                  |
|                              | heide                         |                                     | heide                                               |
|                              | struiken                      |                                     | struiken                                            |
|                              | houtwal                       |                                     | houtsingel                                          |
|                              | duin                          | open duinvegetatie                  | duin                                                |
|                              |                               | gesloten duinvegetatie              | duin                                                |
|                              | grasland overig               |                                     | gras- en kruidachtigen                              |
|                              | moeras                        |                                     | moeras                                              |
|                              | rietland                      |                                     | rietland                                            |
|                              | kwelder                       |                                     | getijdengebied: type schor                          |
|                              | fruitteelt                    | laagstam boomgaarden                | fruit- en kweekboom                                 |
|                              |                               | hoogstam boomgaarden                | fruit- en kweekboom                                 |
|                              |                               | wijngaarden                         | fruit- en kweekboom                                 |
|                              |                               | klein fruit                         | fruit- en kweekboom                                 |
|                              | boomteelt                     |                                     | fruit- en kweekboom                                 |
|                              | bouwland                      | akkerbouw                           | gewas                                               |
|                              |                               | braakliggend                        | gewas                                               |
|                              |                               | vollegrondsteelt                    | gewas                                               |
|                              |                               | bollenteelt                         | gewas                                               |
|                              | grasland agrarisch            |                                     | gras- en kruidachtigen                              |
|                              | groenvoorziening              | bosplantsoen                        | struiken                                            |
|                              |                               | gras- en kruidachtigen              | gras- en kruidachtigen                              |
|                              |                               | planten                             | struiken                                            |
|                              |                               | struikrozen                         | struiken                                            |
|                              |                               | heesters                            | struiken                                            |
|                              |                               | bodembedekkers                      | struiken                                            |

.

|Object|BGT classificatie (verplicht)|Plus classificatie (optioneel)|SOR-begrip|
|-----------------|----------------------|-----------------|---------------|
| *Water*                      |                               |                                     |                                                          |
| **Waterdeel**                | Type:                         |                                     |                                                          |
|                              | zee                           |                                     | watervlakte: type zee                                    |
|                              | waterloop                     | rivier                              | waterloop: type rivier                                   |
|                              |                               | sloot                               | waterloop: type sloot                                    |
|                              |                               | kanaal                              | waterloop: type kanaal                                   |
|                              |                               | beek                                | waterloop: type beek                                     |
|                              |                               | gracht                              | waterloop: type gracht                                   |
|                              |                               | bron                                | bron                                                     |
|                              | watervlakte                   | haven                               | functionele zone: havencomplex : aanleg en overslag      |
|                              |                               | meer, plas, ven, vijver             | watervlakte: type meer, type plas, type ven, type vijver |
|                              | greppel/droge sloot           |                                     | vervalt, wordt eigenschap bij waterloop                  |
|  |  |  |  |
| **Ondersteunend waterdeel**  | oever/slootkant               |                                     | oever                                                    |
|                              | slik                          |                                     | getijdengebied: type slik                                |



### BAG

|BAG object | SOR object|
|---|---|
|woonplaats	|registratief object; woonplaats|
|openbare ruimte|	registratief object; openbare ruimte|
|nummeraanduiding|	registratief object; nummeraanduiding|
|pand	|fysiek object; gebouw|
|ligplaats|	registratief object; benoemde plaats|
|standplaats|	registratief object; benoemde plaats|
|verblijfsobject|	functioneel object; verblijfsobject|


### BRT
populieren zoals nu in de BRT worden in de SOR niet apart onderscheiden, maar vallen bijvoorbeeld onder loofbos

### Nieuw in de SOR
Nieuw in de SOR gezien vanuit de BGT en BAG:

**Reële objecttypen:**

- Onbegroeide grond
- Bomenrij
- Gebouw
- Bouwlaag
- Ruimte
- Gebouwcomponent: dakkapel
- Toegangsdeur
- Openbouwwerk: parkeergarage
- Kunstwerkdeel: sluisdeur’
- Kunstwerkdeel: kolk
- Kerende kunstwerken: schot
- Kerende kunstwerken: dijk
- Scherm
- Installatie: lift
- Installatie: oplaadpunt
- Kast: pakketautomaat

**Functionele objecttypen:**

- Transportvoorzieningen: weg
- Transportvoorzieningen: spoorweg
- Transportvoorzieningen: vaarweg
- Transportvoorzieningen: watersysteem
- Gebouwzone
- Verkeerskundig functionele zone: transferium
- Verkeerskundig functionele zone: snellaadstation
- Verkeerskundig functionele zone: zone
- Spoorzone: emplacement
- Luchtvaartzone: luchthaven
- Complex
- Reducering
- Valbescherming
- Afscheiding

**Registratieve objecttypen:**

- Rijk
- Provincie
- Waterschap
- Gemeente
- Nederlandse territoriale zee
- Nederlandse aansluitende zone
- Nederlandse exclusieve economische zone
- Wijk
- Buurt

**Geografische objecttypen:**

- Bebouwde kom
- Streek
- Bosgebied
- Duingebied
- Heidegebied
- Watergebied
- Eiland
- Polder
- Relief



### Niet opnemen in SOR

Voorstel om de volgende, in BGT|IMGeo 2.2 opgenomen typeringen, niet meer op te nemen in de SOR: 
-	fauna voorziening
-	bedrijvigheid
-	natuur en landschap
-	landbouw
-	bewoning
-	infrastructuur verkeer en vervoer
-   opstelpunt open water
- zuiveringscomplex 
- waterwingebied
- waterbergingsgebied
-	infrastructuur waterstaatswerken
-	waterbergingsgebied
-	maatschappelijke en/of publieksvoorziening
-	functioneel beheer
-	functioneel beheer: hondenuitlaatplaats
-	drinkbak
-	detectielus
-	hoogtemerk
-	molgoot
-	wegmarkering
-	rooster
-	boomspiegel
-	stadsdeel

-	kruinlijn
-	op talud




