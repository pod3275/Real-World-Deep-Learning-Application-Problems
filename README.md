# Methods to Overcome the Real-World Deep Learning Application Problems

## ABSTRACT 

In recent years, the development of machine learning, especially deep learning, and its
applications have been actively studied. Although deep learning is applied in many areas, there are still
problems to be solved in order to introduce deep learning models into real-world systems. In this paper,
we summarized the papers that overcome various problems in the real-world application of the deep
learning model. 

### 1. Detect Adversarial Example Using Gaussian Process-based Detector
For the image classification model, an adversarial attack has been proposed which causes
malfunction of the model by mixing noise that is hardly distinguishable by human into the input image
of the model. As a result, the reliability of the deep learning model has been raised, and a study has
been proposed to prevent the adversarial attack. Lee et al. proposed an adversarial detection method based
on gaussian process regression using intermediate features extracted from the classification model. The
proposed detector showed higher detection performance than other detection methods when extremely few
adversarial examples are used in training. 

### 2. String CAPTCHA attack using CNN
Lee et al. proposed a deep learning model that recognizes string
CAPTCHAs that widely used in internet sites. The proposed method eliminates the noise in the CAPTCHA
image through image processing, separates string image into single character images, and recognizes
CAPTCHA characters by training CNN model. As a result of experiment on CAPTCHA used in Korea ticket
reservation site, the proposed model showed a high recognition rate of 85% based on CAPTCHA.

### 3. Box Office Forecasting using Non-Linear Regression
Won et al. proposed a deep learning model that predicts movie audience demand before opening by using a nonlinear
regression model. In addition to features provided by the KOFIC, which provides cinema information,
they define features that can be used for prediction and proposed a Bi-LSTM deep learning model to
perform sentimental analysis on movie reviews. Experimental results showed that the proposed method had
higher performance than other sentimental analysis methods and effectively predicted the demand of movie
audience.

### 4. Embedding for Out of Vocabulary Words Considering Contextual and Morphosyntactic Information
Won et al. proposed a technique for effectively handling the OOV words that are not in the existing
vocabulary during word embedding. The proposed method is a Bi-LSTM structured deep learning model
named Context-Char, which embeds the OOV words using contextual and morphosyntactic information.
As a result of experiments using datasets containing the OOV words, the proposed method showed higher
performance than other methods of handling OOV words. 

### 5. Deep representation model-based Under-sampling Method for Imbalanced data
Lim et al. proposed an effective under-sampling
technique for processing imbalanced data. They proposed deep representation models that extract the
structural features of major class data and minor class data and calculated the degree of conformity of the
data to determine under-sampling. In the experiments using various imbalanced data, the proposed method
showed higher performance than other processing methods for most datasets.
