
## 2.12 Categorical variables

[![2.12 Categorical variables](https://img.youtube.com/vi/sGLAToAAMa4/0.jpg)](https://www.youtube.com/watch?v=sGLAToAAMa4)

[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-2-slides)


## Notes

Categorical variables are typically strings, and pandas identifies them as object types. These variables need to be converted to a numerical form because ML
models can interpret only numerical features. It is possible to incorporate certain categories from a feature, not necessarily all of them. 
This transformation from categorical to numerical variables is known as One-Hot encoding. 

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

* [Notes from Peter Ernicke](https://knowmledge.com/2023/09/23/ml-zoomcamp-2023-machine-learning-for-regression-part-10/)

## Comments

This way of encoding categorical features is called "one-hot encoding".
We'll learn more about it in Session 3. 


## Navigation

* [Machine Learning Zoomcamp course](../README.md)
* [Session 2: Machine Learning for Regression](./readme.md)
* Previous: [Feature engineering](11-feature-engineering.md)
* Next: [Regularization](13-regularization.md)