---
layout: admin
title: Meetings
nav_order: 4
---

# Meetings
{: .no_toc }

## Inhoudsopgave
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## Inleiding
Meetings zijn alle afspraken binnen jouw club. Er zijn drie mogelijke soorten meetings:
- Training
- Wedstrijd
- Evenement 

## Overzicht 
In het meetingsoverzicht zie je alle meetings voor de geselecteerde maand. 

![meetinglist](/assets/images/training_list.png)
		
Bovenaan kan je kiezen voor kalenderzicht (1) of lijstzicht (2). 
De knop mijn kalender (3) toont de meetings waarop het ingelogde lid is ingeschreven (verleden of toekomst). Op deze pagina zien trainers ook een overzicht van de 
trainingen waarop ze al bevestigd hebben of dewelke ze nog moeten bevestigen (indien degene die de training aangemaakt heeft daarom gevraagd heeft, 
zie [Editeer/creeër meeting](#editeercreeër-meeting)

![meeting_overview](/assets/images/training_buttons.png)

Resultaten kunnen gefilterd worden door het type meeting aan of af te vinken of door meetingscategorieën te selecteren of te deselecteren.

![meeting_filter](/assets/images/meetings_filter.png)

Via de knop "Meeting aanmaken" kan je een nieuwe meeting creëren (zie [Editeer/creeër meeting](#editeercreeër-meeting))

Aanklikken van een meeting opent de meeting detail pagina.

## Detail

### Algemene velden

De meeting detail pagina toont volgende meeting info:
- Titel
- Start- en eind datum 
- Categorie 
- Locatie (Optioneel)
- Beschrijving (Optioneel)
- Aantal bezette plaatsen indien deelnemersbeperking (Optioneel)
- Trainers (enkel meeting-type "Training"): alle aangestelde en bevestigde (optioneel) trainers

![meetingdetails](/assets/images/training_details.png)

### Trainers (enkel meeting-type "Training")

Een overzicht van alle trainers die aangesteld zijn voor de training en hun status (indien bevestiging gevraagd is). Een beheerder kan de status voor elke trainer aanpassen.

![trainers](/assets/images/meeting_trainers.png)

### Deelnemers
In de deelnemers tabel zie je de ingeschreven deelnemers. 

Via + kan je zelf leden handmatig inschrijven voor de meeting. Wanneer een beheerder een lid handmatig inschrijft is het mogelijk om 
ook deelnemers met een ongeldig abonnement in te schrijven, zelfs indien ingesteld is dat de meetingscategorie enkel voor leden met een 
geldig abonnement toegankelijk is (zie [Meetingscategorieën](settings.md#meetingscategorieën)). 
Wanneer een lid zichzelf wilt inschrijven moet hij wel aan deze regel voldoen.

![meeting participants](/assets/images/training-participants.png)

De deelnemers tabel toont: 
- Voornaam/achternaam van het lid
- Geldigheid van zijn abonnement tov de meeting
- Of de deelnemer aanwezig was (bevestigd)
- Verwijderknop.

Een deelnemer kan bevestigd worden voor de meeting indien zijn QR-code gescand wordt (zie QR scanning(qr-scanning.md)) of indien op "Bevestig" geklikt wordt 
in de deelnemers tabel.

### Berichten

Net als bij clubberichten (zie [Berichten](communication.md#berichten)) is het ook hier mogelijk een algemeen publiek bericht over de meeting te plaatsen. Berichten 
kunnen tekst en een afbeelding bevatten.

In tegenstelling tot bij clubberichten kunnen de leden hier zelf ook een nieuw bericht plaatsen. Alle leden die ingeschreven zijn op de meeting krijgen een melding
indien een nieuw bericht geplaatst is.

### Meetingsacties

![meeting actions](/assets/images/training_actions1.png)

**Meeting geschiedenis (1)** 

Hier worden alle gebeurtenissen die plaatsvinden op de meeting getoond. Sommige gebeurtenissen zijn enkel zichtbaar voor een beheerder.
- Aanpassing details meeting (Lid + beheerder)
- Deelnemer schrijft zich uit (Beheerder)
- Beheerder schrijft deelnemer manueel in (Beheerder)
- Beheerder schrijft deelnemer manueel uit (Beheerder)
- Meeting aangemaakt (Lid + beheerder)
- Meeting geannuleerd (Lid + beheerder)
- Trainers aangepast (Beheerder)
			
**Editeer meeting (2)** 

zie [Editeer/creeër meeting](#editeercreeër-meeting)

**Extra acties via (3):**

![meeting actions](/assets/images/training_actions2.png)

- **Maak kopie (1)**  
Toon de bewerk meeting pagina met alle velden ingevuld gelijk aan de waardes van de meeting waarvan een kopie gemaakt is.

- **Verwijder (2)**  
Dit is enkel mogelijk indien er nog geen ingeschreven deelnemers zijn of indien de meeting eerst geannuleerd is. Verwijderen kan niet ongedaan gemaakt worden.

- **Annuleer meeting (3)**  
Meeting krijgt status "geannuleerd". Alle ingeschreven deelnemers krijgen een notificatie. 
	
## Editeer/creeër meeting
	
Om meetings te kunnen aanmaken dien je over minstens 1 meetingscategorie te beschikken. (zie [Meetingscategorieën](settings.md#meetingscategorieën))

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
- Herhaal meeting (optioneel)

**Categorie**

Meetingscategorieën kunnen aangemaakt worden in instellingen, zie [Meetingscategorieën](settings.md#meetingscategorieën)

![meeting categorie](/assets/images/new_training_category.png)

**Trainers**

Hier kan je een of meerdere trainers toevoegen. Dit kan op twee manieren:
- Manueel: klik op "voeg trainer toe" en selecteer de trainer. Enkel leden met een trainer-rol worden getoond. Voor het toekennen van de trainer-rol aan een lid 
zie [Lid gegevens](member-management.md#lid-gegevens)
- Automatisch: indien een trainer gelinkt is aan de gekozen meetingscategorie wordt hij automatisch ingevuld. Voor het linken van trainers aan een 
categorie zie [Meetingscategorieën](settings.md#meetingscategorieën). Wens je de trainer toch niet toe te voegen aan de meeting of wil je hem later weer verwijderen, 
klik op X

![meeting categorie](/assets/images/new_training_trainers.png)

Het is ook mogelijk deze trainers te vragen om hun aanwezigheid te bevestigen. Dit doe je door "Vraag trainer om te bevestigen" aan te vinken. De trainer ontvangt een notificatie 
dat hij zijn aanwezigheid moet bevestigen. Bevestigen kan hij op de detail pagina van de meeting of in zijn "mijn kalender"-pagina waar hij een overzicht heeft op 
alle meetings die hij nog moet bevestigen.

Als beheerder kan je heel precies aangeven wat er dient te gebeuren indien de trainer aangeeft dat hij niet kan aanwezig zijn op de training:
- Dient hij een vervanger te kiezen of niet?
- Dient hij altijd een vervangen te kiezen of gebaseerd op regels? Regels kunnen zijn:
	- Er moeten minstens X aantal trainers aanwezig zijn
	- Er moeten minstens X aantal trainers van een bepaalde groep aanwezig zijn
	- Vervangers kunnen enkel van dezelfde groep komen (zie [Trainer groepen](settings.md#trainer-groepen))
	
Indien een trainer niet kan aanwezig zijn en er door de configuratie geen beschikbare trainers meer zijn dient hij contact op te nemen met een beheerder.

**Automatisch alle leden inschrijven die aan de categorie zijn gekoppeld**

Indien je dit aanvinkt wordt de meeting aangeduid als "automatisch inschrijven". Dit houdt in dat na creatie van de meeting alle leden van jouw club automatisch 
als deelnemer zullen toegevoegd worden aan de meeting indien ze aan volgende criteria voldoen:
- Geldig abonnement op datum van de meeting:
	- Geldigheidsdatum later dan de begintijd
	- Abonnementscategorie is gelinkt aan de meetingscategorie (zie [AbonnementsCategorieën](settings.md#abonnementscategorieën))
	- Met aantal resterende beurten wordt geen rekening gehouden.
- Niet aangeduid als trainer voor de meeting
- De meetingscategorie is geselecteerd onder "Categorieën automatisch inschrijven" op het overeenkomende actieve abonnement van het lid 
(zie [Abonnement](member-management.md#abonnement))
- Lid is niet inactief
- Lid heeft zich niet eerder manueel uitgeschreven van de meeting (enkel toepasbaar indien meeting eerder aangemaakt werd als "gewone" meeting en pas later 
aangepast werd naar "automatisch inschrijven" - meeting)

![automatisch inschrijven](/assets/images/new_training_autosubscribe.png)

Indien een meeting aangeduid is als "automatisch inschrijven" wordt bij verschillende acties gekeken of de deelnemerslijst automatisch moet aangepast worden:
- Aanvinken "automatisch inschrijven" bij aanpassen/aanmaken meeting
- Verwijderen/toevoegen van trainers
- Veranderen categorie van de meeting
- Aanvaarden/toevoegen van een nieuw lid in de club (zie [Ledenbeheer](member-management.md))
- Aanpassen van een abonnement van een lid (zie [Abonnement](member-management.md#abonnement))
- Toewijzen/verwijderen van een meetingcategorie bij een abonnementscategorie

**Automatisch teams inschrijven**

Indien je dit aanvinkt wordt de meeting aangeduid als "automatisch teams inschrijven". Dit houdt in dat na creatie van de meeting alle leden die in een van de toegevoegde teams zitten automatisch 
als deelnemer zullen toegevoegd worden aan de meeting (zie [Teams](settings.md#teams))

![automatisch teams inschrijven](/assets/images/new_training_subscribeteams.png)

Indien een meeting aangeduid is als "automatisch teams inschrijven" wordt bij verschillende acties gekeken of de deelnemerslijst automatisch moet aangepast worden:
- Aanvinken "automatisch teams inschrijven" bij aanpassen/aanmaken meeting
- Verwijderen/toevoegen van trainers
- Aanpassen van een team
- Aanpassen van de teams op de training
	
**Beperk deelnemers**

Geef een maximum aantal deelnemers voor de meeting in. Leden zullen niet zelf kunnen inschrijven voor een meeting die volgeboekt is.
Met deze instelling wordt geen rekening gehouden in volgende gevallen: 
- Wanneer een beheerder zelf manueel een deelnemer toevoegt aan de meeting
- Wanneer de meeting aangeduid is als "automatisch inschrijven" en er hierdoor leden automatisch moeten toevoegd worden

![meeting categorie](/assets/images/new_training_limit_members.png)
		
**Herhaal meeting**

Deze optie is enkel beschikbaar bij het aanmaken van een nieuwe meeting. 
Kies de dagen in de week waarop deze meeting zich moet herhalen (de dag van de intieële meeting dient steeds geselecteerd te worden). Kies ook de datum waarop de 
herhaling dient te stoppen (maximum 1 jaar in de toekomst). Zodra de meeting wordt aangemaakt worden op de opgegeven dagen identieke kopieën gecreerd.

![meeting categorie](/assets/images/new_training_recurrence.png)
		
**Bewaren** 

Indien een meeting wordt aangepast en deze onderdeel is van een serie wordt bij het bewaren van de meeting gevraagd of enkel de geopende meeting moet aangepast worden 
of de aanpassing moet doorgevoerd worden in (een deel van) de serie. 
Indien serie aangeduid wordt: selecteer de meetings waarop de aanpassing moet doorgevoerd worden (standaard staat elke meeting van de serie geselecteerd) en klik op 
bewaren. Alle geselecteerde meetings zullen nu aangepast worden met de ingegeven veranderingen.
