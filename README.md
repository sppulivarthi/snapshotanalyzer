# snapshotanalyzer

Demo project to manage EC2 instance snapshots
# configure AWS cli
aws configure --profile shotty
#Setup
pip3 install pipenv
# Cretae pipfile for this project
pipenv --three
# use boto3 connect to AWS
pipenv install boto3
# install ipython
pipenv install -d ipython

# run python script
pipenv run "python shotty/shotty.py"

# install cick modules
pipenv install click

*command* is instances, volumes, or snapshots
*subcommands* depends on command
*project* is optional
