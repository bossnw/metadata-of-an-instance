How to install
- Have to install on ec2
- Install Python 3 and git on your instance 
    - `sudo yum install python3 git`
- Clone this repository
  - `git clone https://github.com/bluprince13/aws-metadata-json`
- Install pipenv
  - `sudo pip3 install pipenv`
- Open the repository on your instance
  - `cd aws-metadata-json`
- Install project dependancies
  - `pipenv install`


How to run
- Open the `src` folder
  - `cd aws-metadata-json/src`
- Run whichever script you need:
  - `python3 get_metadata.py`
  - `python3 get_key.py`
