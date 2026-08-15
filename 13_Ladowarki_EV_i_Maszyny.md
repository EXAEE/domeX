# 13. Ładowarki EV, Motocykla i Maszyn

## 1. Samochód elektryczny

### Rekomendowane rozwiązania

| Typ | Moc | Zastosowanie | Orientacyjna cena (2026) | Uwagi |
|-----|-----|--------------|---------------------------|-------|
| Wallbox 7,4 kW (1-fazy) | 7,4 kW | Dom z przyłączem 1-fazowym lub słabym 3-fazowym | 2 500 – 4 500 zł | Najtańszy sensowny start |
| Wallbox 11 kW (3-fazy) | 11 kW | Standard dla większości domów | 3 500 – 6 500 zł | Najlepszy stosunek cena/moc |
| Wallbox 22 kW (3-fazy) | 22 kW | Szybkie ładowanie domowe | 5 000 – 9 000 zł | Warto, jeśli często jeździsz dużo |

**Dodatkowo warto:**
- Model z pomiarem energii i sterowaniem przez WiFi / Modbus / OCPP
- Możliwość integracji z Home Assistant
- Zabezpieczenie różnicowoprądowe dedykowane
- Opcja dynamicznego sterowania mocą (żeby nie wywalać korków)

### Miejsce montażu
- Na ścianie domu od strony podjazdu
- Na osobnym słupku przy miejscu postojowym
- Najlepiej pod zadaszeniem

---

## 2. Motocykl / skuter elektryczny

- Większość ładuje się zwykłym gniazdem 230 V (schuko) lub ma własną ładowarkę
- Wystarczy solidne gniazdo 16 A z osobnym zabezpieczeniem w szafce / wiacie
- Opcjonalnie mała stacja 3,7 kW jeśli chcesz szybciej

---

## 3. Maszyny i narzędzia akumulatorowe

- Jedna centralna szafka ładowania narzędzi (kosiarka, podkaszarka, piła, wkrętarki itd.)
- Zasilanie z osobnego obwodu 230 V
- Najlepiej w warsztacie / wiacie / garażu
- Można dodać mały UPS lub priorytet ładowania z nadwyżek PV

---

## 4. Inteligentne zarządzanie

Cel: ładować głównie wtedy, gdy:
- jest nadwyżka z PV, lub
- magazyn energii jest bliski pełna, lub
- obowiązuje tania taryfa.

Narzędzia:
- Home Assistant + integracje wallboxów
- Lokalne LLM do przewidywania i optymalizacji
- Czujniki mocy na przyłączu

---

## 5. Rekomendowany zestaw startowy

1. Wallbox 11 kW z WiFi / sterowaniem
2. Solidne gniazdo 230 V do motocykla i narzędzi
3. Osobny obwód + zabezpieczenia
4. Integracja z EMS domu

Później można dodać drugą ładowarkę lub zwiększyć moc.

---

*Nova*
