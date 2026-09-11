# IMPULS Dotacje Marta 4.2.3 — kandydat do odbioru (RC)

Instalator Windows 64-bit. Pobierz **IMPULS-Dotacje-Marta-4.2.3-Setup.exe** z plików wydania (Assets). Nie pobieraj „Source code” — to archiwum tego repozytorium dystrybucyjnego, nie instalator.

## Pierwsze uruchomienie

1. Pobierz EXE i przeczytaj CZYTAJ-NAJPIERW.txt.
2. Przed aktualizacją zachowaj kopię całego folderu danych przy zamkniętej aplikacji. Kopia JSON bazy nie zawiera wszystkich plików, rozmów i zadań.
3. Uruchom instalator, a następnie Impuls Dotacje Marta. Nie potrzebujesz Node.js ani terminala.
4. Wybierz klienta i sprawę, dodaj dokumenty, sprawdź ich role oraz źródła.
5. Korzystaj z widoków eksperckich i Pomocy AI. Pełny agent chmurowy wymaga konfiguracji administratora w „Ustawienia i kopie”: własny klucz API, dostępny model, zgoda i budżet. Klucza nie ma w instalatorze.
6. Sprawdź „Potrzebuję od Ciebie”, zapisane wyniki i „Sprawdź przed złożeniem”. Pakiet częściowy nie jest gotowy do złożenia.

Do otwierania DOCX/XLSX potrzebny jest osobny zgodny program biurowy.

## Uczciwy status

- Instalator: BUILT; integralność i zgodność zapakowanego kodu sprawdzone.
- Pełne regresje offline, read-back DOCX/XLSX, migracja/restart oraz testy spakowanej aplikacji Linux: PASS.
- Natywna instalacja/aktualizacja/uruchomienie na Windows: NOT RUN.
- Rzeczywisty model API: BLOCKED na brak autoryzacji/klucza/budżetu; testy kontrolowane nie stanowią LIVE PASS.
- Odbiór Marty/właściciela: NOT RUN.
- Pakiet nie ma podpisu cyfrowego. Nie omijaj ostrzeżeń systemowych; administrator powinien zweryfikować pochodzenie i sumę pliku.
- To RC, nie potwierdzone wydanie finalne. Zalecany pierwszy odbiór na odrębnym profilu i syntetycznych dokumentach.

Obsługiwane nabory i analizy mają określony zakres. Nie ma pełnego OCR, wszystkich kalkulatorów Studium ani automatycznego podpisu, złożenia lub wysyłki. Samo NPV nie oznacza kompletnego Studium.

## Integralność

Wersja: 4.2.3
Zweryfikowany commit kodu aplikacji: d5bfe62f9c1100dddc1d9305674b56d491da4429
Rozmiar EXE: 502171720 bajtów
SHA-256 EXE: e7d75c548cdb97be09dec3e2db42766fcd7fae1980809e00b65bd60a73660552
SHA-256 app.asar: 136acc4597e08f3832c3796c0517f88d200450757b4742ed234dbc215b3851fd

To osobne repozytorium dystrybucyjne. Jego tag i archiwum „Source code” obejmują jedynie dokumentację dystrybucji, nie kod aplikacji. Publikacja instalatora nie zmienia widoczności repozytorium źródłowego ani nie zawiera baz klientów lub wspólnego klucza API.
