# Gentree – pobieranie

Najnowsza wersja: **v0.39** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu oraz połączenie z Claude. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** z licencją połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.39 (4.11.2026)

- **Ślub w oknie edycji, u obojga partnerów.** W „Edycji” osoby jest teraz wiersz „Ślub” z imieniem partnera: data, miejsce, notatka, źródło i skan aktu. Ślub jest zapisany przy parze, więc oboje partnerzy widzą i zmieniają to samo (wcześniej ślub był widoczny tylko u osoby, która miała go zapisanego jako własny fakt). Przycisk „+ Ślub” dodaje ślub z partnerem z drzewa, a przy kilku związkach pozwala wybrać, z kim. Pod ślubem „+ rozwód” zaznacza rozwód z datą i miejscem. Akt ślubu wklejony z Geneteki też trafia do ślubu pary. Śluby zapisane wcześniej tylko u jednego z małżonków program sam przenosi do pary razem ze źródłem i skanem; zostawia je tylko wtedy, gdy rok nie zgadza się ze ślubem pary, żebyś sam zdecydował.
- **Claude zna więcej z drzewa.** Połączony z Gentree Claude widzi skany przypięte do faktów, materiały osoby (skany i zdjęcia) oraz akt ślubu i rozwód przy parze. Może dopisać fakt z adresem i skanem z archiwum, a przy ślubie zapisać akt, skan i rozwód. Ślubu nie zapisuje już jako osobnego faktu jednej osoby, tylko przy parze. Zdjęcia osób żyjących pozostają przed nim ukryte.
- **„Zmarł” albo „Zmarła”.** W oknach dodawania i edycji osoby przycisk statusu odmienia się według wybranej płci („Zmarł(a)” zostaje tylko przy płci nieznanej).
- **„Gdzie szukać dalej” podpowiada też akt ślubu, który jest w drzewie bez źródła,** z wyszukiwaniem wokół roku ślubu.
- **Panel osoby z rozwodem znów się otwiera.** W v0.38 po kliknięciu osoby, która ma w drzewie rozwód, panel z faktami się nie pokazywał, a karta nie dostawała żółtej ramki zaznaczenia.
- **Okno kadrowania zdjęcia bez poziomego paska przewijania,** a ✕ przy oznaczonych osobach na zdjęciu jest szare (czerwone dopiero po najechaniu), jak w całym programie.
- **Szybsze drzewa ze zdjęciami wczytanymi z pliku.** Program sam robi małe podglądy zdjęć i skanów, także dla drzewa wczytanego z pliku .ged lub paczki .zip (wcześniej powstawały tylko przy dodawaniu zdjęcia w oknie, więc takie drzewo ładowało pełne skany: działało wolniej, a miniatury były mniej wyraźne). Po wczytaniu pliku do istniejącego drzewa stare podglądy są usuwane, więc nie pokaże się podgląd innego zdjęcia.


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
