# Cycle-Spinning-NN
Cycle-Spinning (CS) method usage in deep learning. Papers:
(<a href="https://ieeexplore.ieee.org/document/9832606" rel="nofollow"> Cycle-Spinning Convolution for Object Detection </a>) and
(<a href="https://ieeexplore.ieee.org/document/8909824" rel="nofollow"> Cycle-Spinning GAN for Raindrop Removal from Images </a>)
## Cycle-Spinning methodology

    - Exploits the shift variance of the underlying method.

    - Has been successfully used in image de-noising, enhancement, and super-resolution problems. 

    - Works by applying predefined spatial translations to the input image to obtain several different estimates of the output.

    - Gets the final output using the results of aligning and merging these different solutions. 
   
   
   
   
<div align="center">
  <p>
  <img width="850" src="https://github.com/UlkuUZUN/assets/blob/main/sekil_son.jpg">
  </p>
</div>

We repeated the experiment by adding Gaussian noise to the Lena image seen in Figure. 
The results of the convolution, CS applied and low-pass filtered versions of the Lena image are show sequentially.
In the upper row of figure, 8 times magnification of Lena’s hat section is shown for better view of the details.
As a result, it is seen that the CS method implementation removes noise without losing details.
When the results have been compared with the low-pass filtered version, it is also seen that the edge lines of the objects are not blurred in the CS-implemented version.


<div align="center">
  <p>
  <img width="850" src="https://github.com/UlkuUZUN/assets/blob/main/2DExperiments.png">
  </p>
</div>



