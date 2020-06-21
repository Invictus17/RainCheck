A Distributed System that produces precipitation graphs given Nexrad radar location and date.

The developemnt of this project was three-fold:
1) Designed a scalable micoservice architecture and developed all the microservices from scratch.  
Please refer branch - Milestone-1.  
2) To migrate the system to the cloud, containerized all services, automated OpenStack cloud VM creation and Kubernetes setup using ansible and deployed it using a Jenkins CI/CD pipeline.  
Please refer branch - Milestone-2
3) Integrated Istio service mesh to the system to improve visibility and analyse telemetry data using Grafana and Kiali dashboards.  
Please refer branch - Milestone-2
