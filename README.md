# Semantic Segmentation
### Parameters
```
epochs = 45
batch_size = 5
learning_rate = 0.0008
keep_prob = 0.5
```

### Learning process
Loss is decreasing during learning process. For example lets take a look on 5th/45 epoch run:
```
Epoch: 5
Loss: = 0.333
Loss: = 0.316
Loss: = 0.305
...
Loss: = 0.264
Loss: = 0.254
Loss: = 0.280
```

### Finding correct part of image:
![alt example_image](./output/final_run/um_000000.png)

![alt example_image](./output/final_run/um_000024.png)

![alt example_image](./output/final_run/umm_000026.png)

![alt example_image](./output/final_run/umm_000061.png)

![alt example_image](./output/final_run/uu_000075.png)

![alt example_image](./output/final_run/uu_000098.png)


### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Implement
Implement the code in the `main.py` module indicated by the "TODO" comments.
The comments indicated with "OPTIONAL" tag are not required to complete.
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission
1. Ensure you've passed all the unit tests.
2. Ensure you pass all points on [the rubric](https://review.udacity.com/#!/rubrics/989/view).
3. Submit the following in a zip file.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder  (**all images from the most recent run**)

 ## How to write a README
A well written README file can enhance your project and portfolio.  Develop your abilities to create professional README files by completing [this free course](https://www.udacity.com/course/writing-readmes--ud777).
