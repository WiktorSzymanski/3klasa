# Lekcja 11 - Jednostki miar

## Dopuszczalne rodzaje wartości to:

    - Liczby
        - Całkowite
        - Rzeczywiste
    - Procenty - określana zawsze względem innej wartości, zależy od rozmiaru okna przeglądarki

## Jednostki miary:

    - Absolutne 
        - in = 2.54cm
        - cm
        - mm
        - pt - punkty 1/72in
        - pc - pika 1pc = 12pt
    - Relatywne
        - px - pixele
        - em - wysokość czciąki elementu
        - ex - x height wysokość litery x

## Przeźroczystość

Za pomocą atrybutu **opacity** może definiować przeźroczystość dla emementów wstawianych na stronę

Nieprzeźroczystość to liczba z od 0.0 do 1.0

0 oznacza przeźroczystość

1 oznacza jej brak

Zdefiniowany poziom przeźroczystości jast nadawany wszystkim elementom znajdującym się wewnątrz określonego elementu

## Obcinanie elementu

Do wycięcia z elementu jego fragmentu w kształcie prostokonta służy atrybut 

selektor{position: absolute; clip: rect(góra, prawo,dół,lewo);}

Wartości góra, prawo, dół, lewo są określone względem lewego górnego narożnika, podawane w jednostkach długości

można użyć auto co oznacza pominięcie cięcia 