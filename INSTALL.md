mkproject -p /usr/bin/python3 landing-page

then delete the project folder and replace it with the repository

pip3 install django

Install django project
django-admin startproject landing_page .

#mv landing_page/manage.py .
#mv landing_page/_landing_page/* landing_page/
#rm -r landing_page/landing_page

To enable the server to be accessed remotely, change the ALLOWED_HOSTS
the setting file is in landing_page/settings.py

ALLOWED_HOSTS = ['emilemultiserver.ddns.net', '192.168.2.14']
