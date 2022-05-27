# React with Django

## Prerequisites :

- Python should be installed. (Version >=3.9.x)
  > > [Download | Python (python.org)](https://www.python.org/downloads/)
- Pip should be installed. (Version >=21.1.x)
  > > [Download | Pip (pip.pypa.io)](https://pip.pypa.io/en/stable/installation/)
- Virtual Environment Wrapper should be installed. (Version >=4.8.x)

  > > [Download | Virtual Environment Wrapper (pypi.org)](https://pypi.org/project/virtualenvwrapper/)\
  > > [Setup: Virtual Environment](https://stackoverflow.com/questions/2615968/installing-virtualenvwrapper-on-windows#:~:text=Navigate%20to%20the%20folder%20%22virtualenvwrapper,Env%20Wrapper%20for%20Powershell%20activated%22)

- Node.js should be installed. (Version >=16.x.x)
  > > [Download | Node.js (nodejs.org)](https://nodejs.org/en/download/)
- An IDE (e.g VSCode, Atom etc)
  > > [Visual Studio Code](https://code.visualstudio.com/)\
  > > [Atom](https://atom.io/)\
  > > [Eclipse](https://www.eclipse.org/downloads/)

## Step-by-Step Walkthrough

- Extract the downloaded starterKit.zip folder.
- Open the starterKit folder and rename it to your requirement.
- Now open the folder and switch to the djangoBackend named folder.
- Create a virtual environment to install all the dependencies by providing command `virtualenv virtualenv_name` (in place of virtualenv_name, provide your preferred name).
- Switch to the virtual environment by providing the command `.\virtualenv_name\Scripts\activate.ps1`.
- Run the command `pip install -r requirements.txt`.
- After all the dependencies are installed, run the command `python manage.py runserver`.
- This will run the local django server and you will be able to use it with react application.
- Open a new terminal window and change directory to frontend folder.
- Install the dependencies by running `npm install`.
- Run the application by giving command `npm start`.
