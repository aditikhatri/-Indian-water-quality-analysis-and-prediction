
# Indian water quality analysis and prediction

With fast economic growth and increased urbanization, water pollution has become
grimmer. Understanding the issues and patterns of water quality is also critical for water
pollution reduction and regulation. Water quality prediction is important for water quality preparation and
regulation. Strategies for the prevention and regulation of water contamination can be
developed by predicting future changes in water safety at varying levels of contamination
and devising rational strategies to prevent and regulate water contamination.

## Objective

Water of low quality can also be economically challenging, given that resources must
be diverted to upgrade water delivery infrastructure any time a problem arises. 
**Achieving precise predictions of changes in water quality
can immensely improve the efficiency of aquaculture.** In general, water quality data are
pre-processed before water quality parameters are predicted. Thus, this section consists
of two stages. **The first stage consists of the pre-treatment of water quality data and the
performance of correlation analysis between different water quality parameters.**

Machine learning have aided in the monitoring of water quality systems by predicting
changes in water quality . They can immensely improve the efficiency of aquaculture.


## Data set
 The datasets employed to conduct the research were acquired from different locations
in India and contained 1679 simples from 666 different sources of rivers and lakes in
the country. The data was collected between 2005 and 2014 .

The link to the datasets is attached.
The datasets include eight important parameters: DO, pH, conductivity, biological oxygen
demand, nitrate, fecal coliform, temp, and total coliform

https://www.kaggle.com/anbarivan/indian-waterquality-data




  
## Calculations

The **WQI**, which is calculated using several parameters that affect WQ , was used
to measure water quality.
![image](https://user-images.githubusercontent.com/63184114/135417379-20c3cd2f-e17e-40c2-bbcb-ec43c5252be0.png)


where N denotes the total number of parameters included in the `WQI` formula, qi denotes
the quality estimate scale for each parameter i calculated by Formula (2), and wi denotes
the unit weight of each parameter in Formula (3)

![image](https://user-images.githubusercontent.com/63184114/135417428-8fdddc1a-aee7-46f8-866e-6b3b2730f8a8.png)

where Vi is a measured value that refers to the water samples tested, VIdeal is an ideal value
and indicates pure water (0 for all parameters except OD = 14.6 mg/L and pH = 7.0), and
Si is a standard value recommended for parameter i, taken from internet.

![image](https://user-images.githubusercontent.com/63184114/135417506-8c34d164-036b-41fa-a8b9-39b9f2657bf9.png)

where K denotes the constant of proportionality, which is calculated using the following
formula:

![image](https://user-images.githubusercontent.com/63184114/135417566-35347cc4-0b6d-4ee0-bbde-2b379fe1f850.png)

  
## Pipeline of the Project

![image](https://user-images.githubusercontent.com/63184114/135414021-b2247177-3b6c-413e-a6d3-8050ece44ff6.png)




  
## Output

Ml model can be developed to predict `WQI` by selecting
important parameters from a standard dataset.Precited using machine learning model .

![image](https://user-images.githubusercontent.com/63184114/135418099-d9ad39b4-48b6-4643-af97-7e8e3f8f97f9.png)

The system will help reduce people’s consumption of poor-quality water and
consequently curtail horrific diseases such as typhoid and diarrhea. In this case, our
application can improve water pollution in different water bodies. The robustness
and efficiency of the proposed model in predicting WQI can be examined in future
works.

  
## References

- https://ieeexplore.ieee.org/document/7944943/metrics#metrics

+ https://www.mdpi.com/2071-1050/13/8/4259/pdf
  
