# Setup for Windows based systems:

1. Open the command prompt
2. Verified the version of Python that is installed on your machine by Typing the command:
   *python -version*
   [I have used the Python version 2.7.12]
3. I installed python on windows using the python-2.7.12.msi file
4. Then set the path for Python by updating the environment vaiables by adding the following command:
   *C:\Python27;*
   *C:\Python27\Python.exe;*
   *C:\Python27\Scripts\;*
   *C:\Python27\Lib\site-packages\django\bin;*
4. After Python 2.7.12 is installed on your machine, I installed Django using pip file (get-pip.py) in the virtual environment:
   *python get-pip.py*
   *pip freeze*
   *pip install virtualenv*
   *virtualenv venv*
   *.\Scripts\activate*
   *pip install django-1.10.1*
5. Verified the that Django is installed properly on your machine using the following commands:
   *pip freeze*
6. Download the ZIP file "world.zip" from Github and extract all files at any desired location on your machine
7. Navigate to the "world" directory
8. Run the following command:
   *python manage.py runserver*
9. Once the server is live, open up a web browser and type in the following in the search bar:
   *127.0.0.0:8000/world*
10. You should be able to see "Hello world!" displayed in your browser

Team members:

Onika Yadav
Swetha Kaza
