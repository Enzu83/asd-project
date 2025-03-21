# ASD Project - Group 4

Kubernetes & Docker project.

## Step 1

- `kubectl apply -f extract_job.yaml -n group4`: Start the Job
- `kubectl get job -n group4`: List the jobs
- `kubectl get pods -n group4`: List all the pods with the true name
- `kubectl delete pod <pod_name> -n group4`: Delete a pod
- `kubectl delete --all job -n group4`: Delete every job in the group
