# IMPULS Dotacje Marta — wydanie testowe RC6

**To kandydat do testów, nie potwierdzony produkt gotowy do obsługi każdej sprawy. LIVE AI pozostaje BLOCKED — potrzebne jest własne logowanie.** Testy z przygotowanymi odpowiedziami nie dowodzą jakości modelu.

- [Pobierz instalator Windows 5.0.0-rc.6](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/download/test-v5.0.0-rc.6/IMPULS-Dotacje-Marta-5.0.0-rc.6-Setup.exe)
- [Instrukcja Marty — PDF](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/download/test-v5.0.0-rc.6/MARTA-Instrukcja-RC6.pdf)
- [Wydanie, raport i dowody testów](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/tag/test-v5.0.0-rc.6)

Nie pobieraj „Source code” jako instalatora — to archiwum repozytorium dystrybucyjnego. Wydanie RC6 jest celowo pomijane przez updater RC4/RC6; dostępne wyłącznie z ręcznego linku. Nie jest rozsyłane do kanału stabilnego.

## Początek pracy

1. Przed aktualizacją wykonaj pełną zaszyfrowaną kopię w programie. Kopia samego JSON nie zawiera wszystkich załączników.
2. Zainstaluj EXE i otwórz Marta AI. Zachowano tożsamość aplikacji oraz katalog danych.
3. W „Silnik i zgody” wybierz Codex i własne konto ChatGPT albo własne API. Oficjalny Codex CLI wymaga osobnej instalacji według instrukcji; nie korzystaj z cudzego konta.
4. Pobierz katalog modeli, zapisz wybór i zgodę, wykonaj test odpowiedzi i procedury. Katalog nie jest testem połączenia.
5. Wybierz sprawę i nabór, dodaj dokumenty, sprawdź ich role i źródła. Rozmawiaj w głównym czacie i kontroluj zapisane wyniki.

API jest płatne osobno i wymaga limitu. ChatGPT podlega limitom własnego konta; program nie przełączy się automatycznie na płatne API. Nieznane zużycie nie jest przedstawiane jako zero. W instalatorze nie ma konta ani klucza. Roboczy dokument i zakończone zadanie nie oznaczają gotowości do złożenia.

## Potwierdzone i niepotwierdzone

- Pełna regresja offline, dodatkowe 65 testów, spakowana aplikacja i dokumenty: PASS w określonych scenariuszach kontrolowanych.
- Windows Server 2025 build 26100: PASS — instalacja, aktualizacja RC4, restart, ConPTY, OCR, DOCX/XLSX i dwie syntetyczne sprawy. Nie jest to test komputera Marty ani wszystkich Windows 10/11.
- Prawdziwy model w głównym czacie: BLOCKED. Rzeczywista sprawa klienta: UNVERIFIED.
- `Get-AuthenticodeSignature`: **NotSigned**. Brak zaufanego podpisu wydawcy; sprawdź źródło i hash pliku. Nie traktuj komunikatu buildu „signing” jako podpisu.
- npm audit: 0 produkcyjnych, 8 high w narzędziach budowania; zakres opisano w raporcie.

## Integralność instalatora

Wersja: 5.0.0-rc.6. Źródłowy commit produktu: `8672ecc44b601266e7ecb068a2b93823a81baff6`.
Rozmiar: 242567180 bajtów.
SHA-256: `bb1608bdc1614b771ada606bf714d5aae91355a8b9c73cac0439605f55ea62e9`.

Publikowane dowody zawierają wyłącznie fikcyjne dane. Repozytorium nie zawiera rzeczywistych dokumentów klientów, prywatnych kopii danych ani poświadczeń.
