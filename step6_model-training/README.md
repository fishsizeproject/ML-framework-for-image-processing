# Step 6: Model training and testing

This framework uses the Tensorflow Lite Model Maker library (Abadi et al. 2016a; b) and transfer learning which reduces the amount of training data required and model training time. Tensorflow Lite supports several model architectures, including EfficientNet-Lite, MobileNetV2 and ResNet50 (He et al. 2016; Sandler et al. 2018; Tan & Le 2019) which are pre-trained models for image classification, and EfficientDet-Lite[0-4], a family of mobile and IoT-friendly models for object detection, derived from the EfficientDet architecture (Tan et al. 2020). The library is flexible and new pre-trained models can be added by customising the library code.

For this framework, we developed the script <i>image_classification.ipynb</i> to train and test (evaluate) an image classification model using the pre-trained models mentioned above. This script also generates a confusion matrix for visualizing model performance and functions to load a trained model and run classification inference on new images. The script <i>object_detection.ipynb</i> includes functions to train and test an object detection model.


  <a href="https://arxiv.org/abs/1603.04467">Abadi M, Agarwal A, Barham P, Brevdo E, Chen Z, Citro C, Corrado GS, Davis A, Dean J, Devin M, Ghemawat S, Goodfellow I, Harp A, Irving G, Isard M, Jia Y, Jozefowicz R, Kaiser L, Kudlur M et al. (2016a) TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems. arXiv. </a>
  
 <a href="chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.usenix.org/system/files/conference/osdi16/osdi16-abadi.pdf">Abadi M, Barham P, Chen J, Chen Z, Davis A, et al . (2016b) TensorFlow.js. In: Proceedings of the 12th USENIX Symposium on Operating Systems Design and Implementation </a>

 <a href="https://ieeexplore.ieee.org/document/7780459">He K, Zhang X, Ren S, Sun J (2016) Deep residual learning for image recognition. Proceedings of the IEEE Computer Society Conference on Computer Vision and Pattern Recognition, 770–778.</a>

 <a href="https://ieeexplore.ieee.org/document/8578572">Sandler M, Howard A, Zhu M, Zhmoginov A, Chen LC (2018) MobileNetV2: Inverted Residuals and Linear Bottlenecks. Proceedings of the IEEE Computer Society Conference on Computer Vision and Pattern Recognition, 4510–4520.</a>

 <a href="https://proceedings.mlr.press/v97/tan19a.html">Tan M, Le Q V. (2019) EfficientNet: Rethinking model scaling for convolutional neural networks. 36th International Conference on Machine Learning, ICML 2019, 10691–10700.</a>

 <a href="https://ieeexplore.ieee.org/document/9156454">Tan M, Pang R, Le Q V. (2020) EfficientDet: Scalable and efficient object detection. Proceedings of the IEEE Computer Society Conference on Computer Vision and Pattern Recognition, 10778–10787.</a>

