
## 2.7 Training linear regression: Normal equation

[![2.7 Training linear regression: Normal equation](https://img.youtube.com/vi/hx6nak-Y11g/0.jpg)](https://www.youtube.com/watch?v=hx6nak-Y11g)

[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-2-slides)


## Notes

Obtaining predictions as close as possible to $y$ target values requires the calculation of weights from the general
LR equation. The feature matrix does not 
have an inverse because it is not square, so it is required to obtain an approximate solution, which can be
obtained using the **Gram matrix** 
(multiplication of feature matrix ($X$) and its transpose ($X^T$)). The vector of weights or coefficients $w$ obtained with this
formula is the closest possible solution to the LR system.

Normal Equation:

$w$ = $(X^TX)^{-1}X^Ty$

Where:

$X^TX$ is the Gram Matrix




The entire code of this project is available in [this jupyter notebook](https://github.com/alexeygrigorev/mlbookcamp-code/blob/master/chapter-02-car-price/02-carprice.ipynb). 

<table>
   <tr>
      <td>⚠️</td>
      <td>
         The notes are written by the community. <br>
         If you see an error here, please create a PR with a fix.
      </td>
   </tr>
</table>

* [Notes from Peter Ernicke](https://knowmledge.com/2023/09/21/ml-zoomcamp-2023-machine-learning-for-regression-part-6/)

## Navigation

* [Machine Learning Zoomcamp course](../README.md)
* [Session 2: Machine Learning for Regression](./readme.md)
* Previous: [Linear regression: vector form](06-linear-regression-vector.md)
* Next: [Baseline model for car price prediction project](08-baseline-model.md)