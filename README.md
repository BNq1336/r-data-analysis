# IMDb Series Episode Rating Analysis

Projekt analizy ocen odcinków seriali wykonany w języku R z wykorzystaniem Quarto oraz danych IMDb.

## Opis projektu

Celem projektu jest analiza ocen odcinków wybranego serialu na podstawie danych z oficjalnych datasetów IMDb.

Raport:
- pobiera dane IMDb,
- analizuje sezony i odcinki,
- oblicza średnie ocen,
- generuje wykresy i tabele,
- tworzy raport HTML.

Projekt pozwala szybko sprawdzić:
- najlepiej oceniane sezony,
- rozkład ocen odcinków,
- trendy jakości serialu w czasie.

---

# Technologie

- R
- Quarto
- Base R
- IMDb Datasets

---

# Wykorzystane dane

Projekt korzysta z publicznych danych IMDb:

- `title.basics.tsv`
- `title.episode.tsv`
- `title.ratings.tsv`

Źródło danych:

https://datasets.imdbws.com/

---

# Funkcjonalności

## Analiza serialu
- wyszukiwanie serialu po nazwie,
- pobieranie ID serialu,
- analiza liczby sezonów.

## Statystyki ocen
- średnia ocen sezonów,
- najwyżej i najniżej oceniane sezony,
- analiza ocen odcinków.

## Wizualizacje
- wykres średnich ocen sezonów,
- szczegółowa wizualizacja ocen wszystkich odcinków.

---

# Jak uruchomić projekt

## 1. Pobierz repozytorium

```bash
git clone https://github.com/twoj-nick/imdb-series-analysis.git
```

## 2. Otwórz projekt w RStudio

## 3. Zainstaluj wymagane pakiety

```r
install.packages("R.utils")
```

## 4. Uruchom renderowanie Quarto

```r
quarto render P_01_Baginski.qmd
```

---

# Konfiguracja

W pliku `.qmd` można zmienić nazwę analizowanego serialu:

```r
serial_name <- "Breaking Bad"
```

Przykłady:
- `"Game of Thrones"`
- `"Dark"`
- `"Friends"`
- `"The Office"`

---

# Przykładowe wyniki

Projekt generuje:
- raport HTML,
- tabele statystyczne,
- wykresy ocen sezonów i odcinków.

---

# Autor

Paweł Bagiński

Student Informatyki  
Uniwersytet Ekonomiczny w Katowicach  
Specjalizacja: Bazy Danych i Inżynieria Danych
