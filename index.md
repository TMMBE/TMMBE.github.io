# Clubdetails
## Clubinfo
Vul informatie in over jouw club, zichtbaar voor jouw leden. Mogelijke velden zijn:
- Beschrijving
- Adres
- Contactinformatie (naam contactpersoon, e-mail, telefoonnummer)
- Website
## Logo
Upload een logo, zichtbaar voor jouw leden

# Berichten
Via berichten kan je alle leden die jouw app gebruiken in éénmaal bereiken. Elk lid wordt op de hoogte gebracht dat je een bericht geplaatst hebt door middel van een e-mail 
		of gsmnotificatie (afhankelijk van hun instellingen). Berichten laten tekst en een afbeelding toe. Gebruikers kunnen jouw bericht zien en erop reageren. Je wordt eveneens op de hoogte
		gebracht van reacties door middel van een notificatie. Berichten kunnen verwijderd of bewerkt worden waarna het bericht de editeerdatum zal tonen (bewerken) of "bericht verwijderd" (verwijderen).
# Trainingen
## Overzicht 
		In het trainingsoverzicht zie je alle trainingen voor de geselecteerde maand. 
		
		Bovenaan kan je kiezen voor kalenderzicht (1) of lijstzicht (2). De knop mijn trainingen toont de trainingen waarop het ingelogde lid is ingeschreven (trainer?) (verleden of toekomst). 
		Via de QR-code knop kom je in de scanning module terecht waar de QR-code van een lid kan worden gescand.
		Via de knop trainingen aanmaken kan je een nieuwe training creëren (zie editeer training)
		Aanklikken van een training opent de training detail pagina

## Detail
De training detail pagina toont volgende training info:
- Titel
- Start- en eind datum 
- Categorie 
- Locatie (Optioneel)
- Beschrijving (Optioneel)
- Aantal bezette plaatsen indien deelnemersbeperking (Optioneel)

In de deelnemers tabel zie je de ingeschreven deelnemers. Via + kan je zelf leden handmatig inschrijven voor de training. Wanneer een beheerder een lid handmatig inschrijft is het
		 mogelijk om ook deelnemers met een ongeldig abonnement in te schrijven, zelfs indien ingesteld is dat de training categorie enkel voor leden met een geldig abonnement is (zie...).
		 Wanneer een lid zichzelf wilt inschrijven moet hij wel aan deze regel voldoen.
		 
		 De deelnemers tabel toont: Voornaam/achternaam van het lid, geldigheid van zijn abonnement tov de training, of de deelnemer aanwezig was (bevestigd), verwijderknop.
		 Een deelnemer kan bevestigd worden voor de training indien zijn QR-code gescand wordt of indien op "bevestigen" geklikt wordt in de deelnemers tabel
		 
		 Training geschiedenis. Hier worden alle gebeurtenissen die plaatsvinden op de training getoond:
			- Aanpassing details training (lid + beheerder)
			- Deelnemer schrijft zich uit (Beheerder)
			- Beheerder schrijft deelnemer manueel in (Beheerder)
			- Beheerder schrijft deelnemer manueel uit (Beheerder)
			- Training aangemaakt (Lid + beheerder)
			- Training geannulleerd (Lid + beheerder)
			- Trainers aangepast (Beheerder)
			
		Editeer training, zie ()
		
		Maak kopie: Toon de bewerk training pagina met alle velden ingevuld gelijk aan de waardes van de training waarvan een kopie gemaakt is.
		Verwijder: dit is enkel mogelijk indien er nog geen ingeschreven deelnemers zijn of indien de training eerst geannuleerd is. Verwijderen kan niet ongedaan gemaakt worden.
		Annuleer training: Training krijgt status "geannuleerd". Alle ingeschreven deelnemers krijgt een notificatie. 
	
	Editeer/creeër training
	
	Om trainingen te kunnen aanmaken dien je over minstens 1 trainingscategorie te beschikken. (zie ())
	
	velden:
		- titel (verplicht)
		- Start datum/uur (verplicht)
		- Eind datum/uur (verplicht)
		- Locatie (optioneel)
		- Beschrijving (optioneel)
		- Categorie (verplicht): trainingscategorieën kunnen aangemaakt worden in de instellingen, zie ()
		- Trainers: (optioneel)
			* Hier kan je een of meerdere trainers toevoegen. Dit kan op twee manieren:
				- Manueel: klik op "voeg trainer toe" en selecteer de trainer. Enkel leden met een trainer-rol worden getoond. Voor het toekennen van de trainer-rol zie ()
				- Automatisch: indien een trainer gelinkt is aan de gekozen trainingscategorie wordt hij automatisch ingevuld. Voor het linken van trainers aan een categorie zie ().
					Wens je de trainer toch niet toe te voegen aan de trainer of wil je hem later weer verwijderen, klik op ()
			* Het is ook mogelijk deze trainers te vragen om hun aanwezigheid te bevestigen. Dit doe door () aan te vinken. De trainer ontvangt een notificatie dat hij zijn aanwezigheid 
			moet bevestigen. Bevestigen kan hij op de detail pagina van de training of in zijn "mijn trainingen"-pagina waar hij een overzicht heeft op alle trainingen die hij nog moet
			bevestigen. Indien de trainer aangeeft dat hij niet aanwezig kan zijn dient hij een vervanger te kiezen uit de andere beschikbare trainers.
		- Automatisch alle leden inschrijven die aan de categorie zijn gekoppeld: (optioneel) Indien je dit aanvinkt wordt de training aangeduid als "automatisch inschrijven". Dit houdt in dat na creatie
		van de training alle leden van jouw club als deelnemer zullen toegevoegd worden aan de training indien ze aan volgende criteria voldoen:
			- Geldig abonnement op datum van de training:
				* Geldigheidsdatum later dan de begintijd
				* Abonnementscategorie is gelinkt aan de trainingscategorie (zie ())
				* Met aantal resterende beurten wordt geen rekening gehouden.
			- Niet aangeduid als trainer voor de training
			- De trainingscategorie is geselecteerd onder "Categorieën automatisch inschrijven" op het overeenkomende abonnement (zie ())
			- Lid is niet inactief
			- Lid heeft zich niet eerder manueel uitgeschreven van de training (enkel toepasbaar indien training eerder aangemaakt werd als "gewone" training en pas later aangepast werd naar
			"automatisch inschrijven" - training)
			
		Indien een training aangeduid is als "automatisch inschrijven" wordt bij verschillende acties gekeken of de deelnemerslijst automatisch moet aangepast worden:
			- aanvinken "automatisch inschrijven" bij aanpassen/aanmaken training
			- verwijderen/toevoegen van trainers
			- veranderen categorie van de training
			- aanvaarden/toevoegen van een nieuw lid in de club (zie ledenbeheerd)
			- aanpassen van een abonnement van een lid (zie)
			- toewijzen/verwijderen van een trainingcategorie bij een abonnementscategorie
		
		- Beperk deelnemers (optioneel): geef een maximum aantal deelnemers voor de training in. Leden zullen niet zelf kunnen inschrijven voor een training die volgeboekt is.
		Met deze instelling wordt geen rekening gehouden in volgende gevallen: 
			(1) wanneer een beheerder zelf manueel een deelnemer toevoegt aan de training
			(2) wanneer de training aangeduid is als "automatisch inschrijven" en er hierdoor leden automatisch moeten toevoegd worden
		
		- Herhaal training (optioneel):
			Deze optie is enkel beschikbaar bij het aanmaken van een nieuwe training. 
			Kies de dagen in de week waarop deze training zich moet herhalen (de dag van de intieële training dient steeds geselecteerd te worden). Kies ook de datum waarop de herhaling dient 
			te stoppen (maximum 1 jaar in de toekomst). Zodra de training wordt aangemaakt worden op de opgegeven dagen identieke kopieën gecreerd.
		
		- Bewaren: indien een training wordt aangepast en deze onderdeel is van een serie (zie herhaal training) wordt bij het bewaren van de training gevraagd of enkel de geopende training
		moet aangepast worden of de aanpassing moet doorgevoerd worden in (een deel van) de serie. 
		Indien serie aangeduid wordt: selecteer de trainingen waarop de aanpassing moet doorgevoerd worden (standaard staat elke training van de serie geselecteerd) en klik op bewaren. Alle
		geselecteerde trainingen zullen nu aangepast worden met de ingegeven veranderingen.







## Squatixxxxx

You can use the [editor on GitHub](https://github.com/TMMBE/TMMBE.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/TMMBE/TMMBE.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
