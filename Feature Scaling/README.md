# Feature Scaling 
 When the range of values are very distinct in each column, we need to scale them to the common level. The values are brought to common level and then we can apply further machine learning algorithm to the input data.

## Different Feature Scaling Techniques

We can use different Scaling Techniques in order to scale the input dataset. We can apply either of the following:

- Standardization
- Normalization

### What is Normalization ?

Normalization is a scaling technique in which values are shifted and rescaled so that they end up ranging **between 0 and 1**. It is also known as Min-Max scaling.

Formula for normalization:
    

$$
X(norm) = \frac{X-Xmin}{Xmax-Xmin}
$$

In the above equation:

     - Xmax and Xmin is Maximum and Minimum Value of the feature column
     - When the value of X is the minimum value in the column, the numerator will be 0, and hence X(norm) is 0
     - On the other hand, when the value of X is the maximum value in the column, the numerator is equal to the 
       denominator and thus the value of X(norm) is 1
     - If the value of X is between the minimum and the maximum value, then the value of X(norm) is between 0 and 1

<a > example of the Normalization </a>
### What is Standardization ?

It is a very effective technique which re-scales a feature value so that it has distribution with 0 mean value and variance equals to 1.

Formula for Standardization:
    

$$
X(stand) = \frac{X-mun}{sigma}
$$

    - number is the mean of the feature values and sigma is the standard deviation of the feature values. 
    - Note that in this case, the values are not restricted to a particular range.


<a> Example of The Standaridzation </a>

## will cover the following recipes:
1 - Standardizing the features <br/>
2 - Scaling to the maximum and minimum values <br/>
3 - Scaling with the median and quantiles <br/>
4 - Implementing maximum absolute scaling <br/>
5 - Scaling to vector unit length




## Scaling to vector unit length
The result of the preceding transformation is called the z-score and represents how many standard 
deviations a given observation deviates from the mean. In this recipe, we will implement standardization 
with scikit-learn. <a> Example code </a>

## Scaling to maximum and minimun value 
Scaling to the minimum and maximum values squeezes the values of the variables between 0 and 1. 
To implement this scaling technique, we subtract the minimum value from all the observations and 
divide the result by the value range, that is, the difference between the maximum and minimum values Y
<a> Code Example </a>

## Scaling with the median and quntiles

