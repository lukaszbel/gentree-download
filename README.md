# Gentree – pobieranie

Najnowsza wersja: **v0.38** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu oraz połączenie z Claude. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** z licencją połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.38 (4.11.2026)

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


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
