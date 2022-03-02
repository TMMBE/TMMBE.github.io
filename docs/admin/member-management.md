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
		
## Ledenacties
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
		
		
## Toevoegen
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

## Ledenverzoeken
	
## Rollen
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
		
## Detail

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
