#FROM registry.access.redhat.com/ubi8/ubi:8.0
FROM registry.access.redhat.com/ubi8/openjdk17
RUN microdnf update -y
ADD info.sh /tmp
CMD /tmp/info.sh
