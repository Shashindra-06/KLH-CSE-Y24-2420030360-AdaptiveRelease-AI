 
DEPARTMENT OF CSE
PROJECT ABSTRACT SUBMISSION
COURSE: ENGINEERING CAPSTONE PROJECT -1(23IE4053R/23IE4053A)                            A.Y. 2026 - 2027
TITLE OF THE PROJECT	

AI-Driven Adaptive Canary Deployment and Release Risk Prediction for Cloud-Native Applications

S. No.	University ID	Name
1	2420030360	Pakkiru Shashindra Reddy
2	2420090124	Chandu Gnana Sree Susheel
3	2420030724	Padiga Tejesh

Name of the Guide	Rajkumar Patil 











Project Abstract:
Modern cloud-native applications are continuously updated through frequent software releases, 
but deploying a new version directly to all users can introduce performance degradation, failures,
and service disruptions. This project proposes an AI-Driven Adaptive Canary Deployment and Release Risk Prediction system 
that combines Artificial Intelligence, Cloud Computing, MLOps, DevOps, and Adaptive Software Engineering to make software deployments safer 
and more intelligent. The system deploys a new application version alongside a stable version using Kubernetes and gradually exposes it to a
controlled percentage of users through canary deployment. Runtime metrics such as CPU utilization, memory usage, request rate, response latency,
error rate, HTTP 5xx responses, and pod health are continuously collected using Prometheus and visualized through Grafana. Machine learning models,
such as XGBoost, analyze these metrics to predict the probability of release failure or performance degradation. Based on the predicted risk,
an adaptive decision engine dynamically increases or decreases canary traffic, pauses the deployment, promotes the new version,
or automatically triggers a rollback. The ML lifecycle is managed using MLflow, while Docker, GitHub Actions, Argo CD, and Argo Rollouts support containerization, 
CI/CD, GitOps, and progressive delivery. DevSecOps practices using SonarQube, Trivy, and OWASP ZAP are integrated to identify security issues before deployment.
The complete system is designed to operate on AWS and demonstrates a closed-loop Observe–Analyze–Decide–Adapt approach, 
enabling cloud applications to continuously respond to changing runtime conditions and make intelligent, reliable deployment decisions with minimal human intervention.
