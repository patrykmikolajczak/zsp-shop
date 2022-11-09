# Sklep
Do stworzenia prosta platforma typu olx.
Czyli strona pozwalająca wystawiać przedmioty, które chcemy sprzedać.
Jednocześnie pozwalająca kupić przedmioty u innych sprzedających

## Baza danych 4pkt.
Zaprojektuj bazę danych pozwalającą przechowywać dane:
użytkowników,
ofert wystawionych przez użytkowników, 
zakupy użytkowników,
administratorów (mają działać podobnie jak użytkownicy i pozwalać na zalogowanie się),
Baza ma być tak zaprojektowana żeby w przyszłości można było dodać opcję rejestracji użytkowników. 
W repozytorium musi znaleźć się projekt stworzony w MySQL Workbench i pliki SQL pozwalające stworzyć bazę danych i uzupełnić ja danymi.
- projekt bazy w MySQL Workbench - 1pkt
- skrypt SQL pozwalający stworzyć bazę danych i wypełnić ją danymi - 1pkt
- uwzględnienie możliwości logowania użytkownika - 1pkt
- uwzględnienie możliwości logowania administratora - 1pkt

## Portal 19,5pkt
Proszę o stworzenie strony w języku php.
Głównie pod ocenę będą brane stworzone zapytania w języku SQL.
Wygląd strony będzie oceniany tylko na prośbę ucznia.
Portal będzie podzielony na kilka stron.
### logowanie 1,5 pkt
Zacznij od stworzenia zapytania pozwalającego sprawdzić czy dane klienta są pozwalają na zalogowanie. 1pkt
Formularz w html z polami login (email, login zależnie co jest w bazie danych) i hasło. 0,25pkt
W tym samym pliku php dodać przechwycenie danych z formularza i wykonanie zapytania. 0,25pht
Trzeba dodać informację o tym kto jest zalogowany (np. w ciasteczku lub w sesji)
### rejestracja 1,5 pkt
Zacznij od stworzenia zapytania pozwalającego dodać nowego użytkownika. 1pkt
Formularz w html z polami login (email, login zależnie co jest w bazie danych) i hasło. 0,25pkt
W tym samym pliku php dodać przechwycenie danych z formularza i wykonanie zapytania. 0,25pht
### widok moich ofert 4 pkt
#### lista
Zacznij od stworzenia zapytania pobierające oferty konkretnego użytkownika. 1pkt
Lista prezentująca oferty 0,25pkt
#### edycja 2,25pkt
Zacznij od stworzenia zapytania pozwalającego na aktualizację danych istniejącej oferty. 1pkt
Stwórz zapytanie pobierające szczegóły konkretnej oferty. 1pkt
Formularz edycji oferty 0,25pkt
### widok moich zakupów 1,5pkt
Zacznij od stworzenia zapytania pobierające oferty zakupione przez konkretnego użytkownika. 1pkt
Po czym stwórz zapytanie pobierające dane o konkretnej ofercie. 0,25pkt
Lista prezentująca te oferty. 0,25pkt
### widok dodawania oferty 1,25pkt
Zacznij od stworzenia zapytania pozwalającego na dodanie nowej oferty. 1pkt
Formularz dodawania nowej oferty. 0,25pkt
### widok listy ofert 1,75pkt
Zacznij od stworzenia zapytania pobierającego wszystkie niekupione oferty. 1pkt
Po czym stwórz zapytanie pobierające dane o konkretnej ofercie. 0,25pkt
Stwórz listę ofert w html i php. 0,25pkt
Stwórz widok szczegółów oferty w html i php (tutaj musi pobierać konkretną ofertę). 0,25pkt
### widok finalizacji zakupu oferty 1,75pkt
Zacznij od stworzenia zapytania pozwalającego na zakup oferty. 1pkt
Po czym stwórz zapytanie pobierające dane o konkretnej ofercie. 0,25pkt
Stwórz widok zakupu oferty, prezentacja ceny. 0,25pkt
Stwórz widok finalizacji, informacja że produkt został kupiony. 0,25pkt

