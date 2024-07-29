# Multi-tier microservices application using Kubernetes

This project demonstrates a Multi-tier microservices application deployed on Kubernetes. The application consists of a voting system with the following microservices:

Voting App : Frontend application for voting.
Redis: In-memory data store for saving votes input.
Worker: Processes votes and stores the results in PostgreSQL.
PostgreSQL: Database for storing voting results.
Results App: Frontend application for displaying the voting results.

### Architecture diagram:-

![K8app](https://github.com/user-attachments/assets/1987beea-bd71-4e73-b944-c47f65e6630b)

### Requirements:-
1. Docker
2. Kubernetes
3. kubectl
4. Minikube (Optional, for local development)
5. AWS CLI (For Amazon EKS)

