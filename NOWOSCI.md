# Co nowego w Gentree

## v0.55 (23.11.2026)

- **🏘 Miejscowości:** nowy widok z kartą każdej miejscowości: nazwy (dawne, niemieckie i inne), części miejscowości, parafie, własne pola i osoby z faktami z tego miejsca. Dla ziem dawnej Galicji program podpowiada jej stan z 1907 roku (powiat, parafia), a ty decydujesz, czy go przyjąć. Z karty ujednolicisz różne zapisy tej samej miejscowości przy faktach, a „Usuń zapis…” czyści pole miejsca tam, gdzie trafił przypadkowy tekst. Miejscowości trafiają do pliku GED i wracają z niego, a Claude połączony z Gentree potrafi je czytać.
- **Położenie miejscowości na mapie:** program lepiej znajduje właściwą miejscowość, także gdy w kraju jest kilka o tej samej nazwie (uwzględnia gminę i powiat).
- **🖨 Drukuj drzewo:** drzewo, które widzisz na ekranie (okienka ze zdjęciami, linie, rozwinięte gałęzie), drukujesz na kilku arkuszach A4 albo A3 do sklejenia w duży plakat (drukarka w prawym górnym rogu drzewa). Wybierasz papier, orientację i wielkość okienek, a program od razu pokazuje, ile arkuszy zajmie wydruk. Całe drzewo zapiszesz też jako obraz PNG (w wersji z licencją także SVG). Osoby żyjące są na wydruku chronione tak jak w reszcie programu.
- **Numery osób:** w „Porównaj i scal” wybierasz, który numer osoby zostaje (domyślnie numer bogatszego wpisu). Program pamięta, że osoba była scalona z inną: drugi numer wpisany w „Szukaj osoby…” pokazuje „scalona z …” i prowadzi do osoby. Numer usuniętej osoby pokazuje, kogo i kiedy usunięto, a „Przywróć” oddaje ją z tym samym numerem i powiązaniami. Przełącznik „Numery osób” w raportach i wydrukach (także w Drukuj drzewo, Drzewie ilustrowanym i Wachlarzu) pokazuje numer przy imieniu i nazwisku, a w „Szukaj osoby…” wystarczą same cyfry.
- **Znajdź duplikaty, wiele naraz:** „Scal zaznaczone” scala wiele par jednym krokiem (z obu osób zostają wszystkie dane, a pary ze sprzecznymi danymi czekają w „Do przejrzenia”) i podaje liczbę wykonanych scaleń. Ta sama osoba wpisana trzy razy i więcej trafia na listę „Grupy”, a „Porównaj i scal grupę” łączy wszystkie kopie naraz. Pary oznaczone „To różne osoby” nie są łączone, także przez łańcuch scaleń. Całość cofniesz jednym ↶.
- **Orientacja papieru:** w Drzewie ilustrowanym i Wachlarzu wybierzesz papier poziomo albo pionowo.
- **Oś faktów z rodziną:** na osi życia obok faktów osoby są narodziny jej dzieci oraz śmierć rodziców, małżonków i dzieci.
- **Pokrewieństwo z małżonkami:** przy osobach na ścieżce pokrewieństwa widać ich małżonków (przy większej liczbie „+N małż.” z listą).
- **📊 Analizy:** doszły cechy Tag, Gałąź, Rok zgonu i Miesiąc zgonu oraz przykład „W których miesiącach umierano”.
- **Wyznanie:** przy fakcie „Wyznanie” lista do wyboru: najpierw wyznania już wpisane w drzewie, potem popularne; można też wpisać własne. Grupy wyznań w „Koloruj” są spójne.
- **Odczyt AI:** Claude odczyta także dokument PDF (wybierasz stronę i fragment). Skan aktu bez daty można odczytać, gdy jest przypięty do faktu osoby zmarłej albo do jej karty, a przy odmowie komunikat mówi, dlaczego i co zrobić.
- **Filmy:** film może mieć do 1 GB (inne pliki do 500 MB), duży plik kopiuje się z widocznym postępem, a film, którego okno nie wyświetli, otworzysz przyciskiem „Otwórz w odtwarzaczu systemu”. Miniatura filmu to klatka z nagrania ze znakiem ▶, a datę nagrania program sam odczytuje z pliku (MP4, MOV).
- **Granice działek:** na dzisiejszej mapie w Domach włącznik „Granice działek (GUGiK)” pokazuje granice działek ewidencyjnych, z bliska także numery.
- **Słowniczek, Imiona:** nowa sekcja ze spisem imion w różnych językach i ich łacińskimi formami z ksiąg metrykalnych, z odmianą.
- **Kto to jest?:** ostrzeżenie o dacie zdjęcia, kolejność wg pokrewieństwa, przycisk „To nie twarz / nie oznaczaj”, podgląd zdjęcia z ramką.
- **Ten sam grób:** „Ten sam grób co…” i „+ Pochowani w tym grobie” szukają w całym drzewie.
- **Losy wojenne i Na tle historii:** w panelu zmarłej osoby wyszukiwanie w archiwum Arolsen, a „Na tle historii” obejmuje także USA, Kanadę, Niemcy, Francję i Wielką Brytanię.
- **Pliki GED:** „Aktualizuj z pliku GED” odświeża adresy zdjęć, które nie zostały jeszcze pobrane (np. wygasłe linki), a pobieranie rusza samo. Puste szablony miejsc z innych programów (zamiast nazwy miejscowości) są przy imporcie pomijane, z informacją w raporcie.
- **Poprawki:** drobne poprawki scalania osób i „Aktualizuj z pliku GED”, edycja osoby nie drży przy dolnej krawędzi okna, menu ⋯ bez podwójnych linii, podpisy pokoleń w Wachlarzu mieszczą się na wydruku, nowa ikona zakładki Domy, mocniejsze ukrywanie osób żyjących przed Claude połączonym z Gentree, liczne poprawki wyglądu.
- Poprawki bezpieczeństwa i ochrony danych.

## v0.54 (22.11.2026)

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

## v0.53 (20.11.2026)

- **Strona do wgrania na hosting:** Archiwum zdjęć działa na wyeksportowanej stronie, także otwartej prosto z dysku. Po eksporcie program wymienia miejsca do sprawdzenia przed wgraniem (tytuły, opisy i notatki, w których pada imię i nazwisko osoby żyjącej) oraz pliki, których nie dołączył. Lepsza ochrona prywatności plików na stronie.
- **Aktualizuj z pliku GED:** drzewo wczytane kiedyś z Ancestry, MyHeritage albo innego programu można uzupełnić świeżym eksportem tego samego drzewa, bez zakładania nowego (menu ⋯ → „Aktualizuj z pliku GED…”, także ⚙ Ustawienia → Drzewa). Program sam znajdzie, co doszło: nowe osoby, fakty, źródła i zdjęcia. Nic nie znika i nic nie zmienia się bez decyzji: „Dodaj nowe i scal wszystko” dopisuje to, czego drzewu brakuje, a „Przejrzyj osoba po osobie” pokazuje każdą różnicę w oknie „W drzewie | Wynik | W pliku”. Wszystko, co dopisano w Gentree (skany, ramki, źródła, notatki, poprawki), zostaje. Data poprawiona u źródła staje się główna, a stara czeka na liście „Do posprzątania”, gdzie o każdej pozycji decydujesz osobno. W oknie plik jest po lewej, drzewo po prawej, w środku „Wynik”; strzałki » « ✕ wybierają, co trafi do drzewa, a Ctrl+Z i Ctrl+Y cofają wybory. Są dwa widoki, „Zwykły” i „GEDCOM”, oraz przełącznik „Tylko konflikty”. Osoby scalone wcześniej w Gentree, kilka par rodziców i nowe związki osób z drzewa też są obsłużone. Cała aktualizacja to jeden krok w Historii, który cofniesz ↶ albo „Wycofaj tę zmianę”; wcześniej program robi kopię drzewa. Claude połączony z Gentree potrafi tę aktualizację podejrzeć i wykonać.
- **Kilka par rodziców:** na karcie osoby „+ Rodzice adopcyjni / zastępczy” dodaje drugą parę (osoby z drzewa albo nowe, z rodzajem więzi), rodzice biologiczni zostają. Gdy w drzewie są tylko rodzice niebiologiczni, jest „+ Rodzice biologiczni”, a „✕ odłącz od tej pary” odpina dziecko od jednej pary. Wszystko cofniesz ↶, a pary trafiają do pliku GED i wracają z niego.
- **Import pliku GED z oknem postępu:** wczytywanie pliku (np. „Utwórz z pliku GED…” w ⚙ Ustawienia → Drzewa) pokazuje etapy i liczby, a „Przerwij” zatrzymuje je bez śladu w drzewie. Po wczytaniu jest podsumowanie, a każdy błąd ma osobne okno z przyczyną i „Co zrobić”. W całym programie nazwa formatu to „plik GED”.
- **Ujednolić miejsca:** wybierasz wzór i warianty, które mają być zamienione na ten wzór (ptaszki, domyślnie tylko prawie identyczne z docelowym); okno liczy też rozwody i inne fakty pary. Znajdź duplikaty: okno scalania wraca do listy duplikatów, a oznaczone „To różne osoby” da się wycofać w Historii.
- **Menu ⋯ w grupach:** pozycje są pogrupowane (Wygląd, Pliki GED, Porządki, O programie). „Do posprzątania po aktualizacji…” nazywa się teraz „Uprzątnij po imporcie GED…”. Z menu zniknęły „Koloruj według…” i „⇄ Pokrewieństwo…” (są w zakładce „Koloruj” i w panelu osoby).
- **Drzewo:** „Rozwiń główną linię” zastępuje „Rozwiń tylko przodków”: przodkowie w górę bez rodzeństwa i wszyscy potomkowie w dół.
- **Okna bez migania:** przejście z okna do okna (np. do następnego materiału, z listy duplikatów do scalania) odbywa się bez zamykania i otwierania. W oknie materiału działają też przyciski myszy „wstecz” i „dalej”.
- **Formularze dodawania jak edycja:** „Dodaj osobę” ma „+ identyfikatory z innych programów” i „+ źródło dotyczące całej osoby”, kolor w zwiniętym „+ kolor osoby”, a przy ✕ rodzica pytanie wymienia dzieci, których to dotyczy. Zapis bez imienia czeka na „Podaj imię” albo zaznaczenie „Czy żyje?”, a program odmawia zapisu sprzecznych lat. Miejsce można wybrać z miejsc już w drzewie, a Karta osoby wylicza fakty chronologicznie.
- **Twarze:** „Potwierdź” twarzy pod ramką tej osoby łączy ją z ramką. W „Kto to?” przycisk „Odrzuć” i „Nie oznaczaj” oraz decyzja „To różne osoby” są krokami Historii, a licznik zgadza się z listą.
- **Domy na dawnej mapie:** ulica przy fakcie osoby nie ukrywa już domu, w polu ulicy „ul. Kościelna” znaczy to samo co „Kościelna”, a szukanie domów rozumie kilka słów.
- **Eksport strony:** uszkodzony plik jest pomijany zamiast przerywać eksport, a materiały przypięte do zmarłych zostają na stronie (ostrożność dotyczy tylko luźnych materiałów).
- **GEDCOM 7:** płeć „inna” (SEX X) zostaje zachowana przy imporcie i eksporcie.
- **Poprawki:** klucz licencji w ⚙ Ustawienia → Licencja aktywuje się Enterem; dodawanie nowych osób w „Aktualizuj z pliku GED” i „Dołącz drzewo kuzyna” nie korzysta już z numerów, do których wisiały odwołania; ✕/Esc zamyka „Ujednolić miejsca” bez pytania; zapis „kto w kim” przy scalaniu osób jest częścią kroku Historii; kolorowanie kart działa po ponownym uruchomieniu; mapa nie zgłasza błędu przy zamknięciu; liczne drobne poprawki wyglądu okien.
- Poprawki bezpieczeństwa i ochrony danych.

## v0.52.1 (17.11.2026)

- **Przywrócone poprawki z 0.51.1:** „Anuluj” w oknie wyboru pliku znowu nie zamyka okna, a „Uzupełnij z pliku GED…” obsługuje pary z kilkoma ślubami. Komunikat startowy o starym imporcie znika po uzupełnieniu, a także od razu, gdy drzewu nic nie brakuje względem pliku. Okno „Uzupełnij z pliku GED…” zamyka się bez pytania, gdy nic w nim nie zmieniono.
- **Wycofanie zmiany koloru, płci albo danych pary:** „Wycofaj tę zmianę” w Historii zmian działa także dla takich zmian. Komunikat „opierają się na niej późniejsze zmiany” pojawia się tylko wtedy, gdy rzeczywiście są późniejsze zmiany tych samych danych.
- **„Program” w historii zmian:** zmiany, które program robi sam (np. porządki materiałów z importu), są oznaczone jako „Program”, a nie jako Twoje, a wpis mówi, co zrobiono („Uporządkowano materiały z importu (N): brak pliku – …, rodzaj pliku – …”).
- **Porządki materiałów z importu tylko po Twojej decyzji:** otwarcie drzewa niczego już nie zmienia. Program pokazuje, ile materiałów można uporządkować, z przyciskami „Uporządkuj” i „Później”; to samo jest w menu ⋯ („Uporządkuj materiały z importu…”). Przed zmianą program robi kopię drzewa, a całość cofniesz jednym ↶.
- **Własne rodzaje dokumentów:** w oknie dokumentu pole „Rodzaj dokumentu” (dawniej „Typ aktu”) ma na końcu „+ Nowy rodzaj dokumentu…” (np. świadectwo szkolne, paszport, książeczka wojskowa). Własne rodzaje są na liście po wbudowanych i działają jak „Inny akt”: przy ramkach wybierasz role osób, a program nie dopisuje z nich faktów. Rodzaj wybierzesz także dla pliku PDF. Link „zarządzaj rodzajami” obok pola zmienia nazwę rodzaju albo go usuwa (dokumenty usuniętego rodzaju dostają „Inny akt”); każdą zmianę cofniesz ↶. Archiwum zdjęć ma filtr „Rodzaj dokumentu” (wbudowane i własne) i szuka po nazwie rodzaju. Rodzaje trafiają do pliku GEDCOM i wracają z niego; nieznane słowo typu z pliku innego programu (np. „Diploma”) staje się własnym rodzajem dokumentu zamiast zginąć, a znane słowa (np. „nagrobek”, „tombstone”) trafiają do właściwego typu.
- **Twarze:** w „Kto to?” przycisk „+ Dodaj do drzewa” tworzy nową osobę i od razu oznacza całą grupę twarzy (cofniesz jednym ↶). Etykieta ramki pokazuje pełne imię i nazwisko, gdy jest miejsce, a najechanie na podpis podświetla ramkę i odwrotnie. Po szukaniu Archiwum podaje, ile zdjęć pominięto (za duże lub nieczytelne), z listą. Obrócone skany TIFF są czytane prosto, a teksty mówią o jednym pobieranym modelu.
- **Koloruj według:** pod wyborem jest opis, co oznacza dana opcja; przy „kompletności danych” podpowiedź mówi, czego brakuje, a kliknięcie poziomu w legendzie otwiera „Braki w danych” z osobami tego poziomu i wszystkimi rodzajami braków.
- **Braki w danych:** nowe filtry „urodzenie bez aktu”, „zgon bez aktu” i „ślub bez aktu” (fakt jest, ale bez skanu i bez linku do skanu), domyślnie wyłączone (włączasz je kliknięciem), a każdy filtr ma podpowiedź z dokładnym znaczeniem.
- **Claude zna nowe funkcje:** asystent połączony z Gentree wyjaśni, jak działają twarze, pewność powiązania z rodzicem, „Skąd pochodzę”, kilka ramek jednej osoby i „Koloruj według”.
- **Role w akcie:** „+ Dodaj rolę ▾” → „Opiekun prawny” i „Inna rola…” dodają wiersz roli jak pozostałe role (przy „Inna rola…” najpierw nazwa roli, np. sąsiad); wcześniej zaczynało się tylko zaznaczanie na skanie i wyglądało, jakby nic się nie stało. Wiersz osoby nie dostaje już zielonej ramki po najechaniu i przy otwartym menu „⋯”.
- **Okno materiału:** przycisk, który zapisuje i przechodzi do następnego materiału, nazywa się „Zapisz i następny” (na ostatnim „Zapisz i pierwszy”), a nie „Zapisz ›”.
- **Prezentacja mapy 3D z Claude** działa bez ręcznego kopiowania plików (program szukał pliku w złym folderze).
- **Puste karty „Dodaj ojca / Dodaj matkę / Dodaj rodziców”** w drzewie mają ten sam rozmiar co karty osób.
- **Ramka z wiersza roli:** „▭” przy roli w akcie zaznacza ramkę na skanie bez dużego dymka – ramka czeka w wierszu, a osobę wpisujesz albo wybierasz w polu tego wiersza. „tylko w akcie ▾” przy osobie rozwija wybór (osoba z drzewa, tylko w akcie).
- **Poprawki okna materiału:** po zamknięciu aktu bez zapisu kolejne materiały znów się zapisują; po „Zapisz i następny” powrót do poprzedniego materiału pokazuje zapisane dane (wcześniej stare, a następny zapis mógł je nadpisać); przy własnym rodzaju dokumentu okno mówi „Dokument” i „Osoby w dokumencie”, a przycisk „Zapisz”; teksty „Odłącz od osoby”, prywatności i błędnej daty pasują do rodzaju materiału; przy PDF zamiast „✨ Odczytaj z AI” jest wyjaśnienie i „✍ Przepiszę sam”; pasek „Zleć odczyt AI” nie chowa się pod ramkami; „Akt zapisany ✓” znika, gdy są nowe niezapisane zmiany; krótsze podpowiedzi pól, lista ról nie zasłania paska ‹ ›, stopka po angielsku mieści się w jednym rzędzie.
- **Okno filmu i nagrania dźwiękowego:** bez „To dokument? Odczyt i akt…”; opis podpowiada „Kto jest na filmie, gdzie i kiedy, skąd pochodzi…”, a pole daty to „Data nagrania”.
- **Osoba wpisana przy roli nie ginie:** imię i nazwisko wpisane w wierszu roli bez Enter zostaje przy dodaniu kolejnej roli, okno pokazuje je jako niezapisane, a „Zapisz” zapisuje taką osobę (jako osobę tylko w akcie).
- **Zmiana rodzaju aktu i Zdjęcie/Dokument bez utraty danych:** osoby wpisane przy rolach przechodzą z rolą do nowego rodzaju, a przełączenie na „Zdjęcie” najpierw pyta. Po „Odrzuć zmiany” okno nie pokazuje już odrzuconego rodzaju. Pytanie przy zamykaniu wymienia wszystko, co nie jest zapisane.
- **PDF, film i nagranie:** pola oryginału i tłumaczenia są od razu widoczne, bez przycisku „✍ Przepiszę sam”.
- **Poprawki okna materiału i twarzy:** podwójne kliknięcie „Dodaj i oznacz” w „Kto to?” tworzy jedną osobę; lista „+ Dodaj rolę ▾” mieści się na ekranie; w węższym oknie nazwiska w rolach są całe; przy własnym rodzaju dokumentu napisy mówią „dokument”, nie „akt”; przy zdjęciu z wycinkiem zdjęcia profilowego komunikat podpowiada ✓ zamiast „Wszystkie twarze są oznaczone”; nowy materiał nie pokazuje miniatury dawno usuniętego; komunikat o porządkach z importu nie zasłania przycisków powiększenia i jaśniej podaje liczby.
- **Drobne poprawki:** napis na pustej karcie „Dodaj matkę” nie wychodzi poza kartę.
- **Kadry zdjęć profilowych** wracają po wczytaniu drzewa z paczki .zip lub pliku .ged (eksport nie zapisywał wymiarów zdjęć).

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
