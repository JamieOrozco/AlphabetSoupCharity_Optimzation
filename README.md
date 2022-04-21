# AlphabetSoupCharity_Optimzation

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 
Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

The features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

### Deliverable 1: Preprocessing Data for a Neural Network Model
Preprocessed the dataset in order to compile, train, and evaluate the neural network model

<img width="230" alt="preprocessing" src="https://user-images.githubusercontent.com/95591222/164358494-915f3da1-c915-44aa-a303-0d5f5fe9a4c7.png">
<img width="130" alt="columns" src="https://user-images.githubusercontent.com/95591222/164358547-450ae3f5-ccc8-4269-ab0e-2257011802df.png">
<img width="239" alt="Density Plot" src="https://user-images.githubusercontent.com/95591222/164358557-2852f54f-2a32-4800-96d0-97e3e0dd8f5c.png">


### Deliverable 2: Compile, Train, and Evaluate the Model

<img width="285" alt="Number of Layers" src="https://user-images.githubusercontent.com/95591222/164358586-e530d465-7c2b-4ee6-8d85-7a811be8f88d.png">
<img width="649" alt="Merged Data" src="https://user-images.githubusercontent.com/95591222/164358616-7130f19d-0343-45a5-9519-3992d9ed0328.png">




### Deliverable 3: Optimize the Model

<img width="382" alt="image" src="https://user-images.githubusercontent.com/95591222/164358721-42168cae-edf5-4369-8f5a-9101a20a9d20.png">
<img width="384" alt="image" src="https://user-images.githubusercontent.com/95591222/164358771-e719fe12-a872-479f-a4fa-9df0435630a9.png">




### Deliverable 4: Neural Network Model Conclusion

<img width="340" alt="image" src="https://user-images.githubusercontent.com/95591222/164356885-4bc99e9c-adf1-4048-ae06-6bf847c9578e.png">

Data Preprocessing
* What variable(s) are considered the target(s) for your model?
     * The target is the IS_SUCCESSFUL field. 
* What variable(s) are considered to be the features for your model?
     * APPLICATION_TYPE
     * AFFILIATION
     * CLASSIFICATION
     *	USE_CASE
     *	ORGANIZATION
     *	STATUS
     *	INCOME_AMT
     *	SPECIAL_CONSIDERATIONS
     *	ASK_AMT
      
* What variable(s) are neither targets nor features, and should be removed from the input data?
    * EIN and NAME should be removed
    
Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
       * 80, 30 and Relu Activation funtions because more layers decreased accuracy

* Were you able to achieve the target model performance?
    * Target model performance was not achieved 
    
* What steps did you take to try and increase model performance?
    * Increased the number or neurons, and layers
    * I would recommeded another classifier
