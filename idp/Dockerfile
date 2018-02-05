FROM unicon/shibboleth-idp:latest

MAINTAINER Unicon, Inc.

ADD  shibboleth-idp/lib/*.jar /opt/shibboleth-idp/webapp/WEB-INF/lib/
COPY shibboleth-idp/ /opt/shibboleth-idp/
COPY shib-jetty-base/ /opt/shib-jetty-base/
