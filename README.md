# NLP-Project

CONTRIBUTIONS: \
Caleb:  Worked on the distilBERT model. This included getting the baseline and making sure that new datasets can be trained on the model. This code can be found in the distilBERT folder 

Ananya: Worked on the T5-Model. This included getting the baseline and making sure that new datasets can be trained on the model. Along with this, created the code to generate the first half dataset. This code can be found in the T5 Colab notebook 

Luke: Helped in getting the enviornments set up for the T5 model and testing with a potential google cloud bucket that could have been used to create better efficiency for training. 

Brennan: Helped in getting the enviornments set up for the T5 model and testing with a potential google cloud bucket that could have been used to create better efficiency for training. 

Lukas: Created the synonym replacement, entity swapped, and prompting datasets. The code for the synonym and prompting can be found in the T5 Colab notebook.

FOR TRAINING DISTILBERT:

In the Drive linked at the bottom there is a zipped file called content. It has to be extracted and be in distilBERT training directory. After it has been unzipped and is in the distilBERT folder, remove the zip file. Inside the distilBERT folder is the python notebook for training distilbert.

FOR TRAINING T5-SMALL:

In the Drive linked at the bottom there are two datasets that need to be downloaded and uploaded to the content page on COLAB. These are the train-v2.0.json and modified_squad_data.json. Once the datasets are uploaded, run all cells. We used Colab for the T5 model, it is recommended to run this on Colab. If you decide to run it locally then make sure that the routes for the datasets are changed and correct. The routes needed to be changed are found when it calls json.open. 

DISTILBERT F1 SCORES: \
Baseline: 81.33 \
Entity Swapping: 80.13 \
Synonym Replacement: 78.92 \
Prompting: 83 \
First Half: 82.488 \
\
T5-SMALL F1 SCORES: \
Baseline: 15 \
Entity Swapping: 13 \
Synonym Replacement: 11 \
Prompting: 14 \
First Half: 9 \
\
\
Drive link for the squad datasets needed: https://drive.google.com/drive/folders/1nHwPSEe3PEStd3fOqcnSvkWGDWJLILVl?usp=drive_link
