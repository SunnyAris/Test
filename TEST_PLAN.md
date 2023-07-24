# TEST PLAN
Jest to dokument przygotowywany na poziomie projektu przez kierownika testów. Plan testów mozna modyfikować w razie potrzeby.

Plan testów szczegółowo opisuje zakres testów i różne czynności wykonywane w testach tj. zastosowane techniki, harmonogaram, zasoby itd.
 
## Dokument planu testów zawiera takie komponenty jak: 
- cechy do przetestowania 
- komponenty, które mogą być testowane
- podejście do testowania
- kryteria zaliczenia i niezaliczenia 
- wyniki testów 
- szacunki 
- założenia 
  

## Plan testów powinien zawierać: 

### 1. Wstęp


Pierwszą sekcją powinien być krótki wstęp, który może zawierać takie informacje jak:

• Cel dokumentu

• Cel działań testowych

W punkcie „Cel dokumentu”, powinniśmy określić, w jakim celu i po co powstał ten dokument oraz czego dotyczyć będzie dalsza część dokumentu.Celem może być określenie ogólnego podejścia do procesu testowego danego oprogramowania, czy wskazanie zakresu testów, podejście za zarządzania ryzykiem, opracowanie harmonogramów itp.
Celem działań testowych może być np. dostarczenie informacji dla interesariuszy, którzy na ich podstawie będą mogli świadomie podjąć decyzję o odbiorze produktu, czy wypuszczeniu / niewypuszczeniu oprogramowania na rynek.



### 2. Zakres Testów

Ten punkt powinien być konkretny i szczegółowy. Informacje, które się tutaj znajdą będą mieć duży wpływ na budżet i czas realizacji całego projektu / procesu. To tutaj powinniśmy spisać wszystkie typy testów, jakimi zamierzamy poddać obiekt testów. Np. Testy jednostkowe, testy integracyjne, testy funkcjonalne, testy wydajnościowe, testy bezpieczeństwa, testy regresji, testy automatyczne itp.



W tej sekcji warto wyszczególnić również rodzaje testów, które zostaną pominięte i nie zostaną wykonane. Należy sumiennie uargumentować, dlaczego dany rodzaj testów został pominięty lub wykluczony z działań testowych. Np. może być taka sytuacja, że nie będziemy realizować testów bezpieczeństwa, gdyż nie mamy do tego wystarczających kompetencji w zespole (brak pentesterów), lub np. klient zrealizuje te testy po własnej stronie z wykorzystaniem swoich zasobów kompetencyjnych / sprzętowych.



### 3. Przedmiot testów


W tym miejscu powinniśmy jasno sprecyzować, jaki jest przedmiot testów. Może to być po prostu gotowy, zamówiony przez klienta produkt, ale równie dobrze może to być tylko jeden, bądź kilka komponentów, usług czy modułów.



### 4. Kryteria zaliczenia / niezaliczenia testów


Po zdefiniowaniu, które testy należy przeprowadzić, musisz wiedzieć, kiedy pojedynczy test będzie „zakończony”. Oznacza to, że musisz zdefiniować kryteria zaliczenia (test pozytywny) i niepowodzenia (test negatywny) dla każdego konkretnego testu.



Aby moc określić status testu (pozytywny, negatywny), będziemy musieli na początku zdefiniować poszczególne metryki, które należy śledzić. 

Na przykład, jeśli robisz test wydajności, możesz spojrzeć na takie metryki, jak:

- Czas odpowiedzi: łączny czas na wysłanie żądania i uzyskanie odpowiedzi
- Czas oczekiwania: ile czasu zajmuje otrzymanie pierwszego bajtu po wysłaniu żądania
- Średni czas ładowania: średni czas potrzebny na dostarczenie każdego żądania
- Maksymalny czas odpowiedzi: najdłuższy czas potrzebny na zrealizowanie żądania
- Żądania na sekundę: ile żądań można obsłużyć w danej jednostce czasu
- Transakcje udane / nieudane: łączna liczba udanych lub nieudanych żądań
- Wykorzystanie pamięci: Ile pamięci jest potrzebne do przetworzenia żądania


### 5. Kryteria wejścia / wyjścia


#### Kryteria wejścia
Tutaj umieszczamy wszystkie elementy, warunki, które muszą zostać spełnione, aby rozpocząć testowanie, czyli np. działające środowisko testowe, dostępny zespół ludzi o odpowiednich kompetencjach technicznych i biznesowych, czy zakończone określone fazy developmentu.


#### Kryteria wyjścia
Określają, kiedy można przerwać testowanie danej funkcji - stan, w którym stwierdzamy, że dana funkcja działa zgodnie z przyjętymi założeniami.

#### Rzadziej spisywane są kryteria zawieszenia

• Kryteria zawieszenia

Określają, kiedy należy wstrzymać test. Odpowiadają na pytania: Czy istnieje próg błędów, przy którym należy przerwać testowanie i zacząć szukać rozwiązań? Jakie są kroki, aby go zamknąć i udokumentować to, co zostało zrobione do tej pory?



### 6. Lista wymagań / funkcjonalności do przetestowania


Często w Planie Testów występuje sekcja, w której umieszczamy spisy konkretnych funkcjonalności, które należy odpowiednio przetestować. W tym miejscu częstą praktyką jest załączanie wcześniej przygotowanych historyjek użytkownika (user story) czy różnego rodzaju scenariuszy testowych pod konkretne funkcjonalności.


### 7. Środowisko testowe

Wyniki testów będą zależeć w takim samym stopniu od testowanej funkcji, jak i środowiska, na którym ją testujesz. W ramach Planu Testów musisz określić, jaki sprzęt, oprogramowanie, system operacyjny będzie niezbędny i wykorzystywany podczas procesu testowego.
Umieszczamy tu szczegółowe konkrety konfiguracyjne, gdyż pozwoli to uniknąć nieścisłości i niedopowiedzeń, a w konsekwencji błędnej konfiguracji. Na przykład, jeśli zamierzasz określić system operacyjny, który ma być używany podczas testów, podaj również wersję/edycję systemu operacyjnego, a nie tylko nazwę. Tak samo postępujemy z całą resztą software’u oraz hardware’u.



### 8. Harmonogram testów


W tej sekcji określamy (w stopniu możliwie najbardziej precyzyjnym i konkretnym ) ogólny harmonogram testów, które zamierzamy przeprowadzić. Warto podzielić harmonogram na fazy oraz typy testów wraz z ich określonymi przedziałami czasowymi (datami). Przy określaniu terminów, dawać sobie lekki zapas czasu na mniej lub bardziej nieprzewidziane sytuacje, problemy i trudności.



### 9. Raporty z testów


To miejsce jest bardzo istotne z punktu widzenia klienta, gdyż to tutaj określamy, jakie artefakty z testów dostarczymy na koniec procesu testowego. To na podstawie właśnie tych informacji, dokumentów klient będzie podejmował decyzję np. o wypuszczeniu / niewypuszczeniu obiektu testów na rynek. Zwykle tutaj dajemy informację, że na koniec testów dostarczymy np. listę przypadków testowych, które zostały przeprowadzone wraz z ich statusami, skrypty testów automatycznych, wszelkie raporty z testów.



### 10. Lista narzędzi


Umieszczamy tutaj listę wszelkich narzędzi, które będą brać udział w procesie testowym.
Często taka lista może być dość obszerna, dlatego w takim wypadku należy podzielić te narzędzia na grupy zastosowania, np. narzędzia do testów automatycznych, narzędzia do zarządzania defektami, narzędzia do raportowania itp.



### 11. Zarządzanie incydentami, błędami

Tutaj należy określić proces, który dotyczy zarządzania wykrytymi incydentami od ich znalezienia, po naprawę, a kończąc na retestach. Oczywiście taki proces w każdej firmie może być nieco inny. Wygląd takiego procesu może również zależeć od wykorzystywanych narzędzi, a także od wielkości i organizacji zespołu testowego. W ramach takiego procesu jednak zawsze należy zwrócić uwagę na takie elementy jak: proces zgłaszania błędów, proces retestowania błędów, proces omawiania i rozwiązywania błędów itp.



### 12. Role i odpowiedzialność

Zwykle w końcowym fragmencie Planu Testów powinna znaleźć się sekcja, w której to precyzyjnie powinniśmy określić role i odpowiedzialności w proponowanym procesie testowym. Ten punkt jest oczywiście tym bardziej istotny, im większy zespół testowym bierze udział w testach. Określamy tutaj wszystkie role, jakie biorą udział w testach, a więc np. tester manualny, tester automatyzujący, test manager, analityk testowy itp. Każda rola powinna zawierać swój precyzyjny zakres odpowiedzialność.



### 13. Ryzyka


Na koniec dokumentu możemy spisać ryzyka, o których mamy jakąkolwiek wiedzę, a które wydają się na tyle istotne, że mogą mieć wpływ na proces testowy oraz testowaną aplikację.

















