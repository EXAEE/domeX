# 01. Mapa Przepływów domeX

## Główne obiegi

### 1. Energia elektryczna
```
Słońce → PV (dach domu + oranżeria)
         ↓
    Magazyn energii (baterie)
         ↓
    Priorytety EMS:
    1. Życie domu (oświetlenie, podstawowe)
    2. Pompa ciepła
    3. Data center / LLM (przy nadwyżce)
    4. Grow lights + pompy upraw
    5. Grzanie rezerwowe / inne
```

### 2. Kaskada ciepła
```
Data Center (ciepło odpadowe)
         ↓
Oranżeria (powietrze + ściany wodne)
         ↓
Dom (niskotemperaturowa instalacja / podłogówka)
         ↓
Zbiorniki aquaponics / masa termiczna
```

Latem: oranżeria + masa termiczna + wentylacja nocna pomagają chłodzić.

### 3. Woda
```
Deszczówka → Cysterny (częściowo podziemne)
              ↓
         Uzupełnianie upraw + eventualmente dom

Greywater → Biofiltry roślinne w oranżerii / strefie buforowej
              ↓
         Nawadnianie / aquaponics

Ścieki czarne → Żywa oczyszczalnia (biologiczna + roślinna)
              ↓
         Woda do ogrodu + osad → kompost
```

### 4. Składniki odżywcze
```
Odpady kuchenne + resztki roślinne + osad + odchody ryb
         ↓
Wermikompost / kompost
         ↓
Grządki + oranżeria + food forest
```

### 5. Informacja
```
Czujniki + kamery
         ↓
Lokalne LLM + Home Assistant
         ↓
Decyzje / alerty / optymalizacja / dokumentacja
```

## Diagram koncepcyjny (ASCII)

```
                    [Słońce]
                       |
                    [PV + Magazyn]
                       |
         +-------------+-------------+
         |             |             |
   [Data Center]  [Pompa ciepła]  [Uprawy/LED]
         |             |             |
         +------→ [Oranżeria] ←------+
                      |
              +-------+-------+
              |               |
           [Dom]         [Aquaponics /
                           Ściany wodne]
              |
         [Żywa oczyszczalnia] ← Greywater + Czarne
              |
         [Food forest / Grządki]
```

---

*Nova*
