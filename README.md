# Deprecated: 

-----

This project was based on OpenShift v2, a new version is available 
for [OpenShift Container Platform](https://github.com/redhatdemocentral/rhcs-brms-install-demo).

-----



## Cartridge for brmsPaaS by JBoss BRMS on OpenShift

This cartridge provides the **_Red Hat JBoss BRMS_** for easy deployment to OpenShift based bpmPaaS with JBoss BRMS.


Install with one click in xPaaS (brmsPaaS)
-----------------------------------------
After clicking button, ensure `Gear` size is set to `large`:

[![Click to install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Install brmsPaaS.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=https://raw.githubusercontent.com/jbossdemocentral/cartridge-brmsPaaS/master/metadata/manifest.yml&name=brmspaas&gear_profile=large&initial_git_url=)

Once installed you can use the JBoss BRMS logins: 

   * u:erics  p: jbossbrms  (admin)

   * u: alan  p: jbossbrms  (analyst)


Important Note
--------------
You need the ability to setup LARGE gears, which is freely available if you [upgrade your account to Bronze here] (https://www.openshift.com/products/pricing). 


Manual setup on OpenShift
-------------------------
Or if you want to use the [rhc command line](https://www.openshift.com/developers/rhc-client-tools-install) type:

    rhc app create -g large <APP NAME> https://raw.githubusercontent.com/jbossdemocentral/cartridge-brmsPaaS/master/metadata/manifest.yml

This will output the generated users and passwords for Business Central.

You can use them to login into Business Central or BAM applications.


Supporting Articles
-------------------
- [7 Steps to Your First Rules with JBoss BRMS Starter Kit](http://www.schabell.org/2015/08/7-steps-first-rules-jboss-brms-starter-kit.html)

- [How to Use Rules and Events to Drive JBoss BRMS Cool Store for xPaaS](http://www.schabell.org/2014/08/how-to-use-rules-events-drive-jboss-brms-coolstore-xpaas.html)


Released versions
-----------------

- v1.1 - moved to JBoss Demo Central, added one click installation button.

- v1.0 - based on brmsPaaS from JBoss BRMS 6.0.2.

[![Video Demo bpmPaaS](https://github.com/jbossdemocentral/erics-images/blob/master/video-images/video-brms-coolstore-bpmpaas.png?raw=true)](http://vimeo.com/ericschabell/bpmpaas-brms-coolstore-demo)

![Decision Table](https://github.com/jbossdemocentral/brms-coolstore-demo/blob/master/docs/demo-images/coolstore-decision-table.png?raw=true)

![Domain Model](https://github.com/jbossdemocentral/brms-coolstore-demo/blob/master/docs/demo-images/coolstore-model.png?raw=true)
