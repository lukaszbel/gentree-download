# Gentree – pobieranie

Najnowsza wersja: **v0.52.1** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** także w wersji bezpłatnej połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.52.1 (17.11.2026)

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


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
