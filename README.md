# PD12M Image Annotations

Projekt przedstawia ręcznie przygotowane anotacje dla 10 wybranych obrazów
z datasetu PD12M.

## Cel projektu

Celem było przygotowanie szczegółowych opisów obrazów w języku polskim
i angielskim, które mogą być wykorzystane w pracy z modelami
Vision-Language (VLM).

Anotacje zostały przygotowane ręcznie, z naciskiem na dokładność,
szczegółowość oraz ograniczenie halucynacji.

## Dataset

Źródło obrazów:

Spawning/PD12M  
Hugging Face

https://huggingface.co/datasets/Spawning/PD12M

Do projektu wybrano 10 przykładowych obrazów z datasetu.

## Metoda anotacji

Sposób przygotowania opisów został zainspirowany podejściem przedstawionym
w pracy:

**ImageInWords: Unlocking Hyper-Detailed Image Descriptions**

Dla każdego obrazu przygotowano:

- `object_annotations` – szczegółowe opisy najważniejszych obiektów,
- `global_description` – szczegółowy opis całej sceny,
- wersję polską (`pl`),
- wersję angielską (`en`).

Podczas anotacji uwzględniano m.in.:

- wygląd i cechy obiektów,
- położenie obiektów,
- relacje przestrzenne,
- działania i interakcje,
- pierwszy plan, tło i perspektywę,
- kolory, światło i ostrość,
- czytelny tekst znajdujący się na obrazie.

Nie dodawano informacji, których nie można było wiarygodnie określić
na podstawie obrazu.

## Struktura anotacji

Przykładowa struktura JSON:

```json
{
  "image": "image_01.jpeg",
  "pl": {
    "object_annotations": [
      {
        "object": "...",
        "description": "..."
      }
    ],
    "global_description": "..."
  },
  "en": {
    "object_annotations": [
      {
        "object": "...",
        "description": "..."
      }
    ],
    "global_description": "..."
  }
}