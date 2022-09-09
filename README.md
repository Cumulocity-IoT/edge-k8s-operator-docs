# Cumulocity IoT Edge Kubernetes Operator
* **[Overview](/user-guide#overview)**
* **[Architecture](/user-guide#architecture)**
* **[Getting Started](/user-guide#getting-started)**
	* **[System Requirements](/user-guide#system-requirements)**
		* **[K3s](/user-guide#k3s)**
		* **[K3d](/user-guide#k3d)**
	* **[Install Operator](/user-guide#install-operator)**
		* **[Requirements](/user-guide#requirements)**
		* **[Get Helm Charts](/user-guide#get-helm-charts)**
		* **[Deploy Edge Kubernetes Operator](/user-guide#deploy-edge-kubernetes-operator)**
	* **[Install Edge](/user-guide#install-edge)**
		* **[Requirements](/user-guide#requirements)**
		* **[Domain Name System (DNS) setup](/user-guide#domain-name-system-dns-setup)**
		* **[Label Kubernetes node](/user-guide#label-kubernetes-node)**
		* **[Prepare namespace](/user-guide#prepare-namespace)**
			* **[Create namespace](/user-guide#create-namespace)**
			* **[Create Secrets](/user-guide#create-secrets)**
		* **[Create Edge Custom Resource (CR)](/user-guide#create-edge-custom-resource-cr)**
		* **[Deploy Edge](/user-guide#deploy-edge)**
		* **[Create Services and Ingress routes](/user-guide#create-services-and-ingress-routes)**
		* **[Verify Edge deployment](/user-guide#verify-edge-deployment)**
	* **[Connect to Edge](/user-guide#connect-to-edge)**
	* **[Accessing logs](/user-guide#accessing-logs)**
	* **[Troubleshooting](/user-guide#troubleshooting)**
* **[Edge Custom Resource Definition](/user-guide#edge-custom-resource-definition)**
	* **[Configuration](/user-guide#configuration)**
	* **[Spec](/user-guide#spec)**
	* **[License Secret](/user-guide#license-secret)**
	* **[TLS Secret](/user-guide#tls-secret)**
	* **[Admin Credentials Secret](/user-guide#admin-credentials-secret)**
	* **[Cumulocity IoT Core configurations](/user-guide#cumulocity-iot-core-configurations)**
	* **[Cumulocity IoT Core values](/user-guide#cumulocity-iot-core-values)**
	* **[Microservices](/user-guide#microservices)**
	* **[Applications](/user-guide#applications)**
	* **[MongoDb](/user-guide#mongodb)**
	* **[MongoDB Credentials Secret](/user-guide#mongodb-credentials-secret)**
	* **[Microservices Registry](/user-guide#microservices-registry)**
	* **[Microservices Registry Credentials Secret](/user-guide#microservices-registry-credentials-secret)**
	* **[Microservices Registry TLS Secret](/user-guide#microservices-registry-tls-secret)**
	* **[Resource Limits Spec](/user-guide#resource-limits-spec)**
	* **[Software AG Registry Credentials Secret](/user-guide#software-ag-registry-credentials-secret)**
* **[Management](/user-guide#management)**
	* **[Modify Edge deployment](/user-guide#modify-edge-deployment)**
		* **[Example Configuration Change](/user-guide#example-configuration-change)**
	* **[Version upgrade](/user-guide#version-upgrade)**
		* **[Start the Upgrade](/user-guide#start-the-upgrade)**
	* **[Undeploy Edge](/user-guide#undeploy-edge)**
* **[Upgrade Operator](/user-guide#upgrade-operator)**
