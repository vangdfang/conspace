# Conspace Sample Project

This is a sample project built on a default Mezzanine installation, customized
to install the Conspace registration application as well.  It's designed to
both run locally using `manage.py runserver` as well as as a deployed app
to OpenShift (https://www.openshift.com) using the Python 3.3 cartridge.

Please note that this is designed as a demo application, so many production
settings (such as disabling Debug mode or using a production database) are
not turned on.  When deploying to OpenShift, default administrative
credentials are generated and output to the console while deploying the
app.  They're available in `app-root/data/CREDENTIALS` should you miss the
one-time output.
