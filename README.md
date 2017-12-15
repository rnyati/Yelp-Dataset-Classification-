# Yelp Dataset Multi-label Classification 

**Yelp Dataset Multi-label Classification** shows star rating predictions on the business review count, total number of checkins, state and city where business is located. The app utilizes the Yelp Dataset for all businesses which includes over 1.2 million business attributes like hours, parking, availability, and ambience. Moreover, aggregated check-ins over time for each of the 156,000 businesses is also provided in different JSON files in the dataset.

Time spent: **50-60** hours spent in total

## Team Members:
Raghav Nyati - 819724367 - raghavnyati90@gmail.com
Kimaya Desai - 820884799 - kimaya.desai@gmail.com

The following models are studied:


## Presentation Walkthrough

Here's a walkthrough of implemented user stories:

https://prezi.com/view/jfrEzftylAF7HE6kbLSR/


## Notes

The various challenges that we realized with the YELP dataset are:
I. The YELP dataset is huge. It contains data of around 5 million reviews, 156,000 businesses. The dataset consists of 5 JSON files with over 1.2 million business attributes. The size of raw data ~5.5GB.
II. The biggest drawbacks of the huge dataset is time taken for processing and taking in account irrelevant information and thereby wasting the resources.
III. It is tricky to find the correlation between these attributes and analyzing the contributing factors.

## Open-source libraries used

- [scikit-learn](http://scikit-learn.org/stable/) - python library for machine learning algorithms
- [pandas](https://pandas.pydata.org/) - data Structure and data analysis tools for Python
- [seaborn](https://seaborn.pydata.org/) - visualization library based on matplotlib
- [numpy](http://www.numpy.org/) - fundamental package for scientific computing with Python
- [matplotlib](https://matplotlib.org/) - for visualization generating 2D images or graphical user interface toolkit

- [spark-mllib](https://spark.apache.org/docs/latest/ml-guide.html) - Spark's machine learning library

## License

    Copyright [2017] [raghav nyati]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
