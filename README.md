# Casava

Deep learning model to detect and identify 4 type of disease based of the cassava image.
I don't own the dataset, dataset taken from: https://www.kaggle.com/datasets/mexwell/crop-diseases-classification/data

The disease is:
1. "Cassava Bacterial Blight (CBB)"
2. "Cassava Brown Streak Disease (CBSD)"
3. "Cassava Green Mottle (CGM)"
4. "Cassava Mosaic Disease (CMD)"


Not only the disease images is available, the healthy plant images also available. Making the dataset consisting of 5 classses.
In CSV file it is noted that there are more than 20.000 samples, but in reality there is only about 17.000 images.
The "Cassava_Sorting_Data.ipynb" is used to separate the class into different folder, resulting in this folder structure:
`![image](https://github.com/Ihsan1331/Casava/assets/126314042/53a6206b-7f2a-471f-949a-5f7d237b948f)

This structure resulted in easier load the dataset into tensorflow flow from directory. The distribution of class is not balance with the Bacterial Blight disease is the smallest amount of sample only about 1.000 while Mosaic disease held the largest amount of sample about 11.000 samples.
