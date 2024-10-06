## 1.4 CRISP-DM

[![1.4 CRISP-DM](https://img.youtube.com/vi/dCa3JvmJbr0/0.jpg)](https://www.youtube.com/watch?v=dCa3JvmJbr0)


[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-14-crispdm)


## Notes

CRISP-DM, which stands for Cross-Industry Standard Process for Data Mining, is an open standard process model that describes common approaches used by data mining experts. It is the most widely-used analytics model. Conceived in 1996, it became a European Union project under the ESPRIT funding initiative in 1997. The project was led by five companies: Integral Solutions Ltd (ISL), Teradata, Daimler AG, NCR Corporation and OHRA, an insurance company: 

1. **Business understanding:** An important question is do we need ML for the project. The goal of the project has to be measurable. 
2. **Data understanding:** Analyze available data sources, and decide if more data is required. 
3. **Data preparation:** Clean data, remove noise applying pipelines, and convert the data to a tabular format, so we can put it into ML.
4. **Modeling:** Train different models and choose the best one. Considering the results of this step, it is proper to decide if it is required to add new features or fix data issues. 
5. **Evaluation:** Measure how well the model is performing and if it solves the business problem. 
6. **Deployment:** Roll out to production to all the users. The evaluation and deployment often happen together - **online evaluation**. 

It is important to consider how well maintainable the project is.
  
In general, ML projects require many iterations.

**Iteration:** 
* Start simple
* Learn from the feedback
* Improve

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
* [Lesson 1: Introduction to Machine Learning](./readme.md)
* Previous: [Supervised Machine Learning](03-supervised-ml.md)
* Next: [Model Selection Process](05-model-selection.md)