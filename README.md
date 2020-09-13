# refactoring-dataset
This dataset has information about .java classes before and after refactoring applications.

This dataset is composed of five .csv files. All files have 26052 rows where the first row is the header and the next 26051 are classes which are in the same order in all the files. Each file and columns and explained next.

##number_refactorings_by_class
It gives the number of refactoring operations a class has played as an actor.

EM (Extract Method) - A method was extracted from this class.
MMT (Move Method Target Class) - A method was moved from this class.
MMS (Move Method Source Class) - A method was moved to this class.
