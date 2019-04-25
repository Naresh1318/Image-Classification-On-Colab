# Image-Classification-On-Colab

This repo is designed to be as easy as possible for instructors to teach how transfer learning works using a hands on example
without installing a single piece of software. The students will get to use keras (with TensorFlow backend) along with GPUs to 
classify different dog breeds.

## You'll still need these things for all the participants though:

1. A web browser preferably chrome
2. Google account
3. And an internet connection 

## Get the dataset

Colab will need to access the [dog breed dataset](https://www.kaggle.com/c/dog-breed-identification). It does this by using a 
copy of the dataset from you google drive account. So, you'll first have to copy over the zip file to your google drive home 
directory.

1. Get the zip file from [this](https://drive.google.com/file/d/1DefmP6vP-2_4RSjusmcIIg3MupWsvbpw/view?usp=sharing) link and add a copy of it to your dive (Hit make a copy).
2. Ensure that the zip file is renamed to `dogbreed.zip` from `Copy of dogbreed.zip` 
and that the zip file is in the home directory (not in any directory).
3. Now open <a href="https://colab.research.google.com/drive/1m16G_WBcpdIpAAq8a7F1znffeQM6Esn1" rel="some text"><img src="https://cdn-images-1.medium.com/max/883/1*g_x1-5iYRn-SmdVucceiWw.png" width=10%></a>.
4. On Colab: Hit the Runtime menu -> Change runtime type -> Hardware Acceleration -> GPU.
5. Now run through the cells on Colab.


## Credits

* https://github.com/floydhub/image-classification-template : I took their code and modified it to work on Colab.
* This repo was originally designed for NEUR 4984: The Artificial Brain at Virginia Tech
