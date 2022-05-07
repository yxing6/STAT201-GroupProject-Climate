### Verify the Effect of Climate Change

In STAT 201 - Statistical Inference for Data Science, we conducted a group project to study:  
> **Is there a significant difference in the weather record of the 1950s and the 2000s in terms of temperature and precipitation?**
  
We sampled from a weather station in BC, and examined two variables: daily temperature and yearly maximum rainfall over two category: historical and contemporary. Hypothesis testing and confidence interval are applied. Method of computer simulation by bootstrap and asymptotic are used to compare the test results. 

Summary of one test results: 
  
**Null Hypothesis**:              <img src="https://render.githubusercontent.com/render/math?math=H_0^{1}: \mu_{ct} - \mu_{ht} = 0">  
The difference between the population mean of the contemporary daily temperature and the historical daily temperature is zero.  
  
**Alternative Hypothesis**:  <img src="https://render.githubusercontent.com/render/math?math=H_A^{1}: \mu_{ct} - \mu_{ht} \neq 0">  
The difference between the population mean of the contemporary daily temperature and the historical daily temperature is not zero.  

| Test Statistic    | Observed Test Statistic |Method  | p-value | Lower CI  |  Upper CI
| :----------: | :----------: | :----------: |:----------:| :---------:| :---------:
| <img src="https://render.githubusercontent.com/render/math?math=\bar{x}_{ct} - \bar{x}_{ht}">  | 1.258 |Simulation|<0.001|1.048|1.465|
| <img src="https://render.githubusercontent.com/render/math?math=\bar{x}_{ct} - \bar{x}_{ht}">  | 1.258 |Asymptotic |<0.001|1.055|1.461|
>**The p-value is < 0.001, we reject the null hypothesis <img src="https://render.githubusercontent.com/render/math?math=H_0^{1}"> in favor of <img src="https://render.githubusercontent.com/render/math?math=H_A^{1}"> at the 5% significant level.  
There is a significant difference between <img src="https://render.githubusercontent.com/render/math?math=\mu_{ct}"> and <img src="https://render.githubusercontent.com/render/math?math=\mu_{ht}">.**  
  
Please feel free to explore our final report for detailed analysis and result discussion. Available in file format of ipynb and html. 
