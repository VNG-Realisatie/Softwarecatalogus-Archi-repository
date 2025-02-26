# Vernieuwing Softwarecatalogus
Snelle toegang tot de relevante view voor de vernieuwing van de Softwarecatalogus


Report generated at: 2025-02-26  17:28:25

---
## Inhoudsopgave

* [Pakket van Eisen aanbesteding](#pakket-van-eisen-aanbesteding)
  * [Softwarecatalogus Pakket van Eisen](#softwarecatalogus-pakket-van-eisen)
  * [Toegangsbeveiliging](#toegangsbeveiliging)
  * [Gebruik](#gebruik)
  * [Beheren content en configuratie](#beheren-content-en-configuratie)
  * [Aanbod](#aanbod)
  * [Organisatie](#organisatie)
  * [Referentiearchitectuur](#referentiearchitectuur)
  * [Management informatie](#management-informatie)
  * [Data-migratie](#data-migratie)
  * [Softwarecatalogus Non-functionals](#softwarecatalogus-non-functionals)
* [Realisatie en onderhoud](#realisatie-en-onderhoud)
  * [Softwarecatalogus gebruikers en eigenaren](#softwarecatalogus-gebruikers-en-eigenaren)
  * [Softwarecatalogus component Referentiearchitectuur](#softwarecatalogus-component-referentiearchitectuur)
  * [Open Registers en -Connector technische architectuur](#open-registers-en-connector-technische-architectuur)
  * [Nextcloud geplot op Common Ground 5-lagen](#nextcloud-geplot-op-common-ground-5-lagen)
  * [Nextcloud technische architectuur](#nextcloud-technische-architectuur)

<div style="page-break-before: always;"></div>

---

## Pakket van Eisen aanbesteding

### Softwarecatalogus Pakket van Eisen

Overzicht van eisen en wensen voor vernieuwing Softwarecatalogus
<figure align="center">
  <img width="2207" src="2025-02-26_Vernieuwing_Softwarecatalogus/Softwarecatalogus_Pakket_van_Eisen.svg" alt="Softwarecatalogus Pakket van Eisen">
  <figcaption><i>Softwarecatalogus Pakket van Eisen</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="4" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="4">Softwarecatalogus website</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Leverancier (Visma Roxit)</td>
      <td><p>Aanbieders van standaard-software(pakketten) voor gemeentelijke taken. Alleen leveranciers die het convenant met VNG/KING ondertekend hebben, mogen hun gegevens in de Softwarecatalogus zetten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Open Source community</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Gemeente</td>
      <td><p>Een gemeente is een groep van woonkernen (dorpen, steden) met het bijbehorende gebied die samen worden bestuurd door een politiek apparaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Samenwerkingsverband</td>
      <td><p>Een samenwerking (of samenwerkingverband) is een juridische vorm waarin gemeenten vastleggen welke specifiek omschreven taken en bevoegdheden aan de samenwerking worden gedelegeerd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Publiek</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Aanbod- en gebruik-beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Aanbod-beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Gebruik-beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Gebruik-raadpleger</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Aanbod-raadpleger</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Geïnteresseerde organisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Ontwikkelaar</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Externe toepassing</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Softwarecatalogus beheer</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Functioneel beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Eisen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Toegangsbeveiliging</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Beheren gebruikers en rollen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Beheren content en configuratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Beheren configuratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Beheren content</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren gebruikte pakketten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Tonen statistieken gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Raadplegen gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren koppelingen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Filteren pakketoverzicht</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Exporteren</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Raadplegen aanbod API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Aanbod</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren aangeboden pakketten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Exporteren</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Raadplegen aanbod</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Organisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Beheren organisaties</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren extra organisatieinformatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Ontsluiten organisaties</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Referentiearchitectuur</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Plotten op views</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Ontsluiten architectuur concepten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Importeren ArchiMate</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Exporteren ArchiMate</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Management informatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Databasetoegang Management Informatietool</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Data-migratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Migreren data huidige SWC naar nieuwe database</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Wensen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Toegangsbeveiliging wensen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Impersonatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Beheren content en configuratie wensen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Zoeken configureren</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Startpagina doelgroep</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Aanbod en gebruik wensen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Exporteren en importeren</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren cloud-provider</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren met tabel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren en raadplegen diensten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Tonen statistieken</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Advisering op basis van AI</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Aanbod wensen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Vergelijken pakketten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Gebruik wensen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Tonen koppelingendiagram</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">AI advisering</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Review-score pakketten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Importeren externe bronnen (CMDB)</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Raadplegen gebruik API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">GT inkoop wensen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren collectieve afspraken met leveranciers</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Commen Ground wensen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Aansluiting op doelen en principes</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren softwarearchitectuur oplossing</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">IBD wensen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Delen verklaringen en overeenkomsten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Kwetsbaarheden notificatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">BIO eisen en compliancy</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Genereren van register van verwerkingen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Could have</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren aanbod API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Registreren gebruik API</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Toegangsbeveiliging

<figure align="center">
  <img width="1153" src="2025-02-26_Vernieuwing_Softwarecatalogus/Toegangsbeveiliging.svg" alt="Toegangsbeveiliging">
  <figcaption><i>Toegangsbeveiliging</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Functioneel beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Aanbod- en gebruik-beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Gemeente</td>
      <td><p>Een gemeente is een groep van woonkernen (dorpen, steden) met het bijbehorende gebied die samen worden bestuurd door een politiek apparaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Toegangsbeveiliging</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Beheren gebruikers en rollen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren gebruikers door organisatie</td>
      <td><p>Als aanbod- en gebruik-beheerder van een organisatie wil ik mijn collega's toegang kunnen geven tot de softwarecatalogus, opdat ik dit onafhankelijk van VNGR kan beheren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren gebruikers delegeren naar organisatie</td>
      <td><p>Als beheerder wil ik dat nieuwe gebruikers van bestaande organisaties zich kunnen aanmelden bij die organisatie, zodat de beheerder van de organisatie hun aanmelding kan fiatteren. Hierdoor wordt de beheerlast geminimaliseerd, wordt misbruik voorkomen, kunnen aanmeldingen snel worden verwerkt, en wordt de kwaliteit van informatie verbeterd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren rollen</td>
      <td><p>Als functioneel beheerder wil ik dat er meerdere type gebruikersrollen komen met bijbehorende rechten, zodat ieder in zijn rol de juiste werkzaamheden kan uitvoeren (zie ook informatiemodel voorzieningencatalogus).</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Gebruiker toegang tot meerdere organisaties</td>
      <td><p>Als gebruik-beheerder wil ik voor meerdere organisaties met één account de pakketoverzichten kunnen bewerken, opdat ik zonder uit -en inloggen kan schakelen tussen organisaties.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Eerste account voor organisatie</td>
      <td><p>Als functioneel beheerder wil ik het eerste (beheer)account aanmaken of fiateren voor een organisatie, opdat de relevante gebruikers de juiste toegangsrechten hebben tot de softwarecatalogus</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Gebruiksgegevens afgeschermd van aanbieders</td>
      <td><p>Als gebruik-beheerder willen we dat aanbieders van pakketten en/of diensten onze applicatielandschappen en koppelingen niet zien, om aquisitie tegen te gaan en op advies van de informatiebeveilgingsdienst.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Gebruikers gekoppeld aan organisatie</td>
      <td><p>Als functioneel beheerder wil ik dat aanbod, gebruik-beheerder en gebruik-raadpleger altijd gekoppeld zijn aan een organisatie, zodat duidelijk is  waar deze gebruiker van is. Een ongekoppelde gebruiker heeft dezelfde toegang als een bezoeker zonder gebruikersaccount.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Data-migratie</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Gebruik

<figure align="center">
  <img width="1783" src="2025-02-26_Vernieuwing_Softwarecatalogus/Gebruik.svg" alt="Gebruik">
  <figcaption><i>Gebruik</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Gebruik-beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Gebruik-raadpleger</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Gemeente</td>
      <td><p>Een gemeente is een groep van woonkernen (dorpen, steden) met het bijbehorende gebied die samen worden bestuurd door een politiek apparaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Externe toepassing</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Raadplegen gebruik API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Filteren pakketoverzicht</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Filteren pakketoverzicht</td>
      <td><p>Als gebruik-raadpleger wil ik mijn pakketoverzicht kunnen filteren op meerdere eigenschappen, zodat ik een overzichtelijk lijst heb die ik kan plotten op architectuurplaten of kan exporteren. Het filteren van producten die tot een samenwerkingsverband behoren is een expliciete wens van gemeenten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Tonen statistieken gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Tonen statistieken gebruik</td>
      <td><p>Als gebruik-raadpleger wil ik statistieken kunnen zien over mijn pakketoverzicht en hoe dit zich verhoudt tot andere gemeenten, zodat ik mijn informatievoorziening kan verbeteren. Suggesties voor statistieken zijn: aantal pakketten met einde ondersteuning, pakketoverzichten die op het mijne lijken, voortgang van de cloudtransitie, aantal sterren, etc.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Registreren gebruikte pakketten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren pakketten vanuit aanbod</td>
      <td><p>Als gebruik-beheerder wil ik geregistreerde pakketten kunnen selecteren en toevoegen aan mijn pakketoverzicht, opdat ik inzicht heb en dit kan delen met andere afnemers</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren pakketten vanuit aanbod</td>
      <td><p>Als gebruik-beheerder wil ik ingevoerde pakketten door aanbod-beheerders eenvoudig kunnen koppelen aan mijn applicatielandschap, zodat ik niet veel tijd kwijt ben aan registratie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren contracten</td>
      <td><p>Als gebruik-beheerder wil ik contractinformatie zoals looptijd, prijs en verlengingsopties kunnen toevoegen, zodat er meer markttransparantie is en gezamenlijke inkooptrajecten makkelijker te organiseren zijn. Deze informatie is alleen zichtbaar voor gemeenten, samenwerkingsverbanden en VNG.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Samenwerking registreert</td>
      <td><p>Als gebruik-beheerder van een samenwerkingsverband wil ik softwarepakketten kunnen opvoeren voor de gemeenten waarvoor we werken, zodat deze gemeenten een volledig applicatieportfolio hebben, inclusief de uitbestede diensten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren informatie gebruikte pakketten</td>
      <td><p>Als gebruik-beheerder wil ik alle informatie over mijn applicaties in de softwarecatalogus kunnen invoeren, zodat ik een volledig overzicht heb van mijn applicatielandschap, dat ik kan gebruiken voor marktoriëntatie, architectuur, inkoop en leveranciersvraagstukken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Raadplegen gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Zoeken en raadplegen gebruikte pakketten</td>
      <td><p>Als gebruik-raadpleger wil ik kunnen zoeken en filteren in alle gebruikte pakketten, zodat ik inzicht krijg in wat andere gemeenten gebruiken en ik referenties kan vinden voor het stellen van vragen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Gluren bij de buren</td>
      <td><p>Als gebruik-raadpleger wil ik kunnen "gluren bij de buren" om te bekijken welke pakketten bij een andere gemeente in gebruik zijn, zodat ik contact kan opnemen om kennis te delen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Gebruik van (vergelijkbare) pakketten</td>
      <td><p>Als gebruik-raadpleger wil ik bij het bekijken van een pakket kunnen zien welke gemeenten het gebruiken en welke andere pakketten vergelijkbaar zijn.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Registreren koppelingen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren koppelingen</td>
      <td><p>Als gebruik-beheerder wil ik koppelingen kunnen registreren tussen applicaties en/of buitengemeentelijke voorzieningen, zodat ik kan zien over welke koppelingen data wordt gedeeld en de kennis over bestaande koppelingen kan worden gedeeld. &nbsp;Let op! Op dit moment worden koppelingen geregistreerd tussen pakketversie, registreren op versies geeft veel beheer en weinig extra inzicht</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren koppelingen met standaard</td>
      <td><p>Als gebruik-beheerder wil ik bij een koppeling kunnen aangeven of er gebruik wordt gemaakt van een standaard en een toelichting kunnen toevoegen, zodat ik kennis over de koppeling kan delen met collega's en andere gemeenten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Exporteren</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Exporteren</td>
      <td><p>Als aanbod- en gebruik-beheerder wil ik data vanuit de softwarecatalogus kunnen exporteren , zodat ik deze in een spreadsheet kan bewerken en/of kan gebruiken voor een andere toepassing.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Data-migratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Aanbod</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Organisatie</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Beheren content en configuratie

<figure align="center">
  <img width="1201" src="2025-02-26_Vernieuwing_Softwarecatalogus/Beheren_content_en_configuratie.svg" alt="Beheren content en configuratie">
  <figcaption><i>Beheren content en configuratie</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Functioneel beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Beheren content en configuratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Beheren configuratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren menustructuur</td>
      <td><p>Als functioneel beheerder wil ik de menustructuur kunnen aanpassen, zodat ik deze kan inrichten naar de behoeften van de bezoekers van de softwarecatalogus.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren toelichtingen en meldingen</td>
      <td><p>Als functioneel beheerder wil ik toelichtende teksten en foutmeldingen kunnen maken en wijzigen, zodat formulieren en andere functionaliteiten zonder tussenkomst van een ontwikkelaar verduidelijkt of verbeterd kunnen worden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren filters</td>
      <td><p>Als functioneel beheerder wil ik filteropties in overzichten kunnen toevoegen, aanpassen, of verwijderen, evenals de volgorde hiervan kunnen bepalen, zodat ik de gebruikerservaring kan verbeteren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Beheren content</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren content</td>
      <td><p>Als functioneel beheerder wil ik verschillende soorten content (tekst, video, nieuwsberichten, documenten, etc.) kunnen publiceren, zodat ik gebruikers kan informeren over de softwarecatalogus en hen uitleg kan geven over hoe deze te gebruiken.</p></td>
    </tr>
  </tbody>
</table>

### Aanbod

<figure align="center">
  <img width="1733" src="2025-02-26_Vernieuwing_Softwarecatalogus/Aanbod.svg" alt="Aanbod">
  <figcaption><i>Aanbod</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Aanbod- en gebruik-beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Gemeente</td>
      <td><p>Een gemeente is een groep van woonkernen (dorpen, steden) met het bijbehorende gebied die samen worden bestuurd door een politiek apparaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Aanbod-raadpleger</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Samenwerkingsverband</td>
      <td><p>Een samenwerking (of samenwerkingverband) is een juridische vorm waarin gemeenten vastleggen welke specifiek omschreven taken en bevoegdheden aan de samenwerking worden gedelegeerd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Publiek</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Gemeente</td>
      <td><p>Een gemeente is een groep van woonkernen (dorpen, steden) met het bijbehorende gebied die samen worden bestuurd door een politiek apparaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Raadplegen aanbod API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Aanbod</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Exporteren</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Exporteren</td>
      <td><p>Als aanbod- en gebruik-beheerder wil ik data vanuit de softwarecatalogus kunnen exporteren , zodat ik deze in een spreadsheet kan bewerken en/of kan gebruiken voor een andere toepassing.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Raadplegen aanbod</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Raadplegen aanbod (1)</td>
      <td><p>Als aanbod-raadpleger wil ik pakketten kunnen zoeken en filteren op ondersteuning van verplichte en aanbevolen standaarden, zodat ik pakketten kan selecteren die goed samenwerken met de door mij gebruikte pakketten en voorzieningen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Registreren aangeboden pakketten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren geschikt voor referentiearchitectuur</td>
      <td><p>Als aanbod-beheerder wil ik mijn pakketten eenmalig registreren en classificeren op basis van de referentiearchitecturen van de voor mij relevante sector(en), opdat mijn pakket vindbaar is voor afnemers uit meerdere sectoren met hun eigen filteringangen</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren licentie en voorwaarden</td>
      <td><p>Als aanbod-beheerder wil ik per pakket de licentievorm kunnen registreren, inclusief open-source licenties, zodat gebruikers de voorwaarden kennen en daarop kunnen zoeken en filteren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren mijn gebruikers</td>
      <td><p>Als aanbod-beheerder wil ik kunnen registreren welke organisaties mijn pakket gebruiken, zodat het pakket als concept verschijnt in hun pakketoverzicht. Dit stelt hen in staat om het gebruik te bevestigen of af te wijzen, waardoor inzichtelijk wordt hoeveel gemeenten daadwerkelijk gebruikmaken van mijn pakket.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren contactpersoon pakket</td>
      <td><p>Als aanbod-beheerder wil ik voor elk pakket een contactpersoon kunnen aanwijzen, zodat gemeenten direct in contact kunnen komen met de verantwoordelijke persoon voor dat pakket.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Overnemen toegevoegd gebruik</td>
      <td><p>Als aanbod-beheerder zie ik de door gebruik-beheerders onder mijn organisatie toegevoegde pakketten, opdat ik het beheer van deze registratie kan overnemen, aanvullen en verbeteren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Modereren toegevoegd gebruik</td>
      <td><p>Als functioneel beheerder wil ik een overzicht kunnen opvragen van alle door gebruik-beheerders geregistreerde pakketten en/of aanbieders, opdat ik deze kan wijzigen en eventueel samenvoegen met een andere concept-pakket of bestaand leveranciers pakket.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren ondersteuning standaarden</td>
      <td><p>Als aanbod-beheerder wil ik kunnen registreren welke standaarden door mijn pakket worden ondersteund en eventueel testrapporten beschikbaar stellen, zodat gebruikers deze informatie kunnen inzien en erop kunnen zoeken en filteren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren hosting</td>
      <td><p>Als aanbod-beheerder  wil ik bij een applicatie kunnen aangeven of deze on-premise of in de Cloud wordt aangeboden, zodat afnemers hierop kunnen zoeken en filteren</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren door gebruik-beheerder</td>
      <td><p>Als gebruik-beheerder wil ik namens een geregistreerde aanbieder pakketten kunnen opvoeren die ontbreken, opdat ik en andere gemeenten en samenwerkingen deze kunnen opnemen in ons landschap. Door gebruik-beheerders toegevoegde pakketten (en organisaties) krijgen een 'concept-status' en een vermelding wie het pakket geregistreerd heeft. Dit kan later door de echte aanbieder worden overgenomen. Dat een pakket een 'concept-status' heeft is altijd expliciet zichtbaar.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Data-migratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Referentiearchitectuur</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Organisatie</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Organisatie

<figure align="center">
  <img width="1465" src="2025-02-26_Vernieuwing_Softwarecatalogus/Organisatie.svg" alt="Organisatie">
  <figcaption><i>Organisatie</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Functioneel beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Aanbod- en gebruik-beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Gemeente</td>
      <td><p>Een gemeente is een groep van woonkernen (dorpen, steden) met het bijbehorende gebied die samen worden bestuurd door een politiek apparaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Organisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Beheren organisaties</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Zelfregistratie van organisatie</td>
      <td><p>Als aanbod-beheerder wil ik zelf mijn organisatiegegevens in concept kunnen registreren, zodat mijn aanmelden snel en zonder fouten afgehandeld kan worden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Fiatteren zelfregistraties</td>
      <td><p>Als functioneel beheerder wil ik een overzicht hebben van organisaties met de status 'concept' (geregistreerd door aanbod- of gebruik-beheerders), zodat ik deze kan fiatteren, wijzigen of samenvoegen met bestaande organisaties.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Samenvoegen organisaties</td>
      <td><p>Als functioneel beheerder wil ik, naar aanleiding van gemeentelijke herindeling of een leveranciersovername, organisaties en al hun relaties (aanbod en/of gebruik) kunnen samenvoegen met een bestaande of nieuwe organisatie, zodat de gemeente of leverancier het bestaande aanbod en gebruik niet opnieuw hoeft in te voeren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren organisatie</td>
      <td><p>Als functioneel beheerder wil ik nieuwe gemeenten, samenwerkingsverbanden tussen gemeenten, en leveranciers kunnen aanmaken, inclusief de bijbehorende gebruikersaccounts, zodat deze organisaties toegang hebben tot de softwarecatalogus.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren aanbieder door gebruiker</td>
      <td><p>Als gebruik-beheerder wil ik een aanbieder kunnen registreren die nog niet in de softwarecatalogus bestaat, zodat ik en andere gemeenten voor deze aanbieder pakketten kunnen registreren.</p>
<p>Voorbeeld: een gemeente voert een open source community op als aanbieder en voert daarna de door deze community onderhouden open source oplossingen op.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Ontsluiten organisaties</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Zoeken en filteren organisaties</td>
      <td><p>Als gebruiker van de Softwarecatalogus wil ik een overzicht met zoek- en filteropties van alle organisaties die pakketten of diensten aanbieden, opdat ik deze kan selecteren en het aanbod kan bekijken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">dubbel met 68</td>
      <td><p>Als gebruik-raadpleger wil ik een overzicht met zoek- en filteropties van alle organisaties die pakketten of diensten gebruiken, opdat ik deze kan selecteren en het gebruik kan bekijken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Registreren extra organisatieinformatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren contactpersonen</td>
      <td><p>Als aanbod-beheerder wil ik meerdere contactpersonen kunnen registreren en deze aan specifieke pakketten kunnen koppelen, zodat gebruikersvragen direct bij de juiste persoon terechtkomen en sneller afgehandeld kunnen worden.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Registreren aanvullende organisatieinformatie</td>
      <td><p>Als aanbod-beheerder wil ik aanvullende informatie over mijn organisatie kunnen delen, een overzicht van de diensten, en links naar ondersteunende pagina's (zoals het support-portaal en handleidingen), zodat gebruikers een compleet beeld krijgen van onze organisatie en de kwaliteit van ons aanbod.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Aanbod</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Data-migratie</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Referentiearchitectuur

<figure align="center">
  <img width="1381" src="2025-02-26_Vernieuwing_Softwarecatalogus/Referentiearchitectuur.svg" alt="Referentiearchitectuur">
  <figcaption><i>Referentiearchitectuur</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Beheren content en configuratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Toegangsbeveiliging</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Organisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Functioneel beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Aanbod</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Referentiearchitectuur</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Exporteren ArchiMate</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Exporteren ArchiMate</td>
      <td><p>Als gebruik-raadpleger wil ik mijn gebruiksdata (pakketoverzicht en koppelingen gelinkt aan de referentiearchitectuur) als AMEFF-bestand exporteren, opdat ik deze kan inlezen in een architectuurtool en kan gebruiken voor mijn gemeentelijke architectuur. Op GEMMA online wordt in een ArchiMate view weergegeven wat nu de relaties zijn tussen de pakketten en het GEMMA model. Zie hiervoor de pagina https://www.gemmaonline.nl/wiki/Softwarecatalogus<em>AMEFF</em>export</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Plotten op views</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Plotten op views</td>
      <td><p>Als gebruiker wil ik de pakketoverzichten of portfolio's die ik mag inzien, kunnen plotten op een GEMMA-view waarop ik kan inzoomen en die ik kan downloaden als SVG, zodat ik een duidelijk overzicht heb en deze kan gebruiken ter ondersteuning van gesprekken.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Importeren ArchiMate</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Importeren ArchiMate</td>
      <td><p>Als functioneel beheerder wil ik dat een nieuwe release van het GEMMA ArchiMate-model gebruiksvriendelijk ingelezen kan worden in de softwarecatalogus, waarbij de relaties die al zijn gemaakt tussen pakketten en de GEMMA blijven bestaan, opdat gemeenten overal dezelfde GEMMA versie zien. Ga naar https://www.gemmaonline.nl/wiki/Download<em>GEMMA</em>ArchiMate-repository voor meer informatie over het AMEFF bestand.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Ontsluiten architectuur concepten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Ontsluiten architectuur concepten </td>
      <td><p>Als gebruiker van de Softwarecatalogus  wil ik beschikken over de GEMMA architectuurconcepten (referentiecomponenten, standaarden, applicatieservices, etc), opdat deze beschikbaar zijn voor het meta-dateren, zoeken en filteren van pakketten en diensten</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Tonen beschrijving bij concept (tooltip/glossary)</td>
      <td><p>Als gebruiker van de Softwarecatalogus  wil ik waar GEMMA-concepten worden getoond, wil ik dat GEMMA-concepten worden uitgelegd of verklaard, zodat ik in één keer kan zien wat deze inhoud. (Glossary)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Doorverwijzen naar GEMMA online</td>
      <td><p>Als gebruiker van de Softwarecatalogus wil ik vanuit de GEMMA architectuurconcepten (referentiecomponenten, standaarden, etc) worden doorverwezen naar GEMMA online, opdat ik direct toegang heb tot de detail architectuurinformatie</p></td>
    </tr>
  </tbody>
</table>

### Management informatie

<figure align="center">
  <img width="673" src="2025-02-26_Vernieuwing_Softwarecatalogus/Management_informatie.svg" alt="Management informatie">
  <figcaption><i>Management informatie</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Functioneel beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Management informatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Databasetoegang Management Informatietool</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Databasetoegang Management Informatietool</td>
      <td><p>Als functioneel beheerder wil ik rapportages maken over de data in de softwarecatalogus in een rapportage oplossing, zodat ik met verschillende rapportages  inzichten kan bieden. (Toegang tot de db)</p></td>
    </tr>
  </tbody>
</table>

### Data-migratie

<figure align="center">
  <img width="673" src="2025-02-26_Vernieuwing_Softwarecatalogus/Data-migratie.svg" alt="Data-migratie">
  <figcaption><i>Data-migratie</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Aanbod</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Organisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Toegangsbeveiliging</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Data-migratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Migreren data huidige SWC naar nieuwe database</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Migreren data huidige SWC naar nieuwe database</td>
      <td><p>Als aanbod- en gebruik-beheerder van de huidige Softwarecatalogus wil ik mijn reeds geregistreerde gegevens weer zien in de nieuwe Softwarecatalogus, zodat ik deze niet opnieuw hoef in te voeren.</p>
<p>De data-migratie is beschreven in het Word-document Programma van Eisen Softwarecatalogus</p></td>
    </tr>
  </tbody>
</table>

### Softwarecatalogus Non-functionals

<figure align="center">
  <img width="2323" src="2025-02-26_Vernieuwing_Softwarecatalogus/Softwarecatalogus_Non-functionals.svg" alt="Softwarecatalogus Non-functionals">
  <figcaption><i>Softwarecatalogus Non-functionals</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Non-functional requirements</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Toegankelijkheid</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Feedback na fout</td>
      <td><p>Als gebruiker wil ik op een juiste manier geïnformeerd worden door het systeem wanneer er een fout optreedt en wat de oorzaak hier van is, zodat ik op basis van deze informatie de juiste actie kan inzetten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Betrouwbaarheid</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheerorganisatie</td>
      <td><p>De Leverancier borgt dat altijd binnen 2 kalenderdagen en tegen marktconforme tarieven expertise beschikbaar is voor ondersteuning bij onder meer het voorbereiden van een mogelijk wijzigingsverzoek</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Bruikbaarheid</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Gebruikersvriendelijk</td>
      <td><p>De gebruikersinterface moet intuïtief en eenvoudig te gebruiken zijn, zodat gebruikers zonder uitgebreide training of technische kennis zelfstandig kunnen navigeren en taken uitvoeren. Het ontwerp moet consistent zijn met gangbare UX-principes, met duidelijke visuele feedback en logische workflows, en mag geen onnodige complexiteit bevatten. </p>
<p>Voorkomen gebruikersfouten</p>
<ul>
<li>De Softwarecatalogus valideert de invoer van metadata</li>
<li>Bij fouten worden aanwijzingen gegeven hoe de fout hersteld kan worden</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Toegankelijkheid</td>
      <td><p>De softwarecatalogus voldoet aan de eisen van digitoegankelijk (https://www.digitoegankelijk.nl/)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Werkwijze</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Testen</td>
      <td><p>De opgeleverde software wordt door de ontwikkelpartij eerst getest volledig getest,  zodat bij oplevering alle (eerder) ontwikkelde functionaliteit werkt.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Informatiemodel</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Gebruik informatiemodel voorzieningencatalogus</td>
      <td><p>De Softwarecatalogus en de Softwarecatalogus API worden gebaseerd op het informatiemodel voorzieningencatalogus</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Informatiebeveiliging</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Logging activiteiten</td>
      <td><p>Inschrijver borgt dat alle activiteiten, ook die van Eindgebruikers en Beheerders worden vastgelegd in audit-/ logbestanden. Dit zodanig beveiligd dat deze bestanden niet zomaar kunnen worden ingezien, gewijzigd of verwijderd door hiertoe niet bevoegd personeel</p>
<p>Inschrijver borgt dat een logregel minimaal het volgende bevat:</p>
<ol>
<li>Waar mogelijk een tot een natuurlijke persoon herleidbare identificatie.</li>
<li>Waar mogelijk de identiteit van het werkstation of de locatie.</li>
<li>Het object waar de handeling op werd uitgevoerd.</li>
<li>Het resultaat van de handeling.</li>
<li>De gebeurtenis.</li>
<li>De datum en het tijdstip van de gebeurtenis.</li>
</ol></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">nl.internet standaarden</td>
      <td><p>De site softwarecatalogus.nl gebruikt alle door https://nl.internet.nl/ geteste internetstandaarden op de juiste manier. In de nl.internet.nl websitetest scoort de domeinnaam Softwarecatalogus.nl 100%.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Toegangsbeveiliging</td>
      <td><p>Voor het beheren van gegevens hebben alleen geautoriseerde gebruikers toegang tot de Softwarecatalogus
Inloggen met 2 factor authenticatie</p>
<ul>
<li>Een username, password (iets weten)</li>
<li>Een (TOTP) token, gegenereerd met een app op eigen telefoon of laptop (iets hebben)</li>
</ul>
<p>Ondersteuning voor role based access control.</p>
<ul>
<li>Beheerders krijgen toegang tot de beheerschermen op basis van een rol én een organisatie
Mogelijke rollen zijn bijvoorbeeld: Aanbod- en gebruik-beheerder, Ciso, …</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Overdraagbaarheid</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Aanpasbaarheid</td>
      <td><p>Softwareplatform</p>
<ul>
<li>De Softwarecatalogus wordt gerealiseerd met open source software componenten</li>
<li>De gebruikte ‘technologie stack’ bestaat uit gangbare componenten met een levendige community</li>
<li>Er wordt altijd gebruik gemaakt van door de community supported versies.</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">OTAP omgeving</td>
      <td><p>Voor de softwarecatalogus is een ontwikkel, test, acceptatie en productie-omgeving (OTAP) ingericht waarbij VNG en gemeenten toegang hebben tot de acceptatie en productieomgeving.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Installeerbaarheid</td>
      <td><p>Componenten zijn out-of-the-box geschikt voor installatie binnen een gestandaardiseerde (cloud-)infrastructuur platform (bijvoorbeeld Haven[1]). </p>
<ul>
<li>De componenten zijn geautomatiseerd te testen en deployen middels een CI/CD pipeline</li>
<li>Het doorlopen van de pipeline duurt max 1 uur</li>
<li>De voorziening dient als container op (bijvoorbeeld een kubernetes) infrastructuur te kunnen worden gedeployed</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Onderhoudbaarheid</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Herbruikbaarheid</td>
      <td><p>Herbruikbaarheid</p>
<ul>
<li>De broncode van (maatwerk)componenten is beschikbaar als open source software met een EUPL-licentie. </li>
<li>De broncode is goed gedocumenteerd</li>
<li>De broncode wordt beheerd in een git-repository van VNG Realisatie</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Techniek toekomstvast</td>
      <td><p>De techniek (programmeertaal, packages, tooling) die gebruikt wordt voor de ontwikkeling van de nieuwe softwarecatalogus, is toekomstvast. Er zijn in Nederland minimaal 100  ontwikkelaars die deze tooling gebruikt en hier kennis van heeft</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Modulariteit</td>
      <td><p>Proceslogica en bedrijfsregels zijn los van elkaar en los van de interactie naar gebruikers instelbaar.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Webstatistieken</td>
      <td><p>Als functioneel beheerder wil ik inzicht in het gebruik van de softwarecatalogus door middel van een open source en confrom privacy omgeving ingericht webstatistiekenpakket, zoals Matomo.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Standaarden</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">e-mail standaarden</td>
      <td><p>De standaarden DKIM en DMARC zijn vereist voor het versturen van e-mails. Bijvoorbeeld voor het ondersteunen van het proces voor als je je wachtwoord bent vergeten</p>
<ul>
<li>DKIM faciliteert van het vaststellen van organisatorische herkomst voor e-mail afkomstig van overheidsdomeinen, als deze over een onbeveiligde, publieke internetverbinding wordt verstuurd wanneer verdere authenticatie ontbreekt.</li>
</ul>
<p>-&nbsp;DMARC is een standaard die het voor organisaties mogelijk maakt om te bepalen hoe e-mailproviders, omgaan met e-mail waarvan niet kan worden vastgesteld dat deze afkomstig is van het eigen domein. Hierdoor kunnen organisaties voorkomen dat anderen e-mails versturen namens het e-maildomein van de organisatie.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">NL API strategie standaarden</td>
      <td><p>We ontwikkelen API-first in lijn met de NL API strategie en de recent gepubliceerde API standaarden bij het forum standaardisatie.</p>
<ul>
<li><p>Dit zijn de OpenAPI Specification (https://www.forumstandaardisatie.nl/open-standaarden/openapi-specification) en </p></li>
<li><p>de REST-API Design Rules (https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules).</p></li>
</ul></td>
    </tr>
  </tbody>
</table>

<div style="page-break-before: always;"></div>

---

## Realisatie en onderhoud

### Softwarecatalogus gebruikers en eigenaren

Verdeling van eigenaarschap en verantwoordelijkheiden voor de Softwarecatalogus en gebruikte services
<figure align="center">
  <img width="1703" src="2025-02-26_Vernieuwing_Softwarecatalogus/Softwarecatalogus_gebruikers_en_eigenaren.svg" alt="Softwarecatalogus gebruikers en eigenaren">
  <figcaption><i>Softwarecatalogus gebruikers en eigenaren</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="4" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="4">Gebruiker Softwarecatalogus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Gemeente</td>
      <td><p>Een gemeente is een groep van woonkernen (dorpen, steden) met het bijbehorende gebied die samen worden bestuurd door een politiek apparaat.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Leverancier</td>
      <td><p>Aanbieders van standaard-software(pakketten) voor gemeentelijke taken. Alleen leveranciers die het convenant met VNG/KING ondertekend hebben, mogen hun gegevens in de Softwarecatalogus zetten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Gebruiker Open Registers</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Gemeente Gouda</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Open Webconcept</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Digilab</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Realisatie en onderhoud</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Applicatiebeheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Conduction</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Eigenaar Softwarecatalogus</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">VNG Realisatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Eigenaar Open Registers</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Gemeente Gouda</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">github</td>
      <td><p>GitHub is een online platform voor softwareontwikkeling en versiebeheer (wikipedia)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Softwarecatalogus git-repository</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">(Project)documentatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">SWC-code</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Configs</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Open Registers git-repository</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">(Project)documentatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Open Registers code</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Open Connector git-repository</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">(Project)documentatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Open Connector code</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Softwarecatalogus nieuw</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Open Registers services</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Open Connector services</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Cloud infrastructuur</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Beheer</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Technisch beheerder</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Conduction</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Hosting provider</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Cyso</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Softwarecatalogus component Referentiearchitectuur

Uitwerking van de realisatie van ArchiMate-functionaliteit in onderliggende services, componenten en functies
<figure align="center">
  <img width="1542" src="2025-02-26_Vernieuwing_Softwarecatalogus/Softwarecatalogus_component_Referentiearchitectuur.svg" alt="Softwarecatalogus component Referentiearchitectuur">
  <figcaption><i>Softwarecatalogus component Referentiearchitectuur</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Gebruik</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Aanbod</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">ArchiMate File Format</td>
      <td><p>Met het ArchiMate Bestandsuitwisselformaat kunnen architectuurtools ArchiMate architectuurmodellen met elkaar uitwisselen. Deze standaard wordt ook aangeduid als ArchiMate Model Exchange File Format (AMEFF)</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">AMEFF export API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">ArchiMate API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Open API standaard</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Softwarecatalogus beheer</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Import formulier</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Softwarecatalogus frontend</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Beheren content en configuratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren content</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren configuratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Toegangsbeveiliging</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Beheren gebruikers en rollen</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Softwarecatalogus backend</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">ArchiMate integratie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">AMEFF importer</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">AMEFF exporter</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Version manager</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">Relation manager</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Referentiearchitectuur</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Importeren ArchiMate</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Exporteren ArchiMate</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Ontsluiten architectuur concepten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Plotten op views</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">ArchiMate ontsluiten</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Opvragen elementen, relaties en views</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">ArchiMate views</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Toevoegen pakketten aan view</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Genereren SVG</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">GEMMA AMEFF-bestand</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Nextcloud platform services</td>
      <td><p>easy, unified access to files wherever they are stored</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Open Connector services</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Open Registers services</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">GEMMA register</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">SVG library x</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Open Registers en -Connector technische architectuur

De services geleverd door Open Registers en Open Connector, en de onderliggende (Nextcloud) technologieservices
<figure align="center">
  <img width="1213" src="2025-02-26_Vernieuwing_Softwarecatalogus/Open_Registers_en_-Connector_technische_architectuur.svg" alt="Open Registers en -Connector technische architectuur">
  <figcaption><i>Open Registers en -Connector technische architectuur</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="3" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="3">Softwarecatalogus nieuw</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">OpenCatalogi services</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">OpenCatalogi</td>
      <td><p>An open-source platform for managing and discovering software, data, and API catalogs, mainly for public sector organizations.  </p>
<p>Key Features:</p>
<ul>
<li>Centralized registry of open data, APIs, and software components.  </li>
<li>Metadata-driven search and categorization.  </li>
<li>API integration for automated catalog updates.  </li>
<li>Supports linked data standards (RDF, SPARQL).</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">PHP-code</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Open Connector services</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Transformation</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Integration</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Open Registers services</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Access control</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Automatic facets</td>
      <td><p>Automatic Facets provide dynamic filtering options based on object properties and metadata.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Synchronisatie / federatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Register en objecten service</td>
      <td><p>Store and manage registers of objects within their Nextcloud instance</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Triple store</td>
      <td><p>Een database service ontworpen voor het opslaan en opvragen van semantische gegevens in RDF-triples.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Open Connector</td>
      <td><p>A middleware service that connects different data sources (APIs, databases, cloud storage) and transforms data into a standardized format for reuse.<br />
Provides gateway and service bus functionality like mapping, translation and synchronisation of data</p>
<p>Key Features:</p>
<ul>
<li>Connects APIs, databases, and external registers.  </li>
<li>Converts and normalizes data into common formats (JSON, RDF, etc.).  </li>
<li>Automates data ingestion and synchronization.  </li>
<li>Supports workflow automation for seamless integration.</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">PHP-code</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Open Registers</td>
      <td><p>A Nextcloud-based app for managing structured, authoritative datasets (registers). It ensures versioned, trusted, and structured data storage, accessible via API and UI.</p>
<p>Key Features:</p>
<ul>
<li>Store and manage registers in JSON, CSV, or XML format.</li>
<li>Version control and access permissions.</li>
<li>WebDAV &amp; API integration for external system access.</li>
<li>Federation support for syncing across Nextcloud instances.</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">PHP-code</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Gegevensverzameling en integratie</td>
      <td><p>Technologieservice voor het verzamelen van gegevens uit verschillende bronnen en het integreren ervan in een samenhangend geheel voor analyse en gebruik.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">ETL-component</td>
      <td><p>Technologiecomponent voor het extraheren, transformeren naar een gewenst formaat en laden in een doelopslagplaats gegevens uit verschillende bronnen. Bijvoorbeeld voor data warehousing.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="1">XML framework</td>
      <td><p>Conduction transform - mapping service</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3">Nextcloud platform services</td>
      <td><p>easy, unified access to files wherever they are stored</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Berichtuitwisseling</td>
      <td><p>Technologieservice voor het verzenden en ontvangen van berichten tussen systemen of applicaties.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Federatie</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Accessing data</td>
      <td><p>While Nextcloud provides a great deal of control over data access and sharing to administrators, users are presented with an easy to use and familiar interface through the web browser, Android and iOS apps and desktop sync applications. </p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Full text search</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="2">Applicatie- en webhosting</td>
      <td><p>Technologieservice voor het installeren en gebruiken van applicaties en websites.</p></td>
    </tr>
  </tbody>
</table>

### Nextcloud geplot op Common Ground 5-lagen

De uitwerking van Nextcloud binnen het Common Ground 5-lagenmodel
<figure align="center">
  <img width="1483" src="2025-02-26_Vernieuwing_Softwarecatalogus/Nextcloud_geplot_op_Common_Ground_5-lagen.svg" alt="Nextcloud geplot op Common Ground 5-lagen">
  <figcaption><i>Nextcloud geplot op Common Ground 5-lagen</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="4" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="4">Dienstenafnemer</td>
      <td><p>De actor of applicatie die diensten afneemt die door een aanbieder worden aangeboden.
Een dienstenafnemer levert de gebruikersinterfaces en procesinrichting voor medewerkers van de gemeente en burgers en bedrijven en maakt daarbij gebruik van bij dienstenaanbieders afgenomen diensten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Interactie</td>
      <td><p>Groep van generieke functies om verantwoord applicatie-interfaces aan gebruikers te bieden voor toegang tot de gemeentelijke informatievoorziening.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Apps interface</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">End user interface</td>
      <td><p>Access their files and folders, initiate and control sharing, monitor who is doing what with their files, search for, comment 
on, edit, view and download files. 
Files can be deleted and brought back from the trash and users can view older versions of files and restore them if they wish</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Audio/video chat (optional)</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Collaborative office document editing (optional)</td>
      <td><p>Enabling users to work individually or collectively on common office documents like XLSX, DOCX or PPTX as well as OpenDocument files.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Browser</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Vue.js</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Javascript</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Mobile and desktop clients (syncing)</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">WebDAV client</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Procesinrichting</td>
      <td><p>Groep van generieke functies voor het kunnen aansturen van processen, uitvoeren van data-analyse en verantwoord gebruik van door aanbieders geleverde diensten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Admin interface</td>
      <td><p>web interface for configuring, managing 
and monitoring Nextcloud systems </p></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Intermediair</td>
      <td><p>Actor of applicatie die bemiddelt tussen aanbieders en afnemers. </p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Connectiviteit</td>
      <td><p>Groep van generieke functies om dienstenafnemers in staat te stellen gebruik te maken van door dienstenaanbieders geleverde diensten.
Dit omvat onder andere afspraken, standaarden en voorzieningen voor het vindbaar maken van diensten, bieden van toegang tot en monitoring van diensten en het veilig uitwisselen van gegevens via verbindingen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Dienstenaanbieder</td>
      <td><p>De actor of applicatie die diensten aanbiedt die door een afnemer zijn af te nemen.
Een dienstenaanbieder levert diensten waarmee dienstenafnemers toegang krijgen tot data uit databronnen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Diensten</td>
      <td><p>Groep van generieke functies voor het kunnen leveren van diensten aan dienstenafnemers.
Passend bij de Informatiekundige Visie Common Ground betreft het met name diensten waarmee afnemers gebruik kunnen maken van data die is vastgelegd in bronregistraties.
Binnen diensten is onderscheid te maken in:</p>
<ul>
<li>Systeemdiensten die data ontsluiten op het niveau van bronsystemen ('systems of record'). Bijvoorbeeld via CRUD-methoden voor het aanmaken, lezen, wijzigen en verwijderen van data. </li>
<li>Procesdiensten die gebruik maken van één of meerdere systeemdiensten en de resultaten gebundeld teruggeven. Bijvoorbeeld door data over een zaak in meerdere registers op te vragen en gebundeld terug te geven.</li>
<li>Gemaks- of ervaringsdiensten die op een afnemersvriendelijke manier één specifieke gebruikersvraag beantwoorden (bijvoorbeeld of een bepaalde persoon ouder is dan 18 jaar).</li>
</ul></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">App API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Apps</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">New functionality</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Nextcloud Platform API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Open Cloud Mesh API</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Databronnen</td>
      <td><p>Groep van generieke functies voor het compliant aan wet- en regelgeving, bij voorkeur gestandaardiseerd, kunnen vastleggen en ontsluiten van data.
Databronnen kunnen een overheidsbreed of domeinspecifiek karakter hebben.
Gemeentelijke gegevens worden onder regie van gemeenten zoveel mogelijk gestandaardiseerd.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Nextcloud server</td>
      <td><p>Een open-source platform voor cloudopslag en samenwerking</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Security standards and  guidlines</td>
      <td><p>Nextcloud aligns with industry standards such as Clause 14 of ISO/IEC27001-2013 and related standards, guidance and security principles</p></td>
    </tr>
  </tbody>
</table>

### Nextcloud technische architectuur

De services geleverd door Nextcloud en de onderliggende technologiecomponenten.
<figure align="center">
  <img width="1004" src="2025-02-26_Vernieuwing_Softwarecatalogus/Nextcloud_technische_architectuur.svg" alt="Nextcloud technische architectuur">
  <figcaption><i>Nextcloud technische architectuur</i></figcaption>
</figure>

<table>
  <thead>
    <tr>
      <th colspan="4" width="20%">Element</th>
      <th rowspan="2" width="80%">Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr><td></td><td></td><td></td><td></td><td></td></tr>
    <tr valign="top")>
      <td colspan="4">Nextcloud App services</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Nextcloud App</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Browser</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Vue.js</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Javascript</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Mobile and desktop clients (syncing)</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">WebDAV client</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Nextcloud platform services</td>
      <td><p>easy, unified access to files wherever they are stored</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Accessing data</td>
      <td><p>While Nextcloud provides a great deal of control over data access and sharing to administrators, users are presented with an easy to use and familiar interface through the web browser, Android and iOS apps and desktop sync applications. </p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2"> Authentication and Provisioning</td>
      <td><p>Nextcloud integrates in existing account handling infrastructure. Active Directory 
and LDAP support provides account provisioning, integration and quota manage
ment.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Server side encryption</td>
      <td><p>object storage can be secured through server side encryption</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">File handling and storage</td>
      <td><p>Nextcloud hides away file system and storage differences for the end users. It 
stores user files in standard file system formats, supporting most enterprise file 
storage systems.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">File Access Control and Processing</td>
      <td><p>Through File Access Control and automatic file tagging, Nextcloud gives administrators control over data access by enabling them to define strict rules requests need to adhere to</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="3"></td>
      <td colspan="1">Workflow engine</td>
      <td><p>The Workflow engine expands these capabilities, enabling administrators to start any kind of actions based on these triggers, for example converting document file types to PDF upon upload by members of a specified group</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Collaborative office service</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Full text search</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Berichtuitwisseling</td>
      <td><p>Technologieservice voor het verzenden en ontvangen van berichten tussen systemen of applicaties.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Federation</td>
      <td><p>This feature enables transparent file sharing between users on different servers</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Applicatie- en webhosting</td>
      <td><p>Technologieservice voor het installeren en gebruiken van applicaties en websites.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Nextcloud platform</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Nextcloud server</td>
      <td><p>Een open-source platform voor cloudopslag en samenwerking</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Webserver</td>
      <td><p>Technologiecomponent voor hosting van webpagina's en webtoepassingen en het leveren van diensten aan clients via HTTP/HTTPS. Bijvoorbeeld Apache HTTP Server en Nginx.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Apache / NGINX</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Apache SOLR</td>
      <td><p>Een krachtige zoekplatform gebaseerd op Apache Lucene voor full-text search en indexing.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">REDIS caching server</td>
      <td><p>Redis (which stands for REmote DIctionary Server) is an open-source in-memory data structure store that is commonly used to implement non-relational key-value databases and caches.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Toegangsbeheercomponent</td>
      <td><p>Technologiecomponent voor het beheren van gebruikersrechten en toegang tot systemen en gegevensbronnen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Open LDAP / Active directory</td>
      <td><p>OpenLDAP is a free, open-source implementation of the Lightweight Directory Access Protocol (LDAP)</p>
<p>Lightweight Directory Access Protocol (LDAP) is een netwerkprotocol dat beschrijft hoe gegevens uit directoryservices benaderd moeten worden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Identiteitbeheercomponent</td>
      <td><p>Technologiecomponent voor het beheren, authenticeren en autoriseren van identiteiten. Bijvoorbeeld van gebruikers en applicaties.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Open LDAP / Active directory</td>
      <td><p>OpenLDAP is a free, open-source implementation of the Lightweight Directory Access Protocol (LDAP)</p>
<p>Lightweight Directory Access Protocol (LDAP) is een netwerkprotocol dat beschrijft hoe gegevens uit directoryservices benaderd moeten worden</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Relationeel DBMS</td>
      <td><p>Technologiecomponent voor het opslaan en beheren van gegevens in relationele tabellen met SQL. Bijvoorbeeld: MySQL, PostgreSQL en Oracle.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Maria DB</td>
      <td><p>Een relationele database-managementsysteem (RDBMS) als open-source alternatief voor MySQL.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Message broker</td>
      <td><p>Technologiecomponent voor het veilig, efficiënt en betrouwbaar uitwisselen van berichten tussen systemen.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">REDIS caching server</td>
      <td><p>Redis (which stands for REmote DIctionary Server) is an open-source in-memory data structure store that is commonly used to implement non-relational key-value databases and caches.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Cloud infrastructuur</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Verwerkingsservices</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Container gebruik</td>
      <td><p>Technologieservice voor het gebruik van containers voor het isoleren en uitvoeren van applicaties in een consistente en reproduceerbare omgeving, onafhankelijk van de onderliggende infrastructuur.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Opslagservices</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Bestandsopslag</td>
      <td><p>Technologieservice voor het opslaan van digitale bestanden op fysieke of cloud-gebaseerde opslagmedia.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Netwerkservices</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Load balancing</td>
      <td><p>Technologieservice voor het verdelen van netwerk- of applicatieverkeer over meerdere servers om betrouwbaarheid en prestaties te optimaliseren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Container platform</td>
      <td><p>Technologiecomponent voor het beheren, implementeren en schalen van applicatiecontainers die applicaties en hun afhankelijkheden in een geïsoleerde omgeving uitvoeren.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Kubernetes</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="2"></td>
      <td colspan="2">Haven</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Bestandsopslagcomponent</td>
      <td><p>Technologiecomponent voor het opslaan en beheren van bestanden op een schijf of in een netwerk.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Load balancer</td>
      <td><p>Technologiecomponent voor het verdelen van netwerk- of toepassingsverkeer over meerdere servers om efficiëntie en betrouwbaarheid te vergroten.</p></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">HAProxy</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="1"></td>
      <td colspan="3">Kubernetes</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">External storage</td>
      <td></td>
    </tr>
    <tr valign="top")>
      <td colspan="4">Primary storage</td>
      <td></td>
    </tr>
  </tbody>
</table>

