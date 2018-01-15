**Assignment #1 for ICS 635**

- - -

1. Implement perceptron learning algorithm: N inputs **x~i** and labels l~i
   * Initialize weight vector **w**
   * While there exist misclassified examples: ⋅⋅

      * Compute output ![equation](http://www.sciweavers.org/tex2img.php?eq=y_i%3D%5Ctheta%20%28wx_i%29&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)
   
      * For each example, update the weights: ![equation](http://www.sciweavers.org/tex2img.php?eq=w%20%2B%3D%20c%28l_i%20-%20y_i%29x_i&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)
   
2. Play around with the parameter (learning rate) and the input data, and verify for yourself what the Perceptron can and cannot do.

   * Make a movie of Perceptron converging, and one of Perceptron failing on the XOR.
 
3. What else do you notice?

   * Is every solution the same? If not, are some "better" than others in some sense?
