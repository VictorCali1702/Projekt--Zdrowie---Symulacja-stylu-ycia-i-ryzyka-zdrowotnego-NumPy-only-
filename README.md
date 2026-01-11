# 🏥 Symulacja i Analiza Zdrowotna Populacji (NumPy)

Projekt stanowi zaawansowaną symulację danych medycznych dla populacji 2000 osób dorosłych. Skupia się na analizie wskaźnika BMI, stylu życia oraz modelowaniu efektów prozdrowotnych zmian w nawykach.

## 🛠️ Stos technologiczny
- **Python 3.x**
- **NumPy** (generowanie rozkładów, maskowanie logiczne, symulacja zmian)
- **Matplotlib** (wizualizacja rozkładów i porównanie scenariuszy)
- **VS Code / Jupyter Notebook**

## 📊 Parametry Symulacji
Dane zostały wygenerowane z wykorzystaniem różnych rozkładów statystycznych:
- **Wiek:** 18 - 80 lat (rozkład jednostajny)
- **Wzrost:** Średnia 170 cm (rozkład normalny)
- **Waga:** Średnia 75 kg (rozkład normalny)
- **Palenie:** 25% populacji (rozkład prawdopodobieństwa)
- **Aktywność:** Niska, średnia, wysoka (losowy wybór)

## 🔍 Zakres Analizy
1. **Kategoryzacja BMI:** Automatyczne wyliczanie wskaźnika BMI oraz identyfikacja osób z nadwagą i otyłością.
2. **Definicja Grupy Ryzyka:** Stworzenie złożonej maski logicznej łączącej parametry fizyczne ze stylem życia (palenie, brak ruchu).
3. **Symulacja Poprawy:** Modelowanie scenariusza "Co jeśli?", w którym grupa ryzyka redukuje wagę o 5% i zwiększa poziom aktywności fizycznej.

## 📈 Kluczowe Wnioski
- Projekt demonstruje, jak proste zmiany w stylu życia (redukcja masy o 5%) wpływają na przesunięcie całej krzywej rozkładu BMI w populacji.
- Wykorzystanie **operacji wektorowych** pozwoliło na natychmiastowe przeliczenie danych dla wszystkich 2000 obiektów bez użycia pętli `for`.
- Wizualizacja przed i po symulacji wyraźnie pokazuje liczbę osób, które dzięki zmianom opuściły strefę wysokiego ryzyka zdrowotnego.

---
**Autor:** Wiktor Naczk
*Projekt wykonany w środowisku VS Code przy użyciu biblioteki NumPy.*