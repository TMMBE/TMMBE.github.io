---
layout: admin
title: Ledenbeheer
nav_order: 6
---

# Ledenbeheer
{: .no_toc }

## Inhoudsopgave
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Overzicht

### Weergave
	
Standaard worden alle actieve leden getoond, alfabetisch gerangschikt op voornaam. Met de pijltjes naast voornaam en achternaam is het mogelijk de resultaten op een 
andere manier te rangschikken. 

Het is echter mogelijk andere weergaven te tonen, dit kan door op het draaiwieltje naast "weergave" te klikken. Mogelijke opties zijn:
- Leden (alle leden)
- Abonnementen (alle leden met hun abonnement informatie, indien een lid twee abonnementen heeft wordt hij tweemaal getoond)
- E-mails (alle leden met hun e-mail en status op de nieuwsbrief, indien een lid twee e-mailadressesn heeft wordt hij tweemaal getoond)

Afhankelijk van de gekozen weergave zijn er ook andere ledenacties mogelijk (zie [Ledenacties](#ledenacties))

### Filters

Het is mogelijk verschillende filters toe te passen:
- Naam (er wordt gezocht in zowel voor- en achternaam)
- Toon inactieve leden (deze verschijnen in het grijs tussen de actieve leden)
- Type lid (gekoppelde leden gebruiken Squatix, niet-gekoppelde leden zijn niet gekoppeld met een echte gebruiker (zie ([Toevoegen leden](#toevoegen))))
- Rol (zie [Rollen](#rollen))
- Status abonnement (geldig of niet meer geldig)
- Type abonnement (met beurten of enkel met een geldigheidsdatum)
- Abonnementscategorie (zie [Abonnement](#abonnement))
- Meetingscategorie (filter wordt enkel getoond indien een abonnementscategorie is geselecteerd, filter bevat de meetingscategorieën gelinkt aan dit abonnement, 
zie [AbonnementsCategorieën](settings.md#abonnementscategorieën). Resultaat toont de leden die een abonnement hebben met de geselecteerde abonnementscategorie en 
waarvoor de aangeduide meetingscategoriën aangevinkt staan als "automatisch inschrijven".
- Nieuwsbrief geabboneerd
- Nieuwsbrief ingeschakeld

![member list](/assets/images/member_list.png)
		
Een van de extra filters weer verwijderen kan door op "meer filters" te klikken en deze weer leeg te maken of door te klikken op het kruisje naast de desbetreffende filter.

### Acties
- Nieuwe leden toevoegen kan via "Voeg toe" (zie [Toevoegen](#toevoegen)).
- Indien er ledenverzoeken zijn wordt dit hier getoond (zie [Ledenverzoeken](#ledenverzoeken)).

![member actions](/assets/images/member_actions1.png)

- Met het drop-down menu en de "Uitvoeren" knop kan je acties uitvoeren op meerdere leden tegelijkertijd, zie [Ledenacties](#ledenacties)

![member actions](/assets/images/member_actions2.png)		
		
## Ledenacties

### Exporteer (weergave leden)

### Genereer QR (weergave leden)
QR-codes van leden kunnen ook afgedrukt worden. Met deze codes kunnen leden gescand worden om hun aanwezigheid op de meeting te bevestigen (zie [QR scanning](qr-scanning.md)). Vink in het overzicht de leden aan, selecteer "Genereer QR" in het drop-down menu en klik op uitvoeren. Een PDF bestand met de gewenste QR codes wordt geopend.

![QR codes](/assets/images/generate_qr.png)

### Aanwezigheidslijst (weergave leden)
Genereer een rapport met de aanwezigheden per lid. Vink eerst een aantal leden aan in het overzichtsscherm, selecteer "aanwezigheidslijst" in het drop-down menu en klik op "uitvoeren", het aanwezigheidslijstscherm wordt geopend.
		
Bovenaan vind je een overzicht met de geselecteerde leden, met X kan je eventueel nog leden terug verwijderen.

![attendance list](/assets/images/attendance_list1.png)	
		
In het onderste deel kan je de meetings filteren waarvoor je de aanwezigheidslijst wilt genereren, eens de juiste parameters zijn ingevuld, klik op "ok" en de resultaten worden zichtbaar. Wens je de lijst gemakkelijk te kunnen afdrukken, klik dan op (1) en er wordt een PDF gegenereerd met hetzelfde overzicht.

![attendance list](/assets/images/attendance_list2.png)

### Team aanmaken (weergave leden)

Met deze functie kan je op een snelle manier een nieuw team aanmaken. Vink in het overzicht de leden aan die in het team moeten toegevoegd worden, selecteer "Team aanmaken". Op de volgende pagina
vul je de naam van het team in, klik je op bewaar en het team is aangemaakt. (zie [Teams](settings.md#teams))

### Betaling aanmaken (weergave leden)

### Maak een groepschat (weergave leden)

### Bewerk abonnementen (weergave abonnementen)
Deze functie kan gebruikt worden indien je bij verschillende leden tegelijk een abonnementsaanpassing wilt doen. Vink in het overzicht de leden aan, selecteer "Bewerk abonnementen" in het drop-down menu en klik op uitvoeren. Het abonnementenscherm wordt geopend.
		
Bovenaan vind je een overzicht met de geselecteerde leden, met X kan je eventueel nog leden terug verwijderen.

![mass subscriptions](/assets/images/mass_subscriptions1.png)	
		
In het onderste deel kan je gewenste actie selecteren:
- Nieuw abonnement toevoegen: alle geselecteerde leden krijgen een nieuwe abonnement toegevoegd. Dit nieuw abonnement moet compatibel zijn met hun bestaande actieve 
abonnementen. Selecteer de gewenste opties van dit nieuwe abonnement en klik op "Bewaar"

![mass subscriptions](/assets/images/mass_subscriptions2.png)

- Abonnement verlengen: alle geselecteerde abonnementen van de geselecteerde leden worden verlengd. Selecteer de termijn en klik op "Bewaar"

![mass subscriptions](/assets/images/mass_subscriptions3.png)				
		
## Toevoegen
Deze functie laat jou toe om leden toe te voegen en hun details te bewaren, ook al gebruiken ze Squatix niet. Indien ze toch later Squatix beginnen gebruiken en een lidverzoek voor jouw club indienen kan je het door jou aangemaakte profiel met de echte gebruiker linken. (zie [Ledenverzoeken](#ledenverzoeken))
Velden die je kan invullen zijn:
- Voornaam (verplicht)
- Achternaam (verplicht)
- Email (optioneel)
- Telefoon (optioneel)
- Geboortedatum (optioneel)
- Geslacht (optioneel)
- Nationaliteit (optioneel)
- Adres (optioneel)
	- Straat
	- Huisnummer
	- Gemeente
	- Postcode 
	- Land

## Ledenverzoeken

Vooraleer een gebruiker toegang krijgt tot de functionaliteiten in jouw club dient hij eerst een lidverzoek in te dienen. Op deze pagina krijg je een overzicht van de lidverzoeken en kan je beslissen 
of je ze wilt aanvaarden of afwijzen. 

![member requests](/assets/images/member_requests.png)	

Door te klikken op een ledenverzoek wordt er meer informatie getoond over de gebruiker die het verzoek verstuurt heeft.

![member requests](/assets/images/member_request.png)	

1) Info gebruiker

Meer info over wie het verzoek verstuurd heeft (indien ingevuld door gebruiker):
- E-mail
- Telefoon
- Geboortedatum 
- Geslacht
- Profielfoto

2) Lid verzoek vragen

Indien je lid verzoek vragen ingesteld hebt (zie [Lid verzoek vragen](settings.md#lid-verzoek-vragen)) kan je hier de antwoorden van de gebruiker lezen.

3) Koppelen

Het is mogelijk de gebruiker te koppelen aan een bestaand ledenprofiel. Op die manier kan je jouw leden initieel zelf aanmaken zonder dat ze gekoppeld zijn met een gebruiker (en zo hun gegevens 
bijhouden). Zodra ze echter de applicatie beginnen te gebruiken kan je met deze functie de gebruiker koppelen met dit eerder aangemaakte profiel. Alle gegevens die je al ingegeven had blijven 
bewaard na koppeling.  

Opteer je ervoor om geen koppeling uit te voeren, dan wordt er een nieuw lid voor de gebruiker aangemaakt en worden de gegevens die de gebruiker in zijn eigen 
gebruikersprofiel al ingegeven had (geboortedatum, geslacht, naam, voornaam, ...) gekopieerd naar dit leden profiel in jouw club.

4) Afwijzen/aanvaarden

Indien je ervoor opteert het ledenverzoek af te wijzen wordt het onherroepelijk verwijderd. 
 
Zodra je het verzoek geaccepteerd hebt wordt er een extra actief lid toegevoegd aan jouw club.

**Opgelet:** Om een kindprofiel lid te laten worden van jouw club en toegang te geven tot alle functionaliteit is het voldoende dat enkel dit kindprofiel een ledenverzoek verstuurt. Het is dus **niet**
nodig dat ook een gekoppeld ouderprofiel lid wordt van de club indien deze in realiteit eigenlijk geen lid is.
		
## Detail
Wijzigingen die doorgevoerd worden in de detailpagina van een lid hebben enkel betrekking op de details van het lid in de club zelf. Deze worden dus niet aangepast 
of overschreven in het gebruikersprofiel van het lid. Beide profielen staan los van elkaar.

In de bovenste sectie kan je het volgende terugvinden:
- Foto: uploaden van een foto voor het lid, deze staat los van de eigen foto die het lid in zijn profiel heeft toegevoegd en zal deze dus niet overschrijven
- Gekoppeld aan gebruikersprofiel: dit label wordt getoond indien een fysieke gebruiker aan dit lid gekoppeld is (na een ledenverzoek, zie [Ledenverzoeken](#ledenverzoeken))
- Kindprofiel: dit label wordt getoond indien een kindprofiel aan dit lid gekoppeld is 
- Inactief maken: door een lid inactief te maken is hij niet meer aanpasbaar maar telt hij ook niet meer mee in het aantal leden (voor berekening van het clubabonnement).
Zijn profiel kan wel nog bekeken worden door te zoeken op inactieve leden in het overzicht (zie ([Overzicht](#toevoegen))).

![member details heading](/assets/images/member_detail_heading.png)

Opgelet, volgende gevolgen zijn onomkeerbaar:
	- Het lid wordt verwijderd uit alle toekomstige meetings waarvoor het ingeschreven is
	- Indien hij als trainer gekoppeld is aan een meetingscategorie wordt deze koppeling verwijderd
	- Indien een fysieke gebruiker gekoppeld is aan dit lid wordt de connectie verwijderd en heeft deze gebruiker geen toegang meer tot de club
- Lid verwijderen: een lid verwijderen heeft dezelfde gevolgen als een lid inactief maken maar hij wordt ook verwijderd uit de lijst met leden en zijn ledenprofiel
kan op geen enkele manier meer bekeken worden. Deze actie is onomkeerbaar. 

### Abonnement

Er wordt een overzicht getoond van alle actieve en inactieve (vorige) abonnementen.  
In het bovenste deel van het scherm worden alle actieve abonnementen getoond en de mogelijke acties op deze abonnementen.  
In het onderste deel van het scherm wordt een overzicht van de vorige abonnementen getoond, deze zijn niet meer aanpasbaar.

![member details subscriptions](/assets/images/member_detail_subscriptions.png)

**Actieve abonnementen**  

Het werken met abonnementen is optioneel. Een lid kan echter ook meerdere actieve abonnementen hebben. De beheerder kan dus zelf kiezen welke aanpak hij verkiest. Volgende beperkingen gelden:
- Er kan maar één abonnement zijn van elke abonnementscategorie
- Er kan maar één abonnement zijn zonder abonnementscategorie
- Twee abonnementen kunnen geen overlappende gelinkte meetingscategorieën hebben.

Om een nieuw actief abonnement toe te voegen, klik op het +-teken. Het scherm om een nieuw abonnement aan te maken opent zich. Volgende velden kunnen ingevuld worden:
- Type (verplicht, abonnement of beurten)
- Categorie (optioneel, zie [Abonnementscategorieën](settings.md#abonnementscategorieën))
- Categorieën automatisch inschrijven (optioneel, enkel indien de geselecteerde abonnementscategorie gelinkte meetingscategorieën heeft, 
zie [Abonnementscategorieën](settings.md#abonnementscategorieën) en [Automatisch inschrijven](#automatisch-inschrijven))
- Geldig tot (verplicht)
- Beurten over (verplicht indien type "Beurten" geselecteerd is)

Om een actief abonnement aan te passen klik op het potloodje. Vorige aanpassingen aan het abonnement kunnen bekeken worden in het scherm dat opent. Om een nieuwe aanpassing 
door te voeren, klik nogmaals op het potloodje.  

Om een abonnement inactief te maken, klik op "inactief maken" op het bewuste abonnement. Het abonnement verdwijnt naar de sectie "Vorige abonnementen" en is niet meer 
aanpasbaar. Dit kan niet ongedaan gemaakt worden.

**Vorige abonnementen**

Dit toont een overzicht van inactieve abonnementen. Indien er aanpassingen geweest zijn aan dit abonnement (geldig-tot datum, aantal beurten, ...) kunnen deze bekeken worden door op het pijltje aan de rechterkant te klikken (enkel getoond indien er aanpassingen waren).


### Lid gegevens

**Extra info**

Volgende informatie kan je hier bekijken:

- Lid sinds welke datum
- Indien kindprofiel: wie zijn de gekoppelde ouders

![member details extra info](/assets/images/member_detail_extrainfo.png)

**Rollen**

Verander de autorisaties van het lid in Squatix door hem een of meerdere rollen toe te kennen (zie [Rollen](#rollen))

![member details roles](/assets/images/member_detail_roles.png)

**Opmerkingen**

Vrij tekstveld om algemene opmerkingen over het lid te bewaren

![member details remarks](/assets/images/member_detail_remarks.png)

**Lid verzoek vragen**

Indien het lid bij zijn ledenverzoek vragen diende te beantwoorden kan je hier de antwoorden nalezen (zie [Lid verzoek vragen](settings.md#lid-verzoek-vragen)).

![member details questions](/assets/images/member_detail_questions.png)

### Persoonlijk

Op deze pagina kan je alle persoonlijke details over het lid bekijken en aanpassen.

Volgende info is beschikbaar:
- Naam
- Geslacht
- Geboortedatum
- Nationaliteit
- Adres
- E-mail (je kan meerdere emailadressen opslaan en ze voorzien van een label)
- Telefoon (je kan meerdere telefoonnummers opslaan en ze voorzien van een label)

![member details subscriptions](/assets/images/member_detail_personal.png)

### Meetings
Hier kan je een overzicht krijgen van alle meetings waarop het lid ingeschreven is (verleden en toekomst). 

Om gerichter te zoeken kan je de meetings filteren op:
- Naam
- Categorie
- Startdatum

![member details subscriptions](/assets/images/member_detail_trainings.png)

## Vrijwilligers
Je kan leden van je club de vrijwilligersrol toekennen. Vrijwilligers kunnen zich inschrijven op vrijwillgerstaken bij meetings. Om een lid vrijwilliger te maken, ga je naar de detailpagina van het lid. Onder de tab 'Lid gegevens' zet je het 'Vrijwilliger'-knopje aan onder de sectie 'Rollen'. Leden kunnen ofwel lid ofwel vrijwilliger zijn of beide. Een lid die de lid-rol niet heeft maar wel de vrijwilligers-rol, kan zich niet inschrijven om deel te nemen aan meetings. Een lid die beide heeft kan zich zowel inschrijven om deel te nemen als zich inschrijven voor een vrijwilligerstaak. Om vrijwilligerstaken toe te voegen aan een meeting, zie [Meetings](meetings.md#vrijwilligers).

![member volunteer roles](/assets/images/volunteer_roles.png)
