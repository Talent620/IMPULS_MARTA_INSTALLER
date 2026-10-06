# IMPULS Dotacje Marta — wersja testowa RC8

**Dokumenty → przygotowanie wniosku → wspólny przegląd → pliki do kontroli.**
Status misji: **PARTIAL**. Pełny przebieg na prawdziwym modelu pozostaje **LIVE BLOCKED**.
Kontrolowane odpowiedzi testowe nie dowodzą autonomicznego wypełniania oficjalnego wniosku.

- [Instalator Windows RC8](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/download/test-v5.0.0-rc.8/IMPULS-Dotacje-Marta-5.0.0-rc.8-Setup.exe)
- [Instrukcja dla Marty — PDF](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/download/test-v5.0.0-rc.8/MARTA-Instrukcja-RC8.pdf)
- [Raport i dowody testów](https://github.com/Talent620/IMPULS_MARTA_INSTALLER/releases/tag/test-v5.0.0-rc.8)

## Jak zacząć

1. Przed aktualizacją wykonaj pełną zaszyfrowaną kopię w aplikacji.
2. Zainstaluj EXE i otwórz **MARTA AI**.
3. W **Ustawieniach AI** wybierz własny sposób dostępu, model i autonomię. Oficjalny Codex CLI wymaga osobnej instalacji. Kliknij **Zapisz i sprawdź połączenie**.
4. Dodaj dokumenty lub folder. Program odczyta materiały nawet bez wybranego naboru i wzoru.
5. Kliknij **Przygotuj wniosek**. W **Przejrzyj propozycje** sprawdź źródła, pola i załączniki. Po decyzjach ponów przygotowanie.
6. Otwórz aktualne wyniki. Braki, nieobsługiwane pola i niepotwierdzone kwoty nie oznaczają gotowego wniosku.

Program nie podpisuje ani nie wysyła wniosku. API jest płatne osobno, ChatGPT podlega limitom własnego konta; nie ma automatycznego przejścia na płatne API.

## Zakres potwierdzenia

- Pełna regresja i nowe kontrolowane testy: PASS. Spakowany główny chat Linux/Windows z kontrolowanym providerem: PASS.
- Windows Server 2025 Datacenter 10.0.26100: instalacja, aktualizacja z RC7 z zachowaniem danych, OCR, dokumenty, restart, aktualizator i dwie fikcyjne sprawy: PASS.
- Pobrano 28 dokumentów rzeczywistego historycznego naboru z oficjalnego źródła; to test pobierania, nie kwalifikowalności ani kompletności dokumentacji.
- LIVE AI: BLOCKED. Komputer Marty i rzeczywista sprawa: UNVERIFIED.
- Złożone kontrolki, wzory PDF i portale bez właściwego adaptera pozostają ograniczeniem. Szkic roboczy nie jest oficjalnym wnioskiem.
- Instalator: **NotSigned**, brak zaufanego podpisu wydawcy.
- npm audit: 3 moderate produkcyjne, 10 moderate łącznie, 0 high/critical; dokładny zakres w raporcie.

To ręczne wydanie testowe, nie aktualizacja kanału stabilnego. Nie pobieraj „Source code” jako programu.

Wersja: `5.0.0-rc.8`. Kod: `4f446d05cff8e6105f8805d5fe4ea21ea58b9587`.
Rozmiar: `242575089` bajtów.
SHA-256: `7ac541a1b968b7243b6bdb0fafcb955ea881358988985d90fecf74ddb885fca2`.

Opublikowane materiały testowe zawierają wyłącznie fikcyjne dane. Instalator nie zawiera konta, kluczy ani rzeczywistych dokumentów klientów.
