# MediaPlanner

Plánovaný prehrávač hudby, internetových streamov a zvukových oznamov podľa prevádzkových hodín.

Pre Windows 10 a Windows 11, x64.

## Stiahnuť

[Stiahnuť MediaPlanner.exe](https://github.com/enthilza/MediaPlanner/releases/latest/download/MediaPlanner.exe) · [Všetky vydania](https://github.com/enthilza/MediaPlanner/releases)

Samostatné EXE obsahuje .NET runtime aj prehrávacie jadro VLC, nič sa neinštaluje. Ulož ho do priečinka, kde máš právo zapisovať, a spusti.

## Aktualizácie

Aplikácia pri štarte overí, či existuje novšie vydanie, a tlačidlom v Nastaveniach (alebo v tray menu) to môžeš skontrolovať aj ručne. Inštaluje sa až po tvojom potvrdení.

Každé vydanie obsahuje `MediaPlanner.exe`, `update.json` a `update.sig`. Aplikácia overí digitálny podpis popisu vydania (RSA-3072/SHA-256) zabudovaným verejným kľúčom a potom veľkosť, kontrolný súčet SHA-256 a verziu stiahnutého EXE. Nová verzia musí pred výmenou úspešne prejsť kontrolou štartu, inak ostane pôvodná verzia nedotknutá.

Nejde o Windows Authenticode podpis, preto môže Windows SmartScreen pri prvom spustení zobraziť upozornenie.

## Súkromie

Kontrola aktualizácií kontaktuje iba GitHub. Plán (`schedule.json`) a log (`app.log`) sa ukladajú vedľa `MediaPlanner.exe`; dočasné súbory aktualizácie sa po inštalácii automaticky vymažú.

Tento repozitár obsahuje iba distribučné súbory a informácie o vydaniach.
