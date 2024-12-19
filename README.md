# DigitRecognizer
Attempts at a Kaggle competition using ML and computer vision to classify images of handwritten digits
This was for my Artificial Intelligence course in my masters program in Computer Science at UTK.

By following the sample code, my initial run returned an accuracy of 0.97485. This
initial run used a CNN model with a batch size of 86 and 1 epoch. In order to improve on
this initial result, I attempted to run the code with different numbers of epochs and found
that both 30 and 35 epochs returned an accuracy of 0.99503. This was the highest
accuracy I was able to reach across all the trials, and due to 30 epochs taking less time
to run, I can conclude that that was the best model.
When looking at the attached documentation I saw that the best performing
models on this database were convolutional nets with a committee of 7 or 35 nets, and
width normalization. Therefore, I attempted to recreate this model and see if I could
improve on the accuracy I was returning with the CNN model. By attempting both 7 and
35 nets with various numbers of epochs, I was able to get very close, but not beat the
previous model. The best accuracy of any of these models was 0.99303, which I
achieved using 35 nets, and 30 epochs. I have attached the code from that model. I spent a lot of time trying to better my
accuracy and didn’t want to just discard these results despite not beating our 0.99503
accuracy.
