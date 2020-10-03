FROM pycontribs/centos:7
RUN true && \
    yum -y update && \
    yum -y install git sshpass && \
    yum -y clean all && \
    true
RUN true && \
    pip install --upgrade pip \
    pip install ansible \
    true
RUN localedef -f UTF-8 -i ja_JP ja_JP.UTF-8
ENV LANG="ja_JP.UTF-8" \
    LANGUAGE="ja_JP:ja" \
    LC_ALL="ja_JP.UTF-8"
CMD ["/sbin/init"]
