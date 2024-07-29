# Multi-tier microservices application using Kubernetes

This project demonstrates a Multi-tier microservices application deployed on Kubernetes. The application consists of a voting system with the following microservices:

1. Voting App: Frontend application for voting.
2. Redis: In-memory data store for saving votes input.
3. Worker: Processes votes and stores the results in PostgreSQL.
4. PostgreSQL: Database for storing voting results.
5. Results App: Frontend application for displaying the voting results.

### Architecture diagram:-

![K8app](https://github.com/user-attachments/assets/5830c8ec-cb7b-4028-afbd-5de48d33aff2)

### Requirements:-
1. Docker
2. Kubernetes
3. kubectl
4. Minikube (Optional, for local development)
5. AWS CLI (Optional, For Amazon EKS)

