# Computer-Vision-Segmentation

UNET and CANet are both neural network architectures used in computer vision, particularly for tasks involving image segmentation. They are designed to segment images into different regions or classes, which is useful for tasks like object detection, medical image analysis, and more.

## UNet:

UNet is a convolutional neural network architecture introduced by Olaf Ronneberger, Philipp Fischer, and Thomas Brox in their paper "U-Net: Convolutional Networks for Biomedical Image Segmentation" (2015). UNet is particularly popular in biomedical image analysis but has also been applied to various other segmentation tasks.

The UNet architecture is characterized by a U-shaped design with a contracting path (encoder) and an expansive path (decoder). The encoder captures the context and features of the input image, while the decoder gradually upsamples the features and reconstructs the segmented output. Skip connections are a key feature of UNet, allowing information from the encoder to be directly transferred to the decoder, aiding in the preservation of spatial information.

UNet has been widely adopted due to its effectiveness in capturing fine details and its ability to handle limited training data.

## CANet (Contextual Attention Network):

CANet is a more recent architecture introduced by Tong He, Zhi Zhang, Hang Zhang, Zhongyue Zhang, Junyuan Xie, and Mu Li in their paper "Contextual Attention for Handwritten Chinese Character Recognition" (2018). CANet is designed to capture long-range dependencies and contextual information for improved image segmentation, especially for complex and structured data like handwritten Chinese characters.

The main innovation of CANet is the contextual attention mechanism, which captures global dependencies and context information across the entire image. It allows the model to focus on relevant regions while suppressing irrelevant parts of the input. This mechanism enhances the model's ability to capture intricate details and improve segmentation accuracy.

