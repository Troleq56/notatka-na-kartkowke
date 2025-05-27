# Odsyłacze

> odsyłacze - linki (głównie) mozna podac sciezke do linka pliku html lub php ewentualnie strony po http np [http://wp.pl/](http://wp.pl/) ostatnia mozliwosc to # i tu mozemy po hashu dodac nazwe ID jakiegos elementu html by do niego przesunelo
> 
> **_struktura odsylacza_**
> 
> `<a href="./sciezka/dostrony.html">to co klikacie by przenioslo xD</a>`

# Formularze

> | znacznik | co on robi |
> | --- | --- |
> | \<input type="text"> | tworzy pole tekstowe cn |
> | \<input type="radio"> | tworzy pole jednokrotnego wyboru takie kóleczko xD |
> | \<input type="checkbox"> | tworzy pole wielokrotnego wyboru kwadracik do zaznaczenia ptaszkiem |
> | \<input type="submit"> | przycisk |
> | \<input type="password"> | pole do hasla zamienia znaki na \* |

to są takie podstawowe rzeczy jak chodzi o rodzaje to wiecej macie [tutaj](https://www.w3schools.com/html/html_form_input_types.asp)

> ## atrybuty do pól formularzy
> 
> | Atrybut | Opis |
> | --- | --- |
> | name | Nazwa pola (klucz przy wysyłaniu danych) |
> | value | Wartość domyślna pola |
> | type | Typ danych (text, password, email, submit, itd.) dla |
> | placeholder | Tekst pomocniczy wyświetlany, gdy pole jest puste |
> | required | Wymusza wypełnienie pola przed wysłaniem formularza |
> | readonly | Pole tylko do odczytu |
> | disabled | Pole nieaktywne (nie można go zaznaczyć ani edytować) |
> | maxlength | Maksymalna liczba znaków |
> | min / max | Minimalna / maksymalna wartość dla pól typu liczbowego lub daty |

# Ogólnie to te inputy muszą być w \<form\>

> `form` to ten znacznik, w którym umieszczacie wszystkie pola. On też ma swoje główne parametry, które są potrzebne głównie jak macie php ale no xD:

| Atrybut            | Opis |
|--------------------|------|
| `action`           | Tutaj podajesz adres, do którego mają zostać przesłane dane po zatwierdzeniu formularza. |
| `target`           | Określa, gdzie pojawi się odpowiedź z serwera: <br> `_self` – na tej samej stronie <br> `_blank` – otwiera w nowej karcie |
| `method`           | Określa metodę protokołu HTTP, z jakiej ma korzystać zapytanie. <br> Najczęściej jest to `POST`, ale mogą być też inne, np. `GET`, `PUT`, `PATCH`, `DELETE`. |
| `name`             | Nazwa formularza. |
| `enctype` *(opcjonalny)* | Określa format danych przekazywanych w zapytaniu, np. `application/x-www-form-urlencoded`, `multipart/form-data` (dla plików), `text/plain`. |
