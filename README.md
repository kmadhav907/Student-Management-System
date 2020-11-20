# Library-Management-System

## How to Install and Run this project?

### Pre-Requisites:
1. Install Git Version Control
[ https://git-scm.com/ ]

2. Install Python Latest Version
[ https://www.python.org/downloads/ ]

3. Install Pip (Package Manager)
[ https://pip.pypa.io/en/stable/installing/ ]

*Alternative to Pip is Homebrew*

### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv
```
For Mac
```
$  python3 -m venv venv
```

Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```


Clone the repository
```
$git clone https://github.com/kmadhav907/Student-Management-System.git
```




**4. Install Requirements from 'requirements.txt'**
```python
$  pip install -r requirements.txt
```
**5. Migrate the files'**
```python
$  python manage.py migrate
```
**6. Run the files'**
```python
$  python manage.py runserver
```
