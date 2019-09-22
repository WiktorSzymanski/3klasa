# Lekcja - JavaScript

## Podstawowe informacje o JavaScript

- język skryptowy
- nie wymaga kompilowania przed uruchomieniem
- wykonany prez program zwany interpretorem/parserem
- parser jest wbudowany w większości przeglądarek

### Dodawanie JS do strony www

<scritp type="text/jaavascript" language="JavaScript 1.5">
    alert(12>6)
</script>
lub
<script>
    alert(12>6)
</script>

### Podłączanie zewnętrznego pliku

Zalecany sposób:

<script type="text/javascript" src="plik.js"></script>
    lub
<script src="plik.js"></script>

### Położenie 
Scipty osadzamy na headzie lub na końcu sektora body

### Bezpieczewństwo JavaScrpit

- JavaScript nie zawiera żadnych mechanizmów bezpieczeństwa
- Każdy skrypt ma takie same prawa - każdy może uzyskać dostęp do innego skryptu i zmodyfikować jego zmienne i funkcje
- Skrypt może nadpisać nawet natywne (wbudowane) funkcje JavaScriptu.

### Dlaczego używać JS?

 - uruchamiany po stronie klienta
 - ograniczony czas wykonywania strony (strona nie jest wysyłana na serwer i odsyłana do klienta po przetworzeniu)

 ## Zmienne JS

 ### Zmienna:
 - Smboliczna nazwa dla wartości w aplikacji
 - Musi zaczynać się literą, podkreśleniem lub znakiem $
 - Rozróżniana jest wielkoć znaków
 liczba != Liczba
 ### Deklaracja zmiennych
 Zmienną można deklarować na 2 sposoby:
 - **Zmienne lokalne** - za pomocą słowa klucz var.
    np.
    var liczba = 10;
    var nazwisko = "Kowaslki";
 - **Zmienne globalne** - za pomocą prostego przypisania wartości
    np.
    liczba = 10;
    nazwisko = "Kowalski"

### Typy danych
- Typ liczbowy
- Typ łańcuchowy
- Typ logiczny
- Typ specjalny

#### Typ liczbowy
- Służy do reprezentacji liczby
- liczby zapisywane są za pomocą literałów liczbowych, czyli ciągów znaków skłądających się na liczbę

#### Typ łańcuchowy
- służy do reprezentacji ciągów znaków (napisów)
- powinien być ujęty w znaki cudzysłowu, aczkolwiek dopuszczalne jest również wykorzystywanie znaków apostrofu
    np. var napis = "Witaj świecie!"
Ciągi mogą też zawierać ponieższe znaki specjalne
- \b - backspace
- \n - nowa linia
- \r - powrót karetki
- \f - nowa strona

#### Typ logiczny
- pozwala na określanie dwóch wartości logicznych: prawda i fausz
- Wartość tego typu są wykorzystywane przy konstrukcji funkcji logicznych

#### Typ specjalnu 
2 wartości:
- null - wartość pusta
- undefinded - niezdefiniowana

### Zmienne a typu danych
- zmienne mogą zmieniać swój typ w trakcie działania programu

var mojaZmienna = "12345"
mojaZmienna = mojaZmienna - 345
wynik = "12000"

var mojaZmienna = "12345"
mojaZmienna = mojaZmienna +678
wynik = "12345678"

**Bo + to też znak konkatenacji (łączenia ciągów znaków)**

### Pętla While

i = 0;

while(i<5)
{
    document.write(i+"br/");
    i++;
}

### Pętla do ... while

Przykład:

i = 0
do {

}

### Pętla for

### Instrukcja switch

switch(wyrażenie){
    case wartość1:
        instrukcja1;
        break;
    case wartość2:
        instrukcja2;
        break;
    default: instrukcja;
}

### Funkcje predefiniowane

Javascript zawiera kilka predefiniowanych fuynkcji o zasięgu globalnym:
    - eval
    - isNaN
    - parselnt oraz paeseFloat
    - Number i String

Funkcja eval - pokazuje łańcuch znaków do kompilatora i wykonuje rezultat

eval(wyrażenie);

np. eval("x=10;y=20;document.write(x*y)");
    document.write("<br>" + eval("2+2"));
    document.write("<br>" + eval("x+2"));

    wynikami będą kolejno:

    200
    4
    27

Funkcja isNaN - sprawdza czy wartość jest leczbą.

isNaN(wartość);

Zwraca true jeśli przekazana wartość nie jest liczbą

### Funkcje parseInt i parseFloat

Funkcje konwertujące łańcuch znaków na liczby całkowite i zmienno przecinkowe.

    parseFloat(str);
    parseInt(str [,base]);

parseFloat - przykłady

    document.write(parseFloat("10"));
    document.write(parseFloat("10.33")); - tylko 10
    document.write(parseFloat("34 45 66")); - spacja przerywa wypisywanie
    document.write(parseFloat(" 60 ")); - spacje są ignorowane
    document.write(parseFloat("40 lat"));
    document.write(parseFloat("On ma 40 lat")); - NaN
    document.write(parseFloat("10", 10)); - tylko 10
    document.write(parseFloat("010")); - jeśli 0 pierwsze w ciągu to system ósemkowy
    document.write(parseFloat("10", 8)); - 8
    document.write(parseFloat("0x10")); - szestnastkowy
    document.write(parseFloat("10", 16)); - baza 16

### Funkcja Number i String

Funkcje pozwalające na konwersję obiektu do liczby lub łańcuchu znaków
    
    var obiekt
    obiekt = Number(obiekt)
    obiekt = String(obiekt)

Ćwiczenie 1

    Napisz funkcję, której 2 pierwsze argumenty będą operandami, a trzeci argument będzie oznaczał rodzaj działania. W zależności od rodzaju działania funkcja powinna zwracać sumę, różnicę, iloraz lub iloczyn dwóch pierwszych argumentów.
    