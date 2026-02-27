# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the independent variable X and dependent variable Y.
2.	Calculate the mean of the X -values and the mean of the Y -values.
3.	Find the slope m of the line of best fit using the formula.
 ![eqn1](./eq1.jpg)
4.	Compute the y -intercept of the line by using the formula:
![eqn2](./eq2.jpg)  
5.	Use the slope m and the y -intercept to form the equation of the line.
6.	Obtain the straight line equation Y=mX+b and plot the scatterplot.
## Program
```python
imoort numpy as np
import matplotlib.pyplot as plt
x=np.array([50, 51, 52, 53, 54, 54, 5, 56, 57, 58])
y=np.array([50, 55, 59, 60, 64, 60, 65, 68, 73, 72])
pIt.xlabel('Height')
plt.ylabel('Weight')
plt.scatter(x, y, color='red')


```
## Output
<img width="1143" height="706" alt="Screenshot 2026-02-26 161930" src="https://github.com/user-attachments/assets/92abf695-53bc-40d5-993b-20a536bd962e" />


## Result
Thus the univariate Linear Regression was implemented to fit a straight line using least squares.
