In this research, we addressed the challenging task of brain tumor detection in MRI scans using a large collection of brain tumor images. We demonstrated that fine tuning a state-of-the-art YOLOv7 model through transfer learning significantly improved its performance in detecting gliomas, meningioma, and pituitary brain tumors. Our proposed deep learning model showed promising results, accurately identifying the presence and precise location of brain tumors in MRI images. The proposed approach achieved better accuracy compared to standard techniques, with a remarkable 99.5% accuracy in our analysis. However, we acknowledge that additional investigation and testing are essential to ensure the effectiveness of our method for detecting small tumors. The complexity of small tumor identification warrants ongoing research in brain tumor identification and continuous refinement of our detection systems. By pursuing this avenue, we aim to enhance the diagnostic capabilities for patients and medical practitioners in the challenging battle against brain cancers.
The rapid development of abnormal brain cells that characterizes a brain tumor is a major health risk for adults since it can cause severe impairment of organ function and even death. These tumors come in a wide variety of sizes, textures, and locations. When trying to locate cancerous tumors, magnetic resonance imaging (MRI) is a crucial tool. However, detecting brain tumors manually is a difficult and time-consuming activity that might lead to inaccuracies. In order to solve this, we provide a refined You Only Look Once version 7 (YOLOv7) model for the accurate detection of meningioma, glioma, and pituitary gland tumors within an improved detection of brain tumors system. The visual representation of the MRI scans is enhanced by the use of image enhancement methods that apply different filters to the original pictures. To further improve the training of our proposed model, we apply data augmentation techniques to the openly accessible brain tumor dataset. The curated data include a wide variety of cases, such as 2548 images of gliomas, 2658 images of pituitary, 2582 images of meningioma, and 2500 images of non-tumors. We included the Convolutional Block Attention Module (CBAM) attention mechanism into YOLOv7 to further enhance its feature extraction capabilities, allowing for better emphasis on salient regions linked with brain malignancies. To further improve the model’s sensitivity, we have added a Spatial Pyramid Pooling Fast+ (SPPF+) layer to the network’s core infrastructure. YOLOv7 now includes decoupled heads, which allow it to efficiently glean useful insights from a wide variety of data. In addition, a Bi-directional Feature Pyramid Network (BiFPN) is used to speed up multi-scale feature fusion and to better collect features associated with tumors. The outcomes verify the efficiency of our suggested method, which achieves a higher overall accuracy in tumor detection than previous state-of-the-art models. As a result, this framework has a lot of potential as a helpful decision-making tool for experts in the field of diagnosing brain tumors.

Keywords: brain tumor, MRI, deep learning, artificial intelligence, YOLOv7, attention mechanism, medical images, CBAM, convolution neural networks (CNN), transfer learning

