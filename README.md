# ASD Project - Group 4

Kubernetes & Docker project.

## Useful Kubernetes commands

- `kubectl apply -f extract_job.yaml -n group4`: Create and start running the job
- `kubectl get job -n group4`: List all the jobs
- `kubectl get pods -n group4`: List all the pods with their full name
- `kubectl delete pod <pod_name> -n group4`: Delete a pod
- `kubectl delete job <job_name> -n group4`: Delete a job
- `kubectl delete deployment <deployment_name> -n group4`: Delete a deployment
- `kubectl delete --all job -n group4`: Delete every job in the group
- `kubectl exec -it <deployment_name> -n group4 -- ../bin/bash`: acces to the terminal (path to bash was incorrect)