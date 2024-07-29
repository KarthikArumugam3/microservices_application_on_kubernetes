# Multi-tier microservices application using Kubernetes

This project demonstrates a Multi-tier microservices application deployed on Kubernetes. The application consists of a voting system with the following microservices:

1. Voting App: Frontend application for voting.
2. Redis: In-memory data store for saving votes input.
3. Worker: Processes votes and stores the results in PostgreSQL.
4. PostgreSQL: Database for storing voting results.
5. Results App: Frontend application for displaying the voting results.

### Architecture diagram:-

![K8app](https://github.com/user-attachments/assets/2df67b10-bd0f-4340-977b-07977b1d6a70)

### Requirements:-
1. Docker
2. Kubernetes
3. kubectl
4. Minikube (Optional, for local development)
5. AWS CLI (Optional, For Amazon EKS)

