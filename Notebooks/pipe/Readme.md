Set start and end date in 'config.py', else it will default to 2023-01-01 to 2023-12-31.

Assumes a WoogleDump is in the folder 'WoogleDumps'
Copy over 'LoadWoogleDump.ipynb' into the WoogleDumps folder as to not build a dataset with all instances, but just the ministries.

Assumes the model 'nl_besluit_gescheiden_lg' is in the folder spacy_models.  
Download from: https://drive.google.com/drive/folders/1AzG_0rQbi4SYRyxSno41R8wCUszkRG-r?usp=drive_link

ExtractWoobesluitenFromWoogleDump is made by my thesis supervisor, Maarten Marx.  
To do:
More meaningful and clear plots in CleanExplore  
Write a better readme