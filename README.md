# indigo-ds-repo-template
Template for cloning data science repos. Notes about this repo template:
- Notebooks in the notebooks folder will be ignored if they start with "work". If you add 2 notebooks called `analysis.ipynb` and `work-dev.ipynb` only `analysis.ipynb` will be tracked.
- The contents of the `data/` folder will not be tracked.
- `images/` directory which can be used to add screenshots/images which will be added to your repo README.

## Setup
Info on how to set up your repo here

### Dependencies

Create a new virtual environment if you would like. This is highly suggested. You can do this by creating a `venv` in the root folder of the repo. In the terminal:

```bash
$ python -m venv venv
```
Which will create a `venv/` directory. To activate the environment:

```bash
$ source venv/bin/activate
```
You should now see `(venv)` in the terminal.

 In the terminal, install requirements:

```bash
$ pip install -r requirements.txt
```

Add any additional dependencies that need to be installed or configured as well.

## Usage

How does a user run the scripts? Detailed instructions go here.

## Change Log
- 2023-06-07
  - Added repo template
  - Added readme template
- 2023-08-16
  - Added isort config file
---

> This is just a simple readme template, feel free to change as needed.
