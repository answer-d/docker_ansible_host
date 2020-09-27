FROM pycontribs/centos:7
RUN true && \
    yum -y install git && \
    yum -y clean all && \
    true
RUN true && \
    pip install --upgrade pip \
    pip install ansible \
    true
CMD ["/sbin/init"]
