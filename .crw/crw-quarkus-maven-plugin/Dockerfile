

FROM quay.io/crw/plugin-java11-rhel8:latest
RUN cd /tmp ; \
    git clone https://github.com/ebramirez/quarkus-quickstarts.git && \
    cd quarkus-quickstarts/getting-started && \
    mvn clean compile && \
    chmod 666 -R /home/jboss/.m2 && \
    rm /tmp/quarkus-quickstarts/ -rf
    
