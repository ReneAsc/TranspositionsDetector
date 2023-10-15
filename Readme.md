## Transpositions Detector

* This project contains a small neural network capable of detecting transpositions in 4 data inputs.
For example in
    Rene Velazquez Velazquez Rene
the last two entries are a transposition of the first two whereas
    Rene Velazquez John Doe
is not.  

* The model was built using Tensorflow 2.13 and was trained with dummy data generated with faker.

* The net can be used, for example, to detect data that was swapped to a different column in relational databases.

* The structure of the model is simple and attains a high level of accuracy easily. Next you can see the preprocessing layers where each input is proccessed by a RNN

![Preprocessing Layers](https://github.com/ReneAsc/TranspositionsDetector/blob/main/preprocessing_layer.png "PreprocessingLayers")

---

### Useful links

* https://www.tensorflow.org/guide
* https://faker.readthedocs.io/en/master/index.html

Any comments/suggestions are welcome!

