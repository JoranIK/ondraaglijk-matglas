Run 'Main_pipe' to execute all notebooks in order, the final dataset will be saved in 'data/minfinal.pkl.gz'
CleanExplore displays the results, the graphs will also be in the Main output.

Set start and end date in 'config.py', else it will default to 2023-01-01 to 2023-12-31.

Due to filesize constraints, a smaller dataset containing only 2023 data is included.  

If a full dataset is present, uncomment the first notebook in Main_pipe, it will assume a WoogleDump is in the folder 'WoogleDumps'.

Assumes the model 'nl_besluit_gescheiden_lg' is in the folder spacy_models.  
Download from: https://drive.google.com/drive/folders/1AzG_0rQbi4SYRyxSno41R8wCUszkRG-r?usp=drive_link

ExtractWoobesluitenFromWoogleDump is made by my thesis supervisor, Maarten Marx.  
