FROM sdaschner/open-liberty:javaee8-jdk11-b3

ADD http://central.maven.org/maven2/org/postgresql/postgresql/9.4.1212/postgresql-9.4.1212.jar ${INSTALL_DIR}lib/postgresql-9.4.1212.jar

COPY postgres-driver.xml ${CONFIG_DIR}configDropins/defaults/
