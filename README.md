### John Cuckovich

Platform and infrastructure automation engineer. I build the infrastructure other teams run in production: bare-metal provisioning through Redfish and Canonical MAAS, golden-image pipelines, VMware Cloud Foundation automation in Ansible and Python, HashiCorp Vault and AWS infrastructure, and the CI estate it all ships through. A career that began in carrier network operations keeps that work grounded in how the network underneath actually behaves.

**Selected work**

- [infra](https://github.com/jpcuckovi/infra): Ansible provisioning of a bare-metal lab estate, from kubeadm HA with Cilium and Longhorn to the shared registry and observability stack.
- [netbox-intent](https://github.com/jpcuckovi/netbox-intent): a network configured from a source of truth. NetBox holds the intent, Jinja2 renders each switch, and a gNMI push with commit-confirmed applies it to a Nokia SR Linux lab, verifies the whole network, and rolls back if anything fails.
- [vault-fargate-aurora](https://github.com/jpcuckovi/vault-fargate-aurora): HashiCorp Vault in high availability on AWS, with ECS Fargate, Aurora PostgreSQL and multi-region KMS.
- [pygnmi](https://github.com/jpcuckovi/pygnmi): a maintained fork of the pure-Python gNMI client.

**Focus:** Linux, bare metal and BMC lifecycle, VMware Cloud Foundation, Kubernetes, Vault, AWS, Ansible, Terraform, Python, and network automation.

[LinkedIn](https://www.linkedin.com/in/jpcuckovich/)
