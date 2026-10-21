# Co nowego w Gentree

## v0.35.1 (21.10.2026)

- **Pierwsze uruchomienie na nowym komputerze naprawione.** Po świeżej instalacji Gentree mógł się w ogóle nie otworzyć – bez okna i bez komunikatu. Teraz przy pierwszym uruchomieniu program zakłada folder na dane w Dokumentach (Dokumenty\Gentree) i od razu się otwiera. Jeśli wcześniej Gentree u Ciebie nie ruszył, zainstaluj tę wersję i uruchom go jeszcze raz.
- **Podpisy w prezentacji wsi bez Claude.** Gdy w zabudowie jest dłuższa przerwa (np. dwa przysiółki), podpis domu przodków pojawia się tuż przed tym domem, a nie kilkaset metrów wcześniej; po minięciu domu podpis znika.

## v0.35 (20.10.2026)

- **Mapa katastralna wsi.** W zakładce „Domy” przy wsi przycisk **„🗺 Mapa katastralna”**: wczytujesz skany mapy katastralnej z XIX wieku – pliki JPG albo od razu cały ZIP pobrany z szukajwarchiwach.gov.pl. Program sam znajduje ramki arkuszy brulionu i układa arkusze według oznaczeń siatki katastralnej (przepisujesz je z powiększonego napisu), a po kliknięciu kilku wspólnych punktów kładzie mapę na dzisiejsze zdjęcie lotnicze z Geoportalu. Chałupom nadajesz numery domów (można wkleić też spis właścicieli). Kliknięcie domu pokazuje właściciela i osoby z drzewa, które według aktów mieszkały pod tym numerem; w liście domów przy takich adresach link „🗺 na mapie”. Suwak przenika dawną mapę z dzisiejszą. Mapy bez siatki (np. pruskie „Flur … Blatt …”, uwłaszczeniowe) też się da – każdy arkusz dopasowujesz osobno.
- **Wieś w 3D i przelot nad nią.** Dawna mapa leży na modelu terenu, a chałupy stoją w miejscach z mapy. Przycisk **„🎬 Utwórz prezentację”** buduje stronę wsi z przelotem drona wzdłuż zabudowy i podpisami przy domach Twoich przodków, z przejściem do dzisiejszego zdjęcia lotniczego. To jeden plik HTML, który możesz wysłać rodzinie – otwiera się w przeglądarce, także na telefonie. Osoby żyjące nigdy się w nim nie pojawiają. Poradnik krok po kroku: https://gentree.com.pl/jak-zrobic-mape-3d/
- **Mapa katastralna z Claude** (z licencją): Claude może odczytać oznaczenia arkuszy i numery domów z map, przepisać spis właścicieli, sprawdzić dopasowanie i wyreżyserować przelot – z trasą, przystankami i opowieścią o rodzinie przy kolejnych chałupach.
- **Przeciąganie zdjęć – teraz widoczne.** Pod „Materiałami” w panelu osoby podpowiedź „lub przeciągnij tu pliki”, a podczas przeciągania galeria podświetla się ramką. Zdjęcia i skany przeciągnięte z Eksploratora na panel (albo na kartę osoby w drzewie) dodają się do tej osoby.
- **Nazwa hasła do strony rodziny bez kombinowania.** W zakładce „Hasła” możesz wpisać nazwę po polsku i ze spacjami („ciocia Basia”) – program sam zamieni ją na dozwoloną postać („ciocia-basia”) zamiast pokazywać błąd.
- **Kopia zapasowa na OneDrive działa.** Gdy folder kopii był w OneDrive (albo Dropbox), kopia kończyła się błędem „Odmowa dostępu” – usługa od razu wysyłała nowe pliki i blokowała ostatni krok. Teraz kopia zapisuje się bez tego kroku, a resztki nieudanych prób program sam usuwa.
- **Drzewo dostępne tylko z okna programu.** Gdy Gentree jest otwarty, inne programy na komputerze nie mogą już odczytać ani zmienić drzewa przez wewnętrzny serwer programu – każde uruchomienie dostaje własny tajny klucz, który zna tylko okno Gentree.
- **Ochrona przed udostępnianiem kluczy.** Przy sprawdzaniu aktualizacji program zgłasza też uruchomienie na gentree.com.pl: wersję i – przy licencji – skrót klucza (nie sam klucz). Serwer zapisuje tylko skrót adresu internetowego zmieniany co miesiąc, więc widać, czy jeden klucz nie działa na kilkudziesięciu komputerach. Żadne dane drzewa nie są wysyłane; wyłączysz to w Ustawieniach → Aktualizacje. Nowa wersja umowy licencyjnej (1.7) – program poprosi o jej akceptację.
- **Szybsze oznaczanie osób na zdjęciach.** Po zaznaczeniu twarzy wystarczy kliknąć osobę na liście – oznaczenie zapisuje się od razu, bez osobnego „Zapisz”. Przycisk zostaje tylko dla nazwy wpisanej ręcznie (osoby spoza drzewa).

## v0.34 (17.10.2026)

- **Migracje w czasie.** Na mapie przycisk **„▶ Migracje w czasie”**: przodkowie jako kolorowe kropki (kolor = ród), które rok po roku pojawiają się w miejscu urodzenia, przemieszczają się między miejscami z drzewa i znikają w roku śmierci – jak autobusy na mapie na żywo. Podróżujący mają podpis „Jan Kowalski → Chicago”. Licznik roku, suwak czasu, prędkość i ślady przebytych tras. Działa też na stronie dla rodziny.
- **Książka rodu do druku.** W panelu osoby „Raporty” → **„📖 Książka rodu”**: potomkowie albo przodkowie wybranej osoby, rozdziałami według pokoleń. Każda osoba ma numer i opis złożony z danych („Urodził się 12 maja 1880 r. w miejscowości Łukawica. Syn Jana i Marii z d. Nowak…”), małżeństwa z dziećmi (numer wskazuje ich dalszy opis), zdjęcie profilowe, notatki i źródła w przypisach. Na początku strona tytułowa i **spis treści**, na końcu **indeks osób, wykaz miejscowości i wykaz źródeł z numerami stron**; strony są numerowane. Możesz dołączyć **zdjęcia rodzinne** (do 3 przy osobie, z podpisem, kto jest na zdjęciu). Osoby żyjące możesz pokazać w pełni, tylko z imieniem i nazwiskiem albo pominąć. Drukujesz albo zapisujesz jako PDF.
- **Wklej wynik z Geneteki.** W panelu osoby („🔎 Gdzie szukać dalej” → „📋 Wklej wynik z Geneteki”) wklejasz skopiowany wiersz – albo **kilka naraz**, np. wszystkie dzieci pary znalezione w Genetece. Program po imionach rodziców rozpozna, czy akt dotyczy tej osoby, jej **dziecka** czy **rodzeństwa**: istniejącym dopisze fakt i **źródło** (numer aktu, rok, parafia), brakujących **doda do drzewa**; przy ślubie doda małżonka i jego rodziców. Imiona porównuje także w dawnych zapisach (Maryanna = Marianna, Joannes = Jan), a gdy rodzice w akcie różnią się od tych w drzewie – ostrzeże. Niczego nie nadpisuje ani nie dubluje; każdą zmianę da się cofnąć.
- **Groby do odwiedzenia (na Wszystkich Świętych).** „Raporty” w panelu osoby → „🪦 Groby do odwiedzenia”: groby przodków lub potomków (z małżonkami) według cmentarzy – z kwaterą, rzędem i numerem. Do druku albo do wysłania: **„📋 Kopiuj listę z linkami”** (wklejasz w Messengerze, WhatsAppie, SMS-ie) i **„✉ Wyślij e-mailem”**. Linki otwierają w telefonie mapę cmentarza, a przy grobie ze współrzędnymi – nawigację prosto do niego.
- **Grób i cmentarz.** W zdarzeniu **„Pochówek”** wpiszesz cmentarz, położenie grobu (kwatera, rząd, numer) i **współrzędne grobu** (wklejone z Google Maps albo z telefonu). W panelu osoby link **„📍 grób na mapie”**, w książce rodu – cmentarz, grób i współrzędne.
- **Szukaj grobu.** U osób zmarłych sekcja **„🪦 Szukaj grobu”**: Grobonet (ponad tysiąc polskich cmentarzy; województwo program dobiera z miejsca pochówku) Find a Grave (groby z całego świata, przydatne przy emigracji) i BillionGraves – zdjęcia nagrobków z położeniem GPS, przeszukiwane przez FamilySearch (darmowe konto). U kobiet zamężnych także wyszukiwanie po nazwisku męża.
- **Wskaż miejsce na mapie.** Miejscowości, których mapa nie umie umieścić (kilka wsi o tej samej nazwie, np. „Wola”, albo przysiółek, którego nie ma w bazie), pokażesz sam: w zakładce **Mapa** kliknij „… bez dokładnego miejsca”, a przy nazwie **„📍 Wskaż”**. Program podpowie miejscowości o tej nazwie – najbliższe Twoim pozostałym miejscom na górze – albo kliknij dowolny punkt na mapie. Źle umieszczone miejsce poprawisz przyciskiem **„📍 Popraw położenie”** w liście zdarzeń miejsca. Każdą zmianę można cofnąć (↶).
- Wskazane punkty trafiają do eksportu GEDCOM (standardowe współrzędne miejsca), a przy imporcie program odczytuje współrzędne zapisane przez inne programy.
- **Słowniczek metrykalny.** Menu ⋯ → „📖 Słowniczek metrykalny”: ok. 230 słów z akt po łacinie, rosyjsku i niemiecku (stan, zawody, przyczyny zgonu, pokrewieństwo, miesiące – także „7bris” = wrzesień) z polskim znaczeniem. Gdy w notatce przy fakcie są takie słowa, panel pokazuje przycisk „📖 łacina w notatce” z ich tłumaczeniem. Działa bez internetu.
- **Dziennik poszukiwań.** W panelu osoby „📓 Dziennik poszukiwań”: zapisujesz, gdzie już szukałeś (archiwum, księga, lata), z jakim skutkiem i co jest jeszcze do sprawdzenia (⏳ / ✓ / ✗) – żeby nie przeglądać tych samych ksiąg drugi raz. Przy podpowiedziach „Gdzie szukać dalej” przycisk 📓 od razu tworzy wpis. Dziennik nie trafia na stronę dla rodziny, a u osób żyjących jest ukryty (jak „Gdzie szukać dalej”).
- **Nowe rodzaje faktów:** pierwsza komunia, bierzmowanie, wykształcenie, ukończenie szkoły, spis ludności, służba wojskowa, wyznanie, adopcja, święcenia, testament, emerytura. Fakty tego rodzaju z plików GEDCOM (np. z Ancestry), dotąd niewidoczne w programie, pokażą się same po aktualizacji.
- Przycisk raportów w panelu osoby ma nową ikonę (dokument) i podpis **„Raporty”** – tam są karta osoby, przodkowie, potomkowie, książka rodu i groby do odwiedzenia.
- **Szybsze zapisywanie w dużych drzewach.** Przy 30 000 osób zapis zmiany trwa ok. pół sekundy zamiast dwóch – program sprawdza poprawność dat tylko u zmienianych osób i ich rodzin, a nie w całym drzewie.
- **Unieważnione klucze licencyjne.** Klucz udostępniony publicznie albo licencja, za którą zwrócono pieniądze, może zostać unieważniona: program pobiera listę unieważnionych kluczy razem z informacją o aktualizacjach (same skróty kluczy, bez danych osobowych). Z unieważnionym kluczem program działa dalej jako wersja darmowa – drzewa i dane zostają nienaruszone. Nowa wersja umowy licencyjnej (1.6) to opisuje; program poprosi o jej akceptację.
- **Poprawka: „Zapisz obrót na stałe” działa w zainstalowanym programie.** Wcześniej obracanie zdjęć kończyło się komunikatem o braku pakietu Pillow; teraz obraca samo okno programu (oznaczenia twarzy i kadr zdjęcia profilowego obracają się razem ze zdjęciem, da się cofnąć ↶).
- **Poprawka: długie i wieloliniowe notatki w plikach GEDCOM.** Przy wczytywaniu długie notatki i opisy źródeł (np. z Ancestry) były ucinane po ok. 250 znakach, a przy zapisie notatka z kilkoma liniami psuła plik. Teraz przechodzą w całości.
- **Poprawka: raport „Karta osoby” drukuje się także dla osób ze zdjęciem profilowym** (wcześniej nic się nie działo).

## v0.33 (17.10.2026)

- **Nowa strona programu: https://gentree.com.pl** – opis wersji, cennik, wersja w przeglądarce i grupa „Szukam przodków” na Facebooku.
- **Nowy adres kontaktowy: kontakt@gentree.com.pl** – w programie (zakup licencji, „O programie”) i na stronie.
- Nowa wersja umowy licencyjnej (1.5) – nowe dane kontaktowe i dane licencjodawcy; program poprosi o jej akceptację.

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
