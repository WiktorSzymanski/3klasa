# Lekcja 7

## Identyfikatory klasy stylów

Identyfiaktor o danej nazwie może zostać użyty tylko raz w kodzie.
Identyfikatory będą służyć to pozycjonowania bloków.
<p id="one">Tekst opisany identyfikatorem</p>

Klasy - raz zdeklarowaną można wykorzystać wielokrotnie, wygodniejszy.
.one { color:blue;}

Klasa uniwersalna - można stosować do wszystkich znaczników, powstaje, gdy pocdczas definiowania klasy pomijamy nazwę selektora
p.one { color:blue;}

Tworząc nazwy albo identyfikatorów należy pamiętać o:
-musi rozpoczynać się od litery,
-może zawierać duże i małe litery, cyfry, dywizy (-), podkreślenia, dwukropki i kropki,
-litery duże i małe są rozróżniane.

## Właściwość position

Pozycjonowanie odpowaida za umieszczanie elementu w dowolnie wybramym miejscu przez zastosowanie właściwości

**Pozycjonowanie bezwzględne** - nazywane również absolutnym, pozwala na ustalenie położenia elementu w stosunku do ram okna przeglądarki lub innego elementu nadrzędnego.

PRZYKŁAD: chcemy pozycjonować obrazek tło.png:
- Należy nadać mu nazwę klasy lub identyfikatora
- Odpowiedznie formatowanie w kaskadoowych arkuszach stylów
<img src="tło.png" id="obrazek_tła">

#obrazek_tła
{
    position: absolute;
    left: 80px;
    top: 40px;
}