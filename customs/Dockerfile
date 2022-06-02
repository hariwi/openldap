#Pull the latest base image from Dockerhub

FROM osixia/openldap

# Set the environment variables

ENV LDAP_ORGANISATION="myldap rhocp Name" \

LDAP_DOMAIN="myldap.rhocp.demo" \

LDAP_BASE_DN="dc=myldap,dc=rhocp,dc=demo"

COPY bootstrap.ldif /container/service/slapd/assets/config/bootstrap/ldif/50-bootstrap.ldif
