Porgram na ocenę 3.0 - modyfikacja domyślnej strony z pogodą.

Opis programu:
Aplikacja Blazor wyświetla 10-dniową prognozę pogody i pozwala filtrować dane:
- według opisu (np. "Hot", "Freezing")
- według temperatury (powyżej 15°C)

Dodatkowo pokazuje liczbę ciepłych dni (TemperatureC > 15°C).

Opis interfejsu:
- Tabela z datą, temperaturą (C/F), opisem
- Pole tekstowe do filtrowania po opisie
- Przycisk "Warm Days Filter" (pokazuje tylko dni > 15°C)
- Przycisk "Reset" (przywraca pełną listę)
- Licznik dni ciepłych

Opis działania:
Dane generowane są losowo przy starcie. Filtrowanie i reset automatycznie aktualizują tabelę. Użycie tablicy (a nie listy) w `filteredForecasts` zapewnia poprawne odświeżanie danych w Blazorze.
