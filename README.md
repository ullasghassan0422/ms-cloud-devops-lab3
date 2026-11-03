# Lab 3 — hello-app on Kubernetes with Terraform

Name:

Roll number:

## Part 1: first `terraform plan`

Paste the `Plan:` line and the summary above it.

```

Plan: 2 to add, 0 to change, 0 to destroy.

Changes to Outputs:
  + url = "http://localhost:8080"


```

## Part 1: `terraform output -raw url`

```

```

## Part 2: plan for the v1 → v2 image change

Paste the lines that show the image change, and the `Plan:` line.

```

```

## Part 3: plan that found the drift after `kubectl scale`

```

```

## Part 4: `kubectl get svc -A` showing dev and prod

```
C:\Users\MSIS\ms-cloud-devops-lab3\envs\prod>kubectl get svc -A
NAMESPACE     NAME         TYPE           CLUSTER-IP     EXTERNAL-IP   PORT(S)                  AGE
default       kubernetes   ClusterIP      10.96.0.1      <none>        443/TCP                  43m
dev           hello-app    LoadBalancer   10.96.58.243   172.18.0.7    8080:32362/TCP           47s
kube-system   kube-dns     ClusterIP      10.96.0.10     <none>        53/UDP,53/TCP,9153/TCP   43m
prod          hello-app    LoadBalancer   10.96.24.231   172.18.0.8    8090:32639/TCP           17s
```

## Break it: the error after deleting `terraform.tfstate`

```

```

## Break it: the wrong selector

What did you see, and how did you find the cause? One or two sentences.



## Screenshot

Save a browser screenshot as `screenshot.png` in the repository root.
