#
# This image adds the repository link for Origin
# RPMs to allow downstream images to install the
# components using `yum'.
#
# The standard name for this image is openshift/origin-source
#
FROM centos:7

ADD origin-local-release.repo /etc/yum.repos.d/
ADD centos-paas-sig-openshift-origin36.repo /etc/yum.repos.d/
