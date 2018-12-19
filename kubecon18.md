
# Jamie's Kubecon 2018 trip notes #

> KubeCon + CloudNativeCon North America 2018

[URL](https://events.linuxfoundation.org/events/kubecon-cloudnativecon-north-america-2018/)

## Notable annoucements ##

- **Kubernetes 1.13 released**

*Kuberentes 1.13 was actually announced earlier this month, prior to KubeCon Seattle. This release continues to focus on stability and extensibility of Kubernetes with three major features that have graduated to general availability in the areas of  Storage and Cluster Lifecycle. Notable features include: simplified cluster management with kubeadm, Container Storage Interface (CSI), and CoreDNS as the default DNS*.

- **On Tuesday 11th December, VMware completed the acquisition of Heptio**.

*VMware paid $550 million for its recently closed acquisition of 2-year-old Kubernetes-focused startup Heptio. Heptio launched under the guise of making Kubernetes more accessible to developers running apps on-premises or in the public cloud. The company’s founders – Joe Beda and Craig McLuckie – formed Heptio having both been involved at Google on its Compute Engine and the platform that eventually became the open source Kubernetes project. Both remain active in the Kubernetes community*.

- **VMware annoucend NSX Service Mesh**.

*VMware announced the new service, which will be available early next year initially as part of Cloud PKS service in early 2019, at the Kubecon + CloudNativeCon conference, being held this week in Seattle. A stand-alone version will be ready later next year. Using the open source Istio as a foundation, VMware has introduced the VMware NSX Service Mesh to provide application-level visibility, control, and security for enterprise-grade microservices, all managed through a developer-friendly application interface (API)*.

- **Cloud Native Computing Foundation (CNCF) voted to accept **etcd** as an incubation-level hosted project**.

*etcd is a distributed key value store that provides a reliable way to manage the coordination state of distributed systems. etcd was first announced in June 2013 by CoreOS (part of Red Hat as of 2018). Since its adoption as part of Kubernetes in 2014, etcd has become a fundamental part of the Kubernetes cluster management software design, and the etcd community has grown exponentially. etcd is now being used in production environments at multiple companies, by large cloud providers such as AWS, Google Cloud Platform, Azure, and other on-premises Kubernetes implementations*.

- **Envoy has become a CNCF graduated project, joining Kubernetes and Prometheus**.

*Envoy’s goal is to abstract the network from application developers so that they can focus on business logic. In order to provide rich and easy to use abstractions for modern cloud native applications, Envoy focuses on the L7 or application layer of the stack. In addition to support for HTTP and gRPC, Envoy also supports Redis, Thrift, MongoDB, global rate limiting, external authentication and authorization, and many other features geared towards building modern distributed applications*.

- **Knative is becoming the defacto framework for running serverless on top of kubernetes**

*Serverless computing, also often referred to as functions-as-a-service, enables organizations to execute functions without the need to first provision a long-running persistent server. At KubeCon + CloudNativeCon 2018, multiple vendors including Red Hat, Google, SAP and IBM announced that they are coming together to support the open-source Knative project*.

## Key Takeaways ##

- **Istio** is the new black. KubeCon focus shifted largely away from Kubernetes (labelled as boring during the keynote) towards Service Mesh.
- Custome Resource Definitions (CRD) and Operators received a large amnount of airtime.

## Must See ##

### Kelsey Hightowers Keynote ###

[![Kelsey Hightowers Keynote](http://img.youtube.com/vi/oNa3xK2GFKY/0.jpg)](http://www.youtube.com/watch?v=oNa3xK2GFKY)

## Ecosystem projects to watch ##

- **gVisor** (gVisor is a user-space kernel that provides secure isolation for containers, while being more lightweight than a virtual machine)
- **Knative** (Knative components offer developers Kubernetes-native APIs for deploying serverless-style functions, applications, and containers to an auto-scaling runtime. Knative together with Kubernetes form a general purpose platform with the unique ability to run serveless, stateful, batch, and machine learning (ML) workloads alongside one another.)
- **KubeEdge** (KubeEdge is an open source system, an optimized version of kubelet on edge, extending native containerized application orchestration and device management to hosts at the Edge.)




## My Schedule ##

### Monday 10th ###

- Kubernetes and Service Mesh Workshop with VMware (all day)

### Tuesday 11th ###