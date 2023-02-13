---
layout: post
title:  "Data science learning resources"
categories: [ Resource, Data-Science ]
image: assets/images/6.jpg
tags: featured
---

cience is a popular field and garners a lot of interest. Whether you’re looking to become a data scientist or leverage data science skills in your current role, “where should I start?” and “what are some good books?” are common questions. Data science is also a broad field, with many skill areas to continue growing in your career. Given this, it can be helpful to put together a learning plan. In this article, we hope to share some worthwhile resources that we’ve used to build a data science foundation.

In an [earlier article](/data-science-at-microsoft/the-data-scientist-toolbelt-985c86e54fd3?source=friends_link&sk=af1dd8797c9e570f3fbfc7da88c01b34), we shared a list of skills to be an effective data scientist. In this one, we provide resources, including ones such as courses, books, and papers, to help develop those skills. In particular, we expand here on the technical skills section of the prior article, given that business and domain resources depend on the particular domain context.

As you dive into data science courseware, you’ll see that it extends from a variety of academic departments, and that various fields of study have contributed to current techniques. Data science is a diverse, interdisciplinary field. Here is a Venn diagram to illustrate how it brings math, statistics, computer science, and domain knowledge together:

![](https://miro.medium.com/max/1155/1*mMQttXFS-jI1YCg8WPGCVw.png)

_Adapted from and with credit to “Data science concepts you need to know! Part 1,” by Michael Barber, on_ [_Medium.com_](https://towardsdatascience.com/introduction-to-statistics-e9d72d818745)_._

Covered topics
==============

Here are the topic areas we cover in this article, starting at the core and working outward, in this conceptual view:

![](https://miro.medium.com/max/1155/1*5XtOanCVSPNUPzTtCaOd4Q.png)

Here are quick links to each section:

*   [Statistical concepts and techniques](#1106)
*   [Programming languages](#2352) (SQL, Python, R, and Kusto)
*   [Data analytics and forecasting](#b5aa)
*   [Machine Learning and Deep Learning](#515c)
*   [Experimentation and causal inference](#33c0)
*   [Data visualization and communication](#a2a9)
*   [Communities, podcasts, datasets, and events](#2bfc)

Statistical concepts and techniques
===================================

Data scientists must be familiar with statistics as they collect data and information and use it to investigate problems, analyze and forecast trends, conduct significance testing, design experiments, and inform business decision-making. Here are some good resources for building a foundation in statistics:

*   Course | [Statistics with R Specialization](https://www.coursera.org/specializations/statistics): This online course helps in mastering statistics with R.
*   Book | [Practical Statistics for Data Scientists: 50 Essential Concepts](https://www.oreilly.com/library/view/practical-statistics-for/9781491952955/): A practical guide that explains how to apply various statistical methods to data science.
*   Book | [The Elements of Statistical Learning: Data Mining, Inference, and Prediction](https://www.springer.com/gp/book/9780387848570): This book helps readers develop a deeper understanding of statistical learning and requires some mathematical and statistical sophistication.
*   Book | [An introduction to Statistical Methods and Data Analysis](https://www.cengage.com/c/an-introduction-to-statistical-methods-and-data-analysis-7e-ott/9781305269477PF/): This book offers a broad overview of statistical methods, providing research studies and examples that connect the statistical concepts to data analysis problems data scientists may encounter in daily work.

Programming languages (SQL, Python, R, and Kusto)
=================================================

As a data scientist, you can choose from a number of programming languages that are useful in your work. SQL is very important to learn because it allows you to query the data in a structured database. Python is particularly popular among data scientists today due to its wide range of uses across domains, such as data collection and cleaning, data visualization, Machine Learning, and Deep Learning. R is another popular language ideal for data science, big data, and Machine Learning. Kusto is a query language for Azure Data Explorer and related services that has a simplified syntax. Here are some training materials to learn these programming languages and their applications to data science:

SQL
---

*   Course | [LinkedIn Learning Path for SQL](https://www.linkedin.com/learning/paths/master-sql-for-data-science?u=3322): This pathway includes various courses on leveraging SQL in data science projects.
*   Course | [SQL for Data Science](https://www.coursera.org/learn/sql-for-data-science): A Coursera course that teaches fundamental SQL query and data manipulation.
*   Tutorial | [W3 Schools SQL Tutorial](https://www.w3schools.com/sql/): This set of online lessons provides hands-on practice with SQL queries.

Python
------

*   Course | [Data Scientist with Python](https://www.datacamp.com/tracks/data-scientist-with-python): DataCamp track consisting of several courses covering introductory and intermediate programming in Python, usage of pandas and matplotlib libraries, and much more.
*   Course | [Python for Data Science](https://www.coursera.org/learn/python-for-applied-data-science-ai): Coursera course that introduces users to foundational Python programming concepts.
*   Course | [LinkedIn Learning Path for Python](https://www.linkedin.com/learning/search?keywords=python&sortBy=POPULARITY&u=3322): This pathway includes various Python courses ranging from introductory programming topics to deep learning and neural networks.
*   Course | [edX: Computational Thinking using Python](https://www.edx.org/xseries/mitx-computational-thinking-using-python?index=product&queryID=0bbc2ddef4f5f90e992baba275ee31bb&position=2): This learning program covers programming, data structures, computational thinking, data science, and algorithms related to Python.
*   Book | [Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython](https://www.oreilly.com/library/view/python-for-data/9781491957653/): This title teaches how to clean and manipulate data using popular libraries.

R
-

*   Book | [An Introduction to Statistical Learning with Applications in R](http://faculty.marshall.usc.edu/gareth-james/): This volume interprets statistical concepts with R programming and is publicly available now.
*   Course | [Learn R with DataCamp](https://www.datacamp.com/learn/r-programming): This course offers several tracks for R programming, ranging from data manipulation to statistical inference.
*   Course | [R Programming](https://www.datacamp.com/learn/r-programming): This is an introductory course to programming R, covering topics like reading data and writing functions.
*   Course | [LinkedIn Learning Path for R](https://www.linkedin.com/learning/topics/r?u=3322): This pathway covers a range of R-related topics including cleaning data, forecasting, and text analytics.

Kusto
-----

*   Reference | [Azure Data Explorer/Kusto Reference Documentation](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/): This is an online reference for Kusto query language syntax and functions.
*   Course | [KQL from Scratch](https://www.pluralsight.com/courses/kusto-query-language-kql-from-scratch?clickid=SbiX3GTd9xyLT5gwUx0Mo3ZXUkBw2OyZr3mLys0&irgwc=1&mpid=2003851&aid=7010a000001xAKZAA2&utm_medium=digital_affiliate&utm_campaign=2003851&utm_source=impactradius): This is an introductory course on fundamental Kusto syntax and function principles.

Data analytics and forecasting
==============================

Data analytics and forecasting are fundamental tools for data scientists. As technology generates vast and growing amounts of data, analytics and forecasting are core steps to explore business opportunities, identify key trends, and find insights to enable data-driven decision making.

*   Course | [Data Science with DataBricks for Data Analyst Specialization](https://www.coursera.org/specializations/data-science-with-databricks-for-data-analysts)
*   Course | [Data Science Fundamentals for Data Analyst](https://www.coursera.org/learn/data-science-fundamentals-for-data-analysts)
*   Course | [Applied Data Science for Data Analysts](https://www.coursera.org/learn/applied-data-science-for-data-analysts)
*   Course| [MicroMasters program from Georgia Tech](https://www.edx.org/micromasters/gtx-analytics-essential-tools-and-methods): This course covers fundamental data science programming in Python, R, and SQL, as well as modeling and data pipelines. (Credit can be counted toward Georgia Tech’s Master’s in Analytics program.)
*   Course | [Forecasting in R | DataCamp](https://learn.datacamp.com/courses/forecasting-in-r)
*   Course | [Sequences, Time Series and Prediction | Coursera](https://www.coursera.org/learn/tensorflow-sequences-time-series-and-prediction)
*   Book | [Forecasting: Principles and Practice (3rd ed) (otexts.com)](https://otexts.com/fpp3/)

Machine Learning and Deep Learning
==================================

Machine Learning includes algorithms that parse data, learn from that data, and then apply what they’ve learned to make informed decisions. Deep Learning is considered an evolution of Machine Learning. It uses a programmable neural network that enables machines to make accurate decisions without help from humans. The following are helpful resources to grow skills in Machine Learning and Deep Learning.

Machine Learning foundations
----------------------------

*   Course | [Machine Learning by Stanford University | Coursera](https://www.coursera.org/learn/machine-learning): Andrew Ng’s popular course that introduces supervised and unsupervised learning, as well as Machine Learning best practices. (Offered to the public through Coursera and to Stanford students as part of the university’s curriculum.)
*   Course | [CalTech: Machine Learning (Yaser Abu-Mostafa)](https://home.work.caltech.edu/telecourse.html): This course is introductory but less friendly for novices. It covers most of the same topics as Ng’s course, but more deeply and with a more theoretical approach, and is recommended for students and practicing data scientists.
*   Course | [Reinforcement Learning](https://www.coursera.org/specializations/reinforcement-learning): Set of four courses covering various fundamental concepts and includes a hands-on project.
*   Course | LinkedIn: [Machine Learning and AI Foundations](https://www.lynda.com/Data-Science-tutorials/Machine-Learning-Essential-Training-Value-Estimations/548594-2.html)
*   Course | LinkedIn: [Become a Machine Learning Specialist](https://www.linkedin.com/learning/paths/become-a-machine-learning-specialist?u=3322)
*   Book | [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python)
*   Course | [Improving your Model Performance — ML Strategy (1) | Coursera](https://www.coursera.org/lecture/machine-learning-projects/improving-your-model-performance-4IPD6)
*   Course | [What is Predictive Model Performance Evaluation | by divya singh | Medium](/@divyacyclitics15/what-is-predictive-model-performance-evaluation-8ef117ae0e40)

Deep Learning
-------------

*   Course | [Deep Learning from Coursera: Five courses to learn the foundations of Deep Learning, understand how to build neural networks with TensorFlow, and how to lead successful Machine Learning projects.](https://www.coursera.org/specializations/deep-learning)
*   Course | [Deep Neural Networks with Pytorch](https://www.coursera.org/learn/deep-neural-networks-with-pytorch): Similar to the course above, but using PyTorch.
*   Course | [Hugo Larochelle-Neural Networks](http://info.usherbrooke.ca/hlarochelle/neural_networks/description.html): Graduate-level course covering topics such as Deep Learning, conditional random fields, autoencoders, and more.
*   Course | [Carnegie Mellon’s Neural Networks for NLP](http://phontron.com/class/nn4nlp2020/schedule.html): This class starts with a brief overview of neural networks, and then spends the majority of the class demonstrating how to apply neural networks to natural language problems.
*   Reference | [Deep Learning Cheat Sheet — Stanford](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-deep-learning#nn): Concise explanations of neural networks.
*   Reference | [Neural Network Zoo:](https://www.asimovinstitute.org/neural-network-zoo-prequel-cells-layers/) Cheat sheet for neural network architectures.
*   Course | [Deep Learning with PyTorch: Build a NN](https://www.coursera.org/projects/deep-learning-with-pytorch-build-a-neural-network) (1 hour; guided project)
*   Course | [Getting started with PyTorch](https://www.coursera.org/projects/pytorch-beginner) (1.5 hours; guided project)
*   Course | [Getting started with PyTorch (2)](https://www.coursera.org/projects/getting-started-pytorch) (2 hours; guided project)
*   Course | [Detecting Covid-19 with chest X-ray using PyTorch](https://www.coursera.org/projects/covid-19-detection-x-ray) (2 hours; guided project)

ML Ops, data engineering and more
---------------------------------

*   Course | [Distributed computing with Spark SQL](https://www.coursera.org/learn/spark-sql) (13 hours)
*   Course | [Introduction to High-Performance and Parallel Computing](https://www.coursera.org/learn/introduction-high-performance-computing) (18 hours)
*   Course | [Custom and Distributed Training with Tensorflow](https://www.coursera.org/learn/custom-distributed-training-with-tensorflow) (approximately 24 hours)
*   Course | [Perform Data Science with Azure Databricks](https://docs.microsoft.com/en-us/learn/paths/perform-data-science-azure-databricks/?source=learn)
*   Course | [Data Engineering with Azure Databricks](https://docs.microsoft.com/en-us/learn/paths/data-engineer-azure-databricks/)
*   Course | [Distributed Programming on the Cloud](https://docs.microsoft.com/en-us/learn/paths/cmu-cloud-computing-distributed-programming/)
*   Book | [Data Science Solutions on Azure: Tools and Techniques Using Databricks and MLOps](https://learning.oreilly.com/library/view/data-science-solutions/9781484264058/)
*   Book | [Beginning Apache Spark Using Azure Databricks: Unleashing Large Cluster Analytics in the Cloud](https://learning.oreilly.com/library/view/beginning-apache-spark/9781484257814/)
*   Course | [Fast-ai course: Practical Deep Learning for Coders](https://course19.fast.ai/) (See Part 1 & Part 2)
*   Book | [Fast-AI Book](https://github.com/fastai/fastbook) (Corresponding to the course above)
*   Course | [Getting Started with Python Concurrency](https://www.pluralsight.com/courses/python-concurrency-getting-started) (approximately 2.5 hours)
*   Article | [Python Concurrency: The Tricky Bits](https://python.hamel.dev/concurrency/?s=03)

Experimentation and causal inference
====================================

Experimentation and causal inference are designed to identify causal relationships among variables. Given the importance of understanding causal drivers to ensure the right data-driven decisions, these techniques have been gaining increased adoption among data scientists in the industry. These resources provide great learning opportunities on these topics:

Experimentation
---------------

*   Book | [Experimentation Works](https://www.hbs.edu/faculty/Pages/item.aspx?num=57045): Covers key tenets of driving an experimentation culture, including case studies from tech company examples.
*   Book | [Trustworthy Online Controlled Experiments (A Practical Guide to A/B Testing)](https://www.cambridge.org/core/books/trustworthy-online-controlled-experiments/D97B26382EB0EB2DC2019A7A7B518F59): Great resource for best practices in experiment design and analysis, using learnings from real-world examples.
*   Course | [EXP platform](https://exp-platform.com/2017abtestingtutorial/)
*   Course | [Udacity](https://www.udacity.com/course/ab-testing--ud257)
*   Course | [Coursera](https://www.coursera.org/learn/crash-course-in-causality)

Causal inference
----------------

*   Course | [Data Science with DataBricks for Data Analyst Specialization](https://www.coursera.org/specializations/data-science-with-databricks-for-data-analysts)
*   Course | [A Crash Course in Causality](https://www.coursera.org/learn/crash-course-in-causality)
*   Course | [Introduction to Causal Inference](https://www.bradyneal.com/causal-inference-course)
*   Book | [The Book of Why: The New Science of Cause and Effect](https://www.basicbooks.com/titles/judea-pearl/the-book-of-why/9780465097616/)
*   Book | [Elements of Causal Inference](https://mitpress.mit.edu/books/elements-causal-inference)
*   Book | [Causal Inference in Statistics: A Primer](https://www.wiley.com/en-us/Causal+Inference+in+Statistics%3A+A+Primer-p-9781119186847)
*   Book | [Introduction to Causal Inference](https://www.bradyneal.com/Introduction_to_Causal_Inference-Dec17_2020-Neal.pdf) (textbook that accompanies course of the same name)
*   Paper | [Causal Structure Learning and Inference: A Selective Review](https://stat.ethz.ch/Manuscripts/buhlmann/causal-review-2013v3.pdf)
*   Paper | [A Crash Course in Good and Bad Controls](https://ftp.cs.ucla.edu/pub/stat_ser/r493.pdf)
*   Paper | [On Identifying Causal Effects](https://faculty.sites.iastate.edu/jtian/files/inline-files/tian-shpitser-2009.pdf)
*   Methodology | [https://arxiv.org/abs/2007.10979](https://arxiv.org/abs/2007.10979)
*   Methodology | [https://github.com/microsoft/dowhy](https://github.com/microsoft/dowhy)
*   Methodology | [https://github.com/microsoft/EconML](https://github.com/microsoft/EconML)
*   Methodology | [https://github.com/uber/causalml](https://github.com/uber/causalml)
*   Research | Meta learners: Künzel, Sören R., et al. “Metalearners for estimating heterogeneous treatment effects using machine learning.” _Proceedings of the National Academy of Sciences_ 116.10 (2019): 4156–4165.
*   Research | Double Machine Learning: V. Chernozhukov, D. Chetverikov, M. Demirer, E. Duflo, C. Hansen, and a. W. Newey. _Double Machine Learning for Treatment and Causal Parameters_. ArXiv e-prints, July 2016.
*   Research | Estimation methods with instruments: W. K. Newey and J. L. Powell. “Instrumental variable estimation of nonparametric models.” _Econometrica_, 71 (5): 1565–1578, 2003. Also: Jason Hartford, Greg Lewis, Kevin Leyton-Brown, and Matt Taddy. Deep IV: “A flexible approach for counterfactual prediction.” _Proceedings of the 34th International Conference on Machine Learning_, 2017.
*   Research | Doubly robust learning: D. Foster and V. Syrgkanis. _Orthogonal Statistical Learning_. arXiv preprint arXiv:1901.09036, 2019. URL [http://arxiv.org/abs/1901.09036](http://arxiv.org/abs/1901.09036).

Data visualization and communication
====================================

Data science organizations often partner with stakeholder teams throughout an organization. Communicating data science deliverables is an important step in maximizing their impact, whether through presentations, data visualizations, or written communications, and whether presented to a business or technical audience. Here are some resources to help with this:

Data visualization
------------------

Here is a range of books, courses and papers on data visualization techniques and approaches that you can incorporate into your work. Also see the [data visualization articles](https://medium.com/data-science-at-microsoft/visualization/home) on the Data Science at Microsoft online publication.

*   Book | [Storytelling with Data](http://www.storytellingwithdata.com/books)
*   Book | [The Wall Street Journal Guide to Information Graphics](https://wwnorton.com/books/The-Wall-Street-Journal-Guide-to-Information-Graphics/)
*   Book | [Information Dashboard Design](http://www.stephen-few.com/idd.php)
*   Book | [The Visual Display of Quantitative Information](https://www.edwardtufte.com/tufte/books_vdqi)
*   Course | [Data Visualization Tips and Tricks](https://www.linkedin.com/learning/data-visualization-tips-and-tricks) | LinkedIn Learning (may require free registration)
*   Course | [PowerPoint: Creating an Infographic](https://www.linkedin.com/learning/powerpoint-creating-an-infographic) | LinkedIn Learning (may require free registration)
*   Paper | [How deceptive are deceptive visualizations? An empirical analysis of common distortion techniques](https://www.researchgate.net/publication/300726103_How_Deceptive_are_Deceptive_Visualizations)
*   Paper | [Surfacing Visualization Mirages](https://arxiv.org/pdf/2001.02316.pdf)
*   Paper | [The Persuasive Power of Data Visualization](http://vis.cs.ucdavis.edu/vis2014papers/TVCG/papers/2211_20tvcg12-pandey-2346419.pdf)
*   Paper | [A Model-Based Visualization Taxonomy](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.12.6920&rep=rep1&type=pdf)
*   Paper | [An Insight-Based Methodology for Evaluating Bioinformatics Visualizations](http://www.ifs.tuwien.ac.at/~silvia/wien/vu-infovis/articles/Saraiya-TVCG-insight-2005.pdf)
*   Paper | [Characterizing Visualization Insights from Quantified Selfers’ Personal Data Presentations](https://www.researchgate.net/publication/276358497_Characterizing_Visualization_Insights_from_Quantified_Selfers'_Personal_Data_Presentations)
*   Paper | [Graphical Perception: Theory, Experimentation, and Application to the Development of Graphical Methods](http://www.math.pku.edu.cn/teachers/xirb/Courses/biostatistics/Biostatistics2016/GraphicalPerception_Jasa1984.pdf)
*   Paper | [More Than Telling a Story: Transforming Data into Visually Shared Stories](https://hal.inria.fr/hal-01158445/document)
*   Paper | [Reaching Broader Audiences with Data Visualization](https://hal.inria.fr/hal-02459678/document)
*   Paper | [Understand Users’ Comprehension and Preferences for Composing Information Visualization](https://www.researchgate.net/publication/262310059_Understand_Users%27_Comprehension_and_Preferences_for_Composing_Information_Visualizations)
*   Paper | [Voyager: Exploratory Analysis via Faceted Browsing of Visualization Recommendations](http://data-people.cs.illinois.edu/courses/cs598/papers/voyager.pdf)
*   Paper | [A Guide to Understanding Color](https://www.xrite.com/-/media/xrite/files/whitepaper_pdfs/l10-001_a_guide_to_understanding_color_communication/l10-001_understand_color_en.pdf)
*   Paper | [Escaping RGBland: Selecting Colors for Statistical Graphics](https://epubdev.wu.ac.at/1692/1/document.pdf)
*   Paper | [Rainbow Color Map (Still) Considered Harmful](http://people.renci.org/~borland/pdfs/RainbowColorMap_VisViewpoints.pdf)
*   Paper | [Somewhere Over the Rainbow: How to Make Effective Use of Colors in Meteorological Visualizations](https://journals.ametsoc.org/bams/article/96/2/203/215862)
*   Paper | [True Colors of Oceanography: Guidelines for Effective and Accurate Colormap Selection](https://www.researchgate.net/publication/307517997_True_Colors_of_Oceanography_Guidelines_for_Effective_and_Accurate_Colormap_Selection)
*   Paper | [ModelTracker: Redesigning Performance Analysis Tools for Machine Learning](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/amershi.CHI2015.ModelTracker.pdf)

Communication and public speaking
---------------------------------

Below are some resources for presentation training and scientific writing, as well as an organization you can join for further practice.

*   Course | [Presentation Skills | LinkedIn Learning](https://www.linkedin.com/learning/paths/develop-your-presentation-skills?u=3322)
*   Course | [Public Speaking | LinkedIn Learning](https://www.linkedin.com/learning/topics/public-speaking?u=3322)
*   Course | [Scientific Writing | Coursera](https://www.coursera.org/learn/sciwrite)
*   Community | [Toastmasters](http://www.toastmasters.org/)

Communities, podcasts, datasets, and events
===========================================

As you continue learn, here are some great spaces where you can exchange ideas with others and hear from their experiences regarding data science in practice. We’ve included opportunities to engage in online communities, participate in hands-on events, leverage publicly available datasets, listen to data science podcasts, and attend relevant conferences. We also recommend [GitHub](https://github.com/) and [Jupyter Notebooks](https://jupyter.org/) as great ways to share your work and collaborate with others.

Communities
-----------

Countless data science meetups and communities exist. Here are a few where you can engage with other data scientists on relevant topics:

*   Reddit channels ([Analytics](https://www.reddit.com/r/analytics/), [AskStatistics](https://www.reddit.com/r/AskStatistics/), [DataScience](https://www.reddit.com/r/datascience/), [Statistics](https://www.reddit.com/r/statistics/)): These subreddits cover data science topics.
*   [KDNuggets](https://www.kdnuggets.com/): This online platform covers business analytics, big data, data mining, and data science.
*   [Time Series Forecasting](https://github.com/rstudio-conf-2020/time-series-forecasting): This is a GitHub site for time series forecasting discussions.

Podcasts
--------

For those who prefer learning via audio, the following podcasts are great options:

*   [Towards Data Science](https://open.spotify.com/show/63diy2DtpHzQfeNVxAPZgU): In-depth subject area discussion.
*   [Women in Data Science](https://open.spotify.com/show/0eaFZXUh8qys3c0Wr3vrA3): Stanford-led community interviewing women leaders in data science.
*   [TW/ML AI](https://open.spotify.com/show/2sp5EL7s7EqxttxwwoJ3i7): Leaders in AI and ML discuss how they’re innovating in their domains.
*   [Super Data Science](https://open.spotify.com/show/1n8P7ZSgfVLVJ3GegxPat1): Higher-level overview of data science topics.

Hands-on events
---------------

These can be a great place to learn about new tools, hone your skills, and uncover best practices in the data science domain.

*   [Kaggle Competitions](https://www.kaggle.com/competitions): Kaggle allow users to work with other data scientists and Machine Learning engineers to enter competitions to solve data science challenges.
*   [Women in Data Science Datathons](https://www.widsconference.org/datathon.html): A global event that encourages more women to enter the field of data science.

Datasets
--------

The best way to learn data science is to practice with different projects. You can search and download free datasets online using the following resources.

*   [Kaggle datasets](https://www.kaggle.com/datasets): Kaggle has one of the largest dataset libraries online. The data is free and you can also upload your own datasets there.
*   [KDNuggets datasets](https://www.kdnuggets.com/datasets/index.html): KDnuggets maintains a good collection of datasets that are free and can be used for learning data science.
*   [Data is Plural](https://www.data-is-plural.com/): A weekly newsletter of useful and interesting datasets.
*   [TidyTuesday](https://github.com/rfordatascience/tidytuesday/tree/master/data/): A weekly data project aimed at the R ecosystem.

Conferences
-----------

Conferences can be a great way to learn from others’ experiences, get exposure to new ideas, and gain additional perspective. Here are some to explore:

*   [NeurIPS](https://nips.cc/): The purpose of the Neural Information Processing Systems annual meeting is to foster the exchange of research on neural information processing systems in their biological, technological, mathematical, and theoretical aspects.
*   [SIGKDD](https://www.kdd.org/conferences): The main professional association for data mining and knowledge discovery.
*   [ICML](https://icml.cc/): The International Conference on Machine Learning is the leading international academic conference in this subject area.
*   [CVPR](http://cvpr2021.thecvf.com/): CVPR is the premier annual computer vision event comprising the main conference and several co-located workshops and short courses.
*   [ACL](https://2021.aclweb.org/): The Association for Computational Linguistics (ACL) is the international scientific and professional society for people working on problems involving natural language and computation.
*   [SIGIR](https://sigir.org/sigir2021/): The annual SIGIR conference is the major international forum for the presentation of new research results and the demonstration of new systems and techniques in the broad field of information retrieval (IR).
*   [MLSys](https://mlsys.org/): The Conference on Machine Learning and Systems targets research at the intersection of systems and Machine Learning.


`Original article`: 
> https://medium.com/data-science-at-microsoft/data-science-learning-resources-193ccf6fafb
> 
