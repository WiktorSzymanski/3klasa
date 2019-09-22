# Lekcja 12 - Modele barw


## Niezależne
- CIE XYZ
- CIE Lab

## Kojarzone z użytkownikiem
- HLS
- HSV

## Kojarzone ze sprzętem
- RGB
- CMY, CMYK


### RGB

<img src="RGB.jpg">

Modele bezpośrednie wywodzące się z teorii trójobudzenia
R – czerwony
G – zielony
B – niebieski

Model najbliższy wartościom sprzęu elektronicznego 
- Pierwsze kolorowe monitory zawierały elementy świecące w trzech kolorach.
- Odpowiednio sterując natężeniem światła tych składowych uzyskiwano różne kolory, czyli dokłądnie pierwsze kineskopy posiadały trzy rodzaje litoformu – emanujące światłem.

### CMY

Zbudowany jest analogicznie do RGB. Podstawowymi współrzędnymi w modelu kolorów najlepiej nadającym się do opisu procesu druku są kolory będące dopełnieniami współrzędnych RGB

R – GB
G – RB
B – RG 

Cyan, Magenta, Yellow, 
Wszystkie kolory opisane przez model CMYK to te same kolory, co opisywane przez model RGB
Jest, więc to ten sam sześcian RGB, tylko widziany od przeciwległego wierzchołka. Współrzędne (0,0,0) to kolor biały, a czarny to (255,255,255). 

### CMYK

<img src="CMYK.jpg">

Rozwinięcie CMY. Spowodowane przez problemy techniczne dodano pojemnik z czarnym kolorek przez co CMYK.

### HSL - Hue Saturation Lightness

<img src="HLS.jpg">

- Hue – (z ang. odcień, barwa), o wartościach z przedziału: od 0 do 360 stopni.
- Saturation – nasycenie koloru. z przedziału 0...1 albo 0...100%.
- Lightness – średnie światło białe, z przedziału 0...1 albo 0...100%.

### HSV - Hue Saturation Value

<img src="HSV.jpg">

- Podchodzi w parametry fali świetlnej
- Value - natężenie światła

### CIE XYZ

<img src="CIE XYZ.jpg">

- Opracowany w 1931 przez Międzynarodową Komisję Oświetlenia CIE
- Model próbuje ogólnie opisać kolor
- Standart składasię z trzech składowych i żadna z nich nie może być powiązana z jakąkolwiek barwą
- Model XYZ opisuje możliwości odwzorowania kolorów przez poszczególne urządzenia
- Przestrzeń barw opisany współrzędnymi będzie inna dla drukarki atramentowej, dla wyświetlaczy LCD, dla wyświetlacza telefonu komurkowego - ponieważ każde urządzenie potrafi wyświetlać inny podzbiór kolorów

### CIE Lab

<img src="CIE Lab.png">

- Model przygotowany przez CIE w 1976 roku
- Stworzony napodstawie teorii o odbieraniu przez człowieka barw jako trzy sygnały
    - jasność
    - stosunek czerwieni do zieleni
    - stosunek błękitu do żółci