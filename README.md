# SSN. Lab. 10 Klasyfikacja obrazów i transfer learning

Zapoznaj się z zawartością notatnika Jupyter umieszczonego w repozytorium  i wykonaj zawarte w nim ćwiczenia.

Notatnik: [cnn2.ipynb](https://github.com/IS-UMK/ssn_lab_10/blob/master/cnn2.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IS-UMK/ssn_lab_10/blob/master/cnn2.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IS-UMK/ssn_lab_10/master?filepath=cnn2.ipynb)

---

## Zad. 10 Klasyfikacja psów i kotów

Zbuduj jak najlepszy model klasyfikacji dla zbioru danych kotów i psów wykorzystując transfer learning oraz rozszerzanie danych:
*  w roli ekstraktora cech wybierz dowolny model wytrenowany na danych ImageNet. <br> Lista modeli dostępnych w Keras znajduje się tu [Model ZOO](https://keras.io/api/applications/). 
* na wyjściu ekstraktora cech dodaj jedną warstwę w pełni połączoną (gęstą) zawierającą minimum 200 jednostek `relu` oraz warstwę regularyzacyjną Dropout a następnie wyjście sieci z jednym neuronem i funkcją aktywacji ``sigmoid`` (klasyfikacja binarna).
* przeprowadź precess douczania trwający co najmniej 10 epok z wykorzystaniem rozszerzania zbioru danych poprzez automatyczne generowane transformacje obrazu
* wyrysuj przebieg funkcji kosztu oraz poprawności klasyfikacji na zbiorze treningowym i walidacyjnym 
  

Rozwiązanie w postaci notatnika Jupyter (``.ipynb``) lub skrypt w języku Python (``.py``) umieść w Moodle lub prześlij do repozytorium GitHub.

---
## Materiały:

* [ML Practicum: Image Classification](https://developers.google.com/machine-learning/practica/image-classification?hl=en) 
* [Neurocomputing, Transfer learning](https://julien-vitay.net/lecturenotes-neurocomputing/5-exercises/11-TransferLearning-solution.html)




