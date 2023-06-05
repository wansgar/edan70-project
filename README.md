# edan70-project

In this project, machine learning models are used to predict the outcome of patients waiting for a heart transplant. Data is provided by the United Network for Organ Sharing (UNOS), and contains data of over 110,000 unique U.S. patients. 

## Setup

The data set contains sensitive information and will not be distributed here.
You will only be able to run the notebook if you have your own copy of the data set csv and store it in a new folder `data`.

Setup and enter a new python environment and install the dependencies:
```
python -m venv venv
source venv/bin/activate
python -m pip install -r requirements.txt
```

Create a kernel for the environment:
```
ipython kernel install --user --name=venv
```

Run the notebook:
```
jupyter notebook main.ipynb
```

Change the kernel to your newly created one:
![Testing](img/change_kernel.png)

Enjoy!