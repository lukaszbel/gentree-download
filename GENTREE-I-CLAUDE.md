# Gentree i Claude – rozmowa z asystentem AI o Twoim drzewie

Gentree może działać jako **konektor (MCP)** dla aplikacji **Claude** firmy Anthropic – Claude Desktop (zwykła aplikacja
okienkowa) albo Claude Code. Rozmawiasz wtedy z Claude o swoim drzewie na **swoim planie Claude** – bez klucza API
i bez dodatkowych opłat za zapytania.

**Wymagania:** Gentree z **licencją** (dowolną – „do 2000 osób” albo „bez limitu”) i konto Claude.

## Co potrafi Claude z Gentree

- **Odpowiada na pytania o drzewo** – „Kto z moich przodków urodził się w Łukawicy?”, „Opowiedz o rodzinie Jana Kowalskiego”.
- **Wskazuje braki i błędy** – brakujące daty, rodzice za młodzi, zdarzenia w złej kolejności.
- **Dopisuje dane, o które poprosisz** – nowe osoby (dziecko, rodzic, małżonek, rodzeństwo), fakty (chrzest, zawód,
  zamieszkanie, pochówek), datę ślubu – **ze źródłem**, np. wynikiem z Geneteki albo numerem aktu.
- **Odczytuje skany aktów** (po łacinie, polsku, rosyjsku, niemiecku), jeśli wkleisz je do rozmowy w Claude.

## Bezpieczeństwo

- Każda zmiana to **jeden krok w historii** programu – cofniesz ją przyciskiem **↶** w Gentree albo prosząc Claude.
- Claude **pyta o zgodę** przed każdą zmianą (aplikacja Claude pokazuje, co chce zrobić).
- **Osoby żyjące są przed Claude ukryte** – widzi tylko „osoba żyjąca”.
- Obowiązuje limit osób z Twojej licencji i ta sama kontrola dat co w oknach programu.
- Dane drzewa, o które Claude pyta, są przesyłane do Anthropic w ramach Twojej rozmowy z Claude.

## Jak połączyć

Potrzebujesz: Gentree z licencją, aplikację Claude (claude.ai/download) i konto Claude.

1. W Gentree otwórz ⚙ **Ustawienia → Program → Claude (MCP)** i zaznacz **„Pozwól Claude łączyć się z Gentree”**.
2. **Claude Desktop:** w Claude otwórz Ustawienia → Developer → **Edit config** i wklej tekst z Gentree (przycisk
   „Kopiuj”). Jeśli plik ma już inne ustawienia, dodaj tylko sekcję `mcpServers`. Zapisz, a potem **zamknij Claude
   całkowicie** – ikona Claude w zasobniku przy zegarze → **Quit** (samo zamknięcie okna nie wystarczy) – i uruchom go
   ponownie. W Ustawienia → Developer powinien pojawić się serwer „gentree”.
   Uwaga: działający Claude może nadpisać plik konfiguracji – dlatego zmiany zapisuj i od razu restartuj Claude.
   **Claude Code:** wklej w terminalu polecenie z Gentree i uruchom Claude Code ponownie.
3. Zapytaj Claude np. „Ile osób jest w moim drzewie i jakie są najczęstsze nazwiska?”.

Claude działa na **drzewie otwartym w Gentree** – po przełączeniu drzewa w programie kolejne pytania dotyczą nowego.
Otwarty program sam pokazuje zmiany wprowadzone przez Claude.

## Przykład: osoby z Geneteki

> Znalazłem w Genetece: „Ignacy, syn Józefa i Marii z d. Nowak, ur. 3.03.1890, Łukawica, akt 45”.
> Dodaj go do drzewa jako dziecko Józefa Kowalskiego.

Claude sprawdzi, czy Ignacego już nie ma w drzewie, znajdzie Józefa, pokaże, co doda (data, miejsce, źródło
„Geneteka: Łukawica, urodzenia 1890, akt 45”), i po Twojej zgodzie wpisze to do drzewa.
