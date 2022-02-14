# VHB-ProDok Course Machine Learning

VHB-ProDok is a format offered by the German Academic Association for Business Research to support doctorates in business studies in German-speaking countries. Detailed information concerning the program and the more than 40 courses it offers are available at the [VHB-ProDok homepage](https://www.vhbonline.org/en/events/prodok).

The repository targets participants of the course Machine Learning, which I will offer anually or bi-annually from 2020 onwards. Please refer to the [course's homepage](https://www.vhbonline.org/en/veranstaltungen/prodok/kurse-2020/translate-to-englisch-2004ms01) for detailed information on the format and content of the course.

The repository comprises the files of the pre-course demos, which are meant to support participants with preparing for Python part of the course. Participants can revisit their abilities in descriptive statistics, multivariate statistical analysis, and, of course, Python programming. 

The pre-course assigment comprises two tasks. The first tasks involves creating some synthetic (linearly seperable) data and fitting a logisitc regression classifier to that data. On the way, you will create some visualizations of both, the data and the classification model. The main learning objectives associated with this task are:
* Basic Python programming
* Creating graphs using [matplotlib](https://matplotlib.org/), which is a popular Python library for plotting
* Grasping the equivalance between a tabular data set (i.e., a table) and data points in a multivariate attribute space

The second task involves working with real data. We use the *home credit* data, which was previously used in a [kaggle competition](https://www.kaggle.com/c/home-credit-default-risk). The competition website provides detailed information about the data set and offers the opportunity to download the data for study purpose. It also provides much background information and [many useful codes](https://www.kaggle.com/c/home-credit-default-risk/code). The data set is large and preparing it for analysis is nontrivial. We provide a Python script for data integration. The script integrates different files, which are only available seperately at the competition websites, performs some rudimentary data pre-processing, and reduces the size of the data to simplify subsequent analysis. Using the resulting prepared data set, you are asked to perform several operations to further prepare the data for machine learning algorithms.
Key learning outcomes of the second task include:

* Familiarity with [Pandas](https://pandas.pydata.org/) data frames
* Experience with standard data preprocessing operations such as missing value replacement in Python
* Experience in working with complex real-world data and the challenges this brings about.

Depending on your prior experiences in applied machine learning, data science, and programming, you will find the tasks more or less demanding. Supposedly, task 2 will prove challenging for most participants because of the complex structure of the data. Please decide for yourself how much time you can and want to invest into solving the tasks on your own. More preparation is always better but other obligations also need your attention. In my opinion, the role of the two tasks for our course is somewhat inbetween a pre-course assignment and a demo. Therefore, the repository also provides demo solutions for the two programming tasks, which you can always consult for help. 

A final note on tooling. If you are new to Python programming, I suggest you explore [Google Colab](https://colab.research.google.com), which is a free online coding environment. Many tutorials about Colab are available on the web (see, e.g., [here](https://www.tutorialspoint.com/google_colab/index.htm)) and will help you to get started. The advantage of Colab is that you do not need to install any software to your local machine. 
If you prefer using your own computer, you can certainly do so. All you need is freely available on the web. The [Anaconda distribution](https://www.anaconda.com/distribution/?gclid=CjwKCAiAhc7yBRAdEiwAplGxX_cnNEcik0eYiYjlORTq7c_4xA3gOhqFc0v-8pwNw5vC6ADTKwuFRhoC-98QAvD_BwE) of Python is the most popular choice for data scientists and includes everything you need to get started. Regarding code editing, we will make use of Jupyter notebooks during the course. However, many other great code editors exist including  [Visual Studio Code](https://code.visualstudio.com/), [PyCharm](https://www.jetbrains.com/pycharm/), and others. You are free to use any of them but I recommend using Jupyter if you are new to Python programming.


**Happy coding and look forward to meeting you in the VHB ProDok course on Machine Learning**

