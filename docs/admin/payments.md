---
layout: admin
title: Betalingen
nav_order: 9
---

# Betalingen
{: .no_toc }

## Inhoudsopgave
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## Inleiding
Via Squatix kan je betalingen innen bij jouw leden. Je krijgt een handig overzicht wie al betaalt heeft waar je later nog naar kan terugkijken. Geen gedoe meer met
lijstjes om alles bij te houden of betalingen die je via verschillende kanalen ontvangt. Om de betalingen zelf uit te voeren werkt Squatix samen met Mollie (zie [Mollie](#mollie))

## Instellen
Om te starten met betalingen dien je eerst een Mollie account aan te maken en deze te linken met Squatix. Ga hiervoor naar instellingen > Mollie en klik op "verbinden"

![mollie connect](/assets/images/mollie_connect.png)

Volg de instructies op het scherm om Squatix toegang te geven tot jouw Mollie account. Maak een nieuwe Mollie-account aan of log in op jouw bestaande Mollie-account indien je daarover beschikt. Zodra je
hiermee klaar bent wordt je teruggestuurd naar Squatix en is jouw account klaar om betalingen aan te maken.

![mollie connect success](/assets/images/mollie_connect_done.png)

Via "verbinding controleren" kan je op elk moment nakijken of de verbinding tussen Squatix en Mollie nog steeds ok is. Wens je te koppelen met een andere Mollie-account klik dan op "opnieuw verbinden".

## Betaling aanmaken

Betalingen kunnen op twee manieren aangemaakt worden:

- Individueel per lid: ga naar "Betalingen" en klik op "Voeg toe"
- Voor meerdere leden tegelijkertijd: Ga naar "Leden" (weergave "Leden"), selecteer een of meerdere leden en actie "Betaling aanmaken", klik op "Uitvoeren"

Volgende velden kan je invullen:

- Lid: Selecteer het lid waarvoor de betaling aangemaakt moet worden. Indien je een betaling voor meerdere leden tegelijkertijd aanmaakt is dit veld afwezig.
- Waarde: Het bedrag van de betaling in euro.
- Beschrijving: Geef een beschrijving aan de betaling, deze beschrijving is ook zichtbaar voor het lid. Maak deze duidelijk genoeg zodat je later nog weet waarvoor de betaling diende.
- Betalingsregels: Je kan één of meerdere betalingsregels toevoegen (zie [Betalingsregels](#betalingsregels)). Dit is niet verplicht.

![payment example](/assets/images/payment.png)

### Betalingsregels

Met betalingsregels kan je leden een korting geven indien ze voor een bepaalde datum betalen of een boete indien ze na een bepaalde datum betalen. Je kan één of meerdere betalingsregels aan een 
betaling koppelen.

Om een betalingsregel toe te voegen klik op "Voeg betalingsregel toe". Volgende velden dien je in te vullen:

- Type betalingsregel: Korting/Boete
- Datum: Indien betaald voor (bij korting)/Indien betaald na (bij boete)
- Soort: Vast (bedrag in euro)/Percentage (een percentage van het betalingsbedrag)
- Waarde: De korting/boete die het lid krijgt in euro of een percentage

Om een betalingsregel weer te verwijderen klik rechts in de betalingsregel op het prullenbakje.

![payment rules](/assets/images/paymentrules.png)

In het voorbeeld hierboven zal het lid:

- €110 moeten betalen voor 8 januari.
- €120 moeten betalen vanaf 8 januari tot en met 15 januari.
- €126 moeten betalen na 15 januari.

## Status controleren

Krijg een overzicht van alle aangemaakte betalingen in jouw club door te navigeren naar "Betalingen". Zoeken kan op lid en op status van de betaling.

De belangrijkste statussen zijn:

- Open: De betaling is aangemaakt maar het lid heeft nog niet betaald.
- Betaald: Het lid heeft betaald.
- Geannuleerd: De betaling is door een beheerder geannuleerd.
- Mislukt: Het lid heeft proberen betalen maar de betaling is mislukt. Hij heeft de mogelijkheid opnieuw te proberen.

### Detail

Door in het overzicht op een betaling te klikken opent zich de detailpagina.

De getoonde details zijn:
- Lid
- Status
- Waarde
- Aanmaakdatum
- Beschrijving
- Eventuele betalingsregels.

Voor een betaling in status open is het mogelijk om de betaling te annuleren.

![payment detail open](/assets/images/payment_detail_open.png)

In het detail van een betaalde betaling waar betalingsregels bij van toepassing zijn wordt het originele bedrag vermeld, het betaalde bedrag en de reden van de aanpassing.

![payment detail closed](/assets/images/payment_detail_closed.png)

## Kost

Squatix rekent een transactiekost aan van 0,9% per transactie (min 0,25 €), excl kosten Mollie.

## Mollie

Om de betalingsfunctionaliteit van Squatix te kunnen gebruiken dien je over een account te beschikken bij Mollie. Indien je hier nog niet over beschikt kan je deze automatisch aanmaken wanneer
je Squatix instelt voor betalingen (zie [Instellen](#instellen)).

Eens jouw leden hun betaling hebben overgemaakt kan je het geld vanop jouw Mollie account overmaken naar een rekeningnummer. Hiervoor dien je naar jouw aangemaakte account op www.mollie.com te
surfen en daar de instructies te volgen.

Voor meer informatie over Mollie ga naar [https://www.mollie.com](https://www.mollie.com).
Voor informatie over de gehanteerde tarieven kijk op [https://www.mollie.com/be/pricing](https://www.mollie.com/be/pricing).

