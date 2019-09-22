# Lekcja nn+1 - Zdarzenia

## Obiekt window
- główny domyślny obiekt w DOM
- reprezentuje okno lub zakładkę w przeglądarce
- zmienne globalne w JavaScript są właściwościami tego obiektu

### Przykładowe
- alert(treść) - wyświetla komunikat zawarty w argumencie treść 
- confirm(treść) - wyświetla komunikat zawarty w argumencie treść oraz

## Obiekt document
Zawiera dokument html wczytany do przeglądarki pozwala na dostęp i manipulacje praktyczne każdym elementem strony

### Podstawowe metody obiektu document
- write(tekst)
- getElementById(id)
- getElementByName(nazwa)
- getElementByTagName(tag)

## Obiekt history
### Właściwości
- current
- lenght
- next
- previous
### Metofy:
- back()
- forward()
- go(paramert)

## Obiekt location
Zawiera adres URL aktualnego dokumentu
Metody:
- assign(url)
- reload(force)
- replace(url) - strona zastąpiona nie zostaje w historii

## Bezpośrednia manipulacja węzłami dokumentu
każdy element nie będącym tekstem zawiera kolekcję węzłów potomnych (childNodes)
var zmienna = cntent.childNodes[0]
zmienna.nodeValue = "Nowa treść"

### Tworzenie elementów przez skrypt
#### Węzły powiązane z elementami html
var div = document.createElement("div")
#### Węzły tekstowe
var tekst = document.createTextNode("Teść")
#### Łączenie
div.appendChild(tekst);
content.appendChild(div);