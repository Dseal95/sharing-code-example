# Sharing_Code_Example
An example of using **setup.py** to create a package and share code across a project.

Link to **Medium** article that uses this repository - https://medium.com/@dan.seal.06/sharing-code-using-a-setup-py-b6a596646532

# Setting Up

- (1) Clone the repository, https://github.com/Dseal95/Sharing_Code_Example.git
- (2) (Optional) Set up a virtual environment by running the following commands:

```
python -m venv .venv
source .venv/bin/activate
```

- (3) Install wheel package into .venv, `pip install wheel`
- (4) Open up your IDE terminal  / CMD (windows) / terminal (Mac) and navigate to the root `/Sharing_Code_Example/`:
- (5) Install the custom Python package `simple-package` by running,

```
pip install ./src
```

Or for installing in editable mode (advised when developing), add a -e: 

```
pip install -e ./src
```


Once complete, you will be able to run both `main.py` files inside the sub-projects `project1` and `project2` without any errors! 
