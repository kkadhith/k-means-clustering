# K Means Clustering in Python

This is my implementation of the k-means clustering algorithm from scratch in Python (using NumPy).

# Results

I ran k-means clustering on a small (256x256) image with different values of K to visualize the algorithm. Here are samples:

<img src="/img/img2.png"> <img src="/img/image.png">

Also, I ran tests on how different values of K and the data's standard deviation changed the SSE. Generally, as the value of K increased, the SSE stabilized faster with a smaller SSE. Here are the results:

## Using Smaller Value for K
<img src="/img/low.png"> <img src="/img/lowsse.png">

## Using Larger Value for K
<img src="/img/high.png"> <img src="/img/highsse.png">

