---
title: Deploying the guide to Cloud Foundry
---

###Build python-api-guide

cd openstack-manuals/doc/pythin-api-guide
mvn clean generate-sources

the target directory is created with the contents of the build

###Copy the target dir

Copy the target directory to openstack-manuals/deployment/python-api-guide/public


###Login to cloud foundry
cf login

Pus the bits to the cloud foundry.
cf push




