# Gentree – pobieranie

Najnowsza wersja: **v0.52** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** także w wersji bezpłatnej połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.52 (17.11.2026)

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


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
