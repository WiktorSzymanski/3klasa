#Lekcja kolejna - Tablice 

##Tworzenie nazw tablic
-rozpoczyna się od małej lub wielkiej litery, znaku _ lub znaku $,
-nie może zawierać operatorów matematycznych (+-), znaków punktacyjnych (takich jak !, &) albo spacji
-na drugim i dalszych miejscach może zawierać cyfry
-słowa kluczowe języka nie mogą być użyte jako

Dwa sposoby
-przez deklaracje zmiennej w nawiasach kwadratowych
var tablica = ["Janek","Franek","Bronek"];
-przez wywołanie konstruktora tablicy
var tablica = new Array("Janek","Franek","Bronek");

##Przykłady
var tablica = [1,2,3,4,5,6,7,8,9,10]; - 10 elementów
var tablica = [1,"Janek",2,"Franek"]; - 5 elementów
var tablica = ["Janek",,"Franek",,"Bronek"]; - ,, = undefined
var tablica = [] - pusta tablica

var tablica = new Array();
var tablica = new Array(1,2,3,4,5,6,7,8,9,10);
var tablica = new Array(5);

##Tablice asocjacyjne
Tworzenie tablicy asocjacyjnej z wypełenienem danymi
var wyplaty = new Array({'Janek':2000,})

Tablica asocjacyjna przekazuje definicje wartości oddzielane dwukropkiem parę kluczy

##Operacje na tablicach
Tablice są obiektami w JavaScript, zawierającymi kilka predefinionwanych metod umożliwiających m.in:
 - Łączenie tablic (concat)
 - Odwrócenie kolejności elementów (reverse)
 - Pobieranie i usuwanie ostatniego elementu tablicy (pop)
 - Dodawanie elementu na końcu tablicy (push)
 - Pobiera i usuwa pierwszy element (shift)
 - Dodawanie elementu na początku tablicy (unshift)
 - sortowanie (sort)
 - sklejanie (join)