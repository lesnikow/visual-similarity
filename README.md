# visual-similarity

Finding visually similar images on a database of men's dress shirts.

This repo contains [our Jupyter notebook](Source/visualSimilarity.ipynb), which uses a deep convolutional neural network to extract deep features from the query images, and a k-nearest neighbors classifier to find the most visually similar images to a given query. [Results/](Results/) contains the test and returned images for the various pipelines, with subfolders DeepFeats256/, DeepFeats16/ and Pixels/, which contain the results from the deep feature classifers with 256 filters, 16 filters and the classifer on pixel space respectively. Query image n is at nquery_image.png, with its top kth visually similar images at nreturn_imagek.png. For example 17query_image.png is the 17th query image, and the returned images are at 17return_image1.png, 17return_image2.png, and so on. 

## Results

### Neural Codes

Here are the first four queries and results from our **deepFeats256** pipeline using 256 filters from a deep neural network, **L2** metric:

![](Results/DeepFeats256/0query_image.png)
![](Results/DeepFeats256/0return_image1.png)
![](Results/DeepFeats256/0return_image2.png)
![](Results/DeepFeats256/0return_image3.png)
![](Results/DeepFeats256/0return_image4.png)
![](Results/DeepFeats256/0return_image5.png)

![](Results/DeepFeats256/1query_image.png)
![](Results/DeepFeats256/1return_image1.png)
![](Results/DeepFeats256/1return_image2.png)
![](Results/DeepFeats256/1return_image3.png)
![](Results/DeepFeats256/1return_image4.png)
![](Results/DeepFeats256/1return_image5.png)

![](Results/DeepFeats256/2query_image.png)
![](Results/DeepFeats256/2return_image1.png)
![](Results/DeepFeats256/2return_image2.png)
![](Results/DeepFeats256/2return_image3.png)
![](Results/DeepFeats256/2return_image4.png)
![](Results/DeepFeats256/2return_image5.png)

![](Results/DeepFeats256/3query_image.png)
![](Results/DeepFeats256/3return_image1.png)
![](Results/DeepFeats256/3return_image2.png)
![](Results/DeepFeats256/3return_image3.png)
![](Results/DeepFeats256/3return_image4.png)
![](Results/DeepFeats256/3return_image5.png)


### Pixel Space Baseline
Versus our **pixel space baseline** search:

![](Results/Pixels/0query_image.png)
![](Results/Pixels/0return_image1.png)
![](Results/Pixels/0return_image2.png)
![](Results/Pixels/0return_image3.png)
![](Results/Pixels/0return_image4.png)
![](Results/Pixels/0return_image5.png)

![](Results/Pixels/1query_image.png)
![](Results/Pixels/1return_image1.png)
![](Results/Pixels/1return_image2.png)
![](Results/Pixels/1return_image3.png)
![](Results/Pixels/1return_image4.png)
![](Results/Pixels/1return_image5.png)

![](Results/Pixels/2query_image.png)
![](Results/Pixels/2return_image1.png)
![](Results/Pixels/2return_image2.png)
![](Results/Pixels/2return_image3.png)
![](Results/Pixels/2return_image4.png)
![](Results/Pixels/2return_image5.png)

![](Results/Pixels/3query_image.png)
![](Results/Pixels/3return_image1.png)
![](Results/Pixels/3return_image2.png)
![](Results/Pixels/3return_image3.png)
![](Results/Pixels/3return_image4.png)
![](Results/Pixels/3return_image5.png)


Date: Aug 4, 2016
Author: Adam Lesnikowski
Edited Aug 5, 2016, Aug 12, 2016.
