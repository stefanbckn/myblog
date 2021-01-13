---
layout: single
title: Siri shortcuts & YNAB
date: 2021-01-13 13:51:01 +0100
tags: [budget,ynab, tech, iphone, shortcuts, siri, siri shortcuts]
categories: [budget, tech]
excerpt: "Hoe vereenvoudig ik het ingeven van transacties in YNAB via Siri shortcuts?"
gallery:
  - url: assets/images/sirishortcuts/IMG_3079.PNG
    image_path: assets/images/sirishortcuts/IMG_3079.PNG
    alt: "Voeg opdracht toe"
    title: "Voeg opdracht toe"
  - url: assets/images/sirishortcuts/IMG_3080.PNG
    image_path: assets/images/sirishortcuts/IMG_3080.PNG
    alt: "Zoek YNAB"
    title: "Zoek YNAB"
  - url: assets/images/sirishortcuts/IMG_3081.PNG
    image_path: assets/images/sirishortcuts/IMG_3081.PNG
    alt: "Geef je shortcut een naam"
    title: "Geef je shortcut een naam"
---
Als je vaak dezelfde transactie ingeeft kan je via *shortcuts* dit proces drastisch vereenvoudigen.
Ik ga bijvoorbeeld meerdere keren per week brood kopen. Telkens dezelfde transactie, op dezelfde plaats en met dezelfde rekening. Momenteel geef ik al mijn transacties manueel in.

Met de volgende stappen heb ik een shortcut **brood** gemaakt die ik nu kan gebruiken telkens ik een brood ga kopen.

#### Wat heb je hier voor nodig
* Een Apple iPhone 📱
* De shortcuts app
* De YNAB app

Open je de *shortcuts* app en maak je een nieuwe shortcut aan.

Volg deze stappen om je shortcut aan te maken:
* Rechtsbovenaan druk je op **+** om een nieuwe shortcut te maken
* Klik op **Voeg een taak toe** en zoek de YNAB opdracht die je wil toevoegen
* Klik op **Volgende** en geef je shortcut een naam
* Klik op **Gereed** en je hebt je shortcut

{% include gallery %}

{% capture siricommand %}
Na al deze stappen kan je via Siri de shortcut uitvoeren. Dit doe je door de naam van je shortcut te gebruiken: "**Hé Siri, <de naam van je shortcut>**". Je kan ook via widgets de shortcut starten.
{% endcapture %}
{{ siricommand | xml_escape | markdownify }}

{% capture notice-waarschuwing %}
Als je **YNAB** niet in de *shortcuts* app ziet staan zorg dan allereerst dat je de laatste versie hebt geïnstalleerd. Ga vervolgens naar YNAB en geef op zijn minst **1 nieuwe** transactie in. Ga terug naar de *shortcuts* app en YNAB zou nu beschikbaar moeten zijn met je laatste transacties. **Sla deze stap niet over.**
{% endcapture %}
<div class="notice--warning">{{ notice-waarschuwing | markdownify }}</div>
