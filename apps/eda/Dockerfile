FROM fedora:37

RUN dnf --assumeyes install java-17-openjdk python3-pip

RUN export JAVA_HOME=/usr/lib/jvm/java-17-openjdk

RUN pip3 install ansible ansible-rulebook ansible-runner

EXPOSE 9999