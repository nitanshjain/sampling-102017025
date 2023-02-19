# sampling-102017025

UCS654 Assignment
Nitansh Jain
102017025

#### Required Task
1. Download Dataset
2. Convert this data-set into balanced class data-set.
3. Create five samples.
4. Apply  five  different  sampling  techniques  (Sampling1, Sampling2, Sampling3, Sampling4, Sampling5) on five different ML models (M1, M2, M3, M4 and M5)
5. Determine Best model which provides best accuracy for which sample

#### Balancing Dataset
Used SMOTEENN to balanced the dataset. It uses a mixture of oversampling and undersampling.

#### Sampling Technique Used
1. Simple Random Sampling
2. Systematic Sampling
3. Stratified Sampling
4. Cluster Sampling

#### Models Used
1. KNN - K Nearest Neighbor
2. LR - Logistic Regression
3. SVC - Support Vector Classifier
4. RFC - Random Forest Classifier
5. DT - Decision Tree Classifier

#### Performace Evaluation:
The cross validation results for the different samples with different models are mentioned below.
|      | Random | Systematic | Stratified | Cluster |
|------|--------|------------|---------|------------|
| KNN  | 0.960  | 0.970      | 0.940   | 0.950      |
| LR   | 0.930  | 0.970      | 0.970   | 0.970      |
| SVC  | 0.950  | 0.940      | 0.960   | 0.970      |
| RFC  | 1.000  | 1.000      | 1.000   | 1.000      |
| DT   | 0.980  | 0.980      | 1.000   | 0.920      |

Random Forest Classifier showed best accuracy for all the sampling techniques.
Stratified Sampling Technique is the best technique in this case but only marginally
