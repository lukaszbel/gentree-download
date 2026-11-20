# Gentree – pobieranie

Najnowsza wersja: **v0.53** – [Gentree-Setup.exe](https://github.com/lukaszbel/gentree-download/releases/latest/download/Gentree-Setup.exe) (instalator, Windows 10/11).

Za darmo do 200 osób (łącznie we wszystkich drzewach; większe drzewo wczytasz do podglądu). Z licencją: do 2000 osób albo bez limitu. Strona, demo i kontakt: https://gentree.com.pl

**Gentree i Claude:** także w wersji bezpłatnej połączysz program z aplikacją Claude (Claude Desktop, Claude Code) – Claude odpowie na pytania o drzewo i na Twoją prośbę dopisze osoby i fakty. [Instrukcja](GENTREE-I-CLAUDE.md)

Instalator nie wymaga uprawnień administratora. Windows może pokazać ostrzeżenie SmartScreen – kliknij „Więcej informacji” → „Uruchom mimo to”.

Korzystanie z programu wymaga akceptacji [umowy licencyjnej](UMOWA-LICENCYJNA.md) (program pokazuje ją przy pierwszym uruchomieniu).

Znalazłeś błąd albo masz pomysł? [Zgłoś go tutaj](https://github.com/lukaszbel/gentree-download/issues/new/choose) (wymaga konta GitHub; zgłoszenia są publiczne – bez danych osób żyjących).

### Co nowego w v0.53 (20.11.2026)

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


[Wszystkie zmiany w kolejnych wersjach](NOWOSCI.md)
