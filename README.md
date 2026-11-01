# Gentree – pobieranie

Najnowsza wersja: **v0.36** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu oraz połączenie z Claude. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** z licencją połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.36 (1.11.2026)

- **Historia: podgląd i wycofanie jednej zmiany.** Kliknięcie wpisu w Historii pokazuje, co dokładnie się zmieniło (było → jest), i daje przycisk „Wycofaj tę zmianę”. Cofa się tylko ta jedna zmiana, nawet jeśli po niej były inne, a samo wycofanie też trafia do Historii, więc można je odwrócić. Gdy te same dane zmieniłeś później, program nie pozwoli wycofać i powie dlaczego.
- **Szukaj w Ancestry.** W „Gdzie szukać dalej” przy brakujących aktach jest przycisk Ancestry, a pod listą „Szukaj w Ancestry”. Otwiera wyszukiwarkę Ancestry z imieniem, nazwiskiem i latami z drzewa (to tylko link, program niczego nie wysyła).
- **„+ Małżonek” w karcie rodziny.** Gdy w rodzinie brakuje męża albo żony, przycisk „+ Małżonek” jest teraz w tej karcie i uzupełnia właśnie tę rodzinę. Wcześniej był tylko ogólny przycisk pod rodzinami, który wybierał pierwszą rodzinę bez partnera.
- **Galeria na stronie drzewa.** Strona drzewa wyeksportowana do HTML i strona rodziny pokazują materiały osób (zdjęcia, skany, PDF) z podglądem, opisem i oznaczonymi osobami. Zdjęcia pojawiają się też w drzewie-plakacie, kartach, raportach i książce rodu.
- **Zapis klucza licencyjnego bez zawieszania okna.** Wpisanie klucza mogło zamrozić program na około 10 sekund. Teraz zapis jest natychmiastowy.
- **Nowa wersja umowy licencyjnej (1.8):** dane licencjodawcy (adres, NIP), odesłanie do regulaminu sprzedaży i licencja „bez limitu osób”. Program poprosi o jej akceptację.
- **Dodawanie krewnego bez daty urodzenia.** Data urodzenia nie jest już obowiązkowa – wystarczy imię i wybór „Żyje” albo „Zmarł(a)”. Osoba oznaczona jako żyjąca jest zawsze ukryta na stronie rodziny i przed Claude, także bez daty.
- **Wyszukiwarka nie gubi już osób.** Gdy wiele osób miało to samo imię i nazwisko, lista podpowiedzi pokazywała tylko 9 z nich, bez informacji o reszcie, i części nie dało się znaleźć. Teraz na dole jest „…i jeszcze 4 – dopisz rok albo miejscowość”, a wyszukiwanie zawęzisz rokiem urodzenia lub śmierci albo miejscem urodzenia („jan kowalski 1888”).
- **Znak Gentree na stronie drzewa.** Strona drzewa wyeksportowana do HTML i strona rodziny w internecie mają w rogu małe logo Gentree z linkiem do gentree.com.pl (w samym programie go nie ma).
- **Hasło główne strony rodziny nie usuwa innego hasła.** Gdy w polu nazwy zostało wpisane np. „mama”, zapisanie nowego hasła głównego po cichu kasowało hasło pełnego dostępu „mama”. Teraz hasło główne zmienia tylko siebie. Uszkodzone zgłoszenie nie blokuje już całej zakładki „Zgłoszenia”.
- **Klucz licencyjny, którego nie da się zapisać.** Gdy folder danych jest tylko do odczytu, program mówi, że klucza nie zapisano, zamiast pokazywać „Licencja aktywna” i zapominać klucz przy następnym uruchomieniu.
- **Claude nie pozna dat osób żyjących z ostrzeżeń.** Komunikaty kontroli dat przy dodawaniu osób, faktów i ślubów przez Claude nie podają dat ani wieku osób żyjących, a lista problemów w drzewie nie pokazuje daty ślubu z osobą żyjącą.
- **Zdjęcia bez zbędnych kopii.** To samo zdjęcie dodane drugi raz pod inną nazwą nie zapisuje się już jako drugi plik, a odrzucone dodanie (np. do nieistniejącej osoby) nie zostawia pliku w archiwum.
- **Klucz licencyjny z Notatnika działa.** Plik license.txt zapisany w Notatniku jako „UTF-8 z BOM” albo klucz przełamany w e-mailu na kilka linii był odrzucany jako nieprawidłowy. Teraz program pomija niewidoczne znaki i przejścia do nowej linii.
- **Claude nie widzi osób żyjących także przy zapisie.** Odpowiedzi narzędzi zapisu (dodanie faktu, cofnięcie zmiany) nie podają już imion i nazwisk osób żyjących, a przy zmarłym z żyjącym małżonkiem Claude nie dostaje daty ani miejsca ślubu.
- **Strona gałęzi bez nazwiska żyjącej osoby w adresie.** Gdy gałąź zaczyna się od osoby żyjącej, folder strony nosi imię najbliższego zmarłego przodka.
- **Mapa katastralna:** pasek postępu „Utwórz prezentację” znów pokazuje postęp; usuwanie mapy usuwa wyłącznie jej własny folder. Prezentacja wsi otwiera się poprawnie także wtedy, gdy w opisie domu lub osoby jest znak „</”; oznaczenie siatki z dwiema literami nie jest już przyjmowane jako poprawne; puste pola zamiast słowa „None”.
- **GEDCOM z innych programów.** Pliki w kodowaniu Windows-1250, UTF-16 albo z wcięciami wczytują się z poprawnymi polskimi znakami; plik w kodowaniu ANSEL program odrzuca z komunikatem zamiast wczytać połowę. Adres zapisany jako ADR1/ADR2 trafia do ulicy. Plik, który nie jest GEDCOM-em, daje jasny komunikat.
- **Eksport GEDCOM nie gubi danych.** Notatki i źródła przy ślubie i rozwodzie zostają w pliku, współrzędne miejsc mają pełną dokładność, a nagłówek podaje kodowanie UTF-8.
- **Dołączanie gałęzi z drugiego drzewa** przenosi też notatki z badań i punkty miejscowości na mapie.
- **Pokrewieństwo po polsku.** Poprawne formy w opisach typu „żona szwagra”, „brat teścia”, „syn przyrodniego brata”; daty z angielską nazwą miesiąca pisaną wielkimi literami („12 JAN 1890”) rozpoznają się w drzewie i w rocznicach.
- **Zmiana folderu danych przenosi wszystko:** także mapy katastralne, kopie drzewa sprzed zmian, zgłoszenia i ustawienia publikacji. Nazwa drzewa jak „CON” albo kończąca się kropką nie psuje już folderu w Windows.


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
