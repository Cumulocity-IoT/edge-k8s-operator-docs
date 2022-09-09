# Cumulocity IoT Edge Kubernetes Operator
* **[Overview](/guides/user-guide#overview)**
* **[Architecture](/guides/user-guide#architecture)**
* **[Getting Started](/guides/user-guide#getting-started)**
	* **[System Requirements](/guides/user-guide#system-requirements)**
		* **[K3s](/guides/user-guide#k3s)**
		* **[K3d](/guides/user-guide#k3d)**
	* **[Install Operator](/guides/user-guide#install-operator)**
		* **[Requirements](/guides/user-guide#requirements)**
		* **[Get Helm Charts](/guides/user-guide#get-helm-charts)**
		* **[Deploy Edge Kubernetes Operator](/guides/user-guide#deploy-edge-kubernetes-operator)**
	* **[Install Edge](/guides/user-guide#install-edge)**
		* **[Requirements](/guides/user-guide#requirements)**
		* **[Domain Name System (DNS) setup](/guides/user-guide#domain-name-system-dns-setup)**
		* **[Label Kubernetes node](/guides/user-guide#label-kubernetes-node)**
		* **[Prepare namespace](/guides/user-guide#prepare-namespace)**
			* **[Create namespace](/guides/user-guide#create-namespace)**
			* **[Create Secrets](/guides/user-guide#create-secrets)**
		* **[Create Edge Custom Resource (CR)](/guides/user-guide#create-edge-custom-resource-cr)**
		* **[Deploy Edge](/guides/user-guide#deploy-edge)**
		* **[Create Services and Ingress routes](/guides/user-guide#create-services-and-ingress-routes)**
		* **[Verify Edge deployment](/guides/user-guide#verify-edge-deployment)**
	* **[Connect to Edge](/guides/user-guide#connect-to-edge)**
	* **[Accessing logs](/guides/user-guide#accessing-logs)**
	* **[Troubleshooting](/guides/user-guide#troubleshooting)**
* **[Edge Custom Resource Definition](/guides/user-guide#edge-custom-resource-definition)**
	* **[Configuration](/guides/user-guide#configuration)**
	* **[Spec](/guides/user-guide#spec)**
	* **[License Secret](/guides/user-guide#license-secret)**
	* **[TLS Secret](/guides/user-guide#tls-secret)**
	* **[Admin Credentials Secret](/guides/user-guide#admin-credentials-secret)**
	* **[Cumulocity IoT Core configurations](/guides/user-guide#cumulocity-iot-core-configurations)**
	* **[Cumulocity IoT Core values](/guides/user-guide#cumulocity-iot-core-values)**
	* **[Microservices](/guides/user-guide#microservices)**
	* **[Applications](/guides/user-guide#applications)**
	* **[MongoDb](/guides/user-guide#mongodb)**
	* **[MongoDB Credentials Secret](/guides/user-guide#mongodb-credentials-secret)**
	* **[Microservices Registry](/guides/user-guide#microservices-registry)**
	* **[Microservices Registry Credentials Secret](/guides/user-guide#microservices-registry-credentials-secret)**
	* **[Microservices Registry TLS Secret](/guides/user-guide#microservices-registry-tls-secret)**
	* **[Resource Limits Spec](/guides/user-guide#resource-limits-spec)**
	* **[Software AG Registry Credentials Secret](/guides/user-guide#software-ag-registry-credentials-secret)**
* **[Management](/guides/user-guide#management)**
	* **[Modify Edge deployment](/guides/user-guide#modify-edge-deployment)**
		* **[Example Configuration Change](/guides/user-guide#example-configuration-change)**
	* **[Version upgrade](/guides/user-guide#version-upgrade)**
		* **[Start the Upgrade](/guides/user-guide#start-the-upgrade)**
	* **[Undeploy Edge](/guides/user-guide#undeploy-edge)**
* **[Upgrade Operator](/guides/user-guide#upgrade-operator)**
