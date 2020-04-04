# irsc - Important Must read
IRSC task

Instruction to Run the Server, Application and Endpoints are given in the Documentation PDF

Use pip install -r requirements.txt after cloning, make sure you install requirements.txt in a virtual environment.

## After Installing Requirements.txt packages in a virtual environment one critical task is required before doing migrations.

### Steps:

  ### If your virtual environement name is venv then go to this location:
  ### ..\venv\Lib\site-packages\status\api
  
  ### Open the mixins.py file and replace 
  
  ### "from django.core.urlresolvers import reverse" with this "from django.urls import reverse"
  
  
