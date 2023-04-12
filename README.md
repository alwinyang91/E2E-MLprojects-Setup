# E2E-MLprojects-Setup

This repository stores the 1st End to End Machine Learning Project  with Deployment-Github and Code Set Up.

## 1. git clone

```python
git clone git@github.com:alwinyang91/E2E-MLprojects-Setup.git
```



## 2. Create an environment locally

Step 1:

```python
python -m venv yourEnvName
# or 
virtualenv yourEnvName -p python3.9
```

Step 2:

```python
source yourEnvNmae/bin/activate
```

Step 3: check your python version if you want to

```python
python --version
```



## 3. Create `requirement.txt` , `src/__init__.py`  files

```python
touch requirements.txt
mkdir src
cd src
touch __init__.py
```



## 4. Create a `setup.py` file

```python
touch setup.py
```



## 5. Run 

```python
pip install -r requirements.txt
```

 
