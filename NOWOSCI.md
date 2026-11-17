# Co nowego w Gentree

## v0.52 (17.11.2026)

- **Twarze na zdjęciach wykrywane od razu:** po otwarciu zdjęcia program sam zaznacza znalezione twarze żółtymi ramkami „kto to?”; kliknij ramkę i wybierz osobę. Wykrywanie jest częścią programu: działa bez internetu i bez zgody, nie liczy wzorców twarzy i niczego nie zapisuje. Bardzo duże skany (ponad 200 MP) są pomijane.
- **Rozpoznawanie twarzy, także w wersji bezpłatnej:** Archiwum zdjęć → „🙂 Twarze” podpowiada przy ramce „Imię Nazwisko?” z ✓ i ✕ na podstawie osób już oznaczonych na innych zdjęciach (kolor ramki to pewność). Przy pierwszym użyciu program pyta o zgodę i jednorazowo pobiera jeden model (ok. 37 MB); wzorce twarzy zostają na Twoim komputerze, zdjęcia nigdzie nie są wysyłane. „Kto to? (N)” w Archiwum zbiera nieoznaczone twarze w grupy podobnych, które nazywasz jednym kliknięciem; każda grupa ma „↶ Cofnij”, a Ctrl+Z w oknie cofa ostatnią decyzję. „Szukaj ponownie” w oknie zdjęcia i w Archiwum przegląda zdjęcia jeszcze raz (oznaczenia i odrzucone podpowiedzi zostają). Rozpoznawanie działa też, gdy w ścieżce do folderu są polskie litery.
- **Kilka ramek jednej osoby na zdjęciu:** np. na arkuszu zdjęć paszportowych albo na dokumencie z twarzą i podpisem. Rodzaj ramki program ustala sam (na zdjęciu twarz, na dokumencie podpis), a w oknie zdjęcia przy osobie jest licznik „×N” z listą ramek, „☆ profilowe” i „Usuń”.
- **Koloruj według:** w Drzewie lewa kolumna ma zakładki „Gałęzie | Koloruj” (także menu ⋯ → „Koloruj według…”), a w Wachlarzu pole „Koloruj według”. Karty i wycinki dostają kolor według wyznania, regionu urodzenia, stulecia urodzenia, długości życia, zawodu, kompletności danych, pewności źródeł, linii dziadków, „żyje / zmarł” albo nazwiska. Legenda liczy całą gałąź („W widoku: 368 z 1405 osób”). Wyznanie program bierze z faktu „Wyznanie”, a bez niego zgaduje z opisu chrztu (np. „gr.-kat.”) i pokazuje to kreskowaniem; w danych nic się nie zmienia.
- **Kolor osoby:** w oknie edycji osoby przycisk „kolor” obok „🕘 Historia zmian” (w oknach dodawania pole „Kolor”) z 8 kolorami: czerwony, żółty, zielony, niebieski, fioletowy, różowy, czarny i turkusowy, albo „brak”. Karta tej osoby w Drzewie ma obwódkę w tym kolorze, np. żeby wyróżnić linię, której szukasz. Kolor trafia do pliku GEDCOM i wraca z niego, a zmianę cofniesz ↶.
- **Koniec linii:** pod kartą osoby oznaczonej „zmarł(a) bezdzietnie” albo zmarłej na pewno przed 14. rokiem życia, bez dzieci w drzewie, Drzewo rysuje znak ⊥, więc widać, że tej linii nie trzeba szukać dalej.
- **Skąd pochodzę:** zakładka Wachlarz ma przełącznik „Wachlarz | Skąd pochodzę”. Półkole pokazuje w procentach, skąd pochodzą przodkowie osoby głównej (z miejsc urodzenia), z listą, mapą i poziomem „Kraj / Region / Miejscowość”; liczysz najdalszych znanych przodków albo wybrane pokolenie (do prapradziadków). „Karta dla rodziny (PNG)” i „Drukuj / PDF” dają gotowy obrazek do wysłania.
- **Pewność powiązania dziecko–rodzic:** „✎ powiązanie z rodzicami” na karcie dziecka ustawia osobno dla ojca i matki „pewne”, „prawdopodobne” albo „hipoteza”, z uzasadnieniem. Hipoteza to kropkowana linia w Drzewie, Wachlarzu i wydruku, a w raportach i książce dopisek „(hipoteza)”. Pewność trafia do pliku GEDCOM i wraca z niego.
- **Film, którego nie da się odtworzyć:** pod odtwarzaczem komunikat mówi, co zrobić, zależnie od przyczyny: Windows w wersji N (Media Feature Pack), film z telefonu w HEVC (Rozszerzenia wideo HEVC) albo sterownik karty graficznej; także na stronie dla rodziny.
- **Zdjęcia drzew wczytanych z GEDCOM przed tą wersją:** przy pierwszym otwarciu program raz poprawia typy plików: skany aktów przestają być zdjęciami profilowymi, a materiały bez pliku są oznaczone „BRAK PLIKU” (do uzupełnienia przez „📎 Dopasuj pliki”). Przed zmianą zapisuje kopię drzewa, a całość cofniesz jednym ↶. Nowe importy od razu rozpoznają skany aktów, a wybór „Zdjęcie | Dokument” zapisuje się przy materiale.
- **Połączenie z Claude także w wersji bezpłatnej:** umowa licencyjna i opis „Gentree i Claude” mówią teraz wprost, że do połączenia (MCP) nie trzeba licencji; obowiązuje limit osób Twojej wersji.
- **Drobne poprawki:** zdjęcie podpięte do osoby tylko ramkami znika z jej materiałów razem z ostatnią ramką; liczby mają poprawną odmianę („Drzewo ma 1 osobę”, „202 osoby”).
- Poprawki bezpieczeństwa i ochrony danych.

## v0.51.1 (16.11.2026)

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

## v0.51 (16.11.2026)

- **Menu prawego przycisku myszy w oknie programu:** w polach tekstowych (np. tłumaczenie aktu, notatka) prawy przycisk pokazuje „Wytnij”, „Kopiuj”, „Wklej”, „Wklej jako zwykły tekst”, „Zaznacz wszystko” i podpowiedzi pisowni, a poza polami „Kopiuj” dla zaznaczonego tekstu. Własne menu programu (np. przy strzałkach historii) działają jak dotąd.
- **Druga dawna mapa tej samej wsi:** w Domach (tryb „Dawna mapa”) wiersz „Mapy tej wsi” z każdą mapą jako przyciskiem z rokiem i rodzajem (np. „1852 · brulion”, „1854 · czystopis”) i przyciskiem „+ Dawna mapa”. Czystopis tych samych arkuszy co ułożony już brulion (albo odwrotnie) przejmuje oznaczenia W.C., pola siatki i wpasowanie w dzisiejszą mapę, więc zostaje tylko wczytać skany i je sprawdzić; domy zaznaczasz na nowej mapie osobno.
- **Widok 3D dawnej mapy:** arkusze leżą dokładnie na terenie, więc na zboczach dzisiejsze zdjęcie lotnicze nie prześwituje już przez starą mapę (także w prezentacji wsi).
- **Widok 3D w oknie mapy pokazuje wykryte zabudowania** (stodoły, obory z żółtych plam na arkuszach); „Pokaż wykryte zabudowania” włącza je i wyłącza od razu.
- **Ostre dawne mapy przy przybliżeniu:** program doczytuje szczegóły z oryginalnego skanu, więc w zakładkach „Arkusze”, „Dopasowanie”, „Domy” i „Na mapie” widać numery domów i działek.
- **Okno dawnej mapy:** zniknął drugi, martwy suwak „Stara mapa” (przebijał z zakładki Domy); Esc nie zamyka już okna (cofa tylko to, co w toku), zamyka je ✕, a po odświeżeniu (F5) program wraca do arkusza, na którym pracowałeś.
- **Przybliżanie przy dopasowaniu ramki dawnej mapy:** przy przycinaniu skanu (i w „Popraw ramkę”) skan przybliżysz kółkiem myszy albo gestem szczypania wokół kursora, przyciskami +, − i „Dopasuj do okna” w rogu; widok przesuniesz, przeciągając skan (także wewnątrz ramki) albo ze spacją; całą ramkę przesuwa Shift + przeciąganie. Uchwyty ramki mają zawsze tę samą wielkość, więc narożnik trafisz co do piksela; samo przybliżenie niczego nie zmienia. W „Dopasowaniu” obie mapy mają też przycisk „Dopasuj do okna”.
- **Obrót mapy (krzywy skan dawnej mapy wyprostujesz):** przy przycinaniu skanu (i w „Popraw ramkę”) przyciski ↺ / ↻ 0,5° (z Shiftem 0,1°) albo uchwyt ↻ nad ramką i strefy tuż za narożnikami ramki (przeciąganie jak w programach graficznych, z Shiftem 10× wolniej, Esc cofa) obracają sam skan pod prostą ramką, z siatką pomocniczą i wskaźnikiem kąta; rogi rysunku nie są obcinane; „Wyprostuj automatycznie” proponuje kąt z linii mapy, „wyzeruj” wraca do skanu jak wczytano. Oryginalny skan zostaje bez zmian, a przy arkuszu ułożonym już pod domami lub punktami program najpierw pyta.
- **Jedna kolejność przycisków decyzji w całym programie:** przy propozycji (fakt lub osoba od asystenta AI, podpowiedź na mapie, wyprostowanie skanu) „✓ Potwierdź” jest po lewej i wyróżnione, „Odrzuć” po prawej; w pytaniach o własny krok powrót („Anuluj”, „Popraw”) po lewej, akcja po prawej, także w „Sprawdź, zanim zapiszesz” („Popraw” | „Zapisz mimo to”).
- **Układanie arkuszy:** Shift + strzałki przesuwa arkusz o pół piksela, Ctrl + strzałki szybciej.
- **Drzewo ponad limit osób licencji:** gdy drzewo jest tylko do podglądu, przyciski edycji są wyszarzone, a formularze (osoba, krewni, materiały, dawne mapy, gałęzie) od razu mówią dlaczego i mają przyciski „Wpisz klucz” i „Kup licencję”. Każda odrzucona zmiana otwiera okno z wyjaśnieniem zamiast krótkiego komunikatu na dole ekranu. Usuwanie i scalanie osób oraz cofanie zmian działają jak dotąd.
- **Licznik osób wersji darmowej:** od 150 osób na górnym pasku widać przycisk „Kup licencję · 162/200” (licznik obejmuje wszystkie drzewa i zmienia się po każdym dodaniu, usunięciu i imporcie); otwiera cennik w przeglądarce. Z licencją przycisku nie ma. Menu ⋯ i Ustawienia → Licencja zawsze prowadzą do sklepu, a w Ustawieniach jest opis, jak kupić klucz i gdzie go wpisać.
- **Kolory do wyboru:** Ustawienia → Program → „Wygląd” → „Kolory”: zielony (jak dotąd), granat, wino albo grafit, każdy w jasnym i ciemnym motywie; tam też „Kształt” – obecny albo lekko zaokrąglony (5 px). Zmianę widać od razu.
- **Historia zmian osoby – przycisk w oknie edycji:** „🕘 Historia zmian” obok ✕ w oknie edycji osoby otwiera osobne okno z tym, co i kiedy zmieniono (np. „Narodziny – data: 1850 → 1851”), od najnowszych; formularz zostaje otwarty z tym, co już wpisałeś. Zmiany asystenta AI mają znaczek „✨ AI”, cofnięcia ↶ też są zapisane, a import pliku to jeden wpis na osobę. Tylko do podglądu, historia zbierana od tej wersji. Asystent AI połączony z Gentree odczyta ją narzędziem „person_history”.
- **Mniejszy plik drzewa przy wielu zmianach asystenta AI:** stare kroki historii czekających faktów od AI nie trzymają już całych kopii danych osoby, a po otwarciu drzewa program oddaje zwolnione miejsce na dysku. Fakty dalej czekają na „Potwierdź” / „Odrzuć”, ↶ / ↷ działają jak dotąd.
- **Szukanie mężatki po nazwisku męża:** wpisanie „Anna Nowak” znajduje też Annę Kowalską, żonę Jana Nowaka, z dopiskiem „(po mężu Nowak)”, bez dopisywania innego zapisu nazwiska. Działa przy każdym małżeństwie i w żeńskiej formie (żona Kowalskiego jako Kowalska, Czarnego jako Czarna, Długiego jako Długa), w górnej szukajce, przy wyborze osoby w formularzach i w asystencie AI. Osoby o tym nazwisku z urodzenia są na liście wyżej.
- **Przywróć kopię zapasową:** Ustawienia → Eksport i dane (albo menu ⋯) pokazuje wszystkie kopie otwartego drzewa: kopie zapasowe oraz te, które program robi sam przed zastąpieniem plikiem .ged i przed aktualizacją, z datą, liczbą osób i rozmiarem. Wybraną kopię przywrócisz jednym kliknięciem, a program najpierw zapisuje obecny stan jako kopię, więc przywrócenie też można cofnąć. Zdjęcia i skany zostają w folderze drzewa.
- **Źródła jako osobne rekordy:** nowa zakładka „Źródła” z listą ksiąg, indeksów i dokumentów, ich cytatami (akt, strona, skan) i osobami, których dotyczą. Przy każdym fakcie „+ Źródło z listy” wybiera źródło albo tworzy nowe (parafia, lata, archiwum, sygnatura, własne pola), a numer aktu i skan wpisujesz w cytacie. W kafelku ślubu dopiszesz też źródło dotyczące całej pary (np. spis ludności) i źródło rozwodu, a w danych osoby źródło całej osoby i jej imienia i nazwiska; wszystkie widać w Faktach w karcie osoby. Dotychczasowe teksty źródeł zostają przy faktach, a „Źródła → Do uporządkowania” proponuje z nich źródła i cytaty do potwierdzenia jednym kliknięciem („✓ Potwierdź”, można cofnąć). „Wpisz akt” i wklejka z Geneteki od razu tworzą źródło z cytatem. Źródła z plików .ged innych programów (MyHeritage, RootsMagic, Gramps i innych) wczytują się i wracają w eksporcie bez strat; w kopii dla rodziny nie ma źródeł osób żyjących. Asystent AI odczyta źródła narzędziami list_sources, get_source i source_proposals. Przy pierwszym otwarciu drzewa program zapisuje jego kopię obok.
- **Okno „Pokrewieństwo”:** menu ⋯ → „⇄ Pokrewieństwo…” albo w karcie osoby „⇄ Pokrewieństwo z…”. Obie osoby wybierasz wyszukiwarką, a drzewo zostaje na miejscu. Program pokazuje wszystkie znane ścieżki, najpierw pokrewieństwo, potem powinowactwo, od najbliższej, z przełącznikiem ◀ ścieżka 1 z N ▶: każdą parę wspólnych przodków osobno (także podwójne pokrewieństwo, np. kuzyn po ojcu i po matce, oraz małżeństwa krewnych), a także powinowactwo (małżonek, szwagier, teść, żona kuzyna). Przy każdej ścieżce opis („wspólni przodkowie: …”) i rysunek pokoleń od wspólnych przodków do obu osób, z każdym pokoleniem obu linii na jednej wysokości; „Pokaż w drzewie” rozwija tylko gałęzie tej ścieżki i zaznacza jej osoby. Przy dalekich krewnych rysunek zwija środek ścieżki („… 6 pokoleń …”, rozwijane kliknięciem), a okno można powiększyć na cały ekran. Okno pamięta ostatnią parę osób. Dotychczasowy opis pokrewieństwa w karcie osoby działa jak wcześniej.
- **Ścieżka pokrewieństwa przy zapętlonym rodowodzie:** gdy ten sam przodek jest po ojcu dalej, a po matce bliżej (np. po małżeństwie krewnych), opis w karcie osoby idzie bliższą linią: brat matki to „wuj”, a nie „stryj”, a narysowana ścieżka dochodzi do wspólnego przodka.
- **Więcej z plików GEDCOM widać w programie:** przyczyna zgonu („przyczyna: suchoty”) i wiek podany w akcie („lat 45 (wg aktu)”, także wiek młodych przy ślubie), nowe rodzaje faktów (kremacja, narodowość, wygląd, majątek, spadek, tytuł, cecha z wartością, np. „Wzrost: 172 cm”, bar i bat micwa, błogosławieństwo, chrzest dorosłego) oraz fakty pary: zaręczyny, zapowiedzi, intercyza, zezwolenie na ślub, umowa przedślubna, pozew rozwodowy, unieważnienie, wspólne zamieszkanie i spis. Fakt pary widać u obojga małżonków, a w edycji osoby wpisujesz go jak zwykły fakt. Dane z wcześniej wczytanych plików program przenosi sam przy pierwszym otwarciu drzewa (wcześniej zapisuje kopię drzewa), a eksport GEDCOM zapisuje je raz, bez powtórzeń.
- **Raport po wczytaniu GEDCOM** podaje, jaki program zapisał plik, jego autora i układ nazw miejsc.
- **Rodzaj ślubu:** przy ślubie widać „Ślub kościelny” albo „Ślub cywilny” (lub własny opis z pliku GEDCOM), a rodzaj ustawisz w kafelku ślubu. Źródła faktów pary (zaręczyny, zapowiedzi, spis i inne) są rekordami źródeł jak przy pozostałych faktach. Zmiana roli osoby przy fakcie (np. chrzestny → świadek), zmiana przyczyny zgonu i połączenie dwóch rodzin tej samej pary nie gubią już źródeł zapisanych przy nich. Zastrzeżenia (RESN) z plików innych programów program zachowuje i zapisuje z powrotem w eksporcie.
- **Inna pisownia imion i nazwiska:** przycisk „Aa+” w polach Imiona i Nazwisko dodaje pod nimi zapis cyrylicą, po angielsku albo po łacinie z metryki (liczba przy przycisku, np. „Aa 2”). Pisownie z plików GEDCOM (ROMN, FONE, imię zapisane cyrylicą) pojawiają się tam same i wracają w eksporcie. Link „+ inne nazwisko” służy teraz do nazwisk panieńskich, po mężu, zakonnych i przybranych.
- **Jedno wyszukiwanie osób w całym programie:** górna szukajka, „Pokrewieństwo”, wybór rodzica, małżonka i osoby w roli, oznaczanie na zdjęciach, archiwum i filtry mapy znajdują osobę po każdym imieniu, nazwisku rodowym i innym, pisowni, pseudonimie, nazwisku męża i bez polskich liter („Lukasz” znajduje „Łukasz”), z dopiskiem, czemu pasuje, np. „(pisownia: Иванов)”.
- **Rozwiń tylko przodków:** nowy przycisk na pasku obok „Rozwiń wszystko” pokazuje w drzewie całą linię przodków wybranej osoby, aż do najstarszego pokolenia, bez rodzeństwa i bocznych gałęzi, dopasowaną do okna. „Domyślny zakres” wraca do zwykłego widoku. Na wąskim ekranie przycisk jest w menu ⋯.
- **Związki i więzi dzieci:** okno „Związek” opisuje parę, także parę bez ślubu, a przy dziecku zaznaczysz adopcję albo rodzinę zastępczą.
- **Ramki osób na zdjęciach zapisują się od razu**, a komunikat po zmianie ma „↶ Cofnij”.
- **Formularze bez przeskakiwania:** przy wpisywaniu okno i pole nie przeskakują.
- **Archiwum na pasku:** przycisk „Archiwum” stoi w zakładkach zaraz po „Źródła” i otwiera Archiwum zdjęć całego drzewa (także Alt+A); na telefonie „Archiwum zdjęć” jest w menu ☰.
- Wewnętrzne zabezpieczenia i poprawki.

## v0.50 (14.11.2026)

Przed pierwszym uruchomieniem program zapisuje kopię drzewa obok niego (plik tree.przed-v0.50.db w folderze drzewa).

### Nowości

- **Gentree po angielsku.** Przycisk EN / PL w górnym pasku przełącza cały program, także Ustawienia i komunikaty.
- **Jedno okno zdjęcia i skanu.** Obraz po lewej, opis, odczyt z tłumaczeniem, osoby i akt po prawej; między materiałami przechodzisz strzałkami albo miniaturami.
- **Wpisz akt.** Przy skanie wybierasz typ (urodzenie, ślub, zgon), oznaczasz osoby w ich rolach, a program pokazuje, co dopisze do drzewa, i zapisuje wszystko jednym krokiem. Także kilka aktów na jednym skanie.
- **Podpowiedzi z drzewa.** Program proponuje osoby do pustych ról w akcie (np. rodziców), Ty tylko potwierdzasz.
- **Odczyt z AI.** Po wybraniu typu aktu „Odczytaj z AI” odczytuje cały akt; bez typu odczytasz i przetłumaczysz zaznaczony fragment. Odczyt zlecisz też asystentowi Claude połączonemu z Gentree.
- **Nic nie zmienia się bez Twojej decyzji.** W oknie skanu zmiany czekają na „Zapisz”; do wyboru „Zapisz”, „Zapisz i następny” albo „Zapisz i zamknij”, a „Odrzuć zmiany” zostawia wszystko jak było.
- **Prywatność przy AI.** AI widzi dokumenty i zdjęcia sprzed ponad 105 lat; nowsze albo bez daty tylko wtedy, gdy są na nich oznaczone wyłącznie osoby zmarłe.
- **Pewność faktów.** Każdy fakt oznaczysz jako potwierdzony źródłem, pewny, prawdopodobny albo hipotezę; lista „Hipotezy do sprawdzenia”.
- **Fakty dodane przez Claude** są oznaczone, dopóki ich nie potwierdzisz albo nie odrzucisz.
- **Wstecz i naprzód** między oglądanymi osobami i lista „Ostatnio oglądane”.
- **Skan aktu obok edycji osoby.** „📄 Dokumenty” pokazuje skan przybliżony do osoby, z opisem, odczytem i tłumaczeniem; jednym kliknięciem przypniesz go do faktu.
- **Udział w akcie na osi czasu:** chrzestny czy świadek widzi u siebie „Chrzestny dziecka: …”, „Świadek ślubu: …” z klikalnymi osobami.
- **Historia zmian:** do cofnięcia 100 ostatnich zmian, zmiany Claude wyróżnione.
- **Dodawanie osoby:** przy narodzinach i śmierci od razu notatka, źródło, skan i pewność.
- **Okna:** zamykasz je ✕ w prawym górnym rogu, a przy niezapisanych zmianach jest „Odrzuć zmiany”.
- **Jasny motyw czytelniejszy:** daty, miejsca i notatki przy faktach czarne zamiast szarych.
- **Claude także w wersji darmowej**, a klucz API Anthropic wpiszesz w Ustawieniach.
- **Dawne mapy w zakładce Domy** i łatwiejsze układanie map katastralnych; nowy podkład dzisiejszej mapy, szybszy teren w widoku 3D, rozjazd punktów dopasowania widoczny przy każdym przybliżeniu.
- **Wygodniejsze formularze.** Enter przechodzi do następnego pola, Ctrl+Enter zapisuje; przy edycji osoby „Zapisz” i „Zapisz i zamknij”.
- **Przeciąganie plików:** osobne pola „Zdjęcie” i „Dokument / skan aktu”.
- **Druk ścieżki pokrewieństwa** (Drukuj / PDF i PNG).
- **GEDCOM:** eksport zapisuje pewność faktów oraz chrzestnych i świadków.

### Poprawki

- **Import GEDCOM:** plik bez żadnej osoby nie zastępuje drzewa pustym.
- **Eksport GEDCOM i paczka .zip zachowują wszystko przy zdjęciach i skanach:** oznaczenia osób z ich rolami, datę zdjęcia, miejsce przechowywania oryginału i wpisany akt.
- **Zapis osoby zmienia tylko to, co zmieniłeś.** Daty i śluby, których nie ruszałeś, zostają w bazie i w historii zmian tak, jak były, a opis służby wojskowej, ukończenia szkoły czy emigracji nie znika przy zapisie.
- **GEDCOM:** adres grobu z samym cmentarzem wraca po eksporcie i imporcie bez zmian.
- **Okno edycji osoby pokazuje fakty w kolejności życia:** od narodzin do pochówku, jak w panelu osoby.
- **Okno skanu:** kliknięcie w nazwisko oznaczonej osoby otwiera jej kartę, najechanie pokazuje ją na skanie.
- **Esc zamyka menu ⋯ i okno dawnych map**, tak jak każde inne okno.
- **Panel osoby:** długie linki i odnośniki do źródeł mieszczą się w panelu.
- **Widok 3D wsi:** na mapach z żółtymi polami program nie stawia już domów na polach; wykryte zabudowania można wyłączyć („Pokaż wykryte zabudowania”).
- **Dawne mapy nie znikają po „Zastąp plikiem .ged”:** dopasowanie, domy i arkusze zostają przy drzewie, a nowa mapa nie nadpisuje plików starej.
- **Mapy katastralne:** arkusz-pasek z brzegu mapy nie rozciąga się na całe pole; ustawisz jego część pola albo zachowasz proporcje ramki.
- **Edycja osoby:** fakt ze źródłem pokazuje „Potwierdzone”, a ręcznie wybrana pewność jest zawsze widoczna.
- **Poprawki:** drobny błąd przy scalaniu duplikatów, podpowiedź daty z pliku nie dubluje wpisanej daty, ✕ w liście do archiwum zamyka bez pytania, czystszy dziennik programu.
- **Poprawki**, w tym bezpieczeństwa.

## v0.43 (10.11.2026)

- **Własne archiwum plików.** Skany i zdjęcia mogą zostać w Twoim folderze, bez kopiowania do Gentree.
- **Gałąź i drzewo kuzyna ze zdjęciami.** Eksport i „Dołącz drzewo kuzyna” przenoszą teraz także zdjęcia i skany.
- **ID osoby w panelu.** Widoczny identyfikator osoby: kliknięcie kopiuje, wyszukiwarka od razu go znajduje.
- **Tekst da się zaznaczyć i skopiować.** Fakty, notatki i opisy skopiujesz jak ze zwykłej strony.
- **Czytelniejsze „Gdzie szukać dalej”.** Stan poszukiwań w serwisach zgadza się z dziennikiem poszukiwań.
- **Lepszy asystent AI.** Połączony z Gentree asystent trafniej podpowiada, gdzie szukać źródeł, i zapisuje zadania w dzienniku poszukiwań.
- **„Do druku” to teraz „Drzewo ilustrowane”.**
- **Druk wachlarza przodków.** Wydruk, PDF i obraz w kilku formatach papieru.
- **Zapis SVG tylko z licencją** (drzewo ilustrowane i wachlarz); PNG i druk bez zmian.
- **Odczyt i tłumaczenie aktu.** Przy skanie zapiszesz tekst aktu i jego tłumaczenie na polski.
- **Odczytuj przy skanie.** Skan i odczyt obok siebie, ze słowniczkiem metrykalnym.
- **Claude odczyta zaznaczony fragment aktu** i przetłumaczy go na polski (z licencją albo na własnym kluczu API Anthropic).
- **Podpowiedź formatów dat** i sprawdzanie daty wykonania zdjęcia.
- **Wygodniejsze okno zdjęcia i skanu**, z osobnymi przyciskami dla dokumentów.
- **Umowa licencyjna 1.10** (nowy punkt o odczycie na własnym kluczu API).

## v0.42 (8.11.2026)

- **Zdjęcia z MyHeritage** wczytują się razem z drzewem, przy właściwych osobach.
- **Zdjęcia z Ancestry i innych programów:** pobrane pliki program sam dopasuje do materiałów.

## v0.41.2 (8.11.2026)

- **Prościej o tym, co widzi AI:** jedno pole „Ukryj przed AI” w oknie zdjęcia.
- **Szybsze okno zdjęcia** przy pierwszym otwarciu.
- **Jaśniejsze podpowiedzi** przy datach z innych programów.

## v0.41.1 (8.11.2026)

- **Wyraźniejsze automatyczne poprawki** w „Brakach w danych”.
- **Opisy zdjęć po kolei**, bez zamykania okna.
- **Twarze na bladych zdjęciach** też są wykrywane.
- **Poprawki** przy oznaczaniu osób i pobieraniu materiałów.

## v0.41 (7.11.2026)

- **Lepsze wklejanie wyników z Geneteki.**
- **Zdjęcia i skany niepubliczne**, niewidoczne dla AI.
- **Sprawdzanie drzewa przy otwieraniu** i propozycja przywrócenia kopii zapasowej.
- **Poprawianie dat i zamienionych małżonków** z plików innych programów, także jednym przyciskiem w drzewie zaimportowanym wcześniej.
- **Umowa licencyjna 1.9** (połączenie z Claude).
- **Poprawki**, w tym bezpieczeństwa.

## v0.40.1 (7.11.2026)

- **Pseudonim, „zmarł bezdzietnie” i inne zapisy nazwiska** także przy dodawaniu osoby.
- **Dłuższe notatki przy faktach.**

## v0.40 (6.11.2026)

- **Claude dodaje i oznacza zdjęcia i skany** oraz poprawia dane w drzewie (każdą zmianę cofniesz).
- **Wiek w panelu osoby.**
- **Przyrodnie rodzeństwo w widoku drzewa.**
- **Lista do kwerendy w archiwum** i **list do archiwum** gotowy do wysłania.
- **Gałęzie bez połączenia z drzewem** na osobnym pasku.
- **Pseudonim, „zmarł bezdzietnie”, inne zapisy nazwiska.**
- **Przypuszczalny rodzic**: hipoteza w drzewie, potwierdzana po znalezieniu aktu.
- **Data z nieczytelną końcówką roku** („189?”).
- **Poprawki** w drzewie i w połączeniu z Claude.

## v0.39.1 (4.11.2026)

- **Poprawki** przy otwieraniu drzew i wczytywaniu plików .ged ze ślubami.

## v0.39 (4.11.2026)

- **Ślub wspólny dla pary**, z aktem, skanem i rozwodem.
- **Claude zna więcej z drzewa**: skany, materiały, śluby.
- **Szybsze drzewa ze zdjęciami** wczytanymi z pliku.
- **Drobne poprawki** wyglądu i podpowiedzi.

## v0.38 (4.11.2026)

- **Nowe okna dodawania krewnego i edycji osoby.**
- **Dodawanie krewnego prosto z karty w drzewie.**
- **Skany aktów przy faktach.**
- **Eksport drzewa razem ze zdjęciami.**
- **Lepsze wczytywanie drzew z innych programów.**
- **Połączenie z Claude Desktop jednym kliknięciem.**
- **Jednolity wygląd programu** i drobne poprawki.

## v0.37 (1.11.2026)

- **Archiwum zdjęć:** wiele zdjęć naraz, Poczekalnia, przybliżone daty, szukanie po latach.
- **Skanery zdjęć i rewersy.**
- **Wykrywanie twarzy**, wyłącznie na Twoim komputerze.
- **Osoby spoza drzewa na zdjęciach.**
- **Rozwód widać w drzewie.**
- **„Nie wiadomo”** przy dodawaniu krewnego.

## v0.36 (1.11.2026)

- **Historia: podgląd i wycofanie jednej zmiany.**
- **Szukaj w Ancestry.**
- **Galeria zdjęć na stronie drzewa.**
- **Lepsza wyszukiwarka** przy wielu osobach o tym samym nazwisku.
- **Umowa licencyjna 1.8.**
- **Wiele poprawek**: licencja, import i eksport GEDCOM, prywatność osób żyjących.

## v0.35.1 (21.10.2026)

- **Poprawka pierwszego uruchomienia** na nowym komputerze.

## v0.35 (20.10.2026)

- **Mapa katastralna wsi** na tle dzisiejszej mapy, z domami przodków.
- **Wieś w 3D i przelot nad nią** jako strona do wysłania rodzinie. Poradnik: https://gentree.com.pl/jak-zrobic-mape-3d/
- **Przeciąganie zdjęć** do osoby.
- **Kopia zapasowa na OneDrive** działa.
- **Lepsza ochrona drzewa i licencji**; umowa licencyjna 1.7.

## v0.34 (17.10.2026)

- **Migracje w czasie** na mapie.
- **Książka rodu do druku.**
- **Wklej wynik z Geneteki.**
- **Groby do odwiedzenia** i **szukanie grobów.**
- **Wskaż miejsce na mapie.**
- **Słowniczek metrykalny.**
- **Dziennik poszukiwań.**
- **Nowe rodzaje faktów.**
- **Szybsze zapisywanie w dużych drzewach** i poprawki; umowa licencyjna 1.6.

## v0.33 (17.10.2026)

- **Nowa strona programu: https://gentree.com.pl** i adres kontakt@gentree.com.pl; umowa licencyjna 1.5.

## v0.32 (17.10.2026)

- **Zdjęcie czy dokument.**
- **Program pamięta motyw.**

## v0.31 (17.10.2026)

- **Nowa mapa** z polskimi nazwami miejscowości; umowa licencyjna 1.4.
- **Żyje / Zmarł(a) / Nie wiadomo** w oknie edycji.

## v0.30 (15.10.2026)

- **Poprawki** mapy na telefonie.

## v0.29 (15.10.2026)

- **Gentree i Claude** (z licencją): rozmowa o drzewie i dopisywanie danych. Szczegóły w [instrukcji](GENTREE-I-CLAUDE.md).
- **Trafniejsze „Gdzie szukać dalej”.**
- **Kopia bazy przed aktualizacją**; umowa licencyjna 1.3.

## v0.28 (15.10.2026)

- **Dowolna liczba drzew w wersji darmowej**, każdy plik GEDCOM się wczyta; umowa licencyjna 1.2.

## v0.27 (15.10.2026)

- **Porządkowanie drzewa:** duplikaty, ujednolicanie miejsc, formy imion, dołączanie drzewa kuzyna.
- **Wpisywanie:** podpowiedzi, źródła przy faktach, podwójne daty z zaboru rosyjskiego.
- **Odkrywanie:** „Gdzie szukać dalej”, tło historyczne, Ciekawostki, Archiwum zdjęć.
- **Druk i eksport:** raporty, eksport gałęzi, automatyczna kopia zapasowa.

## v0.25 (14.10.2026)

- **Mapa zna dużo więcej miejscowości**, działa bez internetu.
- **Ulica i numer domu** przy zdarzeniach.
- **Szukaj w Genetece.**

## v0.24 (14.10.2026)

- **Nowa budowa programu** i poprawka mapy na stronie.

## v0.23 (14.10.2026)

- **Czytelniejsze drzewo, listy i wachlarz.**

## v0.22.1

- **Poprawka** przy usuwaniu osoby głównej.

## v0.22

- Program przeniesiony do nowego kodu; dane przenoszą się automatycznie.

## v0.20 – v0.21

- Instalator zamiast pojedynczego pliku .exe.
