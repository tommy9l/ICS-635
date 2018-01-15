**Assignment #1 for ICS 635**

- - -

1. Implement perceptron learning algorithm: N inputs **x<sub>i</sub>** and labels l<sub>i</sub>
   * Initialize weight vector **w**
   * While there exist misclassified examples: ⋅⋅

      * Compute y<sub>i</sub> = θ(**wx<sub>i</sub>**)      
 
      * For each example, update the weights: **w** += c(l<sub>i</sub>-y<sub>i</sub>)**x<sub>i</sub>**
   
1. Play around with the parameter (learning rate) and the input data, and verify for yourself what the Perceptron can and cannot do.

   * Make a movie of Perceptron converging, and one of Perceptron failing on the XOR.
 
1. What else do you notice?

   * Is every solution the same? If not, are some "better" than others in some sense?


- - -

Pseudo Code for perceptron (as I understand):

2. Provide the perceptron with inputs for which there is a known answer
2. Ask the perceptron to guess an answer
2. Computer the error.
    
    * Error = Answer - Guess

2. Adjust all the weights according to the error.

    * Delta Weight = (Error * input) * learning_rate
    * New Weight = weight  + Delta Weight
    
2. Return to step 1 and repeat.
