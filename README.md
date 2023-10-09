# Numbers

The program is designed to recognize written digits and using a classification algorithm
KNN (k nearest neighbors) predict their values.
The program assigns an object from the validation set (photo of a digit) of an unknown class (from 0 to
9) to the most frequently occurring class among its k nearest neighbors. The algorithm calculates
distance between the checked object and other objects in the training set at
using Euclidean distance, and then selects the k nearest neighbors and assigns it
class based on their majority affiliation.

# User manual
When you start the program for the first time, you must run all the commands you can do
done using the "Run All" button. The next time you run the program, this will be enough
run the "data shuffling" part of the code and the "performance calculation" part of the code
algorithm", in the length of sets section of the code you can modify the size of the training set
and test. The data are photos of handwritten numbers and their corresponding values.
The photos have a size of 28x28px, the database is divided into two test sets of size
10,000 photos and a training one of 60,000. This set of photos was downloaded from kaggle.com.
The program result appears in the console, the current progress is displayed in real time.
seeing numbers from the test set and after all calculations, a percentage appears
effectiveness for the KNN algorithm.

![Algorytm KNN](https://github.com/Dryzhakova/Numbers/raw/master/Photo/Algorytm\KNN.png)

