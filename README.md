# Django
okay! 
i am just getting started with django which is very new experience to me...
is a research paper for Django 

--------------------------Day01:03/05/26----------------------------------------

"my first commit that i have successfully installed Django on my windows system "
I am easiest steps to install Django on your system:
1. Install Python (includes pip automatically)
Step 1: Go to python.org/downloads

Step 2: Click the yellow Download Python button (latest version)

Step 3: Run the downloaded installer

Step 4: ⚠️ IMPORTANT - Check "Add Python to PATH" at the bottom

Step 5: Click "Install Now"

Step 6: Close the installer when finished

2. Verify Python & pip installation
Open Command Prompt (search "cmd" in Start menu) and type:

bash
python --version
Expected output: Python 3.x.x

bash
pip --version

3. Install Django
In the same Command Prompt, type:

bash
pip install django
4. Verify Django installation


bash
django-admin --version


5. Test Django (optional)
Create a test project:

bash
django-admin startproject mytest
cd mytest
python manage.py runserver

