# Gentree – pobieranie

Najnowsza wersja: **v0.37** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu oraz połączenie z Claude. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** z licencją połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.37 (1.11.2026)

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


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
