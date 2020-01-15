# Assignment 2019B-3: Mining over datasets

In this exercise you are called to apply data mining practices to existing datasets. You need to provide:

- one report, containing individual sections per dataset, which will describe the method, tools and results of the analysis, based on the (per-dataset) questions and  requirements, elaborated below. Each group will be assigned

- one (link to a) file which will contain all needed information to reproduce the analyses.

- one presentation, summarizing the work so that it can be presented in 10min.

The report should end with a brief mention (in bullet-points) of who in the group worked on what part of the analyses (and the corresponding time taken).

My evaluation will take into account:

- the clarity of writing and coherence of the report

- the completeness of the application parameters of the method(s) used

- the explanation of why the selected methods were appropriate

- the reproducibility of the process

## Dataset 1 [link](http://data.gov.gr/dataset/statistika-stoixeia-egklhmatikothtas)

and especially the file "Στατιστικά στοιχεία εγκληματικότητας 2016"

### Tasks

- Cluster the types of crimes based on the success of police in facing/solving them.
- Cluster the types of crimes and explain what each cluster represents.
- Identify outliers in crime types and explain what they represent/why they are outliers.
- Try to predict the super-category (e.g. ΕΠΙΚΡΑΤΕΙΑ/ΚΛΟΠΕΣ-ΔΙΑΡΡΗΞΕΙΣ, ...) of a record given only its numeric fields (τελ/να, απόπειρες, εξιχνιάσεις, ημεδαποί, αλλοδαποί), providing an explanation of the main factors for the decision and report the performance on a cross-validation evaluation.

## Dataset 2 [link](https://sourceforge.net/projects/moa-datastream/files/Datasets/Classification/covtypeNorm.arff.zip/download/)

### Tasks

- Provide an overview of the dataset size, features, and distribution of feature values.
- Select a random subset of 1000 instances from the dataset. Then identify the 20 features that are least useful in predicting the class and report them.
- Having removed the useless features, search for the top 3 associations with support of at least 0.1 and confidence of at least 0.5 and report them.

## Dataset 3 [link](http://users.iit.demokritos.gr/~ggianna/Tutorials%20and%20Presentations/2018%20-%20DataScience%20-%20DataMining/Datasets/Dataset3%20-%20Final.arff.zip)

Airlines Dataset Inspired in the regression dataset from Elena Ikonomovska 

- Provide an overview of the dataset size, features, and distribution of feature values.
- Describe the average delays per airport/airline.
- Identify and report the most prominent rules of association between delays and point of origin AND/OR point of arrival.
- Try to predict the delay given all other features and report the appropriate performance on cross-validation.
- Identify patterns/rules regarding delays and try to explain when delays should be expected, based on these patterns.

## Dataset 4 [link](https://github.com/aaronpenne/data_visualization/blob/master/religion/data/1952.xls)

Description: [link](https://github.com/aaronpenne/data_visualization/blob/master/religion/data/1952.txt)

### Tasks

- Summarize the data to help understand the overall picture of religious groups over the US.
- Which are the counties with the highest per person ratio of Orthodox Christian members?
- Can you find the 3 most extreme (outlier) counties with respect to the distribution of their churches across religions?
- Where would you create a cross-religion centre of discussion between religions to maximize its impact? Support the proposal based on data analysis results.
