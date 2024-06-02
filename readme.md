to change from development to production_deployment


1. settings.py 

ALLOWED_HOSTS = [] changed to ALLOWED_HOSTS = ['.vercel.app']

2. require requirements.txt

3. vercel.json file in root dir

4. app = application

5. 
# WSGI_APPLICATION = 'webbot.wsgi.application'
WSGI_APPLICATION = 'api.wsgi.app'



