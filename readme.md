# ID Card Segmentation with U-Net

Performing semantic segmentation on ID cards using U-Net implemented in Tensorflow 2.10.0

## Example Usage
Run `python example.py -i <path-to-image> -o <path-to-output-file>` to generate a segmented ID card image.
![Test Image](https://drive.google.com/uc?export=view&id=1adz2BHx_x3ibqgF8vim2ZDzbDykRAqAr)

See `example.py` for more details.

## Implementation
See the U-Net Semantic Segmentation notebook for comprehensive details regarding model implementation, training, inference and a complete pipeline example.

## Model
You can use the pre-trained model `best_model.h5`. This model achieved 96.5% mean IoU on the test set.

## References
1. Github: [ML_IDCard_Segmentation-TF-Keras](https://github.com/tobiassteidle/ML_IDCard_Segmentation-TF-Keras)

2. Dataset: [MIDV-500](https://arxiv.org/abs/1807.05786)

3. Perspective transformation from 
How to Build a Kick-Ass Mobile Document Scanner by [PyimageSearch](https://pyimagesearch.com/2014/09/01/build-kick-ass-mobile-document-scanner-just-5-minutes/)

4. Github: [Imutils](https://github.com/PyImageSearch/imutils)
