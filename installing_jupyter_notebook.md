# Utilizing a Jupyter Notebook 

## Installing Python3.X

Be sure you are utilizing **Python 3.X**, python 2.7 comes native to MacOS so go onto the [python website](https://www.python.org/) and download **Python3.X**. Once you have done so for MacOS you should be able to utilize python3 from the terminal using:

	python3 

For which you should see something similar: 

	Python 3.6.2 
	Type "help", "copyright", "credits" or "license" for more information.
	>>>

You can exit now by doing:

	>>> quit()

## Setting Environment Variable

For windows an extra step is needed for your command prompt to recognize the `python` command. Press the `windows` button and search **enviroment**, you should see `Edit the system Environment Variables`, click on it. Next on the lower left side you'll see a button called **Environment Variables...** click on it and click **New** on the **User** variables. 

The **Variable Name** should be called `PYTHONPATH` and the value should be where `python.exe` is located (I would just search python.exe and right click to get the file location). 

Click ok, close the command prompt and open a new one. You should now be able to utilize **Python3.X** on your command prompt. 

## Installing Jupyter Notebook 

Python comes with an installer called `pip`, with `pip` you can download 3rd party packages that are helpful in any python project. 

## Virtual Environment 

This section is optional but if you want to abstract your notebooks for reproducibility I recommend looking at these projects:

+ [Virtual Enviroments](https://www.inertia7.com/projects/1)
+ [Virtual Enviroments (for Windows)](https://www.inertia7.com/projects/75)

Next let's go ahead and install jupyter utilzing pip as follows

### Windows 

	python -m pip install jupyter

### MacOS

	pip3 install jupyter 

## Running Jupyter Notebook

Once you have downloaded the package you are ready to use it!

Remember to be mindful of where you are in your computer, because the notebook will save in that directory. So I would move to either your Desktop or your my_projects folder. You can find basic terminal commands on this [project](https://www.inertia7.com/projects/38). 

Now we create an instance that will allow us to create a notebook!
## Windows

	python -m notebook

## MacOS

	jupyter notebook 

Once you do this you should be referenced to the **Jupyter** interface where you can start creating notebooks! If you were to lose it, you can easily accecss it by writing http://localhost:8888 on your web browser. 

## Exiting Jupyter Notebook 

Once you've done all the work you need to do, you should (goes without saying) name and save your file. But more importantly you have to exit out since it is being localy hosted on your computer. The way you do this is go to the terminal that has the notebook running and press `Control+C` which will exit the notebook and won't allow you to do anything on the interface until you re-run the previously mentioned commands. 

