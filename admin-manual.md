---
layout: default
description: Handleiding beheerder
---
* TOC
{:toc}

# Clubdetails
## Clubinfo

Vul informatie in over jouw club, zichtbaar voor jouw leden. Mogelijke velden zijn:
- Beschrijving
- Adres
- Contactinformatie (naam contactpersoon, e-mail, telefoonnummer)
- Website

![clubinfo](/assets/images/club_info.png)

## Logo

Upload een logo, zichtbaar voor jouw leden

![logo](/assets/images/upload_logo.png)

# Berichten
Via berichten kan je alle leden die jouw app gebruiken in éénmaal bereiken. Elk lid wordt op de hoogte gebracht dat je een bericht geplaatst hebt door middel van een e-mail of gsmnotificatie (afhankelijk van hun instellingen). Berichten laten tekst en een afbeelding toe. Gebruikers kunnen jouw bericht zien en erop reageren. Je wordt eveneens op de hoogtegebracht van reacties door middel van een notificatie. Berichten kunnen verwijderd of bewerkt worden waarna het bericht de editeerdatum zal tonen (bewerken) of "bericht verwijderd" (verwijderen).

# Trainingen
## Overzicht 
In het trainingsoverzicht zie je alle trainingen voor de geselecteerde maand. 

![training_overview](/assets/images/training_buttons.png)
		
Bovenaan kan je kiezen voor kalenderzicht (1) of lijstzicht (2). 
De knop mijn trainingen (3) toont de trainingen waarop het ingelogde lid is ingeschreven (trainer?) (verleden of toekomst). 
Via de QR-code knop (4) kom je in de scanning module terecht waar de QR-code van een lid kan worden gescand. (zie QR scanning)
Via de knop trainingen aanmaken kan je een nieuwe training creëren (zie [Editeer/creeër training](#editeercreeër-training))
Aanklikken van een training opent de training detail pagina

## Detail
De training detail pagina toont volgende training info:
- Titel
- Start- en eind datum 
- Categorie 
- Locatie (Optioneel)
- Beschrijving (Optioneel)
- Aantal bezette plaatsen indien deelnemersbeperking (Optioneel)

In de deelnemers tabel zie je de ingeschreven deelnemers. Via + kan je zelf leden handmatig inschrijven voor de training. Wanneer een beheerder een lid handmatig inschrijft is het mogelijk om ook deelnemers met een ongeldig abonnement in te schrijven, zelfs indien ingesteld is dat de training categorie enkel voor leden met een geldig abonnement is (zie ([TrainingsCategorieën](#trainingscategorieën)). Wanneer een lid zichzelf wilt inschrijven moet hij wel aan deze regel voldoen.
		 
De deelnemers tabel toont: 
- Voornaam/achternaam van het lid
- Geldigheid van zijn abonnement tov de training
- Of de deelnemer aanwezig was (bevestigd)
- Verwijderknop.

Een deelnemer kan bevestigd worden voor de training indien zijn QR-code gescand wordt of indien op "bevestigen" geklikt wordt in de deelnemers tabel.

### Trainingsacties
**Training geschiedenis** 
Hier worden alle gebeurtenissen die plaatsvinden op de training getoond:
- Aanpassing details training (lid + beheerder)
- Deelnemer schrijft zich uit (Beheerder)
- Beheerder schrijft deelnemer manueel in (Beheerder)
- Beheerder schrijft deelnemer manueel uit (Beheerder)
- Training aangemaakt (Lid + beheerder)
- Training geannulleerd (Lid + beheerder)
- Trainers aangepast (Beheerder)
			
**Editeer training**, (zie [Editeer/creeër training](#editeercreeër-training))
		
**Maak kopie** 
Toon de bewerk training pagina met alle velden ingevuld gelijk aan de waardes van de training waarvan een kopie gemaakt is.

**Verwijder**
Dit is enkel mogelijk indien er nog geen ingeschreven deelnemers zijn of indien de training eerst geannuleerd is. Verwijderen kan niet ongedaan gemaakt worden.

**Annuleer training** 
Training krijgt status "geannuleerd". Alle ingeschreven deelnemers krijgt een notificatie. 
	
## Editeer/creeër training
	
Om trainingen te kunnen aanmaken dien je over minstens 1 trainingscategorie te beschikken. (zie ([TrainingsCategorieën](#trainingscategorieën)))
	
Volgende velden kan je invullen:
- Titel (verplicht)
- Start datum/uur (verplicht)
- Eind datum/uur (verplicht)
- Locatie (optioneel)
- Beschrijving (optioneel)
- Categorie (verplicht)
- Trainers (optioneel)
- Automatisch alle leden inschrijven die aan de categorie zijn gekoppeld (optioneel)
- Beperk deelnemers (optioneel)
- Herhaal training (optioneel)

**Categorie**
Trainingscategorieën kunnen aangemaakt worden in de instellingen, zie ([TrainingsCategorieën](#trainingscategorieën))

**Trainers**
Hier kan je een of meerdere trainers toevoegen. Dit kan op twee manieren:
- Manueel: klik op "voeg trainer toe" en selecteer de trainer. Enkel leden met een trainer-rol worden getoond. Voor het toekennen van de trainer-rol zie ()
- Automatisch: indien een trainer gelinkt is aan de gekozen trainingscategorie wordt hij automatisch ingevuld. Voor het linken van trainers aan een categorie zie ([AbonnementsCategorieën](#abonnementscategorieën). Wens je de trainer toch niet toe te voegen aan de trainer of wil je hem later weer verwijderen, klik op ()

Het is ook mogelijk deze trainers te vragen om hun aanwezigheid te bevestigen. Dit doe je door () aan te vinken. De trainer ontvangt een notificatie dat hij zijn aanwezigheid moet bevestigen. Bevestigen kan hij op de detail pagina van de training of in zijn "mijn trainingen"-pagina waar hij een overzicht heeft op alle trainingen die hij nog moet
bevestigen. Indien de trainer aangeeft dat hij niet aanwezig kan zijn dient hij een vervanger te kiezen uit de andere beschikbare trainers.

**Automatisch alle leden inschrijven die aan de categorie zijn gekoppeld**
Indien je dit aanvinkt wordt de training aangeduid als "automatisch inschrijven". Dit houdt in dat na creatie van de training alle leden van jouw club als deelnemer zullen toegevoegd worden aan de training indien ze aan volgende criteria voldoen:
- Geldig abonnement op datum van de training:
	- Geldigheidsdatum later dan de begintijd
	- Abonnementscategorie is gelinkt aan de trainingscategorie (zie ([AbonnementsCategorieën](#abonnementscategorieën)))
	- Met aantal resterende beurten wordt geen rekening gehouden.
- Niet aangeduid als trainer voor de training
- De trainingscategorie is geselecteerd onder "Categorieën automatisch inschrijven" op het overeenkomende abonnement (zie [Abonnement](#abonnement))
- Lid is niet inactief
- Lid heeft zich niet eerder manueel uitgeschreven van de training (enkel toepasbaar indien training eerder aangemaakt werd als "gewone" training en pas later aangepast werd naar "automatisch inschrijven" - training)
			
Indien een training aangeduid is als "automatisch inschrijven" wordt bij verschillende acties gekeken of de deelnemerslijst automatisch moet aangepast worden:
- Aanvinken "automatisch inschrijven" bij aanpassen/aanmaken training
- Verwijderen/toevoegen van trainers
- Veranderen categorie van de training
- Aanvaarden/toevoegen van een nieuw lid in de club (zie [Ledenbeheer](#ledenbeheer))
- Aanpassen van een abonnement van een lid (zie [Abonnement](#abonnement))
- Toewijzen/verwijderen van een trainingcategorie bij een abonnementscategorie
		
**Beperk deelnemers**
Geef een maximum aantal deelnemers voor de training in. Leden zullen niet zelf kunnen inschrijven voor een training die volgeboekt is.
Met deze instelling wordt geen rekening gehouden in volgende gevallen: 
- Wanneer een beheerder zelf manueel een deelnemer toevoegt aan de training
- Wanneer de training aangeduid is als "automatisch inschrijven" en er hierdoor leden automatisch moeten toevoegd worden
		
**Herhaal training**
Deze optie is enkel beschikbaar bij het aanmaken van een nieuwe training. 
Kies de dagen in de week waarop deze training zich moet herhalen (de dag van de intieële training dient steeds geselecteerd te worden). Kies ook de datum waarop de herhaling dient te stoppen (maximum 1 jaar in de toekomst). Zodra de training wordt aangemaakt worden op de opgegeven dagen identieke kopieën gecreerd.
		
**Bewaren** 
Indien een training wordt aangepast en deze onderdeel is van een serie wordt bij het bewaren van de training gevraagd of enkel de geopende training moet aangepast worden of de aanpassing moet doorgevoerd worden in (een deel van) de serie. 
Indien serie aangeduid wordt: selecteer de trainingen waarop de aanpassing moet doorgevoerd worden (standaard staat elke training van de serie geselecteerd) en klik op bewaren. Alle geselecteerde trainingen zullen nu aangepast worden met de ingegeven veranderingen.

# QR scanning			
	
# Ledenbeheer

## Overzicht
	
Standaard worden alle actieve leven getoond, alfabetisch gerangschikt op voornaam. Met () en () is het mogelijk de resultaten op een andere manier te rangschikken. Het is mogelijk verschillende
filters toe te passen:
- naam (er wordt gezocht in zowel voor- en achternaam)
- toon inactieve leden (deze verschijnen in het grijs tussen de actieve leden)
- type lid (gekoppelde leden gebruiken Squatix, niet-gekoppelde leden zijn niet gekoppeld met een echte gebruiker)
- rol (zie)
- status abonnement (geldig of niet meer geldig, beurten tellen WEL/NIET mee?)
- type abonnement (met beurten of enkel met een geldigheidsdatum)
- abonnementscategorie (zie ([Abonnement](#abonnement))
- trainingscategorie (filter wordt enkel getoond indien een abonnementscategorie is geselecteerd, filter bevat de trainingscategorieën gelinkt aan dit abonnement, zie ([AbonnementsCategorieën](#abonnementscategorieën))
		
Een van de extra filters weer verwijderen kan door op "meer filters" te klikken en deze weer leeg te maken of door te klikken p het kruisje naast de desbetreffende filter.
		
Nieuwe leden toevoegen kan via "Voeg toe" (zie ([Toevoegen](#toevoegen))
Rollen bewerken kan via "Rollen" (zie ([Rollen](#rollen))
Met het drop-down menu en de "Uitvoeren" knop kan je acties uitvoeren op meerdere leden tegelijkertijd, zie ([Ledenacties](#ledenacties)
Indien er ledenverzoeken zijn wordt dit hier getoond (zie ([Ledenverzoeken](#ledenverzoeken))
		
		
## Ledenacties
### Abonnementen bewerken
Deze functie kan gebruikt worden indien je bij verschillende leden tegelijk een abonnementsaanpassing wilt doen. Vink in het overzicht de leden aan, selecteer "Bewerk abonnementen" in het drop-down menu en klik op uitvoeren. Het abonnementenscherm wordt geopend.
		
Bovenaan vind je een overzicht met de geselecteerde leden, met () kan je eventueel nog leden terug verwijderen.
		
In het onderste deel kan je gewenste actie selecteren:
- Nieuw abonnement toevoegen: alle geselecteerde leden krijgen een nieuwe abonnementen toegevoegd. Dit nieuw abonnement moet compatibel zijn met hun bestaande actieve abonnementen. Selecteer de gewenste opties van dit nieuwe abonnement en klik op "bewaar"
- Abonnement verlengen: alle geselecteerd abonnementen van de geselecteerde leden worden verlengd. Selecteer de termijn en klik op "bewaar"
		
		
		
### QR genereren
QR-codes van leden kunnen ook afgedrukt worden. Met deze codes kunnen leden gescand worden om hun aanwezigheid op de training te bevestigen (zie ([QR scanning](#qr-scanning)). Vink in het overzicht de leden, selecteer "Genereer QR" in het drop-down menu en klik op uitvoeren. Een PDF bestand met de gewenste QR codes wordt geopend.
		
### Aanwezigheidslijst
Genereer een rapport met de aanwezigheden per lid. Vink eerst een aantal leden aan in het overzichtsscherm, selecteer "aanwezigheidslijst" in het drop-down menu en klik op "uitvoeren", het aanwezigheidslijstscherm wordt geopend.
		
Bovenaan vind je een overzicht met de geselecteerde leden, met () kan je eventueel nog leden terug verwijderen.
		
In het onderste deel kan je de trainingen filteren waarvoor je de aanwezigheidslijst wilt genereren, eens de juiste parameters zijn ingevuld, klik op "ok" en de resultaten worden zichtbaar. Wens je de lijst gemakkelijk te kunnen afdrukken, klik dan op () en er wordt een PDF gegenereerd met hetzelfde overzicht.
		
		
## Toevoegen
Deze functie laat jou toe om leden toe te voegen en hun details te bewaren, ook al gebruiken ze Squatix niet. Indien ze toch later Squatix beginnen gebruiken en een lidverzoek voor jouw club indienen kan je het door jou aangemaakte profiel met de echte gebruiker linken. (zie ([Ledenverzoeken](#ledenverzoeken))
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
Met rollen kan je jouw leden toegang geven tot bepaalde functionaliteiten of pagina's waar een lid zonder die rol geen toegang toe heeft. Op de rollen-pagina kan je de verschillende rollen en hun permissies voor jouw club definiëren. Daarna kan je in de detail pagina van een lid hem een van die rollen toekennen (zie ([Lid gegevens](#lid-gegevens)).
	
Volgende permissies kunnen aan een rol gegeven worden:
- Club info wijzigen ()
- Club chat ()
- Leden lezen ()
- Leden wijzigen ()
- Rollen beheren ()
- Trainer ()
- Trainingen wijzigen ()

Standaard rollen die niet kunnen verwijderd op aangepast worden:
- Eigenaar (Alle permissies, uitgezonder trainer. Enkel toegekend aan persoon die de club aangemaakt heeft, kan beheerders aanduiden)
- Beheerder (Alle permissies, uitgezonderd trainer)
		
## Detail
### Abonnement
### Lid gegevens
### Persoonlijk
### Trainingen
Hier kan je een overzicht krijgen van alle trainingen waarop het lid ingeschreven is (verleden en toekomst)

# Instellingen
## Trainingscategorieën
Om een trainingscategorie toe te voegen, klik op "voeg toe". 
Volgende data kan ingegeven worden:
- Naam
- Kleur: wordt weergegeven in de traingskalender om trainingen met een andere categorie van elkaar te kunnen onderscheiden
- Inschrijven: enkel leden met een geldig abonnement kunnen inschrijven op de training of alle leden kunnen inschrijven
- Trainers: selecteer trainers die automatisch zullen ingevuld worden bij het aanmaken van een training van deze categorie

Voor het aanpassen van een trainingscategorie: klik op ()

## Abonnementscategorieën
AbonnementsCategorieën zijn optioneel. Het is ook mogelijk een abonnement aan te maken zonder categorie.

Om een abonnementscategorie toe te voegen, klik op "voeg toe". 
Volgende data kan ingegeven worden:
- Naam
- Gelinkte trainingscategorieën: link een van de aangemaakte trainingscategorieën aan de abonnementscategorie. Op deze manier kan je bepalen voor welke trainingen een lid kan inschrijven (indien de categorie enkel voor geldig abonnement inschrijfbaar is) of voor welke trainingen een lid automatisch kan ingeschreven worden (zie ([Automatisch inschrijven](#automatischinschrijven))
			
Aanpassen van een AbonnementsCategorie: klik op ()
		
## Lid verzoek vragen
Wanneer leden een verzoek verzenden om lid te worden van jouw club kan je hen vragen een aantal vragen te beantwoorden. Zo kan je bijvoorbeeld vragen of ze ook een vrijwillige functie in de club willen uitvoeren, voor welke afdeling ze zich inschrijven in jouw club enzovoort. De antwoorden van het lid zie je bij hun lidverzoek (zie ([Lidverzoeken](#lid-verzoeken)). De vragen en antwoorden kunnen aangemaakt worden in verschillende talen. De vraag zal voor de gebruiker automatisch verschijnen in de taal die hij in zijn profiel ingevuld heeft.
		
Om een nieuwe vraag aan te maken, klik op "voeg toe".
Onder "vraag" vul je de vraag in. Klik op "vertaling toevoegen" om de vraag in meerdere talen beschikbaar te stellen.
Onder "antwoorden" vul je een mogelijk antwoord op de vraag in. Klik op "vertaling toevoegen" om het antwoord in meerdere talen beschikbaar te stellen. Klik op + om een extra mogelijk antwoord op de vraag toe te voegen.

Om de vraag te bewaren klik je op "bewaar". Het volgende lid dat lid wil worden van de club zal de vraag dienen te beantwoorden.
		
Om een eerder aangemaakte vraag aan te passen, klik op (). Hetzelfde scherm als bij het aanmaken van een vraag opent zich met de reeds eerder ingevulde waarden.
	
## Club
Onder club kan je volgende dingen bekijken:
- Bekijk het abonnement waarover de club beschikt bij squatix en de geldigheidsdatum. Zodra de geldigheidsdatum is overschreven is het niet meer mogelijk nieuwe leden toe te voegen.
- Agenda delen: Het is mogelijk de trainingskalender te gebruiken in een externe kalender applicatie die ICS ondersteunt. Kopieër daartoe de ics-url naar de benodigde plaats. Voor ondersteuning neem contact op met het team dat de applicatie aanbiedt.

## Chats
