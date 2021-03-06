# TurrisGadgets
(Český popis níže)

UWP library for Turris Gadgets see below

https://www.turris.cz/gadgets/start

This library is primary focused and tested on Raspberry Pi 2 running Windows 10 IoT core

Because Turris Gadgets is a community project in Czech republic only (as far as I know) Wiki and forum will be in Czech language only. If somebody is interested in this project or Turris Gadgets you may contact CZ.NIC or Jablotron. CZ.NIC is running project Turris and newly even Turris Omnia (succesor os Turris router) https://www.indiegogo.com/projects/turris-omnia-hi-performance-open-source-router#/ https://omnia.turris.cz/en/ Jablotron is producer of (not only) surveillance/security system http://www.jablotron.com/

## Popis
Knihovna slouží pro zjednodušení práce a vývoje nad Windows 10 pomocí C#. V současné době je projekt v aplha fázi kde se postupně přidávají funkcionality a ladí komunikace se sadou.

## Instalace
Pro instalaci lze použít nuget balíček https://www.nuget.org/packages/Pospa.NET.TurrisGadgets

## Plány
<s>Přeškrtnuté</s> už realizováno.
* <s>Komunikace s Turris Dongle</s>
* <s>Enumerace zařízení připojených k Turris Dongle</s>
* <s>Eventy pro zprávy ze zařízení</s>
* Plné ovládání sady pomocí managed objektů a nikoliv zpráv přímo do Turris Dongle
   - AC-82  Přijímač 2x relé 230V Ovládání světel  
   - AC-88  Dálkově ovládaná zásuvka Zapnutí přímotopu  
   - JA-80L Interní siréna Zvuková signalizace 
   - <s>JA-81M  Univerzální rozhraní Pro připojení externích detektorů</s>
   - <s>JA-82SH  Detektor otřesu nebo náklonu Detekce manipulace s předměty</s>
   - <s>JA-83M  Magnetický detektor mini Detekce otevření dveří</s>
   - <s>JA-83P  PIR detektor Detekce pohybu osob</s>
   - <s>JA-85ST  Detektor kouře a teploty Detekce požáru</s>
   - RC-86K  Dálkový ovladač Aktivace/deaktivace systému
   - <s>TP-82N  Termostat</s>
* Podpora pro Azure IoT Suite https://www.microsoft.com/en-us/server-cloud/internet-of-things/azure-iot-suite.aspx
   - <s>Podpora IoT Hub REST API</s>
   - Registrace do IoT Hubu
   - Posílání událostí do IoT Hubu
   - Posílání zpětných zpráv do zařízení
* Podpora SIGFOX sítě (http://www.sigfox.com/en/) pomocí SNOC modulu (http://yadom.fr/carte-rpisigfox.html)
   - <s>Podpora SNOC modulu pro Sigfox</s>
   - Podpora posílání událostí do IoT Hubu přes SIGFOX (záložní varianta pro případ výpadku Internetu, nebo sabotáže sítě)
   - Podpora zasílání příkazů je díky technologickým omezením takřka nemožná a nebudu se o ní ani pokoušet
* Podpora pro automatické učení se nových prvků
* Možnost vytváření workflow na základě událostí od zařízení

## Kontakt
V případě že najdete chybu, budete mít nápad na rozšíření, budete se chtít zeptat, nebo prostě jen pokecat, napište mi na pospa@pospa.net, nebo nechte zprávu zde. Díky

-<{Pospa}>-
