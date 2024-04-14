---
layout: admin
title: Configuratie
nav_order: 7
---

# Configuratie
{: .no_toc }

## Inhoudsopgave
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Meetingscategorieën

Om een meetingscategorie toe te voegen, klik op het + symbool. 
Volgende data kan ingegeven worden:
- Naam
- Kleur: wordt weergegeven in de meetingskalender om meetings met een verschillende categorie van elkaar te kunnen onderscheiden
- Inschrijven: enkel leden met een geldig abonnement kunnen inschrijven op de meeting of alle leden kunnen inschrijven
- Zichtbaarheid: enkel leden met een overeenkomend abonnement kunnen deze categorie zien of alle leden kunnen deze categorie zien
- Prijs voor een enkele meeting: je kan hierin optioneel een prijs instellen. Wanneer leden zich willen inschrijven voor een meeting van deze categorie en ze hebben geen geldig abonnement voor deze meeting zal de prijs getoond worden. Wanneer het lid zich dan inschrijft, wordt er doorverwezen naar de betaalpagina. Zodra de betaling voltooid is, is het lid automatisch ingeschreven. Indien dit veld leeg gelaten wordt, is inschrijven gratis tenzij "enkel leden met een geldig abonnement kunnen inschrijven" is ingeschakeld.
- Trainers: selecteer trainers die automatisch zullen ingevuld worden bij het aanmaken van een meeting van deze categorie

![Meeting category](/assets/images/training_categorie.png)

Voor het aanpassen van een meetingscategorie: klik op het potloodje

## Abonnementscategorieën

Om een abonnementscategorie toe te voegen, klik op het + symbool. 
Volgende data kan ingegeven worden:
- Naam
- Gelinkte meetingscategorieën: link een van de aangemaakte meetingscategorieën aan de abonnementscategorie. Op deze manier kan je bepalen voor welke meetings een lid kan inschrijven 
(indien de meetingscategorie enkel voor een geldig abonnement inschrijfbaar is).

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
- Meetings wijzigen (Aanpassen en aanmaken van meetings)

Een aantal standaard rollen zijn altijd aanwezig en kunnen niet verwijderd of aangepast worden:
- Eigenaar (Alle permissies, uitgezonder trainer. Enkel toegekend aan de persoon die de club aangemaakt heeft, kan beheerders aanduiden of verwijderen.)
- Beheerder (Alle permissies, uitgezonderd trainer, kan geen andere beheerders aanduiden of verwijderen)
- Trainer (Kan als trainer toegevoegd worden aan een meeting)

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
Met teams kan je jouw leden onderverdelen in verschillende teams. Bij het zenden van nieuwsbrieven kan je bijvoorbeeld een team gebruiken als ontvanger van de nieuwsbrief. 
(zie [Nieuwsbrieven](newsletter.md)) Je kan ook een of meerdere teams aan een training linken zodat alle leden van deze teams automatisch ingeschreven worden voor die 
training (zie [Editeer/creeër meeting](meetings.md#editeercreeër-meeting))

![Teams](/assets/images/teams.png)

Om een team toe te voegen, klik op het + symbool. 
Volgende data kan ingegeven worden:
- Naam
- Leden: selecteer alle leden die tot het team behoren

Aanpassen van een Team: klik op het potloodje

Aanmaken van een team kan ook door in de leden pagina eerst de leden te selecteren en daarna de actie "Team aanmaken" te selecteren (zie [Team aanmaken](member-management.md#team-aanmaken))
	
## Vragenlijsten
Indien gewenst kan je jouw leden op elk moment een aantal vragen laten beantwoorden. Zo kan je bijvoorbeeld vragen of ze ook een 
vrijwillige functie in de club willen uitvoeren, voor welke afdeling ze zich inschrijven in jouw club enzovoort. Standaard is er ook een vragenlijst die kan getoond worden wanneer een gebruiker
lid wilt worden van jouw club. De antwoorden van het lid zie je bij hun lidverzoek (zie [Ledenverzoeken](member-management.md#ledenverzoeken)) wanneer het over een lid verzoek vragenlijst gaat
of bij formulieren (zie [Formulieren](member-management.md#formulieren)).

De vragen en antwoorden kunnen aangemaakt worden in verschillende talen. De vraag zal voor de gebruiker 
automatisch verschijnen in de taal die hij in zijn profiel ingevuld heeft.

![member question](/assets/images/member_question.png)
		
Om een nieuwe vraag aan te maken, klik op "Voeg toe". Onder "Vraag" vul je de vraag in. Klik op "Vertaling toevoegen" om de vraag in meerdere talen beschikbaar te stellen.
Onder "Antwoorden" vul je een mogelijk antwoord op de vraag in. Klik op "Vertaling toevoegen" om het antwoord in meerdere talen beschikbaar te stellen. Klik op + om een extra mogelijk antwoord op de vraag toe te voegen.

Om de vraag te bewaren klik je op "Bewaar". Het volgende lid dat lid wil worden van de club zal de vraag dienen te beantwoorden.
		
Om een eerder aangemaakte vraag aan te passen, klik op het potloodje. Hetzelfde scherm als bij het aanmaken van een vraag opent zich met de reeds eerder ingevulde waarden.

**Standaard vragen**

Er zijn ook een aantal standaard vragen beschikbaar. Deze dien je enkel actief of inactief te zetten om ze te laten verschijnen.

- Ik wil me inschrijven voor de nieuwsbrief van club X
- Welk abonnement wens je? (hiervoor dienen abonnementen aangemaakt te zijn (zie [Abonnementen](#abonnementen)))
- Aan welk team moet je toegevoegd worden? (hiervoor dienen teams aangemaakt te zijn (zie [Teams](#teams)))

![standard questions](/assets/images/standard_questions.png)
	
## Club

Onder club kan je volgende dingen bekijken:
- Bekijk het abonnement waarover de club beschikt bij squatix en de geldigheidsdatum. Zodra de geldigheidsdatum is overschreden is het niet meer mogelijk nieuwe leden toe te voegen.
- Agenda delen: het is mogelijk de meetingskalender te gebruiken in een externe kalender applicatie die ICS ondersteunt. Kopieër daartoe de ics-url naar de benodigde 
plaats. Voor ondersteuning neem contact op met het team dat de applicatie aanbiedt.
- Handleiding: klik op de link om de beheerdershandleiding te bekijken.
- Mollie: koppel jouw Squatix account met een mollie account om betalingen te kunnen ontvangen (zie [Mollie](payments.md#mollie))
- Shop: toon de shop aan jouw leden waar ze zelf abonnementen kunnen aankopen (dit gaat enkel wanneer je een mollie account gekoppeld hebt)
- Verzendadres nieuwsbrieven: Gebruik het standaard Squatix-adres om nieuwsbrieven te verzenden (info@squatix.com) of stel een ander e-mailadres in.

![club settings](/assets/images/club_settings.png)
