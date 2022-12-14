# **Challenge_Portfolio_Magdalena**

# **Task 1**
## Subtask 1
Podczas testu wiedzy zdoby艂am 9 punkt贸w. 馃弳
## Subtask 3
Cze艣膰 艣wiecie DareIT! :upside_down_face:

Nazywam si臋 Magda i od d艂u偶szego czasu staram si臋 wej艣膰 w 艣wiat testowania. Droga jest do艣膰 wyboista, jednak bardzo interesuj膮ca. 
Wzie艂am udzia艂 w projekcie, bo lubi臋 nowe wyzwania. Od naszych cotygodniowych spotka艅 i zada艅 oczekuj臋 ogromu praktycznej wiedzy, 
kt贸ra pozwoli mi poczu膰 si臋 jak w prawdziwym projekcie. Jestem zaciekawiona i z niecierpliwo艣ci膮 b臋d臋 wyczekiwa膰 kolejnych task贸w. :)
## Subtask 4

**Aplikacja kt贸r膮 testujemy: https://scouts-test.futbolkolektyw.pl/pl**

*1. Do czego s艂u偶y aplikacja?*

   Aplikacja s艂u偶y do gromadzenia informacji o graczach/pi艂karzach. 
   Znajdziemy w niej szczeg贸艂owe informacje o konkretnym pi艂karzu (pochodzenie, pozycja, cechy fizyczne itp.). 
   Ka偶dy gracz ma przypisan膮 histori臋 meczy, w kt贸rych gra艂 oraz u偶ytkownik ma mo偶liwo艣膰 sprawdzenia sumarycznych raport贸w z mecz贸w.
   Raporty mo偶na uzupe艂nia膰 o szczeg贸艂owe informacje dotycz膮ce zachowania zawodnika na boisku.
    
*2. Jakie funkcjonalno艣ci ma aplikacja?*

   **W aplikacji mo偶na wyr贸偶ni膰 nast臋puj膮ce funkcjonalno艣ci:**
   * Dodawanie gracza do listy; 
   
     *UWAGA: Opcja dodania gracza z widoku zak艂adki gracze, by艂aby wygodna i intuicyjna.*
     
     *UWAGA: Mo偶liwo艣膰 edycji informacji o zawodniku nie powinna by膰 dost臋pna po naci艣ni臋ciu w konkretny wiersz (imi臋 i nazwisko gracza), 
             uwa偶am 偶e powinna si臋 wy艣wietla膰 strona, kt贸ra jest podsumowaniem, a nie edycj膮. Opcja edycji mog艂aby by膰 dost臋pna tylko dla autora rekordu.*
   * Dodawanie i edycja informacji o meczu, kt贸re s膮 przypisane do okre艣lonego gracza;
   
     *UWAGA: Mo偶liwo艣膰 wej艣cia do zak艂adki "Mecze" z menu g艂贸wnego, by艂aby wygodna i intuicyjna.
             Kto艣 mo偶e zna膰 informacje z meczu i chcie膰 kogo艣 znale藕膰, bez znajmo艣ci imienia i nazwiska gracza.*
   * 艢ci膮ganie listy graczy w postaci plik贸w .CSV, poprzez naci艣ni臋cie odpowiedniej ikony;
   * Wydruk listy graczy, poprzez naci艣ni臋cie odpowiedniej ikony;
   * Mo偶liwo艣膰 zmiany wy艣wietlanej tabeli z graczami (np. ukrywanie kolumn), poprzez naci艣ni臋cie odpowiedniej ikony;
   * Filtrowanie listy graczy, poprzez naci艣ni臋cie odpowiedniej ikony;
   
      *UWAGA: Powinna by膰 dost臋pno艣膰 podstawowych filtr贸w, czyli sortowanie alfabatyczne, rosn膮ce, malej膮ce (np. wiekiem, ilo艣ci膮 meczy, raport贸w).*
   * Mo偶liwo艣膰 wyszukiwania zawodnik贸w.
    
*3. Interfejs aplikacji*

   * Strona jest prosta, nie za bardzo rozbudowana. Na pierwszy rzut oka, na stronie g艂贸wnej nawigacja wydaje si臋 艂atwa i przejrzysta.
   * Kafelki u g贸ry strony informuj膮 nas o liczbie graczy, meczy, raport贸w, akcji, jednak nie s膮 one interaktywne i nie nawiguj膮 do konkretnych zbior贸w. 
   * Nie ma mo偶liwo艣ci prze艣ledzenia meczy, poniewa偶 dost臋pna jest tylko zak艂adka Graczy.
   * Przechodz膮c dalej w menu boczne, w zak艂adk臋 "Gracze", brakuje sp贸jno艣ci. Nie jest jasne czy istnieje mo偶liwo艣膰 klikni臋cia w konkretnego gracza, 
     zobaczenia jego danych, czy edycji informacji.
   * Zalet膮 aplikacji jest dost臋pno艣膰 t艂umaczenia na jezyk angielski.
   * Tekstury i kolory s膮 poprawne, nie s膮 jaskrawe, nie atakuj膮 u偶ytkownika i nie rozpraszaj膮 jego uwagi.
   * Pojawiaj膮 si臋 powiadomienia, kt贸re informuj膮 u偶ytkownika o zmianach na stronie (np. dodaj膮c nowego zawodnika).
   * Strona jest dost臋pna na urz膮dzeniach moblinych.
   * Korzystaj膮c z DevTools Lighthouse przegl膮darki Chrome, Performance dla urz膮dze艅 mobilnych jest ni偶szy (ok. 75), ni偶 dla przegl膮darek desktopowych (ok. 88).

*4. Intuicyjno艣膰*

   Z poziomu strony g艂贸wnej wszystko jest jasne. Wyst臋puje opcja "Dodaj gracza", wida膰 kt贸re informacje odsy艂aj膮 nas do kolejnych podstron.
   Z poziomu zak艂adki "Gracze" brak mo偶liwo艣ci dodania nowego gracza. Mog艂aby pojawi膰 si臋 opcja dodania gracza w tym oknie, 
   przycisk z plusem, jako dodanie nowego gracza. Taka opcja wyst臋puje w podstronie z meczami i raportami.
   Na stronie g艂ownej pojawiaj膮 si臋 informacje o ilo艣ci graczy, meczy, raport贸w, jednak opr贸czzawodnik贸w nie mo偶emy niczego innego przegl膮da膰.
   Powinna pojawi膰 si臋 opcja wej艣cia we wszystkie mecze i raporty, np. z bocznego menu, tam gdzie znajduje si臋 opcja "Gracze".
   Brak mo偶liwo艣ci usuwania graczy/meczy z listy. 

*5. B艂臋dy*

   * "Niepoprawne 艣ci膮ganie listy graczy w postaci pliku .CSV"
   
      Rezultat: 艢ci膮gni臋cie listy graczy tylko z aktualnie otwartej strony spisu zawodnik贸w (10 rekord贸w).
   
      Oczekiwany rezultat: 艢ci膮gni臋cie ca艂ej bazy zawodnik贸w.
   
      Priorytet: niski
   
      *Komentarz: Mam na uwadz臋 sytuacj臋, 偶e taka funkcjonalno艣膰 mog艂a zosta膰 tak zaprojektowana, 
                  jednak ze wzgl臋du na u偶yteczno艣膰 wydaje mi si臋, 偶e wygenerowanie raportu z list膮 dost臋pnych graczy w ca艂o艣ci,
                  by艂oby bardziej optymalne (przeniesienie do innej aplikacji/bazy).*
                  
   * "W sekcji "Gracze" po najechaniu na zawodnika nie wy艣wietla si臋 odsy艂acz do indywidyulanej strony"
   
      Rezultat: Najechanie na wiersz z graczem nie wskazuje na mo偶liwo艣膰 klikni臋cia.
   
      Oczekiwany rezultat: Pojawienie si臋 odsy艂acza do indywidualnej strony zawodnika.
   
      Priorytet: niski
   
   * "Po dodaniu gracza przekierowuje nas na stron臋 edycji"
   
      Rezultat: Po uzupe艂nieniu informacji o graczu, kt贸rego dodajemy do systemu, pojawia si臋 informacja o dodaniu i przekierowaniu do opcji edycji.
   
      Oczekiwany rezultat: Przekierowanie na stron臋 z og贸lnym profilem gracza.
   
      Priorytet: 艣redni
      
   * "Podczas edycji raportu z meczu, wprowadzaniu zmian, przycisk "SAVE" nachodzi na sekcj臋 "Dodatkowy komentarz"
   
      Rezultat: Po uzupe艂nieniu informacj o meczu, przycisk "SAVE" nachodzi na inne pola tekstowe.
   
      Oczekiwany rezultat: Przycisk "SAVE" pozostaje w jednym miejscu.
   
      Priorytet: 艣redni
      
   * "W oknie "Rozpocznij mecz" mo偶na rozpocz膮膰 wi臋cej ni偶 2 po艂owy meczu."
      
      Rezultat: Po uruchomieniu meczu, klikaj膮c z przycisk zegarka, mo偶na ustawi膰 wi臋ksz膮 liczb臋 po艂贸w ni偶 dwie.
   
      Oczekiwany rezultat: Dost臋pne s膮 tylko dwie po艂owy meczu.
   
      Priorytet: wysoki
      
  * "W oknie dodawania gracza, przycisk "Clear" nie usuwa informacji z formularza."
      
      Rezultat: Po klikni臋ciu w przycisk "Clear" w formularzu edycji informacji o graczu, nie nast臋puje usuni臋cie danych.
   
      Oczekiwany rezultat: Usuni臋cie danych w formularzu.
   
      Priorytet: 艣redni
      
   * "Mo偶liwo艣膰 dodania gracza bez danych"
      
      Rezultat: Stworzenie konta gracza, po wpisaniu SPACJI w puste pola.
   
      Oczekiwany rezultat: Informacja o konieczno艣ci wype艂nienia pustego pola ci膮giem znak贸w, cyfr.
   
      Priorytet: wysoki 
      
   **Og贸lny komentarz:**
   
   Sekcja dodawania graczy i wszystkie pola do uzupe艂nienia powinny by膰 zablokowane przed wpiasaniem niepoprawnych danych.
   
   Puste pola lub pola ze spacj膮, abstrakcyjne warto艣ci wagi i wzorstu, daty, powinny by膰 blokowane przed wpisaniem niepoprawnej danej
   np. litery w pola numeryczne (numer telefonu).
   
   Brakuje profilu osoby zalogowanej, gdzie mogliby艣my sprawdzi膰 ile os贸b dodali艣my do bazy, gdzie widnia艂yby nasze dane.
   
   W oknie logowania, w polu "Login" powinna si臋 pojawi膰 informacja, 偶e konieczne jest wpisanie adresu e-mail.
   
# **Task 2**
## Subtask 1

馃崁 [Test Case's based on User Stories](https://docs.google.com/spreadsheets/d/1Mt6FQfttUFqRPDLyb7hc2ceToqsZNYIl9pZsS1tunlI/edit?usp=share_link) 

## Subtask 2

馃挕 [Mind map](https://drive.google.com/file/d/1Ss96V3r3SxSOSsJsx9XGYkWmtub9qNM9/view?usp=sharing) 

馃崁 [Test Case's based on experience_Website in English 馃嚭馃嚫](https://docs.google.com/spreadsheets/d/1589dqUD6PTWXDCuFfejT0MtGR948kEbCJlDr_RXLel8/edit?usp=sharing) 

馃崁 [Test Case's based on experience_Website in Polish 馃嚨馃嚤](https://docs.google.com/spreadsheets/d/1_b5FHHD66fsbNYWxK1uss5EWN4cLvsm8mHx3zcd7j2g/edit?usp=sharing)

## Subtask 3
[Po co piszemy Test Case'y, komu to potrzebne? / Why are we writing Test Cases, who needs them?](https://www.youtube.com/watch?v=OO3FANjwKHY&t=1s) 馃檲

Test cases are important to systematize what we plan to do / test.

Test cases allow us to determine the functionality coverage.

We can create them at the stage when the product documentation is not yet fully ready, 
by the principle that **Early testing saves time and money**.

Test cases help get to know the application.

Test cases find defects in the product.

# **Task 3**
## Subtask 2

馃挕 [Mind map](https://drive.google.com/file/d/1Ss96V3r3SxSOSsJsx9XGYkWmtub9qNM9/view?usp=sharing) 

馃崁 [Test Case's based on experience_Website in English 馃嚭馃嚫](https://docs.google.com/spreadsheets/d/1589dqUD6PTWXDCuFfejT0MtGR948kEbCJlDr_RXLel8/edit?usp=sharing) 

馃崁 [Test Case's based on experience_Website in Polish 馃嚨馃嚤](https://docs.google.com/spreadsheets/d/1_b5FHHD66fsbNYWxK1uss5EWN4cLvsm8mHx3zcd7j2g/edit?usp=sharing)

## Subtask 3

馃搱馃搲 [Test Report](https://drive.google.com/file/d/1VGMOqnqYJ60v0evxkWfCRPHHpuTganN6/view?usp=sharing)

# **Task 4**
## Subtask 2

馃 [Bug Report](https://docs.google.com/spreadsheets/d/1HwSalkbEryYPYpr7G_5F2mwVYxa2ND41hCxHNOjhizE/edit?usp=sharing)

## Subtask 3

*1. What is this app for? What is the purpose of this app?*

馃挕 The Focusly app focuses on learning how to meditate and breathe properly. 

   Podcasts and recordings allow you to calm down, improve creativity, fight with lack of concentration, anxiety or bad sleep.
    
   It helps to achieve the goals selected in the application and builds the habit of regularity.

*2. Who is going to be the end user of the application?*  

馃拞鈥嶁檧锔忦煉員he end user of this application can be any person who wants to learn to meditate or people who already have some experience in meditating.

*3. Do you think the application is user friendly?* 

馃崁 The application has a friendly look, the colors are subdued, they don't attack the user. 

   The application doesn't consume too much energy, it can be run in the background. 
   
   The application doesn't have its equivalent in the form of a website where data could be synchronized. 
   
   The advantage of the application is the ability to delete an account from the application level.

*4. How would you improve the application? What would you improve about it? Do you have any idea for additional functionality?*

馃寶As an additional functionality I would introduce:

   馃寱 The ability to set the playback speed;

   馃寲 The ability to scroll through the lessons with your finger (swipe right - swpie left for next lessons or previous);

   馃寳 In breathing tasks, add the possibility of obtaining a sound that tells us to inhale, exhale;

   馃寴 The first time when user enter the application, add a tutorial (understand what to do with the app);

   馃寬 The ability to create a playlist;
     
   馃寭 The ability to change the profile picture;
     
   馃寯 Availability of foreign-language podcasts in the Polish version of the application without changing the language

*5. What differences do you see between testing a web application and a native one?* 

When we are testing web applications, we can receive information from the server in the form of code. 
Testing web applications takes place in different browsers, while testing mobile applications takes place on different devices with different operating systems. 
In testing mobile applications, we can take into account factors such as: battery levels, push notifications, sensors built into the device.

# **Task 5**
## Subtask 1

馃搳鉁掞笍[Finished course "Kurs SQL od podstaw"](https://www.udemy.com/course/kurs-sql-od-podstaw/)

**Typ zapytania:**
SELECT/INSERT/UPDATE/DELETE - typ zapytania

1. **FROM** - 藕r贸d艂o pobrania danych
2. **WHERE** - warunek
3. **GROUP BY** - grupowanie rekord贸w
4. **ORDER BY** - sortowanie

馃 **SELECT** - wybieranie danych z bazy danych

*SELECT column1, column2, ... FROM table_name;*

**SELECT DISTINCT** - zwraca tylko odr臋bne warto艣ci, zwraca unikalne warto艣ci, bez duplikat贸w

*SELECT DISTINCT column1, column2, ... FROM table_name;*

馃椇 **WHERE** - filtruje rekordy, po zadeklarowaniu warunku

*SELECT column1, column2, ... FROM table_name;*
*WHERE condition;*

**Operatory AND, OR, NOT**

馃悳 **AND** - wszystkie warunki musz膮 by膰 prawd膮

馃挜 **OR** - kt贸rykolwiek warunek jest PRAWDZIWY

鉂? **NOT** - nieprawdziwy warunek

0锔忊儯 **IS NULL** - r贸wna zero, pusta kolumna

馃敘 **IS NOT NULL** - nie jest r贸wna zerem, pe艂ne kolumny

猬嗭笍 **TOP** - liczba rekord贸w do zw贸rcenia

鉃? **LIMIT** - obs艂ugiwany przez MySQL

*SELECT column1, column2, ... FROM table_name*
*WHERE condition1 AND condition2;*

*SELECT column1, column2, ... FROM table_name*
*WHERE condition IS NULL;*

*SELECT TOP number column_name(s) FROM table_name*
*WHERE condition1;*

*SELECT column_name(s)FROM table_nameWHERE condition LIMIT number;*

鈫橈笍 **MIN()** najmniejsza warto艣膰 z wybranej kolumny

鈫楋笍 **MAX()** najwi臋ksza warto艣膰 z wybranej kolumny

*SELECT MIN (column_name) FROM table_name WHERE condition1;*

鈴? **COUNT()** - podaje liczb臋 wierszy spe艂niaj膮cych warunek

*SELECT COUNT (column_name) FROM table_name WHERE condition1;*

鉃? **AVG()** - zwraca 艣redni膮 warto艣膰 kolumny numerycznej

*SELECT AVG (column_name) FROM table_name WHERE condition1;*

鉃? **SUM()** - ca艂kowita suma kolumny numerycznej

*SELECT SUM (column_name) FROM table_name WHERE condition1;*

馃挶 **LIKE** - w klauzuli WHERE, do wyszukiwania okre艣lonego wzorca

*SELECT column1, column2, ... FROM table_name WHERE columnN LIKE pattern;*

馃馃従鈥嶁檧锔忦煂仇煣嶐煆? **BETWEEN** - wybiera warto艣ci z danego zakresu.

*SELECT column_name(S) FROM table_name WHERE column_name BETWEEN value1 AND value2;*

**Aliasy** - nadawanie kolumnie w tabeli tymczasowej nazwy, 
nazwa ta zostaje na czas aktualnego zapytania

*SELECT column_name AS alias-name FROM table_name;*

馃洅 **ORDER BY** - sortowanie zestawu wynik贸w w kolejno艣ci rosn膮cej lub majlej膮ce
rosn膮co **ASC**, malej膮co **DESC**

*SELECT column1, column2, ... FROM table_name ORDER BY column1, column2, ... ASC|DESC;*

**Pokazanie ca艂ej zawarto艣ci tabeli:**

*SELECT * FROM categories;*

Wyszukiwanie string贸w zawsze w cudzys艂owie

**%** oznacza dowoln膮 liter臋
**_** pozwoli wskaza膰 konkretne miejsce litery w wyrazie

**INSERT INTO** - s艂u偶y do wstawiania nowych rekord贸w do tabeli

*INSERT INTO Customers (CustomerName, City, Country) VALUES ('Cardinal', 'Stvanger', 'Norway');*

鉁? **UPDATE** s艂u偶y do aktualizacji istniej膮cych rekord贸w  w tabeli

*UPDATE Customers SET ContactName = 'Alfred Schmidt', City = 'Frankfurt' WHERE CustomerID = 1*

鉀旓笍 **DELETE** - s艂u偶y do usuwania istniej膮cych rekord贸w w tabeli

*DELETE FROM Customers WHERE CudtomerName = 'Alfreds Futterkiste'*

馃挄**GRUOP BY** pozwala na grupowanie rekord贸w wed艂ug r贸znych zasad

*SELECT COUNT (CustomerID), Country FROM Customers GROUP BY Country;*

馃Ь**HAVING** zwraca podsumowanie dla ca艂ej tabeli, wywo艂ana funkcja GROUP BY

*SELECT COUNT (CustomerID), Country FROM Customers GROUP BY Country; HAVING COUNT (CustomerID) >5;*

馃梽**INNER JOIN** 艂膮czenie wierszy z conajmniej dw贸ch tabel na podstawie powi膮zanej mi臋dzy nimi kolumny

*SELECT Orders.OrderID, Customers.CustomerName FROM Orders INNER JOIN Customers ON Orders.CustomerID=Customers.CustomerID*

鈼?锔? **LEFT JOIN** zwraca wszystkie rekordy z lewej tabeli oraz pasuj膮ce rekordy z prawej tabeli

*SELECT column_name(s) FROM table1 (lewa tabelka) LEFT JOIN table2 (prawa tabelka) ON table1.column_name = table2.column_name*

鈻讹笍 **RIGHT JOIN** zwraca wszystkie rekordy z prawej tabeli oraz pasuj膮ce rekordy z lewej tabeli

*SELECT column_name(s) FROM table1 (prawa tabelka) RIGHT JOIN table2 lewa tabelka) ON table1.column_name = table2.column_name*

馃叞锔? 馃叡锔? 馃啂**UNION** s艂u偶y do 艂膮czenia zestawu wynik贸w dw贸ch lub wi臋cej instrukcji SELECT

*SELECT column_name(s) FROM table1 UNION SELECT colu(s) FROM table2*

## Subtask 3

1锔忊儯 Wy艣wietl tabel臋 actors w kolejno艣ci alfabetycznej sortuj膮c po kolumnie surname.

馃挱 SELECT * FROM actors ORDER BY surname;

![image](https://user-images.githubusercontent.com/71427633/204322271-536ec16b-56a6-416a-8f4c-bcc35e3a93ee.png)

2锔忊儯 Wy艣wietl film, kt贸ry powsta艂 w 2019 roku.

馃挱 SELECT * FROM movies WHERE year_of_production = 2019;

![image](https://user-images.githubusercontent.com/71427633/204321948-b3f12cb1-86f6-411f-a015-f3da7fb5bd4e.png)

3锔忊儯 Wy艣wietl wszystkie filmy, kt贸re powsta艂y mi臋dzy 1900, a 1999 rokiem.

馃挱 SELECT * FROM movies WHERE year_of_production BETWEEN 1900 AND 1999;

![image](https://user-images.githubusercontent.com/71427633/204322558-f2e68805-7cf5-475f-b291-4cfe1a3a8f55.png)

4锔忊儯 Wy艣wietl JEDYNIE tytu艂 i cen臋 film贸w, kt贸re kosztuj膮 poni偶ej 7$ 

馃挱 SELECT title, price FROM movies WHERE price < 7;

![image](https://user-images.githubusercontent.com/71427633/204323118-428f9405-8dc1-4d61-bd05-2029c32916f4.png)

5锔忊儯 U偶yj operatora logicznego AND, aby wy艣wietli膰 aktor贸w o actor_id pomi臋dzy 4-7 (4 i 7 powinny si臋 wy艣wietla膰). NIE U呕YWAJ operatora BETWEEN.

馃挱 SELECT * FROM actors WHERE actor_id >= 4 AND actor_id <= 7;

![image](https://user-images.githubusercontent.com/71427633/204323630-9d4c0671-ea16-4270-b527-2fc2d002d3ab.png)

6锔忊儯 Wy艣wietl klient贸w o id 2,4,6 wykorzystaj do tego warunek logiczny. 

馃挱 SELECT * FROM customers WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6;
馃挱 SELECT * FROM customers WHERE customer_id % 2 = 0;

![image](https://user-images.githubusercontent.com/71427633/204324715-e86d7cb4-fbd5-4cfb-872b-90acf6823897.png)

7锔忊儯 Wy艣wietl klient贸w o id 1,3,5 wykorzystaj do tego operator IN.

馃挱 SELECT * FROM customers WHERE customer_id IN (1,3,5);

![image](https://user-images.githubusercontent.com/71427633/204325637-973bb5d0-4c23-494e-bd9d-a09624cb0f58.png)

8锔忊儯 Wy艣wietl dane wszystkich os贸b z tabeli 鈥榓ctors鈥?, kt贸rych imi臋 zaczyna si臋 od ci膮gu 鈥淎n鈥?.

馃挱 SELECT * FROM actors WHERE name LIKE  "An%";

![image](https://user-images.githubusercontent.com/71427633/204326739-a4eb30d5-eba5-47a4-a697-395b82137eb9.png)

9锔忊儯 Wy艣wietl dane klienta, kt贸ry nie ma podanego adresu email.

馃挱 SELECT * FROM customers WHERE email IS NULL;

![image](https://user-images.githubusercontent.com/71427633/204326945-19617e6e-9557-4873-878a-0821ba973cfc.png)

馃敓 Wy艣wietl wszystkie filmy, kt贸rych cena wynosi powy偶ej 9$ oraz ich ID mie艣ci si臋 pomi臋dzy 2 i 8 movie_id.

馃挱 SELECT * FROM movies WHERE movie_id <= 8 AND movie_id >= 2 AND price > 9;

![image](https://user-images.githubusercontent.com/71427633/204328299-fa454a3d-12b9-4fdd-9bf4-8a76cc846ac7.png)

馃挱 SELECT * FROM movies WHERE movie_id < 8 AND movie_id > 2 AND price > 9;

![image](https://user-images.githubusercontent.com/71427633/204328399-f89e3676-f80b-4023-aef8-a782d186ff2c.png)

# **Task 6**
## Subtask 1

1锔忊儯1锔忊儯 Pope艂ni艂am b艂膮d wpisuj膮c nazwisko Ani Miler 鈥? wpisa艂am Muler. Znajd藕 i zastosuj funkcj臋, kt贸ra poprawi m贸j karko艂omny b艂膮d 馃檲

馃挱 UPDATE customers SET surname = "Miler" WHERE customer_id = 3;

![image](https://user-images.githubusercontent.com/71427633/205694602-a1b211dc-9de1-4700-bc28-da2d5c27faed.png)

1锔忊儯2锔忊儯 Pobra艂am za du偶o pieni臋dzy od klienta, kt贸ry kupi艂 w ostatnim czasie film o id 4. 
      Korzystaj膮c z funkcji join sprawd藕, jak ma na imi臋 klient i jakiego ma maila. W celu napisania mu wiadomo艣ci o pomy艂ce fantastycznej szefowej.

馃挱 SELECT sale.movie_id, customers.email FROM sale INNER JOIN customers ON sale.customer_id = customers.customer_id;

![image](https://user-images.githubusercontent.com/71427633/205697231-c8d4fc4f-76ce-4070-a3bc-4ada8bfcd1bf.png)

1锔忊儯3锔忊儯 Na pewno zauwa偶y艂a艣, 偶e sprzedawca zapomnia艂 wpisa膰 emaila klientce Patrycji. Uzupe艂nij ten brak wpisuj膮c: pati@mail.com

馃挱 UPDATE customers SET email = 'pati@mail.com' WHERE customer_id=4;

![image](https://user-images.githubusercontent.com/71427633/205697640-66687f61-bddf-41e2-924e-a77e9e6986bf.png)

1锔忊儯4锔忊儯 Dla ka偶dego zakupu wy艣wietl, imi臋 i nazwisko klienta, kt贸ry dokona艂 wypo偶yczenia oraz tytu艂 wypo偶yczonego filmu. 
(wykorzystaj do tego funkcj臋 inner join, zastan贸w si臋 wcze艣niej, kt贸re tabele Ci si臋 przydadz膮 do wykonania 膰wiczenia).

馃挱 SELECT sale.movie_id, sale.customer_id, customers.name, customers.surname, movies.title 
FROM ((sale 
INNER JOIN customers ON sale.customer_id = customers.customer_id)
INNER JOIN movies ON sale.movie_id = movies.movie_id);

![image](https://user-images.githubusercontent.com/71427633/205699895-cd56bec1-ce89-498b-88b6-7fe8bdb325b0.png)

1锔忊儯5锔忊儯 W celu anonimizacji danych, chcesz stworzy膰 pseudonimy swoich klient贸w. 
- Dodaj kolumn臋 o nazwie 鈥榩seudonym鈥? do tabeli customer,
- Wype艂nij kolumn臋 w taki spos贸b, aby pseudonim stworzy艂 si臋 z dw贸ch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling 鈫? Nag

馃挱 SELECT *, CONCAT(SUBSTRING(name, 1, 2), SUBSTRING(surname, LENGTH(surname), 1)) AS pseudonim FROM customers;

![image](https://user-images.githubusercontent.com/71427633/205709549-139cb15e-4bec-463e-bea2-92d7ad3e035f.png)

1锔忊儯6锔忊儯 Wy艣wietl tytu艂y film贸w, kt贸re zosta艂y zakupione, wy艣wietl tabel臋 w taki spos贸b, aby tytu艂y si臋 nie powtarza艂y.

馃挱 SELECT DISTINCT sale.movie_id, movies.title FROM sale INNER JOIN movies ON sale.movie_id = movies.movie_id;

![image](https://user-images.githubusercontent.com/71427633/205709998-391311d8-3551-40bb-86f9-916403d14dcf.png)

1锔忊儯7锔忊儯 Wy艣wietl wsp贸ln膮 list臋 imion wszystkich aktor贸w i klient贸w, a wynik uporz膮dkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

馃挱 SELECT name FROM actors UNION SELECT name FROM customers ORDER BY name;

![image](https://user-images.githubusercontent.com/71427633/205711051-6dad98ef-d950-4cdb-8f99-245aff3d8539.png)

1锔忊儯8锔忊儯 Polsk臋 opanowa艂a inflacja i nasz sklepik z filmami r贸wnie偶 dotkn膮艂 ten problem. 
Podnie艣 cen臋 wszystkich film贸w wyprodukowanych po 2000 roku o 2,5 $ (Pami臋taj, 偶e dolar to domy艣lna jednostka- nie u偶ywaj jej nigdzie).

馃挱 UPDATE movies SET price = price + 2.5 WHERE year_of_production > 2000;

![image](https://user-images.githubusercontent.com/71427633/205711677-ded4d702-04b6-4f5d-81a3-2233f6e16114.png)

1锔忊儯9锔忊儯 Wy艣wietl imi臋 i nazwisko aktora o id 4 i tytu艂 filmu, w kt贸rym zagra艂

馃挱 SELECT cast.actor_id, actors.name, actors.surname, movies.title 
FROM ((cast 
INNER JOIN actors ON cast.actor_id = actors.actor_id)
INNER JOIN movies ON cast.movie_id = movies.movie_id)
WHERE cast.actor_id = 4;

![image](https://user-images.githubusercontent.com/71427633/205713111-edf971bb-ad67-49be-9854-26e2c99c5cf2.png)

2锔忊儯0锔忊儯 A gdzie nasza HONIA!? Dodaj do tabeli customers now膮 krotk臋, 
gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa

馃挱 INSERT INTO customers (customer_id, name, surname, email, pseudonim)
VALUES (7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa');

## Subtask 2

Wynik testu Ecru: 13/15
