About
================================================================================

Openshift template for Play Framework applications

Usage
================================================================================

If you have rhc installed, create your new application as follows:

```
rhc app create appname -t diy-0.1 --from-code https://github.com/egor-k8n/openshift-play-framework
```

Otherwise, create a new diy application at https://openshift.redhat.com/app/console/applications
and specify the URL of this repository as your source code repository.

First run
================================================================================

Please keep in mind that the first run of the new application will take a long time,
as play framework and build dependencies would be downloaded behind the scenes.
