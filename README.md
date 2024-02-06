# ondraaglijk-matglas
The code used in my thesis can be found here.

In pipe, the full pipeline is stored, which can be executed from `Main_pipe`.
A smaller dataset is used in this repo, as the github file size constraints do not allow files over 100MB.
If you want to try it out with the full dataset, make an issue to ask me.

In `Experimenten` some standalone notebooks can be found for:
1. Classifying the decision ([Training](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/Besluit_Training.ipynb), [Testing](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/Besluit-SpacyTest.ipynb))
2. Creation of graphs ([CleanExplore](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/CleanExplore-foi_decisionDate.ipynb), [CompDia](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/CompDiaExcelData-foi_decisionDate.ipynb))
3. Converting multiple excel files to one dataframe ([ExcelToDF](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/ExcelToDF.ipynb)
4. Manual explorations ([Manual vs automatic](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/Handmatig%20vs%20spacy.ipynb), [Manual](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/HandmatigsSpreadsheet.ipynb), [MinFin](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/MinFin-Verschil.ipynb))
5. Statistics comparing automatic lead times against manual data ([Statistics](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/Statistiek-foi_decisionDate.ipynb))
6. Combining found data with manual data where automatic dates could not be found ([Join](https://github.com/JoranIK/ondraaglijk-matglas/blob/main/Notebooks/Experimenten/JoinHandmatig.ipynb))

A quick view of the distributions of automatic lead times and the ground truth:

![matglas_alles_en_automatisch](https://github.com/JoranIK/ondraaglijk-matglas/assets/54799309/cd3bec78-7b73-41d5-b3e3-a9748ccdb133)

A quick view of lead times over the years:

![comb](https://github.com/JoranIK/ondraaglijk-matglas/assets/54799309/89e142e7-6806-4447-89a1-a080a6ed174f)


An example of the way some dates were noted in the documents:

![dagtekeningen](https://github.com/JoranIK/ondraaglijk-matglas/assets/54799309/2171f397-fb87-4f4a-90b5-8a0cdf600903)


