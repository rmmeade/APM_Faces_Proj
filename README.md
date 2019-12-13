# Bias in Age & Gender Prediction CNN

#### Examining bias in VGG-Face through the lens of age and gender prediction to encourage the development of fair, accountable, and transparent machine learning.

The initial approach focuses in predicting the age and gender of people based on their facial images, with the goal of implementing real-time image classification for deployment in retail locations. 

While some stores already use visual recognition for theft control. The business implication of this could be facial recognition to enhance store loyalty programs or for customization of services. A Forbes article points out that loyalty members have generally already agreed to share personal data with the brand, so enhancement of loyalty programs through facial recognition may not be far in the future.

With its burgeoning ubiquity, it felt important to understand this technology, so the inner workings of image detection and classification are explored by building a convolutional neural net capable of predicting a person’s age and gender from his or her image. With the use of transfer learning, a model trained with a large image set can be re-trained with a dataset of photos of people "in-the-wild", which are more suited for the interests of the project. Then using predictions from the model, a further examination of any bias the model might have is made. Although the findings may not be perfectly representative of the models being used in commercial deployment today, this project aims to shed light on bias in machine learning and to highlight the importance of thoughtful development of fair, accountable, and transparent machine learning.
