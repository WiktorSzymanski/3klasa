# Lekcja n - Wzorce

    ^        początek wzorca
    $        koniec wzorca
    .        dowolny pojecyńczy znak
    [...]    dowolny z wymienionych znaków;w nawiasach można podać kolejne znaki lub wpisać zakres
    [^...]   dowolny z niewymienionych znaków
    |        jeden z ciągów rozdzielonych znakiem
    {3}      dokładnie trzy poprzedzające znaki lub elementy
    {3, }    co najmniej trzy poprzezedzające znaki lub elementy
    {2,5}    od 2 do 5 poprzedzających znaków lub elementów
    \.       znak kropki


## Klasy znaków
Klasami znaków określa się jakie znaki są dozwolone

\s          znak spacji, tabulacji lub nowego wiersza
\S          znak nie jest spacją, znakiem tabulacji lub znakiem nowego wirsza
\w          każdy znak, który jest literą, cyfrą i znakiem
\W          każdy znak, który nie jest literą, cyfrą i znakiem
\d          każdy znak, który jest cyfrą
\D          każdy znak, który nie jest cyfrą