
# Kubernetes Pods

## Objective
Learn how Kubernetes Pods work and how containers run inside them.

---

## Topics Covered
- Single Container Pod
- Multi-Container Pod
- Pod Lifecycle
- Pod Logs
- Pod Debugging

---

## YAML Files
- nginx-pod.yaml
- busybox-pod.yaml
- multi-container-pod.yaml

---

## Commands Used

```bash
kubectl apply -f nginx-pod.yaml

kubectl get pods

kubectl describe pod nginx-pod

kubectl logs nginx-pod
```

---

## Hands-On Practice

- Created nginx pod
- Checked pod logs
- Used describe command
- Executed commands inside container
- Simulated pod failure

---

## Key Learning

Pods are the smallest deployable units in Kubernetes and can contain one or more tightly coupled containers.
