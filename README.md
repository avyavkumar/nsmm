# National Society Matrix Mapping

## Instructions to set up the environment

* cd into the working directory (assumed to be ~/dev here) `mkdir -p dev; cd ~/dev`
* Create a directory for virtualenvironment `mkdir virtualenvs`
* Install pyvenv if not already installed `sudo apt-get install python3-venv`
* Create the virtualenv `pyvenv ~/dev/virtualenvs/nsmm`
* Clone the repository `git clone http://github.com/avyavkumar/nsmm`
* Activate the virtual environment `source ~/dev/virtualenvs/nsmm/bin/activate`
* cd into the project directory `cd nsmm`
* Install dependencies `pip3 install -r requirements.txt`
* Start the development server with `python3 manage.py runserver`

## General Instructions

* Do ensure the virtualenvironment is activated while working on the project
