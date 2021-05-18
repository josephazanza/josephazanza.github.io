[<img src="../images/bdcc_censor_info.png">](https://raw.githubusercontent.com/josephazanza/josephazanza.github.io/master/images/bdcc_censor_info.png)

# Splitting the Internet with Big D: A Machine Learning Porn Classifier using Big Data

[Joseph Matthew Azanza](https://www.linkedin.com/in/josephazanza/) | [Ralph Roland Caubalejo](https://www.linkedin.com/in/ralph-caubalejo) | [Josef Ivan Monje](https://www.linkedin.com/in/josefmonje/) | [John Christopher Tambago](https://www.linkedin.com/in/jctambago/) <br>
Asian Institute of Management

## Abstract
<p align='justify'>
Pornography has its upsides and downsides. Porn has been one of the main drivers of technology, but on the flipside, it is also associated with increasing sexual crime rates, hindrance on children's sexual development, distortion of sexual attitutes and realities of adults, and dissatisfaction in marriages. Because of this seemingly double-edged nature of pornography, we feel that it's important to maintain our safe space online. With this project, we aim to answer the question, <i>“How can we leverage Machine Learning and Big Data techniques to develop a classifier model that flags pornographic, sex-related, and not safe for work (NSFW) objects?”</i>

In answering this, we first scraped 30,000 images of porn and non-porn from various websites of the internet. We then preprocessed this by manually removing the misclassified images and broken images. Following the manual cleaning, we uploaded this dataset to an AWS S3 bucket and followed two paths of processing: using CSV files that contain the flattened images vs using the images directly. Both methods dealt with at least 50 GB of data (55 GB and 70 GB, respectively) where we used Amazon EC2 instances + Dask and Dask-ML for the data reading and machine learning modelling proper. Following the different experimentations we did, our best model is a Random Forest Classifier that uses the images as its input, with an accuracy of 83.3%. This test accuracy beats the 1.25PCC baseline of 62.5%.

Overall, we successfully developed a machine learning model that classifies porn from neutral images using Big Data Techniques. With Dask and Dask-ML, we processed this large amount of data faster than traditional data wrangling techniques (via Pandas) and most importantly, our model captures more context due to the use of big data, making the predictions and generalizations more robust. In terms of further improvements we can do, we recommend to explore the use of Deep Learning or Convolutional Neural Networks to improve the accuracy values further and to create a more balanced dataset by meticulously ensuring an even distribution of different factors, i.e., equal counts of male and female genitalia.
<br><br>
<b>Keywords:</b> pornography classifier, big data, distributed machine learning
</p>

---

**Source code can be provided upon request, and upon approval of all project collaborators**

---

## [Back to main page](https://josephazanza.github.io/)