# SimpleHTR
Handwritten Text Recognition (HTR) system implemented with TensorFlow (TF) and trained on the IAM off-line HTR dataset.
This Neural Network (NN) model recognizes the text contained in the images of segmented words as shown in the illustration below.
As these word-images are smaller than images of complete text-lines, the NN can be kept small and training on the CPU is feasible.
3/4 of the words from the validation-set are correctly recognized and the character error rate is around 10%.
I will give some hints how to extend the model in case you need larger input-images (e.g. to recognize text-lines) or want better recognition accuracy.

