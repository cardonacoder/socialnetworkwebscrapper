# Python Social Network Web Scrapper

Social Network (Fb, Ig, Tw, Li, Tk ) web scrapper made in Python with Django and Beautiful Soup

## Follow this steps for running this app

1. **Install python**. This app was developed on Python [3.11.1]
![1.Python_exe](https://github.com/cardonacoder/socialnetworkwebscrapper/blob/main/README_images/1.Python_exe.png?raw=true)
Check the Python version with ```python --version``` command:

![2.Check_installation_&_python_version](https://github.com/cardonacoder/socialnetworkwebscrapper/blob/main/README_images/2.Check_installation_&_python_version.png?raw=true)
2. **Set Up a Virtual Python Environment**
Go to ```C:\Users\%username%\AppData\Local\Programs\Python\PythonVERSION\```

In my case **VERSION** was 311, that is:

```C:\Users\%username%\AppData\Local\Programs\Python\Python311\```

Then go to the ```Scripts``` and search for ```virtualenv.exe``` file.

![3.Checking_venv.exe](https://github.com/cardonacoder/socialnetworkwebscrapper/blob/main/README_images/3.Checking_venv.exe.png?raw=true)

If not, install it via ```pip install virtualenv``` command on a shell, like this:
![4.Installing_venv](https://github.com/cardonacoder/socialnetworkwebscrapper/blob/main/README_images/4.Installing_venv.png?raw=true)
3. With the ```virtualenv``` library globaly installed, it proceed to situate in the project folder and create the envirorment by typing the following command ```virtualenv -p python3 env``` in the terminal like it shows in the picture:

![5.Creating_venv](https://github.com/cardonacoder/socialnetworkwebscrapper/blob/main/README_images/4.Instal_venv.exe.png?raw=true)

After the envirorment creation, this one must be activated introducing the next code line:  ```.\env\Scripts\activate```. It is important to note that if the machine in which it is working has windows OS, the following error could appear:

![6.Activate_venv_and_error](https://github.com/cardonacoder/socialnetworkwebscrapper/blob/main/README_images/6.Activate_venv_and_error.png?raw=true)

That error can be solved opening the shell with administrative privileges

![7.ps_adm](https://github.com/cardonacoder/socialnetworkwebscrapper/blob/main/README_images/7.ps_adm.png?raw=true)

with this command ```Set-ExecutionPolicy RemoteSigned -Scope CurrentUser``` like this:

![8.FixingError](https://github.com/cardonacoder/socialnetworkwebscrapper/blob/main/README_images/8.FixingError.png?raw=true)

The main reason to follow the previous steps, was because have a virtual envirorment for every  project it's a good practice in the way that every project, independently, have their own libraries and packages.
3. Finaly _activate_ the venv and proceed to install the needed libraries, in this case Django:
![9.Activate_and_DjangoInstall](https://github.com/cardonacoder/socialnetworkwebscrapper/blob/main/README_images/9.Activate_and_DjangoInstall.png?raw=true)

[3.11.1]:(https://www.python.org/downloads/release/python-3111/)