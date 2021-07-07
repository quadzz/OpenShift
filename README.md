# OpenShift
Repository to gather data, yamls and help using OpenShift



## Object & API groups
This can be used to do roles definitions and rolebinding:
| Object | ApiGroup |
|--|--|
| pods pods/attach pods/exec pods/portforward pods/proxy||
|configmaps endpoints persistentvolumeclaims replicationcontrollers replicationcontrollers/scale secrets serviceaccounts services services/proxy||
|namespaces||
|serviceaccounts||
|resourcequotausages||
|controllerrevisions daemonsets deployments deployments/rollback deployments/scale replicasets replicasets/scale statefulsets statefulsets/scale|apps|
|horizontalpodautoscalers|autoscaling|
|cronjobs jobs|batch|
|daemonsets deployments deployments/rollback deployments/scale ingresses networkpolicies replicasets replicasets/scale replicationcontrollers/scale|extensions|
|poddisruptionbudgets|policy|
|networkpolicies|networking.k8s.io|
|localsubjectaccessreviews|authorization.k8s.io|
|rolebindings roles|rbac.authorization.k8s.io|
|nodes pods|metrics.k8s.io|
|rolebindings roles|authorization.openshift.io|
|localresourceaccessreviews localsubjectaccessreviews subjectrulesreviews|authorization.openshift.io|
|rolebindingrestrictions|authorization.openshift.io|
|podsecuritypolicyreviews podsecuritypolicyselfsubjectreviews podsecuritypolicysubjectreviews|security.openshift.io
|buildconfigs buildconfigs/webhooks builds|build.openshift.io|
|builds/log|build.openshift.io|
|buildconfigs/instantiate buildconfigs/instantiatebinary builds/clone|build.openshift.io|
|builds/details|build.openshift.io|
|jenkins|build.openshift.io|
|deploymentconfigs deploymentconfigs/scale|apps.openshift.io |
|deploymentconfigrollbacks deploymentconfigs/instantiate deploymentconfigs/rollback|apps.openshift.io|
|deploymentconfigs/log deploymentconfigs/status|apps.openshift.io|
|imagestreamimages imagestreammappings imagestreams imagestreams/secrets imagestreamtags|image.openshift.io|
|imagestreams/status|image.openshift.io|
|imagestreams/layers|image.openshift.io|
|imagestreamimports|image.openshift.io|
|projects|project.openshift.io|
|appliedclusterresourcequotas|quota.openshift.io|
|routes|route.openshift.io|
|routes/custom-host|route.openshift.io|
|routes/status|route.openshift.io|
|processedtemplates templateconfigs templateinstances templates|template.openshift.io|
|networkpolicies|extensions networking.k8s.io|
|buildlogs|build.openshift.io|
|resourceaccessreviews subjectaccessreviews|authorization.openshift.io|