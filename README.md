# gitlab-runner-openshift
Gitlab runner for Kubernetes and OpenShift with auto register.


Create new project/namespace

oc new-project gitlab-runner

Import template

oc create -f https://raw.githubusercontent.com/peerapach/gitlab-runner-openshift/master/gitlab-runner-template.yml -n gitlab-runner
