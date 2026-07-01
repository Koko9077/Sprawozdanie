=====
Wstęp
=====

:Autor: Michał Bednarczyk

Wstęp do sprawozdania
---------------------

Głównym tematem zajęć laboratoryjnych było praktyczne przejście przez pełen cykl życia projektu relacyjnej bazy danych dla sklepu elektronicznego. Ćwiczenia rozpoczęły się od stworzenia kompletnej dokumentacji projektowej, obejmującej analizę procesów, prototypowanie w formacie JSON oraz tworzenie modeli koncepcyjnych i logicznych (z użyciem diagramów Chena i notacji IE). Zwieńczeniem tej pracy było przełożenie przygotowanych schematów na rzeczywisty model fizyczny w środowiskach PostgreSQL i SQLite, zasilenie ich danymi oraz opracowanie zapytań.

Wnioski z przeprowadzonych ćwiczeń
----------------------------------

Zrealizowanie całego procesu na laboratoriach udowodniło, że rzetelnie stworzona dokumentacja i poprawna normalizacja są absolutnym fundamentem do bezbłędnego wdrożenia modelu fizycznego. Podczas implementacji i testowania obu środowisk wyraźnie zarysowała się przewaga PostgreSQL nad SQLite w kontekście budowania profesjonalnych systemów. Rygorystyczne typowanie danych, bogatsza składnia oraz natywne, ścisłe egzekwowanie więzów integralności w PostgreSQL sprawiają, że jest to rozwiązanie znacznie bezpieczniejsze i bardziej przewidywalne niż uproszczony, plikowy SQLite. Etap końcowy, polegający na tworzeniu skomplikowanych zapytań (z wielokrotnymi złączeniami i podzapytaniami), ostatecznie potwierdził, że choć SQLite jest wygodny w prostych zastosowaniach, to właśnie PostgreSQL oferuje stabilność, precyzję i wydajność niezbędną do profesjonalnego przetwarzania złożonych informacji.

Główne repozytorium sprawozdania 
--------------------------------
Link do mojego repozytorium ze sprawozdaniem:

* **Link:** https://github.com/Koko9077/Sprawozdanie

Repozytorium z modelami fizycznymi naszej bazy 
----------------------------------------------

* **Link:** https://github.com/Koko9077/Model-fizyczny-baz

Repozytoria reszty grupy 
------------------------
Poniżej znajdują się odnośniki do repozytoriów reszty grupy:

* **Grupa 1 (rozdzial_1):** https://github.com/karaskamil/Sprzet-dla-bazy-danych.git
* **Grupa 2 (rozdzial_2):** https://github.com/Youarecheck/Bazy_Danych_Tematyczne_Repo_MK.git
* **Grupa 3 (rozdzial_3):** https://github.com/pawlos1337/Bazy-danych-temat.git
* **Grupa 4 (rozdzial_4):** https://github.com/OskarProgrammer/monitorowanie_i_diagnostyka.git
* **Grupa 5 (rozdzial_5):** https://github.com/KMachoK/Tematyczne.git
* **Grupa 6 (rozdzial_6):** https://github.com/domino0472/Partycjonowani-Danych
* **Grupa 7 (rozdzial_7):** https://github.com/oski486/BazyDanych-Subject.git
* **Grupa 8 (rozdzial_8):** https://github.com/Koko9077/Kopie-zapasowe-i-odzyskiwanie-danych.git
