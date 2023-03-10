# Task 1

## Subtask 1

10 punktów!

## Subtask 3

**Dzień dobry!** 


Mam na imię Milena. Uczestniczę w *Dare It Challenge* ponieważ chciałabym zobaczyć jak wygląda praca *testera manualnego*. Mam nadzieję, że dzięki temu wyzwaniu uda mi się zdobyć praktyczne umiejętności i stworzyć swoje pierwsze portfolio, którym będę mogła się pochwalić w niedalekiej przyszłości. Wierzę, że te siedem tygodni będzie nie tylko nauką cennych umiejętności pod okiem mentorek ale też i dobrą zabawą!
## Subtask 4
***Aplikacja Scouts Panel***

* Weryfikacja funckjonalności logowania do aplikacji:


Po otwarciu strony pod adresem: https://scouts-test.futbolkolektyw.pl/pl, zostaje wyświetlony panel logowania (Scouts Panel).


Przy wprowadzeniu poprawnego loginu jak i hasła możemy zalogować się do aplikacji, za pomocą przycisku Zaloguj (możliwa jest również zmiana języka aplikacji na język angielski). 


Przy wprowadzeniu prawidłowego loginu ale nie wpisaniu hasła, formularz logowania wyświetla następujące informacje: Please provide your password oraz Przypomnij hasło. 


Przy wprowadzeniu poprawnego loginu ale wpisaniu błędnego hasła, formularz logowania wyświetla następujące informacje: Identifier or password invalid oraz Przypomnij hasło. 


Przy wprowadzeniu błędnego loginu jak i błędnego hasła, formularz logowania wyświetla następujące informacje: Identifier or password invalid oraz Przypomnij hasło. 


Przy wprowadzeniu błędnego loginu ale poprawnego hasła, formularz logowania wyświetla następujące informacje: Identifier or password invalid oraz Przypomnij hasło. 

* Prawidłowe zalogowanie do aplikacji:


Przy wpisaniu poprawnych danych loginu i hasła, po kliknięciu przycisku Zaloguj, zostajemy przeniesieni do strony głównej aplikacji Scouts Panel. 
Strona główna aplikacji posiada nagłówek z nazwą aplikacji tj. Scouts Panel. Aplikacja wyświetla informacje na temat ilości graczy, ilości meczy, ilości raportów i ilości akcji. Na stronie głównej znajduje się również okno o nazwie Scouts Panel, pod tą nazwą widnieje przycisk DEV TEAM CONTACT (przycisk jest aktywny, przekierowuje nas do *Slack*, w oknie tym znajduje się również grafika. Kolejnym oknem jest okno pod nazwą Linki pomocnicze (nazwa linki pomocnicze jest nieaktywna, nie stanowi przycisku), pod nazwą Linki pomocnicze, w tym samym oknie, wyświetla się napis DODAJ GRACZA, jest to przycisk aktywny, umożliwiający dodanie nowego gracza do aplikacji. Ostatnim oknem jest okno o nazwie Aktywnosć (nazwa z błędem, literówka "ś"); w oknie Aktywnosć znajdziemy informacje o ostatnim stworzonym graczu, ostatnio zaktualizowanym graczu, ostatnim stworzonym, zaktualizowanym meczu czy ostatnio zaktualizowanym raporcie. Linki te są aktywne, przenoszą nas do edycji danego gracza, edycji danego meczu oraz raportu meczowego, gdzie znajdziemy informacje m.in. o inteligencji boiskowej, mentalności, podsumowaniu, recenzji, danych statystycznych.


Po lewej stronie znajduje się kolumna z czterema zakładkami : **Strona główna, Gracze, English oraz Wyloguj**; wszystkie cztery zakładki są aktywne. Do każdej zakładki przypisana jest inna ikona. 


Po kliknięciu zakładki **Gracze**, zostajemy przeniesieni do tabeli, w której znajduje się osiem kolumn o nazwie: imię, nazwisko, wiek, pozycja, klub, recenzja, mecze oraz raporty. Ponadto u góry tabeli po prawej stronie widnieją cztery ikonki, z następującymi funkcjonalnościami: Download CSV, Print, View Columns oraz Filter Table (zarówno w polskiej jak i angielskiej wersji aplikacji napisy wieświetlają się w języku angielskim). 


Niektóre dane graczy w tabeli wypełnione są w sposób nieprawidłowy lub/i są oczywiście sprzeczne.


Przykładowo:
* wiek wynosi -4 lub 1022 lat;
* imię i nazwisko stanowi jedynie ciąg przykładowych liter i znaków specjalnych;
* pozycje niektórych graczy opisane są jako "najstarsi górole ni wiedzo hej";
* niektórzy gracze nie są przypisani do żadnego klubu (pola te są puste);
* do części graczy nie zostały dodane recenzje; widnieje znak "-".


Za pomocą kliknięcia na konkretnego gracza w tabeli np. ***ggagaga Matuefregszewski***, wyświetlane zostają dodatkowe informacje o tym graczu; niektóre z tych danych również wypełnione są w sposób błędny (np. numer telefonu) lub pozostają nieuzupełnione (pola puste); ponadto w kolumnie po lewej stronie wyświetlają się dodatkowe trzy zakładki: zakładka z **Imieniem i Nazwiskiem** danego gracza; zakładka **Mecze**, gdzie znajdziemy informacje o drużynach danego zawodnika, zdobytych i straconych golach, drużynach przeciwnych, datach, jaki był czas gry, recenzjach i autorach, a także akcjach w ramach których możemy edytować mecz danego gracza, dodać raport oraz rozpocząć mecz (odpowiednio trzy ikonki); nad tabelką w tej zakładce (Mecze) widnieje również aktywny przycisk dodaj mecz, który przenosi nas do dodania meczy dla danego gracza; ostatnią zakładką jest zakładka **Raporty**, gdzie widnieją informacje w formie tabeli o danym zawodniku; nad tabelą widnieje aktywy przycik dodaj raport, przenoszący nas do zakładki Mecze.


W zakładce Gracze, aplikacja umożliwia również wyszukanie konkretnego gracza *(Search...)*; funkcjonalność ta znajduje się u góry strony na pasku w kolorze niebieskim. 


Zakładka **English** pozwala na zmianę języka aplikacji na język angielski. 


Po kliknięciu zakładki **Wyloguj**, zostajemy prawidłowo wylogowani z aplikacji. 




***Podsumowanie:***


Aplikacja dostarcza nam informacji o graczach, daje możliwość dodania nowego gracza, zmiany już istniejących danych graczy oraz informuje nas ostatnich aktywnościach w aplikacji. Jest aplikacją dwujęzyczną. Aplikacja Scouts Panel jest prosta w obsłudze, raczej intuicyjna, jednakże zawierająca wiele błędów i niedociągnięć. 




# Task 2


## Subtask 1

https://docs.google.com/document/d/18D_-8GQwhYld5gUiebtUObIoynIa3029IHZEb0m61OU/edit


## Subtask 3


***Dlaczego piszemy przypadki testowe?*** 


Dla testera oprogramowania przypadki testowe stanowią swoiste dowody pomiaru funkcjonalności systemu, modułu czy aplikacji. Piszemy je, aby udokumentować w jaki sposób należy sprawdzić określony cel testowy, który zweryfikuje czy oczekiwane zachowania oprogramowania zotały zrealizowane. Dzięki pokryciu przypadkami testowymi mamy pewność, że nie została pominięta żadna istotna funkcjonalność. Po zakończeniu naszych testów, to właśnie na podstawie przypadków testowych, testerzy oprogramowania, mogą przygotowywać raporty z wykonanych testów. Przypadki testowe stanowią również bardzo pomocne źródło informacji o oprogramowaniu czy aplikacji. Przypadki testowe wykorzystywane są również celem potwierdzenia działania oprogramowania/ aplikacji zgodnie z wymaganiami użytkowników czy interesariuszy (walidacja).



