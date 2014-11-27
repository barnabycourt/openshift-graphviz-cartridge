OpenShift Graphviz Cartridge
============================

An OpenShift cartridge to be used as an add-on for any primary cartridge.
This cartridge provides a [Graphviz](http://www.graphviz.org) installation.

Usage
-----

The cartridge can be added to any application either through the OpenShift web console or the [OpenShift client tools](https://developers.openshift.com/en/getting-started-client-tools.html)
using the URL http://cartreflect-claytondev.rhcloud.com/github/puzzle/openshift-graphviz-cartridge. 
Example using the OpenShift client tools:

    rhc -amyapp cartridge-add http://cartreflect-claytondev.rhcloud.com/github/puzzle/openshift-graphviz-cartridge
    rhc -amyapp app restart

Graphviz Version Info
---------------------
The [Graphviz](http://www.graphviz.org) version provided, currently *2.26.0*, is taken from the rpm included in [CentOS](http://www.centos.org/) 6.

Graphviz sources are available at http://github.com/ellson/graphviz/
