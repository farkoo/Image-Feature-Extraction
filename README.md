# Image feature extraction using keras

### what is Feature Extraction?
Feature extraction is a process of dimensionality reduction by which an initial set of raw data is reduced to more manageable groups for processing. A characteristic of these large data sets is a large number of variables that require a lot of computing resources to process. Feature extraction is the name for methods that select and /or combine variables into features, effectively reducing the amount of data that must be processed, while still accurately and completely describing the original data set.

Feature extraction involves reducing the number of resources required to describe a large set of data. When performing analysis of complex data one of the major problems stems from the number of variables involved. Analysis with a large number of variables generally requires a large amount of memory and computation power, also it may cause a classification algorithm to overfit to training samples and generalize poorly to new samples. Feature extraction is a general term for methods of constructing combinations of the variables to get around these problems while still describing the data with sufficient accuracy. Many machine learning practitioners believe that properly optimized feature extraction is the key to effective model construction.

### Implementation:
When performing deep learning feature extraction, we treat the pre-trained network as an arbitrary feature extractor, allowing the input image to propagate forward, stopping at pre-specified layer, and taking the outputs of that layer as our features.

<p align=center>
<img src="https://www.pyimagesearch.com/wp-content/uploads/2019/05/transfer_learning_keras_feature_extract.png">
</p>

*Left:* The original VGG16 network architecture that outputs probabilities for each of the 1,000 ImageNet class labels. 

*Right:* Removing the FC layers from VGG16 and instead returning the final POOL layer. This output will serve as our extracted features.

 
## Support

**Contact me @:**

e-mail:

* farzanehkoohestani2000@gmail.com

Telegram id:

* [@farzaneh_koohestani](https://t.me/farzaneh_koohestani)

## License
[MIT](https://github.com/farkoo/Image-Feature-Extraction/blob/master/LICENSE)
&#0169; 
[Farzaneh Koohestani](https://github.com/farkoo)
