---
source: Lab 2_ Counting Statistics.pdf
converted_by: pdf2md
---

# **Lab 2: Counting Statistics**

by **Christian Cox, Devlin Jenkins**


PHYS 252, Section **001**


02/11/2025


**Abstract**

​ The purpose of this lab is to experiment with the concept of Poisson and Gaussian
probability distributions in the context of ionizing radiation sources. We will learn some
statistical analysis techniques using Google Sheets and Python to analyze, graph, and compare
results from a geiger counter being used on Strontium-90 and Cesium-137.

**Methodology**
​
In this lab we used a geiger counter to measure ionizing radiation from different
radioactive sources. We used Strontium-90 for a Poisson distribution analysis, and we used
Cesium-137 for a Gaussian distribution analysis. To collect this data; we connected the geiger
counter to the associated software on our lab computer and set the voltage to 800 V with 1000
runs at 1 second intervals. For the Poisson distribution, we collected data for a period of 1000
seconds and saved that into an excel file. We repeated that process with the Cesium-137 for a
period of 2500 seconds instead to find a Gaussian distribution.

**Data Analysis**
**​**


_Figure 1, a graph displaying the Frequency Distribution of our data from our_
_Strontium-90 during Run 1._


_Figure 2, a graph displaying the Poisson Distribution of our data from our Strontium-90_
_during Run 1._


_Figure 3, a graph displaying our frequency distribution for Run 1 using a Python script._

We processed and analyzed the data within our excel files and the given python scripts.
We started with the Poisson distribution by computing the average number of counts using the


formula 𝑛̄ = [1] ∑𝑛 . We then created a histogram of the recorded frequency counts. Next,


𝑚


𝑚
∑𝑛
𝑖


𝑖=1


𝑛
𝑒

𝑛!


−𝑛̄


we used the Poisson formula: 𝑃(𝑛) = [𝑛] 𝑒 to compute the Poisson probability and compare it


with our histogram we created earlier.


_Figure 4, a graph displaying the Frequency Distribution of our data from our_
_Cesium-139 during Run 2._


_Figure 5, a graph displaying the Gaussian Distribution of our data from our Cesium-139_
_during Run 2._


_Figure 6, a graph displaying our frequency distribution for Run 2 using a Python script._

​ As for the Gaussian distribution; we started by computing the average count rate of the


−(𝑛−𝑛)2


2σ


2


multiplied that by 2500 like before to find the theoretical Gaussian distribution. This was then
compared with the histogram we created earlier. As shown in Figure 5, our Gaussian distribution
doesn’t have the proper bell curve shape, which we postulate that it was because of an extreme
number of outliers in our data.

**Discussions**
_Compare your data by overlaying it on the same graph as the frequency plot. Is it different?_
_​_ The frequency plot looks very similar.
_What happens if you truncate your data such that you collected data for only 100 seconds? Does_
_your distribution change? Does the average number of counts change?_


There are larger deviations with a smaller number of counts. This also results in a slightly
different average number of counts.
_What is the average number of counts for your distribution_
_​_ 7.63 counts.
_If you binned your data into 2 second intervals, how would your data change?_
​ Our total number of bins would go from 1000 to 500. The frequency distribution would
be different as well because there would be less data points. The histogram would be a similar
shape but smoother because of less data.
_Does your histogram change if you truncate your data to 100 runs?_
_​_ Yes the histogram would change as well because there would be less data.
_Now add an aluminum attenuator between the Sr 90 source and the Geiger counter. This will_
_reduce the number of counts/second. How do your results change? Is your distribution skewed to_
_the right?_
_​_ The distribution changes because there are less counts per second. Yes, the distribution is
skewed to the right due to less counts.
_What happens if you truncate your data such that you collected data for only 100 seconds? Does_
_your distribution change? Does the average number of counts change?_
_​_ The histogram will be less smooth with less points. The gaussian shape will also be less
accurate due to the smaller amount of data points. Thus, the distribution changes. I would
imagine that since we are only capping the time, and not the amount of counts, that the average
number of counts would not change very much at all if we assume that radiation is emitted at a
somewhat constant rate.
_Approximate the full-width half-maximum of your distribution._

The full-width half-maximum seems to be around 90.
_What is the average number of counts for your distribution?_
_​_ 33.4 counts.
_If you binned your data into 2 second intervals, how would your data change?_
_​_ The histogram shape would be smoother but the bell curve would probably be roughly
the same.
_Does your histogram change if you truncate your data to 100 runs?_
_​_ Yes, the histogram would change as well because there would be less data. _​_

**Conclusion**
​ In this lab we analyzed the statistical nature of radioactive decay by studying the Poisson
and Gaussian distributions of two different materials using a geiger counter. Our graphs fit well
when compared to the python analysis graphs from the original data. This experiment
demonstrated the role of probability distributions in the process of radioactive decay, which goes
along with our learning of quantum tunneling in class right now.

![drawing from page 1](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p1_drawing0.png)


![embedded from page 2](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p2_img0.png)

![embedded from page 2](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p2_img1.png)

![drawing from page 2](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p2_drawing0.png)


![embedded from page 3](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p3_img0.png)

![embedded from page 3](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p3_img1.png)

![drawing from page 3](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p3_drawing0.png)


![embedded from page 4](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p4_img0.png)

![embedded from page 4](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p4_img1.png)

![drawing from page 4](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p4_drawing0.png)


![drawing from page 5](Lab 2_ Counting Statistics_images/Lab 2_ Counting Statistics_p5_drawing0.png)
