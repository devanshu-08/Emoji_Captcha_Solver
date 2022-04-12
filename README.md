# Emoji_Captcha_Solver

This captcha solver has been developed using deep learning and convolutional neural networks along with the help of OpenCv for letter segmentation. It can be used to recognize captchas consisting of different letters as well as emoji. The model was trained on Google Colab using the hand drawn dataset in the form of a csv file. The model was trained to achieve a validation accuracy of 97% and a test accuracy of 98%.

#   Special Features of The Model

1. This model can recognize captchas consisting of letters and numbers rotated at a max. angle of 30 deg.
2. Can detect captchas having letters and emoji of variable thickness and size.

# Characters

The characters on which the model was trained are given in the file characters.txt.
To decode captchas you need to input the image paths in the decode_captchas.py file and run the file. The python libraries required for this are mentioned in the requirements.txt file. The csv file on which the model was trained is also available. A few sample captchas have also been provided in the sample captchas folder.
