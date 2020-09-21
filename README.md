# Mask-Detection-System-Tensorflow
### Colab version.
If you don't have gpu no problem I too don't have one. But google is at the rescue, Google colab is where they offer free GPU access and my project has been completely done in google colab. 

We all have felt the pressure that Covid-19 has exerted on our physical, economical and daily life. One of the main precautions that we had to mantain was wearing mask. So i was like why not build a system which can detect masks!!.

**Implementation**
  - Countries where masks are mandetory to wear
  - Offices that are functional during this pandemic

**Requirements**
  - [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)
  
Go to `File` **->** `New notebook`. You must enable GPU to speed up the process.

To enable GPU go to `Runtime` **->** `Change runtime type` select `gpu` and click on `SAVE` and you are good to go.

# Dataset
The credit for the dataset goes to this [Repo](https://github.com/chandrikadeb7/Face-Mask-Detection)


Use your power-shell to clone the repo
```Code
git clone https://github.com/chandrikadeb7/Face-Mask-Detection.git
```
Open the file and go to the dataset folder and do the following:
  - Make 2 folders, `train` , `val`
  - Inside train folder make more two folder's `with_mask`, `without_mask` do the same with folder `val`
  - Inside dataset folder you will see two folder name `with_mask`, `without_mask`
  - take 450 images from `with_mask` folder and **Cut Paste** it inside `val`,`with_mask` and the rest of the images in `train`,`with_mask`
  - take 450 images form `without_mask` folder and **Cut Paste** it inside `val`,`without_mask` and the rest of the images in `train`,`without_mask
  
its upto you how yoy devide the images, Most preffered way is to keep **80% of dataset** in training  and **20% of dataset** in validation/test.
Now in your dataset folder there must be 4 folder `train`, `val`, `with_mask`**(empty)**, `without_mask`**(empty)**. Delete the empty folders.

**UPLOAD THE DATASET FOLDER TO YOUR GOOGLE DRIVE**
