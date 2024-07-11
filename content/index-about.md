
![test](/LaREx-website/images/LaREx_demo.gif)
LaREM confidence score signal in Object Detection with BDD-100K


## Abstract
Distribution shift detection is paramount in safety-critical tasks that rely on Deep Neural Networks (DNNs). 
The detection task entails deriving a confidence score to assert whether a new input sample aligns with the training data distribution of the DNN model. 
While DNN predictive uncertainty offers an intuitive confidence measure, exploring uncertainty-based distribution shift detection with simple sample-based techniques has been relatively overlooked in recent years due to computational overhead and lower performance than plain post-hoc methods. 
This paper proposes using simple sample-based techniques for estimating uncertainty and employing the entropy density from intermediate representations to detect distribution shifts. 
We demonstrate the effectiveness of our method using standard benchmark datasets for out-of-distribution 
detection and across different common perception tasks with convolutional neural network architectures. 
Our scope extends beyond classification, encompassing image-level distribution shift detection for 
object detection and semantic segmentation tasks. 
Our results show that our method's performance is comparable to existing _State-of-the-Art_ 
methods while being computationally faster and lighter than other Bayesian approaches, 
affirming its practical utility.

![test](/LaREx-website/images/LaREx_method.png)


### Acknowledgements

This work has been supported by the French government
under the "France 2030” program, as part of the SystemX
Technological Research Institute within the confiance.ai
Program (www.confiance.ai).

This publication was made possible by the use of FactoryIA
supercomputer, financially supported by the Ile-de-France
Regional Council.

