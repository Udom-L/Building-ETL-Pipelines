# Building-ETL-Pipelines

![Fig](https://miro.medium.com/max/720/1*audZQV_S1dRMgtIs2QHfLg.png)
__Fig 1__: ETL Process (Ref: [Haq Nawaz](https://blog.devgenius.io/how-to-build-an-etl-pipeline-with-python-1b78407c3875))


> This ETL pipeline document is directly referenced from [Buliding ETL pipeline's article of freecodecamp](https://www.freecodecamp.org/news/sqlalchemy-makes-etl-magically-easy-ab2bd0df928/) written by Peter Gleeson. 

__The process of Data Integration is commonly referred to as “Extract-Transform-Load,” in order words, ETL in short.__

 
__This document will present how to build the data pipelines, how to design the data structure (schema), how to extract data from the database, how to transform their data format to be easily readible, and how to load their modified data into another database.__


___"This is the indispensible process of data science workflow: sourcing, cleaning, and storing of raw data in a form that can be used upstream."___

___"It is significant to design efficient, robust, and reliable ETL processes, or so called “Data pipelines.” Otherwise, an inefficient pipeline will make working with data slow and unproductive. A non-robust pipeline will break easily, leaving gaps"___ ([Peter Gleeson](https://www.freecodecamp.org/news/sqlalchemy-makes-etl-magically-easy-ab2bd0df928/)).

__"Therefore, ETL comes into the picture here to move data from the source, transform it and load it in order to an optimized database/storage layer for data analytics."__ ([Haq Nawaz](https://blog.devgenius.io/how-to-build-an-etl-pipeline-with-python-1b78407c3875))
 
