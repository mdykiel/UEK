# 5. WYCENA METODĄ DOCHODOWĄ (DCF)

## 5.1 Metodologia

### Formuła FCFF
```
FCFF = EBIT × (1 - stopa podatku) + Amortyzacja - CAPEX +/- Zmiana kapitału pracującego
```

### Stopa dyskontowa (WACC)
**Obliczony WACC: 18,50%**

**Składniki:**
- **Stopa wolna od ryzyka:** 5,72% (rentowność 10-letnich obligacji skarbowych)
- **Premia za ryzyko rynkowe:** 5,84% (dane Damodarana dla Polski)
- **Beta odciążona:** 0,57 (średnia grupy porównawczej)
- **Beta dociążona:** 0,70
- **Narzut na ryzyko specyficzne:** 11,00%
- **Koszt kapitału własnego:** 20,78%
- **Koszt długu:** 8,04%
- **Struktura kapitału:** 84% kapitał własny, 16% dług

## 5.2 Założenia prognostyczne

### Przychody
| Rok | Wzrost r/r | Przychody (PLN) |
|-----|------------|-----------------|
| 2024 | 8,0% | 5 537 002 |
| 2025 | 10,0% | 6 087 495 |
| 2026 | 8,0% | 6 574 495 |
| 2027 | 6,0% | 6 968 965 |
| 2028 | 4,0% | 7 247 723 |
| 2029 | 2,5% | 7 428 916 |

### Główne założenia kosztowe
- **Wynagrodzenia:** wzrost zgodny z prognozami inflacji wynagrodzeń NBP
- **Usługi obce:** indeksacja zgodnie z inflacją CPI
- **Materiały i energia:** wzrost zgodny z inflacją cen energii
- **Pozostałe koszty:** indeksacja inflacją CPI

### Kapitał pracujący
- **Należności:** 90 dni rotacji
- **Zapasy:** 0,64 dnia rotacji (minimalne)
- **Zobowiązania:** 25 dni rotacji

### Nakłady inwestycyjne (CAPEX)
- **2024:** 50 000 PLN
- **2025-2027:** 50 000 PLN rocznie (50% salda środków trwałych)
- **2028-2029:** 50 000 PLN rocznie (45% salda środków trwałych)

### Amortyzacja
- Przewidywana na poziomie 45% wartości środków trwałych na początek roku

## 5.3 Prognoza przepływów pieniężnych

### Szczegółowa prognoza FCFF (w PLN)

| Okres | 2H 2024 | 2025 | 2026 | 2027 | 2028 | 2029 |
|-------|----------|------|------|------|------|------|
| **EBIT** | 1 062 771 | 1 211 263 | 1 240 435 | 1 201 630 | 1 333 049 | 1 364 342 |
| **Podatek (19%)** | -201 926 | -230 140 | -235 683 | -228 310 | -253 279 | -259 225 |
| **NOPAT** | 860 844 | 981 123 | 1 004 752 | 973 320 | 1 079 770 | 1 105 117 |
| **Amortyzacja** | 16 689 | 31 679 | 39 923 | 44 458 | 46 952 | 48 323 |
| **CAPEX** | -13 120 | -50 000 | -50 000 | -50 000 | -50 000 | -50 000 |
| **Zmiana kap. pracującego** | -297 700 | -122 222 | -90 143 | -68 592 | -59 303 | -34 822 |
| **FCFF** | 566 713 | 840 580 | 904 533 | 899 186 | 1 017 419 | 1 068 618 |

### Wartość rezydualna
- **Wzrost długoterminowy:** 2,5%
- **FCFF 2029 × (1 + g) / (WACC - g):** 6 856 890 PLN

## 5.4 Dyskontowanie przepływów

### Czynniki dyskontowe
| Okres | Odległość | Czynnik dyskontowy |
|-------|-----------|-------------------|
| 2H 2024 | 0,5 | 0,92 |
| 2025 | 1,5 | 0,78 |
| 2026 | 2,5 | 0,65 |
| 2027 | 3,5 | 0,55 |
| 2028 | 4,5 | 0,47 |
| 2029 | 5,5 | 0,39 |

### Zdyskontowane przepływy
| Okres | FCFF | Wartość bieżąca |
|-------|------|-----------------|
| 2H 2024 | 566 713 | 520 601 |
| 2025 | 840 580 | 651 637 |
| 2026 | 904 533 | 591 746 |
| 2027 | 899 186 | 496 415 |
| 2028 | 1 017 419 | 474 001 |
| 2029 | 1 068 618 | 420 133 |
| Wartość rezydualna | 6 856 890 | 2 695 821 |
| **Suma** | - | **5 850 353** |

## 5.5 Wartość kapitału własnego

### Kalkulacja wartości equity
- **Suma zdyskontowanych przepływów:** 5 850 353 PLN
- **Plus: Gotówka (30.06.2024):** 6 141 521 PLN
- **Minus: Dług oprocentowany:** 0 PLN
- **Minus: Zobowiązania z tyt. dywidend:** 0 PLN

**Wartość kapitału własnego (metoda DCF): 11 991 874 PLN**
