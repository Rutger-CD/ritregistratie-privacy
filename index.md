---
layout: default
title: Privacy policy — Weg.log Ritregistratie
---

# Privacyverklaring — Weg.log Ritregistratie

**Versie 1.0 — Laatst bijgewerkt: 2026-05-27**

Deze privacyverklaring beschrijft welke gegevens de Weg.log Ritregistratie-app
("de app") verzamelt, waarom, hoe lang we ze bewaren en welke rechten je hebt
op basis van de Algemene Verordening Gegevensbescherming (AVG/GDPR).

De verwerkingsverantwoordelijke is **Rutger Thus** (Craft Digital), bereikbaar
via [rutger@craft-digital.nl](mailto:rutger@craft-digital.nl).

## Welke gegevens verzamelen we

De app verzamelt uitsluitend de gegevens die nodig zijn om je ritten te
registreren, te tonen en — indien je daarvoor inlogt — te synchroniseren
tussen je apparaten.

- **GPS-locatiegegevens.** Tijdens een actieve rit registreert de app je
  positie (locatie, snelheid, tijdstempel) zodat het ritverloop, de afstand
  en de start- en eindpunten bepaald kunnen worden. Buiten een actieve rit
  wordt er geen locatie opgeslagen.
- **E-mailadres.** Als je een account aanmaakt, koppelen we je e-mailadres
  aan je account zodat je op meerdere apparaten op dezelfde data kunt inloggen
  en zodat we je accountverzoeken (bv. wachtwoord-reset, accountverwijdering)
  kunnen verwerken.
- **Gebruikersnaam.** Vrij te kiezen weergavenaam, alleen zichtbaar voor jezelf
  in de app.
- **Rithistorie.** Per geregistreerde rit: starttijd, eindtijd, afstand, route
  (geanonimiseerde GPS-punten), rit-type (privé/zakelijk), eventuele klant- of
  locatie-labels die je zelf invoert.
- **Apparaat- en diagnose-informatie.** Bij het versturen van feedback via de
  "Stuur feedback"-knop voegt de app automatisch de app-versie, het
  apparaatmodel en de Android-versie toe — uitsluitend om bugrapporten
  reproduceerbaar te maken.

We verzamelen **géén** advertentie-identifiers, contacten, foto's, of
content van andere apps.

## Waar wordt het opgeslagen

- **On-device SQLite-database.** Alle ritten, klanten, locaties en
  voorkeursinstellingen staan primair lokaal op je apparaat opgeslagen. Zonder
  account werkt de app volledig offline en verlaat geen enkele rit je toestel.
- **Firebase Firestore (Google Ireland Limited).** Als je inlogt én
  "Routes synchroniseren" aanzet in *Mijn account*, worden ritten en
  voorkeuren versleuteld in transit gesynchroniseerd naar Firestore zodat ze
  beschikbaar zijn op je andere apparaten. Servers staan binnen de EU.
- **Firebase Authentication (Google Ireland Limited).** Beheert je
  inloggegevens (e-mail + versleuteld wachtwoord, of OAuth-provider-token).

## Wie heeft toegang

- **Jij.** Via de app op je eigen ingelogde apparaten.
- **De ontwikkelaar** (Rutger Thus / Craft Digital). Heeft beheers­toegang tot
  het Firebase-project voor onderhoud, troubleshooting en het uitvoeren van
  verwijderingsverzoeken. Je rit­data wordt **niet** ingezien voor andere
  doeleinden en niet gedeeld met derden.
- **Firebase / Google als verwerker.** Verwerkt data uitsluitend in opdracht
  van de ontwikkelaar onder een
  [Data Processing Addendum](https://firebase.google.com/terms/data-processing-terms).
  Google heeft geen zelfstandig gebruiksrecht op je data.

We verkopen, verhuren of delen je gegevens niet met advertentienetwerken,
analytics-derden of marketingpartners.

## Bewaartermijn

We bewaren je gegevens zolang je account actief is.

- **Lokale data** blijft op je apparaat staan totdat je de app verwijdert of
  via *Mijn account → Account verwijderen* je account opzegt.
- **Cloud-data** (Firestore + Authentication) wordt volledig verwijderd zodra
  je je account verwijdert. Dit gaat via een server-side delete-flow die alle
  documenten onder jouw user-id wegschrijft.

We hanteren geen automatische inactiviteits­verwijdering en geen extra
"soft-delete"-periode na verwijdering — een verwijderingsverzoek leidt
direct tot permanente verwijdering.

## Cookies en tracking

De app gebruikt **geen** cookies, **geen** advertentie-identifiers en
**geen** analytics-tracking op individueel niveau.

Firebase Analytics is in de app **uitgeschakeld** voor user-level events.
Indien er in de toekomst geaggregeerde gebruiksstatistieken worden ingezet
(bv. crash-rates), gebeurt dat uitsluitend in geanonimiseerde, geaggregeerde
vorm — nooit herleidbaar tot individuele gebruikers.

## Je rechten onder de AVG/GDPR

Als gebruiker heb je de volgende rechten met betrekking tot jouw
persoonsgegevens. Je kunt elk verzoek indienen door een e-mail te sturen naar
[rutger@craft-digital.nl](mailto:rutger@craft-digital.nl). We reageren in de
regel binnen 14 dagen.

- **Inzage** — een overzicht ontvangen van alle gegevens die we van je
  opslaan.
- **Rectificatie** — onjuiste gegevens laten corrigeren. Veel velden
  (gebruikersnaam, e-mail, rit-eigenschappen) kun je zelf in de app aanpassen.
- **Verwijdering ("recht om vergeten te worden")** — je volledige account en
  alle bijbehorende data laten wissen. Dit kan direct via *Mijn account →
  Account verwijderen* in de app, of op verzoek per e-mail.
- **Dataportabiliteit** — een export van je gegevens in een
  machine-leesbaar formaat (JSON of CSV) ontvangen.
- **Bezwaar of beperking** — bezwaar maken tegen verwerking, of de
  verwerking laten beperken zolang een correctie- of bezwaar-verzoek loopt.
- **Klacht bij de toezichthouder** — je kunt te allen tijde een klacht
  indienen bij de
  [Autoriteit Persoonsgegevens](https://autoriteitpersoonsgegevens.nl) als
  je vindt dat we onzorgvuldig met je gegevens omgaan.

## Beveiliging

- Communicatie tussen de app en Firebase verloopt over TLS (HTTPS).
- Wachtwoorden worden door Firebase Authentication versleuteld opgeslagen.
- Toegang tot Firestore is afgeschermd via per-user security rules — andere
  ingelogde gebruikers kunnen jouw data niet inzien.
- De on-device database is alleen toegankelijk voor de Weg.log-app
  (standaard Android-isolatie).

## Wijzigingen in deze verklaring

We kunnen deze privacyverklaring aanpassen, bijvoorbeeld als de
functionaliteit van de app uitbreidt of als regelgeving wijzigt. Het
versienummer en de datum boven aan deze pagina geven aan wanneer de
verklaring voor het laatst is bijgewerkt; significante wijzigingen worden
hieronder in de changelog vermeld.

## Contact

Vragen, verzoeken of klachten kun je richten aan:

**Rutger Thus — Craft Digital**
E-mail: [rutger@craft-digital.nl](mailto:rutger@craft-digital.nl)

## Changelog

- **v1.0 — 2026-05-27** — Initiële publicatie.
