---
layout: admin
---

# 4 QR scanning			
	
# 5 Ledenbeheer

## 5.1 Overzicht
	
Standaard worden alle actieve leden getoond, alfabetisch gerangschikt op voornaam. Met de pijltjes naast voornaam en achternaam is het mogelijk de resultaten op een andere manier te rangschikken. Het is mogelijk verschillende filters toe te passen:
- naam (er wordt gezocht in zowel voor- en achternaam)
- toon inactieve leden (deze verschijnen in het grijs tussen de actieve leden)
- type lid (gekoppelde leden gebruiken Squatix, niet-gekoppelde leden zijn niet gekoppeld met een echte gebruiker)
- rol (zie [Rollen](#rollen))
- status abonnement (geldig of niet meer geldig)
- type abonnement (met beurten of enkel met een geldigheidsdatum)
- abonnementscategorie (zie [Abonnement](#abonnement))
- trainingscategorie (filter wordt enkel getoond indien een abonnementscategorie is geselecteerd, filter bevat de trainingscategorieën gelinkt aan dit abonnement, zie ([AbonnementsCategorieën](#abonnementscategorieën))

![member list](/assets/images/member_list.png)
		
Een van de extra filters weer verwijderen kan door op "meer filters" te klikken en deze weer leeg te maken of door te klikken op het kruisje naast de desbetreffende filter.

**Acties**
- Nieuwe leden toevoegen kan via "Voeg toe" (zie [Toevoegen](#toevoegen)).
- Rollen bewerken kan via "Rollen" (zie [Rollen](#rollen)).
- Indien er ledenverzoeken zijn wordt dit hier getoond (zie [Ledenverzoeken](#ledenverzoeken)).

![member actions](/assets/images/member_actions1.png)

- Met het drop-down menu en de "Uitvoeren" knop kan je acties uitvoeren op meerdere leden tegelijkertijd, zie [Ledenacties](#ledenacties)

![member actions](/assets/images/member_actions2.png)		
		
## 5.2 Ledenacties
### Abonnementen bewerken
Deze functie kan gebruikt worden indien je bij verschillende leden tegelijk een abonnementsaanpassing wilt doen. Vink in het overzicht de leden aan, selecteer "Bewerk abonnementen" in het drop-down menu en klik op uitvoeren. Het abonnementenscherm wordt geopend.
		
Bovenaan vind je een overzicht met de geselecteerde leden, met X kan je eventueel nog leden terug verwijderen.

![mass subscriptions](/assets/images/mass_subscriptions1.png)	
		
In het onderste deel kan je gewenste actie selecteren:
- Nieuw abonnement toevoegen: alle geselecteerde leden krijgen een nieuwe abonnementen toegevoegd. Dit nieuw abonnement moet compatibel zijn met hun bestaande actieve abonnementen. Selecteer de gewenste opties van dit nieuwe abonnement en klik op "Bewaar"

![mass subscriptions](/assets/images/mass_subscriptions2.png)

- Abonnement verlengen: alle geselecteerde abonnementen van de geselecteerde leden worden verlengd. Selecteer de termijn en klik op "Bewaar"

![mass subscriptions](/assets/images/mass_subscriptions3.png)		
		
		
### QR genereren
QR-codes van leden kunnen ook afgedrukt worden. Met deze codes kunnen leden gescand worden om hun aanwezigheid op de training te bevestigen (zie [QR scanning](#qr-scanning)). Vink in het overzicht de leden aan, selecteer "Genereer QR" in het drop-down menu en klik op uitvoeren. Een PDF bestand met de gewenste QR codes wordt geopend.

![QR codes](/assets/images/generate_qr.png)	
		
### Aanwezigheidslijst
Genereer een rapport met de aanwezigheden per lid. Vink eerst een aantal leden aan in het overzichtsscherm, selecteer "aanwezigheidslijst" in het drop-down menu en klik op "uitvoeren", het aanwezigheidslijstscherm wordt geopend.
		
Bovenaan vind je een overzicht met de geselecteerde leden, met X kan je eventueel nog leden terug verwijderen.

![attendance list](/assets/images/attendance_list1.png)	
		
In het onderste deel kan je de trainingen filteren waarvoor je de aanwezigheidslijst wilt genereren, eens de juiste parameters zijn ingevuld, klik op "ok" en de resultaten worden zichtbaar. Wens je de lijst gemakkelijk te kunnen afdrukken, klik dan op (1) en er wordt een PDF gegenereerd met hetzelfde overzicht.

![attendance list](/assets/images/attendance_list2.png)	
		
		
## 5.3 Toevoegen
Deze functie laat jou toe om leden toe te voegen en hun details te bewaren, ook al gebruiken ze Squatix niet. Indien ze toch later Squatix beginnen gebruiken en een lidverzoek voor jouw club indienen kan je het door jou aangemaakte profiel met de echte gebruiker linken. (zie [Ledenverzoeken](#ledenverzoeken))
Velden die je kan invullen zijn:
- voornaam (verplicht)
- achternaam (verplicht)
- email (optioneel)
- telefoon (optioneel)
- geboortedatum (optioneel)
- geslacht (optioneel)
- nationaliteit (optioneel)
- adres (optioneel)
	- straat
	- huisnummer
	- gemeente
	- postcode 
	- land

## 5.4 Ledenverzoeken
	
## 5.5 Rollen
Met rollen kan je jouw leden toegang geven tot bepaalde functionaliteiten of pagina's waar een lid zonder die rol geen toegang toe heeft. Op de rollen-pagina kan je de verschillende rollen en hun permissies voor jouw club definiëren. Daarna kan je in de detail pagina van een lid hem een van die rollen toekennen (zie [Lid gegevens](#lid-gegevens).

![roles](/assets/images/roles.png)	

Volgende permissies kunnen aan een rol gegeven worden:
- Club info wijzigen ()
- Club chat ()
- Leden lezen ()
- Leden wijzigen ()
- Rollen beheren ()
- Trainer ()
- Trainingen wijzigen ()

Standaard rollen die niet kunnen verwijderd of aangepast worden:
- Eigenaar (Alle permissies, uitgezonder trainer. Enkel toegekend aan persoon die de club aangemaakt heeft, kan beheerders aanduiden of verwijderen.)
- Beheerder (Alle permissies, uitgezonderd trainer)
- Trainer (Kan als trainer toegevoegd worden aan een training)
		
## 5.6 Detail

In de bovenste sectie kan je het volgende terugvinden:
- Foto: uploaden van een foto voor het lid, deze staat los van de eigen foto die het lid in zijn profiel heeft toegevoegd en zal deze dus niet overschrijven
- Gekoppeld aan gebruikersprofiel: dit label wordt getoond indien een fysieke gebruiker aan dit lid gekoppeld is (na een ledenverzoek, zie [Ledenverzoeken](#ledenverzoeken)
- Kindprofiel: dit label wordt getoond indien een kindprofiel aan dit lid gekoppeld is 
- Inactief maken: door een lid inactief te maken is hij niet meer aanpasbaar maar telt hij ook niet meer mee in het aantal leden (voor berekening van het clubabonnement). Opgelet, volgende gevolgen zijn onomkeerbaar:
	- Het lid wordt verwijderd uit alle toekomstige trainingen waarvoor het ingeschreven is
	- Indien hij als trainer gekoppeld is aan een trainingscategorie wordt hij verwijderd
	- Indien een fysieke gebruiker gekoppeld is aan dit lid wordt de connectie verwijderd en heeft deze gebruiker geen toegang meer tot de club
- Lid verwijderen: een lid verwijderen heeft dezelfde gevolgen als een lid inactief maken maar hij wordt ook verwijderd uit de lijst met leden, dit is onomkeerbaar. 

### Abonnement

Er wordt een overzicht getoond van alle actieve en inactieve (vorige) abonnementen. In het bovenste deel van het scherm worden alle actieve abonnementen getoond en de mogelijke acties op deze abonnementen. In het onderste deel van het scherm wordt een overzicht van de vorige abonnementen getoond, deze zijn niet meer aanpasbaar.

![member details subscriptions](/assets/images/member_detail_subscriptions.png)

**Actieve abonnementen**  

Het werken met abonnementen is optioneel. Een lid kan echter ook meerdere actieve abonnementen hebben. De beheerder kan dus zelf kiezen welke aanpak hij verkiest. Volgende beperkingen gelden:
- Er kan maar één abonnement zijn van elke abonnementscategorie
- Er kan maar één abonnement zijn zonder abonnementscategorie
- Twee abonnementen kunnen geen overlappende gelinkte trainingscategorieën hebben.

Om een nieuw actief abonnement toe te voegen, klik op het +-teken. Het scherm om een nieuw abonnement aan te maken opent zich. Volgende velden kunnen ingevuld worden:
- Type (verplicht, abonnement of beurten)
- Categorie (optioneel, zie [Abonnementscategorieën](#abonnementscategorieën)
- Categorieën automatisch inschrijven (optioneel, enkel indien abonnementscategorie geselecteerd met gelinkte trainingscategorieën, zie [Abonnementscategorieën](#abonnementscategorieën) en [Automatisch inschrijven](#automatisch-inschrijven))
- Geldig tot (verplicht)
- Beurten over (verplicht indien type beurten geselecteerd)

Om een actief abonnement aan te passen klik op het potloodje. Vorige aanpassingen aan het abonnement kunnen bekeken worden in het scherm dat opent. Om een nieuwe aanpassing door te voeren, klik nogmaals op het potloodje.  

Om een abonnement inactief te maken, klik op "inactief maken" op het bewuste abonnement. Het abonnement verdwijnt naar de sectie "Vorige abonnementen" en is niet meer aanpasbaar.

**Vorige abonnementen**

Dit toont een overzicht van inactieve abonnementen. Indien er aanpassingen geweest zijn aan dit abonnement (geldig-tot datum, aantal beurten, ...) kunnen deze bekeken worden door op het pijltje aan de rechterkant te klikken (enkel getoond indien er aanpassingen waren).


### Lid gegevens

**Extra info**

- Lid sinds welke datum
- Indien kindprofiel: wie zijn de gekoppelde ouders

**Rollen**

Verander de autorisaties van het lid in Squatix door hem een of meerdere rollen toe te kennen (zie [Rollen](#rollen)

**Opmerkingen**

Vrij tekstveld om algemene opmerkingen over het lid te bewaren


![member details subscriptions](/assets/images/member_detail_memberdetails.png)

### Persoonlijk

![member details subscriptions](/assets/images/member_detail_personal.png)

### Trainingen
Hier kan je een overzicht krijgen van alle trainingen waarop het lid ingeschreven is (verleden en toekomst)

![member details subscriptions](/assets/images/member_detail_trainings.png)

# 6.Instellingen
## 6.1 Trainingscategorieën
Om een trainingscategorie toe te voegen, klik op "Voeg toe". 
Volgende data kan ingegeven worden:
- Naam
- Kleur: wordt weergegeven in de trainingskalender om trainingen met een verschillende categorie van elkaar te kunnen onderscheiden
- Inschrijven: enkel leden met een geldig abonnement kunnen inschrijven op de training of alle leden kunnen inschrijven
- Trainers: selecteer trainers die automatisch zullen ingevuld worden bij het aanmaken van een training van deze categorie

![Training category](/assets/images/training_categorie.png)

Voor het aanpassen van een trainingscategorie: klik op het potloodje

## 6.2 Abonnementscategorieën
Abonnementscategorieën zijn optioneel. Het is ook mogelijk een abonnement aan te maken zonder categorie.

Om een abonnementscategorie toe te voegen, klik op "Voeg toe". 
Volgende data kan ingegeven worden:
- Naam
- Gelinkte trainingscategorieën: link een van de aangemaakte trainingscategorieën aan de abonnementscategorie. Op deze manier kan je bepalen voor welke trainingen een lid kan inschrijven (indien de trainingscategorie enkel voor een geldig abonnement inschrijfbaar is) of voor welke trainingen een lid automatisch kan ingeschreven worden (zie [Automatisch inschrijven](#automatischinschrijven))

![Subscription category](/assets/images/subscription_categorie.png)
			
Aanpassen van een Abonnementscategorie: klik op het potloodje
		
## 6.3 Lid verzoek vragen
Wanneer leden een verzoek verzenden om lid te worden van jouw club kan je hen vragen een aantal vragen te beantwoorden. Zo kan je bijvoorbeeld vragen of ze ook een vrijwillige functie in de club willen uitvoeren, voor welke afdeling ze zich inschrijven in jouw club enzovoort. De antwoorden van het lid zie je bij hun lidverzoek (zie [Lidverzoeken](#lid-verzoeken)). De vragen en antwoorden kunnen aangemaakt worden in verschillende talen. De vraag zal voor de gebruiker automatisch verschijnen in de taal die hij in zijn profiel ingevuld heeft.

![member question](/assets/images/member_question.png)
		
Om een nieuwe vraag aan te maken, klik op "Voeg toe".Onder "Vraag" vul je de vraag in. Klik op "Vertaling toevoegen" om de vraag in meerdere talen beschikbaar te stellen.
Onder "Antwoorden" vul je een mogelijk antwoord op de vraag in. Klik op "Vertaling toevoegen" om het antwoord in meerdere talen beschikbaar te stellen. Klik op + om een extra mogelijk antwoord op de vraag toe te voegen.

Om de vraag te bewaren klik je op "Bewaar". Het volgende lid dat lid wil worden van de club zal de vraag dienen te beantwoorden.
		
Om een eerder aangemaakte vraag aan te passen, klik op het potloodje. Hetzelfde scherm als bij het aanmaken van een vraag opent zich met de reeds eerder ingevulde waarden.
	
## 6.4 Club
Onder club kan je volgende dingen bekijken:
- Bekijk het abonnement waarover de club beschikt bij squatix en de geldigheidsdatum. Zodra de geldigheidsdatum is overschreden is het niet meer mogelijk nieuwe leden toe te voegen.
- Agenda delen: Het is mogelijk de trainingskalender te gebruiken in een externe kalender applicatie die ICS ondersteunt. Kopieër daartoe de ics-url naar de benodigde plaats. Voor ondersteuning neem contact op met het team dat de applicatie aanbiedt.

![club settings](/assets/images/club_settings.png)

# 7 Chats
De leden van jouw club kunnen een privé-bericht versturen naar de beheerders van de club. Deze berichten zullen verschijnen in het "chats"-scherm. Alle beheerders kunnen hierop antwoorden en de antwoorden zullen ook zichbaar worden voor de andere beheerders.
