# Co nowego w Gentree

## v0.39 (4.11.2026)

- **Ślub w oknie edycji, u obojga partnerów.** W „Edycji” osoby jest teraz wiersz „Ślub” z imieniem partnera: data, miejsce, notatka, źródło i skan aktu. Ślub jest zapisany przy parze, więc oboje partnerzy widzą i zmieniają to samo (wcześniej ślub był widoczny tylko u osoby, która miała go zapisanego jako własny fakt). Przycisk „+ Ślub” dodaje ślub z partnerem z drzewa, a przy kilku związkach pozwala wybrać, z kim. Pod ślubem „+ rozwód” zaznacza rozwód z datą i miejscem. Akt ślubu wklejony z Geneteki też trafia do ślubu pary. Śluby zapisane wcześniej tylko u jednego z małżonków program sam przenosi do pary razem ze źródłem i skanem; zostawia je tylko wtedy, gdy rok nie zgadza się ze ślubem pary, żebyś sam zdecydował.
- **Claude zna więcej z drzewa.** Połączony z Gentree Claude widzi skany przypięte do faktów, materiały osoby (skany i zdjęcia) oraz akt ślubu i rozwód przy parze. Może dopisać fakt z adresem i skanem z archiwum, a przy ślubie zapisać akt, skan i rozwód. Ślubu nie zapisuje już jako osobnego faktu jednej osoby, tylko przy parze. Zdjęcia osób żyjących pozostają przed nim ukryte.
- **„Zmarł” albo „Zmarła”.** W oknach dodawania i edycji osoby przycisk statusu odmienia się według wybranej płci („Zmarł(a)” zostaje tylko przy płci nieznanej).
- **„Gdzie szukać dalej” podpowiada też akt ślubu, który jest w drzewie bez źródła,** z wyszukiwaniem wokół roku ślubu.
- **Panel osoby z rozwodem znów się otwiera.** W v0.38 po kliknięciu osoby, która ma w drzewie rozwód, panel z faktami się nie pokazywał, a karta nie dostawała żółtej ramki zaznaczenia.
- **Okno kadrowania zdjęcia bez poziomego paska przewijania,** a ✕ przy oznaczonych osobach na zdjęciu jest szare (czerwone dopiero po najechaniu), jak w całym programie.
- **Szybsze drzewa ze zdjęciami wczytanymi z pliku.** Program sam robi małe podglądy zdjęć i skanów, także dla drzewa wczytanego z pliku .ged lub paczki .zip (wcześniej powstawały tylko przy dodawaniu zdjęcia w oknie, więc takie drzewo ładowało pełne skany: działało wolniej, a miniatury były mniej wyraźne). Po wczytaniu pliku do istniejącego drzewa stare podglądy są usuwane, więc nie pokaże się podgląd innego zdjęcia.

## v0.38 (4.11.2026)

- **Nowe okna dodawania krewnego i edycji osoby.** Pola są podzielone na czytelne sekcje, płeć i „czy żyje” wybiera się przyciskami (płeć także „Nieznana”, a po wpisaniu imienia program sam ją podpowiada), pod datą od razu widać, jak program ją rozumie („✓ około 1900”), a miejsca podpowiadają się z drzewa. Przy partnerze można od razu wpisać datę i miejsce ślubu, przy dziecku program pyta, z którego związku jest, a „Zapisz i dodaj kolejne” pozwala dodać rodzeństwo bez zamykania okna (Ctrl+Enter zapisuje). Wybierając osobę, która już jest w drzewie, widzisz, kogo nie da się dodać i dlaczego (np. przodek jako dziecko). Osoba bez zdjęcia ma w nagłówku sylwetkę zamiast litery.
- **„+” i ✎ na karcie w drzewie.** Zaznaczona karta ma w rogu „+” (menu: rodzic, rodzeństwo, partner, dziecko) i ✎ do edycji danych, więc krewnego dodasz prosto z drzewa.
- **Skany aktów przy faktach.** Pod narodzinami, ślubem czy zgonem „+ Skan z archiwum” przypina skan aktu: z materiałów osoby, z dokumentów w Archiwum zdjęć (z wyszukiwaniem) albo plik z komputera. W panelu osoby przy fakcie pojawia się „📄” z tytułem skanu, który otwiera się jednym kliknięciem, a „Gdzie szukać dalej” liczy taki fakt jako mający akt. Link do skanu w internecie (np. metryki.genealodzy.pl) dalej można wpisać.
- **Eksport drzewa razem ze zdjęciami.** „Eksportuj do pliku .ged” zapisuje teraz także zdjęcia i skany: plik .ged z folderem zdjęć obok albo jedną paczkę .zip (do wyboru w oknie zapisu). Drugi program genealogiczny dostaje zdjęcia przypięte do osób, z tytułami i zdjęciem profilowym, a Gentree wczytuje taką paczkę .zip z powrotem razem ze zdjęciami.
- **Drzewa z innych programów wczytują się lepiej.** Pliki z MyHeritage, Family Tree Builder, Legacy, PAF, Gramps i starszych programów (także w kodowaniach innych niż UTF-8) otwierają się bez błędów, z notatkami osób i faktów oraz ze zdjęciami, jeśli leżą obok pliku. Po wczytaniu program pokazuje krótki raport: ile zdjęć znalazł, czego brakuje i co poprawił w pliku.
- **„Gdzie szukać dalej” mówi jaśniej, czego brakuje,** np. „narodziny są w drzewie, ale bez aktu jako źródła” albo „brak daty ślubu w drzewie”, a przy każdej pozycji widać liczbę znalezionych aktów.
- **Jednolity wygląd programu.** Okna, pola, listy, przełączniki i paski wszystkich widoków (Wachlarz, Druk, Rocznice, Domy, Braki, Mapa, Archiwum zdjęć) wyglądają tak samo; okno zdjęcia ma jeden pasek do przewijania i obracania, a okno mapy katastralnej prowadzi przyciskiem „Dalej”.
- **Claude dopisuje więcej naraz.** Dodając przez Claude małżonka, można od razu podać datę i miejsce ślubu (jedna zmiana w Historii), a przy narodzinach i zgonie także ulicę i numer domu z aktu.
- **Data „około 1900” przyjmowana.** Wpisana w całości („około”, nie tylko „ok.”) dawała komunikat „Nieprawidłowa data”.
- **Jaśniejsze dołączanie drugiego drzewa.** „Dodaj osoby z pliku .ged” nazywa się teraz „Dołącz drzewo kuzyna z pliku .ged” i na górze okna podpowiada, że swoje drzewo z innego programu (Family Tree Builder, MyHeritage, Ancestry) najlepiej wczytać jako nowe drzewo (⚙ Ustawienia → Drzewa → „Utwórz z pliku .ged”). Gdy w pliku nie ma osób z otwartego drzewa, okno mówi wprost, że osoby z pliku dojdą jako osobna gałąź z zachowanymi rodzinami. Wcześniej komunikat „nie znaleziono wspólnych osób” można było zrozumieć tak, jakby w pliku nikt nie był ze sobą połączony.
- **Połączenie z Claude Desktop jednym kliknięciem.** W ⚙ Ustawieniach → Claude (MCP), po włączeniu przełącznika, przycisk „Połącz z Claude Desktop” sam dopisuje Gentree w ustawieniach aplikacji Claude – także w wersji ze sklepu Microsoft, z zachowaniem innych ustawień Claude i kopią poprzedniego pliku. Wystarczy potem zamknąć Claude (ikona przy zegarze → Quit) i uruchomić go ponownie. Program pokazuje, czy połączenie jest już ustawione, a „Odłącz od Claude Desktop” usuwa tylko wpis Gentree. Ręczny sposób (z nową ścieżką w Claude: Ustawienia → Desktop app → Extensions → Edit config) jest pod „Ręcznie”.
- **Zdjęcia przeciągnięte do Poczekalni zostają w Poczekalni.** Plik upuszczony na okno Archiwum zdjęć trafia tam, gdzie „＋ Dodaj”: przy „Ta osoba” do tej osoby, w pozostałych widokach (Poczekalnia, Całe drzewo, gałąź) do Poczekalni. Wcześniej był przypinany do osoby, przy której otwarto archiwum.
- **Import GEDCOM z polskich programów.** Plik, który w nagłówku deklaruje UTF-8, a w rzeczywistości jest zapisany w kodowaniu polskiego Windows, wczytuje się teraz z poprawnymi polskimi literami.

## v0.37 (1.11.2026)

- **Archiwum zdjęć: wiele zdjęć naraz.** „☑ Zaznaczanie” w Archiwum zdjęć pozwala wybrać wiele zdjęć (także z Ctrl i Shift) i jednym ruchem ustawić im datę, pochodzenie (np. „album babci”) albo dodać je do osoby. Zaznaczone zdjęcia można też usunąć.
- **Przybliżone daty zdjęć.** W dacie zdjęcia można wpisać „ok. 1935”, „1930–1935” albo „lata 50.”. Pod datą program podpowiada, z jakich lat może być zdjęcie, na podstawie dat urodzenia i śmierci oznaczonych osób, a „📅 Data z wydarzenia” bierze datę ze ślubu, chrztu czy innego faktu.
- **Poczekalnia.** Zdjęcia dodane bez osoby trafiają do „📥 Poczekalni” obok „Całe drzewo”. Tam spokojnie je przeglądasz i przypisujesz do osób. Odłączenie zdjęcia od ostatniej osoby nie usuwa go już z archiwum, tylko przenosi do Poczekalni.
- **Skaner zdjęć (np. Epson FastFoto) i rewersy.** Przy dodawaniu wielu plików program rozpoznaje pary przód + tył („zdjecie.jpg” i „zdjecie_b.jpg”, „_back”, „_rewers”, „_tył”) i zapisuje tył jako rewers tego samego zdjęcia (przycisk „↻ Rewers”). Rewers można też dodać później albo połączyć dwa osobno dodane zdjęcia („↻ Połącz: przód + rewers”).
- **Wykrywanie twarzy.** Po otwarciu zdjęcia program sam zaznacza znalezione twarze żółtymi ramkami „kto to?” – klikasz ramkę i wybierasz osobę. Twarz, której program nie znalazł, zaznaczysz ręcznie. Wykrywanie działa wyłącznie na Twoim komputerze, nic nie jest wysyłane.
- **Osoby spoza drzewa na zdjęciach.** Sąsiadów, przyjaciół i inne osoby spoza drzewa można podpisać samym imieniem i nazwiskiem; filtr „👥 spoza drzewa” pokazuje te podpisy, a gdy taka osoba trafi do drzewa, „→ w drzewie” przenosi na nią wszystkie jej podpisy naraz.
- **Szukanie zdjęć po roku i dekadzie.** „łukasz 1990” znajduje zdjęcia Łukasza z 1990 roku, przyciski dekad pokazują zdjęcia z danego dziesięciolecia, a „zdjęcia bez oznaczeń” i „👤 bez zdjęcia” pomagają znaleźć, co jeszcze trzeba opisać.
- **Rozwód widać w drzewie.** Para po rozwodzie ma w drzewie przerywaną linię, rozsunięte obrączki i dopisek „rozw.”, a w karcie rodziny i na liście potomków znak ⚮.
- **Dziennik poszukiwań: „szukano”.** Przy brakujących aktach w „Gdzie szukać dalej” obok Geneteki, FamilySearch i Ancestry jest pole do odhaczenia, że już tam szukałeś (z datą, wpis trafia do dziennika poszukiwań). W polu „Gdzie szukano” cała lista źródeł pokazuje się od razu.
- **„Nie wiadomo” przy dodawaniu krewnego.** Oprócz „Żyje” i „Zmarł(a)” można wybrać „Nie wiadomo”. Taka osoba bez dat jest ukryta na stronie rodziny i przed Claude jak żyjąca, dopóki daty nie wskażą, że to dawny przodek.
- **Naprawiony błąd dziennika poszukiwań:** usunięcie wpisu kończyło się komunikatem o błędzie i panel się nie odświeżał.

## v0.36 (1.11.2026)

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
