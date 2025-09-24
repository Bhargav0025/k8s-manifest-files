# k8s-manifest-files
├── dev/
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── configmap.yaml
│   ├── ingress.yaml  (optional but useful)
│   └── autoscale.yaml  (optional for dev, useful in QA/Staging/Prod)
k8s/qa/
├── deployment.yaml
├── service.yaml
├── configmap.yaml
├── ingress.yaml
└── autoscale.yaml



Summary:

apiVersion & kind --  define the resource type.
metadata includes -- name, namespace, and labels.
spec configures-- replicas, update strategy, pod selector, and pod template.
container config --  defines the image, ports, environment variables, health probes, and resource limits.
