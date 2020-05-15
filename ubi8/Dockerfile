FROM registry.access.redhat.com/ubi8/ubi

RUN yum update -y \
yum clean all
RUN sed -i 's/.*ubi-8-baseos.*/&\npriority = 10/' /etc/yum.repos.d/ubi.repo
