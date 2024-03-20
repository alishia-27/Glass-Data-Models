# Glass-Data-Models
I applied three different models for this glass dataset, based on chemical composition: Random Forest Classifier, Support Vector Machine (SVM), and KNN. Other techniques applicable to this problem include Decision Trees, Gradient Boosting Machines, and Neural Networks.
In this project I looked at the Random Forest, SVM, and KNN models on the original, oversampled, and under sampled datasets. Focusing on their accuracy, precision, recall, and f1-score across all the data sampling techniques.

Model Analysis:

Original Models:

•	Random Forest shows good performance with an accuracy of 77%, and strong results in precision and recall for most classes.

•	SVM has an accuracy of 71%, with decent precision and recall, but it struggles with class 3.

•	KNN shows an accuracy of 65%, with mixed results across different metrics and classes.

 
Oversampled Models:

•	Random Forest has an accuracy of 72%. Oversampling improved the recall for minority classes (class 3), but overall accuracy slightly decreased compared to the original dataset.

•	SVM shows an accuracy of 65%, with some improvement in recall for minority classes but a decrease in overall accuracy.

•	KNN has an accuracy of 68%, showing a slight improvement in handling minority classes but a slight drop in overall accuracy compared to the original data.

 
Under sampled Models:

•	Random Forest presents an accuracy of 62%. The model's ability to identify minority classes improved at the cost of overall accuracy.

•	SVM has an accuracy of 55%, with notable improvements in identifying minority classes but a significant drop in overall performance.

•	KNN shows an accuracy of 58%, with enhanced recall for minority classes but reduced overall accuracy.

 
Best Model:

Random Forest consistently shows good performance across different sampling techniques, balancing well between accuracy and recall for minority classes. SVM and KNN show variability in their performance, with some gains in minority class recognition at the expense of overall accuracy.
 


Conclusion:

Random Forest on the original dataset shows as the most balanced model. This provides a good trade-off between overall accuracy and class-specific performance. While oversampling and under sampling helped improve minority class recognition for all models, this often came at the cost of reduced overall accuracy. Considering the balance between accuracy, precision, recall, and f1-score, the Random Forest model trained on the original dataset would be the recommended choice for this classification task. It provides great performance without the need for complex data resampling strategies.
 
In summary, while data resampling techniques can help in addressing class imbalance, they may not always lead to better overall model performance. The choice of model and data sampling strategy should be tailored to the specific requirements of the classification task, emphasizing the importance of balance between overall accuracy and the ability to recognize minority classes.
