# Lekcja 9 - Pseudo klasy i selektory

:active - link odwiedzany, storna jest aktualnie załadowana

:link   - link nieaktywny, storna jeszcze nie otwarta                                   - Do odnośników
:visited - link odwiedzony i oznacza, że storna była już otwarta

:hover - czyli kursor zmajduje się nad obiektem, coś jest gotowe od kliknięcia          - można przypisać do każdego wybranego elementu 

**W CSS muszą być w takiej kolejności**

a:link {font-size:20px;
       color:pink;}

a:visited{font-family:Arial;
         color:orange;}

a:hover{background:black;
        color:white;}
        
a:active {text-decoration:none;
         color:navy;}



## Selektory:

- Elementów
        
        - selektory typu np.: p, h1, div
        - selektor universalny (dotyczny całej storny, umieszczamy tam z regóły rodzaj czcionki, wielkość czcionki itd.)
                *{ } - tak w css piszemy
        - selektor potomka np. div p {font-size:23apx;} - potomek leży niżej w hierarchi drzewa dokumentu
        - selektor dziecka leży o jeden rząd niżej w hierarchi drzewa dokumentu np. div > span {color:pink;}
        - selektor brata:
                - bliższego np. p + h1 {color:red;}
                - dalszego np. p ~ h2 {color:blue;}
        
- Atrybutów

        - odnosi się do konkretnego atrybutu np. <p [align]>

- Pseudo klas
- Pseudo elementów
- Specjalne

        - selektor klasy
        - selektor identyfikatora