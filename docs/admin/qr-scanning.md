---
layout: admin
title: QR scanning
nav_order: 5
---

# QR scanning
{: .no_toc }

## Inhoudsopgave
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Introductie

Door de QR-code van een lid te scannen kan je hem of haar als aanwezig aanduiden voor een meeting. Door een lid te scannen wanneer hij een meeting binnenkomt wordt hij aangeduid als "bevestigd".
Na het scannen wordt gemeld indien het lid niet over een geldig abonnement beschikt. Het is ook mogelijk automatisch een beurt af te trekken van het abonnement indien het lid over een 
beurten abonnement beschikt.

Scanning kan enkel uitgevoerd worden met de mobiele app versie van de applicatie. Om het scannen op te starten, ga onderaan naar "Club", open "Meetings" en klik op de QR-scan knop (1)

![QR scan button](/assets/images/qr_scanbutton.png)

Het scan scherm opent zich, richt de scanner naar een QR-code om verder te gaan.

![QR scan new scan](/assets/images/qr_newscan.png)

## Code scannen

Een QR-code scannen kan op twee manieren:
- De afgeprinte code scannen die kan gegenereerd worden via [QR genereren](member-management.md#genereer-qr). 
- De code scannen die het lid toont op zijn smartphone

Na het scannen van de code kunnen twee gevallen zich voordoen:

**Lid bevestigen**  
Het lid heeft één profiel dat lid is van de club en het "lid bevestigen" scherm opent zich. Indien het getoonde lid correct is,  duw op "Bevestig"

![Confirm member](/assets/images/qr_confirmmember.png)

**Selecteer lid**  
Het lid is gekoppeld aan meerdere profielen die lid zijn van de club: in dit geval weet Squatix niet welk van deze leden
zich momenteel wil laten bevestigen voor de meeting. Selecteer in de dropdown het juiste lid en klik op "Bevestig"

![Select member](/assets/images/qr_selectmember.png)

## Meeting selecteren

Nadat het lid geselecteerd of bevestigd is wordt de lijst van mogelijke meetings getoond. De lijst bevat alle meetings die starten tussen (nu - 1 uur) en (nu + 2 uur). Klik naast de 
juiste meeting op
- Inschrijven en bevestigen: het lid is nog niet ingeschreven voor de meeting, de actie zal hem zowel inschrijven als bevestigen
- Bevestigen: het lid is ingeschreven voor de meeting, de actie zal hem bevestigen

Zodra het lid bevestigd is vernieuwt het scherm zich. Het is mogelijk het lid weer te verwijderen indien een fout gemaakt is. Na de bevestiging zal naast het lid in de detail pagina van de meeting
een vinkje staan in de "Bevestig" kolom (zie [Meeting deelnemers](meetings.md#deelnemers))

![Select meeting](/assets/images/qr_selecttraining.png)

Twee extra meldingen kunnen getoond worden zodra op "Bevestigen" geklikt is:
- Het lid heeft geen geldig abonnement: wilt u doorgaan ja/nee
- Wilt u een beurt aftrekken van het abonnement: indien het lid een beurtenkaart heeft

## Fouten

Zodra zich een fout voorgedaan heeft wordt deze getoond in een rode kader. Volgende fouten kunnen zich voordoen:

- Foute QR-code gescand: mogelijk behoort de getoonde code niet toe aan een lid van uw club
- Geen meetings beschikbaar: er zijn geen meetings gevonden die starten tussen 1 uur voor en 2 uur na het moment van scannen

![Error scanning](/assets/images/qr_error.png)





