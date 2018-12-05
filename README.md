# Collaborative filtering
* Authors: ...
* Source: [Project subject](project-subject.pdf)

## Install environment:
### Requirement
If you work with anaconda, these following tools will be neccessary:
https://sigdelta.com/blog/how-to-install-pyspark-locally/

### Trouble shoot:
If you are having with JAVA_HOME is not correctly set (WINDOWS problem with space):\
* Download Java and install it.
* Add **System variables** the __JAVA_HOME__ with value __<path>/jdk1.8.0_xx__
* **Be careful**: if your __<path>__ contains **Program Files**, change it to **PROGRA~1**.
If you already have **Java**:
* Right click on **My Computer**/**Ce PC**, choose **Proprieties**.
* On the menu in the right click **Advance system parameters**, click **Environment variables**.
* Look in the **System variables** (the below one), in **JAVA_HOME** change **Program Files* to **PROGRA~1**

## Documents
* Explication sur map-reduce rdd: https://spark.apache.org/docs/2.2.0/rdd-programming-guide.html#rdd-operations
* Recommendation example: https://github.com/eBay/Spark/blob/master/examples/src/main/python/mllib/recommendation_example.py
* Tuto de spark pour beginner: https://spark.apache.org/docs/2.2.0/rdd-programming-guide.html
* Calculate avg in pyspark: https://stackoverflow.com/questions/29930110/calculating-the-averages-for-each-key-in-a-pairwise-k-v-rdd-in-spark-with-pyth
* 