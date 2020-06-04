---
title: Zadanie 10
body_classes: title-center title-h1h2
---
# Táto stránka je hostovaná na Azure!

### Prečo hostovať web na Azure web services.
Predstavte si, že pracujete pre spoločnosť, ktorá napríklad robí zdravotnícky výskum a vy máte na starosti správu serverov v priestoroch spoločnosti. Servery, ktoré spravujete, prevádzkujú všetku firemnú infraštruktúru, od webových serverov po databázy. Časom však narazíte na problém, že hardvér už nestíha držať krok s novými aplikáciami na analýzu údajov, ktoré sú nasadené na konkrétny server. V prípade, že máte niekoľko rôznych serverov a prispôsobených softvérov, je pre vás jednoduchšie preniesť si vaše servery do Azure pomocou Azure Virtual Machines.

#### Výhody Azure
Najväčšie výhody Azure oproti svojej konkurencii:
* Vysoká dostupnosť
* Vynikajúce dátové zabezpečenie
* Rozšíriteľnosť
* Cenovo výhodné
* Umelá inteligencia
* Umožňuje automatizáciu opakujúcich úloh
* Azure vám dovoľuje používať akýkoľvek framework, správcovskú platformu či nástroj

### Ako začať s web hostingom? 
V bežnom hostiteľskom prostredí sa vývojári zvyčajne stretávajú s problémom, keď svoje webové stránky nasadia do výroby. Služba webových stránok Azure zaisťuje, že vývojári pri nasadení svojich webových stránok narazia na najmenšie problémy. Webová služba Azure tiež patrí do kategórie PaaS (Platform as a Service). To znamená, že webové stránky môžu byť nasadené bez toho, aby skutočne mali plnohodnotnú infraštruktúru. Pomocou nasledujúcich krokov si môžete jednoducho vytvoriť nový web v službe Microsoft Azure.

#### Jednoduché vytvorenie
1.	Prihláste sa do služby Azure Management Portal.  
2.	Vyberte možnosť “Virtual Machines” a kliknite na “Add”.  
3.	Vyberte si možnosť predplatného (Všetky zdroje v predplatnom Azure sa fakturujú spoločne) a zvoľte resource group.  
4.	Zvoľte si meno Vašej Virtual Machine, región, v ktorom sa nachádzate , možnosti dostupnosti (Azure ponúka celý rad možností pre správu dostupnosti a odolnosti vašich aplikácií. Navrhnite svoje riešenie na použitie replikovaných virtuálnych počítačov v zónach dostupnosti alebo množinách dostupnosti, aby ste ochránili svoje aplikácie a údaje pred výpadkami a údržbou dátového centra.)   
5.	Vyberte základný operačný systém pre VM.  
6.	Vyberte veľkosť VM na podporu pracovného zaťaženia, ktoré chcete spustiť. Veľkosť, ktorú si vyberiete, potom určuje faktory, ako je výkon spracovania, pamäť a kapacita pamäte. Azure ponúka širokú škálu veľkostí na podporu mnohých druhov použitia. Azure účtuje hodinovú cenu na základe veľkosti a operačného systému VM. 
7.	Vyberte, či účet správcu, ktorý bude použitý  na autentifikáciu. Používateľské meno / heslo alebo kľúče SSH. 
8.	Zadajte verejný kľúč RSA vo formáte s jedným riadkom (začínajúci na „ssh-rsa“) alebo vo viacerých riadkoch vo formáte PEM. Kľúče SSH môžete generovať pomocou ssh-keygen v systéme Linux a OS X alebo PuTTYGen v systéme Windows. 
9.	V predvolenom nastavení je prístup k virtuálnemu stroju obmedzený na zdroje v rovnakej virtuálnej sieti a prenos z riešení na vyrovnávanie záťaže Azure. Vyberte Žiadne, ak chcete potvrdiť, alebo sa rozhodnite povoliť prenos z verejného internetu do jedného z týchto bežných portov.

#### Ako vytvoriť vlastnú  Webovú aplikáciu?
1.	Prihláste sa do vášho konta Azure.
2.	Kliknite na možnosť „Web apps“ a kliknite na „add“.
3.	Vyberte si možnosť predplatného (Všetky zdroje v predplatnom Azure sa fakturujú spoločne) a taktiež zvoľte resource group.  
4.	Zvoľte si meno Vašej Web App, možnosť publikovania webovej aplikácie (Code alebo Docker Container)
5.	Ak zvolíte možnosť Docker Container, máte možnosť si zvoliť operačný systém na ktorom bude aplikácia spúšťaná.
6.	Vyberte región, v ktorom sa nachádzate.

### Microsoft Azure vo vzdelávaní
Microsoft ponúka široké spektrum bezplatných overených kurzov na jednom mieste. Vďaka týmto kurzom môžete vašim žiakom poskytnúť bezpečný a spoľahlivý priestor na učenie. Nájdete tu viac ako 500 kurzov, ktoré sú momentálne dostupné primárne v angličtine. Všetky kurzy nájdete [tu](https://docs.microsoft.com/sk-sk/learn/browse/?products=azure). Vaši žiaci sa tak môžu zlepšovať v množstve programovacích jazykov, či službách, ktoré ponúka Microsoft Azure.

#### Odporúčame:
* [Umelá inteligencia (začiatočník)](https://docs.microsoft.com/sk-sk/learn/paths/get-started-with-artificial-intelligence-on-azure/)
* [Základy dátovej vedy](https://docs.microsoft.com/sk-sk/learn/paths/foundations-data-science/)

### Zhrnutie
Vďaka Microsoft Azure môžete hostovať svoj web v bezpečnom a prehľadom prostredí. Jedna z najväčších výhod Microsoft Azure je rozšíriteľnosť služieb a cenová výhodnosť služieb. Nezabudnite taktiež využiť služby Microsoft Learn kde sa môžete získať množstvo nových vedomostí a znalostí o Cloudovom systéme Microsoft Azure. 