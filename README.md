# SSN. Lab. 10 Klasyfikacja obrazów i transfer learning

Zapoznaj się z zawartością notatnika Jupyter umieszczonego w repozytorium  i wykonaj zawarte w nim ćwiczenia.

Notatnik: [cnn2.ipynb](https://github.com/IS-UMK/ssn_lab_10/blob/master/cnn2.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IS-UMK/ssn_lab_10/blob/master/cnn2.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IS-UMK/ssn_lab_10/master?filepath=cnn2.ipynb)

---

## Zad. 10 Klasyfikacja psów i kotów

Zbuduj jak najlepszy model klasyfikacji dla zbioru danych kotów i psów wykorzystując transfer learning oraz rozszerzanie danych:
*  w roli ekstraktora cech wybierz dowolny model (oprócz InceptionV3) wytrenowany do klasyfikacji obrazów ImageNet z listy [Keras Applications](https://keras.io/api/applications/). Możesz wybrać dowolną warstwę (lub warstwy) jako wyjście z ekstraktora cech. Wagi modelu należy zamrozić (nie będą podlegały uczeniu)
* na wyjściu ekstraktora cech dodaj przynajmniej jedną warstę w pełni połączoną (gęstą) zawierającą minimum 200 jednostek `relu` wraz z warstwę regularyzacyjną Dropout
* wyjściem sieci będzie pojedynczy neuron z funkcją aktywacji ``sigmoid`` (klasyfikacja binarna)
* przeprowadź preces douczania trwający conajmniej 10 epok z wykorzystaniem rozszerzania zbioru danych poprzez automatyczne generowane transformacje obrazu.
* stwórz wykres prezentujący przebieg wartości funkcji kosztu oraz poprawności klasyfikacji w kolejnych epokach uczenia na zbiorze treningowym i walidacyjnym

Rozwiązanie w postaci notatnika Jupyter (``.ipynb``) lub skrypt w języku Python (``.py``) umieść w repozytorium GitHub.

---
## Materiały:

* [ML Practicum: Image Classification](https://developers.google.com/machine-learning/practica/image-classification?hl=en) 
* [Neurocomputing, Transfer learning](https://julien-vitay.net/lecturenotes-neurocomputing/5-exercises/11-TransferLearning-solution.html)




