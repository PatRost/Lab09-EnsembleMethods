
# Lab 09 – Ensemble Methods
## Group 4 – ITAI 1371
### Reflection Journal

---

## Member 1: Patrick Rostand Gandjouon Tchassem

In this lab, I learned how ensemble methods work and why using multiple models can sometimes give better results than using just one. Before this lab, I thought that using more models would always improve accuracy, but I realized that is not always the case.

We used the Iris dataset to train a Decision Tree and a Random Forest with 100 trees. What surprised me the most was that both models achieved 100% accuracy. I expected the Random Forest to perform better because it combines predictions from many trees. This helped me understand that a more complex model does not always produce better results, especially when the dataset is simple.

Another interesting part was the feature importance graph. I learned that petal width and petal length were the most important features for identifying the flowers. This helped me see how machine learning models use different features to make predictions.

Overall, this lab helped me better understand the difference between a single Decision Tree and a Random Forest. I also learned the importance of comparing model results instead of assuming that one model will always perform better.

---

## Member 2: Saimi Manasiya

Through this lab, I gained a better understanding of ensemble methods and how they are used in machine learning to improve prediction results. I learned that instead of depending on a single model, ensemble methods combine multiple models to make a final prediction. This approach is based on the idea of the “wisdom of the crowd,” where different models work together to produce more reliable results. I also learned about two important techniques, Bagging and Boosting, and how they help improve model performance.

During this lab, I worked with the Iris dataset and trained two different machine learning models: a single Decision Tree and a Random Forest. I found it interesting that both models achieved 100% accuracy on the test data. Initially, I expected the Random Forest to perform better because it combines multiple Decision Trees. However, both models produced the same accuracy. This helped me understand that using a more complex model does not always guarantee better results, especially when working with a simple dataset.

Another important part of this lab was learning about feature importance. I used the Random Forest model to identify which features were most important for classifying Iris flowers. From the results, I found that petal width and petal length were the two most important features. This helped me understand how machine learning models identify patterns in data and use important features to make predictions. Overall, this lab improved my knowledge of machine learning, model comparison, prediction accuracy, and data visualization. It also helped me understand how combining multiple models can make predictions more reliable.



---

## Member 3: Kenneth Kouokam

The part of this lab that interests me most is that adding 99 more trees did not change the reported
accuracy. At first glance, that result makes a forest of 100 trees seem unnecessary. Counting the test
flowers gives me a better explanation: the single tree already got all 45 right. Even if the forest
learned different rules, there was no mistake left for it to correct on this test set.

Thinking about one flower makes the percentage easier for me to interpret. One wrong prediction
would move the score from 100% to about 97.8%. Those numbers look different in a table, but the
difference is a single flower. Now, when I see a percentage, I want to know how many examples it
represents. I would be more interested in which flower was misclassified and whether its
measurements resembled another species than in the percentage alone.

The tie also helps me connect ensemble methods to the bias-variance lab. A single tree can learn
different rules when its training examples change. A forest combines trees trained with some
randomness, so one unusual tree has less influence on the final prediction. That possible benefit is
about consistency. Two models can agree on every flower in one test set without being equally
sensitive to a change in the training data.

If I were extending this comparison, I would use the same cross-validation folds for both models. That
way, whenever I compared two scores, both models would have faced the same flowers. I would look
at their average accuracy and whether one model had a particularly weak fold. The question I would
take into that experiment is whether the forest stays reliable on the cases that challenge a single tree.
The current result gives me a reason to ask that question, but it does not answer it.


---

## Member 4: Anavictoria Cavazos

 After completing lab 09 this week, I learned more about how a random forest works and how it compares to using a decision tree. In this 
 particular dataset of iris, the random forest and the decision tree both appeared to give the same accuracy of 100%. This didn't give a 
 chance to explore how a decision tree compares to a forest tree entirely, but I understand that, in most cases, a forest tree is 
 expected to perform better than a decision tree. However, now I see how that strongly depends on the dataset provided. In this case, the 
 iris dataset is quite simple, but in other cases, with more complex data, it is possible that a difference would be clearly shown 
 between these two models. 

My prior idea when working on this lab was the idea that a forest tree is a better use than a decision tree. A forest tree has multiple 
trees, each having something different from the data; it allows better and more similar predictions to the other trees, and it is like a 
team effort. Since a decision tree is just one that likely will stick to what the specific data is shown or imputed, it can create a 
problem when new data is put in that it has never seen, because it does not know how to properly process it and  perform as well as a 
forest tree would or is expected to. 

Now, reflecting on this prior idea, I see that it does not always apply and how this sometimes happens when working with models and data. 
Sometimes what you expect to work better with your data ends up not being the best or ends up being just as good as another model, 
because it is about knowing and testing, working with your data to its accommodations, and being flexible about what works best with the 
data. 



---

## Member 5: [Member Name]

### Personal Reflection



---
