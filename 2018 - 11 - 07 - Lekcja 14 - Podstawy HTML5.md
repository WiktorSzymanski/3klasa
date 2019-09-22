# Lekcja 14 - Podstawy HTML5

2008r - Pierwsza wersja HTML5
2014r - W3C udziela rekomandacji HTML5
2017r - HTML5.2

## Wprowadzenie
- HTML5 jako rozwinięcie HTML4 i XHTML
- Kompatybilny z poprzednimi wersjami języka HTML
- Pojawiają się nowe znaczniki, typy wejść i nowe atrybuty elementów formularzy
- Obsługa wideo i dźwięku
- Starsze przeglądarki bez problemu mogą ignorować nowe polecenia
- Wielkość liter w znacznikach i atrybutach nie ma znaczenia
- Domykanie wszystkich znaczników nie jest konieczne
- Nie ma elementów i znaczników deprecjonowanych, jednak niektóre elementy są klasyfikowane jako przestarzałe
- <!doctype html> - skrócone DPD
- Dołączanie arkusza stylów nie wymaga atrybutu type

<link rel="stylesheet" href="style.css">

- Deklaracja JavaScrypt nie wymaga atrybutu type

<script src="plik.js"></script>

- Znacznik <basefont> nie jest obsługiwany

## Znaczniki semantyczne

        - <article>
        - <aside> - jest to znacznik który powstał z myślą o reklamach, najnowszych artykółach, w skórcie panel boczny
        - <details>
        - <figcaption> - podpis do <figure>
        - <figure> - można umieszczać wszelkeigo roczadju zdjęcia lub odwołania do niech, które mogą się znaleźć na stronie
        - <footer>
        - <header>
        - <main>
        - <mark> - pozwala na zakreślenie, pokolorowanie tekstu, który się w nim znajduje
        - <nav>
        - <section>
        - <summary>

        +---------------------+
        |       <header>      |
        |---------------------|
        |        <nav>        |
        |---------------------|
        | <section> |         |
        |-----------| <aside> |
        | <article> |         |
        |---------------------|
        |       <footer>      |
        +---------------------+

        <wbr> - alternatywa do znaków specjalnych, do dzielenia tekstu
        <iframe src="link"> - pozwala na podłączanie elementów audio-wizualnych np. filmmik z yt
        <bdi> - określa z której storny czyta się dany tekst 
