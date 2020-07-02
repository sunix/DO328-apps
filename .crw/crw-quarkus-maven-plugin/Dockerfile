

FROM quay.io/crw/plugin-java11-rhel8:latest
USER jboss
RUN cd /tmp ; \
    git clone https://github.com/ebramirez/quarkus-quickstarts.git && \
    cd quarkus-quickstarts/getting-started && \
    mvn clean compile && \
    rm /tmp/quarkus-quickstarts/ -rf
    
