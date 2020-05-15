FROM registry.access.redhat.com/ubi7/ubi

RUN yum-config-manager --enable rhel-7-server-optional-rpms \
yum install -y yum-plugin-priorities \
yum clean all
RUN sed -i 's/.*ubi-7-server.*/&\npriority = 10/' /etc/yum.repos.d/ubi.repo
