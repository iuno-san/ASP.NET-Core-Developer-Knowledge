# ASP.NET-Core-Developer-Knowledge
Znajomość podstaw ASP.NET, dzięki której zostaniesz programistą .NET

<img src="https://raw.githubusercontent.com/iuno-san/ASP.NET-Core-Developer-Knowledge/main/asp.net%20road.png"> 
<hr>


# GIT - System Kontroli Wersji

GIT to system kontroli wersji, który jest szeroko używany w programowaniu do śledzenia zmian w kodzie źródłowym i zarządzania projektem. Pozwala programistom na efektywne współpracowanie nad projektem, śledzenie historii zmian, przywracanie wcześniejszych wersji kodu i wiele innych. Oto kilka podstawowych koncepcji i poleceń związanych z GIT:

## Repozytorium GIT
Repozytorium to miejsce, w którym przechowywany jest cały kod źródłowy i jego historia. Może to być repozytorium na lokalnym komputerze lub zdalnym serwerze (na przykład na platformie GitHub, GitLab lub Bitbucket).

## Polecenie git init
Aby rozpocząć nowy projekt GIT, możesz użyć polecenia `git init`. Tworzy ono lokalne repozytorium w katalogu projektu.

```bash
git init
```

## Polecenie git clone
Jeśli chcesz pobrać istniejące repozytorium z serwera zdalnego, użyj polecenia `git clone`. Na przykład:

```bash
git clone URL-repozytorium
```

## Polecenie git add
Służy do dodawania zmian do indeksu GIT, przygotowując je do zatwierdzenia. Możesz używać go do dodawania pojedynczych plików lub całych katalogów.

```csharp
git add plik.txt
```

## Polecenie git commit
Po dodaniu zmian do indeksu, użyj polecenia `git commit`, aby zatwierdzić te zmiany w historii repozytorium. Podczas commita dodajesz krótki opis wprowadzanych zmian.

```sql
git commit -m "Dodano nową funkcjonalność"
```

## Polecenie git push
Jeśli pracujesz w repozytorium zdalnym, użyj polecenia `git push`, aby wysłać swoje lokalne zmiany na serwer.

```perl
git push
```

## Polecenie git pull
Aby pobrać zmiany z repozytorium zdalnego i zaktualizować swój lokalny kod, użyj polecenia `git pull`.

```bash
git pull
```

## Polecenie git branch
Pozwala na zarządzanie gałęziami (branches) w repozytorium. Możesz tworzyć, usuwać, łączyć i przełączać się między gałęziami.

```bash
git branch nowa-galez
git checkout nowa-galez
```

## Polecenie git merge
Służy do łączenia dwóch gałęzi w jedną. Na przykład, aby połączyć zmiany z gałęzi "nowa-galez" do gałęzi "galez-glowna", użyj:

```sql
git checkout galez-glowna
git merge nowa-galez
```

## Polecenie git status
Pozwala na sprawdzenie stanu repozytorium, tj. jakie zmiany zostały dodane do indeksu i jakie pliki są nieśledzone.

```lua
git status
```

GIT oferuje wiele innych komend i funkcji, które pomagają w zarządzaniu projektem. Jest to niezwykle przydatne narzędzie do śledzenia historii projektu, rozwiązywania konfliktów, pracy w zespołach i utrzymania porządku w kodzie źródłowym. Warto nauczyć się GIT-a, jeśli chcesz być skutecznym programistą.

<hr>
<br><br><br>

# HTTP i HTTPS - Protokoły Komunikacji w Internecie

HTTP (Hypertext Transfer Protocol) i HTTPS (Hypertext Transfer Protocol Secure) są protokołami komunikacji używanymi w internecie do przesyłania danych między przeglądarką internetową a serwerem. Oto krótka charakteryzacja tych protokołów i ich związku z TLS/SSL:

## HTTP (Hypertext Transfer Protocol):

- HTTP to podstawowy protokół używany w internecie do przesyłania żądań i odpowiedzi między klientem (na przykład przeglądarką) a serwerem webowym.
- Jest to protokół tekstowy, co oznacza, że dane przesyłane w ramach HTTP nie są szyfrowane i mogą być odczytane przez osoby trzecie podczas transmisji.

## HTTPS (Hypertext Transfer Protocol Secure):

- HTTPS to zabezpieczona wersja protokołu HTTP, która wykorzystuje protokół TLS/SSL w celu szyfrowania danych między klientem a serwerem.
- Dane przesyłane za pomocą HTTPS są szyfrowane, co zapewnia poufność i integralność danych oraz zabezpiecza przed atakami typu Man-in-the-Middle (MitM).

## TLS (Transport Layer Security) i SSL (Secure Sockets Layer):

- TLS i SSL to protokoły kryptograficzne, które zapewniają bezpieczne połączenia między klientem a serwerem.
- SSL został pierwotnie opracowany jako protokół bezpieczeństwa, ale został zastąpiony przez bardziej zaawansowany TLS.
- TLS działa na wyższym poziomie niż protokoły HTTP i TCP/IP, co oznacza, że może być stosowany do szyfrowania różnych rodzajów komunikacji internetowej, nie tylko przeglądania stron internetowych.

## Dlaczego HTTPS z TLS/SSL jest ważne:

- Szyfrowanie danych: HTTPS z TLS/SSL zapewnia poufność danych, chroniąc je przed odczytem przez osoby trzecie.
- Integralność danych: Obejmuje mechanizmy kontroli integralności danych, które uniemożliwiają zmianę przesyłanych informacji przez osoby trzecie.
- Autentyczność serwera: Dzięki certyfikatom SSL klient może zweryfikować tożsamość serwera, co chroni przed atakami typu MitM.
- Bezpieczeństwo użytkowników: Zapewnia użytkownikom pewność, że przeglądane strony są bezpieczne i autentyczne.

Aby wdrożyć HTTPS z TLS/SSL na swojej stronie internetowej, potrzebujesz certyfikatu SSL. Możesz go zdobyć od dostawców certyfikatów SSL, takich jak Let's Encrypt, DigiCert, Comodo itp. Instalując certyfikat SSL na serwerze, możesz zabezpieczyć komunikację między serwerem a klientami oraz zwiększyć bezpieczeństwo i zaufanie użytkowników wobec Twojej strony internetowej.

<hr>
<br><br><br>

# Wyszukiwanie rozwiązań za pomocą Google i korzystanie z ChatGPT

Wyszukiwanie rozwiązań za pomocą Google:

- **Sprecyzuj swoje zapytanie:** Wprowadź jak najbardziej precyzyjne zapytanie w Google. Im dokładniejsze pytanie, tym bardziej prawdopodobne jest uzyskanie odpowiedzi.

- **Używaj cudzysłowów:** Jeśli poszukujesz konkretnego terminu lub frazy, użyj cudzysłowów, aby dokładnie wyszukać to, czego potrzebujesz. Na przykład, "programowanie w C#" zwróci wyniki zawierające dokładnie tę frazę.

- **Dodaj kluczowe słowa:** Jeśli nie jesteś pewien, jak sformułować zapytanie, dodaj kluczowe słowa, które opisują temat. Na przykład, "rozwiązywanie problemów z komunikacją w sieci lokalnej".

- **Filtruj wyniki:** Po otrzymaniu wyników wyszukiwania użyj narzędzi do filtrowania wyników. Możesz ograniczyć wyniki do określonego okresu czasu, strony internetowe, które zostały zaktualizowane, lub innych kryteriów.

- **Znajdź źródła autorytatywne:** Sprawdź źródła informacji, takie jak oficjalne dokumentacje, strony internetowe renomowanych firm, forum tematyczne itp. Zawsze warto odwoływać się do wiarygodnych źródeł.

- **Czytaj recenzje i opinie:** Jeśli jesteś zainteresowany narzędziem lub rozwiązaniem, przeczytaj recenzje i opinie innych użytkowników, aby dowiedzieć się, czy jest to dobre rozwiązanie.

Korzystanie z ChatGPT (lub innych AI):

- **Sprecyzuj pytanie:** Jak w przypadku wyszukiwania Google, im dokładniej sformułujesz pytanie, tym bardziej precyzyjna odpowiedź.

- **Zadawaj konkretne pytania:** Jeśli masz pytanie, na które oczekujesz konkretnej odpowiedzi, sformułuj pytanie w sposób, który umożliwi dostarczenie odpowiedzi "tak" lub "nie".

- **Użyj różnych źródeł informacji:** ChatGPT może dostarczyć informacje na podstawie swojej wiedzy, ale zawsze warto potwierdzić informacje, korzystając z innych źródeł, zwłaszcza w przypadku ważnych decyzji czy profesjonalnych kwestii.

- **Bądź krytyczny:** Pamiętaj, że ChatGPT, choć potężny, może dostarczyć informacje, które są nieprawdziwe lub nieaktualne. Bądź krytyczny wobec otrzymywanych odpowiedzi.

- **Eksperymentuj:** Jeśli masz złożone pytanie, można eksperymentować z różnymi wariantami pytania, aby uzyskać bardziej satysfakcjonującą odpowiedź.

Ważne jest, aby połączyć umiejętności wyszukiwania w Google z umiejętnościami korzystania z narzędzi AI, takich jak ChatGPT. Kombinacja tych dwóch źródeł może pomóc w szybkim rozwiązywaniu problemów, zdobywaniu wiedzy i podejmowaniu bardziej świadomych decyzji.

<hr>
<br><br><br>


# Struktury danych i Algorytmy

Struktury danych i algorytmy są fundamentalnymi pojęciami w informatyce i programowaniu. Są one niezbędne do efektywnego rozwiązywania problemów i projektowania stabilnego oprogramowania. Oto bardziej szczegółowe omówienie tych tematów:

## Struktury danych:

- **Tablice:** Uporządkowane kolekcje elementów, do których można uzyskać dostęp za pomocą indeksu. Tablice są proste i efektywne przy dostępie losowym.

- **Listy jednokierunkowe:** Struktury danych, w których każdy element (węzeł) zawiera wartość i odnośnik (lub link) do następnego elementu. Istnieją listy jednokierunkowe i listy dwukierunkowe.

- **Stosy:** Struktura danych liniowa, która stosuje zasadę "Last-In-First-Out" (LIFO). Stosy są często wykorzystywane do zarządzania wywołaniami funkcji, funkcją cofania (undo) i analizą wyrażeń.

- **Kolejki:** Struktura danych liniowa, która stosuje zasadę "First-In-First-Out" (FIFO). Kolejki są używane do zarządzania zadaniami i planowania procesów.

- **Drzewa:** Hierarchiczne struktury danych z węzłem korzenia i węzłami potomnymi. Popularne typy to drzewa binarne, drzewa przeszukiwania binarnego i drzewa AVL.

- **Grafy:** Zbiory węzłów (wierzchołków) połączonych krawędziami. Grafy mogą być wykorzystywane do modelowania różnych relacji i problemów w świecie rzeczywistym.

- **Tablice mieszające (hash tables):** Struktury danych przechowujące pary klucz-wartość, umożliwiające szybkie odnajdywanie wartości na podstawie klucza.

## Algorytmy:

### Algorytmy wyszukiwania:

- Wyszukiwanie liniowe
- Wyszukiwanie binarne (dla posortowanych tablic)
- Haszowanie (dla tablic mieszających)

### Algorytmy sortowania:

- Sortowanie bąbelkowe
- Sortowanie przez wstawianie
- Sortowanie przez wybieranie
- Sortowanie przez scalanie
- Szybkie sortowanie
- Sortowanie przez kopcowanie
- Sortowanie przez przeliczanie (Radix Sort)

### Inne algorytmy:

- Algorytmy rekurencyjne
- Programowanie dynamiczne
- Algorytmy zachłanne
- Algorytmy grafowe
- Dzielenie i zwyciężanie
- Backtracking
- Algorytmy dla łańcuchów znaków
- Algorytmy numeryczne

Zrozumienie struktur danych i algorytmów jest kluczowe dla rozwoju oprogramowania, programowania konkurencyjnego i udanych rozmów kwalifikacyjnych. Pozwala to na efektywne pisanie kodu i rozwiązywanie złożonych problemów. Istnieje wiele dostępnych zasobów online, kursów i książek, które pomogą pogłębić wiedzę w tych dziedzinach.

<hr>
<br><br><br>

# Naucz się podstaw języka C#

- https://www.chillcode.org/Csharp-basic/Introduction_to_Csharp.html
- https://learn.microsoft.com/pl-pl/dotnet/csharp/

<hr>
<br><br><br>

# Naucz się podstaw ASP.NET

- https://www.chillcode.org/ASP.NET-CORE-Basic/Introduction_to_ASP.NET-Core.html
- https://learn.microsoft.com/pl-pl/dotnet/fundamentals/

<hr>
<br><br><br>


# .NET CLI - Podstawowe Operacje

.NET CLI (Command Line Interface) to narzędzie, które umożliwia programistom pracę z platformą .NET za pomocą wiersza poleceń. Jest to narzędzie niezwykle przydatne do zarządzania projektami .NET, kompilowania kodu, uruchamiania aplikacji i wiele innych zadań. Oto kilka podstawowych poleceń i operacji, które można wykonywać za pomocą .NET CLI:

## Tworzenie nowego projektu:

Możesz użyć .NET CLI do tworzenia nowego projektu, na przykład:

```shell
dotnet new console -n MyConsoleApp
```

To polecenie stworzy nową konsolową aplikację o nazwie "MyConsoleApp".

## Kompilacja projektu:

Aby skompilować projekt, użyj polecenia `dotnet build`. Na przykład:

```shell
dotnet build
```

## Uruchamianie projektu:

Aby uruchomić projekt, użyj polecenia `dotnet run`. Na przykład:

```shell
dotnet run
```

To uruchomi aplikację w trybie konsolowym.

## Dodawanie zależności:

Możesz użyć `dotnet add` do dodawania zależności do projektu. Na przykład, aby dodać pakiet NuGet, możesz użyć polecenia:

```shell
dotnet add package NazwaPakietu
```

## Testowanie projektu:

.NET CLI umożliwia również wykonywanie testów jednostkowych. Możesz użyć polecenia `dotnet test`, aby uruchomić testy zdefiniowane w projekcie.

## Publikowanie projektu:

Aby opublikować projekt do wdrożenia, użyj polecenia `dotnet publish`. Możesz dostosować opcje publikowania, takie jak framework docelowy i środowisko docelowe.

## Sprawdzanie informacji o projekcie:

Polecenie `dotnet list` pozwala uzyskać informacje o projektach w bieżącym katalogu lub wskazanym katalogu.

## Kontrola wersji SDK .NET:

Możesz użyć polecenia `dotnet --version`, aby sprawdzić zainstalowaną wersję SDK .NET. Możesz również użyć `dotnet --list-sdks`, aby wyświetlić dostępne wersje SDK .NET na twoim systemie.

## Inne komendy:

.NET CLI oferuje wiele innych komend i opcji, które pozwalają na różne operacje, takie jak zarządzanie paketami, obsługa projektów webowych, praca z bazami danych itp.

.NET CLI jest wszechstronnym narzędziem, które ułatwia pracę z platformą .NET. Możesz używać go do zarządzania projektami ASP.NET Core, projektami konsolowymi, bibliotekami i innymi rodzajami projektów .NET. Pamiętaj, że dostępne komendy mogą się różnić w zależności od wersji SDK .NET, więc zawsze warto sprawdzić dokumentację dla najnowszej wersji narzędzia.

<hr>
<br><br><br>

# Podstawy Projektowania Baz Danych i Języka SQL

## Projektowanie Baz Danych

Projektowanie baz danych to proces tworzenia struktury bazy danych, która umożliwia skuteczne przechowywanie i zarządzanie danymi. Oto kluczowe koncepcje związane z projektowaniem baz danych:

### Tabele

Tabele stanowią podstawową jednostkę przechowywania danych w bazie danych. Każda tabela jest zbiorem rekordów, a każdy rekord składa się z kolumn, które reprezentują różne atrybuty danych.

### Klucze główne (Primary Keys)

Klucz główny to unikalny identyfikator dla każdego rekordu w tabeli. Pomaga to w jednoznacznym identyfikowaniu danych.

### Klucze obce (Foreign Keys)

Klucz obcy jest polem w tabeli, które odnosi się do klucza głównego w innej tabeli. Pozwala to na tworzenie relacji między tabelami.

### Relacje

Relacje określają, jak dwie lub więcej tabel są powiązane ze sobą. Najczęściej spotykanymi relacjami są relacje jeden do wielu, wiele do jednego i wiele do wielu.

### Normalizacja

Normalizacja jest procesem organizacji danych w celu uniknięcia powtarzających się informacji i zapewnienia spójności danych. Istnieje kilka form normalizacji, takich jak pierwsza, druga i trzecia normalizacja.

### Indeksy

Indeksy są strukturami danych, które przyspieszają wyszukiwanie w tabelach. Pozwalają na efektywne odnajdywanie danych na podstawie określonych kryteriów.

## Język SQL (Structured Query Language)

SQL to język programowania używany do zarządzania danymi w bazach danych. Oto podstawowe polecenia SQL i ich zastosowania:

### Polecenie SELECT

Służy do wybierania danych z tabeli. Przykład:

```sql
SELECT kolumna1, kolumna2 FROM tabela WHERE warunek;
```

### Polecenie INSERT

Dodaje nowe dane do tabeli. Przykład:

```sql
INSERT INTO tabela (kolumna1, kolumna2) VALUES (wartość1, wartość2);
```

### Polecenie UPDATE

Aktualizuje istniejące dane w tabeli. Przykład:

```sql
UPDATE tabela SET kolumna1 = nowa_wartość WHERE warunek;
```

### Polecenie DELETE

Usuwa dane z tabeli. Przykład:

```sql
DELETE FROM tabela WHERE warunek;
```

### Polecenie CREATE TABLE

Tworzy nową tabelę w bazie danych. Przykład:

```sql
CREATE TABLE tabela (
    kolumna1 typ_danych,
    kolumna2 typ_danych,
    PRIMARY KEY (kolumna1)
);
```

### Polecenie ALTER TABLE

Zmienia strukturę istniejącej tabeli. Przykład:

```sql
ALTER TABLE tabela ADD COLUMN nowa_kolumna typ_danych;
```

### Polecenie JOIN

Łączy dane z dwóch lub więcej tabel na podstawie określonych relacji. Przykład:

```sql
SELECT kolumna1, kolumna2 FROM tabela1
JOIN tabela2 ON tabela1.klucz_obcy = tabela2.klucz_główny;
```

### Polecenie GROUP BY

Grupuje dane na podstawie określonych kolumn i oblicza agregaty, takie jak SUM, AVG, COUNT itp. Przykład:

```sql
SELECT kolumna1, AVG(kolumna2) FROM tabela GROUP BY kolumna1;
```

### Polecenie ORDER BY

Sortuje wyniki zapytania według określonej kolumny. Przykład:

```sql
SELECT kolumna1, kolumna2 FROM tabela ORDER BY kolumna1 ASC;
```

To tylko podstawy projektowania baz danych i języka SQL. Oba te zagadnienia są obszernym tematem, który można zgłębiać, ucząc się bardziej zaawansowanych koncepcji i technik. Warto również korzystać z dokumentacji systemu zarządzania bazą danych (np. MySQL, PostgreSQL, SQL Server itp.), aby poznać specyficzne polecenia i funkcje dostępne w danym systemie.

<hr>
<br><br><br>

# Procedury Składowane w Bazach Danych

Procedury składowane to zestawy instrukcji SQL, które są zapisane w bazie danych i mogą być wykonywane wielokrotnie przez aplikacje lub użytkowników. Procedury składowane pozwalają na przechowywanie i ponowne wykorzystywanie logicznych operacji na danych, co może przyczynić się do poprawy wydajności, zwiększenia bezpieczeństwa i ułatwienia zarządzania bazą danych. Oto podstawowe informacje o SQL procedurach składowanych:

## Tworzenie Procedur Składowanych

Aby utworzyć procedurę składowaną, używa się polecenia `CREATE PROCEDURE`. Przykład tworzenia prostej procedury składowanej w języku T-SQL (dla baz danych SQL Server):

```sql
CREATE PROCEDURE Nazwa_Procedury
AS
BEGIN
    -- Ciało procedury składowanej
END;
```

## Parametry Procedury

Procedury składowane mogą przyjmować parametry, które umożliwiają dostarczenie wartości przy wywoływaniu procedury. Parametry są deklarowane w sekcji `CREATE PROCEDURE`. Przykład:

```sql
CREATE PROCEDURE DodajKlienta
    @Imie NVARCHAR(50),
    @Nazwisko NVARCHAR(50)
AS
BEGIN
    -- Ciało procedury, które wykorzystuje parametry
END;
```

## Wywoływanie Procedury

Aby wywołać procedurę składowaną, używa się polecenia `EXECUTE` lub jego skróconej formy `EXEC`. Przykład wywołania procedury:

```sql
EXEC DodajKlienta @Imie = 'Jan', @Nazwisko = 'Kowalski';
```

## Zwracanie Wyników

Procedury składowane mogą zwracać wyniki na różne sposoby. Możesz użyć polecenia `SELECT` wewnątrz procedury, aby zwrócić wynik zapytania. Innym sposobem jest użycie parametrów wyjściowych lub `OUTPUT`, aby przekazać wyniki procedury na zewnątrz.

## Aktualizacja Danych

Procedury składowane mogą być używane do aktualizacji danych w bazie danych. Można wykonywać operacje `INSERT`, `UPDATE` lub `DELETE` wewnątrz procedury.

## Transakcje

Procedury składowane mogą być używane do zarządzania transakcjami. Można rozpoczynać, zatwierdzać lub anulować transakcje w obrębie procedury.

## Bezpieczeństwo

Procedury składowane mogą pomóc w zwiększeniu bezpieczeństwa bazy danych, ponieważ dostęp do procedury można kontrolować za pomocą uprawnień dostępu.

## Przechowywanie Kodu SQL

Przechowywanie logiki biznesowej w procedurach składowanych pozwala na oddzielenie kodu aplikacji od kodu SQL, co ułatwia zarządzanie i utrzymanie systemu.

## Optymalizacja Wydajności

Procedury składowane mogą poprawić wydajność, ponieważ mogą być kompilowane i buforowane w pamięci, co eliminuje potrzebę analizy zapytań za każdym razem, gdy są wywoływane.

Procedury składowane są dostępne w wielu systemach zarządzania bazą danych, takich jak Microsoft SQL Server, MySQL, PostgreSQL, Oracle i wiele innych. Składnia i funkcje procedur składowanych mogą się różnić w zależności od używanego systemu, dlatego zawsze warto sprawdzić dokumentację dla konkretnego systemu.

<hr>
<br><br><br>

# Ograniczenia w Języku SQL

Ograniczenia w języku SQL to reguły lub warunki, które definiują, jak dane w bazie danych muszą być przechowywane lub zmieniane. Służą do zapewnienia spójności danych, uniknięcia błędów i utrzymania integralności bazy danych. Oto kilka najważniejszych typów ograniczeń w SQL:

## Ograniczenie klucza głównego (Primary Key Constraint):

- Definiuje jedno lub więcej kolumn jako unikalne klucze główne tabeli.
- Gwarantuje, że każdy wiersz w tabeli jest jednoznacznie identyfikowany przez wartości w tych kolumnach.
- Zapobiega duplikatom i pustym wartościom.

```sql
CREATE TABLE Uzytkownicy (
    ID INT PRIMARY KEY,
    Nazwa UZYTKOWNIKA VARCHAR(50)
);
```

## Ograniczenie klucza obcego (Foreign Key Constraint):

- Określa, że wartości w jednej kolumnie muszą pasować do wartości w innej kolumnie w innej tabeli.
- Ustanawia relacje między tabelami.

```sql
CREATE TABLE Zamowienia (
    ID INT PRIMARY KEY,
    KlientID INT,
    FOREIGN KEY (KlientID) REFERENCES Klienci(ID)
);
```

## Ograniczenie unikalności (Unique Constraint):

- Zapewnia, że wartości w danej kolumnie lub grupie kolumn są unikalne w całej tabeli, z wyjątkiem wartości NULL.

```sql
CREATE TABLE Produkty (
    ID INT PRIMARY KEY,
    NazwaProduktu VARCHAR(50) UNIQUE
);
```

## Ograniczenie sprawdzania (Check Constraint):

- Określa warunki, które muszą być spełnione, aby dane mogły być wprowadzane do tabeli.
- Możesz używać wyrażeń logicznych do zdefiniowania warunków.

```sql
CREATE TABLE Pracownicy (
    ID INT PRIMARY KEY,
    DataZatrudnienia DATE,
    CONSTRAINT CheckData CHECK (DataZatrudnienia >= '2000-01-01')
);
```

## Ograniczenie NOT NULL:

- Określa, że dana kolumna nie może mieć wartości NULL, czyli musi zawsze zawierać jakieś dane.

```sql
CREATE TABLE Produkty (
    ID INT PRIMARY KEY,
    NazwaProduktu VARCHAR(50) NOT NULL
);
```

## Ograniczenie CASCADE:

- Stosowane w ograniczeniach klucza obcego.
- Określa, że zmiany w tabeli nadrzędnej (np. usunięcie rekordu) zostaną odzwierciedlone w tabeli podrzędnej (np. usunięcie powiązanych rekordów).

```sql
CREATE TABLE Zamowienia (
    ID INT PRIMARY KEY,
    KlientID INT,
    FOREIGN KEY (KlientID) REFERENCES Klienci(ID) ON DELETE CASCADE
);
```

Ograniczenia SQL są ważnym narzędziem do zapewnienia spójności danych i integralności bazy danych. Pozwalają na definiowanie zasad, których należy przestrzegać podczas dodawania, aktualizowania lub usuwania danych, co prowadzi do bardziej niezawodnych i bezpiecznych baz danych.


<hr>
<br><br><br>

# Wyzwalacze SQL

Wyzwalacze (triggers) w języku SQL to specjalne procedury lub reguły, które są automatycznie uruchamiane w odpowiedzi na określone operacje wykonywane na tabelach, takie jak wstawianie, aktualizacja lub usuwanie danych. Wyzwalacze pozwalają na automatyzację działań, analizę i kontrolę zmian w bazie danych. Oto kilka kluczowych informacji na temat wyzwalaczy SQL:

## Typy wyzwalaczy

- Wyzwalacze dzielą się na dwa podstawowe typy: przedoperacyjne (BEFORE) i pooperacyjne (AFTER). Wyzwalacze "przed" uruchamiane są przed wykonaniem operacji na tabeli, podczas gdy wyzwalacze "po" uruchamiane są po wykonaniu operacji.

## Operacje wyzwalacza

- Wyzwalacze można przypisać do różnych operacji na tabeli, takich jak INSERT, UPDATE i DELETE. W ten sposób można kontrolować zachowanie bazy danych w odpowiedzi na konkretne zmiany danych.

## Kiedy są uruchamiane

- Wyzwalacze są automatycznie uruchamiane, gdy określona operacja jest wykonywana na tabeli, do której są przypisane. Na przykład, wyzwalacz "przed wstawieniem" uruchomi się, gdy próbujesz wstawić nowy rekord.

## Składnia tworzenia wyzwalaczy

W SQL, wyzwalacze są tworzone za pomocą polecenia `CREATE TRIGGER`. W składni definiuje się, kiedy wyzwalacz ma być uruchamiany, co ma robić i w jakiej tabeli.

```sql
CREATE TRIGGER nazwa_wyzwalacza
BEFORE INSERT ON tabela
FOR EACH ROW
BEGIN
    -- Ciało wyzwalacza
END;
```

## Kontekst wyzwalacza

- W wyzwalaczach można odwoływać się do starych i nowych danych. Stare dane to wartości przed operacją, a nowe dane to wartości po operacji. W zależności od kontekstu wyzwalacza można używać specjalnych słów kluczowych, takich jak `OLD` i `NEW`, aby odwołać się do tych danych.

## Przykłady zastosowań

- Wyzwalacze są przydatne do tworzenia zabezpieczeń (np. sprawdzanie uprawnień przed operacją), kontroli spójności danych (np. automatyczne aktualizacje powiązanych rekordów) oraz audytu (np. zapisywanie zmian do logów).

## Zarządzanie wyzwalaczami

- Można tworzyć, modyfikować i usuwać wyzwalacze w bazie danych za pomocą odpowiednich poleceń. Jeśli nieprawidłowo zaprojektowany wyzwalacz może prowadzić do problemów z wydajnością, więc warto być ostrożnym w ich stosowaniu.

Wyzwalacze SQL są potężnym narzędziem do automatyzacji działań i zapewnienia integralności danych w bazach danych. Jednak należy pamiętać, że nadmierna ilość i skomplikowane wyzwalacze mogą skomplikować zarządzanie bazą danych, dlatego zawsze warto starannie przemyśleć, gdzie i kiedy je używać.

<hr>
<br><br><br>
