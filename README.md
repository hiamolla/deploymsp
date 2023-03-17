# altschool-cloud-examination-kubernetes-project



 flux bootstrap github \
--components-extra=image-reflector-controller,image-automation-controller \
--owner=$GITHUB_USER \
--repository=flux-repo \
--branch=main \
--path=./clusters/my-cluster \
--personal
