## Poziomy testów:
• testowanie modułowe;

• testowanie integracyjne;

• testowanie systemowe;

• testowanie akceptacyjne.



### Każdy poziom testów charakteryzują następujące atrybuty:

• cele szczegółowe;

• podstawa testów (do której należy odwoływać się przy wyprowadzaniu przypadków testowych);

• przedmiot testów (czyli to, co jest testowane);

• typowe defekty i awarie;

• konkretne podejścia i odpowiedzialności.

Każdy poziom testów wymaga odpowiedniego środowiska testowego, np. do testowania 
akceptacyjnego idealnie nadaje się środowisko testowe podobne do środowiska produkcyjnego, 
a podczas testowania modułowego programiści zwykle korzystają z własnego środowiska 
rozwojowego.

## Testowanie modułowe (po części znać wykonuje programista) (zwane także testowaniem jednostkowym, testowaniem komponentów lub testowaniem programu) 

Skupia się na modułach, które można przetestować oddzielnie. Cele tego typu 
testowania to między innymi: 

• zmniejszanie ryzyka;

• weryfikacja zgodności zachowań funkcjonalnych i niefunkcjonalnych modułu z projektem 
i specyfikacjami

• budowanie zaufania do jakości modułu;

• wykrywanie defektów w module;

• zapobieganie przedostawaniu się defektów na wyższe poziomy testowania.

Testy modułowe są często wykonywane w izolacji od reszty systemu (zależnie od modelu cyklu życia 
oprogramowania i konkretnego systemu), przy czym w takiej sytuacji może być konieczne użycie atrap 
obiektów (ang. mock object), wirtualizacji usług, jarzm testowych, zaślepek bądź sterowników. 

Testowanie modułowe może obejmować funkcjonalność (np. poprawność obliczeń), parametry 
niefunkcjonalne (np. wycieki pamięci) oraz właściwości strukturalne (np. testowanie decyzji).

### Podstawa testów
Przykładowe produkty pracy, które mogą być wykorzystywane jako podstawa testów w ramach 
testowania modułowego, to między innymi:

• projekt szczegółowy;

• kod;

• model danych;

• specyfikacje modułów.

### Przedmioty testów

Do typowych przedmiotów testów dla testów modułowych zalicza się:

• moduły, jednostki lub komponenty;

• kod i struktury danych;

• klasy;

• moduły baz danych.

### Typowe defekty i awarie
Przykładami typowych defektów i awarii wykrywanych w ramach testowania modułowego są:

• niepoprawna funkcjonalność (np. niezgodna ze specyfikacją projektu);

• problemy z przepływem danych;

• niepoprawny kod i logika



## Testowanie integracyjne 

Skupia się na interakcjach między modułami lub systemami. Cele testowania 
integracyjnego to: 

• zmniejszanie ryzyka;

• weryfikacja zgodności zachowań funkcjonalnych i niefunkcjonalnych z projektem 
i specyfikacjami;

• budowanie zaufania do jakości interfejsów;

• wykrywanie defektów (które mogą występować w samych interfejsach lub 
w modułach/systemach);

• zapobieganie przedostawaniu się defektów na wyższe poziomy testowania.

### Podstawa testów

Przykładowe produkty pracy, które mogą być wykorzystywane jako podstawa testów w ramach 
testowania integracyjnego, to między innymi:

• projekt oprogramowania i systemu;

• diagramy sekwencji;

• specyfikacje interfejsów i protokołów komunikacyjnych;

• przypadki użycia;

• architektura na poziomie modułów i systemu;

• przepływy pracy;

• definicje interfejsów zewnętrznych.
Przedmioty testów

### Do typowych przedmiotów testów zalicza się:
• podsystemy;

• bazy danych;

• infrastrukturę;

• interfejsy;

• interfejsy programowania aplikacji (ang. Application Programming Interface — API);

• mikrousługi.


### Typowe defekty i awarie
Przykładami typowych defektów i awarii wykrywanych w ramach testowania integracji modułów są:

• niepoprawne lub brakujące dane bądź niepoprawne kodowanie danych;

• niepoprawne uszeregowanie lub niepoprawna synchronizacja wywołań interfejsów;

• niezgodności interfejsów;

• błędy komunikacji między modułami;

• brak obsługi lub nieprawidłowa obsługa błędów komunikacji między modułami;

• niepoprawne założenia dotyczące znaczenia, jednostek lub granic danych przesyłanych między 
modułami.




## Testowanie systemowe (czarnoskrzynkowe) 

Skupia się na zachowaniu i możliwościach całego systemu lub produktu, często 
z uwzględnieniem całokształtu zadań, jakie może on wykonywać oraz zachowań niefunkcjonalnych, 
jakie można stwierdzić podczas wykonywania tych zadań. 

### Cele testowania systemowego to między 
innymi: 

• zmniejszanie ryzyka;

• werfikacja zgodności zachowań funkcjonalnych i niefunkcjonalnych systemu z projektem 
i specyfikacjami;

• walidacja, czy system jest kompletny i działa zgodnie z oczekiwaniami;

• budowanie zaufania do jakości systemu jako całości;

• wykrywanie defektów;

• zapobieganie przedostawaniu się defektów na wyższe poziomy testowania lub na produkcję



### Przykładowe produkty pracy, które mogą być wykorzystywane jako podstawa testów w ramach testowania systemowego, to między innymi:

• specyfikacje wymagań (funkcjonalnych i niefunkcjonalnych) dotyczących systemu 
i oprogramowania;

• raporty z analizy ryzyka;

• przypadki użycia;

• opowieści i historyjki użytkownika;

• modele zachowania systemu;

• diagramy stanów;

• instrukcje obsługi systemu i podręczniki użytkownika

### Przedmioty testów

Do typowych przedmiotów testów dla testów systemowych zalicza się:

• aplikacje;

• systemy łączące sprzęt i oprogramowanie;

• systemy operacyjne;

• system podlegający testowaniu;

• konfiguracja i dane konfiguracyjne systemu.

### Typowe defekty i awarie

Przykładami typowych defektów i awarii wykrywanych w ramach testowania systemowego są:

• niepoprawne obliczenia;

• niepoprawne lub nieoczekiwane zachowania funkcjonalne lub niefunkcjonalne systemu;

• niepoprawne przepływy sterowania i/lub przepływy danych w systemie;

• problemy z prawidłowym i kompletnym wykonywaniem całościowych zadań funkcjonalnych;

• problemy z prawidłowym działaniem systemu w środowisku (środowiskach) testów 
systemowych;

• niezgodność działania systemu z opisami zawartymi w instrukcji obsługi systemu 
i podręcznikach użytkownika


## Testowanie akceptacyjne — podobnie jak testowanie systemowe — skupia się zwykle na zachowaniu i możliwościach całego systemu lub produktu. 

Cele testowania akceptacyjnego to najczęściej: 

• budowanie zaufania do systemu;

• walidacja, czy system jest kompletny i czy będzie działał zgodnie z oczekiwaniami;

• weryfikacja zgodności zachowania funkcjonalnego i niefunkcjonalnego systemu ze 
specyfikacją

### Najczęściej występujące formy testowania akceptacyjnego to:

#### Testowanie akceptacyjne przez użytkownika;. User Acceptance Testing – UAT

Testowanie akceptacyjne systemu przez użytkownika odbywa się w (symulowanym) środowisku 
produkcyjnym i skupia się zwykle na walidacji, czy system nadaje się do użytkowania przez przyszłych 
odbiorców. Głównym celem jest tu zbudowanie pewności, że system umożliwi użytkownikom spełnienie ich potrzeb, postawionych przed nim wymagań i wykona proces biznesowy z minimalną liczbą problemów, minimalnymi kosztem i ryzykiem.


#### Produkcyjne testy akceptacyjne;  Operational Acceptance Testing – OAT 

Testowanie akceptacyjne systemu przez operatorów lub administratorów odbywa się zwykle 
w (symulowanym) środowisku produkcyjnym. Testy skupiają się na aspektach operacyjnych i mogą 
obejmować:

- testowanie mechanizmów tworzenia kopii zapasowych i odtwarzania danych;
  
- instalowanie, odinstalowywanie i aktualizowanie oprogramowania;
  
- usuwanie skutków awarii
  
Głównym celem produkcyjnych testów akceptacyjnych jest uzyskanie pewności, że operatorzy lub 
administratorzy systemu będą w stanie zapewnić użytkownikom prawidłową pracę systemu 
w środowisku produkcyjnym, nawet w wyjątkowych i trudnych warunkach


#### Testowanie akceptacyjne zgodności z umową i zgodności z przepisami prawa;

Testowanie akceptacyjne zgodności z przepisami prawa jest wykonywane w kontekście 
obowiązujących aktów prawnych, takich jak: ustawy, rozporządzenia czy normy bezpieczeństwa. 
Podobnie jak w przypadku testowania akceptacyjnego zgodności z umową, tego rodzaju testowanie 
akceptacyjne często wykonują użytkownicy lub niezależni testerzy, a rezultaty mogą być obserwowane lub kontrolowane przez organy nadzoru

#### Testowanie alfa i beta

Testowanie alfa jest wykonywane w siedzibie organizacji wytwarzającej oprogramowanie, ale zamiast zespołu wytwórczego testy wykonują potencjalni lub obecni klienci, i/lub operatorzy bądź niezależni testerzy. Z kolei testowanie beta wykonują obecni lub potencjalni klienci we własnych lokalizacjach. 
Testy beta mogą być, ale nie muszą, poprzedzone testami alfa.



