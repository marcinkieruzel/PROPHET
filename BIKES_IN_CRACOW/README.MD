# BIKES - Ruch Rowerowy w Krakowie

![Kraków - rower nad Wisłą](krk.jpg)

## Opis projektu

W pliku `bikes.csv` znajduje się duża baza danych na temat ruchu rowerowego w Krakowie.

## Zadania

1. **Przygotowanie danych**
   - Skonwertuj kolumnę z datą do formatu datetime
   - Sprawdź dane pod kątem braków i wartości odstających

2. **Prognoza ruchu rowerowego**
   - Użyj modelu Facebook Prophet do przeprowadzenia prognozy ruchu na lata 2026-2028
   - Przygotuj wizualizację prognozy z przedziałami ufności

3. **Analiza korelacji**
   - Zbadaj korelację między ruchem rowerowym a temperaturą i ilością opadów
   - Stwórz wykresy rozrzutu i macierz korelacji

## Wymagania

- Python 3.x
- Facebook Prophet
- pandas
- matplotlib/seaborn (do wizualizacji)