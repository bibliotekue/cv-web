# Django Online-CV

Hi there. This is a Django app that helps me to digitize my resume. With any luck, I will stand out in a round and land my dream job.

## Run locally

**Clone project**
    
     git clone https://github.com/bibliotekue/cv-web.git

**Get project folder**
    
     cd cv-web/
    
**Create virtual environment**

    python -m venv venv
    
**Acrivate virtual Environment**

    source venv/bin/activate
    
**Install dependencies**

    pip install -r requirements.txt

**Migrate**

    python manage.py makemigrations

    python manage.py migrate

**Create super user**

    python manage.py createsuperuser
    
**Run server**

    python manage.py runserver

---
After this you could do anything on your local server. 

Also, if something went wrong with layout you need to configure STATIC_URL and MEDIA_URL in ***cv-engine/settings.py***.
