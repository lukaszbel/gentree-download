# Gentree – pobieranie

Najnowsza wersja: **v0.39.1** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu oraz połączenie z Claude. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** z licencją połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.39.1 (4.11.2026)

- **Poprawka: drzewo ze ślubem bez źródła otwiera się za pierwszym razem, a plik .ged z takim ślubem daje się wczytać.** W v0.39 ślub zapisany u jednej osoby bez źródła psuł pierwsze otwarcie drzewa z poprzedniej wersji (do ponownego uruchomienia programu drzewo było zablokowane), a pliku .ged z takim ślubem nie dało się wczytać. Przy okazji w takim drzewie nie pokazywały się źródła i notatki ślubów par zapisane w pliku .ged. Teraz program przy pierwszym otwarciu robi to, czego v0.39 nie zdążyła: przenosi takie śluby do pary i pokazuje źródła ślubów par. Zmienia tylko to, co było w drzewie przed v0.39; tego, co dopisałeś lub poprawiłeś w v0.39, nie rusza. Przed zmianą zapisuje kopię drzewa obok (plik „…przed-aktualizacja-s4.db”).
- **Skan aktu ślubu jest w materiałach obojga małżonków** także w drzewach przeniesionych z poprzedniej wersji (do tej pory tylko po wczytaniu pliku .ged).


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
