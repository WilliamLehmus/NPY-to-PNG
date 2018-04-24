# NPY-to-PNG


What it does: It extracts and converts the datasets contained in .npy files to .png format. You can find googles .npy dataset for Google Doodle at https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/numpy_bitmap

Why do this?: Many people (like me) don't use Python for neural networks but prefer other languages. There are not many options for using .npy files outside python that´s why I created this program to extract them into png files keeping the original size intact (28x28 pixels).

How to use: You need the free IDE Processing 3x you can download it from processing.org. Open the file in processing. Set the path to the npy dataset and the name of the output folder and hit the play button in the upper left corner. A subfolder to the sketch folder (where this file is saved) will be created with all the images from the dataset will be labeled 0.png, 1.png and so forth.

Make sure to use forward slashes in path / to dataset

Let me know if you have any issues or need help with this tool. //William Lehmus
