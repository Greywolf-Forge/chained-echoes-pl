# Changelog

Pełne notatki każdej wersji, zakres tłumaczenia i sumy SHA-256 paczek są w
[GitHub Releases](https://github.com/Greywolf-Forge/chained-echoes-pl/releases).

## Unreleased

- Repozytorium przeniesiono do organizacji
  [Greywolf Forge](https://github.com/Greywolf-Forge); linki i domyślny cel
  publikacji wskazują teraz `Greywolf-Forge/chained-echoes-pl`.

## 0.9.1 — 2026-08-29

- Aktualne wydanie dla Windows x64 i Kubuntu/Linux x64 (Steam build `21147362`).
- Dialogi: pełny zakres EF-001R (1807 checkpointów, 17846 pól); BGDatabase:
  5712 pól; polskie fonty i skumulowany katalog Addressables.

## 0.8.x — 2026-08-16

- 0.8.0: pierwszy kandydat z pełnym zakresem dialogów EF-001R.
- 0.8.1–0.8.2: ręcznie wklejane ścieżki Windows akceptują spacje i cudzysłowy;
  instalator sprawdza wszystkie biblioteki Steam i czyta katalog gry z manifestu
  App 1229240.
- 0.8.3: natywny podział `Chained Echoes_Data` (Windows) i
  `Chained_Echoes_Data` (Linux) przy instalacji, weryfikacji i rollbacku;
  osobny zestaw 7 payloadów na platformę.

## 0.4.0-rc.1 — 2026-08-05

- Opublikowano wspólne instalatory Windows x64 i Kubuntu/Linux x64.
- Zaktualizowano BGDatabase do 5712 zaakceptowanych pól.
- Rozszerzono dialogi rozmów 165–195 i dodano zatwierdzone etykiety aktorów DLC.
- Zachowano polskie fonty oraz skumulowany katalog Addressables.
- Powiązano wydanie z siedmioplikowym RC ND-7, preflightem 9/9 i podwójnym
  byte-identical buildem.

## Wcześniej

- Utworzono publiczne repozytorium dystrybucyjne.
- Dodano instrukcje instalacji, wsparcia i publikowania kolejnych wydań.
- Dodano wspólny manifestowy instalator Windows x64 i Kubuntu/Linux x64.
- Dodano jedno polecenie budujące, testujące i opcjonalnie publikujące oba ZIP-y.
- Poprawiono Windows: instalator przyjmuje katalog gry, plik EXE lub
  `Chained_Echoes_Data` i wykrywa oba spotykane layouty Addressables.
