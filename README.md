## Projekt z Podstaw sztucznej inteligencji
* [Informacja podstawowa](#wstęp)
* [Biblioteki](#biblioteki)

## Wstęp
Projekt przedstawia model, który rozpoznaje 5 rodzajów zwierząt na zdjęciach.

Rodzaje zwierząt:
* kot
* pies
* słoń
* koń
* lew

Zbiór danych zawiera 38 tys. zdjęć treningowych i 3 tys. zdjęć walidacyjnych.
Zbiór jest podzielony na 5 klas, które reprezentują każdy rodzaj zwierząt.

Na początku usuwamy uszkodzone zdjęcia.
Później skalujemy nasze zdjęcia i dzielimy na batche.
Mamy generator, który nam może zmienić zdjęcia (przybliżyć lub przekręcić)
I uczymy nasz model na danych.
Później testuję model na zdjęciach pobranych z internetu.

## Biblioteki
* TensorFlow
* NumPy
* PIL
* MatPlotLib
* OS