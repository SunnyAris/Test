### Przypadek testowy dostarcza szczegółowych informacji: 
- co należy przetestować, 
- jakie kroki należy podjąć, 
- oczekiwany rezultat.

Chodzi o dokumentowanie szczegółow. 
Pisanie przypadków testowych ze szczegółami pomoże w odtworzeniu przebiegu testów przez innych, synchronizacji deweloperów i zespołu ds.kontroli jakości.

Dokumentacja wszystkich przypadków testowych jest przydatna do śledzenia wielu rund testów regresji w przyszłości. Jest to bardzo pomocne przy zgłaszaniu błędów.

### KLUCZOWE elementy przypadku testowego:

- Cel
  
- ID unikalny identyfikator

- Warunki wstępne uruchomienia

- Kroki do wykonania testu

- Oczekiwany rezultat

- Warunek końcowy

### Dodatkowo:

- Tytuł

- Dane testowe

- Środowisko uruchomienia

- Powiązania z wymaganiem (pokrycie testowe)

- Kategoria / typ

- Tagi - słowa kluczowe powiązane z przypadkiem

- Autor (wraz z danymi kontaktowymi)

- Informacje o wersji.


Przykład : 

```
ID 1.1
Tytuł: Poprawne zalogowanie się do aplikacji
Środowisko: przeglądarka FF12, system operacyjny W10, SP 1
Warunek wstępny: włączona przeglądarka na stronie http://.............../user/login/; użytkownik nie może być zalogowany
Kroki do wykonania:

1. wpisz istniejący login: xxx
2. wpisz istniejące i przypisane do loginu hasło: 123
3. Naciśnij klawisz "Zaloguj"

Oczekiwany rezultat: Zalogowanie się jako użytkownik xxx z przekierowaniem na stronę główną.

Warunki końcowe: Użytkownik jest zalogowany
```

Przypadek powyższy jest przypadkiem pozytywnym, ponieważ weryfikuje podstawową funkcjonalność. 

Przypadek testowy negatywny może być weryfikacją komunikatów przy logowaniu się przy niepoprawnych danych testowych.

Przypadek testowy może być znacznie bardziej ogólny.


### Każdy przypadek ma swój cel, dla którego go uruchamiamy jak:

- Znalezienie błędów
- Maksymalizacja liczby błędów
- Wstrzymywanie niedojrzałych wersji systemu
- Wsparcie szefów projektu w podjęciu decyzji o wstrzymaniu/wprowadzeniu systemu
- Minimalizacja kosztów wsparcia technicznego
- Ocena zgodności ze specyfikacją
- Dostosowanie do przepisów
- Minimalizacja ryzyka prawnego
- Znalezienie bezpiecznych scenariuszy użytkowania systemu
- Ocena jakości
- Weryfikacja poprawności systemu
- Zapewnienie jakości

### Każdy z przypadków testowych jest powiązany z danym rodzajem testów Poszczególne typy testów można dowolnie łączyć:

- Testowanie funkcji
- Testowanie domen
- Testowanie oparte o specyfikację
- Testowanie oparte o ryzyko
- Testowanie wydajnościowe
- Testowanie regresyjne
- Testowanie przez użytkowników
- Testowanie scenariuszowe
- Testowanie stanów
- Przeciążeniowe testowanie automatyczne
- Testowanie eksploracyjne





