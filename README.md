# Gentree – pobieranie

Najnowsza wersja: **v0.55** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** także w wersji bezpłatnej połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.55 (23.11.2026)

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


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
