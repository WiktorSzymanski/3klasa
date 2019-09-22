# Lekcja 5 - Kaskadowe Arkusze Stylów

Język, który poznala na oddzielne treści storny, umieszczanej w plikach *.html, od sposobu ich prezentacji *.css

W przypadku występowania różnych arkuszy stylów na jednej stronie stopień ich ważności roście w następującej kolejności

- 4 Domyśle ustawienia przeglądarki
- 3 Zewnętrzny arkusz stylów
- 2 Osadzony arkusz styów
- 1 Styl wpisany (inaczej liniowy)

Reguła CSS
- selektor {właściwość: wartość;}
{...} - deklaracja

np. selektor1, selektor2 {właściwość1: wartość1; właściwość2: wartość2;}

<span style="color:blue;background-color:yellow">niebieski tekst na żółtym tle</span>

##styl osadzony
<html>
<head>
<style type="text/css">
body {background-color: red;}
p {color:#FFFF00;font size:14pt;}
</head>
<body>
</body>
</html>
