Infrastructure
--------------
IT manages infrastructure as code when possible. It is operated in a continuous delivery and continuous integration pipeline. Systems are orchestrated from a central platform, allowing a rapidly scalable infrastructure and minimizing human errors by automating deployments. Rubin Observatory software is fully integrated into this platform.

Production environment consists of virtual machines and containers running in physical clusters. Testing and development infrastructure has local resources but also leverages cloud computing resources.

The platform to deploy infrastructure includes:

- Infrastructure automation - `Puppet <https://puppet.com/>`_
- Orchestration - `Kubernetes <https://kubernetes.io/>`_
- Automated user provisioning - `FreeIPA <https://www.freeipa.org>`_

The objective is to provide highly available systems and rapidly scalable platforms.

The project in general favors open source software but uses licensed software when that is the best option.

For details about the deployment platform please review https://ittn-002.lsst.io/

For details of the Puppet standards please review https://ittn-005.lsst.io/
