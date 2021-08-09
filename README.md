# Machine Learning Basics with Scikit-learn Workshop
Repository for the 2021 Summer Python Visualization Workshop at Northwestern University.

The workshop is divided into five parts. Day 1 is about the introduction of the scikit-learn library. Day 2 focuses on supervised learning models. Day 3 explores non-supervised learning models. Day 4 is about data cleaning and transformation. Finally, Day 5 focuses on model selection and evaluation.  

The data is contained in the data folder of this repository, but you do not need to download the entire repository to load the data in the code.

## Note on Versioning

This workshop was created using Python 3.9.1, scikit-learn 0.24.1, pandas 1.3.1, numpy 1.21.1 and matplotlib 3.4.2. The code was not tested on any other versions. Therefore, there is no guarantee that the code will work with different versions of the same software. These are the software version that anaconda official channel currently (August 2021) distributes. You can follow the instructions below to install the software on your machine or you can run the code on Google Collaboratory.

## How to Run the Notebooks on Google Colab
The notebooks require `Pandas`, `Matplotlib` and `scikit-learn`. You can use the Google Collaboratory version of the notebooks. 
To use the colaboratory version, it is sufficient to open click on the following badges, corresponding to the four notebooks composing the workshop:


1.   Day 1 on Colab: <a href="https://drive.google.com/file/d/1Q8bzq2cphO1_I_DpAnajXk6PH5HbeVCS/view?usp=sharing" target="_parent"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
2.   Day 2 on Colab: <a href="https://drive.google.com/file/d/1fEymjY33L_BxYzLDLo5PSmPERhbTxtNB/view?usp=sharing" target="_parent"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
3.   Day 3 on Colab: <a href="" target="_parent"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
4.   Day 4 on Colab: <a href="" target="_parent"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
5.   Day 5 on Colab: <a href="" target="_parent"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## How to Run the Notebooks on your Local Machine

You can run the workshop on your local maching by creating a specific Anaconda environment with this line of code:

`conda create -n python_ml_env pandas numpy matplotlib scikit-learn jupyterlab`

To activate the environment, you can use

`conda activate python_ml_env`

After this, you can download the entire repository with the "downloand code" green button on the right-upper corner of the [repository homepage](https://github.com/dgzara/python-ml-workshop). Finally, you can use Jupyter Notebook or Jupyter Lab (both included with Anaconda) to open the local versions of the notebooks.

The very last part of the workshop cannot be run on Colab, so it may be convenient to run the entire workshop locally. 

## Solutions to Exercises

You can find the solutions to the exercises in the following links:

1.   [Solution Exercises Part 1](Day_1_Answers.ipynb)
2.   [Solution Exercises Part 2](Day_2_Answers.ipynb)
3.   [Solution Exercises Part 3](Day_3_Answers.ipynb)
4.   [Solution Exercises Part 4](Day_4_Answers.ipynb)
5.   [Solution Exercises Part 5](Day_5_Answers.ipynb)

To see how the solutions work, you will have to copy paste the code in the original notebooks: the code will not work in the solutions' notebook.
