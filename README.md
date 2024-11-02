This implementation demonstrates image colorization using Conditional Generative Adversarial Networks (cGANs), following the approach outlined in the paper Image-to-Image Translation with Conditional Adversarial Networks.

RESULTS:
The first row is the input grayscale image, second row is the output color image of the model and the third row is actual color image(or ground truth).  
![image](https://github.com/user-attachments/assets/12dea5bf-1ce3-4383-a834-093db7c0af74)
![image](https://github.com/user-attachments/assets/f46369b8-418e-42c4-ad47-1b5ac85df8f7)
![image](https://github.com/user-attachments/assets/d7942a00-3a12-48a4-af3f-3e1257ccccfd)


The model has a basic understanding of common objects and environments, such as skies and trees, and can colorize them in a somewhat realistic manner.

However, the output is often far from appealing, with the model struggling to assign appropriate colors to rare or less-common objects(Can see all different outputs in google colab). 

Notably, color spillovers and artifacts are visible in some images, such as circular-shaped color blotches. This basically suggests that the model lacks precision, possibly due to the dataset's limitations as I have trained the model on 18000 randomly chosen images from COCO dataset and tested on different 2000 images. 





