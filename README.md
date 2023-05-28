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


