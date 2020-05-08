# Semantic-Scene-Composition-For-Amodal-Segmentation


## Abstract for the Project
 Visual recognition tasks such as object detection, classification and semantic segmentation, are now almost approaching human levels performances due to rapid rate of progress in recent years. However, the task of Amodal instance segmentation, which is to predict the region encompassing both visible and occluded parts of objects in an image, is still far for reaching maturity.  Human beings learn and have this innate ability to imagine what the complete objects look like, even if objects might be half occluded. Amodal instance segmentation lets the model act in a similar way, by imagining beyond the visible pixels and providing complex reasoning about full scene structure. But a major roadblock in this task so far has been the lack of a dataset with annotations for amodal instances. In this work, we propose an architecture capable of generating scene composition by placing provided individual objects in the scene, in a context aware manner. We do this by learning a projection matrix based on encoded geometry and semantic information, and use a discriminator loss for training it to produce realistic compositions. Using this pipeline, we would get free amodal mask even in cases where objects are half occluded without human labelling, which can be further used for several other tasks such as scene inpainting of occluded part of the objects or other related segmentation tasks. 
 
 ## File Structure and description of each file
 
 ### datasets.py
 ### inference.py
 ### inference_522.py
 ### inference_baseline.py
 ### models.py
 ### models_baseline.py
 ### spectral_normalization.py
 ### train.py
 ### train_baseline.py
 ### vis_tools.py
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 ## Instructions to run the code
