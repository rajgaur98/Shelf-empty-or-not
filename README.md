# Shelf-empty-or-not

I have used TensorFlow for designing the model and training on the data.
First I manually distributed the data to empty and non empty folders.
Then divided this dataset into training and validation set.
Please use the correct path on your machine wherever I have included the path for folders.
The images were divided as follows:
  196 -> training images
  24 -> validation images
After running 20 epochs, the model achieved 98% accuracy on training data and 79.17% accuracy on validation data.


For extracting text from images, I have used pytesseract python library.
It did extract text from the image but I am not able to seperate the product name from other text and everything is jumbled up.
Therefore, I didn't move any further.

To run this project do the steps above, i.e. manually distribute data into empty or not-empty folders, and give correct paths for the same.

Use jupyter notebook to launch the python file.

