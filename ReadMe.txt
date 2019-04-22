Camel Project for Apache CXF code-first using Spring
=========================================================================

Instalar 

    mvn install

Antes del deploy JBoss Fuse  6.3 Karaf fabric

    features:install camel-velocity
    features:install camel-cxf


    osgi:install -s mvn:com.mycompany/camel-spring-cxf-code-first/1.0.0-SNAPSHOT

Ingrego al servicio 

    http://localhost:9292/cxf

Wsdl 
    http://localhost:9292/cxf/report/?wsdl

 Camel documentation

    http://camel.apache.org/
