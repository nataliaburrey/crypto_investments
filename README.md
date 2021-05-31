
[
<img width="659" alt="Screen Shot 2021-05-31 at 4 46 14 AM" src="https://user-images.githubusercontent.com/80833988/120188585-28aed380-c1cb-11eb-82d6-e825270cb3d0.png">
](url)


> "In this Challenge, I will assume the role of an advisor in one of the top five financial advisory firms in the world. I will combine  financial Python programming skills with the new unsupervised learning skills acquired in rescent Module 10.
"



# Crypto Investments



:star: Challenge 10




[
<img width="595" alt="Screen Shot 2021-05-18 at 10 22 37 AM" src="https://user-images.githubusercontent.com/80833988/118696288-ff517900-b7c2-11eb-944d-50b5ca93cc94.png">
](url)



## Table of content
- [An executive summary](https://github.com/nataliaburrey/project_1#an-executive-summary)
    - [Overview of the project and project goals](https://github.com/nataliaburrey/project_1#overview-of-the-project-and-project-goals)
  
- [Software version control](https://github.com/nataliaburrey/project_1#software-version-control)
    - [Libraries / interfaces](https://github.com/nataliaburrey/project_1#libraries--interfaces)
    - [Work with GitHub](https://github.com/nataliaburrey/project_1#work-with-github)
    - [How to install](https://github.com/nataliaburrey/project_1#how-to-install)
- [Results and summary of the analysis](https://github.com/nataliaburrey/project_1/blob/main/README.md#results-and-summary-of-the-analysis)
- [Helps recruiters]()
- [License](https://github.com/nataliaburrey/project_1#license)





## An executive summary

The goal is to create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods, then plot the results so that we can visually show the performance.


[
<img width="1066" alt="Screen Shot 2021-05-31 at 5 05 32 AM" src="https://user-images.githubusercontent.com/80833988/120190715-d6bb7d00-c1cd-11eb-9b7c-98cb07ded68d.png">
](url)


###  Overview of the project and project goals.


## Software version control

### Libraries / interfaces
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* With the combination of Pandas and Jupyter Notebook, you can efficiently import, prepare, and analyze data of any type or quantity.
* Following libraries were used to analyze the data

```
# Import the required libraries and dependencies
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```





 
### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* Our repository is organized, and includes Resources folder with CSV  project files, 
* Jupyter Notebook with code runs without errors.
* Answers on nesassary questions are included

### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/crypto_investments.git
```

now you can find repo on your desktop


* Open a Jupyter Lab: In Terminal type command

```
jupyter lab
```

* In Jupyter Lab access saved repo folder 
* Choose [ crypto_investments.ipynb ] file to see the analysis report.




### Results and summary of the analysis

[
<img width="744" alt="Screen Shot 2021-05-31 at 5 00 22 AM" src="https://user-images.githubusercontent.com/80833988/120190186-1cc41100-c1cd-11eb-94ab-7df0aa80167c.png">
](url)

Based on the Elbow curve vizualisation, most likely the optimal value of clusters is 4. Hovever its always up to interpritation< so we will use further analysys to determine an actual optimal number of clusters.

[
<img width="756" alt="Screen Shot 2021-05-31 at 5 02 33 AM" src="https://user-images.githubusercontent.com/80833988/120190415-6b71ab00-c1cd-11eb-8910-b75165e2564e.png">
](url)

The total explained variance of the three principal components is 0.8844285111826466. It means that more than 88% of the data included in our scaled data, and less than 12% of original data we will sacrafice for simplicity of visualization. 

[
<img width="712" alt="Screen Shot 2021-05-31 at 5 01 17 AM" src="https://user-images.githubusercontent.com/80833988/120190288-3e24fd00-c1cd-11eb-87ca-d514f3cfee04.png">
](url)

It seems like k=4 is the optimal number of clusters to group cryptocurrencies according to their profitability 

## Helps recruiters

The project was created in collaboration with Berkeley Fintech Bootcamp team: Allan Hall, Joel Gonzales
Tutor Lavina Tang helped me to polish my code and tought me how to run separate parts of code to see if it works every step.
AskBCS Learning Assistant channel was used to troubleshoot some of the accuring problems outside of the classroom

## License

MIT
