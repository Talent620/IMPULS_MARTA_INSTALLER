# IMPULS Dotacje Marta — wersja testowa RC7

Nowy sposób pracy: **pliki → przygotowanie sprawy w czacie → decyzje → dokumenty do kontroli**.

**LIVE AI pozostaje niepotwierdzone.** Kontrolowane odpowiedzi w testach nie są dowodem jakości prawdziwego modelu. Własne konto, model i zgoda wymagają konfiguracji.

- [Instalator Windows RC7](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/download/test-v5.0.0-rc.7/IMPULS-Dotacje-Marta-5.0.0-rc.7-Setup.exe)
- [Instrukcja dla Marty — PDF](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/download/test-v5.0.0-rc.7/MARTA-Instrukcja-RC7.pdf)
- [Raport i dowody testów przy wydaniu](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/tag/test-v5.0.0-rc.7)

## Jak zacząć

1. Przed aktualizacją wykonaj pełną zaszyfrowaną kopię w aplikacji.
2. Zainstaluj EXE i otwórz **MARTA AI**.
3. Wybierz sprawę albo **Rozpocznij z plików**. Sam import nie wywołuje AI.
4. W **Ustawieniach AI** wybierz Codex, własny sposób dostępu, model i autonomię. Oficjalny Codex CLI wymaga osobnej instalacji. Wykonaj test odpowiedzi i procedury.
5. Dodaj materiały, sprawdź ich role i kliknij **Przygotuj całą sprawę**. Możesz wcześniej dopisać wskazówki w polu rozmowy.
6. Odpowiadaj na rzeczywiste braki, zatwierdzaj ważne decyzje i sprawdzaj zapisane wyniki.

Program korzysta z jednej bazy i rozmowy. Nie podpisuje ani nie wysyła wniosku. Zapisany plik nie oznacza zatwierdzenia. API jest płatne osobno, ChatGPT podlega limitom własnego konta; nie ma automatycznego przejścia na płatne API.

## Zakres potwierdzenia

- Kontrolowane testy i nowy przycisk w spakowanym głównym czacie Linux/Windows: PASS.
- Dodatkowe testy integracji Codex: 65 PASS, 0 FAIL, 0 SKIP.
- Windows Server 2025 Datacenter, build 26100: instalacja, aktualizacja RC4 z zachowaniem danych, OCR, dokumenty, restart, aktualizator i dwie fikcyjne sprawy: PASS.
- Komputer Marty, jej rzeczywista sprawa i odpowiedź żywego modelu: UNVERIFIED.
- Instalator: **NotSigned** — brak zaufanego podpisu wydawcy.
- npm audit: 0 produkcyjnych, 1 high w narzędziach budowania; szczegóły i dostępna poprawka opisane w raporcie.

To ręczne wydanie testowe, nie aktualizacja kanału stabilnego. Nie pobieraj „Source code” jako programu.

## Integralność

Wersja: `5.0.0-rc.7`. Kod: `4823c6e4d4841157a866fd54d1dc379ae105925a`.
Rozmiar: `242569914` bajtów.
SHA-256: `b2f10c5b126d58daf05e13aafcbd7659c96b7cedd740c778a501980f7414d4db`.

Opublikowane materiały testowe zawierają wyłącznie fikcyjne dane. Instalator nie zawiera konta, kluczy ani rzeczywistych dokumentów klientów.
