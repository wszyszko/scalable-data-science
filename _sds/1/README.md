# SDS 1x: Scalable Data Science 1x from Middle Earth

Scalable data science is a technical course in the area of Big Data, aimed at the needs of the
data industry.  This course uses
Apache Spark, a fast and general engine for large-scale data processing via databricks to compute
with datasets that won't fit in a single computer. The course will introduce Spark’s core concepts
via hands-on coding, including resilient distributed datasets and map-reduce algorithms, DataFrame
and Spark SQL on Catalyst, scalable machine-learning pipelines in MlLib and vertex programs using
the distributed graph processing framework of GraphX. We will solve instances of real-world big data
decision problems from various scientific domains.

This is being prepared by Raazesh Sainudiin and Sivanand Sivaram
with assistance from Paul Brouwers, Dillon George and Ivan Sadikov.

All course projects by seven enrolled and four observing students for Semester 1 of 2016 at UC, Ilam are part of this content.

## How to self-learn this content?

The 2016 instance of this [scalable-data-science course](http://lamastex.org/courses/ScalableDataScience/) finished on June 30 2016.

To learn Apache Spark for free try **databricks Community edition** by starting from [https://databricks.com/try-databricks](https://databricks.com/try-databricks).

All course content can be uploaded for self-paced learning by copying the following [URL for 2016/Spark1_6_to_1_3/scalable-data-science.dbc archive](https://raw.githubusercontent.com/raazesh-sainudiin/scalable-data-science/master/dbcArchives/2016/Spark1_6_to_1_3/scalable-data-science.dbc)
and importing it from the URL to your [free Databricks Community Edition](https://community.cloud.databricks.com).

The Gitbook version of this content is [https://www.gitbook.com/book/raazesh-sainudiin/scalable-data-science/details](https://www.gitbook.com/book/raazesh-sainudiin/scalable-data-science/details).

The browsable git-pages version of the content is [http://raazesh-sainudiin.github.io/scalable-data-science/](http://raazesh-sainudiin.github.io/scalable-data-science/).

## How to cite this work?

Scalable Data Science, Raazesh Sainudiin and Sivanand Sivaram, Published by GitBook [https://www.gitbook.com/book/raazesh-sainudiin/scalable-data-science/details](https://www.gitbook.com/book/raazesh-sainudiin/scalable-data-science/details), 787 pages, 30th June 2016.

## Supported By
[Databricks Academic Partners Program](https://databricks.com/academic) and [Amazon Web Services Educate](https://www.awseducate.com/microsite/CommunitiesEngageHome).

## Summary of Contents

* [Prelude of 2016 Version ](db/sdsBlog.md)

* [Week 1: Introduction to Scalable Data Science](db/week1/README.md)
    * [Scalable Data Science](db/week1/01_introduction/000_scalableDataScience.md)
    * [Why Spark?](db/week1/01_introduction/001_whySpark.md)
    * [Login to databricks](db/week1/01_introduction/002_loginToDatabricks.md)
    * [Scala Crash Course](db/week1/01_introduction/003_scalaCrashCourse.md)

* [Week 2: Introduction to Spark RDDs, Transformations and Actions and Word Count of the US State of the Union Addresses](db/week2/README.md)
    * [RDDs, Transformations and Actions](db/week2/02_SparkEssentials/004_RDDsTransformationsActions.md)
    * [HOMEWORK: RDDs, Transformations and Actions](db/week2/02_SparkEssentials/005_RDDsTransformationsActionsHOMEWORK.md)
    * [Word Count: US State of Union Addesses](db/week2/03_WordCount/006_WordCount.md)
    * [EXTRA_Word Count: ETL of US State of Union Addesses](db/xtraResources/sdsDatasets/scraperUSStateofUnionAddresses.md)

* [Week 3: Introduction to Spark SQL, ETL and EDA of Diamonds, Power Plant and Wiki CLick Streams Data](db/week3/README.md)
    * [Spark SQL Introduction](db/week3/04_SparkSQLIntro/007_SparkSQLIntroBasics.md)
        * [HOMEWORK: overview](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/001_overview_sqlProgGuide.md)
        * [HOMEWORK: getting started](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/002_gettingStarted_sqlProgGuide.md)
        * [HOMEWORK: data sources](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/003_dataSources_sqlProgGuide.md)
        * [HOMEWORK: performance tuning](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/004_performanceTuning_sqlProgGuide.md)
        * [HOMEWORK: distributed sql engine](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/005_distributedSqlEngine_sqlProgGuide.md)
    * [ETL and EDA of Diamonds Data](db/week3/05_SparkSQLETLEDA/008_DiamondsPipeline_01ETLEDA.md)
    * [ETL and EDA of Power Plant Data](db/week3/05_SparkSQLETLEDA/009_PowerPlantPipeline_01ETLEDA.md)
    * [ETL and EDA of Wiki Click Stream Data](db/week3/05_SparkSQLETLEDA/010_wikipediaClickStream_01ETLEDA.md)

* [Week 4: Introduction to Machine Learning - Unsupervised Clustering and Supervised Classification](db/week4/README.md)
    * [Introduction to Machine Learning](db/week4/06_MLIntro/011_IntroToML.md)
    * [Unsupervised Clustering of 1 Million Songs via K-Means in 3 Stages](db/week4/07_UnsupervisedClusteringKMeans_1MSongs/012_1MSongsKMeans_Intro.md)
        * [Stage 1: Extract-Transform-Load](db/week4/07_UnsupervisedClusteringKMeans_1MSongs/013_1MSongsKMeans_Stage1ETL.md)
        * [Stage 2: Explore](db/week4/07_UnsupervisedClusteringKMeans_1MSongs/014_1MSongsKMeans_Stage2Explore.md)
        * [Stage 3: Model](db/week4/07_UnsupervisedClusteringKMeans_1MSongs/015_1MSongsKMeans_Stage3Model.md)
    * [Supervised Classification of Hand-written Digits via Decision Trees](db/week4/08_SupervisedLearningDecisionTrees/016_DecisionTrees_HandWrittenDigitRecognition.md)

* [Week 5: Introduction to Non-distributed and Distributed Linear Algebra and Applied Linear Regression](db/week5/README.md)
    * [Linear Algebra Introduction](db/week5/09_LinearAlgebraIntro/017_LAlgIntro.md)
        * [HOMEWORK: breeze linear algebra cheat sheet](db/xtraResources/LinearAlgebra/LAlgCheatSheet.md)
    * [Linear Regression Introduction](db/week5/10_LinearRegressionIntro/018_LinRegIntro.md)
    * [Distributed Linear Algebra for Linear Regression Introduction](db/week5/10_LinearRegressionIntro/019_DistLAlgForLinRegIntro.md)
        * [HOMEWORK: Spark Data Types for Distributed Linear Algebra](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/000_dataTypesProgGuide.md)
            * [Local Vector](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/001_LocalVector.md)
            * [Labeled Point](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/002_LabeledPoint.md)
            * [Local Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/003_LocalMatrix.md)
            * [Distributed Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/004_DistributedMatrix.md)
            * [Row Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/005_RowMatrix.md)
            * [Indexed Row Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/006_IndexedRowMatrix.md)
            * [Coordinate Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/007_CoordinateMatrix.md)
            * [Block Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/008_BlockMatrix.md)
    * [Power Plant Pipeline: Model, Tune, Evaluate](db/week5/11_MLlibModelTuneEvaluate/020_PowerPlantPipeline_02ModelTuneEvaluate)

* [Week 6: Introduction to Spark Streaming, Twitter Collector, Top Hashtag Counter and Streaming Model-Prediction Server](db/week6/README.md)
    * [Introduction to Spark Streaming](db/week6/12_SparkStreaming/021_SparkStreamingIntro.md)
    * [Tweet Collector - broken down](db/week6/12_SparkStreaming/022_TweetCollector.md)
    * [Tweet Collector - Generic](db/week6/12_SparkStreaming/022_TweetGenericCollector.md)
    * [Tweet Hashtag Counter](db/week6/12_SparkStreaming/023_TweetHashtagCount.md)
    * [Streaming Model-Prediction Server, the Full Powerplant Pipeline](db/week6/13_StreamingMLlib_ModelTuneEvaluateDeploy/024_PowerPlantPipeline_03ModelTuneEvaluateDeploy.md)

* [Week 7: Probabilistic Topic Modelling via Latent Dirichlet Allocation and Intro to XML-parsing of Old Bailey Online](db/week7/README.md)
    * [Probabilistic Topic Modelling](db/week7/14_ProbabilisticTopicModels/025_LDA_20NewsGroupsSmall.md)
    * [HOMEWORK: Introduction to XML-parsing of Old Bailey Online](db/xtraResources/OldBaileyOnline/OBO_LoadExtract.md)

* [Week 8: Graph Querying in GraphFrames and Distributed Vertex Programming in GraphX](db/week8/README.md)
    * [Introduction to GraphFrames](db/week8/15_GraphX/026_GraphFramesUserGuide.md)
    * [HOMEWORK: On-Time Flight Performance with GraphFrames](db/week8/15_GraphX/028_OnTimeFlightPerformance.md)

* [Week 9: Deep Learning, Convolutional Neural Nets, Sparkling Water and Tensor Flow](db/week9/README.md)
    * [Deep Learning, A Crash Introduction](db/week9/16_Deep_learning/030_Deep_learning.md)
    * [H2O Sparkling Water](db/week9/17_SparklingWater/031_H2O_sparkling_water.md)
    * [H2O Sparkling Water: Ham or Spam Example](db/week9/17_SparklingWater/032_Deep_learning_ham_or_spam.md)
    * [Setting up TensorFlow Spark Cluster](db/week9/18_sparklingTensorFlow/033_SetupCluster_SparkTensorFlow.md)
    * [Scalable Object Identification with Sparkling TensorFlow](db/week9/18_sparklingTensorFlow/034_SampleML_SparkTensorFlow.md)

* [Week 10: Scalable Geospatial Analytics with Magellan](db/week10/README.md)
    * [What is Scalable Geospatial Analytics](db/week10/035_ScalableGeoSpatialComputing.md)
    * [Introduction to Magellan for Scalable Geospatial Analytics](db/week10/036_IntroductionToMagellan.md)

* [Week 11 and 12: Student Projects](db/studentProjects/README.md)
    * [Student Projects](db/studentProjects/00_studentPresentations.md)
    * [Dillon George, Scalable Geospatial Algorithms](db/studentProjects/01_DillonGeorge/README.md)
        * [Scalable Spatio-temporal Constraint Satisfaction](db/studentProjects/01_DillonGeorge/037_MSR_BeijingTaxiTrajectories_MagellanQueries.md)
        * [Map-matching](db/studentProjects/01_DillonGeorge/038_UberMapMatchingAndVisualization.md)
        * [OpenStreetMap to GraphX](db/studentProjects/01_DillonGeorge/039_OSMMap2GraphX.md)
    * [Akinwande Atanda, Twitter Analytics](db/studentProjects/02_AkinwandeAtanda/README.md) 
        * [Chapter_Outline_and_Objectives](db/studentProjects/02_AkinwandeAtanda/Tweet_Analytics/039_TA00_Chapter_Outline_and_Objectives.md)
        * [Unfiltered_Tweets_Collector_Set-up](db/studentProjects/02_AkinwandeAtanda/Tweet_Analytics/040_TA01_01_Unfiltered_Tweets_Collector_Set-up.md)
        * [Filtered_Tweets_Collector_Set-up_by_Keywords_and_Hashtags](db/studentProjects/02_AkinwandeAtanda/Tweet_Analytics/041_TA01_02_Filtered_Tweets_Collector_Set-up_by_Keywords_and_Hashtags.md)
        * [Filtered_Tweets_Collector_Set-up_by_Class](db/studentProjects/02_AkinwandeAtanda/Tweet_Analytics/042_TA01_03_Filtered_Tweets_Collector_Set-up_by_Class.md)
        * [ETL_Tweets](db/studentProjects/02_AkinwandeAtanda/Tweet_Analytics/043_TA02_ETL_Tweets.md)
        * [binary_classification](db/studentProjects/02_AkinwandeAtanda/Tweet_Analytics/045_TA03_02_binary_classification.md)
        * [binary_classification_with_Loop](db/studentProjects/02_AkinwandeAtanda/Tweet_Analytics/046_TA03_03_binary_classification_with_Loop.md)
        * [binary_classification_with_Loop_TweetDataSet](db/studentProjects/02_AkinwandeAtanda/Tweet_Analytics/047_TA03_04_binary_classification_with_Loop_TweetDataSet.md)
	
    * [Yinnon Dolev, Deciphering Spider Vision](db/studentProjects/03_YinnonDolev/048_decipheringSpiderVision.md)
    * [Xin Zhao, Higher Order Spectral CLustering](db/studentProjects/04_XinZhao/049_Introduction_HighOrderSpectralClustering.md)
        * [Case-study](db/studentProjects/04_XinZhao/050_CaseStudy_HighOrderSpectralClustering.md)
    * [Shanshan Zhou, Exploring EEG](db/studentProjects/05_ShanshanZhou/051_EEG_Explore.md)
    * [Shakira Suwan, Change Detection in Random Graph Series](db/studentProjects/06_ShakiraSuwan/052_ChangeDetectionInRandomGraphSeries.md)
    * [Matthew Hendtlass, The ATP graph](db/studentProjects/07_MatthewHendtlass/053_The_ATP_graph.md)
        * [Yuki_Katoh_GSW_Passing_Analysis](db/studentProjects/07_MatthewHendtlass/054_Yuki_Katoh_GSW_Passing_Analysis.md)
    * [Andrey Konstantinov, Keystroke Biometric](db/studentProjects/08_AndreyKonstantinov/055_KeystrokeBiometric.md)
    * [Dominic Lee, Random Matrices](db/studentProjects/09_DominicLee/056_RandomMatrices.md)
        * [References](db/studentProjects/09_DominicLee/057_QuickReferences.md)
    * [Harry Wallace, Movie Recommender](db/studentProjects/10_HarryWallace/058_MovieRecommender.md)
    * [Ivan Sadikov, Reading NetFlow Logs](db/studentProjects/11_IvanSadikov/059_SparkNetFlow.md)

* [Extra Resources](db/xtraResources/README.md)
    * [AWS Educate](db/xtraResources/awsEducate/sharing.md)
    * Databricksified Spark SQL Programming Guide 1.6
        * [overview](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/001_overview_sqlProgGuide.md)
        * [getting started](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/002_gettingStarted_sqlProgGuide.md)
        * [data sources](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/003_dataSources_sqlProgGuide.md)
        * [performance tuning](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/004_performanceTuning_sqlProgGuide.md)
        * [distributed sql engine](db/xtraResources/ProgGuides1_6/sqlProgrammingGuide/005_distributedSqlEngine_sqlProgGuide.md)
    * [Linear Algebra Cheat Sheet](db/xtraResources/LinearAlgebra/LAlgCheatSheet.md)
    * Databricksified Data Types in MLLib Programming Guide 1.6 
        * [Local Vector](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/001_LocalVector.md)
        * [Labeled Point](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/002_LabeledPoint.md)
        * [Local Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/003_LocalMatrix.md)
        * [Distributed Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/004_DistributedMatrix.md)
        * [Row Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/005_RowMatrix.md)
        * [Indexed Row Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/006_IndexedRowMatrix.md)
        * [Coordinate Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/007_CoordinateMatrix.md)
        * [Block Matrix](db/xtraResources/ProgGuides1_6/MLlibProgrammingGuide/dataTypes/008_BlockMatrix.md)
    * [Introduction to XML-parsing of Old Bailey Online](db/xtraResources/OldBaileyOnline/OBO_LoadExtract.md)

## Contribute

All course content is currently being pushed by Raazesh Sainudiin after it has been tested in
Databricks cloud (mostly under Spark 1.6 and some involving Magellan under Spark 1.5.1).

The markdown version for `gitbook` is generated from the Databricks `.scala`, `.py` and other source codes.
The gitbook is not a substitute for the Databricks notebooks available in the Databricks cloud. The following issues need to be resolved:

* need to find a stable solution for the output of various databricks cells to be shown in gitbook, including those from `display_HTML` and `frameIt` with their in-place embeds of web content.

Please feel free to fork the github repository: 

* [https://github.com/raazesh-sainudiin/scalable-data-science](https://github.com/raazesh-sainudiin/scalable-data-science).

Furthermore, due to the anticipation of Spark 2.0 this mostly Spark 1.6 version could be enhanced with a 2.0 version-specific upgrade. 

Please send any typos or suggestions to raazesh.sainudiin@gmail.com

Please read a note on [babel](https://github.com/raazesh-sainudiin/scalable-data-science/blob/master/babel/README.md) to understand how the gitbook is generated from the `.scala` source of the databricks notebook.


Raazesh Sainudiin, 
Laboratory for Mathematical Statistical Experiments, Christchurch Centre 
and School of Mathematics and Statistics, 
University of Canterbury, 
Private Bag 4800, 
Christchurch 8041, 
Aotearoa New Zealand 

Sun Jun 19 21:59:19 NZST 2016
