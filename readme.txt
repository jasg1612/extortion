The datav2.xlsx file contains the knowledge base on which the algorithm has been validated to detect whether a sentence is extortionate. 

First, the list of words that will form the basis of the data dictionary is created. To do this, cell no. 01 of the judgment analysis in the Excel.ipynb file is executed. This list of words will be the historical cloud of words commonly used in extortion sentences.

Second, the data dictionary is generated based on the list generated in the previous cell by executing cell #02. This algorithm classifies words of the “demand” type and words of the “threat” type. This analysis is based on a database of words initially entered.

Third, in cell #03, the algorithm classifies the phrases entered based on the dictionary created above. There are four classes.

Fourth, in cell #04, the confusion matrix is obtained, where the algorithm's prediction is compared with the actual nature of the sentence (extortionate, non-extortionate).

Fifth, cell no. 05 is the algorithm for making morphological corrections to the sentences and then entering them into the database called datav2.xlsx. 

