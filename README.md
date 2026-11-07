# Gentree – pobieranie

Najnowsza wersja: **v0.41** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu oraz połączenie z Claude. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** z licencją połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.41 (7.11.2026)

- **Lepsze wklejanie wyników z Geneteki.** Program rozpoznaje wiersze bez numeru aktu, z uwag bierze numer domu i sygnaturę księgi, a dokładną datę osobno dla każdego wiersza, także przy wklejeniu kilku naraz. Ten sam chrzest zaindeksowany w dwóch księgach dodaje raz (drugi indeks zapisuje w notatce). Inne zapisy imion (Prakseda, Parascewa = Paraskewa) i nazwisko matki po mężu („Jaremkowa”) nie przeszkadzają w dopasowaniu rodziców.
- **Zdjęcia i skany „Niepubliczne”.** W oknie materiału, w sekcji „Prywatność”, możesz oznaczyć zdjęcie lub skan jako niepubliczny: nie zobaczy go Claude i nie trafi na stronę rodziny. Nowsze zdjęcia bez oznaczonych osób Claude zobaczy dopiero po zaznaczeniu „Pokaż Claude”.
- **Sprawdzanie drzewa przy otwieraniu.** Gdy plik drzewa jest uszkodzony albo zmienił go inny program, Gentree pokaże, co jest nie tak, i zaproponuje przywrócenie ostatniej kopii zapasowej. Sam niczego nie zmienia. Daty zapisane w postaci, której program nie odczyta (np. „4/18/1922”), pokazuje w zakładce „Braki w danych”.
- **Ostrzeżenie przed połączeniem z Claude.** Przy włączaniu połączenia program wyjaśnia, że dane odczytane przez Claude trafiają do firmy Anthropic, i prosi o potwierdzenie. Kto miał połączenie włączone wcześniej, nie musi go włączać ponownie.
- **Nowa wersja umowy licencyjnej (1.9)** z zasadami połączenia z Claude; przy pierwszym uruchomieniu program poprosi o jej akceptację.
- **Rodzice dopisani przez Claude od razu widoczni w drzewie**, tak jak po dodaniu w formularzu.
- **Poprawki:** numer domu „dom nr 155” nie pokazuje się już jako „dom dom nr 155”; skan aktu dodany jako dokument nie zostaje zdjęciem profilowym osoby.
- **Import z MyHeritage: zamieniony mąż i żona.** Gdy w pliku .ged kobieta jest zapisana w rodzinie jako mąż, a mężczyzna jako żona, program przy imporcie sam ustawia ich na właściwych miejscach i podaje to w podsumowaniu importu. W drzewie zaimportowanym wcześniej popraw to jednym przyciskiem: „Braki w danych” → „Sprawdź drzewo” → „Popraw zamienionego męża i żonę” (da się cofnąć ↶).
- **Daty zapisane przez inne programy.** Daty w rodzaju „4/18/1922”, „22Aug1901”, „25 11 1921” czy „1906-02-05” program przy imporcie sam zamienia na swój zapis, gdy ich znaczenie jest pewne. W drzewie zaimportowanym wcześniej zrobisz to jednym przyciskiem: „Braki w danych” → „Sprawdź drzewo” → „Popraw zapis dat” (da się cofnąć ↶). Przy niejednoznacznych, np. „4/5/1922”, program podpowie oba odczyty (4 maja albo 5 kwietnia).
- **Poprawki bezpieczeństwa w połączeniu z Claude.**


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
