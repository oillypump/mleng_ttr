## 2.2 Data preparation

[![2.2 Data preparation](https://img.youtube.com/vi/Kd74oR4QWGM/0.jpg)](https://www.youtube.com/watch?v=Kd74oR4QWGM)

[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-2-slides)


## Notes

**Pandas attributes and methods:** 

* pd.read_csv(<file_path_string>) - read csv files 
* df.head() - take a look of the dataframe 
* df.columns - retrieve colum names of a dataframe 
* df.columns.str.lower() - lowercase all the letters 
* df.columns.str.replace(' ', '_') - replace the space separator 
* df.dtypes - retrieve data types of all features 
* df.index - retrieve indices of a dataframe

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

## Navigation

* [Machine Learning Zoomcamp course](../README.md)
* [Session 2: Machine Learning for Regression](./readme.md)
* Previous: [Car price prediction project](01-car-price-intro.md)
* Next: [Exploratory data analysis](03-eda.md)