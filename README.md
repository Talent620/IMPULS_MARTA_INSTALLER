# IMPULS Dotacje Marta — wydanie testowe RC5

**To kandydat do testów, nie potwierdzony produkt gotowy do obsługi każdej sprawy. LIVE AI pozostaje BLOCKED — potrzebne jest własne logowanie.** Testy z przygotowanymi odpowiedziami nie dowodzą jakości modelu.

- [Pobierz instalator Windows 5.0.0-rc.5](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/download/test-v5.0.0-rc.5/IMPULS-Dotacje-Marta-5.0.0-rc.5-Setup.exe)
- [Instrukcja Marty — PDF](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/download/test-v5.0.0-rc.5/MARTA-Instrukcja-RC5.pdf)
- [Wydanie, raport i dowody testów](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/tag/test-v5.0.0-rc.5)

Nie pobieraj „Source code” jako instalatora — to archiwum repozytorium dystrybucyjnego. Wydanie RC5 jest celowo pomijane przez updater RC4/RC5; dostępne wyłącznie z ręcznego linku. Nie jest rozsyłane do kanału stabilnego.

## Początek pracy

1. Przed aktualizacją wykonaj pełną zaszyfrowaną kopię w programie. Kopia samego JSON nie zawiera wszystkich załączników.
2. Zainstaluj EXE i otwórz Marta AI. Zachowano tożsamość aplikacji oraz katalog danych.
3. W „Silnik i zgody” wybierz Codex i własne konto ChatGPT albo własne API. Oficjalny Codex CLI wymaga osobnej instalacji według instrukcji; nie korzystaj z cudzego konta.
4. Pobierz katalog modeli, zapisz wybór i zgodę, wykonaj test odpowiedzi i procedury. Katalog nie jest testem połączenia.
5. Wybierz sprawę i nabór, dodaj dokumenty, sprawdź ich role i źródła. Rozmawiaj w głównym czacie i kontroluj zapisane wyniki.

API jest płatne osobno i wymaga limitu. ChatGPT podlega limitom własnego konta; program nie przełączy się automatycznie na płatne API. Nieznane zużycie nie jest przedstawiane jako zero. W instalatorze nie ma konta ani klucza. Roboczy dokument i zakończone zadanie nie oznaczają gotowości do złożenia.

## Potwierdzone i niepotwierdzone

- Pełna regresja offline, dodatkowe 64 testy, spakowana aplikacja i dokumenty: PASS w określonych scenariuszach kontrolowanych.
- Windows Server 2025 build 26100: PASS — instalacja, aktualizacja RC4, restart, ConPTY, OCR, DOCX/XLSX i dwie syntetyczne sprawy. Nie jest to test komputera Marty ani wszystkich Windows 10/11.
- Prawdziwy model w głównym czacie: BLOCKED. Rzeczywista sprawa klienta: UNVERIFIED.
- `Get-AuthenticodeSignature`: **NotSigned**. Brak zaufanego podpisu wydawcy; sprawdź źródło i hash pliku. Nie traktuj komunikatu buildu „signing” jako podpisu.
- npm audit: 0 produkcyjnych, 8 high w narzędziach budowania; zakres opisano w raporcie.

## Integralność instalatora

Wersja: 5.0.0-rc.5. Źródłowy commit produktu: `d1a63140f00a4b620a157066ebabcdab75ade03b`.
Rozmiar: 242566996 bajtów.
SHA-256: `0ab328c0d9ec5a4032b4368c9cdba9dd33904fe2649c16ba20ad3bf224c7ae82`.

Publikowane dowody zawierają wyłącznie fikcyjne dane. Repozytorium nie zawiera rzeczywistych dokumentów klientów, prywatnych kopii danych ani poświadczeń.
