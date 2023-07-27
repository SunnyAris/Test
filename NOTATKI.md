## Testowanie dzielimy na dynamiczne i statyczne 

Główna różnica pomiędzy testowaniem statycznym a dynamicznych polega na tym, że testowanie
statyczne pozwala wykryć defekty bezpośrednio w produktach pracy, a nie na podstawie
spowodowanych przez te defekty awarii zidentyfikowanych podczas uruchamiania oprogramowania. 


## Testowanie statyczne 

### Testowanie statyczne to testowanie bez uruchamiania aplikacji. Sprawdza podstawową poprawność.

Testowanie statyczne występuje przed testowaniem dynamicznym.

W przeciwieństwie do testowania dynamicznego, które wymaga uruchomienia testowanego
oprogramowania, testowanie statyczne opiera się na ręcznym badaniu produktów pracy
(tj. wykonywaniu przeglądów) bądź dokonywaniu oceny kodu przy użyciu odpowiednich narzędzi lub
innych produktów pracy (tj. analizie statycznej). Oba typy testowania statycznego pozwalają ocenić
testowany kod lub inny produkt pracy bez jego uruchamiania

## Testowanie statyczne pozwala wykryć:

• defekty w wymaganiach (takie jak: niespójności, przeoczenia czy elementy nadmiarowe
w wymaganiach);

• defekty w projekcie (np. nieefektywne algorytmy lub struktury baz danych, wysoki stopień
sprzężenia (ang. coupling) czy mała spójność (ang. cohesion);

• defekty w kodzie (np. zmienne z niezdefiniowanymi wartościami, zmienne zadeklarowane —
lecz nigdy nie używane, niedostępny (martwy) kod, powielony kod);

• odchylenia od standardów (np. brak zgodności ze standardami tworzenia kodu);

• niepoprawne specyfikacje interfejsów (np. użycie różnych jednostek miary w systemie
wywołującym i systemie wywoływanym);

• słabe punkty zabezpieczeń (np. podatność na przepełnienie bufora);

• luki lub nieścisłości w zakresie śledzenia powiązań między podstawą testów a produktami pracy
związanymi z testowaniem lub luki pokrycia (np. brak testów odpowiadających kryteriom
akceptacji)

## Testy dynamiczne 

### Testy dynamiczne to testy wykonywane po testach statycznych wykonywane poprzez uruchomienie aplikacji i badanie jej 


Typ testów to grupa dynamicznych czynności testowych wykonywanych z myślą o przetestowaniu
określonych charakterystyk systemu/oprogramowania (lub jego części) zgodnie z określonymi celami
testów


* Testowanie Funkcjonalne

 Testowanie funkcjonalne systemu polega na wykonaniu testów, które umożliwiają dokonanie oceny
funkcji, jakie system ten powinien realizować. Sprawdzane jest czy aplikacja spełnia normy i wymagania biznesu. Czy wszystko działa zgodnie z założeniami skupia się na najbardziej podstawowych ogólnych testach.

Testy funkcjonalne mogą być testowane technikami czarnoskrzynkowymi tak jak niefunkcjonalne

* Testy niefunkcjonalne 

O wiele bardziej szczegółowe testy niż funkcjonalne.
Celem testowania niefunkcjonalnego jest dokonanie oceny charakterystyk systemów i oprogramowania,
takich jak: 
użyteczność, 
wydajność, 
bezpieczeństwo itd. 
Klasyfikację charakterystyk jakościowych
oprogramowania zawiera standard ISO/IEC 25010. Testowanie niefunkcjonalne pozwala sprawdzić to,
„jak dobrze” zachowuje się dany system. 

#### Do projektowania i wykonywania testów niefunkcjonalnych mogą być potrzebne specjalne umiejętności lub specjalna wiedza taka jak 

- znajomość słabych punktów charakterystycznych dla danego projektu lub danej technologii (np. słabe punkty zabezpieczeń związanych z określonymi językami programowania) 
- bądź konkretnej grupy użytkowników (np. profili użytkowników systemów do zarządzania placówkami opieki zdrowotnej)


Na potrzeby testowania niefunkcjonalnego można używać technik czarnoskrzynkowych. Przykładem może być zastosowanie analizy wartości brzegowych do zdefiniowania warunków skrajnych
dotyczących testów wydajnościowych.

(Technika czarnoskrzynkowa) testowanie funkcjonalne lub niefunkcjonalne bez odniesienia do wewnętrznej struktóry.
Najważniejsze cechy charakterystyczne czarnoskrzynkowych technik testowania:

• warunki testowe, przypadki testowe i dane testowe wyprowadza się z podstawy testów, którą
mogą stanowić wymagania na oprogramowanie, specyfikacje, przypadki użycia i historyjki
użytkownika;

Techniki czarnoskrzynkowe to: 
- Podział na klasy równoważnośc
- Analiza wartości brzegowych
- Testowanie w oparciu o tablicę decyzyjną
- Testowanie przejść pomiędzy stanami
- Testowanie oparte na przypadkach użycia


 ### Testowanie białoskrzynkowe / strukturalne


Najważniejsze cechy charakterystyczne białoskrzynkowych technik testowania:

• warunki testowe, przypadki testowe i dane testowe wyprowadza się z podstawy testów, która
może obejmować: kod, architekturę oprogramowania, szczegółowy projekt bądź dowolne inne źródło informacji o strukturze oprogramowania;



W przypadku testowania białoskrzynkowego warunki testowe wyprowadza się na podstawie struktury
wewnętrznej lub implementacji danego systemu. Struktura wewnętrzna może obejmować kod,
architekturę, przepływy pracy i/lub przepływy danych w obrębie systemu


Do projektowania i wykonywania testów białoskrzynkowych mogą być potrzebne specjalne umiejętności
lub specjalna wiedza, np.: 

- znajomość struktury kodu,
- wiedza o sposobie przechowywania danych
- bądź sposób korzystania z narzędzi do pomiaru
pokrycia i poprawnego interpretowania generowanych przez nie rezultatów.


## Testowanie na podstawie doświadczenia 
Najważniejsze cechy charakterystyczne technik testowania opartych na doświadczeniu:

• warunki testowe, przypadki testowe i dane testowe wyprowadza się z podstawy testów, która
może obejmować wiedzę i doświadczenie testerów, deweloperów, użytkowników oraz innych
interesariuszy;



* Testowanie pielęgnacyjne

Po dokonaniu każdej zmiany w fazie pielęgnacji, należy wykonać testowanie pielęgnacyjne, którego
celem jest zarówno sprawdzenie, czy zmiana została wprowadzona pomyślnie, jak i wykrycie
ewentualnych, niezamierzonych skutków ubocznych (np. regresji) w niezmienionych częściach systemu
(czyli zwykle w większości jego obszarów). Pielęgnacja może być wykonywana zarówno planowo
(w związku z nowymi wersjami), jak i w sposób niezaplanowany (w związku z poprawkami doraźnymi) 

* smoke testing - testowanie podstawowych funkcji =>

* retesting - testowanie po znalezionych bugach => 

* sanity testing - sprawdzamy czy jakaś część moduły aplikacji zostały dotknięte zmianą i czy jest ok => 

* regresion - sprawdza całą aplikację czy wszystko działa po zmianach i czy naprawa miała wpływ na całość 

![Alt text](<smoke sanity regresion.png>)


 AUT-Application Under Test

- test strategy - strategia testów określona na poziomie organizacji ogólne wytyczne i zasady testowania w danej firmie jak wygląda testowanie jakich narzędzi się używa 
jak wykrywa się defekty jak należy z nimi postępować  każdy projekt się na tym opiera i ogólna strategia pozostaje niezmienna zmiany w ogólnym działaniu występują bardzo rzadko 
jest to ogólna wizja tego jak powinno się testować 

- test plan - tworzony na pozniomie projektowym opiera się na test strategy. Test plan jest tworzony pod dany projekt taski test planu mogą się znieniać zależnie od postępów projektu i napotkanych problemów 
test plan zawiera szczególy na temat kto przeprowadza testy jakie są szczegóły działania aplikacji jak powinna działać jakie są cele jaki jest timeline
jest to wizja działania jakie będą podjęte w ramach testowania 



Podstawa testów (test bases)- dokumentacja w której znajdziemy informację dotyczącą jak powinien się zachowywać system z tego wyciągamy informacje co mamy testować zdarzenia lub procesy lub poszczególne elementy (formularze przyciski zachowania)


Warunki testowe (test condition) formularze zachowania to zdarzenia które wyciągamy z podstawy testowej coś co musimy przetestować 


Przypadki testowe (test case) szereg różnych testów które przeprowadzamy testując jakieś warunki testowe   
Przypadek testowy opisuje kroki do wykonania i oczekiwane rezultaty po wykonaniu tych kroków


objekt testów - aplikacja mobilna lub strona internetowa lub jakiekolwiek inne rozwiązanie 
coś co ma realizować założenia opisane w podstawie testów w tej dokumentacji 









