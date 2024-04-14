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
- Type lid (gekoppelde leden gebruiken Squatix, niet-gekoppelde leden zijn niet gekoppeld met een echte gebruiker (zie [Toevoegen leden](#toevoegen)))
- Rol (zie [Lid gegevens](#lid-gegevens))
- Status abonnement (geldig of niet meer geldig)
- Type abonnement (met beurten of enkel met een geldigheidsdatum)
- Abonnementscategorie (zie [Abonnement](#abonnement))
- Nieuwsbrief geabboneerd

![member list](/assets/images/member_list.png)
		
Een van de extra filters weer verwijderen kan door op "meer filters" te klikken en deze weer leeg te maken of door te klikken op het kruisje naast de desbetreffende filter.

### Acties
- Nieuwe leden toevoegen kan via "Voeg toe" (zie [Toevoegen](#toevoegen)).
- Indien er ledenverzoeken zijn wordt dit hier getoond (zie [Ledenverzoeken](#ledenverzoeken)).

![member actions](/assets/images/member_actions1.png)

- Met het drop-down menu en de "Uitvoeren" knop kan je acties uitvoeren op meerdere leden tegelijkertijd, zie [Ledenacties](#ledenacties)

![member actions](/assets/images/member_actions2.png)		
		
## Ledenacties

### Exporteer

(weergave leden)

Data van de leden kan geexporteerd worden naar een excel file. Vink eerst de leden aan, selecteer "exporteer" in het drop-down menu en klik op "uitvoeren".

In het geopende scherm kan je de layout van de excel file definiëren: selecteer of deselecteer data die je wel of niet wilt zien. Ook de volgorde van de kolommen kan aangepast worden door ze hoger of lager te plaatsen.

![Export excel](/assets/images/export_excel.png)

### Genereer QR 

(weergave leden)

QR-codes van leden kunnen ook afgedrukt worden. Met deze codes kunnen leden gescand worden om hun aanwezigheid op de meeting te bevestigen (zie [QR scanning](qr-scanning.md)). Vink in het overzicht de leden aan, selecteer "Genereer QR" in het drop-down menu en klik op uitvoeren. Een PDF bestand met de gewenste QR codes wordt geopend.

![QR codes](/assets/images/generate_qr.png)

### Aanwezigheidslijst 

(weergave leden)

Genereer een rapport met de aanwezigheden per lid. Vink eerst een aantal leden aan in het overzichtsscherm, selecteer "aanwezigheidslijst" in het drop-down menu en klik op "uitvoeren", het aanwezigheidslijstscherm wordt geopend.
		
Bovenaan vind je een overzicht met de geselecteerde leden, met X kan je eventueel nog leden terug verwijderen.

![attendance list](/assets/images/attendance_list1.png)	
		
In het onderste deel kan je de meetings filteren waarvoor je de aanwezigheidslijst wilt genereren, eens de juiste parameters zijn ingevuld, klik op "ok" en de resultaten worden zichtbaar. Wens je de lijst gemakkelijk te kunnen afdrukken, klik dan op (1) en er wordt een PDF gegenereerd met hetzelfde overzicht.

![attendance list](/assets/images/attendance_list2.png)

### Team aanmaken 

(weergave leden)

Met deze functie kan je op een snelle manier een nieuw team aanmaken. Vink in het overzicht de leden aan die in het team moeten toegevoegd worden, selecteer "Team aanmaken". Op de volgende pagina
vul je de naam van het team in, klik je op bewaar en het team is aangemaakt. (zie [Teams](settings.md#teams))

### Betaling aanmaken 

(weergave leden)

Deze actie kan gebruikt worden om voor meerdere leden tegelijk een losse betaling aan te maken. Vink in het overzicht de gewenste leden aan en selecteer "Betaling aanmaken". Op de volgende pagina
kan je een bedrag en een beschrijving invullen en eventueel betalingsregels toevoegen. Klik op bewaar en de geselecteerde leden krijgen een melding dat hen een betaling wacht. Voor meer uitleg
over betalingen zie [Betalingen](payments.md))

![create payment](/assets/images/memberactions_payment.png)

### Maak een groepschat 

(weergave leden)

Vink in het overzicht de gewenste leden aan en selecteer "Maak een groepschat". Op de volgende pagina kan je een bericht aanmaken om te versturen en de chat te openen.

### Vragenlijst opsturen 

(weergave leden)

Met deze functionaliteit kan je naar alle of een deel van jouw leden vragen opsturen die dienen beantwoord worden. Hiervoor dien je eerst vragen en vragenlijsten te definiëren (zie [Vragenlijsten](settings.md#vragenlijsten)).

Vink in het overzicht de leden aan die vragen moeten ontvangen en selecteer "Vragenlijst opsturen" en uitvoeren. Op de volgende pagina krijg je een overzicht van de geselecteerde leden en dien je
een vragenlijst te selecteren. Duw op ok om te verzenden. Let op: enkel leden gekoppeld aan een gebruikersprofiel kunnen een vragenlijst ontvangen.

![send questionnaire](/assets/images/send_questionnaire.png)

### Bewerk abonnementen 

(weergave abonnementen)

Deze functie kan gebruikt worden indien je bij verschillende leden tegelijk een abonnementsaanpassing wilt doen. Vink in het overzicht de leden aan, selecteer "Bewerk abonnementen" in het drop-down menu en klik op uitvoeren. Het abonnementenscherm wordt geopend.
		
Bovenaan vind je een overzicht met de geselecteerde leden, met X kan je eventueel nog leden terug verwijderen.

![mass subscriptions](/assets/images/mass_subscriptions1.png)	
		
In het onderste deel kan je gewenste actie selecteren:
- Nieuw abonnement toevoegen: alle geselecteerde leden krijgen een nieuwe abonnement toegevoegd. Selecteer het gewenste abonnement en pas eventueel de standaardprijs nog aan. Klik op "Bewaar".
Om abonnementen te definiëren zie [Abonnementen](settings.md#abonnementen)

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

Om een ledenverzoek af te wijzen klik je op het verwijder symbool. Indien je ervoor opteert het ledenverzoek af te wijzen wordt het onherroepelijk verwijderd. 

Door te klikken op een ledenverzoek opent zich een nieuw scherm waarin je het ledenverzoek kan aanpassen en aanvaarden.

Volgende stappen worden doorlopen:

### Verzoek

![member request](/assets/images/member_request_request.png)	

**Verzoek**

Meer details over de persoon die lid wil worden van de club:
- Foto
- E-mail
- Telefoon
- Geboortedatum
- Geslacht

**Antwoorden**

De antwoorden op de eventuele vragen die je opgesteld had voor nieuwe leden (zie [Lid verzoek vragen](settings.md#lid-verzoek-vragen))

**Koppel**

Indien je voor dit lid reeds eerder een profiel had aangemaakt kan je het bestaande profiel met het echte lid koppelen (zie [Toevoegen leden](#toevoegen)). Op deze manier wordt de door jou reeds
ingegeven informatie bewaard.

### Persoonlijk

![member request](/assets/images/member_request_personal.png)	

In deze stap zie je alle informatie over de gebruiker in detail. Eventueel kan je deze nog aanpassen of aanvullen.

- Persoonlijke info
- Adres
- Telefoon
- E-mail

Telefoon en e-mail zijn reeds ingevuld met de gegevens die de gebruiker heeft opgegeven. Deze zijn niet aanpasbaar en worden steeds automatisch gesynchroniseerd gehouden elke keer de gebruiker deze aanpast.
Het is wel mogelijk extra telefoonnummers of e-mailadressen toe te voegen.

### Lid

![member request](/assets/images/member_request_member.png)	

**Rollen**

Verander de autorisaties van het lid in Squatix door hem een of meerdere rollen toe te kennen (zie [Rollen](settings.md#rollen))

**Teams**

Ken het nieuwe lid toe aan een of meerdere teams (zie [Teams](settings.md#teams)). Indien je de standaardvraag "Aan welk team moet je toegevoegd worden" actief gezet hebt 
(zie [Lid verzoek vragen](settings.md#lid-verzoek-vragen)) zie je hier het antwoord van het nieuwe lid en is hij al automatisch toegevoegd aan het team van zijn keuze. Dit kan nog aangepast worden.

Indien je in stap1 gekoppeld hebt met een bestaand profiel en deze was al aan teams toegekend blijven deze ook hier behouden.

**Abonnementen**

Hier kan je onmiddelijk een of meerdere abonnementen toekennen. Indien je de standaardvraag "Welk abonnement wens je" actief gezet hebt 
(zie [Lid verzoek vragen](settings.md#lid-verzoek-vragen)) zie je hier het antwoord van het nieuwe lid en is het gekozen abonnement al automatisch toegevoegd. Dit kan nog aangepast worden.

Indien je in stap1 gekoppeld hebt met een bestaand profiel en deze had al een abonnement blijven deze ook hier behouden.

### Aanvaarden

Zodra je op aanvaarden klikt wordt het lid aan jouw club toegevoegd met de gekozen opties.
		
## Detail
Wijzigingen die doorgevoerd worden in de detailpagina van een lid hebben enkel betrekking op de details van het lid in de club zelf. Deze worden dus niet aangepast 
of overschreven in het gebruikersprofiel van het lid. Beide profielen staan los van elkaar.

![member details heading](/assets/images/member_detail_heading.png)

In de bovenste sectie kan je het volgende terugvinden:
- Foto: uploaden van een foto voor het lid, deze staat los van de eigen foto die het lid in zijn profiel heeft toegevoegd en zal deze dus niet overschrijven
- Gekoppeld aan gebruikersprofiel: dit label wordt getoond indien een fysieke gebruiker aan dit lid gekoppeld is (na een ledenverzoek, zie [Ledenverzoeken](#ledenverzoeken))
- Inactief maken: door een lid inactief te maken is hij niet meer aanpasbaar maar telt hij ook niet meer mee in het aantal leden (voor berekening van het clubabonnement).
Zijn profiel kan wel nog bekeken worden door te zoeken op inactieve leden in het overzicht (zie [Overzicht](#overzicht)).

Opgelet, volgende gevolgen zijn onomkeerbaar: (1) Het lid wordt verwijderd uit alle toekomstige meetings waarvoor het ingeschreven is (2) Indien hij als trainer gekoppeld is aan een meetingscategorie wordt 
deze koppeling verwijderd (3) Indien een fysieke gebruiker gekoppeld is aan dit lid wordt de connectie verwijderd en heeft deze gebruiker geen toegang meer tot de club

- Lid verwijderen: een lid verwijderen heeft dezelfde gevolgen als een lid inactief maken maar hij wordt ook verwijderd uit de lijst met leden en zijn ledenprofiel
kan op geen enkele manier meer bekeken worden. Deze actie is onomkeerbaar. 

### Abonnement

Er wordt een overzicht getoond van alle actieve en inactieve (vorige) abonnementen.  
In het bovenste deel van het scherm worden alle actieve abonnementen getoond en de mogelijke acties op deze abonnementen.  
In het onderste deel van het scherm wordt een overzicht van de vorige abonnementen getoond, deze zijn niet meer aanpasbaar.

![member details subscriptions](/assets/images/member_detail_subscriptions.png)

**Actieve abonnementen**  

Het werken met abonnementen is optioneel. Een lid kan echter ook meerdere actieve abonnementen hebben. De beheerder kan dus zelf kiezen welke aanpak hij verkiest.

Om een nieuw actief abonnement toe te voegen, klik op het +-teken. Het scherm om een nieuw abonnement te selecteren opent zich. 

![member details subscriptions](/assets/images/member_detail_subscriptions_new.png)

Het drop-down menu bevat de vooraf gedefinieerde abonnementen (zie [Abonnementen](settings.md#abonnementen))

Na het selecteren van een abonnement worden de details geladen. Het is nog mogelijk twee parameters aan te passen:

- Prijs: vul een ander bedrag in dan vooraf gedefinieerd
- Groepsabonnement: door het vakje "Groepsabonnement" aan te vinken kan je een of meerdere leden toevoegen aan dit abonnement. Zij zullen dan samen met het huidige lid gebruik kunnen maken van dit abonnement.
Het abonnement zal ook verschijnen op de detailpagina van deze leden. Indien het een beurtenkaart betreft en een van de leden verbruikt een beurt zal deze er bij allen afgetrokken worden.

![member details subscriptions](/assets/images/member_detail_subscriptions_new_detail.png)

Om een actief abonnement aan te passen klik op het potloodje. Het aantal beurten kan gewijzigd worden en de groepsabonnement-optie.

Vorige aanpassingen aan het abonnement kunnen bekeken worden door op het oogje te klikken.

Om een abonnement inactief te maken, klik op "inactief maken" op het bewuste abonnement. Het abonnement verdwijnt naar de sectie "Vorige abonnementen" en is niet meer 
aanpasbaar. Dit kan niet ongedaan gemaakt worden.

**Vorige abonnementen**

Dit toont een overzicht van inactieve abonnementen. Indien er aanpassingen geweest zijn aan dit abonnement kunnen deze bekeken worden door op het pijltje aan de rechterkant 
te klikken (enkel getoond indien er aanpassingen waren).

### Lid gegevens

**Extra info**

Volgende informatie kan je hier bekijken:

- Lid sinds welke datum
- Gekoppelde gebruiker

![member details extra info](/assets/images/member_detail_extrainfo.png)

**Teams**

Ken het lid toe aan een of meerdere teams (zie [Teams](settings.md#teams))

**Rollen**

Verander de autorisaties van het lid in Squatix door hem een of meerdere rollen toe te kennen (zie [Rollen](settings.md#rollen))

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

Het e-mailadres en telefoonnummer dat het lid gebruikt in Squatix worden automatisch gesynchroniseerd en kunnen niet door de beheerder van de club aangepast worden. Dit geldt natuurlijk enkel voor
gekoppelde leden.

### Meetings

Hier kan je een overzicht krijgen van alle meetings waarop het lid ingeschreven is (verleden en toekomst). 

Om gerichter te zoeken kan je de meetings filteren op:
- Naam
- Categorie
- Startdatum

![member details subscriptions](/assets/images/member_detail_trainings.png)

## Vrijwilligers

Je kan leden van je club de vrijwilligersrol toekennen. Vrijwilligers kunnen zich inschrijven op vrijwillgerstaken bij meetings. Om een lid vrijwilliger te maken, ga je naar de detailpagina van het lid. 
Onder de tab 'Lid gegevens' zet je het 'Vrijwilliger'-knopje aan onder de sectie 'Rollen' (zie [Lid gegevens](#lid-gegevens)). Leden kunnen ofwel lid ofwel vrijwilliger zijn of beide. Een lid die de lid-rol niet heeft 
maar wel de vrijwilligers-rol, kan zich niet inschrijven om deel te nemen aan meetings. Een lid die beide heeft kan zich zowel inschrijven om deel te nemen als zich inschrijven voor een vrijwilligerstaak. 
Om vrijwilligerstaken toe te voegen aan een meeting, zie [Meetings](meetings.md#vrijwilligers).

![member volunteer roles](/assets/images/volunteer_roles.png)

## Formulieren

Krijg een overzicht van de opgestuurde formulieren in jouw club en hun actuele status. Klik op een formulier om de details te zien of (indien in status "wachten op beheerder") te verwerken.

![forms overview](/assets/images/forms_overview.png)

De mogelijke soorten formulieren:
- Lid gegevens: een lid heeft zijn persoonlijke gegevens (adres, geboortedatum, ...) aangepast. Verwerk het formulier om deze gegevens ook in jouw club op te slaan of aan te passen.
- Leden vragen: je hebt een vragenlijst opgestuurd en een lid heeft deze beantwoord. Open het antwoord om de antwoorden te bekijken en eventueel door te voeren (bv nieuwe abonnementen).

![forms detail](/assets/images/forms_detail.png)


