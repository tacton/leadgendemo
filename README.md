# Tacton CPQ LeadGen GUI framework

This git repository contains an example GUI code and application communicating with *Tacton CPQ LeadGen API*. 
It can be used as a starting template when creating an web application with configurator functionality, e.g. in a Tacton CPQ project or demo. 
This GUI framework application requires a running Tacton CPQ instance, with LeadGen API feature licenses activated.
Before start using this framework, you should be acquainted with the scope and functions of the *Tacton CPQ LeadGen API*, 
which you find in the Help center of your Tacton CPQ instance.

This repository contains general images and text for running and debugging the application. 
Imagery and text messages should be tailored for your particular Tacton CPQ LeadGen project.
The "products" folder is a place to store model specific images (product images and group images displayed in
the configurator).

Before deploying application developer should change config_vars values in tactonleadgen.js file such as Tacton CPQ LeadGen API key, API URL, Tacton CPQ ProductId and other.
To use Tacton CPQ Visualization a developer should edit index.html file with correct Tacton CPQ instance URL.

To deploy application, simply copy all files to your web server (Apache or Nginx) and navigate to http://your_server/

To debug and get acquainted with application flow see developer console in your web browser - requests and responses are logged to console.