First, the list of words that will form the basis for the data dictionary is created. To do this, cell #01 of the analyze judgment from Excel.ipynb file is executed. This list of words will be the historical cloud of words commonly used in extortion sentences.

Second, the data dictionary is generated based on the list generated in the previous cell by executing Cell #02. This algorithm classifies words of the demand type and words of the threat type. This analysis is based on a database of words entered initially.

Third, in cell #03, the algorithm classifies the sentences entered based on the dictionary created previously. There are four classes.

Fourth, in Cell #04, non-extortionate sentences are added to the database to run the classification algorithm and test whether it also detects the non-extortionate category.

Fifth, cell #05 obtains the confusion matrix.

Sixth, cell #06 is the algorithm for making morphological corrections to the sentences and then entering them into the database called datav2.xlsx. 