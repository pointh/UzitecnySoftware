# Užitečný Software
## Verze 1

Užitečný software podle vlastního uvážení. Jen hry jsou zakázané.

Pavel Švec <br/>
pavel.svec@ssps.cz <br/>
10. 5. 2021

* Úvod
  * Účel dokumentu
  * Konvence dokumentu
    * Důležitost - 1 nejvyšší, 5 nejnižší
    * Všechny kritické požadavky budou tučně
  * Kontakty
    * Pavel Švec pavel.svec@ssps.cz, tel. 333 333 333, Twitter @progman
    * Jaromír Jonáš jonas@ssps.cz, Twitter @jjonas
  * Odkazy na ostatní dokumenty
    * Zadávací dokumentace na ...
* Celkový popis
  * Funkce
  * Uživatelské skupiny
  * Omezení návrhu a implementace
* Požadavky na rozhraní
  * Uživatelská rozhraní
  * Softwarová rozhraní
* Vlastnosti systému
  1. Autentikace
    * Důležitost: 1
    * Vstup : jméno a heslo. Jméno přidělené administrátorem, heslo min 6 znaků
    * Akce : odeslání jména a hesla na server tlačítkem Přihlásit
    * Výstup : přihlášený uživatel s oprávněním pro editaci záznamů
    * Výstup : chybové hlášení při nesprávných přihlašovacích údajích
  1. ... další vlastnosti
  1. ...
  1. ...
* Nefunkční požadavky
  * Odezva
    * Systém bude poskytovat odezvu do 2s od zadání akce
  * Spolehlivost
    * Systém neskončí s chybou ve více než 1% případů
  * Bezpečnost
    * Systém nedovoví přihlášení neautorizovaným uživatelům
    * Systém nebude ukládat hesla v otevřeném formátu (budou hashovaná SHA256)
  * Dokumentace
    * Příručka administrátora - manuál pro instalaci a zálohování systému
    * Uživatelská příručka - základní manuál pro běžného uživatele
    * Atd...
