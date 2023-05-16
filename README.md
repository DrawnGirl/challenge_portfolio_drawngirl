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

📎👉 <a href="https://docs.google.com/spreadsheets/d/1SrheTq43fNrCxlAWMDvzKuV10O1w7IIIHxNkFuNHEHQ/edit?usp=sharing">Mobile Test Case</a>

## Subtask 2

📎👉 <a href="https://docs.google.com/spreadsheets/d/1W5_lQwj8pds8YRSkElBHx0JGre-dbL4WlcbUuOSdRQ8/edit?usp=sharing">Bug Reports</a>

## Subtask 3

1. Jest to aplikacja do wystawiania róznych ogłoszeń oraz do przeglądania już wystawionych ofert.
2. Uzytkownikiem końcowym są zarówno zwykli użytkownicy jak i firmy.
3. Myślę, że poruszanie się po aplikacji jest intuicyjne a różne opcje do wyboru są dobrze opisane. Jest dużo opcji sortowania oraz filtrowania ogłoszeń i kategorii.
4. Wydłużyłabym sesję logowania. Aplikacja często wylogowuje użytkownika, jeśli nie korzysta z niej przez kilka dni. Z tego powodu przestają przychodzić powiadomienia np. o nowych wiadomościach lub aktualności na temat obserwowanych/wystawionych ogłoszeń.
5. Przy testowaniu aplikacji mobilnych trzeba byc gotowym na większą ilość wariantów różnych urządzeń, na których użytkownicy będą korzystać z danej aplikacji. Użytkownicy urządzeń mobilnych mają inne priorytety i wymagania niż uzytkownicy aplikacji internetowych. Myślę jednak, że daje to większe pole do popisu dla testerów i to jest fajne 😁
