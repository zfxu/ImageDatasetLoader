# ImageDatasetLoader

Function to extract data from images to numpy array.
If the dataset images havn't got the same shape it will be resized.
This numpy array will have the shape (num_samples, width, height, channels).
The numpy array data will be stored to npy files for later on, fast read-in data.
The dataset has to be stored one class per sub-folder in the given file_dir.
The values are in [0, 255] ant the targets are the class nums.

## Modules:

  - NumPy
  - OpenCV-Python
  - Matplotlib