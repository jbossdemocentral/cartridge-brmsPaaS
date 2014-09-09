## Cartridge for bpmPaaS with CoolStore Demo

Summary
-------
This cartridge provides the **_Red Hat JBoss BRMS_** for easy deployment to OpenShift based bpmPaaS with JBoss BRMS.

JBoss BRMS logins: 

   * u:erics  p: jbossbrms  (admin)

   * u: alan  p: jbossbrms  (analyst)


Important Note
--------------
You need the ability to setup LARGE gears, which is freely available if you [upgrade your account to Bronze here] (https://www.openshift.com/products/pricing). 


Deployment
----------

To try out JBoss BRMS on OpenShift please follow the instructions:

If you want to use the [OpenShift create application page](https://openshift.redhat.com/app/console/application_types), enter this cartridge URI in the entry field (at the bottom left of the form):

  **https://raw.githubusercontent.com/eschabell/cartridge-brmsPaaS/master/metadata/manifest.yml**

Or if you want to use the [rhc command line](https://www.openshift.com/developers/rhc-client-tools-install) type:

    rhc app create -g medium <APP NAME> https://raw.githubusercontent.com/eschabell/cartridge-brmsPaaS/master/metadata/manifest.yml

This will output the generated users and passwords for Business Central.

You can use them to login into Business Central or BAM applications.


Supporting Articles
-------------------

[How to Use Rules and Events to Drive JBoss BRMS Cool Store for xPaaS](http://www.schabell.org/2014/08/how-to-use-rules-events-drive-jboss-brms-coolstore-xpaas.html)

Released versions
-----------------

- v1.0 - based on brmsPaaS from JBoss BRMS 6.0.2.

[![Video Demo bpmPaaS](https://github.com/eschabell/erics-images/blob/master/video-images/video-brms-coolstore-bpmpaas.png?raw=true)](http://vimeo.com/ericschabell/bpmpaas-brms-coolstore-demo)

![Decision Table](https://github.com/eschabell/brms-coolstore-demo/blob/master/docs/demo-images/coolstore-decision-table.png?raw=true)

![Domain Model](https://github.com/eschabell/brms-coolstore-demo/blob/master/docs/demo-images/coolstore-model.png?raw=true)
