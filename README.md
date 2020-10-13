# NiFi Container Image for OpenShift

Based on the Apache image from here: https://github.com/apache/nifi/tree/main/nifi-docker/dockerhub

oc create configmap nifi-keystore --from-file keystore.jks --from-file truststore.jks