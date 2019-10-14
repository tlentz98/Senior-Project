# FlaskAPP

#### The basic necessities to run it

## Install [Python](https://www.python.org/), [pip](https://pip.pypa.io/en/stable/installing/), and [Virtualenv](https://virtualenv.pypa.io/en/latest/)
###### Once they're downloaded verify installation:
```
python --version
Python 3.7.2

pip --version
pip 19.2.3

virtualenv --version
16.4.3
```
## Get Environment Started
```
# Clone and cd into this repo
git clone https://github.com/mzacierka/SeniorProj.git
cd FlaskAPP

# Create and activate the Virtualenv
virtualenv venv
./venv/bin/activate.bat

# Install all dependencies
pip install -e .

# Lets flask know where the app starts, the "FlaskAPP" dir
set FLASK_APP=FlaskAPP

# Puts flask into dev mode
# so auto reload flask on file change & nice Traceback/stacktrace
set FLASK_ENV=development

# Run it
flask run
```