# MNIST-adversarial-images
Create adversarial images to fool a MNIST classifier in TensorFlow

## A Tech Challenge
**Backstory**

The original concept of this notebook was based on a Machine Learning (intern) candidate tech challenge from the Toronto startup [500px](https://500px.com). When I first saw the posting, it was at the beginning of my 3 month career pivot into Deep Learning and I thought this challenge would be a great way for me to benchmark my progress once I get started. You can read more about my career transition journey on [Medium](https://medium.com/towards-data-science/my-3-month-deep-learning-career-pivot-af94cd8d6a31) and a revised/updated version on [LinkedIn]().

Although, I didn't follow through with providing the entire final output of the challenge, I'm quite satisfied that I've successfully completed it and consider it a demonstration of my current knowledge and capability. Prior to starting this challenge, I completed [Fast.ai: Practical Deep Learning - Part 1](http://course.fast.ai/). Read through my blog post to see my reading material - [Deep Learning Reading List](http://jasonicarter.github.io/deep-learning-reading-list).

**The Challenge (summarized)**

Create adversarial images to fool a MNIST classifier in TensorFlow.
1. Learn how adversarial examples are created. For example, “Breaking Linear Classifiers on ImageNet” gives a good overview on the 
2. Install Tensorflow
3. Follow “Deep MNIST for Experts” tutorial to get the MNIST classifier running.
4. Expand the code from the previous step to generate adversarial images. Specifically, pick 10 images of digit ‘2’ which are correctly classified as ‘2’ by the trained model and modify them so the network incorrectly classifies them as 6.
5. Generate adversarial examples and save them as a single image containing a grid of 10 rows and 3 columns. The rows correspond to the selected examples of ‘2’. The columns are original image, delta and adversarial image. Provide link to the resulting image.
6. Make your code clean and readable. Add comments where needed.
