# Earthquake_Prediction
## About The Project

[\* This was an academic project.]

Our project data is from a laboratory prediction of earthquake occurrences. The scientists use a model like the picture shown below. They wrapped the rock sample by a sensor frame. 

![Schematic diagram of experimental device](https://github.com/Runtao-Xue/Earthquake_Prediction/blob/main/Schematic%20diagram%20of%20experimental%20device.PNG)

The model will be putted in the high-temperature and high-pressure environment, just like the condition of crust movement of the Earth. Before they put the model into that environment, they added some ultrasonic transducer, which can recognize grain fault, around the wrapped cylinder. 

Each time the grain occurs on the surface or within the sample, the ultrasonic transducer will reflect a signal. And the scientists regard those signals as the sample signal of every time the mini-earthquake happening. 

Hence, we will get the acoustic signal data, which is the simulate sample of seismic signal, and the time to failure, the time interval between two mini-earthquake occurrences.

What we do is using these data to forecast the occurrence time of next mini-earthquake.

**Built With**

* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](https://matplotlib.org/)

* [Scikit-learn](https://scikit-learn.org/stable/)

**Data Source**

[LANL Earthquake Prediction](https://www.kaggle.com/c/LANL-Earthquake-Prediction/) From [kaggle.com](https://www.kaggle.com/)

## Getting Started

**Installation** 

1. Clone the repo

   ```
   https://github.com/Runtao-Xue/Earthquake_Prediction
   ```

2. Install packages

   ```python
   # In Jupyter Notebook
   !pip install numpy
   !pip install pandas
   !pip install seaborn
   !pip install matplotlib
   !pip install scikit-learn
   ```

## Contact

Runtao Xue - runtao.xue@gmail.com

Project Link: https://github.com/Runtao-Xue/Earthquake_Prediction

## Acknowledgements

* Professor: Yingjie Zhang
* Group member: Tong Liu, Jiexuan Du

