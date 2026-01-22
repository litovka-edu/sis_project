# sis_project
A project assignment with a semantic image segmentation U-net model

To get the original dataset please use this link: https://datasetninja.com/ade20k

After loading, put folders training and validation in folder "dataset2" 

Before running the model, there is a preprocessing part with resizing the dataset and getting mask from annotations, to run this, please use code provided in "dataset_preprocess.ipynb"

Model itself is located in file "model.ipynb"

U-net model properties:
- Total params: 7,772,302 (29.65 MB)
- Trainable params: 7,766,414 
- Non-trainable params: 5,888 
