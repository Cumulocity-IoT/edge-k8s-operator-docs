# Cumulocity IoT Edge Kubernetes Operator
* **[Overview](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#overview)**
* **[Architecture](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#architecture)**
* **[Getting Started](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#getting-started)**
	* **[System Requirements](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#system-requirements)**
		* **[K3s](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#k3s)**
		* **[K3d](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#k3d)**
	* **[Install Operator](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#install-operator)**
		* **[Requirements](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#requirements)**
		* **[Get Helm Charts](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#get-helm-charts)**
		* **[Deploy Edge Kubernetes Operator](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#deploy-edge-kubernetes-operator)**
	* **[Install Edge](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#install-edge)**
		* **[Requirements](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#requirements)**
		* **[Domain Name System (DNS) setup](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#domain-name-system-dns-setup)**
		* **[Label Kubernetes node](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#label-kubernetes-node)**
		* **[Prepare namespace](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#prepare-namespace)**
			* **[Create namespace](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#create-namespace)**
			* **[Create Secrets](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#create-secrets)**
		* **[Create Edge Custom Resource (CR)](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#create-edge-custom-resource-cr)**
		* **[Deploy Edge](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#deploy-edge)**
		* **[Create Services and Ingress routes](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#create-services-and-ingress-routes)**
		* **[Verify Edge deployment](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#verify-edge-deployment)**
	* **[Connect to Edge](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#connect-to-edge)**
	* **[Accessing logs](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#accessing-logs)**
	* **[Troubleshooting](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#troubleshooting)**
* **[Edge Custom Resource Definition](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#edge-custom-resource-definition)**
	* **[Configuration](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#configuration)**
	* **[Spec](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#spec)**
	* **[License Secret](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#license-secret)**
	* **[TLS Secret](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#tls-secret)**
	* **[Admin Credentials Secret](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#admin-credentials-secret)**
	* **[Cumulocity IoT Core configurations](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#cumulocity-iot-core-configurations)**
	* **[Cumulocity IoT Core values](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#cumulocity-iot-core-values)**
	* **[Microservices](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#microservices)**
	* **[Applications](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#applications)**
	* **[MongoDb](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#mongodb)**
	* **[MongoDB Credentials Secret](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#mongodb-credentials-secret)**
	* **[Microservices Registry](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#microservices-registry)**
	* **[Microservices Registry Credentials Secret](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#microservices-registry-credentials-secret)**
	* **[Microservices Registry TLS Secret](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#microservices-registry-tls-secret)**
	* **[Resource Limits Spec](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#resource-limits-spec)**
	* **[Software AG Registry Credentials Secret](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#software-ag-registry-credentials-secret)**
* **[Management](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#management)**
	* **[Modify Edge deployment](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#modify-edge-deployment)**
		* **[Example Configuration Change](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#example-configuration-change)**
	* **[Version upgrade](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#version-upgrade)**
		* **[Start the Upgrade](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#start-the-upgrade)**
	* **[Undeploy Edge](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#undeploy-edge)**
* **[Upgrade Operator](https://github.softwareag.com/IOTA/edge-k8s-operator/wiki/user-guide#upgrade-operator)**
