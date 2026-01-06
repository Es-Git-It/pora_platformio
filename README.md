# PlatformIO

## Utemeljitev izbire

* Orodje za razvoj programov za različne mikrokrmilnike
* Avtomatizira nastavitve, upravljanje knjižnic, prevajanje in nalaganje kode na napravo
* Najpogosteje uporabljen kot razširitev za VS Code (lahko tudi v CLion ali pa kot CLI orodje za terminal)

## Prednosti

* Napredno upravljanje knjižnic (samodejno reševanje odvisnosti)
* Glede na izbran mikrokrmilnik sam nastavi prevajalnik, build nastavitve in okolje
* Nastavitve so poenoteno shranjene v datoteki platformio.ini in vezane na projekt (ne rabimo spreminjati nastavitev v urejevalniku, ko delamo z novo napravo)

## Slabosti

* Za začetnike kompleksnejša namestitev
* Zakasnitev pri podpori najnovejše opreme (razvijalci PlatformIO morajo nove knjižnice in definicije integrirati v svoj sistem)
* Požrešnejše od alternativ (Arduino vzame dosti manj prostora), zato ga je nesmiselno uporabljati za preproste naloge (npr. Arduino IDE je bolj praktičen za enostaven senzor)

## Licenca

Apache License 2.0

## Število uporabnikov

* Več kot [6 milijonov](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) prenosov na Visual Studio Marketplace

## Časovna in prostorska zahtevnost

* Odvisno od projekta, knjižnic in izbrane platforme
* V mojem primeru O(1) saj je bilo branje senzorja in pošiljanje meritev konstantno ter neodvisno od količine podatkov

## Vzdrževanje

* Število razvijalcev: 92
* Zadnja sprememba: 11.3.2025

## Lastna uporaba

* Druga aplikacija pri vajah
* Na M5StickC PLUS2 sem naložil kodo in s senzorjem M5Stack ENV III zabeležil vlago in temperaturo ob nastanku grafita, saj vplivata na njegovo obstojnost
* PlatformIO uporabil kot VS Code extension
* Uporabil sem tudi MQTT protokol in Mosquitto broker ter Arduino (framework)
<img width="1000" height="1000" alt="image" src="https://github.com/user-attachments/assets/4fa4ed27-3801-4207-a649-578cb05ae64c" />
<img width="270" height="532" alt="pic2" src="https://github.com/user-attachments/assets/555ad1f3-a962-4bce-b2bd-9507a5a1b8fa" />
<img width="400" height="900" alt="pic1" src="https://github.com/user-attachments/assets/c4874cbe-6e6d-4e69-b4d4-c11b47fab6be" />
