# World of Microservices
## Mentality of cloud native - Pet vs Cattle
    • Infra becomes immutable & disposable 
    • Provisioned in minutes & destroyed on demand 
    • Only re provisioning, no update or patching
    
## Greenfield VS Brownfield
    • Greenfield - new project 
    . Brownfield projects - legacy project
    
## Generic tools Micro services
### Orchestration 
    • Kubernetes
    • Helm chart
### Observability & Analysis
    • Prometheus
    • Fluentd
    • Jaeger
    • Open tracing
### Service proxy, discovery & Mesh
    • CoreDNS - service discovery
    • Envoy & Linkerd - mesh architecture & health check, routing & load balancing
    • 
### Networking, Policy & Security
    • CNI - for networking use - Calico, Flannel or Weave Net
    • Open Policy Agent - general purpose policy engine
    . Falco - anomaly detection engine for cloud native

## Containers
    • Move faster by deploying smaller units
    • Use fewer resources
    • Fit more into the same host
    • Faster automation
    • Portability
    • Isolation

## VM vs Container
    - virtual machine
        • Larger footprint 
        • Slower to boot 
        • Ideal for long running tasks
    - container 
        • Lightweight 
        • Quick to start (you don't have to boot) 
        • Portable 
        • Ideal for short lived tasks
    

### Layers of the Container
    1. Base OS ( win/linux/mac)
    2. Customisations
    3. Application (on top)

## Orchestrators
    • Manage
        ○ Infrastructure
        ○ Containers
        ○ Deployment
        ○ Scaling
        ○ Failover
        ○ Health monitoring
        ○ App upgrades, Zero-Downtime deployments
    • Install your own
        ○ Kubernetes, Swarm, Service Fabric
    • Orchestration as a Service
        ○ Azure Kubernetes Service, Service Fabric

