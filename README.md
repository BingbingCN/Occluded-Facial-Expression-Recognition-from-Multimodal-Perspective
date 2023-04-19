# Occluded Facial Expression Recognition from Multimodal Perspective
Although expression recognition has been widely applied in our daily life, there remain some tough challenges posed to the expression recognition with occlusion. The recognition of facial expression through image features relies on a large amount of data annotation with low accuracy. Along with the popularity of visual language models (e.g., CLIP), the problem with unimodal image recognition can be converted into the problem with multimodal graphical matching. Thus, the problem with occluded  expression recognition can be converted into a problem of matching image and text descriptions, such as "This is a face image that may be partially occluded. Expression on the image is [class]". However, the effect of image matching is affected by the prompt. Therefore, to address this problem for CLIP, we introduce soft prompt based on a multilayer perceptron on the CLIP image encoder, based on the soft prompt introduced by CoOp on the text encoder. According to the experimental results, the visual language model based on CLIP and soft prompt outperforms the current state-of-the-art methods in dealing with occluded expression recognition

This repository is the Github code involved in the manuscript submitted to Image and Vision Computing, and we will update the executable runner at some point in the future.

