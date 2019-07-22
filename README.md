# Machine Learning with Python 1 (Classification)
Membandingkan hasil akurasi **klasifikasi** dari algoritma **Machine Learning**, antara lain: 

* k - Nearest Neighbor (k-NN)
* Naïve Bayes
* Logistic Regression
* Support Vector Machines (SVMs)
* Decision Trees
* Random Forests
* Neural Networks

Kode dibawah ini executable dan viewable yang tersedia di **Jupyter Notebook**.

[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ksnugroho/machine-learning/master?filepath=ml-python-classification.ipynb)
[![nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.jupyter.org/github/ksnugroho/machine-learning/blob/master/ml-python-classification.ipynb)

## Library
1. [Scikit Learn](https://scikit-learn.org) - Machine learning library for Python.

## Dataset
Dataset yang digunakan adalah **iris dataset** yang sudah tersedia di library `scikit learn`.

<img src="https://github.com/ksnugroho/machine-learning/blob/master/Iris%20Dataset.png" width="500">

## Result
Hasil ujicoba 7 algoritma yang digunakan untuk klasifikasi dataset iris dapat digambarkan ke sebuah tabel sebagai berikut:

| Algoritma                      | Akurasi (%) |
|--------------------------------|-------------|
| k - Nearest Neighbor (k-NN)    |      95     |
| Naïve Bayes                    |      97     |
| Logistic Regression            |      97     |
| Support Vector Machines (SVMs) |      97     |
| Decision Trees                 |      95     |
| Random Forests                 |      97     |
| Neural Networks                |      97     |

Berdasaran tabel diatas, Algoritma k - Nearest Neighbor (k-NN) dan Decision Tress memiliki nilai akurasi yang lebih rendah (95%) dibandingkan 5 algoritma lainnya (97%).  

Setiap algoritma memiliki cara yang berbeda untuk menyelesaikan masalah klasifikasi pada dataset yang diberikan. Selain itu, masing-masing algoritma memiliki parameter yang harus diberikan untuk mendapatkan nilai akurasi yang maskimal. Contohnya pada model k-NN diatas, nilai *k* yang diberikan adalah 1. Jika diberikan nilai *k* yang berbeda tentunya akan menghasilkan nilai akurasi yang berbeda pula.
