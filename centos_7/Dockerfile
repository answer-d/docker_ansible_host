FROM pycontribs/centos:7
RUN true && \
    yum -y install git sshpass && \
    yum -y clean all && \
    true
RUN true && \
    pip install --upgrade pip \
    pip install ansible \
    true
RUN echo 'LANG="ja_JP.UTF-8" > /etc/locale.conf'
CMD ["/sbin/init"]
