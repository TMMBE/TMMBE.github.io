---
layout: admin
title: Configuratie
nav_order: 11
---

# Configuratie
{: .no_toc }

## Inhoudsopgave
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Activiteitscategorieën

Om een activiteitscategorie toe te voegen, klik op het + symbool. 
Volgende data kan ingegeven worden:
- Naam
- Kleur: wordt weergegeven in de activiteitskalender om activiteiten met een verschillende categorie van elkaar te kunnen onderscheiden
- Inschrijven: enkel leden met een geldig abonnement kunnen inschrijven op de activiteit of alle leden kunnen inschrijven
- Zichtbaarheid: enkel leden met een overeenkomend abonnement kunnen deze categorie zien of alle leden kunnen deze categorie zien
- Prijs voor een enkele activiteit: je kan hierin optioneel een prijs instellen. Wanneer leden zich willen inschrijven voor een activiteit van deze categorie en ze hebben geen geldig abonnement voor deze activiteit zal de prijs getoond worden. Wanneer het lid zich dan inschrijft, wordt er doorverwezen naar de betaalpagina. Zodra de betaling voltooid is, is het lid automatisch ingeschreven. Indien dit veld leeg gelaten wordt, is inschrijven gratis tenzij "enkel leden met een geldig abonnement kunnen inschrijven" is ingeschakeld.
- Trainers: selecteer trainers die automatisch zullen ingevuld worden bij het aanmaken van een activiteit van deze categorie

![Meeting category](/assets/images/training_categorie.png)

Voor het aanpassen van een activiteitscategorie: klik op het potloodje

## Abonnementscategorieën

Om een abonnementscategorie toe te voegen, klik op het + symbool. 
Volgende data kan ingegeven worden:
- Naam
- Gelinkte activiteitscategorieën: link een van de aangemaakte activiteitscategorieën aan de abonnementscategorie. Op deze manier kan je bepalen voor welke activiteiten een lid kan inschrijven 
(indien de activiteitscategorie enkel voor een geldig abonnement inschrijfbaar is).

![Subscription category](/assets/images/subscription_categorie.png)
			
Aanpassen van een abonnementscategorie: klik op het potloodje

## Abonnementen

Definieer hier de abonnementen die je daarna kan toekennen aan jouw leden (zie [Abonnement](member-management.md#abonnement)) of die ze zelf kunnen aankopen in de shop 
wanneer deze geactiveerd is (zie [Shop](shop.md))

Om een nieuw abonnement toe te voegen, klik op het +-teken. Het scherm om een nieuw abonnement aan te maken opent zich. Volgende velden dienen ingevuld te worden:
- Naam: Een naam voor het abonnement, ook zichtbaar voor jouw leden
- Type: Abonnement of beurten
- Categorie: Zie [Abonnementscategorieën](#abonnementscategorieën)
- Geldig tot: Keuze uit een datum of een periode: de periode gaat in zodra het abonnement aan een lid wordt toegekend
- Beurten over: Enkel indien type "Beurten" geselecteerd is
- Prijs: Het bedrag waarvoor het lid een betaling ontvangt op moment dat het abonnement toegekend wordt. Indien leeg gelaten of gelijk aan 0 volgt er geen betaling. 
Enkel van toepassing indien er een mollie-account gekoppeld is (zie [Mollie](payments.md#mollie))

![Subscription definition](/assets/images/subscription_definition.png)

Aanpassen van een abonnement: klik op het potloodje

Door een abonnement inactief te maken verdwijnt het uit de shop en kan het niet meer toegekend worden.

## Shop

In de shop instellingen kan je zelf items configureren om te verkopen.

![Shop items overzicht](/assets/images/shop_overview_settings.png)

Klik op het + teken om een nieuw item te configureren. Configureer de item, prijs en voeg eventueel een afbeelding toe. Verder kan je zelf een lijst met beschikbare maten en kleuren definieren.

Klik op bewaren. Dit item is nu beschikbaar in je shop.

![Shop item configureren 1](/assets/images/shop_item_config_1.png)
![Shop item configureren 1](/assets/images/shop_item_config_2.png)

## Rollen
Met rollen kan je jouw leden toegang geven tot bepaalde functionaliteiten of pagina's waar een lid zonder die rol geen toegang toe heeft. Op de rollen-pagina kan je de 
verschillende rollen en hun permissies voor jouw club definiëren. Daarna kan je in de detail pagina van een lid hem een of meerdere van die rollen toekennen 
(zie [Lid gegevens](member-management.md#lid-gegevens)).

![roles](/assets/images/roles.png)	

Volgende permissies kunnen aan een rol gegeven worden:
- Club info wijzigen (Wijzig de club info, upload een logo)
- Club chat (Ontvang en beantwoord chatberichten die leden naar de club sturen)
- Leden lezen (Bekijk de ledenlijst)
- Leden wijzigen (Bekijk en wijzig de leden)
- Rollen beheren (Rollen bekijken, toevoegen en aanpassen)
- Trainer (Kan geselecteerd worden als trainer)
- Activiteiten wijzigen (Aanpassen en aanmaken van activiteiten)

Een aantal standaard rollen zijn altijd aanwezig en kunnen niet verwijderd of aangepast worden:
- Eigenaar (Alle permissies, uitgezonder trainer. Enkel toegekend aan de persoon die de club aangemaakt heeft, kan beheerders aanduiden of verwijderen.)
- Beheerder (Alle permissies, uitgezonderd trainer, kan geen andere beheerders aanduiden of verwijderen)
- Trainer (Kan als trainer toegevoegd worden aan een activiteit)

## Trainer groepen
Indien je wilt dat trainers bevestigen of ze aanwezig kunnen zijn op een training en een vervanger moeten kiezen indien nodig kan je trainer groepen gebruiken zodat ze enkel een vervanger
uit dezelfde groep als zichzelf kunnen kiezen. Op deze manier kan je ervoor zorgen dat er altijd genoeg trainers van een bepaald niveau aanwezig zijn.

Om een trainer groep toe te voegen, klik op het + symbool. 
Volgende data kan ingegeven worden:
- Naam
- Trainers: selecteer alle trainers die tot de groep behoren

Aanpassen van een Trainer groep: klik op het potloodje

![Trainer groups](/assets/images/trainer_groups.png)

## Teams
Met teams kan je jouw leden onderverdelen in verschillende teams. Bij het zenden van mails kan je bijvoorbeeld een team gebruiken als ontvanger van de mail. 
(zie [Mails](mail.md)) Je kan ook een of meerdere teams aan een activiteit linken zodat alle leden van deze teams automatisch ingeschreven worden voor die 
activiteit (zie [Editeer/creeër activiteit](activities.md#editeercreeër-activiteit))

![Teams](/assets/images/teams.png)

Om een team toe te voegen, klik op het + symbool. 
Volgende data kan ingegeven worden:
- Naam
- Leden: selecteer alle leden die tot het team behoren

Aanpassen van een Team: klik op het potloodje

Aanmaken van een team kan ook door in de leden pagina eerst de leden te selecteren en daarna de actie "Team aanmaken" te selecteren (zie [Team aanmaken](member-management.md#team-aanmaken))
	
## Vragenlijsten
Indien gewenst kan je jouw leden op elk moment een aantal vragen laten beantwoorden. Zo kan je bijvoorbeeld vragen of ze ook een 
vrijwilliger functie in de club willen uitvoeren, voor welke afdeling ze zich inschrijven in jouw club enzovoort. Standaard is er een vragenlijst die kan getoond worden wanneer een gebruiker
lid wilt worden van jouw club maar je kan ook zelf extra vragenlijsten aanmaken. De antwoorden van het lid zie je bij hun lidverzoek (zie [Ledenverzoeken](member-management.md#ledenverzoeken)) 
wanneer het over een lid verzoek vragenlijst gaat of bij formulieren (zie [Formulieren](member-management.md#formulieren)).

**Vragen**

De vragen en antwoorden kunnen aangemaakt worden in verschillende talen. De vraag zal voor de gebruiker 
automatisch verschijnen in de taal die hij in zijn profiel ingevuld heeft.

![member question](/assets/images/member_question.png)
		
Om een nieuwe vraag aan te maken, klik op het + symbool. Onder "Vraag" vul je de vraag in. Klik op "Vertaling toevoegen" om de vraag in meerdere talen beschikbaar te stellen.
Onder "Antwoorden" vul je een mogelijk antwoord op de vraag in. Klik op "Vertaling toevoegen" om het antwoord in meerdere talen beschikbaar te stellen. Klik op + om een extra mogelijk 
antwoord op de vraag toe te voegen. Selecteer desgewenst de checkbox "Meerdere antwoorden toestaan".

Om de vraag te bewaren klik je op "Bewaar".
		
Om een eerder aangemaakte vraag aan te passen, klik op het potloodje. Hetzelfde scherm als bij het aanmaken van een vraag opent zich met de reeds eerder ingevulde waarden.

**Standaard vragen**

Er zijn ook een aantal standaard vragen beschikbaar. Deze kan je niet aanpassen of verwijderen.

- Ik wil me inschrijven voor de nieuwsbrief van club X
- Welk abonnement wens je? (hiervoor dienen abonnementen aangemaakt te zijn (zie [Abonnementen](#abonnementen)))
- Aan welk team moet je toegevoegd worden? (hiervoor dienen teams aangemaakt te zijn (zie [Teams](#teams)))

![standard questions](/assets/images/standard_questions.png)

**Vragenlijsten**

Om een nieuwe vragenlijst aan te maken klik op het + symbool. Geef de vragenlijst een naam en link de gewenste vragen aan de vragenlijst. Klik op "Bewaar".

Om een eerder aangemaakte vragenlijst aan te passen, klik op het potloodje.

![define questionnaire](/assets/images/define_questionnaire.png)

**Standaard vragenlijst**

Er is een standaard vragenlijst om te tonen aan gebruikers die lid willen worden van de club. Deze kan je niet verwijderen. Je kan wel bepalen welke vragen gelinkt zijn aan deze vragenlijst.
Zodra de vragenlijst minstens één vraag bevat zal hij getoond worden bij lidaanvragen.

![standard questionnaires](/assets/images/standard_questionnaires.png)
	
## Club

Onder club kan je volgende dingen bekijken:
- Bekijk het abonnement waarover de club beschikt bij squatix en de geldigheidsdatum. Zodra de geldigheidsdatum is overschreden is het niet meer mogelijk nieuwe leden toe te voegen.
- Agenda delen: het is mogelijk de activiteitskalender te gebruiken in een externe kalender applicatie die ICS ondersteunt. Kopieër daartoe de ics-url naar de benodigde 
plaats. Voor ondersteuning neem contact op met het team dat de applicatie aanbiedt.
- Handleiding: klik op de link om de beheerdershandleiding te bekijken.
- Mollie: koppel jouw Squatix account met een mollie account om betalingen te kunnen ontvangen (zie [Mollie](payments.md#mollie))
- Shop: toon de shop aan jouw leden waar ze zelf abonnementen kunnen aankopen (dit gaat enkel wanneer je een mollie account gekoppeld hebt)
- Verzendadres nieuwsbrieven: Gebruik het standaard Squatix-adres om nieuwsbrieven te verzenden (info@squatix.com) of stel een ander e-mailadres in.

![club settings](/assets/images/club_settings.png)
