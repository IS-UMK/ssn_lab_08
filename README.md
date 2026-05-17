# SSN. Lab. 8 Klasyfikacja obrazów i transfer learning

* [cnn2.ipynb](cnn2.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IS-UMK/ssn_lab_08/blob/master/cnn2.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IS-UMK/ssn_lab_08/master?filepath=cnn2.ipynb)
* [README.md](README.md) - treść zadania
* [zadanie.ipynb](zadanie.ipynb) - notatnik, w którym należy umieścić rozwiązanie zadania
* [dane/hymenoptera_data.zip](dane/hymenoptera_data.zip) - zbiór danych do zadania (mrówki i pszczoły)

---

## Zad. 8 Klasyfikacja obrazów i transfer learning

Zbuduj jak najlepszy model klasyfikacji dla zbioru danych mrówek i pszczół ([dane/hymenoptera_data.zip](dane/hymenoptera_data.zip)), wykorzystując transfer learning oraz rozszerzanie danych:

* rozpakuj zbiór danych z pliku [dane/hymenoptera_data.zip](dane/hymenoptera_data.zip) i zapoznaj się z jego strukturą. Zbiór danych zawiera obrazy dwóch klas: mrówek (`ants`) i pszczół (`bees`). Dane są podzielone na zbiór treningowy (`train`) i walidacyjny (`val`).
* w roli ekstraktora cech wybierz dowolny model (oprócz InceptionV3) wytrenowany do klasyfikacji obrazów ImageNet z listy [Keras Applications](https://keras.io/api/applications/). Możesz wybrać dowolną warstwę (lub warstwy) jako wyjście z ekstraktora cech. Wagi modelu pełniącego rolę ekstraktora należy zamrozić (nie będą podlegały uczeniu).
* na wyjściu ekstraktora cech dodaj przynajmniej jedną warstwę gęstą z aktywacją `relu` oraz regularyzację Dropout.
* wyjściem sieci będzie pojedynczy neuron z funkcją aktywacji `sigmoid` (klasyfikacja binarna).
* przeprowadź dostrojenie (_fine-tuning_) uzyskanego modelu z wykorzystaniem rozszerzania zbioru danych poprzez automatycznie generowane transformacje obrazów (dobierz odpowiednie transformacje, np. obrót, przesunięcie, odbicie lustrzane itp.).
* stwórz wykres prezentujący przebieg wartości funkcji kosztu oraz poprawności klasyfikacji w kolejnych epokach uczenia na zbiorze treningowym i walidacyjnym.
* wyznacz poprawność klasyfikacji na zbiorze walidacyjnym.

Rozwiązanie umieść w notatniku [zadanie.ipynb](zadanie.ipynb) lub w osobnym skrypcie Python (`.py`). W przypadku realizacji rozwiązania w formie skryptu umieść w repozytorium także pliki z wynikami (np. wyjście programu, wykresy itp.).

---

## Materiały:

* [Neurocomputing, Transfer learning](https://julien-vitay.net/lecturenotes-neurocomputing/5-exercises/11-TransferLearning-solution.html)




