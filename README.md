## Automation

Simple examples of automating computer networking tasks.

### Environment Requirements

Python >= 3.8  
Ansible >= 2.9

Create a Python virtual environment and install the 
requirements.txt file located in this directory. It 
contains every unique Python library needed by any 
resource in this repo.

The virtual environment will aid in maintaining the
tidyness of your base Python environment and provide
a fresh environment for the required libraries to
be installed into.
```sh
# clone the repository with git.
git clone https://github.com/billminear/automation.git

# install virtualenv and setup a virtual environment.
# - this is on Ubuntu Desktop 20.04. if you're using windows
# - or macOS, the following commands may vary. be advised.
python3 -m pip install virtualenv
python3 -m venv ~/venvs/automation # adjust path to your liking.
source ~/venv/automation/bin/activate # if you modified the path, update here.

# your virtual environment is now active. let's install
# the required libraries.

python3 -m pip install -r requirements.txt

# at this point, you're free to navigate the directories
# and try out the available utilities. instructions for 
# each resource can be found in the directory of the utility.

# when you're done, deactivate your virtual environment.
deactivate

# if you have questions, reach out!
````
