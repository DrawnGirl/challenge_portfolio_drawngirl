# TASK 1
## Subtask 1
7/10 pkt 😎
## Subtask 3
Hej! Mam na imię Iza, ale lubię też formę Issabel 😉 Dołączyłam do projektu ponieważ jakieś 2 miesiące temu zainteresowałam się testowaniem manualnym. Studiowałam Informatyke, konkretnie PHP i Magento w kierunku Developera Ecommerce ale nie do końca mi to "leżało". Jakiś czas temu wzięłam udział w maratonie testowania od GoIT i poczułam, że to może być dobry kierunek w którym chciałabym podążać w swoim życiu zawodowym.

Głównie chciałabym się dowiedzieć jak ten świat wygląda w praktyce, a nie tylko uczyć się suchej teorii ktora potem i tak będzie wykorzystywana w ISTQB, raz na ruski rok albo wcale 😜

📎👉 <a href="https://drive.google.com/drive/folders/1HnLv-Wl9ri-DuomHIXAqFkM126pXqJoW?usp=sharing">Mój link do folderu w GoogleDrive</a>

## Subtask 4
* Aplikacja służy do gromadzenia informacji o graczach, meczach i do dodawania raportów.

* Dodawanie graczy: 
    - przycisk dodawania nowego gracza powinien być w zakładce "Gracze" lub w obu zakładkach (Strona Główna i Gracze).  
    W formularzu dodawania gracza:
      - Można podać datę urodzenia z przyszłości - np 2032 rok
      - Pole "Języki" najlepiej aby zawierało rozwijaną listę z językami do wyboru, zamiast ręcznego wpisywania
      - "Profil facebook" powinien akceptować tylko linki
      - W polu "Telefon" można wpisać więcej niż 9 cyfr, najlepiej aby zostało to ograniczone do wyboru krajowego nr (np +48) i następnie 9 cyfr
      - Pola "Waga" oraz "Wzrost" nie powinny akceptować liczb ujemnych i dobrze by było dać tam jakiś konkretny zakres wartości
      - Po wpisaniu złego formatu wyskakuje informacja, że nie udało się zaktualizować danych zawodnika, ale brakuje podświetlenia pola które zostało źle uzupełnione oraz     co zostało źle wpisane
      - Co oznacza pole "Łączy nas piłka" i "90 minut")? Co należy tam wpisać?
      - Przycisk "Clear" nie działa
* Dodawanie meczy:
    - brakuje przycisku dodawania meczu na stronie głównej  
    W formularzu dodawania meczu:
      - można podać date meczu w przód, może jakieś ograniczenie do dnia teraźniejszego?
      - W polach "Czas gry" i "Numer" po wpisaniu za dużej ilości cyfr, zapisaniu formularza i odświeżeniu strony wyskakuje notacja (np 1e+82), powinna wyskakiwać przy próbie zapisu że wpisane są zbyt duze wartości
      - Przycisk "Clear" nie działa
* Rozpoczęcie meczu:
    - Można dodać więcej niż 2 połowy
* Raport źle się skaluje zarówno przy otwartych DevToolsach jak i w widoku mobilnym
* W zakładce "Gracze" wyświetlona lista graczy ma dwie ramki, padding jest w tym wypadku zbędny, źle to wygląda dla oka
* Opcje dodawania meczu oraz raportów powinny znajdować się także na stronie głównej
* Stronie przydałby się tryb ciemny oraz udogodnienia dla osób ze ślepotą barw

# TASK 2

## Subtask 1

📎👉 <a href="https://docs.google.com/spreadsheets/d/1YYV-omBHwfXd2Nbd3gPLC-5eoFfGCombsxRiBuFFWa4/edit?usp=sharing">Zadanko 1</a>

## Subtask 2

📎👉 <a href="https://docs.google.com/spreadsheets/d/1mO2sG1nVOD55XlaCMJivStgHn0kSA8KTPMmdEO4ljZY/edit?usp=sharing">Zadanko 2</a>

## Subtask 3
Piszemy Test Case'y aby po każdej zmianie w projekcie można było przeprowadzić te same kroki i sprawdzić czy aplikacja działa tak samo. Myślę, że jest to przydatne nie tylko dla samych testerów aby nie musieli wykonywać dwa razy tej samej pracy, ale również dla programistów którzy mogą sprawdzić swój kod jeszcze przed wysłaniem go dalej. A przynajmniej mogliby to robić ;)

# TASK 3

## Subtask 1

📎👉 <a href="https://drive.google.com/drive/folders/1D1qdifDkuaBR_XLjWw76bCe12DEEDog7?usp=sharing">Folder do zadania</a>

## Subtask 2

📎👉 <a href="https://docs.google.com/spreadsheets/d/1mO2sG1nVOD55XlaCMJivStgHn0kSA8KTPMmdEO4ljZY/edit?usp=sharing">Test case</a>

📎👉 <a href="https://docs.google.com/spreadsheets/d/1kds9_MwOZCMiJhTvuCZW15Hdr9TIowSmDQOorX0ybb0/edit?usp=sharing">Bug report</a>

## Subtask 3

📎👉 <a href="https://docs.google.com/document/d/1Gu6HebRCrGp9FNibCCU9dV4L6incLgXFBDPDvIshpuk/edit?usp=sharing">Test report</a>

# TASK 4

## Subtask 1

📎👉 <a href="https://docs.google.com/spreadsheets/d/1rEmvnlmlfQOP9lMbGRDrnqdIKBZGE7bIegh1aOfewkM/edit?usp=sharing">Mobile Bug report</a>

## Subtask 2

📎👉 <a href="https://docs.google.com/spreadsheets/d/1D01RFEOdUBrRwOYDSxcmORUKASaRBM1OtcOarzpPBNA/edit?usp=sharing">OLX Bug Reports</a>

## Subtask 3

1. Jest to aplikacja do wystawiania róznych ogłoszeń oraz do przeglądania już wystawionych ofert.
2. Uzytkownikiem końcowym są zarówno zwykli użytkownicy jak i firmy.
3. Myślę, że poruszanie się po aplikacji jest intuicyjne a różne opcje do wyboru są dobrze opisane. Jest dużo opcji sortowania oraz filtrowania ogłoszeń i kategorii.
4. Wydłużyłabym sesję logowania. Aplikacja często wylogowuje użytkownika, jeśli nie korzysta z niej przez kilka dni. Z tego powodu przestają przychodzić powiadomienia np. o nowych wiadomościach lub aktualności na temat obserwowanych/wystawionych ogłoszeń.
5. Przy testowaniu aplikacji mobilnych trzeba byc gotowym na większą ilość wariantów różnych urządzeń, na których użytkownicy będą korzystać z danej aplikacji. Użytkownicy urządzeń mobilnych mają inne priorytety i wymagania niż uzytkownicy aplikacji internetowych. Myślę jednak, że daje to większe pole do popisu dla testerów i to jest fajne 😁

# TASK 5

## Subtask 3

   1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
        ```sql
        SELECT * FROM actors ORDER BY surname ASC;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/882a14e2-565c-408f-bf78-52ea658d6d51)
   2. Wyświetl film, który powstał w 2019 roku.
        ```sql
        SELECT * FROM movies WHERE year_of_production=2019;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/c9a9c415-e25b-4e30-a105-3c650439fd50)
   3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
        ```sql
        SELECT * FROM movies WHERE year_of_production BETWEEN 1900 AND 1999;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/fa20d008-a655-4ecc-996c-2e05152cf2d9)
   4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$
        ```sql
        SELECT title, price FROM movies WHERE price < 7;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/a7306eca-46b4-4809-a37a-db0392de12bc)
   5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
        ```sql
        SELECT * FROM actors WHERE actor_id >= 4 AND actor_id <= 7;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/6bf9ea75-f361-4116-a0e2-a950177dbbd6)
   6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.
        ```sql
        SELECT * FROM customers WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/bd17437b-3c21-438c-857f-ad73742bc59a)
   7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.
        ```sql
        SELECT * FROM customers WHERE customer_id IN ('1','3','5');
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/762c4d23-cd1a-4a53-8528-69918375209f)
   8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
        ```sql
        SELECT * FROM actors WHERE name LIKE 'An%';
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/553abe74-8791-4149-b294-c7095ec39cb8)
   9. Wyświetl dane klienta, który nie ma podanego adresu email.
        ```sql
        SELECT * FROM customers WHERE email IS NULL;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/e1f91b7a-0d6b-4356-8b22-a8f7542fe168)
   10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
        ```sql
        SELECT * FROM movies WHERE price > 9 AND movie_id BETWEEN 2 AND 8;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/c712553d-36bd-4d24-a32a-cc37233ff7fd)

# TASK 6

## Subtask 1

  11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈
        ```sql
        UPDATE `customers` SET surname = 'Miler' WHERE customer_id = 3;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/567b68e7-d39f-4623-9cc8-ab7b5ead8f4d)
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/25e071e2-dab7-4a85-bd60-845f395366a5)
  12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.
        ```sql
        SELECT customers.name, customers.email FROM sale INNER JOIN customers ON sale.movie_id=4 ORDER BY sale.sale_date DESC LIMIT 1;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/9e9b0cbb-2dbf-4761-85db-ec0adbad83c3)
  13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com
        ```sql
        UPDATE `customers` SET email = 'pati@mail.com' WHERE customer_id = 4;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/235ff6aa-dfbd-47c1-b089-be4acbc8c66d)
  14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).
        ```sql
        SELECT customers.name, customers.surname, movies.title FROM sale INNER JOIN customers ON sale.customer_id=customers.customer_id INNER JOIN movies ON movies.movie_id=sale.movie_id;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/93e50101-566e-44d3-93a6-a0bb6fc1753c)
  15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag
        ```sql
        ALTER TABLE customers ADD COLUMN pseudonym VARCHAR(3) GENERATED ALWAYS AS (CONCAT(LEFT(name, 2), RIGHT(surname, 1))) STORED;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/3ea3c843-3b9e-4d2e-a490-6e4dd002edfc)
  16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.
        ```sql
        SELECT DISTINCT movies.title FROM movies INNER JOIN sale ON sale.movie_id=movies.movie_id;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/23af16a8-42cd-42fa-8128-fc8a285744a7)
  17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)
        ```sql
        SELECT name FROM actors UNION SELECT name FROM customers ORDER BY name ASC;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/429882c4-2dc9-4a6e-bff9-6f8b8bda396f)
  18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).
        ```sql
        UPDATE movies SET price=price+2.5 WHERE year_of_production>2000;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/4b84de1e-a7de-4643-90b0-0530551eef30)
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/5e44ba8c-39fc-42b1-9cf7-7c3a157338af)
  19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał
        ```sql
        SELECT actors.name, actors.surname, movies.title FROM actors INNER JOIN cast ON actors.actor_id = cast.actor_id INNER JOIN movies ON cast.movie_id = movies.movie_id WHERE actors.actor_id = 4;
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/769a4dcc-b91a-4253-bf4e-774881d669ce)
  20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa
        ```sql
        INSERT INTO customers (customer_id, name, surname, email, pseudonym) VALUES (7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa');
        ```
        ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/3c46815d-78a1-48d4-b856-0721d0b9140b)
## Subtask 2 
Wynik testu 👇
   ![image](https://github.com/DrawnGirl/challenge_portfolio_drawngirl/assets/83364852/9d8454da-158a-46f4-9635-33b1487e39fd)
Nie jest źle, ale mogło być lepiej 😅
