# modeling-project

>GitHub Tricks: Upload Images & Live Demos

http://solutionoptimist.com/2013/12/28/awesome-github-tricks/

>Jupyter Lab project setup

https://florianwilhelm.info/2018/11/working_efficiently_with_jupyter_lab/

>Neural Network Projects with Python

https://github.com/PacktPublishing/Neural-Network-Projects-with-Python

>Confusion Matrix

https://www.python-course.eu/confusion_matrix.php

>How to delete condo envs

```
$ conda info --envs
$ conda remove --name modeling_project --all
```

>How to create project

```
$ conda create -n modeling_project python=3.6 jupyterlab pandas scikit-learn seaborn
$ conda activate modeling_project

$ conda install -c conda-forge pyscaffold
$ putup modeling_project

$ cd modeling_project

$ python setup.py develop
```

>How to check code quality in jupyter notebook
```
brew install jupyter
```

```
jupyter nbconvert \
    --to=script \
    --output-dir=./tmp/converted-notebooks/ \
    ./todo.ipynb
pylint ./tmp/converted-notebooks/todo.py
```
> https://stackoverflow.com/questions/50358327/using-pylint-in-ipython-jupyter-notebook

```
https://github.com/mattijn/pycodestyle_magicv
```

>Python Programming

http://sandbox.mc.edu/~bennet/python/code/


```
Travel

France
Paris 12/29/2019 - 01/04/2020  7days
Germany
Leipzig 01/05/2020  1day
Berlin 01/06/2020- 01/07/2020 2day
Austria
Vienna 01/08/2020-01/09/2020 2day

France
Paris 01/10/2020 - 01/12/2020  3days

Belgium
Brussels 01/13/2020 1day

Germany
Cologne 01/13/2020

Germany
Munich 01/14/2020 1day

Switzerland
Zurich 01/15/2020 1day

Italy
Milan 01/15/2020
Florence 01/16/2020 1day
Rome 01/16/2020

Greece
Athens 01/17/2020 - 01/18/2020  2days

Hungary
Budapest 01/19/2020 - 01/20/2020  2days
```

```
1. Amazon Review Classification
2. NYC Taxi Fare
3. Credit Card Transaction Fraud
4. Journal Paper Classification
5. EML
6. Fishing Email Detection
```

### developer tools
```
Alfred
```
> https://www.alfredapp.com/

> https://www.spectacleapp.com/

> https://github.com/ohmyzsh/ohmyzsh

> https://code.visualstudio.com/

> https://atom.io/

> https://www.sourcetreeapp.com/

> https://brew.sh/

```
Install conda via brew
```
> https://medium.com/ayuth/install-anaconda-on-macos-with-homebrew-c94437d63a37





```
Python

Can verify by typing python3 -V and pip3 -V. 
If using MacOS then do not remove/change the default Python version installed on your machine 
and rather add Python3. This site has good info on how to properly setup and install Python3 
on a Mac:
```
https://opensource.com/article/19/5/python-3-default-mac.


```
Data Pipeline
```
https://edu.51cto.com/

https://ke.qq.com/course/list/AWS?page=1

https://www.dataapplab.com/intl/

https://www.laioffer.com/zh/course/cloud-computing/

https://www.jiuzhang.com/course/43/

https://www.switchup.org/bootcamps/nyc-data-science-academy

http://www.bitbootcamp.com/Hadoop_PT.html

https://www.chinahadoop.cn/jobclass

https://www.laioffer.com/zh/course/ai-and-data-engineering/

https://dbaplus.cn/news-134-1863-1.html

https://zhuanlan.zhihu.com/p/33466906



```
Big Data
```
https://www.boxuegu.com/news/16.html



```
Shell

http://linuxcommand.org/lc3_lts0010.php
```

To Read

http://www.oreilly.com.cn/ideas/?p=1311

http://www.oreilly.com.cn/ideas/?p=1889

http://www.oreilly.com.cn/ideas/?p=945

http://www.oreilly.com.cn/ideas/?p=1228

https://www.oreilly.com/learning/introduction-to-local-interpretable-model-agnostic-explanations-lime

https://arxiv.org/abs/1703.04730

https://www.oreilly.com/radar/what-are-machine-learning-engineers/

```
Supporting Skills for Data Practitioners
Capital One software teams leverage a full suite of tools from cloud-based infrastructure to 
DevOps for continuous integration and continuous development. This learning path will provide 
an overview of key skills that augment the core data competencies to provide our aspiring data 
practitioners with a more holistic understanding of implementing sounds data solutions.

Learning Objectives
Explore supporting skills that are required to implement full-stack data engineering or data science solutions.
Acknowledge how a solid foundation in programming and software engineering is essential for being a successful data or practitioner. Recognize the foundational skills needed to help technical associates convey their outcomes from the data to executives or non-technical audiences. Identify how Capital One leverages the cloud to lower cost, increase security, and solve problems faster. See how DevOps practices and tools can increase an organization’s ability to deliver applications and services at high velocity. Distinguish between the high-level differences between SQL and NoSQL platforms.

Making data mean more through storytelling
Storytelling is the social and cultural activity of sharing stories, often with improvisation, 
theatrics, or embellishment and it becomes a key part while working with range of Data sets. 
This skill will help the technical folks to convey their observations and research from the data to the executives.

What is DevOps?
DevOps is the combination of cultural philosophies, practices, and tools that increases an 
organization’s ability to deliver applications and services at high velocity; evolving and 
improving products at a faster pace than organizations using traditional software development 
and infrastructure management processes.DevOps is about removing the barriers between two 
traditionally siloed teams, development and operations. With DevOps, the teams can work together 
to optimize the productivity of developers and the reliability of operations.
```

```
Data Warehousing
With the enterprise adoption of cloud-based technology, the data warehousing landscape has 
dramatically changed in recent years. Now, teams are able to obtain high performance, simple 
deployment, near infinite scaling, and easy administration at a fraction of the cost of 
on-premises solutions. At Capital One, teams are rapidly transitioning to cloud-based solutions 
in conjunction with the data transformation. This learning path aims to equip associates with 
an overview of data warehousing and guide learners to which platform best supports their business need.

```

```
Kafka:
https://www.infoq.com/articles/apache-kafka/
https://www.confluent.io/blog/event-streaming-platform-1
https://www.youtube.com/watch?v=mAgmwHHR6xY
http://cloudurable.com/blog/kafka-tutorial-kafka-from-command-line/index.html
```

```
Pyspark:
https://www.guru99.com/pyspark-tutorial.html
https://github.com/jubins/Spark-And-MLlib-Projects
https://github.com/AlexIoannides/pyspark-example-project
https://github.com/HyukjinKwon/pyspark-project-example
https://github.com/mgiridhar/PySpark-Projects
https://spark.apache.org/docs/latest/quick-start.html
https://codeday.me/bug/20190410/933667.html
```

```
AWS Cloud:
The cloud by allowing for scaling up and down ressources made it much easier to 
handle high peak batch jobs typical in data engineering. This however came at 
the cost of having to manage infrastructure and the scaling process through code.

```
https://medium.com/analytics-and-data/on-the-evolution-of-data-engineering-c5e56d273e37

```
EMR:
In a sentence, AWS Elastic MapReduce is a managed service for computing clusters.

EMR provides:
Managed clusters (so we don't need to install Spark and configure our clusters manually)
A variety of applications (Spark, Hadoop, Hive, Pig, etc.)
Easy integration with S3
Painless migration from Chef/Ansible/etc.-based clusters

An EMR cluster is a managed cluster consisting of master, core, and task nodes. 
The nodes themselves are EC2 instances.
When a cluster is created, the first thing it does is run bootstrap actions, 
which are scripts that install the Spark, Hadoop, etc. applications and perform 
other configurations. We can specify additional bootstrap actions (ISRM, Sphinx, etc.).
EMR runs jobs called steps. Steps are most commonly Spark jobs, but can also be any 
of the other applications available on the cluster, or shell scripts.
```
https://docs.aws.amazon.com/en_pv/emr/latest/ManagementGuide/emr-overview.html

```
CloudFormation:

```

```
AWS Lambda:

```

```
Data Engineer:
A holistic understanding of data is also important. “We need [data engineers] to 
know how the entire big data operation works and want [them] to look for ways to 
make it better,” says Blue. Sometimes, he adds, that can mean thinking and acting 
like an engineer and sometimes that can mean thinking more like a traditional 
product manager.

The move to the cloud had multiple implication for data engineers. The cloud abstracted 
physical limitations, for most users it meant that storage and compute was essentially 
infinite provided one can pay for it. Optimization previously done to keep business 
running waiting for new servers to be installed or upgraded needed not to be done anymore. 
So was the work previously done tasks scheduling to allocate the load across time due to 
ressource constraint. The cloud by allowing for scaling up and down ressources made it 
much easier to handle high peak batch jobs typical in data engineering. This however came 
at the cost of having to manage infrastructure and the scaling process through code.


What is often neglected is the amount of engineering required to make that data accessible. 
Simply using SQL is no longer an option for large, unstructured, or real-time data. 
Building a system that makes data usable becomes a monumental challenge for data engineers.

Here’s a brief glossary to describe data engineering and some common practices and technologies in the data engineering ecosystem.

Data Engineering: 
the task of building infrastructure and process for ingesting, processing, and 
aggregating data so that it can be displayed to users or made available to data scientists.

Data Science: 
the practice of using statistics, machine learning, and other tools to analyze data 
to discover trends and truths that can be used to provide business intelligence.

Batch Processing: 
processing large amounts of data at once. This is acceptable for smaller amounts 
of data and can be simpler in terms of engineering and deployment. Some batch processes 
can also be useful for “recomputing the world” when you want to analyze existing data in a new way.

Data Streaming: 
processing data in small chunks, one at a time, rather than processing all data at once. 
Streaming is necessary for processing infinite event streams. It’s also useful for processing 
large amounts of data, because it prevents memory overflows during processing and makes it 
easier to process data in a distributed manner or real-time manner.

Real-time: 
analyzing data and delivering results simultaneously so that stream output is always visible. 
For example, real-time analytics will mean that the system is constantly processing 
events (clicks, purchases, etc) and displaying the latest results in a user interface.

Distributed Data Processing: 
breaking up data into partitions so that large amounts of data can be processed by many machines simultaneously.

Cluster: 
several computers (or virtual machines) grouped together to perform a single task.

Scala: 
a programming language (like Ruby, Python, or JavaScript) which is fast and has 
become popular for data-focused tasks. Scala runs on the Java Virtual Machine, which 
is a high-performance engine for running languages like Scala that compile into bytecode.

Spark: 
a distributed computing engine for big data and data streams. Spark is a Scala-focused 
framework for data engineering and data science.

Kafka: 
a distributed commit log for data streams. Many of the large data systems deployed today use Kafka.

Within the Data Science universe, there is always overlap between the three professions. 
Data Engineers are often responsible for simple Data Analysis projects or for transforming 
algorithms written by Data Scientists into more robust formats that can be run in parallel. 
Data Analysts and Data Scientists need to learn basic Data Engineering skills, especially 
if they’re working in an early-stage startup where engineering resources are scarce.
```
https://www.oreilly.com/ideas/data-engineering-a-quick-and-simple-definition

https://www.oreilly.com/radar/data-engineers-vs-data-scientists/

https://www.oreilly.com/ideas/why-a-data-scientist-is-not-a-data-engineer

https://blog.insightdatascience.com/the-data-engineering-ecosystem-an-interactive-map-b682627c2534

https://blog.insightdatascience.com/ingestion-comparison-kafka-vs-kinesis-4c7f5193a7cd

http://www.oreilly.com.cn/ideas/?p=2138

```
The data has been cleaned up somewhat; for example:
The dataset is comprised of only English reviews.
All text has been converted to lowercase.
There is white space around punctuation like periods, commas, and brackets.
Text has been split into one sentence per line.
After unzipping the file, you will have a directory called “txt_sentoken” with 
two sub-directories containing the text “neg” and “pos” for negative and 
positive reviews. Reviews are stored one per file with a naming convention 
cv000 to cv999 for each neg and pos. 

Data Preparation
In this section, we will look at 3 things:
Separation of data into training and test sets.
Loading and cleaning the data to remove punctuation and numbers.
Prepare all reviews and save to file.

Duplicate Data
The preprocessor normalizes commands in order to reduce the probability of 
a data leakage problem that, in our setting, may result from using
almost-identical commands for training the model
and for validating it.

Imbalanced Data
Our dataset is very imbalanced, since the number
of clean commands is an order of magnitude larger
than that of malicious commands. In order to prevent
model bias towards the larger class, we constructed
the training set by duplicating each malicious command used for training 8 times so that the ratio of
clean/malicious training commands is 1:1. We preferred to handle imbalance this way rather than by
using under-sampling in order to avoid the risk of
over-fitting, which may result when a neural network
is trained using a small number of examples.

Monitering
PowerShell commands can be executed from memory,
hence identifying malicious commands and blocking
them prior to their execution is, in general, impractical. We therefore estimate that the most plausible deployment scenario of our detector would be as
a post-breach tool. In such a deployment scenario,
PowerShell commands that execute will be recorded
and then classified by our detector. Commands classified as malicious would generate alerts that should
trigger further investigation. In corporate networks,
this type of alerts is typically sent to a security information and event management (SIEM) system and
presented on a dashboard monitored by the organization’s CISO (chief information security officer) team.

AfterWork
There are several ways in which this work can be
extended. First, while we have implemented and
evaluated several deep-learning and traditional NLP
based classifiers, the design space of both types of
models is very large and a more comprehensive evaluation of additional techniques and architectures may
yield even better detection results.
Secondly, in this work we targeted the detection of
individual PowerShell commands that are executed
via the command-line. An interesting direction for
future work is to devise detectors for complete PowerShell scripts rather than individual commands. Such
scripts are typically longer than single commands and
their structure is richer, as they generally contain
multiple commands, functions and definitions. Effective detection of malicious scripts would probably
require significantly different input encoding and/or
detection models than those we used in this work.
Another interesting avenue for future work is to devise detectors that leverage the information collected
by Microsoft’s AntiMalware Scan Interface (AMSI)
[18]. As mentioned previously, AMSI is able to record
PowerShell commands (generated both statically and
dynamically) that are executed in run-time, so detectors may have more data to operate on. However,
although AMSI may be less vulnerable to many of
the obfuscation methods described in Section 2.1.1,
attackers may be able to find new ways of camouflaging the AMSI traces of their malicious commands.
```

```
Split into Train and Test Sets

After the model is developed, we will need to make predictions 
on new input data. This will require all of the same data preparation to 
be performed on those new data as is performed on the training data for the 
model.
We will ensure that this constraint is built into the evaluation of our models 
by splitting the training and test datasets prior to any data preparation. This 
means that any knowledge in the data in the test set that could help us better 
prepare the data (e.g. the words used) is unavailable in the preparation of 
data used for training the model. 
That being said, we will use the last 100 positive reviews and the last 100 
negative reviews as a test set (100 reviews) and the remaining 1,800 reviews as 
the training dataset. 
This is a 90% train, 10% split of the data.
```

```
Loading and Cleaning Reviews

Split tokens on white space.
Remove all punctuation from words.
Remove all words that are not purely comprised of alphabetical characters.
Remove all words that are known stop words.
Remove all words that have a length <= 1 character.
```

```
Multichannel CNN Model for Text Classification

After loading dataset, I fit a Keras Tokenizer on the training dataset. I will use this tokenizer to both define the vocabulary for the Embedding layer and encode the instances as integers.
```
