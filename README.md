# jenkins-vagrant-openshift

Prerequiste:
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](https://www.vagrantup.com/)


## Running open shift:
* git clone 
* vagrant up
* vagrant ssh 
* oc login https://10.2.2.2:8443 ' --> based on the url on the console.' 
* oc project openshift-infra
* oc deploy jenkins --latest -n openshift-infra
* oc get route ' --> see routes in jenkins' 

## More Details:
1. [openShift-Jenkins](https://github.com/openshift/origin/blob/master/examples/jenkins/README.md)
2. https://blog.openshift.com/pipelines-with-jenkins-2-on-openshift/


