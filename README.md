# Gentree – pobieranie

Najnowsza wersja: **v0.51.1** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu oraz połączenie z Claude. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** z licencją połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.51.1 (w przygotowaniu)

- **Pliki GEDCOM bez strat:** plik wczytany i zapisany z powrotem (także wiele razy z rzędu) ma te same dane. Kilka wpisów ślubu jednej pary (np. cywilny i kościelny) to teraz osobne śluby, każdy z datą, miejscem i rodzajem („Ślub cywilny”, „Ślub kościelny”, do zmiany w edycji); wpis ślubu z samą notatką albo źródłem dołącza do ślubu z datą, a dwa identyczne wpisy to jeden ślub; ślub zapisany przy osobie przechodzi do pary tylko wtedy, gdy nic nie ginie (ślub z innym miejscem, inną datą albo danymi, których ślub pary nie przechowa, zostaje przy osobie). Chrzest (BAPM), wspólne notatki, opis pliku zdjęcia i dopisek „ślub był” wracają w eksporcie jak w pliku, nowe źródła dostają kolejny numer w stylu pliku (po S54 jest S55), a daty w pliku mają miesiąc wielkimi literami (23 APR 1805). Kilka notatek przy jednym fakcie to jedna notatka (każda w osobnym akapicie, żadna nie ginie przy edycji), zdjęcie albo skan zapisany wprost pod faktem staje się skanem tego faktu, a zdjęcie przypisane w pliku do pary jest przy obojgu małżonkach (skany faktów i zdjęcia par nie stają się zdjęciem profilowym). Zapis dużego drzewa do pliku GEDCOM jest kilka razy szybszy.
- **Raport po wczytaniu GEDCOM pokazuje, czego eksport nie odda tak samo:** program porównuje plik z tym, co sam by zapisał, i podaje, co eksport pominie lub zapisze inaczej, z przykładem (np. „odnośnik do pliku lub zdjęcia (OBJE) – 2×, np. osoba I12”). Plik źródłowy zostaje bez zmian.
- **Drzewa wczytane z GEDCOM we wcześniejszej wersji:** jeśli w pliku para miała kilka wpisów ślubu, program pokazuje komunikat, że daty i miejsca części ślubów mogły nie trafić do drzewa, dopóki go nie zamkniesz („Rozumiem”) albo nie uzupełnisz drzewa z pliku (wtedy zamyka się sam). Samo drzewo zostaje bez zmian, dopóki go nie uzupełnisz.
- **Uzupełnij z pliku GED…** (menu ⋯ i przycisk w tym komunikacie): wskazujesz plik, z którego wczytano drzewo, a program pokazuje listę ślubów, którym w drzewie brakuje daty albo miejsca, a plik je ma (np. „F11 Jan Kowalski i Anna Nowak: ślub 22 lis 1905, Pstrągowa”). Dopisuje tylko zaznaczone i tylko puste pola: niczego nie nadpisuje i nie dodaje nowych faktów. Pary, przy których data w pliku należy do innego ślubu (np. cywilnego, a w drzewie jest kościelny) albo gdy imię lub nazwisko małżonka różni się od pliku, pomija i pokazuje z powodem; inny plik (te same numery, inne osoby) rozpoznaje i niczego nie zmienia. Przed zapisem robi kopię drzewa, a całość cofniesz jednym ↶.
- **Notatka przy osobie w roli:** przy chrzestnym, świadku, akuszerce i innych osobach w roli dopiszesz notatkę (np. zawód, miejscowość, wiek); karta faktu pokazuje ją przy nazwisku („Chrzestny: Jan Nowak (rolnik z Pstrągowej)”), kliknięcie osoby w edycji zmienia rolę i notatkę, a plik GEDCOM zapisuje ją jako notatkę powiązania (ASSO / NOTE). Notatki osób żyjących nie trafiają do kopii dla rodziny.
- **Asystent AI dopina skany bez ryzyka:** przy zmianie faktu może dopiąć albo odpiąć pojedyncze skany (add_scans, remove_scans), a pozostałe skany faktu zostają. Po zmianie podaje aktualną listę skanów faktu.
- **Skan aktu jednym poleceniem:** asystent AI dodaje plik, od razu przypina go do wskazanego faktu osoby i zaznacza ją ramką (z rolą w akcie). Taki skan jest dokumentem, więc nie staje się zdjęciem profilowym. Całość to jeden krok, który cofniesz jednym ↶.
- **Kto zmienił:** historia zmian zapisuje, czy zmianę zrobiłeś w programie, czy asystent AI, a asystent może pokazać tylko swoje albo tylko Twoje zmiany. Zmiany sprzed tej wersji, przy których źródło nie było zapisane, są oznaczone jako „nieznane”.
- **„Wpisz klucz” przy limicie osób:** otwiera Ustawienia → Licencja na wierzchu, z kursorem w polu klucza; okno blokady nie wraca już nad Ustawieniami, a komunikat wskazuje przyciski „Kup licencję” i „Wpisz klucz” tuż pod nim (także przy eksporcie i stronie do internetu w Ustawieniach).
- Poprawki bezpieczeństwa i ochrony danych osób żyjących przy imporcie i na stronie rodziny.


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
