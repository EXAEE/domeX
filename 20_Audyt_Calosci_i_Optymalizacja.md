# 20. Audyt Całości projektu domeX + Propozycje Poprawek i Optymalizacji

Data audytu: 16 sierpnia 2026

---

## 1. Spojrzenie na projekt jako na jedną rzecz

DomeX próbował połączyć:
- produkcję żywności,
- energię i mobilność,
- wodę i odpady,
- ciepło i pasywność,
- lokalną inteligencję,
- reużycie,
- odporność,
- estetykę i styl życia.

Ambcja jest wysoka i spójna ideowo.  
Główne napięcie projektu polega na tym, że **pierwotne wymaganie „maksymalnie zautomatyzowany i bezobsługowy”** koliduje z liczbą zaawansowanych modułów (data center, LLM, aquaponics, ściany wodne, bio-basen, kury, pełna oranżeria mieszkalna).

Im więcej inteligentnych i biologicznych podsystemów, tym więcej punktów awarii, decyzji i obsługi.

---

## 2. Znalezione luki i problemy

### A. Luki logiczne i zasadnościowe

1. **Konflikt „bezobsługowy” vs złożoność**  
   Data center + lokalne LLM + zaawansowana automatyka + aquaponics + ewentualne kury tworzą system, który wymaga wiedzy, monitoringu i interwencji. To nie jest system, który można „włączyć i zapomnieć”.

2. **Data center jako mózg – za wcześnie i za drogo energetycznie**  
   Lokalne LLM ma sens jako narzędzie optymalizacji, ale na początku projektu generuje więcej problemów (ciepło latem, zużycie energii, koszt, złożoność) niż rozwiązuje.

3. **Oranżeria duża i mieszkalna vs kontrola klimatyczna**  
   Inspiracje (duże przeszklenia, antresola, przestrzeń życiowa) są piękne, ale w polskim klimacie mocno zwiększają ryzyko przegrzewania latem i strat ciepła zimą, jeśli nie zostaną wykonane w bardzo wysokim standardzie.

4. **Oczekiwania żywnościowe**  
   Nawet przy dobrej oranżerii i food forest realna samowystarczalność kaloryczna pozostaje niska. System dobrze pokrywa warzywa, zioła, część owoców i ryby – i tak powinno zostać jasno nazwane.

5. **Zbyt wiele równoległych innowacji**  
   Ściany wodne + kaskada ciepła + żywa oczyszczalnia + aquaponics + bio-basen + LLM jednocześnie to za dużo eksperymentów na start.

### B. Luki projektowe

- Brak precyzyjnego bilansu energetycznego miesiąc po miesiącu (szczególnie zima).
- Brak obliczeń zysków i strat ciepła oranżerii przy konkretnej wielkości i przeszkleniu.
- Słabe powiązanie wielkości magazynu energii z realnym profilem ładowania EV + pompy ciepła + ewentualnego data center.
- Piwnica / root cellar jest jednym z najwyżej opłacalnych elementów, a w planowaniu często schodzi na dalszy plan.
- Modularność jest deklarowana, ale nie zawsze egzekwowana w priorytetach.

### C. Luki obliczeniowe i finansowe

- Widełki kosztów są szerokie i optymistyczne przy wysokiej jakości oranżerii + standardzie zbliżonym do pasywnego.
- Zwrot z inwestycji w data center / LLM jest trudny do wykazania liczbowo.
- Kredyt etapowy jest lepszy niż duży kredyt, ale nadal wymaga bardzo realistycznej poduszki płynnościowej.
- Brakuje prostego „Minimum Viable DomeX” z jasną ceną i zakresem.

---

## 3. Propozycja uporządkowania – hierarchia wartości

### Must Have (rdzeń, bez którego system traci sens)
1. Izolacja + szczelność + wentylacja z odzyskiem ciepła (dom quasi-pasywny)
2. PV + magazyn energii dopasowany do realnego zużycia
3. Pompa ciepła niskotemperaturowa
4. Oranżeria o kontrolowanej skali (najpierw funkcjonalna, potem reprezentacyjna)
5. Zbieranie deszczówki + sensowna gospodarka greywater
6. Podstawowa produkcja żywności (grządki + oranżeria + piwnica)
7. Kompost / wermikompost

### Should Have (mocno wzmacnia system)
- Żywa oczyszczalnia / modernizacja istniejącej
- Food forest
- Ściany wodne lub inna forma masy termicznej
- Inteligentne sterowanie energią (EMS) bez pełnego data center
- Ładowarka EV
- Dobra piwnica / root cellar

### Could Have (dopiero gdy rdzeń działa i są dane)
- Lokalne LLM / mały data center
- Rozbudowany aquaponics
- Bio-basen
- Antresola i wysoki standard mieszkalny oranżerii
- Pszczoły
- Małe stadko ptaków (świadomie)

### Won’t Have (na tym etapie lub w ogóle)
- Pełny schron bojowy jako priorytet
- Duża hodowla zwierząt mięsnych
- Próba 100 % samowystarczalności kalorycznej
- Jednoczesne wdrażanie wszystkich innowacji naraz

---

## 4. Konkretne poprawki i optymalizacje

### 4.1. Uproszczenie inteligencji
- Na start: Home Assistant + czujniki + proste automaty + ewentualnie mały lokalny model do alertów.
- Pełne „LLM jako mózg” dopiero gdy system fizyczny jest stabilny i są realne dane do analizy.
- Data center traktować jako opcjonalny moduł fazy 3+, a nie element konieczny.

### 4.2. Oranżeria – zmiana podejścia
- Najpierw zbudować **funkcjonalną oranżerię 25–35 m²** z dobrą izolacją północnej ściany, zewnętrznym zacienianiem i masą termiczną.
- Antresolę, dużą przestrzeń mieszkalną i „efekt wow” dodać dopiero po zmierzeniu zachowania klimatycznego pierwszej wersji.
- Priorytet: oranżeria ma być zimą zyskiem, latem nie być problemem.

### 4.3. Energia
- Wymiarować PV i magazyn najpierw pod: dom + pompę ciepła + EV + podstawowe doświetlanie.
- Data center doliczać dopiero gdy powstanie.
- Wprowadzić twardą regułę priorytetów obciążenia (życie → ciepło → żywność → mobilność → obliczenia).

### 4.4. Żywność
- Oficjalnie przyjąć cel: **maksymalne pokrycie warzyw, ziół, microgreens, części owoców i ryb**.
- Piwnica + kiszonki + mrożenie traktować jako równorzędne z produkcją.
- Microgreens i kiełki jako najbardziej automatyzowalny i całoroczny element.

### 4.5. Woda i odpady
- Najpierw deszczówka + proste greywater + solidna oczyszczalnia.
- Żywa oczyszczalnia i bio-basen jako rozwinięcie, nie fundament.

### 4.6. Etapowanie (zaktualizowane, bardziej realistyczne)

**Faza 0**  
Audyt energetyczny, szczelność, mapa słońca i wody, decyzja o skali oranżerii.

**Faza 1 – Fundament odporności**  
Docieplenie + MVHR + PV + magazyn + pompa ciepła + ładowarka EV + podstawowe grządki + kompost + deszczówka.

**Faza 2 – Serce biologiczne**  
Oranżeria w wersji funkcjonalnej + piwnica + greywater + początek food forest.

**Faza 3 – Rozszerzenie i inteligencja**  
Masa termiczna / ściany wodne, żywa oczyszczalnia, bogatsza automatyzacja, ewentualnie aquaponics.

**Faza 4 – Eksperymenty i komfort**  
LLM/data center, antresola, bio-basen, pszczoły, dalsze optymalizacje.

---

## 5. Co zostaje mocne w projekcie

- Idea oranżerii jako organu centralnego
- Kaskada ciepła (z zastrzeżeniem sezonowego wyłączania)
- Silne reużycie i DIY w elementach niekrytycznych
- Dążenie do zamkniętych obiegów wody i składników
- Realistyczne podejście do zwierząt przy diecie wegetariańskiej + ryby
- Świadomość problemów letnich i ryzyk systemowych

---

## 6. Rekomendacja nadrzędna

**Zbuduj najpierw prostszy, mierzący i działający system, a dopiero potem dokładaj inteligencję i innowacje.**

Największą wartością domeX nie jest liczba modułów, tylko to, że elementy mają się wzajemnie wspierać.  
Każdy kolejny moduł powinien przechodzić test:

> „Czy po dodaniu tego elementu system staje się bardziej odporny, prostszy w codziennym życiu albo wyraźnie bardziej produktywny – czy tylko bardziej skomplikowany?”

Jeśli odpowiedź nie jest jasna – odłóż.

---

## 7. Proponowane natychmiastowe działania porządkujące

1. Przyjąć oficjalny podział Must / Should / Could.
2. Zmniejszyć rangę data center i pełnego LLM do fazy późnej.
3. Traktować pierwszą oranżerię jako prototyp klimatyczny, nie od razu wersję finalną z antresolą.
4. Wzmocnić rolę piwnicy i przetwarzania żywności.
5. Zrobić prosty miesięczny bilans energii (nawet szacunkowy) przed kolejnymi decyzjami o mocy PV i magazynu.
6. Każdą innowację (ściany wodne, kaskada, aquaponics) uruchamiać jako mały test, a nie od razu pełną instalację.

---

*Nova – spójność i odporność są ważniejsze niż kompletność wizji.*
