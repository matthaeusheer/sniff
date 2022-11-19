# ipt-competence-profile
![](assets/sniff.png)

(yes, I stole this graphics from Google)

## About
What are those juicy competence profiles of ipt folks hiding?

## Installation

### Prerequisites
- [pyenv](https://github.com/pyenv/pyenv) - to manage your local python versions like a boss, easy to install via [pyenv-installer](https://github.com/pyenv/pyenv-installer) (check common build problems if issues arise)
- [pipenv](https://github.com/pypa/pipenv) - to manage dependencies in virtual environments with joy

### Create pipenv environment and install dependencies
1. Clone the repo
```sh
git clone https://github.com/matthaeusheer/sniff.git
```
2. Install python dependencies via `pipenv` (check prerequisites before)
```sh
cd sniff
pipenv install
```
3. Active virtual environment
```sh
pipenv shell
```

If you are lame, you can also of course do everything with your system  
python installation, use your system pip, fuck everything up and end up in dependency hell.

### Getting started
#### Getting the data ready
Go download the competence profile folder from GDrive and put all the .docx  
files into the folder `~/competence_profiles`.

#### Running the notebooks
There is a **notebooks** folder holding all the jupyter notebooks with deeeeeeeep insights. Go run them:  
Having the pipenv environment activated by running
```
pipenv shell
```
you can then run the jupyter lab with
```
jupyter lab
```