# Neural-Network-from-Scratch
A neural network built entirely with basic math functions in c++ that distinguish circles and rectangles    
# Explanation     
In normal circumstances, the step activation function choosed for a neural network is either sigmoid or tanh shown in the equations below  
         
![image](https://user-images.githubusercontent.com/101462429/164486917-0d8785a5-5a6e-4f6b-a846-ed40c1bfad71.png)         
        
![image](https://user-images.githubusercontent.com/101462429/164487397-27d4892c-b37b-4cb2-be77-4e9844d27dbe.png)      
          
For each individual activation functon, there has to be a corresponding function for updating weights.
In most networks, the function for updating the weight is shown below             
                       
![image](https://user-images.githubusercontent.com/101462429/164485414-74b39564-e841-4eb2-b845-17a688712405.png)             
            
W':      New weight that has been updated.      
W:       A Weight which connects two neurons that need to be update.
m, n:    Index values expressing the relative position of the input neuron.      
Eta:     Learning Rate.            
Delta:   Loss       
f(u):    The output of the input neuron as a function of "u".          
u:       The sum of the product of each weight and output of output neurons in the previous.          
X:       The output of the output neuron which the weight in connecting.              
