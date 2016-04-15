# RAP-Mail-Example-Product

This repository contains an example how a RAP 3.0 based application can be packaged as an executable running an embedded Jetty in an OSGi runtime.
The example project is the mail example shipping with RAP.

The branch `emf-rap` shows what to do, when the EMF RAP Target Components are installed with your application.

## IDE Setup

Use the eclipse installer and switch into advanced mode. Then select "Eclipse IDE for Java Developers" and click "Next". On the next use the green plus icon to add the following link `https://raw.githubusercontent.com/Boereck/RAP-Mail-Example-Product/master/releng/mail.setup/MailProductExample.setup` to the catalog. Then double click to select project `<User>\Mail Product Example` so the entry has bold font. Then click "Next" and choose the details where the eclipse should be located and git repository should be checked out.

