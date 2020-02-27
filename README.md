# VHB-ProDok Course Machine Learning

VHB-ProDok is a format offered by the German Academic Association for Business Research to support doctorates in business studies in German-speaking countries. Detailed information concerning the program and the more than 40 courses it offers are available at the [VHB-ProDok homepage](https://www.vhbonline.org/en/events/prodok).

The repository targets participants of the course Machine Learning, which I will offer anually or bi-annually from 2020 onwards. Please refer to the [course's homepage](https://www.vhbonline.org/en/veranstaltungen/prodok/kurse-2020/translate-to-englisch-2004ms01) for detailed information on the format and content of the course.

For now, the repository comprises the files of the pre-course mini-assignment, which enables participants to familiarize themselves with the Python programming language and revisit their abilities in descriptive statistics and multivariate statistical analysis. Detailed solutions to the tasks will be provided during the course, 06. to 09. April, 2020 in Berlin.

The pre-course assigment comprises two tasks. The first tasks involves creating some synthetic (linearly seperable) data and fitting a logisitc regression classifier to that data. On the way, you will create some visualizations of both, the data and the classification model. The main learning objective associated with this task are:
* Basic Python programming
* Creating graphs using [matplotlib] (https://matplotlib.org/), which is a popular Python library for plotting
* Grasping the equivalance between a tabular data set (i.e., a table) and data points in a multivariate attribute space

The second task involves working with real data. We use the *home credit* data, which was used in [kaggle competition](https://www.kaggle.com/c/home-credit-default-risk). The competition website provides detailed information about the data set and offers the opportunity to download the data for study purpose. It also provides much background information and useful codes. The data set is large and preparing it for analysis is nontrivial. We provide a Python script for data integration. The script integrates different files, which are only available seperately at the competition websites, performs some rudimentary data pre-processing, and reduces the size of the data to simplify subsequent analysis. Using the resulting prepared data set, you are asked to perform several operations to further prepare the data for machine learning algorithms
Key learning outcomes of the second task include:

* Familiarity of Pandas dataframes
* Experience with standard data preprocessing operations such as missing value replacement in Python
* Experience in working with complex real-world data and the challenges this brings about.

Depending on your prior experiences in applied machine learning, data science, and programming, you will find the tasks more or less demanding. Supposedly, task 2 will prove challenging because of the complex structure of the data. We will discuss solutions to the tasks in the course and also continue working with the *home credit* data. Therefore, I strongly encourage all course participants to spend a good amount of time on the tasks. At times, you might feel a bit lost, lacking an idea how to solve a task. This is perfectly normal in programming. Search engines are your friend! I bet that solutions to each sub-task of the pre-course assigment are available on the web in some blog, programming forum (e.g., [stackoverflow](https://stackoverflow.com/), etc. A carefully chosen search query will almost surely provide an answer / solution to the
assignment tasks. Make intensive use of the many great resources out there on the web just waiting for you. Just to stress this point, one of the assignment tasks asks you to fix the seed of the random number generator. Try this query with your favorite search engine to get an answer: "python random number fix seed". 

A final note on tooling. If you are new to Python programming, I suggest you explore [Google Colab](https://colab.research.google.com), which is a free online coding environment. Many tutorials about Colab are available on the web (see, e.g., [here](https://www.tutorialspoint.com/google_colab/index.htm)) and will help you to get started. The advantage of Colab is that you do not need to install any software to your local machine. 

If you prefer using your own computer, you can certainly do so. All you need is freely available on the web. One note of caution: we use large data in task 2. Unless your computer has a sufficient amount of RAM, it is better to use Colab. I guess that 8 GB RAM is the minimum that you would need whgile 16 GB would be better. For beginners, the [Anaconda distribution] (https://www.anaconda.com/distribution/?gclid=CjwKCAiAhc7yBRAdEiwAplGxX_cnNEcik0eYiYjlORTq7c_4xA3gOhqFc0v-8pwNw5vC6ADTKwuFRhoC-98QAvD_BwE) of Python is probably the best choice and should include everything you need to get started. Regarding code editing, the use of Jupyter notebooks is common. [Visual Studio Code](https://code.visualstudio.com/) from Microsoft is another editor that gained some popularity in the community. Many other tools exist and can be used. 

Please understand that we cannot provide support how to install software or fix issues that occur during installation. Working with Python can be a little cumbersome at times because of different versions of the programming language, the libraries, which provide certain functionalities, many different tools and options, etc. If you feel a little adventurous feel very free to setup everything yourself and otherwise use Google Colab. 

**Happy coding and look forward to meeting you in Berlin in April 2020**

