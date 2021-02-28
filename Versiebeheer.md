# Colofon 

Deze versie van dit document is tot stand gekomen onder begeleiding van de werkgroep "inhoud van de samenhangende objectenregistratie" van DiSGeo, waar de volgende personen deel van uit hebben gemaakt:

| Naam                      | Organisatie    | 
|---------------------------|----------------|
| Koos Boersma	            | Informatiehuis Water|
| Annemiek Droogh           | Waarderingskamer |
| Stefan van Gerwen	        | Provincie Noord Brabant|
| Remco in ’t Hout	        | Rijkswaterstaat|
| Dick Krijtenburg	        | Geonovum|
| Paul Peter Kuiper         | Kadaster|
| Sandra Leijten	        | VNG Realisatie|
| Martijn Odijk             | Ministerie BZK    | 
| Marcel Rietdijk	        | VNG Realisatie |
| Eric van der Ster         | Ministerie I&W |
| Richard Witmer	        | Kadaster|

## Belangrijke opmerkingen vooraf 

Dit document beschrijft het conceptueel model voor een samenhangende objectenregistratie (SOR). De SOR is een basisregistratie waarin de basisregistratie adressen en gebouwen, de basisregistratie grootschalige topografie, de basisregistratie topografie en delen van de basisregistratie waarde onroerende zaken en delen van enkele andere registraties kunnen opgaan. Voorafgaand aan de beschrijving van het conceptueel model worden de volgende belangrijke aandachtspunten meegegeven:

**Expertvisie waarover nog geen besluitvorming heeft plaatsgevonden**

Het conceptueel model voor de SOR is nadrukkelijk een document dat is opgesteld door inhoudelijke experts en informatiemodel experts vanuit verschillende organisaties. Over de beschreven inhoud van het conceptueel model heeft nog geen enkele besluitvorming plaatsgevonden. Dat betekent dat de nu opgenomen ordening en beschrijvingen als gevolg van besluitvorming nog (ingrijpende) aanpassingen, aanscherpingen en nadere uitwerkingen kunnen ondergaan. Dit geldt in het bijzonder voor de nu opgenomen eerste indicatie van de mate waarin bepaalde gegevens verplicht in de registratie zullen worden vastgelegd. De nu opgenomen definities, waardenlijsten en aansluitingstabellen moeten dan ook niet worden gelezen als definitief of vastgesteld.


**Eindbeeld waarvan de invulling van de noodzakelijke transitie later volgt**

Het conceptueel model voor de SOR beschrijft de inhoud van de samenhangende objectenregistratie zoals deze op een termijn van enkele jaren zou moeten ontstaan. In dit document worden geen uitspraken gedaan over de wijze waarop een eventuele transitie van de bestaande registraties naar een samenhangende objectenregistratie zou kunnen worden vormgegeven. Deze is namelijk afhankelijk van de besluitvorming over de SOR en hangt bovendien samen met een eveneens benodigde transitie van de ICT-architectuur. In dat licht zijn in dit conceptueel model nu dan ook nog geen beschrijvingen opgenomen van tijdelijke objecttypen, eigenschappen of waarden die het mogelijk maken om een eventuele transitie naar de SOR op een soepele wijze te laten verlopen. Ook is het mogelijk dat in de praktijk voor een stapsgewijze transitie vanuit de huidige praktijk gekozen wordt. Om de belangrijkste verschillen met de bestaande situatie te kunnen duiden is als hulpmiddel wel een [transponering](#transponering) opgenomen.


**Samenhangende objectenregistratie die bestaat naast andere sectorale registraties**

De SOR is slechts één van de (basis)registraties die onderdeel uitmaakt van een breed gegevenslandschap. Daarvan maken naast de basisregistraties ook een groot aantal domein specifieke (sectorregistraties) en organisatie specifieke registraties (lokale registraties) onderdeel uit. De grondgedachte is dat in de SOR objecten eenduidig worden afgebakend en geregistreerd die van belang zijn voor gebruik in andere registraties in verschillende overheidsdomeinen. De eigenschappen van deze in de SOR afgebakende objecten worden nadrukkelijk niet allemaal in de SOR opgenomen. Deze blijven voornamelijk geregistreerd worden in verschillende sectorregistraties en lokale registraties (zie [aansluiting sectormodellen](#aansluiting-sectormodellen)). Omdat dezelfde objecten die in de SOR worden geregistreerd ook worden gebruikt in deze andere registraties, vervult de SOR dus vooral een brugfunctie tussen de verschillende registraties waardoor het mogelijk wordt gegevens over een object integraal te kunnen gebruiken.


**Gegevens in een informatieproduct zijn anders geordend dan in de registratie**

Het conceptueel model voor de SOR beschrijft de inhoud van de samenhangende objectenregistratie als één van de gegevensbronnen van waaruit informatieproducten voor gebruikers worden samengesteld. In het conceptueel model voor de SOR worden daarvoor een aantal begrippen gedefinieerd, worden eigenschappen die behoren bij deze begrippen beschreven en wordt aangegeven hoe de verschillende begrippen zich tot elkaar verhouden. Het conceptueel model beschrijft daarmee de eisen die er inhoudelijk worden gesteld aan het later op te stellen informatiemodel voor de registratie. Het beschrijft daarmee dus nadrukkelijk niet de inhoud van de verschillende informatieproducten die er kunnen worden geleverd op basis van in de registratie opgenomen gegevens (al dan niet in combinatie met gegevens in andere registraties). Dat voor het samenstellen van deze informatieproducten gebruik wordt gemaakt van een andere ordening van de onderliggende gegevens, zal hierbij voor hen in principe niet zichtbaar zijn (zie [model van begrippen en informatieproducten](#model-van-begrippen-en-informatieproducten)).


## Versiebeheer

Dit document is aan verandering onderhevig. Het versiebeheer van het document geeft inzicht in wijzigen en de actualiteit ervan.

| **Versie** | **Datum**      | **Status** | **Bewerking**                   | **Toelichting**                   |
|------------|----------------|------------|---------------------------------|-----------------------------------| 
| 0.1    | 16-04-2020     |  concept    | Initieel document               | Kapstok document  aangemaakt  |
| 0.4   | 4-10-2020     |  concept    | 1e opbouw              | Document met vertegenwoordigers werkveld vormgegeven |
| 0.x  |  x-3-2021  |  concept | 2e opbouw              | Document met vertegenwoordigers werkveld bijgesteld na 1e consultatie |
                           



