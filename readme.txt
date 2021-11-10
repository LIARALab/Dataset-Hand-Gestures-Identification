##########################
#Alex Roberge, 2021-11-09#
##########################

Here are folders containing the datasets collected for hand gestures Identification for fine-grained human activity recognition in smart homes. 

The nomenclature of files is like so:

LOO = leave one out
LH, RH = left hand, right hand

Here is a description for each of folder:
->Classification_Results: contains the results of the classification process presented in the paper.
->Filtered_Data: Data that passed the feature extraction program. This data is ready to use with a classification model.
->Filtered_Data_LOO: like Filtered_Data but taking a leave-one-out approach. See the other readme in this folder for more information.
->Raw_And_Annotated_Data: contains the original signal data and annotated data (with tag), without the feature extraction process.  Note that, originally, the process was done in French, so the file names are according to this language. This doesn’t affect the tags in the annotated files (the ones ending with _O), as they were in English from the beginning. Here is a word-to-word translation of the gestures’ name in the files to the tags:

MD = Right hand
MG = Left hand
Boire = Drink
Canne = Can
Casser = break(*egg)
Couper = Cut
Fouetter = Whip
Marcher = Walk
Mélanger = Mix
Râper = Grate
Rouler = Roll
Saler = Salt
Tourner = Flip
Verser = Pour
