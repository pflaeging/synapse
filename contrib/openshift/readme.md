# Example config for Openshift or OKD (tested with 3.11)

Here are the example CRD's for Openshift

you need the following:
- 2 PV's (postgresql DB and synapse files)
- you have to change the route.yaml (certs)

The configuration consist of the following components:
- 2 pvc
- 1 configmap for all pods
- 2 deployments (synapse & postgresql)
- 2 services (synapse & postgresql)
- 1 route with SSL termination

This is not a fixed config. It's more a base template. You have to understand how openshift or okd is working.

Greets

Peter Pfläging <peter@pflaeging.net>