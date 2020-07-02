

FROM quay.io/crw/plugin-java11-rhel8:latest
RUN cd /tmp ; \
    git clone https://github.com/ebramirez/quarkus-quickstarts.git && \
    cd quarkus-quickstarts/getting-started && \
    mvn clean compile && \
    chmod go+rw -R /home/jboss/.m2/repository/* && \
    rm /tmp/quarkus-quickstarts/ -rf
    
