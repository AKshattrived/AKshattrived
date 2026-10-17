# Akshat Trivedi

I like understanding systems from the ground up. Not just how to build them, but what happens underneath, where things break, and why they were designed that way.

I've found myself working at quite different layers of the stack — setting up hypervisors on bare metal, running compute clusters, building backend services, and digging into production networking infrastructure.

### Some rabbit holes I've gone down

- **Networking:** Following traffic through Nginx, tunnel servers, and Envoy; digging into connection tracking, firewall policies, queue limits, and what happens when network resources get exhausted.

- **Reliability:** Building conntrack health signals and Kubernetes readiness probes, designing resilient feature-flag fallbacks, and figuring out how rate limits and configuration policies should behave when dependencies fail or services restart.

- **Observability:** Building TLS certificate monitoring that lets engineers inspect certificate state and expiry without logging into production containers. Getting that data from Nginx through Unix sockets, MDSD, Geneva, and Kusto, and turning it into dashboards and proactive alerts. Also setting up Prometheus and Grafana to monitor compute infrastructure, lab temperatures, and freezers.

- **Infrastructure & automation:** Installing Proxmox on bare-metal servers, using Ansible for provisioning and configuration, managing HPC workloads, building and maintaining CI/CD pipelines, and handling Kubernetes deployments, rollouts, and troubleshooting. More recently, automating container builds, deployments, rollout validation, and failure diagnosis using agent-assisted workflows.

- **Cloud & data systems:** Designing AWS architectures with compute, networking, storage, and serverless services; building data ingestion pipelines and working with large datasets, storage systems, and the tradeoffs between different architectures.

Lately, I've been exploring agent runtimes, sandboxed execution, and how agents can safely interact with real infrastructure.

I mostly write Go and Python, with some C++ and Rust along the way. I'm getting into open source — reading unfamiliar codebases, understanding design decisions, and looking for useful things to contribute.

Outside of computers: gaming, photography, cooking, and woodworking.
