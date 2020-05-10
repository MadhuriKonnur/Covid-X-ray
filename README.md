# Covid-X-ray
Classification  of COVID-19 chest x-ray  .




Dataset Details
-------------------------
Extracting  our data samples  following links

Covid X-Ray Image Dataset - https://github.com/ieee8023/covid-chestxray-dataset           for positive cases.
(regularly this set is upadated with fresh covid x-ray)

Kaggle X-Ray Chest Images - https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
for negative cases.
(Taking the samples of normal x-ray)


File Details
-------------------------
DataSet Creator.ipynb - Gives "Dataset" folder  with  "Covid"  and  "Normal"  image  folders (with 145 images each)
                      -

test_train.ipynb -  splits  train and val data from "Dataset" folder and stores in "output" folder using split_folders.
                 -

for example
output/

train/

    class1/

        img1.jpg
        ...
    class2/
        imga.jpg
        ...



val/
    class1/
        img2.jpg
        ...
    class2/
        imgb.jpg
        ...
 
 MK_CNN_Covid_model.ipynb - Process  of  CNN model  using  keras. Details  of  all layer  and  obtaining  model to predict.
                          -
                          -  with  saved  model "model_mk.h5"
                          -
                           
