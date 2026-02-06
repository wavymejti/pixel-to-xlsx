# Pixel to XLSX 🎨📊

Skrypt Python, który analizuje obraz i konwertuje dane o kolorach pikseli do arkusza kalkulacyjnego Excel (.xlsx).

## Funkcje
* Odczyt danych z plików graficznych.
* Wykorzystanie biblioteki `pandas` do strukturyzacji danych.
* Eksport do formatu Excel przy użyciu `openpyxl`.

## Wymagania
* Python 3.12+
* Biblioteki: `pandas`, `openpyxl`, `Pillow` (zależnie od tego, jakiej biblioteki używasz do wczytywania obrazów)

## Instalacja i uruchomienie

1. Sklonuj repozytorium:
    git clone [https://github.com/wavymejti/pixel-to-xlsx.git](https://github.com/wavymejti/pixel-to-xlsx.git)
    cd pixel-to-xlsx```
2. Stwórz i aktywuj wirtualne środowisko:
    python3 -m venv env
    # macOS/Linux:
    source env/bin/activate
    # Windows:
    .\env\Scripts\activate
3. Zainstaluj wymagane biblioteki:
    pip install pandas openpyxl


Struktura projektu
pixel.py – główny skrypt programu.

env/ – (ignorowane przez git) wirtualne środowisko Pythona.

.gitignore – plik definiujący, których plików nie wysyłać do repozytorium.