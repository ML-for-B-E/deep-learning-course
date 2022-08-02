# deep-learning-course

![use](https://img.shields.io/badge/use-Summer%20Camp-green) 


# Setup your execution environment
We assume here a Linux environnement for the CLI.

* Put yourself at the root of project. Depending of your current working directory, you may have to adjust `cd deep-learning-course` 
* Run the command `python3 -m venv venv`
* Activate the venv: `source venv/bin/activate`
* Upgrade pip if needed `pip install --upgrade pip`
* Install packages needed with `pip install -r requirements/dev.txt`
* Install our package `deeplearning` with `pip install -e .`
* Create a jupyter kernel linked to this venv 
  - `ipython kernel install --name "venv" --user`
  References: https://queirozf.com/entries/jupyter-kernels-how-to-add-change-remove.
* You can now open a notebook by running `jupyter notebook --no-browser`
* Select the kernel `venv` to run the notebook.
