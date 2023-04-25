# TASK 1
## Subtask 1
7/10 pkt 😎
## Subtask 3
Hej! Mam na imię Iza, ale lubię też formę Issabel 😉 Dołączyłam do projektu ponieważ jakieś 2 miesiące temu zainteresowałam się testowaniem manualnym. Studiowałam Informatyke, konkretnie PHP i Magento w kierunku Developera Ecommerce ale nie do końca mi to "leżało". Jakiś czas temu wzięłam udział w maratonie testowania od GoIT i poczułam, że to może być dobry kierunek w którym chciałabym podążać w swoim życiu zawodowym.

Głównie chciałabym się dowiedzieć jak ten świat wygląda w praktyce, a nie tylko uczyć się suchej teorii ktora potem i tak będzie wykorzystywana w ISTQB, raz na ruski rok albo wcale 😜

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
