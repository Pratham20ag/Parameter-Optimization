## Parameter-Optimization
Exploring Different Methods for Estimating Parameters for a Machine Learning Model.

#### 1. Using 100 sets of Random Parameters for a Support Vector Machine and Finding the Best Parameter Set for the specific DataSet
    Steps
         1. Divide the Dataset into 10 Equal Sized Samples with 2000 rows each.
         2. Using the random Library generate 100 random sets of Parameters used in an SVM(i.e. Kernerl, epsilon, and nu).
         2. Initializing an SVM for the parameters and each sample and calculating the accuracy of the machine.
         3. Iteratively compare accuracy to find the Set of parameters with the Best Accuracy for each sample.
         
    DataSet Used - 
    
    Dry Bean. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C50S4B.
---
The Results are As Follows :
| Sample_No. | Best Accuracy | Epsilon  | Nu       | Kernel |
|------------|---------------|----------|----------|--------|                           
| 1          | 0.920000      | 0.947903 | 0.126627 | sigmoid|
| 2          | 0.916667      | 0.873418 | 0.170332 | sigmoid|
| 3          | 0.926667      | 0.058894 | 0.127191 | poly   |
| 4          | 0.933333      | 0.200512 | 0.202831 | sigmoid|
| 5          | 0.910000      | 0.559005 | 0.111917 | sigmoid|
| 6          | 0.948333      | 0.300074 | 0.083273 | sigmoid|
| 7          | 0.928333      | 0.777512 | 0.139235 | rbf    |
| 8          | 0.925000      | 0.436616 | 0.189995 | sigmoid|
| 9          | 0.943333      | 0.256725 | 0.085982 | linear |
| 10         | 0.908333      | 0.055472 | 0.210726 | rbf    |

Convergence Graph for Best Sample with best Accuracy.

![image](https://github.com/Pratham20ag/Parameter-Optimization/assets/124654924/a8019522-5378-4740-b4f0-432b311d2b2e)



---
#### 2. Using the Least Sum of Square Method to find the best weights for a Linear Model.

Formula Used

![image](https://github.com/Pratham20ag/Parameter-Optimization/assets/124654924/c6f72a4d-27bf-43aa-ad50-67a846fa41ca)



Features and target values used


![image](https://github.com/Pratham20ag/Parameter-Optimization/assets/124654924/82df8a89-5005-431e-a63f-3b60540c7a2f)




