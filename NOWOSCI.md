# Co nowego w Gentree

## v0.32 (17.10.2026)

- **Zdjęcie czy dokument.** W oknie materiału oznaczysz skan aktu, list czy inny dokument przyciskiem **„📄 To dokument (skan)”** (i z powrotem „🖼 To jednak zdjęcie”). Dokumenty mają na kafelkach znaczek 📄, a w Archiwum zdjęć są osobno od fotografii. Materiały oznaczone tak w Ancestry są rozpoznawane same.
- **Poprawka: program pamięta motyw.** Wybrany jasny lub ciemny wygląd (przycisk ◐) zostaje po ponownym uruchomieniu programu.

## v0.31 (17.10.2026)

- **Nowa mapa.** Mapa ma wyraźniejszy wygląd i **polskie nazwy miejscowości** – także za granicą (np. Ostrawa, Żylina). Kółka miejsc, ścieżka życia osoby i lista zdarzeń działają jak dotąd. Tak samo wygląda mapa na stronie zrobionej w programie.
- Nowa wersja umowy licencyjnej (1.4) – wymienia nowy serwis, z którego pochodzi mapa; program poprosi o jej akceptację.
- **Poprawka: osoba zmarła bez daty śmierci nie jest już pokazywana jako „żyje”.** W oknie edycji osoby wybierasz teraz **Żyje / Zmarł(a) / Nie wiadomo** – „Zmarł(a)” wystarczy, gdy data śmierci jest nieznana. Przycisk „Zapisz” pojawia się też po samej zmianie tego wyboru.

## v0.30 (15.10.2026)

- **Poprawki:** na telefonie, na stronie zrobionej w programie, mapa nie zasłania już otwartej karty osoby – po wybraniu osoby z mapy karta jest widoczna, a po jej zamknięciu mapę znów da się przesuwać palcem. Program uruchomiony obok innej kopii Gentree zawsze pokazuje swoje własne drzewo.

## v0.29 (15.10.2026)

- **Gentree i Claude.** Z licencją połączysz program z aplikacją **Claude** (Claude Desktop albo Claude Code) – na swoim planie Claude, bez dodatkowych opłat. Pytasz o drzewo zwykłym językiem („Kto z moich przodków urodził się w Krakowie?”, „Czego brakuje u Jana Kowalskiego?”), a na Twoją prośbę Claude dopisze osoby i fakty – np. z wyników Geneteki – razem ze źródłem. Każdą zmianę cofniesz przyciskiem ↶, a osoby żyjące są przed Claude ukryte. Włączysz to w Ustawienia → Program → Claude (MCP); szczegóły w [instrukcji](GENTREE-I-CLAUDE.md).
- **„Gdzie szukać dalej”** podpowiada akty tylko tam, gdzie mogą być dostępne: urodzenia i ślubu – dla zmarłych urodzonych przed 1950, zgonu – dla zmarłych co najmniej 50 lat temu. Dla osób żyjących nie ma tej sekcji (ich akty nie są udostępniane).
- **Kopia bazy przed aktualizacją** – gdy nowa wersja zmienia sposób zapisu danych, program najpierw sam zapisuje kopię drzewa obok niego.
- Nowa wersja umowy licencyjnej (1.3) – opisuje połączenie z Claude; program poprosi o jej akceptację.
- **Poprawki:** po usunięciu drzewa albo wpisaniu klucza informacja o trybie tylko do podglądu znika od razu po zamknięciu Ustawień; po wczytaniu dużego pliku ta informacja jest wyraźnie oznaczona na czerwono.

## v0.28 (15.10.2026)

- **Dowolna liczba drzew także w wersji darmowej.** Limit 200 osób liczy się łącznie dla wszystkich drzew – możesz prowadzić osobno np. swoją rodzinę i rodzinę współmałżonka.
- **Każdy plik GEDCOM się wczyta.** Drzewo większe niż limit licencji otwiera się do przeglądania: wszystkie widoki, wyszukiwanie, Ciekawostki i historia działają, a edycję, eksport i stronę do internetu odblokowuje klucz licencyjny. Osoby można usuwać i scalać, a zmiany cofać.
- **Wydruki w wersji darmowej** mają dyskretne oznaczenie „Gentree – wersja darmowa”. Z licencją drukujesz bez niego.
- **Cofanie zmian** działa także w drzewie otwartym tylko do podglądu.
- Nowa wersja umowy licencyjnej (1.2) – opisuje powyższe zasady wersji darmowej; program poprosi o jej akceptację.

## v0.27 (15.10.2026)

**Porządkowanie drzewa**
- **Znajdź duplikaty** (menu ⋯) – program wskazuje osoby wpisane dwa razy i mówi, dlaczego tak uważa. Scalasz je w oknie z trzema kolumnami: osoba A, wynik i osoba B. Dane przeciągasz albo przenosisz strzałkami, a takie same wartości są wypełnione od razu. Gdy wpisy mają różnych rodziców, wybierasz, która para zostaje.
- **Ujednolić miejsca** (menu ⋯) – różne zapisy tej samej miejscowości („Lisko”, „Lesko, Podkarpackie”) zamienisz na jeden.
- **Formy imion** – wyszukiwarka i „Znajdź duplikaty” wiedzą, że Joannes, Johann, Иван i Jan to to samo imię (także łacińska pisownia: Zophia = Zofia). Gdy nie ma dokładnego wyniku, wyszukiwarka pokazuje osoby różniące się jedną literą (Zys → Zyz).
- **Niepołączone z drzewem** – w „Brakach w danych” lista osób i gałęzi, do których nie prowadzi żadna droga od osoby startowej (zwykle osoba wpisana dwa razy), z przyciskiem „Porównaj i scal”.
- **Dodaj osoby z pliku .ged…** (menu ⋯) – dołączasz do swojego drzewa drzewo kuzyna, np. z Ancestry albo MyHeritage. Nic w Twoim drzewie nie znika. Program podpowiada, która osoba jest w obu plikach (np. wspólny dziadek), i otwiera okno scalania.

**Wpisywanie**
- **Podpowiedzi** przy wpisywaniu miejscowości (także dawnych nazw: Lisko → Lesko), imion i nazwisk. Płeć ustawia się sama po imieniu.
- **Źródło przy każdym fakcie** – akt, księga, archiwum i link do skanu. Źródła z zaimportowanego pliku GEDCOM wczytują się same. W „Brakach w danych” zobaczysz fakty bez źródła.
- **Podwójne daty z zaboru rosyjskiego** – wpisz „12/24 maja 1890” albo „jul. 12 maja 1890”. Program sprawdza, czy obie daty się zgadzają, a wiek i rocznice liczy według nowego stylu.
- **Dodawanie krewnego** – od razu z dodatkowymi faktami (zawód, zamieszkanie, chrzest…) oraz ulicą i numerem domu. Notatki mogą mieć wiele linii.

**Odkrywanie**
- **Gdzie szukać dalej** – w panelu osoby lista brakujących aktów z szacowanymi latami i miejscem. Jedno kliknięcie otwiera gotowe wyszukiwanie w Genetece (z właściwym województwem) albo w FamilySearch. Przycisk 🔎 przeniósł się tutaj.
- **📅 Na tle historii** – pod jakim zaborem osoba się urodziła i jakie wydarzenia przeżyła (powstania, wojny, emigracja) – z jej wiekiem w danym czasie.
- **Ciekawostki** – nowa zakładka: najpopularniejsze imiona w każdym stuleciu, długość życia, wiek przy ślubie, bliźnięta, skąd i dokąd wyjeżdżała rodzina.
- **🗂 Archiwum zdjęć** – wszystkie zdjęcia i dokumenty w jednym dużym oknie: tej osoby, jej gałęzi albo całego drzewa. Możesz szukać, sortować i zobaczyć zdjęcia, na których nikt nie jest oznaczony.

- **Data zdjęcia z pliku** – w oknie zdjęcia program pokazuje datę i aparat zapisane w pliku (EXIF) z przyciskiem „Użyj tej daty”. Nie wpisuje jej sam, bo przy skanach to data skanowania.
- **Daty po polsku w formularzach** – „14 wrz 2024”, „ok. 1900” zamiast zapisu technicznego.

**Druk i eksport**
- **🖨 Raporty do druku i PDF** – karta osoby, przodkowie i potomkowie.
- **⤓ Eksport gałęzi** – przodkowie albo potomkowie jednej osoby jako plik GEDCOM albo osobna strona do internetu.
- **Automatyczna kopia zapasowa** (⚙ Ustawienia → Eksport i dane) – program sam zapisuje kopię drzewa w wybranym folderze, np. na pendrivie albo w OneDrive.

## v0.25 (14.10.2026)

- **Mapa zna dużo więcej miejscowości.** Program ma wbudowaną bazę ok. 158 tysięcy miejscowości – cała Polska razem ze wsiami, dawne ziemie wschodnie (np. Lwów, Wilno, Stanisławów) i miasta na emigracji. Działa bez internetu i nigdzie nie wysyła nazw z Twojego drzewa.
- **Mapa rozróżnia miejscowości o tej samej nazwie** po województwie, powiecie albo sąsiedniej miejscowości z opisu („Wola, Lesko, Podkarpackie”). Gdy nie da się rozstrzygnąć, miejsce trafia na listę „bez dokładnego miejsca” – kliknij ją pod mapą, żeby zobaczyć, co uzupełnić.
- **Ulica i numer domu** – przy każdym zdarzeniu osobne pola „Ulica” i „Nr domu”. Zakładka **Domy** grupuje według miejscowości, ulicy i numeru, więc ten sam numer na różnych ulicach to różne domy.
- **🔎 Szukaj w Genetece** – w panelu osoby: otwiera w przeglądarce wyszukiwarkę Geneteki z nazwiskiem, imieniem i latami tej osoby.
- **Krótsze przyciski w panelu osoby** – „Drzewo osoby”, „Potomkowie”, ✎ (edycja) i 🔎 mieszczą się w jednym rzędzie.
- **Strona do internetu** ma tę samą mapę z bazą miejscowości.

## v0.24 (14.10.2026)

- **Nowa budowa programu.** Gentree uruchamia się teraz jako jeden program `Gentree.exe`. Aktualizacja sama usuwa stare pliki programu – Twoje drzewa, zdjęcia i licencja zostają bez zmian.
- **Poprawka:** strona do internetu otwarta prosto z dysku (bez wgrywania na serwer) pokazywała mapę pełną komunikatów „Access blocked”. Teraz zakładka Mapa pojawia się dopiero na stronie wgranej do internetu – serwery map wymagają adresu strony.

## v0.23 (14.10.2026)

- **Czytelniejsze listy osób.** Płeć widać po kolorze imienia i nazwiska (niebieski – mężczyzna, różowy – kobieta), zamiast kolorowego paska z boku.
- **Zdjęcia przy osobach** w widoku Potomkowie, w Rocznicach (przy rocznicy ślubu – oboje małżonkowie) i na ścieżce pokrewieństwa.
- **„Braki w danych”** – nowa nazwa zakładki, która pokazuje, czego w drzewie jeszcze brakuje (rodziców, dat, skanów).
- **Wachlarz bez obciętych nazwisk.** Długie imiona i nazwiska dzielą się na dwie, trzy linie albo dostają mniejszą czcionkę, zamiast kończyć się na „…”.
- **Drzewo bez nachodzących kart.** Przy rozwijaniu dalszych gałęzi (rodzeństwo przodków i ich potomkowie) karty nie wchodzą już na siebie, a drzewo nie rozjeżdża się niepotrzebnie na boki.
- **Linie, które da się śledzić.** Gdy linie kilku rodzin biegną obok siebie, każda rodzina ma swoją wysokość i zaokrąglone narożniki – widać, od której pary schodzi która linia.
- **Strzałki rodzeństwa** na środku karty i nigdy na ikonkach „drzewo tej osoby”.
- **Poprawka:** w oknie „Dodaj ojca / matkę / dziecko…” opcja „Osoba, która już jest w archiwum” nie pokazywała pola wyszukiwania.

## v0.22.1

- **Poprawka:** usunięcie osoby głównej (★) psuło widok drzewa. Teraz osobą główną zostaje ktoś z najbliższej rodziny, a jedynej osoby w drzewie nie da się usunąć.

## v0.22

- Program przeniesiony do nowego, uporządkowanego kodu. Twoje drzewa, zdjęcia i licencja przenoszą się automatycznie.

## v0.20 – v0.21

- Instalator zamiast pojedynczego pliku .exe – mniej fałszywych alarmów antywirusów, aktualizacja nie rusza Twoich danych.
- Okno programu startuje zmaksymalizowane.
