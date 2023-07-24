### Scenariusz testowy to dokument określając ciąg akcji umożliwiających wykonanie testu. 

Inaczej mówiąc, scenariusz składa się z przypadków testowych w celu przetestowania konkretnej funkcjonalności systemu.

Scenariusze testowe opracowywane są na podstawie Specyfikacji Wymagań Biznesowych lub Specyfikacji Wymagań Systemowych. Określają jaka funkcjonalność i co ma być przedmiotem testów.

### Przykładowe funkcjonalności: 

- Rejestrowanie się użytkowników

- Logowanie się zarejestrowanych użytkowników

- Dodawanie komentarzy pod artykułami przez zalogowanych użytkowników

- Zablokowanie możliwości dodawania komentarzy pod artykułami przez niezalogowanych użytkowników

Każda z tych funkcjonalności będzie testowana w ramach osobnego scenariusza testowego. 

Sprawdzenie działania funkcjonalności rejestrowania się nowego użytkownika /zakładania konta użytkownika.

Wymieniamy czynności przygotowawcze, czyli co powinno być zrobione, żeby można było wykonać scenariusz. W tym wypadku będzie to dostępność odpowiedniej przeglądarki oraz posiadanie aktywnego konta e-mail przez użytkownika.

Teraz możemy dobrać lub stworzyć przypadki testowe (test cases).

### SCENARIUSZ NR 1. Rejestracja użytkownika 


#### Na podstawie dokumentacji nr AA-BB-CC

Autor: XXX

Data utworzenia:01.01.01


```
Test Case 1a: Użytkownik poprawnie rejestruje się do aplikacji

Warunek wstępny: Posiadanie aktywnego adresu e-mail.

Kroki testowe
1. Rejestrowanie się nowego użytkowania przez podanie poprawnego adresu e-mail

2. Spełniającego wymogi hasła (o odpowiedniej długości i zawierającego dopuszczalne znaki)

3. Przejście testu CAPTCHA, potwierdzenie akceptacji regulaminu

Oczekiwany rezultat: Użytkownik zostaje pomyślnie zajerestrowany
```
```
Test Case 1b: Użytkownik próbuje zarejestrować się do aplikacji używając niepoprawnego adresu e-mail.

Warunek wstępny: Posiadanie niepoprawnego adresu e-mail

Kroki testowe
1.Rejestrowanie się nowego użytkowania przez podanie niepoprawnego adresu e-mail spełniającego wymogi hasła (o odpowiedniej długości i zawierającego dopuszczalne znaki)

2. Przejście testu CAPTCHA 

3. Potwierdzenie akceptacji regulaminu

Oczekiwany rezultat: Pojawienie się komunikatu "Błędny adres e-mail"
```
```
Test Case 1c: Użytkownik próbuje zarejestrować się używając adresu e-mail przy pomocy którego został zarejestrowany inny użytkownik

Warunek wstępny: Posiadanie adresu e-mail z zarejestrowanym użytkownikiem  


Kroki testowe
1. Próba rejestracji użytkownika z takim samym adresem e-mail i hasłem, co zarejestrowany już użytkownik 

Oczekiwany rezultat: Pojawienie się komunikatu " Ten adres e-mail jest już zajęty. Wybierz inny adres"
```

### SCENARIUSZ NR 2. Logowanie się do aplikacji 

#### Na podstawie dokumentacji nr AA-BB-CC

Autor: XXX

Data utworzenia:01.01.01
```
Test Case 2a. Poprawne zalogowanie się użutkownika

Warunek wstępny: Użytkownik posiada aktywne konto w aplikacji

Kroki testowe
1. Otwarcie aplikacji webowej

2. Wprowadzenie prawidłowej nazwy użytkownika w polu "Login"

3. Wprowadzenie prawidłowego hasła w polu "Hasło"

4. Kliknięcie przycisku "Logowanie"

Oczekiwany rezultat: Użutkownik zostaje pomyślnie zalogowany
```
```
Test Case 2b. Nieudane logowanie użutkownika do aplikacji przy użyciu niepoprawnego hasła.

Warunek wstępny: Użytkownik posiada aktywne konto w aplikacji

Kroki testowe: 
1. Otwarcie aplikacji webowej

2. Wprowadzenie prawidłowej nazwy użytkownika w polu "Login"

3. Wprowadzenie nieprawidłowego hasła w polu "Hasło"

4. Kliknięcie przycisku "Logowanie"

Oczekiwany rezultat: Pojawienie się komunikatu "Błędne hasło"
```
### Scenariusz testowy powinien składać się z:

#### Identyfikacja scenariusza testowego – w tej sekcji dokumentowane są takie dane jak: :
- id scenariusza
- nazwa scenariusza
- opis scenariusza (cele)
- typ scenariusza (np. testy funkcjonalne, bezpieczeństwa)


#### Czynności przygotowawcze scenariusza testowego – spis wszystkich czynności, które należy wykonać przed przystąpieniem do wykonywania scenariusza testowego. 

- weryfikacja poprawności instalacji i konfiguracji testowanego oprogramowania
- weryfikacja narzędzi potrzebnych do wykonania i udokumentowania testów
- weryfikacja użytkowników i ich uprawnień niezbędnych do przeprowadzenia testów
  
#### Spis przypadków testowych – należy zidentyfikować i uporządkować wszystkie przypadki testowe przewidziane do realizacji danego scenariusza testowego.

- czynności końcowe scenariusza testowego – wykaz czynności, jakie należy wykonać po zakończeniu testów w ramach danego scenariusza. 
  
  Są to czynności, bez których niemożliwe byłoby wykonanie kolejnych scenariuszy. Mogą być to również czynności wynikające z polityk bezpieczeństwa.








