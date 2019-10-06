# Lekcja 1 - Jak komputer wykonuje program?

**Program** - komputerowy to ciąg symboli tworzących instrukcje, opisujących realizowane oliczenia zgodne z przyjętymi regółami, związanymi językiem programowania.

**Aplikacja** - to program lub zbiór programów realizujących określone działania (np. MS Office Word)

**Język wysokiego poziomu**

    - Abstrakcyjne (np, języki obiektowe)
    - Niezależne od architektóry
    - Łatwe do zrozumienia przez człowieka

**Języki niskiego poziomu**

    - Ściśle związane z bierzącą architektórą
    - Trudne do zrozumienia przez człowieka

**Translator** - to program komputerowy, który przekształca kod w pewnym określonym języku programowania na kod w innym języku programowania (zwykle tego samego lub wyższego poziomu). Proces takiego przekształcenia nazywamy **translacją**.

**Kompilator** - to program komputerowy, który przekształca kod w pewnym określonym języku programowania wyższego poziomu na kod w języku programowania niższego poziomu. Proces takiego przekształcenia nazywamy **kompilacją**. W szczególności, kompilator może przekształcić kod w danym języku programowania na kod w języku maszynowym.

Każdy język programowania, dla którego istnieje kompilator, nazywamy **językiem kompilowalnym**.

**Przykłady języków kompilowalnych**: Pascal (Delphi),C,C++,C#,Java,język assemblera.

**Assembler** to kompilator, który przekształca kod w języku assemblera na kod w języku maszynowym. Proces takiego przekształcania nazywamy **assemblacją**.

**Kompilacją** nazywamy również ciąg procesów przekształcających kod 
źródłowy w plik wykonywalny, gotowy do uruchomienia na maszynie.

Standardowy proces kompilacji składa się z czkrech kroków: 

**Krok l** (prekompilacja). Pliki z kodem źródłowym przygotowywane są do etapu kompilacji.

**Krok 2** (kompilacja). Pliki z kodem żródłowym są kompilowane do języka 
assemblera.

**Krok 3** (assemblacja). Pliki z kodem źródłowym w języku assemblera 
przetwarzane są na język maszynowy.

**Krok 4** (linkowanie). Program zwany linkerem łączy wszystkie pliki w 
jeden plik wykonywaŁny.

**Interpreter** to program komputerowy, który analizuje, interpretuje i natychmiast wykonuje kod w pewnym określonym języku programowania.

Proces ten nazywamy **interpretacją**.

Każdy język programowania, dla którego istnieje interpreter, nazywamy **językiem interpretowanym** (skryptowym). Źródło zawierające kod w języku interpretowalnym nazywamy skryptem.

**Przykłady języków interpretowalnych**: Python, JavaScript, Ruby, Bash, PHP.

**Debugger** to program komputerowy służący do dynamicznej analizy działania innych programów. Analiza ta, obejmująca obserwację wykonywanych instrukcji i zawartości zmiennych, pozwala zidentyfikować błędy występujące w badanym programie.

**Aplet** to program komputerowy osadzony na stronie internetowej, uruchamiający (np. aplet uruchamiany w wirtualnym środowisku Javy) lub interpretowany (np. kod w języka JavaScript) przez przeglądarkę internetową.

## Zadanie Domowe

    - Opisz cykl życia aplikacji

Etap 1. Analiza i projektowanie

- zamawiający oprogramowanie i wykonujący je uzgadniają szczegóły dotyczące wspólnych celów
- ustalone zostają wykorzystane technologie
- powstanie specyfikacji funkcjonalnej

Etap 2. Implementacja

- realizacja funkcjonalności w procesie programowania
- budowa wykorzystwanych baz danych
- debuggowanie powstałego kodu

Etap 3. Testowanie i weryfikacja

- testowanie może się odbywać fragmentami
- sprawdzanie zgodności z dokumentacją projektową (weryfikacja) i prawidłowości działania

Etap 4. Dokumentacja

- dokumentacja projektu - zawiera opis projektu, wymogi, np. kontrakt, specyfikacja funkcjonalna i/lub harmonogram płac
- dokumentacja programistyczna - opisuje ona zasady działania utworzonego kodu
- dokumentacja użytkownika - opisuje zasady użytkowania aplikacji

Etap 5. Wdrożenie

- instalacja aplikacji w środowisku produkcyjnym (uruchomieniowym)
- migracja danych ze starych aplikacji
- szkolenie użytkowników

Etap 6. Wsparcie i utrzymanie

- naprawa błędów niewykrytych w czasie testów
- wsparcie użytkownika
- aktualizacja oprogramowania (np. dostosowanie do zmian w prawie)
