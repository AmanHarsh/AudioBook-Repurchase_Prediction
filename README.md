# AudioBook-Repurchase_Prediction

Problem-Statement: 
An AudioBook selling company wants to know, how many of its current customers will Repurchase the AudioBook service.
DataSet = ID, Book_length, Price, Review, Total_Minutes_Listened, Completion, Support_request, Last_visited, Target

Solution: 
Built a Machine Learning Model that predicts Repurchase, using past experiences with companies.

Techniques Used:
Data-Cleaning = Balancing_Dataset + Scaling_Data
Data_Splitting = Train_Dataset + Validation_Dataset + Test_Dataset
Loss-Function = Sparse_Categorical_Crossentrpy
Optimizer = Adam
Activation_Function = Relu
Over-Fit Check = Validation Dataset
Callback = Early_Stopping


About-Project:
Input_Size = 10
Output_Size = 2
Hidden_Layer_Size = 80
Epochs = 100
Batch-Size = 50
No. of Hidden Layer used = 2

Train-Result:
Loss: 0.3396 
Accuracy: 0.8148 
Val_Loss: 0.3292 
Val_Accuracy: 0.8456

Test-Result:
Loss: 0.3161 
Accuracy: 0.8304
