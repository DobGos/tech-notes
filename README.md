# Dob's Tech notes

### Import certificate to JDK (e.g. needed for mvn connections to nexus servers)
sudo keytool -alias [MY-ALIAS] -keystore $JAVA_HOME/jre/lib/security/cacerts -importcert -file ~/[CERT_TO_IMPORT.crt]
