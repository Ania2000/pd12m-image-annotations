# Mini Best Practices – anotacja obrazów

Anotacje zostały przygotowane zgodnie z podejściem inspirowanym ImageInWords.

## Najważniejsze zasady

1. **Opisuj tylko to, co jest widoczne**
   - Nie zgaduj tożsamości osób, miejsca, gatunku, marki ani innych informacji, których nie można pewnie określić na podstawie obrazu.

2. **Najpierw obiekty, potem cały obraz**
   - `object_annotations` – opis najważniejszych obiektów.
   - `global_description` – szczegółowy opis całej sceny.

3. **Opisuj cechy obiektów**
   - kolor,
   - kształt,
   - wygląd,
   - położenie,
   - widoczne działanie,
   - relacje z innymi obiektami.

4. **Uwzględniaj przestrzeń**
   - pierwszy plan,
   - środkowy plan,
   - tło,
   - położenie obiektów względem siebie,
   - perspektywę i częściowe zasłonięcie.

5. **Nie halucynuj**
   - Jeśli szczegół jest niepewny, użyj ogólniejszego określenia.
   - Przykład: `owad` zamiast konkretnego gatunku, jeśli gatunku nie można pewnie rozpoznać.

6. **Tekst na obrazie zapisuj tylko wtedy, gdy jest czytelny**
   - Nie zgaduj niewyraźnych napisów.

7. **Nie identyfikuj osób**
   - Opisuj ich wygląd, ubranie, pozycję i widoczne działanie, ale nie ustalaj tożsamości na podstawie zdjęcia.

8. **Unikaj subiektywnych ocen**
   - Zamiast „piękny budynek” opisz jego widoczne cechy.

9. **Opis powinien być szczegółowy, ale bez powtórzeń**
   - Każde zdanie powinno wnosić nową informację.

10. **PL i EN muszą być zgodne**
    - Polska i angielska anotacja powinny przekazywać te same informacje.

## Zasada końcowa

Dobra anotacja jest szczegółowa, konkretna, neutralna i zgodna z tym, co rzeczywiście można zobaczyć na obrazie. Lepiej pominąć niepewną informację niż dodać informację nieprawdziwą.

Literatura

Garg et al., ImageInWords: Unlocking Hyper-Detailed Image Descriptions,
EMNLP 2024.