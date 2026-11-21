# Gentree – pobieranie

Najnowsza wersja: **v0.54** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** także w wersji bezpłatnej połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.54 (22.11.2026)

- **📊 Analizy:** nowy przycisk na pasku otwiera osobne okno ze statystykami drzewa. Tabela przestawna i wykres: cechy przeciągasz albo klikasz do stref „Wiersze”, „Kolumny” i „Filtry”, wybierasz, co liczyć (osoby albo zdarzenia) i według czego (czas, miejsce, płeć, nazwisko, pokolenie, wiek, zawód, wyznanie, przyczyna zgonu i inne), a program pokazuje tabelę, wykres albo jedno i drugie. Są gotowe przykłady (np. „Na co umierali ludzie w XIX wieku”), a własne analizy zapisujesz pod nazwą i wracasz do nich później. Wynik wyeksportujesz do CSV (do Excela) albo wykresu PNG. Dla bardziej wymagających jest „Zaawansowane: SQL” (tylko odczyt). Analizy niczego nie zmieniają w drzewie i domyślnie pomijają osoby żyjące. Claude połączony z Gentree potrafi liczyć te same statystyki.
- **Tagi przy osobach i materiałach:** własne słowa (np. „do sprawdzenia”, „Ameryka”, „album babci”) dopiszesz przyciskiem „+ tag” w edycji osoby, w oknach dodawania i w oknie materiału. Widok „🏷 Tagi” (także z menu ⋯) wyszukuje tagi w drzewie i pokazuje osoby i materiały z wybranymi tagami; tag zmienisz albo usuniesz w jednym miejscu (↶ cofa). Tagi trafiają do pliku GED i wracają z niego, a Claude połączony z Gentree potrafi je czytać i dopisywać.
- **Drzewa i Ustawienia:** kliknięcie nazwy drzewa na pasku otwiera menedżera drzew: przełączanie między drzewami, nowe puste drzewo, utworzenie z pliku GED, kopie zapasowe, „Aktualizuj z pliku GED”, „Dołącz drzewo kuzyna”, „Przywróć kopię”, „Do posprzątania” i „Nowa gałąź” są teraz w jednym miejscu (z menu ⋯ zniknęły). ⚙ Ustawienia to jedna strona ze spisem sekcji (Wygląd, Kopie automatyczne, Claude, Aktualizacje, Licencja, Zaawansowane), w kolorach wybranego motywu. Język przełączasz przyciskiem EN / PL na pasku.
- **Górny pasek przy każdej szerokości okna:** zakładki i przyciski mieszczą się od 1024 do 2560 px, przy braku miejsca Archiwum i Analizy są ikonami, a pasek przechodzi do dwóch linii dopiero wtedy, gdy naprawdę się nie mieści.
- **Aktualizuj z pliku GED zamiast „Uzupełnij”:** stary „Uzupełnij z pliku GED…” zniknął, wszystko robi „Aktualizuj z pliku GED”. Strzałki ← → obok tytułu okna przechodzą po różnicach osoby i dalej do następnej (albo poprzedniej) osoby, a bieżąca różnica jest podświetlona także w widoku „GEDCOM”. Lepsza obsługa ślubów par z wcześniejszego importu: rodzaj ślubu zostaje, data ślubu cywilnego nie trafia do kościelnego, a eksport nie dubluje ślubów. Dokładniejsza data albo miejsce z drzewa nie są zastępowane mniej dokładnymi z pliku, a małżonek jest dopasowany po rodzinie zamiast dodawany drugi raz. Komunikat startowy o starym imporcie znika po aktualizacji.
- **Podpowiedzi miejsc z dawnymi nazwami:** przy wpisywaniu miejsca program zna dawne i niemieckie nazwy miejscowości (np. „niem. Breslau”, nazwy okupacyjne osobno) i znajduje miejscowość także po drugiej nazwie.
- **Ujednolić miejsca:** sama nazwa miejscowości, bez gminy i województwa, trafia do grupy pełnego zapisu tej miejscowości (gdy pasuje do kilku, jest w każdej z grup z dopiskiem). Wzorem jest zawsze pełny zapis z punktem na mapie, bez ulicy i numeru domu.
- **Ten sam grób:** przy pochówku można wybrać „Ten sam grób co…” (kopiuje grób innej osoby razem ze zdjęciami, bez dublowania plików) oraz dopisać „+ Pochowani w tym grobie”, także w oknach dodawania osoby. Program pyta, zanim zastąpi inny grób, a całość cofniesz jednym ↶.
- **Mapa 3D do oglądania:** „Widok 3D” w Domach jest tylko do oglądania (bez zakładek edycji i przycisków usuwania). Do zmian służy „Edytuj mapę…” w rogu.
- **Skąd pochodzę w kolorach wachlarza:** półkole pochodzenia używa tych samych kolorów co Wachlarz, na szarym tle.
- **Kto to?:** najpierw osoby już podpięte do materiału, a jeszcze nieoznaczone na zdjęciu.
- **Zdjęcie profilowe tylko z wyboru:** program sam nie ustawia już zdjęcia profilowego (przy dodaniu, imporcie ani pobieraniu), robi to tylko ★ albo plik GED, który je wskazuje, a przy zdjęciu profilowym jest przycisk „Nie używaj jako profilowego”.
- **Szukaj grobu:** gdy pochówek jest już wpisany, sekcja jest zwinięta z dopiskiem „(pochówek wpisany)”.
- **Słowniczek metrykalny:** doszły przyczyny zgonów (po łacinie, niemiecku, rosyjsku i staropolskie).
- **Cofanie:** Ctrl+Z działa także w otwartych oknach, a „Cofnij” cofa tylko swój krok (duplikaty, twarze w oknie zdjęcia i w „Kto to?”).
- **Kto żyje:** osoba bez daty urodzenia, ale z chrztem albo innym faktem z datą, jest oceniana po tej dacie (wcześniej mogła zostać uznana za zmarłą). Niepełne daty są liczone na korzyść „może żyć”, a jawne „Żyje” zostaje.
- **Instalator:** przy aktualizacji ostatnia strona instalatora proponuje „Zobacz, co nowego w wersji …”.
- **Wygląd:** nieaktywne przyciski są wyszarzone (w ciemnym motywie nie wyglądają już jak aktywne), a podpowiedź tagu przesuwa się razem z polem przy przewijaniu formularza i go nie zasłania.
- **Poprawki:** „Nie wiadomo” bez dat zapisuje się jako „Żyje”; w „Aktualizuj z pliku GED” rodzice są dopisywani także rodzeństwu, „Pomiń” nie myli się z „Do posprzątania”, a niemożliwa data ślubu jest oznaczona ⚠; „Dołącz drzewo kuzyna” kończy komunikatem z „↶ Cofnij” i przejściem do dołączonej gałęzi; drzewo z błędnymi wpisami (wskazującymi na nieistniejące osoby lub rodziny) otwiera się, a „Napraw drzewo” usuwa je po zachowaniu kopii pliku; liczne drobne poprawki wyglądu okien i poprawki po testach nowej wersji.
- Poprawki bezpieczeństwa i ochrony danych.


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
