# NSO UI
-	A user friendly portal for customer demonstrations

You can use this template to create in a easy way to customize NSO features, using authentication process and create frames as GUI to show dasboards. 

# High Level Design

![High Level Design](https://github.com/moacosta/NSO_flaskGUI.png)

Once you implement the GUI using this template you can have something like this: 

![GUI mock up](https://github.com/moacosta/NSO_flaskGUI2.png)
 

# Installation

Please be sure that you have NSO already installed in the same server you will install this PoV. Also there is a need for a DB for authentication. 

pip install -r requirements.txt (use virtualenv when appropriate)

# Configuration

config.py - configuration, including credentials; settings.py - administrative settings.

The project uses iFrame, which is not allowed by NSO web server. In order for it to work, the restriction should be ignored by a browser. It can be achieved using plug-ins. For instance, iFrame Allow in Google Chrome

# Usage

Launching: python nso_cat.py

Currently project expects NSO to run and listen on localhost:8080. Default username and password to access the portal: admin password
