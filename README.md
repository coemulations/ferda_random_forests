# Random Forests by Team FERDA
In this lesson, students will learn about Random Forests and their implementation by helping Jones, a collector of High MPG Vehicles. The notes, slides and assignment will first provide a recap on decision trees. In doing so, the formulae behind Gini Entropy and Information Gain will be covered. 

In helping Jones in the coding assignment, students will have to modify and clean the incoming dataset. This assignment uses the file 'auto-mpg.csv' which contains a few features of information on cars, including metrics such as weight, engine displacement, and model year. The file also contains the fuel efficiency of each car in miles per gallon. Students will modify this column to be categorical, putting the range of MPGs into various buckets which are helpful for Jones' to interpret.

Once the data is fully prepared for the models, students will learn how to utilize sklearn's DecisionTreeClassifer and RandomForestsClassifier by comparing efficacy of a Decision Tree compared to a Random Forest on the cars dataset. An introduction to these classifiers as well a link to the scikit-learn user guide are given in the notes to provide an introduction to and facilitate usage and understand of the scikit-learn library for industry and research purposes.

The disadvantages of decision trees are covered in the notes, and students will see the advantages of Random Forests over Decision trees in the models created in the coding asssignment. 

A deeper understanding of the nature of Random Forests is facilitated in programming questions which have the students examine how the random nature of Random Forests manifests itself in the results of the models.

Lastly, students will understand visually how a random forest makes splits on the dataset by examining the splits made by a single tree. They will have to effectively verbalize the findings of the tree in a few short answer questions at the end of the assignment.

Listed in bullet points for ease:
- Structure and Intuition behind Decision Trees.
- Entropy vs. Gini Impurity.
- Disadvantages of Decision Trees and how Random Forests can fix them.
- How to use Random Forests for an industry classification task.
- Using Decision Tree and Random Forest visualization to understand what splits are made to classify datapoints.
- Reporting information on splits in an efficient manner.

## Files:
- **Random_Forests_Slides.pdf** Assignment Slides
- **Random_Forests.pdf** Assignment Notes
- **Random_Forests.ipnyb:** Jupyter Notebook of assignment
- **Random_Forests_Solutions.ipnyb:** Jupyter Notebook of assignment with solutions
- **auto-mpg.csv:** Car MPG and features dataset to be used in Random_Features.ipnyb
