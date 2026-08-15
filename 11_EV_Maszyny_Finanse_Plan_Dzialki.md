# 11. EV + Maszyny + Finanse + Rozplanowanie na Działce

**Aktualizacja systemu domeX** – 15 sierpnia 2026

---

## 1. Nowe potrzeby: samochód i motocykl elektryczny + maszyny

### Założenia
- 1 samochód elektryczny (typowy zasięg 300–450 km, zużycie 15–20 kWh/100 km)
- 1 motocykl / skuter elektryczny
- Maszyny ogrodowe i warsztatowe na prąd (kosiarka, podkaszarka, piła, elektronarzędzia, ewentualnie mała ładowarka do narzędzi akumulatorowych)

### Wpływ na system energetyczny

**Szacunkowe dodatkowe zużycie roczne:**
- Samochód (12–15 tys. km/rok): 1 800 – 3 000 kWh/rok
- Motocykl (3–5 tys. km/rok): 150 – 400 kWh/rok
- Maszyny i narzędzia: 100 – 300 kWh/rok
- **Razem dodatkowe: ok. 2 100 – 3 700 kWh/rok**

To oznacza konieczność:
- Zwiększenia mocy PV o ok. 2–4 kWp (w zależności od lokalnej insolacji i autokonsumpcji)
- Ewentualnego powiększenia magazynu energii (szczególnie jeśli ładowanie nocne)
- Inteligentnego zarządzania ładowaniem (ładowanie głównie z nadwyżek PV + w godzinach taniej taryfy)

### Integracja z istniejącym systemem
- Ładowarki ścienne (Wallbox) przy garażu / podjeździe – sterowane przez EMS
- Priorytet ładowania: najpierw dom + pompa ciepła + uprawy, potem EV gdy jest nadwyżka
- Możliwość V2H / V2L w przyszłości (samochód jako magazyn awaryjny) – warto wybierać modele z taką opcją
- Miejsce na ładowanie motocykla i narzędzi w warsztacie / garażu

### Modularność
System pozostaje modularny:
- Można zacząć od jednej ładowarki 7–11 kW
- Magazyn i PV da się rozbudowywać etapami
- EMS (Home Assistant + lokalne LLM) łatwo dopisuje nowe obciążenia

---

## 2. Przeliczenie przestrzeni na działce

### Minimalne / optymalne zapotrzebowanie powierzchni (orientacyjne)

| Element                        | Powierzchnia orientacyjna     | Uwagi |
|--------------------------------|-------------------------------|-------|
| Dom + oranżeria                | 120–200 m² zabudowy           | Oranżeria 20–40 m² |
| Food forest + grządki intensywne | 150–400 m²                   | Im więcej tym lepiej |
| Podjazd + miejsca parkingowe EV | 40–80 m²                      | 2 miejsca + manewry |
| Warsztat / garaż (naziemny lub podziemny) | 25–50 m²                 | Na narzędzia + ładowanie |
| Cysterny + technika            | 10–30 m²                      | Częściowo podziemne |
| Żywa oczyszczalnia + złoże roślinne | 20–60 m²                   | |
| Ścieżki, bufory, kompost       | 50–100 m²                     | |
| **Razem użytkowe**             | **ok. 400–900 m²**            | Przy działce 800–1500 m² wygodnie, poniżej 600 m² robi się ciasno |

**Wniosek:**  
Najlepiej mieć działkę **min. 800–1000 m²** netto (bez dróg dojazdowych).  
Poniżej 600 m² system da się zmieścić, ale trzeba iść mocno w pion (oranżeria + vertical) i podziemne rozwiązania.

---

## 3. Wstępne rozplanowanie na załączonym planie działki

Na podstawie Twojego rysunku (dom w centrum, podjazd od prawej, dużo zieleni po lewej, oczyszczalnia zaznaczona, stara studnia, brama i furtka):

### Propozycja stref

**Strefa wschodnia / podjazd (prawa strona rysunku)**
- Główny podjazd zostaje
- 1–2 miejsca postojowe EV + ładowarka ścienna (najlepiej zadaszone lub przy budynku)
- Ewentualny mały garaż / wiata na motocykl i narzędzia

**Strefa północno-wschodnia (przy oczyszczalni)**
- Rozbudowa / modernizacja przydomowej oczyszczalni → żywa oczyszczalnia z złożem roślinnym
- Bufor roślinny oddzielający od drogi

**Strefa centralna – dom + oranżeria**
- Oranżeria od strony południowej lub południowo-zachodniej domu (najlepsza ekspozycja)
- Połączenie oranżerii z domem (ganek / drzwi)
- Ściany wodne wewnątrz oranżerii

**Strefa zachodnia / lewa (dużo zieleni)**
- Food forest (warstwy wieloletnie)
- Podniesione grządki / keyhole bliżej domu
- Kompost i wermikompost

**Strefa południowa / przy furtce i betonowym chodniku**
- Intensywne grządki + ewentualne pionowe systemy
- Łatwy dostęp z domu

**Podziemne (jeśli decydujesz się)**
- Piwnica / magazyn najlepiej pod oranżerią lub od strony północnej domu
- Cysterny deszczówki pod podjazdem lub w sąsiedztwie domu

**Technika i data center**
- Data center najlepiej w pomieszczeniu technicznym domu lub w podziemiu (stabilna temperatura + łatwe odprowadzenie ciepła do oranżerii)

### Kolejność zajmowania terenu
1. Dom + podjazd + ładowanie EV
2. Oranżeria (południe)
3. Oczyszczalnia + złoże roślinne
4. Food forest i grządki (zachód i południe)
5. Podziemny magazyn / cysterny

---

## 4. Finanse – dotacje, kredyt, finansowanie własne

### Aktualne główne programy wsparcia (2026, orientacyjnie)
- **Mój Prąd** – PV + magazyn energii
- **Czyste Powietrze** – pompa ciepła, termomodernizacja, czasem rekuperacja
- Ulga termomodernizacyjna (PIT)
- Lokalne programy gminne / WFOŚiGW (oczyszczalnie, czasem zazielenienie)
- Ewentualne dopłaty do ładowarek EV / pojazdów elektrycznych (sprawdzać aktualne nabory)

### Scenariusze finansowania (orientacyjne dla całości synergicznej + EV)

**Scenariusz A – wszystko z własnych środków**
- Najbezpieczniejszy
- Wolniejszy
- Zero odsetek
- Wymaga cierpliwości i etapowania

**Scenariusz B – kredyt etapowy (rekomendowany)**
- Kredyt tylko na fazę 1 (energia + pompa + podstawowa woda + ładowarka EV)
- Kolejne fazy z oszczędności + ewentualnie małe dopłaty
- Niższe ryzyko niż jeden duży kredyt

**Scenariusz C – duży kredyt na całość**
- Możliwy, ale ryzykowny (rata 4–7 tys. zł miesięcznie przy 300–450 tys. zł)
- Oszczędności energetyczne + żywnościowe pokrywają tylko część raty
- Warto tylko przy bardzo stabilnej sytuacji finansowej i maksymalnym wykorzystaniu dotacji

### Porównanie (uproszczone)

| Podejście              | Koszt odsetek | Tempo realizacji | Ryzyko | Rekomendacja |
|------------------------|---------------|------------------|--------|--------------|
| Własne środki          | 0             | Wolne            | Niskie | Najlepsze długoterminowo |
| Kredyt etapowy         | Średnie       | Średnie          | Średnie | Najrozsądniejszy kompromis |
| Duży kredyt na wszystko| Wysokie       | Szybkie          | Wysokie | Tylko przy silnej poduszce finansowej |

---

## 5. Zaktualizowane priorytety wdrożenia (z EV)

**Faza 1 (najwyższy zwrot + nowe potrzeby)**
- PV + magazyn (z zapasem pod EV)
- Pompa ciepła
- Ładowarka EV + miejsce postojowe
- Podstawowa modernizacja wody / oczyszczalni
- Mały start upraw

**Faza 2**
- Oranżeria + integracja ciepła i greywater
- Food forest + grządki
- Warsztat / miejsce na maszyny

**Faza 3**
- Data center + pełna automatyzacja
- Ściany wodne i kaskada ciepła w pełnej wersji
- Podziemny magazyn (opcjonalnie)

---

## 6. Podsumowanie zmian w systemie

Dodanie EV i maszyn:
- Zwiększa zapotrzebowanie na PV i magazyn
- Wymusza inteligentne zarządzanie energią (bardzo dobrze współgra z lokalnym LLM + EMS)
- Wymaga miejsca na podjeździe / przy domu
- Nie psuje modularności – da się dodawać etapami

Rozplanowanie na Twojej działce jest wykonalne. Najcenniejsze strefy to:
- Południe/południowy-zachód od domu → oranżeria
- Zachód → food forest
- Wschód przy podjeździe → EV + ewentualny garaż
- Okolice obecnej oczyszczalni → żywa oczyszczalnia

---

*Nova – system rośnie razem z potrzebami, a nie odwrotnie.*
