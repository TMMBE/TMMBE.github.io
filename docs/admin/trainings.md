---
layout: admin
---

# Trainingen
## Overzicht 
In het trainingsoverzicht zie je alle trainingen voor de geselecteerde maand. 

![traininglist](/assets/images/training_list.png)
		
Bovenaan kan je kiezen voor kalenderzicht (1) of lijstzicht (2). 
De knop mijn trainingen (3) toont de trainingen waarop het ingelogde lid is ingeschreven (trainer?) (verleden of toekomst). 

![training_overview](/assets/images/training_buttons.png)

Via de knop "Training aanmaken" kan je een nieuwe training creëren (zie [Editeer/creeër training](#editeercreeër-training))

Aanklikken van een training opent de training detail pagina.

## Detail
De training detail pagina toont volgende training info:
- Titel
- Start- en eind datum 
- Categorie 
- Locatie (Optioneel)
- Beschrijving (Optioneel)
- Aantal bezette plaatsen indien deelnemersbeperking (Optioneel)

![trainingdetails](/assets/images/training_details.png)

In de deelnemers tabel zie je de ingeschreven deelnemers. Via + kan je zelf leden handmatig inschrijven voor de training. Wanneer een beheerder een lid handmatig inschrijft is het mogelijk om ook deelnemers met een ongeldig abonnement in te schrijven, zelfs indien ingesteld is dat de training categorie enkel voor leden met een geldig abonnement is (zie [6.1 Trainingscategorieën](#6.1-trainingscategorieën)). Wanneer een lid zichzelf wilt inschrijven moet hij wel aan deze regel voldoen.

![training participants](/assets/images/training-participants.png)

De deelnemers tabel toont: 
- Voornaam/achternaam van het lid
- Geldigheid van zijn abonnement tov de training
- Of de deelnemer aanwezig was (bevestigd)
- Verwijderknop.

Een deelnemer kan bevestigd worden voor de training indien zijn QR-code gescand wordt of indien op "bevestigen" geklikt wordt in de deelnemers tabel.

### Trainingsacties

![training actions](/assets/images/training_actions1.png)

**Training geschiedenis (1)** 

Hier worden alle gebeurtenissen die plaatsvinden op de training getoond. Sommige gebeurtenissen zijn enkel zichtbaar voor een beheerder.
- Aanpassing details training (Lid + beheerder)
- Deelnemer schrijft zich uit (Beheerder)
- Beheerder schrijft deelnemer manueel in (Beheerder)
- Beheerder schrijft deelnemer manueel uit (Beheerder)
- Training aangemaakt (Lid + beheerder)
- Training geannulleerd (Lid + beheerder)
- Trainers aangepast (Beheerder)
			
**Editeer training (2)** 

zie [Editeer/creeër training](#editeercreeër-training)

**Extra acties via (3):**

![training actions](/assets/images/training_actions2.png)

- **Maak kopie (1)**  
Toon de bewerk training pagina met alle velden ingevuld gelijk aan de waardes van de training waarvan een kopie gemaakt is.

- **Verwijder (2)**  
Dit is enkel mogelijk indien er nog geen ingeschreven deelnemers zijn of indien de training eerst geannuleerd is. Verwijderen kan niet ongedaan gemaakt worden.

- **Annuleer training (3)**  
Training krijgt status "geannuleerd". Alle ingeschreven deelnemers krijgt een notificatie. 
	
## Editeer/creeër training
	
Om trainingen te kunnen aanmaken dien je over minstens 1 trainingscategorie te beschikken. (zie [6.1 Trainingscategorieën](#6.1-trainingscategorieën))

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

Trainingscategorieën kunnen aangemaakt worden in instellingen, zie [6.1 Trainingscategorieën](#6.1-trainingscategorieën)

![training categorie](/assets/images/new_training_category.png)

**Trainers**

Hier kan je een of meerdere trainers toevoegen. Dit kan op twee manieren:
- Manueel: klik op "voeg trainer toe" en selecteer de trainer. Enkel leden met een trainer-rol worden getoond. Voor het toekennen van de trainer-rol zie [Lid gegevens](#lid-gegevens)
- Automatisch: indien een trainer gelinkt is aan de gekozen trainingscategorie wordt hij automatisch ingevuld. Voor het linken van trainers aan een categorie zie ([AbonnementsCategorieën](#abonnementscategorieën). Wens je de trainer toch niet toe te voegen aan de trainer of wil je hem later weer verwijderen, klik op X

![training categorie](/assets/images/new_training_trainers.png)

Het is ook mogelijk deze trainers te vragen om hun aanwezigheid te bevestigen. Dit doe je door "Vraag bevestiging" aan te vinken. De trainer ontvangt een notificatie dat hij zijn aanwezigheid moet bevestigen. Bevestigen kan hij op de detail pagina van de training of in zijn "mijn trainingen"-pagina waar hij een overzicht heeft op alle trainingen die hij nog moet bevestigen. Indien de trainer aangeeft dat hij niet aanwezig kan zijn dient hij een vervanger te kiezen uit de andere beschikbare trainers.

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

![training categorie](/assets/images/new_training_autosubscribe.png)

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

![training categorie](/assets/images/new_training_limit_members.png)
		
**Herhaal training**

Deze optie is enkel beschikbaar bij het aanmaken van een nieuwe training. 
Kies de dagen in de week waarop deze training zich moet herhalen (de dag van de intieële training dient steeds geselecteerd te worden). Kies ook de datum waarop de herhaling dient te stoppen (maximum 1 jaar in de toekomst). Zodra de training wordt aangemaakt worden op de opgegeven dagen identieke kopieën gecreerd.

![training categorie](/assets/images/new_training_recurrence.png)
		
**Bewaren** 

Indien een training wordt aangepast en deze onderdeel is van een serie wordt bij het bewaren van de training gevraagd of enkel de geopende training moet aangepast worden of de aanpassing moet doorgevoerd worden in (een deel van) de serie. 
Indien serie aangeduid wordt: selecteer de trainingen waarop de aanpassing moet doorgevoerd worden (standaard staat elke training van de serie geselecteerd) en klik op bewaren. Alle geselecteerde trainingen zullen nu aangepast worden met de ingegeven veranderingen.
