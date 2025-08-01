---
layout: admin
title: Activiteiten
nav_order: 4
---

# Activiteiten
{: .no_toc }

## Inhoudsopgave
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## Inleiding
Activiteiten zijn alle afspraken binnen jouw club. Er zijn drie mogelijke soorten activiteiten:
- Training
- Wedstrijd
- Evenement 

## Lijst 

### Kalender

In de kalender zie je alle activiteiten voor de geselecteerde maand. 

![meetinglist](/assets/images/meeting_list.png)
		
De knop mijn kalender toont de activiteiten waarop het ingelogde lid is ingeschreven (verleden of toekomst). Op deze pagina zien trainers ook een overzicht van de 
trainingen waarop ze al bevestigd hebben of dewelke ze nog moeten bevestigen (indien degene die de training aangemaakt heeft daarom gevraagd heeft, 
zie [Editeer/creeër activiteit](#editeercreeër-activiteit)

Resultaten kunnen gefilterd worden door het type activiteit aan of af te vinken of door activiteitscategorieën te selecteren of te deselecteren.

![meeting_filter](/assets/images/meetings_filter.png)

Via de knop "Activiteit aanmaken" kan je een nieuwe activiteit creëren (zie [Editeer/creeër activiteit](#editeercreeër-activiteit))

Aanklikken van een activiteit opent de activiteit detail pagina.

### Overzicht 

Hier kan je op basis van een begin -en einddatum en eventueel (een deel van) een titel op zoek gaan naar activiteiten. 

Bovenaan kan je kiezen voor kalenderzicht (1) of lijstzicht (2). De knop mijn kalender (3) toont de activiteiten waarop het ingelogde lid is ingeschreven (verleden of toekomst).

![meeting_overview](/assets/images/meeting_buttons.png)

Resultaten kunnen ook hier gefilterd worden door het type activiteit aan of af te vinken of door activiteitscategorieën te selecteren of te deselecteren.

![meeting_filter](/assets/images/meetings_filter.png)

Aanklikken van een activiteit opent de activiteit detail pagina.

## Detail

### Algemene velden

De activiteit detail pagina toont volgende activiteit info:
- Titel
- Start- en eind datum 
- Categorie 
- Toegangsvoorwaarden
- Locatie (Optioneel)
- Beschrijving (Optioneel)
- Aantal bezette plaatsen indien deelnemersbeperking (Optioneel)
- Trainers (enkel activiteit-type "Training"): alle aangestelde en bevestigde (optioneel) trainers

![meetingdetails](/assets/images/meeting_details.png)

### Trainers (enkel activiteit-type "Training")

Een overzicht van alle trainers die aangesteld zijn voor de training en hun status (indien bevestiging gevraagd is). Een beheerder kan de status voor elke trainer aanpassen.

![trainers](/assets/images/meeting_trainers.png)

### Deelnemers
Onder deelnemers zie je het aantal ingeschreven deelnemers. Via hier kan je navigeren naar de deelnemers pagina (zie [Deelnemers](#deelnemers))

### Vrijwilligers
Onder Vrijwilligers zie je het aantal ingeschreven vrijwilligers. Via hier kan je navigeren naar de vrijwilligers pagina (zie [Vrijwilligers](#vrijwilligers))

### Berichten

Net als bij clubberichten (zie [Berichten](communication.md#berichten)) is het ook hier mogelijk een algemeen publiek bericht over de activiteit te plaatsen. Berichten 
kunnen tekst en een afbeelding bevatten.

In tegenstelling tot bij clubberichten kunnen de leden hier zelf ook een nieuw bericht plaatsen. Alle leden die ingeschreven zijn op de activiteit krijgen een melding
indien een nieuw bericht geplaatst is.

### Activiteitsacties

**Geschiedenis** 

Hier worden alle gebeurtenissen die plaatsvinden op de activiteit getoond. Sommige gebeurtenissen zijn enkel zichtbaar voor een beheerder.
- Aanpassing details activiteit (Lid + beheerder)
- Deelnemer schrijft zich uit (Beheerder)
- Beheerder schrijft deelnemer manueel in (Beheerder)
- Beheerder schrijft deelnemer manueel uit (Beheerder)
- Activiteit aangemaakt (Lid + beheerder)
- Activiteit geannuleerd (Lid + beheerder)
- Trainers aangepast (Beheerder)
			
**Details bewerken**

zie [Editeer/creeër activiteit](#editeercreeër-activiteit)

**Timing bewerken**

zie [Editeer/creeër activiteit](#editeercreeër-activiteit)

- **Maak kopie**  
Toon de bewerk activiteit pagina met alle velden ingevuld gelijk aan de waardes van de activiteit waarvan een kopie gemaakt is.

- **Verwijder**  
Dit is enkel mogelijk indien er nog geen ingeschreven deelnemers zijn of indien de activiteit eerst geannuleerd is. Verwijderen kan niet ongedaan gemaakt worden.

- **Annuleer activiteit**  
Activiteit krijgt status "geannuleerd". Alle ingeschreven deelnemers krijgen een notificatie. 
	
## Editeer/creeër activiteit
	
Om activiteiten te kunnen aanmaken dien je over minstens 1 activiteitscategorie te beschikken. (zie [Activiteitscategorieën](settings.md#activiteitscategorieën))

Volgende velden kan je invullen:
- Titel (verplicht)
- Start datum/uur (verplicht)
- Eind datum/uur (verplicht)
- Locatie (optioneel)
- Beschrijving (optioneel)
- Categorie (verplicht)
- Trainers (optioneel)
- Automatisch teams inschrijven (optioneel)
- Beperk deelnemers (optioneel)
- Wachtlijst toestaan (optioneel)
- Herhaal activiteit (optioneel)

**Categorie**

Activiteitscategorieën kunnen aangemaakt worden in instellingen, zie [Activiteitscategorieën](settings.md#activiteitscategorieën)

![meeting categorie](/assets/images/new_meeting_category.png)

**Trainers**

Hier kan je een of meerdere trainers toevoegen. Dit kan op twee manieren:
- Manueel: klik op "voeg trainer toe" en selecteer de trainer. Enkel leden met een trainer-rol worden getoond. Voor het toekennen van de trainer-rol aan een lid 
zie [Lid gegevens](member-management.md#lid-gegevens)
- Automatisch: indien een trainer gelinkt is aan de gekozen activiteitscategorie wordt hij automatisch ingevuld. Voor het linken van trainers aan een 
categorie zie [Activiteitscategorieën](settings.md#activiteitscategorieën). Wens je de trainer toch niet toe te voegen aan de activiteit of wil je hem later weer verwijderen, 
klik op X

![meeting categorie](/assets/images/new_meeting_trainers.png)

Het is ook mogelijk deze trainers te vragen om hun aanwezigheid te bevestigen. Dit doe je door "Vraag trainer om te bevestigen" aan te vinken. De trainer ontvangt een notificatie 
dat hij zijn aanwezigheid moet bevestigen. Bevestigen kan hij op de detail pagina van de activiteit of in zijn "mijn kalender"-pagina waar hij een overzicht heeft op 
alle activiteiten die hij nog moet bevestigen.

Als beheerder kan je heel precies aangeven wat er dient te gebeuren indien de trainer aangeeft dat hij niet kan aanwezig zijn op de training:
- Dient hij een vervanger te kiezen of niet?
- Dient hij altijd een vervangen te kiezen of gebaseerd op regels? Regels kunnen zijn:
	- Er moeten minstens X aantal trainers aanwezig zijn
	- Er moeten minstens X aantal trainers van een bepaalde groep aanwezig zijn
	- Vervangers kunnen enkel van dezelfde groep komen (zie [Trainer groepen](settings.md#trainer-groepen))
	
Indien een trainer niet kan aanwezig zijn en er door de configuratie geen beschikbare trainers meer zijn dient hij contact op te nemen met een beheerder.

**Vrijwilligers**

Wanneer je vrijwilligers wil toelaten op een activiteit vink je dit vakje aan.

![meeting volunteers](/assets/images/meeting_volunteers.png)

Hierdoor zullen leden zich kunnen inschrijven als vrijwilliger. Wil je het aantal vrijwilligers beperken voor deze activiteit, dan vink je 'Beperk vrijwilligers' aan. Zo geef je het maximum aantal toegelaten vrijwilligers op.

![meeting volunteers](/assets/images/meeting_volunteers_max.png)

Je kan er ook voor kiezen om verschillende taken op te geven, zo kunnen vrijwilligers zich inschrijven op een specifieke taak. Je kan het maximum aantal per taak beperken.

![meeting volunteers](/assets/images/meeting_volunteers_tasks.png)

Om leden van je club vrijwilliger te maken, zie [Ledenbeheer](member-management.md#vrijwilligers).

**Automatisch teams inschrijven**

Indien je dit aanvinkt wordt de activiteit aangeduid als "automatisch teams inschrijven". Dit houdt in dat na creatie van de activiteit alle leden die in een van de toegevoegde teams zitten automatisch 
als deelnemer zullen toegevoegd worden aan de activiteit (zie [Teams](settings.md#teams))

![automatisch teams inschrijven](/assets/images/new_meeting_subscribeteams.png)

Indien een activiteit aangeduid is als "automatisch teams inschrijven" wordt bij verschillende acties gekeken of de deelnemerslijst automatisch moet aangepast worden:
- Aanvinken "automatisch teams inschrijven" bij aanpassen/aanmaken activiteit
- Verwijderen/toevoegen van trainers
- Aanpassen van een team
- Aanpassen van de teams op de activiteit
	
**Beperk deelnemers**

Geef een maximum aantal deelnemers voor de activiteit in. Leden zullen niet zelf kunnen inschrijven voor een activiteit die volgeboekt is.
Met deze instelling wordt geen rekening gehouden in volgende gevallen: 
- Wanneer een beheerder zelf manueel een deelnemer toevoegt aan de activiteit
- Wanneer de activiteit aangeduid is als "automatisch inschrijven" en er hierdoor leden automatisch moeten toevoegd worden

![meeting categorie](/assets/images/new_meeting_limit_members.png)
		
**Herhaal activiteit**

Deze optie is enkel beschikbaar bij het aanmaken van een nieuwe activiteit. 
Kies de dagen in de week waarop deze activiteit zich moet herhalen (de dag van de intieële activiteit dient steeds geselecteerd te worden). Kies ook de datum waarop de 
herhaling dient te stoppen (maximum 1 jaar in de toekomst). Zodra de activiteit wordt aangemaakt worden op de opgegeven dagen identieke kopieën gecreerd.

![meeting categorie](/assets/images/new_meeting_recurrence.png)
		
**Bewaren** 

Indien een activiteit wordt aangepast en deze onderdeel is van een serie wordt bij het starten van het editeren van de activiteit gevraagd of enkel de geopende activiteit moet aangepast worden 
of de aanpassing moet doorgevoerd worden in de serie. 

## Deelnemers

In de deelnemers tabel zie je de ingeschreven deelnemers. 

Via + kan je zelf leden handmatig inschrijven voor de activiteit. Wanneer een beheerder een lid handmatig inschrijft is het mogelijk om 
ook deelnemers met een ongeldig abonnement in te schrijven, zelfs indien ingesteld is dat de activiteitscategorie enkel voor leden met een 
geldig abonnement toegankelijk is (zie [Activiteitscategorieën](settings.md#activiteitscategorieën)). 
Wanneer een lid zichzelf wilt inschrijven moet hij wel aan deze regel voldoen.

![meeting participants](/assets/images/meeting_participants.png)

De deelnemers tabel toont: 
- Voornaam/achternaam van het lid
- Geldigheid van zijn abonnement tov de activiteit
- Of de deelnemer aanwezig was (bevestigd)
- Verwijderknop.

Een deelnemer kan bevestigd worden voor de activiteit indien zijn QR-code gescand wordt (zie [QR scanning](qr-scanning.md)) of indien op "Bevestig" geklikt wordt 
in de deelnemers tabel.

## Vrijwilligers

Gelijkaardig aan de deelnemers tabel, kan je in de vrijwilligers tabel de ingeschreven vrijwilligers bekijken. Indien er aparte vrijwilligerstaken zijn ingesteld, wordt er per vrijwilliger vermeld 
voor welke taak het lid is ingeschreven. Je kan de inschrijving ongedaan maken door op de afvalemmer te klikken. Je kan zelf een vrijwilliger toevoegen door bovenaan de tabel op '+' te klikken.

![meeting volunteer participants](/assets/images/meeting_volunteer_participants.png)

