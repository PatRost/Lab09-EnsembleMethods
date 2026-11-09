
# Lab 09 – Ensemble Methods
## Group 4 – ITAI 1371
### Individual Contribution Journal

---

## Member 1: Patrick Rostand Gandjouon Tchassem

### My Contribution

For this lab, I worked on the Google Colab notebook by helping with the code implementation and testing the models. I worked with the Iris dataset, trained the Decision Tree and Random Forest models, and checked their accuracy results.

I also worked on the feature importance graph to identify which flower measurements were most important for making predictions. After running the code, I reviewed the outputs and helped answer the Knowledge Check questions based on our results.

I also helped organize the lab notebook and make sure the code, explanations, and outputs were clearly presented for submission.

---

## Member 2: Saimi Manasiya

I contributed to this lab by completing the practical activities and following each step to build, train, and evaluate the machine learning models. First, I loaded the Iris dataset using Python libraries and divided the data into training and testing sets. I then created and trained a single Decision Tree model and used the testing data to make predictions. After calculating its accuracy, I observed that the Decision Tree achieved 100% accuracy.

Next, I created a Random Forest model using 100 decision trees and trained it using the same training dataset. I made predictions using the test data and compared the results with the single Decision Tree model. The Random Forest also achieved 100% accuracy, which allowed me to understand the similarities in the performance of both models.

I also completed the feature importance activity by extracting the importance values from the Random Forest model and creating a bar chart to display the results. This helped me identify which features played the biggest role in classifying the Iris flower species. Finally, I completed the knowledge check questions by reviewing the results and explaining my understanding of ensemble methods, model performance, and important features. Through my contribution to this lab, I gained practical experience with Python, machine learning algorithms, model evaluation, and data visualization.


---

## Member 3: Kenneth Kouokam

My part of Lab 09 is explaining the tie between the Decision Tree and the Random Forest. Saimi
reported 100% accuracy for both models. The notebook sets aside 30% of the 150 Iris flowers for
testing, which gives 45 test flowers and leaves 105 for training. On that split, the reported scores
mean that each model correctly classified all 45 test flowers. Neither model had an advantage in the
number of correct predictions.

My interpretation also puts that result in perspective. If either model had missed just one flower, its
accuracy would have been 44 out of 45, or about 97.8%. With so few test examples, I would describe
the result as a tie on this particular split. To find out whether the forest gives more consistent
predictions, I would compare both models across the same additional splits and look at how much
their scores change.


---

## Member 4: Anavictoria Cavazos

My contribution to this assignment in part has to do with explaining how a random forest makes a prediction. The way that it functions in 
Module 9 with the iris dataset is that when a random forest is in use, it goes with the majority vote. For instance, with the 100 
different trees, if a random new iris was input and 70 out of the 100 trees classify it as a specific species and then the other 30 as a 
different species. The result or final prediction would be what the 70 predict it to be because it is the majority prediction, so the 30 
are not taken into consideration when the prediction happens; that error is sort of looked over or passed by. 



---

## Member 5: Hashim Sayed Hoosini

Because of my work schedule, I wasn't able to join my team members for synchronous group sessions. However, I kept up active and consistent communication with everyone through our GroupMe chat to stay on top of the team's directions, share progress updates, and make sure we were all aligned on our final submission requirements. Working this way allowed me to contribute meaningfully on my own timeline while ensuring my work stayed perfectly in sync with the group's objective.


To make sure I fully understood the material, I worked through and executed this entire Colab notebook independently. During this process, I hit some resource limit issues where Colab wouldn't let me connect to a backend. I spent time troubleshooting the runtime environment on my own, clearing up the connection, and eventually got every single cell to run perfectly. Doing this hands-on debugging, checking each block of code, and analyzing how the ensemble methods work on my own time really helped me master the material and successfully contribute my individual workflow to the group.




---
