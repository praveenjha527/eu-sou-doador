I am Donor
Service to help people who need blood donation to find nearest compatible donors.

Requirements development environment

Python 2.7
postgres 9.1
GEOS
PROJ.4
GDAL
PostGIS
RabbitMQ
You can help with the installation of GEOS, PROJ, GDAL and in PostGIS: https://docs.djangoproject.com/en/1.6/ref/contrib/gis/install/geolibs/

Python environmental requirements

django
bpython
django-braces
django-model-utils
logutils
south
psycopg2
celery
django-autoslug
django-widget-tweaks
django-contact-form
coverage
django-discover-runner
django-debug-toolbar
sphinx
Installation of dependencies

$ Pip install -r requirements.txt
Running the application locally

$ Python manage.py runserver
If you are using Vagrant.

$ Python manage.py runserver [::]: 8000
or simply run local.sh file using the following command:

$ Sh local.sh
The Site

The most recent and working example is http://eusoudoador.com.br
