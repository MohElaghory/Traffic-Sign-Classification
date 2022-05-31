# Traffic Sign Classification  🚦🚗

## Image Scraping & Classification Using CNN

________

We'll Scraping the 5 categories of traffic signs from google then save each one in folder, then build a CNN using Keras to use it classifying these five categories.

### **About Dataset**

#### **Context**
The dataset contains less than 1000 images of five types of traffic signs. It is further classified into 5 different classes. The dataset is high varying, some of the classes have many images while some classes have few images. 

#### **Content**
**Note**   The Accuracy is not good due to lack of data, but just here I want to proof of concept, not more.

{ 'stop trafic sign' -> 0,

'road narrows on both sides sign'    --> 1,

'two-way traffic sign'   --> 2,

'roundabout sign'  --> 3,

'no pedestrians sign'       --> 4}

_____

### Test Acc after Augmentation : **`60 %`**

![download (1)](https://user-images.githubusercontent.com/44786324/171248211-d15585a7-4a40-4c0f-a712-80c5497c57a0.png)

![download](https://user-images.githubusercontent.com/44786324/171247213-db428e48-6ab1-4f22-b171-b764b72ad655.png)



