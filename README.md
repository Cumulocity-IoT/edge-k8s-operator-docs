# Cumulocity IoT Edge Kubernetes Operator User Guide

* **[Overview](01-overview)**
* **[Architecture](02-architecture)**
* **[Getting Started](03-getting-started)**
    * **[System Requirements](03-getting-started#system-requirements)**
        * **[K3s](03-getting-started#k3s)**
        * **[K3d](03-getting-started#k3d)**
    * **[Install Operator](03-getting-started#install-operator)**
        * **[Requirements](03-getting-started#requirements)**
        * **[Get Helm Charts](03-getting-started#get-helm-charts)**
        * **[Deploy Edge Kubernetes Operator](03-getting-started#deploy-edge-kubernetes-operator)**
    * **[Install Edge](03-getting-started#install-edge)**
        * **[Requirements](03-getting-started#requirements)**
        * **[Domain Name System (DNS) setup](03-getting-started#domain-name-system-dns-setup)**
        * **[Label Kubernetes node](03-getting-started#label-kubernetes-node)**
        * **[Prepare namespace](03-getting-started#prepare-namespace)**
            * **[Create namespace](03-getting-started#create-namespace)**
            * **[Create Secrets](03-getting-started#create-secrets)**
        * **[Create Edge Custom Resource (CR)](03-getting-started#create-edge-custom-resource-cr)**
        * **[Deploy Edge](03-getting-started#deploy-edge)**
        * **[Create Services and Ingress routes](03-getting-started#create-services-and-ingress-routes)**
        * **[Verify Edge deployment](03-getting-started#verify-edge-deployment)**
    * **[Connect to Edge](03-getting-started#connect-to-edge)**
    * **[Accessing logs](03-getting-started#accessing-logs)**
    * **[Troubleshooting](03-getting-started#troubleshooting)**
* **[Edge Custom Resource Definition](04-edge-custom-resource-definition)**
    * **[Configuration](04-edge-custom-resource-definition#configuration)**
    * **[Spec](04-edge-custom-resource-definition#spec)**
    * **[License Secret](04-edge-custom-resource-definition#license-secret)**
    * **[TLS Secret](04-edge-custom-resource-definition#tls-secret)**
    * **[Admin Credentials Secret](04-edge-custom-resource-definition#admin-credentials-secret)**
    * **[Cumulocity IoT Core configurations](04-edge-custom-resource-definition#cumulocity-iot-core-configurations)**
    * **[Cumulocity IoT Core values](04-edge-custom-resource-definition#cumulocity-iot-core-values)**
    * **[Microservices](04-edge-custom-resource-definition#microservices)**
    * **[Applications](04-edge-custom-resource-definition#applications)**
    * **[MongoDb](04-edge-custom-resource-definition#mongodb)**
    * **[MongoDB Credentials Secret](04-edge-custom-resource-definition#mongodb-credentials-secret)**
    * **[Microservices Registry](04-edge-custom-resource-definition#microservices-registry)**
    * **[Microservices Registry Credentials Secret](04-edge-custom-resource-definition#microservices-registry-credentials-secret)**
    * **[Microservices Registry TLS Secret](04-edge-custom-resource-definition#microservices-registry-tls-secret)**
    * **[Resource Limits Spec](04-edge-custom-resource-definition#resource-limits-spec)**
    * **[Software AG Registry Credentials Secret](04-edge-custom-resource-definition#software-ag-registry-credentials-secret)**
* **[Management](05-management)**
    * **[Modify Edge deployment](05-management#modify-edge-deployment)**
        * **[Example Configuration Change](05-management#example-configuration-change)**
    * **[Version upgrade](05-management#version-upgrade)**
        * **[Start the Upgrade](05-management#start-the-upgrade)**
    * **[Undeploy Edge](05-management#undeploy-edge)**
* **[Upgrade Operator](06-upgrade-operator)**
