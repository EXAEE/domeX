# 05. Energia + Data Center + Lokalne LLM

## Rola w systemie

Energia jest kręgosłupem, a lokalne LLM + sensory – układem nerwowym domeX.

## Fotowoltaika + magazyn

### Zalecenia
- Panele na dachu domu + oranżerii (maksymalne wykorzystanie powierzchni).
- Magazyn LiFePO4 wymiarowany nie tylko pod dom, ale też pod szczytowe obciążenia data center i grow lights.
- Hybrydowy falownik + dobry EMS (Energy Management System).
- Priorytetyzacja obciążeń (życie domu → pompa ciepła → data center przy nadwyżce → uprawy).

### Integracja
- Nadwyżki energii kierowane do data center (dynamiczne obciążenie).
- Ciepło odpadowe z data center → kaskada ciepła (oranżeria).

## Mini Data Center / Lokalne LLM

### Cel
Nie „zabawka”, tylko praktyczny mózg systemu:
- Analiza obrazów z kamer (szkodniki, niedobory, wzrost roślin)
- Optymalizacja parametrów klimatycznych i energetycznych
- Predykcja i alerty
- Lokalne asystenty do dokumentacji i planowania
- Pełna prywatność (dane nie wychodzą na zewnątrz)

### Rekomendowany start
- 1 mocna stacja robocza lub mały serwer z 1–2 dobrymi GPU (można używane, ale sprawdzone)
- Dobry system chłodzenia (powietrze lub ciecz) z odzyskiem ciepła
- Lokalny stack: Ollama / llama.cpp / podobne + Home Assistant + ESPHome
- Kamery i sensory jako źródło danych

### Rozwój
Skalować tylko wtedy, gdy:
- jest realna potrzeba mocy obliczeniowej,
- jest nadwyżka energii,
- dane pokazują, że lokalne modele dają mierzalną wartość.

## Dynamiczne obciążenie (propozycja)

LLM inference i cięższe zadania uruchamiane preferencyjnie:
- gdy jest nadwyżka z PV,
- gdy magazyn jest bliski pełna,
- gdy cena energii jest niska (jeśli net-billing / taryfy dynamiczne).

## Bezpieczeństwo i ryzyka
- Chłodzenie i odprowadzanie ciepła – krytyczne
- Zasilanie awaryjne (UPS + magazyn)
- Zabezpieczenie fizyczne i dostępowe
- Monitorowanie temperatur GPU i zasilaczy

---

*Nova – energia zasila, LLM myśli, ciepło wraca do obiegu.*
