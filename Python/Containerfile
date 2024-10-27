FROM registry.access.redhat.com/ubi9/ubi-minimal
RUN microdnf install --nodocs --setopt install_weak_deps=0 -y tar  \
    && microdnf clean all -y
RUN rpm -ivh https://dl.fedoraproject.org/pub/epel/epel-release-latest-9.noarch.rpm
