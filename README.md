# $\textcolor{green}{Task\ 1}$

## $\textcolor{green}{Subtask\ 1}$
> __Zapisz ilość punktów, którą udało Ci się uzyskać podczas testu.__
> * _**10** punktów_ :+1:
  
## $\textcolor{green}{Subtask\ 3}$

_<p align="justify">Zdecydowałam się na udział w programie ponieważ w mojej aktualnej pracy jestem bardziej zaangażowana w projekty optymalizacyjne i automatyzujące procesy niż księgowość :woman_office_worker:. Testuję to co dział IT przygotował według moich wytycznych, szukam błędów. Nauczyłam się VBA żeby praca z excelami dla mnie i członków zespołu była przyjemniejsza. Zbliżając się do brzegu dlaczego biorę udział w programie. Tak mi się spodobało to szukanie błędów, które od kilku lat wykonuję w pracy, że chciałbym zajmować się tym zawodowo.</p>_

_<p align="justify">Uczę się i ten program jest kolejnym krokiem żeby wiedzieć więcej i eliminować błędy.</p>_
  
  
## $\textcolor{green}{Subtask\ 4}$

__1. Na czym polega ta aplikacja? Do czego służy?__
  * Aplikacja $\textcolor{red}{Scouts\ Panel}$ służy do _zarządzania graczami, meczami i do tworzenia raportów._
  * <p align="justify">Działanie aplikacji polega na tworzeniu bazy profili zawodników piłki nożnej. Aplikacja pozwala stworzyć profil z informacjami takimi jak m.in. wzrost, wiek, waga, klub czy pozycja. Aplikacja umożliwia dodawanie informacji o rozegranych przez zawodnika meczach jak również generacje raportu z analizą sportowej aktywności podczas rozgrywki. Aplikacja umożliwia gromadzenie danych o zawodnikach, generowanie raportów meczowych i recenzje potencjału zawodnika.</P>
  
__2. Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!).__
__wymienie 10 przykładowych funkcjonalności__

| FUNKCJONALNOŚĆ | ZACHOWANIE  |OPIS|
|----------------|:------------|:------------|
| Logowanie do aplikacji          | Aplikacja powinna pozwolić na logowanie przy użyciu  loginu i hasła.     |Na stronie głównej znajduje się ekran służący do logowania z polami: Login [wymagane] i Hasło [wymagane].|
| Odzyskiwanie hasła          |Aplikacja powinna pozwolić na odzyskanie hasła poprzez naciśnięcie guzika "Przypomnij hasło", wpisanie E-maila i kliknięcie na guzik "Wyślij".      |Po kliknięciu na link "Przypomnij hasło" użytkownik zostaje przekierowany na osobną stronę, na której może odzyskać hasło z następującym polem E-mail [wymagane].|
|Wylogowanie z aplikacji     | Aplikacja powinna pozwolić na wylogowanie przez naciśnięnie guzika "Wyloguj".    |Po zalogowanie, po lewej stronie ekranu znajduje się przycisk "Wyloguj", który znajduje się na każdym ekranie.|
|Dodanie nowego gracza    | Aplikacja powinna pozwolić na przejście do formularza profilu nowego gracza przez naciśnięnie na stronie głównej guzika "DODAJ GRACZA".    |Po zalogowanie z poziomu widoku strony głównej w centralnej części ekranu znajduje się guzik służący do dodania profilu nowego gracza "DODAJ GRACZA".|
|Dostęp do profilu graczy    | Aplikacja powinna pozwolić na przejście do bazy graczy przez naciśnięnie guzika "Gracze".   |Po zalogowanie, po lewej stronie ekranu znajduje się przycisk "GRACZE", który znajduje się na każdym ekranie.|
|Dostęp do profilów graczy    | Aplikacja powinna pozwolić na przejście do bazy graczy przez naciśnięnie guzika "Gracze".   |Po zalogowanie, po lewej stronie ekranu znajduje się przycisk "GRACZE", który znajduje się na każdym ekranie.|
|Edycja danych o graczu  | Aplikacja powinna pozwolić na edycje danych o graczu i podlegają jej takie same pola jak przy dodawaniu gracza.  |  Po lewej stronie ekranu znajduje się przycisk "GRACZE" jego wybór otwiera baze graczy.|
|Dodanie danych o meczu | Aplikacja powinna pozwolić na dodanie danych o meczu.  |  Po lewej stronie ekranu znajduje się przycisk "GRACZE" jego wybór otwiera baze graczy następnie po wyborze gracza na liści po lewej stronie ekranu pojawia się guzik wyboru "Mecze" po jego wyborze w lewym górnym rogu centralnej części ekranu widoczny jest guzik "+DODAJ MECZ". |
|Dostęp do raportów | Aplikacja powinna pozwolić na podgląd oraz dodanie nowego raportu.  |  Po lewej stronie ekranu znajduje się przycisk "GRACZE" jego wybór otwiera baze graczy następnie po wyborze gracza na liści po lewej stronie ekranu pojawia się guzik wyboru "Raporty" po jego wyborze w lewym górnym rogu centralnej części ekranu widoczny jest guzik "+DODAJ RAPORT" oraz możliwy jest podgląd zapisanych raportów. |

* <p align="justify">Dla mnie aplikacja i funkcjonalności nie są intuicyjne np. guzik dodania nowego gracza znajduje się tylko na stronie głównej w centralnej części ekranu, logiczniejsze byłoby stałe położenie tego guzika po lewej stronie nad guzikiem "GRACZE". Dodatkowo raporty widoczne są tylko z poziomu danego zawodnika mnie bardziej odpowiadałoby gdyby zarówno guzik "MECZE" jak i "RAPORTY" były widoczne stale na liście wyboru a już z poziomu tej wybranej dyspozycji odbywało się przypisanie do konkretnego zawodnika. Raporty widoczne w bazie nie jest znany ich status, czy są one dodane błędnie, ostateczne, zatwierdzone, brakuje również możliwości eksportu raportu jednego czy kilku. Gdy przejdę do "GRACZY" filtr wyboru mógłby zostać umieszczony jako belka na białym polu centralnie nad tabelą zawodników w której można wpisać jakiego zawodnika szukamy bez konieczności filtrowania przez dodatkowy guzik "Filter Table" ponieważ filtr który znajduje się na niebieskim polu obok nazwy aplikacji zlewa się z tłem i jego położenie nie jest intuicyjne. Na stronie głównej znajdują się także cztery prostokąty ze statystką: Ilość meczy, Ilość graczy, Ilość raportów, Ilość akcji. Dla mnie jako użytkownika byłoby miło gdybym mogła przejść do analityki każdego prostokąta przez jego kliknięcie. </p>

__3. Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?__
* <p align="justify">Nie podoba mi się, tak jak napisałam przy poprzednim pytaniu nie jest intuicyjna i wygląd nie jest przyjemny dla użytkownika. Strona główna położenie i rozmiar widocznych pól mógłby zostać lepiej przemyślany. Nie jest przyjemne dla oka to co widzę, puste pole na środku, informacje które wymagają przesunięcia ekranu suwakiem, załączam widok.</p>

![darescout](https://user-images.githubusercontent.com/121487022/212549101-1329cd9b-2a55-4c58-950d-fc6c87bdcb79.jpg)

__4. Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).__
* <p align="justify">Aplikacja nie jest intuicyjna i samo położenie przykładowego guzika dodania nowego zawodnika jest dla mnie nielogiczne. Dodanie zawodnika możliwe jest tylko z poziomu strony głównej. Co wymaga przy każdym kolejnym dodawaniu nowego zawodnika cofania się do tej strony. </p>

__5. Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)__

* <p align="justify"> Tak, zauważam. Są to m.in. przyjmowanie wartości ujemnych w formularzu dodawania nowego zawodnika w polach wzrost i waga. Kolejnym błędem w tym samym formularzu jest w polu data urodzenia możliwość dodania daty przyszłej czy też daty skrajnie odległej z przeszłości jak np. rok 1205. W tym samym formularzy przy parametrze "Pozycja główna" i "Pozycja alternatywna" można wpisać jakiekolwiek słowo czy liczbę nie mające związku z tymi pozycjami. Ponadto dodanie raportu o zawodniku wymaga aby w profilu zawodnika została uzupełniona informacja o województwie kiedy pole to nie jest wymagane.</p>

![image](https://user-images.githubusercontent.com/121487022/212550212-42309cf4-4687-4d16-9016-88feb21bd72b.png)


* <p align="justify">Dodatkowo kliknięcie guzika "Przypomnij hasło" a następnie "Wyślij" bez uzupełniania pola E- mail powoduje tak jak widoczne jest na załączonym obrazku wysłanie E-maila w próżnie.</p>

![image](https://user-images.githubusercontent.com/121487022/212550441-76d30c3d-ad51-4dcb-8b7f-8e1a37d0a83d.png)

## $\textcolor{green}{Subtask\ 5}$
* Jira - projekt: https://kaskaseeker.atlassian.net/jira/software/projects/CPK/boards/1 

# $\textcolor{red}{Task\ 2 }$
## $\textcolor{red}{Subtask\ 1}$
* https://docs.google.com/spreadsheets/d/1AEyh1ODwBvXqr6g5A_6cmBcwUVQD9E_2JIDubxtvawM/edit?usp=share_link
## $\textcolor{red}{Subtask\ 2}$
* https://docs.google.com/spreadsheets/d/1vuyt3FxnPkFPv3KshgpyYcHQEX91TwYYYGtV_gVzof8/edit?usp=share_link
## $\textcolor{red}{Subtask\ 3}$
> __Po co piszemy test case’y?.__
<p align="justify">Odpowiem na to pytanie na przykładzie. Ktoś wymyślił aplikacje, która pozwala na dostęp do wszystkich kont bankowych jakie użytkownik do tej aplikacji doda z jednej wspólnej aplikacji zamiast dedykowanej dla banku. I tak jest pomysł, twórca spisał jak aplikacja ma wyglądać, jak ma działać, jakie mają być funkcjonalności, jak aplikacja ma się zachować w przypadku próby nieuprawnionych dostępów etc. Test casy pozwalają krok po kroku sprawdzić wszystkie warstwy działania tej aplikacji z punktów widzenia różnych użytkowników takich jak twórca, haker, deweloper, support czy zwykły Kowalski, który będzie użytkownikiem końcowym tej aplikacje. Ponadto testy case umożliwią weryfikacje jak aplikacja współpracuje z innymi aplikacjami, bankami etc. Test case służą przede wszystkim sprawdzeniu przed oficjalnym udostepnieniem aplikacji użytkownikom, że spełnia on wymagania takie jak bezpieczeństwa, stabilności i nie narazi uzytkownika jak i własciciela na straty czy to finansowe czy reputacji. </p>:+1:

## $\textcolor{red}{Subtask\ 4}$
* https://docs.google.com/spreadsheets/d/1LoXivrbCj4B5XkPIkCuVfSC9KQlAXF_DWfj7_2iTi-s/edit?usp=share_link

# $\textcolor{blue}{Task\ 3 }$
## $\textcolor{blue}{Subtask\ 1}$
_Utworzenie formatki do zgłaszania błędów systemu._ - https://docs.google.com/spreadsheets/d/12EuJSMnDSLTuqU_cqPDJ0bmXj91PsR7cnLsZwDZrNfE/edit?usp=sharing
## $\textcolor{blue}{Subtask\ 2}$
_Testowanie według planów testów i raportowanie błędów._ - https://docs.google.com/spreadsheets/d/12EuJSMnDSLTuqU_cqPDJ0bmXj91PsR7cnLsZwDZrNfE/edit?usp=sharing
## $\textcolor{blue}{Subtask\ 3}$
_Raport z wykonanych testów_ - https://docs.google.com/document/d/1xY9QshU_hse6pFw2iFvYIwJFML68XYNK_6w2eU_ZSZE/edit?usp=sharing
## $\textcolor{blue}{Subtask\ 4}$
_Dla grupy i chętnych. Sesja testów eksploracyjnych._

# $\textcolor{yellow}{Task\ 4}$
**Testowanie aplikacji mobilnych**
## $\textcolor{yellow}{Subtask\ 1}$
_Utworzenie formatki do zgłaszania błędów systemu._ - https://docs.google.com/spreadsheets/d/1pFjhnMcJdCHPFbncKNLhGnc0equoQdS3hu2Hpt0OZl8/edit?usp=share_link
## $\textcolor{yellow}{Subtask\ 2}$
_Testowanie eksploracyjne i raportowanie błędów._ -  https://focusly.co/ / https://docs.google.com/spreadsheets/d/1pFjhnMcJdCHPFbncKNLhGnc0equoQdS3hu2Hpt0OZl8/edit?usp=share_link
## $\textcolor{yellow}{Subtask\ 3}$
_Do czego służy ta aplikacja_ 

__1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?__
> * Aplikacja $\textcolor{red}{Focusly\}$ skierowana jest do osób którym wydaje się że, spokojony głos innej osoby, motywujące treści w przekazie plus kojące muzyka są lekarstwem na skołatane nerwy.
> 
__2. Kto ma być użytkownikiem końcowym aplikacji?__
> * Każdy kto potrzebuję tego typu treści.

__3. Czy według Ciebie aplikacja jest user friendly?__
>* <p align="justify">Design na plus, ładne kolory, przejrzyste menu. Na minus jest widoczny loading podczas przełączenia np. wersji języka, do korzystania z konta wymagane jest oznaczenie zgody do na wykorzystania technologii pozwalających na zbieranie i analizowanie przez focusly informacji o mnie i o tym jak korzystam z aplikacji (...) takie śledzenie nie za bardzo mi się podoba. Dodatkowo powiadomienia ustawione są jako domyślnie włączone co dla mnie jest minusem, jeszcze dobrze nie włączyłam apki a już przychodzą z niej powiadomienia. Na minus dodatkowo jest skalowanie, niektóre opisy nie zmieściły się w polach do tego przeznaczonych a suwak nie jest dostępny. Podobnie po przejściu do "Twórców" nazwiska są dziwnie podzielone, niezgodnie z zasadami. Na minus jeszcze położenie na ekranie głównym guzika Profil powinien być dostępny na dolnej belce a nie gdzieś na górze, Oraz to co mnie najbardziej denerwowało to brak przy wyłącznym audio opcji stop, jest pausa oraz play ale stop brak.</p>

__4. Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?__
>* <p align="justify">Na pewno dodałam bym przy audio opcje stop. Dodałam być także opcje budowania playlisty, dodałam być również opcje zmiany ustawień nagrań, nie tylko głośności ale również tonu głosu, szybkości. Dodatkowo gdy wysyłam do kogoś linka do tej aplikacji to po jego włączeniu widoczna jest tylko opcja z subskrypcją brakuje informacji, że z aplikacji można korzystać w trybie gościa bez konieczności od razu podawania danych do karty kredytowej.</p>

__5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?__
>* <p align="justify">Aplikacja natywna nie wymaga przeglądarki i działa offline. Aplikacja internetowa wymaga przeglądarki i dostępu do internetu.</p>

## $\textcolor{yellow}{Subtask\ 4}$
_Dla grupy i chętnych. Sesja testów eksploracyjnych._


# $\textcolor{purple}{Task\ 5 }$
## $\textcolor{purple}{Subtask\ 3}$
 _1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname._
 
  SELECT * FROM actors ORDER BY surname asc;
 ![1](https://user-images.githubusercontent.com/121487022/218339137-05f58b8a-d6bf-48e4-9516-cd6064ffa09f.jpg)

 _2. Wyświetl film, który powstał w 2019 roku._
 
  SELECT * FROM movies WHERE year_of_production='2019';
  ![1](https://user-images.githubusercontent.com/121487022/218338084-b1c6c81d-96e5-4339-bf5c-42bc2babb4d3.jpg)
 _3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem._
 
  SELECT * FROM movies WHERE year_of_production BETWEEN 1900 AND 1999;
  ![1](https://user-images.githubusercontent.com/121487022/218338171-67072436-d53e-482d-9ad8-f045ac231ecc.jpg)
 _4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$._
 
  SELECT title, price FROM movies WHERE price <7;
  ![1](https://user-images.githubusercontent.com/121487022/218338303-e17d891a-9a50-4ba6-b847-850941a3ddcb.jpg)
 _5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN._
 
  SELECT * FROM actors WHERE actor_id >=4 and actor_id <=7;
  ![1](https://user-images.githubusercontent.com/121487022/218338431-7d245003-0854-447c-9521-74bb8d2c5345.jpg)
 _6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny._
 
  SELECT * FROM customers WHERE customer_id IN(2,4,6);
  ![1](https://user-images.githubusercontent.com/121487022/218338525-70a8556a-9dd4-492e-86fb-dc8300e8c5a0.jpg)
 _7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN._
 
   SELECT * FROM customers WHERE customer_id IN(1,3,5);
 ![1](https://user-images.githubusercontent.com/121487022/218338614-3a213de3-e904-4cef-a52c-955336f9273c.jpg)
 _8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”._
 
  SELECT * FROM actors WHERE name LIKE 'AN%';
 ![1](https://user-images.githubusercontent.com/121487022/218338713-881c1a79-659e-41a6-8e45-4233a17f68c8.jpg)
 _9. Wyświetl dane klienta, który nie ma podanego adresu email._
 
  SELECT * FROM customers WHERE email IS NULL;
 ![1](https://user-images.githubusercontent.com/121487022/218338771-9e7c2882-3b09-461f-9e68-ade9f6b4dda5.jpg)
 _10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id._
 
  SELECT * FROM movies WHERE price >9 AND movie_id BETWEEN 2 AND 8;
 ![1](https://user-images.githubusercontent.com/121487022/218338904-f496ea89-b2f8-43c9-9b4f-cae03144482a.jpg)


# $\textcolor{fuchsia}{Task\ 6 }$
## $\textcolor{fuchsia}{Subtask\ 1}$

***
***Kaśka***
