

FROM registry.redhat.io/codeready-workspaces/plugin-java11-rhel8:2.2
RUN cd /tmp ; \
    git clone https://github.com/ebramirez/quarkus-quickstarts.git && \
    cd quarkus-quickstarts/getting-started && \
    mvn clean compile && \
    rm /tmp/uarkus-quickstarts/ -rf
    
