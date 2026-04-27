# projekt_analityka_bizesowa
Analiza danych sprzedaży detalicznej w Power BI z wykorzystaniem DAX. Interaktywny raport obejmujący m.in. rentowność, segmentację klientów, analizę koszykową, logistykę oraz trendy sprzedaży. Projekt zespołowy z elementami CRISP-DM i SCRUM.

# Opis projektu
Projekt został wykonany w ramach zajęć z analityki biznesowej i polegał na stworzeniu kompleksowego raportu analitycznego w środowisku Microsoft Power BI z wykorzystaniem języka DAX.

Celem projektu była wielowymiarowa analiza danych sprzedaży detalicznej wybranej firmy, obejmująca zarówno efektywność sprzedaży, zachowania klientów, jak i aspekty logistyczne.

Projekt został zrealizowany zespołowo (5 osób).

# Cele projektu
* analiza rentowności sprzedaży
* identyfikacja wzorców zakupowych klientów (analiza koszykowa)
* segmentacja klientów i analiza lojalności
* ocena efektywności dostaw i logistyki
* analiza sprzedaży w czasie oraz geograficznie
* wsparcie decyzji biznesowych na podstawie danych

# Wykorzystane narzędzia i technologie
* Microsoft Power BI
* DAX (Data Analysis Expressions)
* Microsoft Excel (przygotowanie danych)

# Wykorzystanie języka DAX
W projekcie zastosowano zaawansowane elementy języka DAX:
* miary i kolumny obliczeniowe
* tabele obliczeniowe
* iteratory (np. SUMX, AVERAGEX)
* funkcje filtrujące (FILTER)
* funkcje logiczne (AND)
* funkcję CALCULATE i CALCULATETABLE
* zmienne (VAR) do optymalizacji obliczeń
* funkcje statystyczne

# Model danych
Model danych składa się z wielu powiązanych tabel, zawierających m.in.:
* dane sprzedażowe
* dane klientów
* produkty
* lokalizacje
* dane logistyczne

Zostały utworzone relacje oraz hierarchie umożliwiające analizę danych z różnych perspektyw.

# Zakres raportu (7 stron)
Raport składa się z 7 interaktywnych stron:
1. Rentowność – analiza marży i zyskowności
2. Analiza koszykowa I – współwystępowanie produktów
3. Analiza koszykowa II – pogłębiona analiza zachowań zakupowych
4. Logistyka i dostawa – czas realizacji, efektywność dostaw
5. Segmentacja i klienci – podział klientów oraz ich wartość
6. Sprzedaż w czasie i lojalność – trendy oraz powracalność klientów
7. Analiza geograficzna – sprzedaż w ujęciu lokalizacyjnym

# Wykorzystane elementy wizualne
* wykresy (liniowe, słupkowe, kołowe)
* tabele i macierze
* fragmentatory (slicery)
* mapy
* wskaźniki KPI

# Kluczowe wnioski
1. Produkty Technology są kluczowe dla rentowności
Generują najwyższy zysk jednostkowy i całkowity, mimo niższego wolumenu sprzedaży → to na nich firma powinna się strategicznie skupiać.
2. Rabaty powyżej 20% są nieopłacalne
Znacząco obniżają marżę i często prowadzą do strat → konieczna jest kontrola i optymalizacja polityki rabatowej.
3. Istnieje duży potencjał cross-sellingu
Klienci często kupują razem powiązane produkty (np. Office Supplies + Technology) → warto wdrożyć rekomendacje i zestawy produktowe.
4. Poważny problem w logistyce – 75% opóźnionych dostaw
Średnie opóźnienie ~1,8 dnia → wymaga optymalizacji procesów operacyjnych.
5. Segment Consumer generuje największą wartość biznesową
Najwyższa sprzedaż i zysk → strategia powinna być dostosowana do różnych segmentów klientów.

# Dokumentacja projektowa (SCRUM + CRISP-DM)
Projekt został zrealizowany zgodnie z elementami metodyk:
CRISP-DM:
* zrozumienie problemu biznesowego
* przygotowanie i czyszczenie danych
* modelowanie danych
* ewaluacja wyników

SCRUM:
* przygotowanie product backlogu
* podział user stories na zadania
* realizacja projektu w sprintach
* testowanie i iteracyjne ulepszanie rozwiązania

