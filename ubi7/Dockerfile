FROM registry.access.redhat.com/ubi8/ubi

RUN yum-config-manager --enable rhel-7-server-optional-rpms \
yum install -y yum-plugin-priorities \
sed -i 's/.*ubi-7-server.*/&\npriority = 10/' /etc/yum.repos.d/ubi.repo
