# Lekcja 10 - Uzupełnienie wiadomości CSS

## Czcionki

### Rodziny czcionek:

    - serif - czcionki szeryfowe mające wykończenie liter i cyfr. Do tej grupy należą np. Times New Roman, Georgia, Bodoni.
    - sans-serif - czcionki bezszeryfowe. Końcówki znaków są proste np. Arial, Verdana, Futura.
    - monospace - czcionki monotypiczne, znaki mają stałą szerokość np. Courier New, Courier.
    - cursive - czcionki mające cechy czciąki pochyłej. Znaki wyglądają jak pisane ręcznie np. Comic Sans, Florence.
    - fanatasy - czcionki dekoracyjne np. Impact. OldTown.

### Rozmiar

    - Atrybut font-size
    
        Rozmiar można ustalić na cztery sposoby:
            - Według słów kluczowych
            - za pomocą wartości względnych
            - poprzez wielkość podaną w jednostkach miary
            - poprzez wielkość podaną w procentach

        Słowa kluczowe
        
            - xx-small
            - x-small
            - small
            - medium - podstawowa czcionka
            - large
            - x-large
            - xx-large

        Wartość względna - wielkośc ustalana względem wielkkości czcionki elementu nadrzędnego 
        
        - small
        - large

    - Atrybut font-variant 

        - normal - czcionka normalna
        - small-caps - kapitaliki (duże litery wielkości małych znaków)

    - Atrybut font-weight

        - normal
        - bold
        
        za pomocą wartości względnych

        - lighter
        - bolder

    - Atrybut line-height

        Liczna - jako wielokrotność aktualnego rozmiaru czciąki
        Wysokość - jest podawana z jednostką miary (np. px, cm, itd.) określa stałą wartość odstępu
        Wartośc procentowa - względem wartości elementu nadrzędnego

### Łączenie kodu

Muszą być zadeklarowane w tej kolejności:

- font-style
- font-variant
- font-weight
- font-size
- font-height
- font-family

np. p{font:italic bold 12px /2cm Georgia;}
Wartość dla atrybutów font-size i font-family są wymagane.

## Tekst

### Atrybut text-intend

    - wcięcie tekstu

### Atrybut text-align

### Atrybut text-decoration

    - none
    - underline
    - overline
    - line-through
    - blink

### Atrybut letter-spacing

### Atrybut word-spacing

### Atrybut line-height

    - odstępy między wierszami

### Atrybut text-transform

    - capitalize
    - uppercase
    - lowercase
    - none

### Atrybut white-space
 pozwala na sterowanie wyświetlaniem na stronie spacji i innych białych znaków

    - normal
    - pre
    - nowrap
    - pre-wrap
    - pre-line

## Tło

### Atrybut background-reapeat

Wartości powtarzania:

- repeat - powtarzanie tła w obu kierunkach
- repeat-x
- repeat-y 
- no-repeat

Jeżeli treść naszej strony jest przesuwana przy użyciu suwaka, to wstawiona grafika (tło) przesuwa się także. Aby stało się inaczej tzm. tyło było nie ruchome stosujemuy atrybut: **background-attachment**

- scroll
- fixed
- local

### Atrybut background-position

Wstawiona grafika na stronę umiejscawia się w lewym górnym rogu ekranu. Do zmiany jej ustawień i pozycjonowania grafiki słyży atrybut **background-position**

- center - umieszczona na środku strony
- left - umieszcza z lewej
- right - z prawej
- top - na górze
- bottom - na dole
- jdnostka długości - umieszcza w określonej długości od lewego marginesu

### Atrybut background-color

np.
body {background: #ffff00 url(tło.png) no-repeat fixed right-top;}

## Listy

Większość przeglądarek wyświetla dla list punktowalnych okrągłe punktory, a dla isty numerowanych - cyfry

Za pomocą atrybutu list-style-type można zmienić punktor lub cyfrę

selektor {list-style-type: typ;}

        <ol>
        <ul>
        <li>

### Dostępne Typy

    - Disc
    - Circle
    - Square
    - Decimal
    - Lower-roman
    - Upper-alpha
    - None

### Obraz jako punktor

selektor {list-style-image: url(ścieżka do pliku);}

### Pozycja punktora

selektor {list-type-position: pozycja;}

    inside -punktor pojawi się wewnątrz zawartości
    outside - punktor pojawi się zewnątrz zawartości

### Grupowanie atrybutów listy

    ul {listy-style: square inside;}
    
