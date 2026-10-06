# Awesome DevOps with stars

<p align="center">
  <a href="https://awesome-devops.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/readme-banner-dark.png">
      <img alt="Awesome DevOps" src=".github/assets/readme-banner-light.png" width="640">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://awesome-devops.xyz"><img alt="Website" src="https://img.shields.io/website?url=https%3A%2F%2Fawesome-devops.xyz&label=website&up_message=online&up_color=2f9e5b&down_message=offline&style=flat-square&labelColor=141518"></a>
  <a href="https://awesome-devops.xyz"><img alt="Tools in the list" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fawesome-devops.xyz%2Fbadge%2Ftools.json&style=flat-square&cacheSeconds=3600"></a>
  <a href="https://github.com/wmariuss/awesome-devops/actions/workflows/links-validator.yml"><img alt="Links" src="https://img.shields.io/github/actions/workflow/status/wmariuss/awesome-devops/links-validator.yml?branch=main&label=links&style=flat-square&labelColor=141518"></a>
  <a href="CONTRIBUTING.md"><img alt="Contributions welcome" src="https://img.shields.io/badge/contributions-welcome-e0b84a?style=flat-square&labelColor=141518"></a>
</p>

> A curated list of platforms, tools, practices and resources to create, improve DevOps culture and SRE Team in the organization.

DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes. This speed enables organizations to better serve their customers and compete more effectively in the market.

Browse, search and filter the list at **[awesome-devops.xyz](https://awesome-devops.xyz)**.

Each entry ends with tags: `oss` open source, `free` free plan or free to use, `paid` paid plans or support, `self-hosted` can run on your own infrastructure without being open source.

## Contents

* [Cloud Platforms](#cloud-platforms)
* [Open Source Cloud Platforms](#open-source-cloud-platforms)
* [Operating Systems](#operating-systems)
* [Package Management & System Configuration](#package-management--system-configuration)
* [Distributed Filesystems](#distributed-filesystems)
* [Applications Platforms](#applications-platforms)
* [Internal Developer Platforms](#internal-developer-platforms)
* [Container Image Registry](#container-image-registry)
* [Automation & Orchestration](#automation--orchestration)
* [Productivity Tools](#productivity-tools)
* [Continuous Integration & Delivery](#continuous-integration--delivery)
* [Source Code Management](#source-code-management)
* [Web Servers](#web-servers)
* [SSL](#ssl)
* [Databases](#databases)
* [Observability and Monitoring](#observability--monitoring)
* [Service Discovery & Service Mesh](#service-discovery--service-mesh)
* [Chaos Engineering](#chaos-engineering)
* [API Gateway](#api-gateway)
* [Code review](#code-review)
* [Distributed messaging](#distributed-messaging)
* [Programming Languages](#programming-languages)
* [Chat and ChatOps](#chat-and-chatops)
* [Secret Management](#secret-management)
* [Security](#security)
* [Sharing](#sharing)
* [VPN](#vpn)
* [Resources](#resources)
  * [Books](#books)
  * [Conferences](#conferences)
  * [Blogs](#blogs)
  * [DevOps Roadmap](#devops-roadmap)

***

## Cloud Platforms

*Public and Private Cloud Platforms.*

* [Amazon Web Services (AWS)](https://aws.amazon.com/) - Cloud Computing Services. `free` `paid`
* [Google Cloud Platform (GCP)](https://cloud.google.com/) - Cloud Computing Services. `free` `paid`
* [Azure](https://azure.microsoft.com/) - Cloud Computing Platform & Services. `free` `paid`
* [Alibaba Cloud](https://us.alibabacloud.com/) - Integrated suite of cloud products and services. `free` `paid`
* [Oracle Cloud](https://www.oracle.com/cloud/) - Comprehensive and fully integrated stack of cloud applications and platform services. `free` `paid`
* [DigitalOcean](https://www.digitalocean.com/) - Helping developers easily build, test, manage, and scale applications of any size. `paid`
* [Scaleway](https://www.scaleway.com/) - Single way to create, deploy and scale your infrastructure in the cloud. `paid`
* [Vultr](https://www.vultr.com/) - Easily deploy cloud servers, bare metal, and storage worldwide. `paid`
* [IBM Cloud](https://www.ibm.com/cloud) - Tools, data & APIs to make AI real now. `free` `paid`
* [Interserver](https://www.interserver.net/) - Cloud VPS, Linux VPS, Windows VPS, dedicated servers and web hosting services. `paid`
* [Linode](https://linode.com/) - Accelerate innovation in the cloud, virtual computing must be more accessible, affordable, and simple. `paid`
* [Kinsta](https://kinsta.com/application-hosting/) - Create and deploy web applications and databases in minutes. `free` `paid`
* [Equinix](https://www.equinix.com/) - Global data center and colocation provider for enterprise network and cloud computing. `paid`
* [Clever Cloud](https://clever.cloud/) - European Platform as a Service (PaaS) with managed databases and object storage. `paid`

## Open Source Cloud Platforms

*Private, Public and Hybrid open-source Cloud Platforms.*

* [Localstack](https://github.com/localstack/localstack) ⚠️ Archived - Fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline. `oss` `paid`
* [Fakecloud](https://github.com/faiscadev/fakecloud) ⭐ 741 | 🐛 4 | 🌐 Rust | 📅 2026-10-06 - Free, open-source local AWS cloud emulator for development and testing. `oss`
* [Openstack](https://www.openstack.org/) - Open source software for creating private and public clouds. `oss`
* [Apache CloudStack](https://cloudstack.apache.org/) - Designed to deploy and manage large networks of virtual machines. `oss`
* [OpenNebula](https://opennebula.org/) - Build Private Clouds and manage Data Center virtualization based on KVM, LXD and VMware. `oss` `paid`
* [Eucalyptus](https://www.eucalyptus.cloud/) - Building AWS-compatible private and hybrid clouds. `oss`
* [DC/OS](https://dcos.io/) - Distributed operating system based on the Apache Mesos distributed systems kernel. `oss`
* [Apache Mesos](http://mesos.apache.org/) - Program against your data center like it’s a single pool of resources. `oss`

## Operating Systems

*Operating Systems - Server Platform.*

* [Ubuntu](https://ubuntu.com/) - Enterprise Open Source and Linux. `oss` `paid`
* [Rocky Linux](https://rockylinux.org/) - Open-source enterprise operating system designed to be 100% bug-for-bug compatible with Red Hat Enterprise Linux. `oss`
* [CoreOS](http://coreos.com/) - The pioneering lightweight container host. `oss`
* [OSv](http://osv.io/) - Versatile modular unikernel designed to run unmodified Linux applications securely on micro-VMs in the cloud. `oss`
* [Atomic](http://www.projectatomic.io/) - Use immutable infrastructure to deploy and scale your containerized applications. `oss`
* [Talos Linux](https://www.siderolabs.com/talos-linux) - Minimal, immutable Linux distribution for running Kubernetes, managed through an API. `oss` `paid`
* [Photon](https://github.com/vmware/photon) ⭐ 3,178 | 🐛 248 | 🌐 C | 📅 2026-10-05 - Linux container host optimized for cloud-native applications, cloud platforms, and VMware infrastructure. `oss`

## Package Management & System Configuration

*Builds packages in isolation from each other.*

* [Nix/NixOS](https://nixos.org/) - A tool that takes a unique approach to package management and system configuration. `oss`

## Distributed Filesystems

*Network distributed filesystems.*

* [Ceph](https://ceph.io/en/) - Highly scalable object, block and file-based storage under one whole system. `oss`
* [Gluster](https://www.gluster.org/) - Free and open source software scalable network filesystem. `oss`
* [LINBIT](https://www.linbit.com/en/) - Create, remove, and replicate block storage devices for datacenter scale environments. `oss` `paid`
* [XtreemFS](http://www.xtreemfs.org/) - Fault-tolerant distributed file system for all storage needs. `oss`
* [min.io](https://min.io/) - High-performance, distributed object storage system. `oss` `paid`

## Applications Platforms

*Applications management platforms, Containers platform and Containers management.*

* [Docker Compose](https://github.com/docker/compose) ⭐ 38,289 | 🐛 92 | 🌐 Go | 📅 2026-10-02 - Define and run multi-container applications with Docker. `oss`
* [Podman](https://github.com/containers/podman) ⭐ 33,002 | 🐛 1,024 | 🌐 Go | 📅 2026-10-05 - A tool for managing OCI containers and pods. `oss`
* [Piku](https://github.com/piku/piku) ⭐ 6,604 | 🐛 6 | 🌐 Python | 📅 2026-09-04 - The tiniest PaaS you've ever seen. Piku allows you to do git push deployments to your own servers. `oss`
* [Docker Swarm](https://github.com/docker/swarm) ⚠️ Archived - Docker-native clustering system. `oss`
* [AppScale](https://github.com/AppScale/appscale) ⭐ 2,421 | 🐛 52 | 🌐 Python | 📅 2024-05-22 - Easy-to-manage serverless platform for building and running scalable web and mobile applications. `oss`
* [Openshift](https://www.openshift.com/) - The Kubernetes platform for big ideas. `paid` `self-hosted`
* [Cycle.io](https://cycle.io/) - DevOps platform for building platforms. Handle container orchestration, load-balancing, monitoring, and more from a single control plane. `paid`
* [Dokku](https://dokku.com/) - Helps you build and manage the lifecycle of applications. `oss` `paid`
* [Cloud 66](https://www.cloud66.com/) - DevOps as a service that helps to build, deploy and manage any application on any cloud or server. `paid`
* [Docker](https://www.docker.com/) - Create, deploy, and run applications by using containers. `oss` `paid`
* [Kubernetes](https://kubernetes.io/) - Automating deployment, scaling, and management of containerized applications. `oss`
* [LXC](https://linuxcontainers.org/) - Lets Linux users easily create and manage system or application containers. `oss`
* [Rancher](https://rancher.com/) - Lets you deliver Kubernetes-as-a-Service. `oss` `paid`
* [Singularity](https://sylabs.io/singularity/) - Run the application from the local environment to the cloud. `oss` `paid`
* [Kata Containers](https://katacontainers.io/) - Building lightweight virtual machines that seamlessly plug into the containers ecosystem. `oss`
* [K3S](https://k3s.io/) - The certified Kubernetes distribution built for IoT and Edge computing. `oss`
* [OrbStack](https://orbstack.dev/) - fast, light, and easy way to run Docker containers and Linux on MacOS. `free` `paid`
* [Canine](https://canine.sh/) - Deploy applications to Kubernetes as easily as deploying to Heroku. `oss` `paid`
* [AZIN](https://azin.run/) - BYOC deployment platform. Deploy to your own GCP account with git-push, no Kubernetes config needed. GKE Autopilot under the hood. `paid`
* [vCluster](https://vcluster.sh/) - A open source project that helps you create virtual clusters. `oss` `paid`
* [devpod](https://devpod.sh/) - Open-source, codebases-like tool that creates reproducible developer environments, supporting numerous providers (Kubernetes, AWS, GCP, etc.). `oss`
* [KubeStellar Console](https://console.kubestellar.io/) - Open source AI-powered multi-cluster Kubernetes dashboard with real-time observability, AI-guided operations, and 20+ CNCF integrations (Argo, Kyverno, Prometheus, Grafana, Istio, Flux, Falco, OPA/Gatekeeper). CNCF Sandbox project. `oss`

## Internal Developer Platforms

*Tools, services and processes that support and accelerate software development.*

* [Qovery](https://www.qovery.com/) - Enterprise Kubernetes management platform for deploying applications on AWS, GCP, Azure, and Scaleway. Includes Terraform provider, CLI, API, and an [AI Agent Skill](https://github.com/Qovery/qovery-skills) ⭐ 12 | 🐛 2 | 🌐 Shell | 📅 2026-09-25 for deploying from AI coding tools like Claude Code, Cursor, and OpenCode. `free` `paid`
* [Port](https://www.getport.io/) - A platform for building no-code, holistic, Internal Developer Portals. `free` `paid` `self-hosted`
* [Backstage](https://backstage.io/) - An open platform for building developer portals. `oss`
* [Kratix](https://kratix.io/) - A framework used by platform teams to build the custom platforms tailored to their organisation. `oss` `paid`
* [OpenChoreo](https://openchoreo.dev/) - A complete, modular, open-source developer platform. `oss`

## Container Image Registry

*Container Image registry.*

* [Dockyard](https://github.com/Huawei/dockyard) ⭐ 278 | 🐛 12 | 🌐 Go | 📅 2023-04-12 - Container & Artifact Repository. `oss`
* [Quay](https://www.projectquay.io/) - Container image registry that enables you to build, organize, distribute, and deploy containers. `oss` `paid`
* [Harbor](https://goharbor.io/) - An open source trusted cloud native registry project that stores, signs, and scans content. `oss`
* [GitHub Container Registry](https://github.blog/2020-09-01-introducing-github-container-registry/) - Container registry free for public images. `free` `paid`

## Automation & Orchestration

*Tools for automation, orchestration, deployment, provisioning and configuration management.*

* [OctoDNS](https://github.com/github/octodns) ⭐ 3,772 | 🐛 3 | 🌐 Python | 📅 2026-10-05 - Managing DNS across multiple providers. DNS as code. `oss`
* [Ignite](https://github.com/weaveworks/ignite) ⚠️ Archived - Open Source Virtual Machine (VM) manager with a container UX and built-in GitOps management. `oss`
* [Servy](https://github.com/aelassas/servy) ⭐ 2,039 | 🐛 2 | 🌐 C# | 📅 2026-10-05 - Runs any application as a native Windows service, with logging, health checks and restart policies. `oss`
* [Selefra](https://github.com/selefra/selefra) ⭐ 545 | 🐛 0 | 🌐 Go | 📅 2023-08-30 - An open-source policy-as-code software that provides analytics for multi-cloud and SaaS. `oss`
* [Ansible](https://www.ansible.com/) - Simple IT automation platform that makes your applications and systems easier to deploy. `oss` `paid`
* [Salt](https://saltproject.io/) - Automate the management and configuration of any infrastructure or application at scale. `oss`
* [Puppet](https://puppet.com/) - Unparalleled infrastructure automation and delivery. `oss` `paid`
* [Chef](https://www.chef.io/) - Automate infrastructure and applications. `oss` `paid`
* [Juju](https://jaas.ai/) - Simplifies how you configure, scale and operate today's complex software. `oss` `paid`
* [Rundeck](https://www.rundeck.com/) - Runbook Automation For Modernizing Your Operations. `oss` `paid`
* [StackStorm](https://stackstorm.com/) - Connects all your apps, services, and workflows. Automate DevOps your way. `oss`
* [Bosh](https://www.cloudfoundry.org/bosh/) - Release engineering, deployment, and lifecycle management of complex distributed systems. `oss`
* [Cloudify](https://cloudify.co/) - Connect, Control, & Automate from core to edge: unlimited locations, clouds and devices. `oss` `paid`
* [Tsuru](https://tsuru.io/) - An extensible and open source Platform as a Service software. `oss`
* [Fabric](http://www.fabfile.org/) - High-level Python library designed to execute shell commands remotely over SSH. `oss`
* [Capistrano](https://capistranorb.com/) - A remote server automation and deployment tool. `oss`
* [Mina](http://nadarei.co/mina/) - Really fast deployer and server automation tool. `oss`
* [Terraform](https://www.terraform.io/) - use Infrastructure as Code to provision and manage any cloud, infrastructure, or service. `free` `paid` `self-hosted`
* [Pulumi](https://www.pulumi.com/) - Modern infrastructure as code platform that allows you to use familiar programming languages and tools to build, deploy, and manage cloud infrastructure. `oss` `paid`
* [Packer](https://www.packer.io/) - Build Automated Machine Images. `free` `paid` `self-hosted`
* [Vagrant](https://www.vagrantup.com/) - Development Environments Made Easy. `free` `self-hosted`
* [Foreman](https://theforeman.org/) - Complete lifecycle management tool for physical and virtual servers. `oss`
* [Nomad](https://learn.hashicorp.com/nomad) - Deploy and Manage Any Containerized, Legacy, or Batch Application. `free` `paid` `self-hosted`
* [ManageIQ](https://www.manageiq.org/) - Manage containers, virtual machines, networks, and storage from a single platform. `oss`
* [Spacelift](https://spacelift.io/) - Flexible orchestration solution for IaC development. `free` `paid`
* [Atlantis](https://www.runatlantis.io/) - Terraform Pull Request Automation. `oss`
* [KubeVela](https://kubevela.io/) - Modern application delivery platform that makes deploying and operating applications across today's hybrid, multi-cloud environments easier, faster and more reliable. `oss`
* [Stacktape](https://stacktape.com) - Developer-friendly Infrastructure as a Code framework built on top of AWS. `free` `paid`
* [Score](https://score.dev) - Open Source developer-centric and platform-agnostic workload specification. `oss`
* [Stategraph](https://stategraph.com) - Terraform and OpenTofu without the state file bottleneck. `paid`
* [Meshery](https://meshery.io/) - An open-source, cloud native manager that enables the design and management of all Kubernetes-based infrastructure and applications. `oss` `paid`
* [Digger](https://digger.dev) - Open Source Infrastructure as Code management tool that runs within your CI/CD system. `oss` `paid`
* [Deployment.io](https://deployment.io) - DevOps co-pilot for developers to automate deployments to AWS. `free` `paid`
* [RapidForge.io](https://rapidforge.io/) - Create end points, forms and tasks using scripts. Automate your workflows. `oss`
* [Terrateam](https://terrateam.io) - Open-source alternative to Terraform Cloud/Enterprise, GitOps-first with native GitHub integration and designed for scale, security, and reliability. `oss` `paid`
* [Scalr](https://scalr.com/) - Drop-in Terraform Cloud alternative, usage-based pricing, unlimited concurrency. `free` `paid`
* [CloudRay](https://cloudray.io) - Centralised platform for managing servers, organizing Bash scripts, and automating infrastructure tasks across cloud and virtual machines. `free` `paid`

## Productivity Tools

*Tools and services which increase productivity, developer velocity and developer experience.*

* [pyenv](https://github.com/pyenv/pyenv) ⭐ 45,125 | 🐛 52 | 🌐 Shell | 📅 2026-10-03 - Simple Python version management. `oss`
* [tfenv](https://github.com/tfutils/tfenv) ⭐ 4,980 | 🐛 35 | 🌐 Shell | 📅 2026-07-01 - Terraform version manager. `oss`
* [kubefwd](https://github.com/txn2/kubefwd) ⭐ 4,173 | 🐛 1 | 🌐 Go | 📅 2026-10-03 - Bulk port forwarding Kubernetes services for local development. `oss`
* [tenv](https://github.com/tofuutils/tenv) ⭐ 1,448 | 🐛 49 | 🌐 Go | 📅 2026-10-05 - streamline IaC version manager for OpenTofu, Terraform, Terragrunt and Atmos, written in Go. `oss`
* [purple](https://github.com/erickochen/purple) ⭐ 721 | 🐛 4 | 🌐 Rust | 📅 2026-10-02 - SSH client with AWS/GCP/Azure sync, Docker/Podman and SCP transfers. `oss`
* [Telert](https://github.com/navig-me/telert) ⭐ 287 | 🐛 10 | 🌐 Python | 📅 2026-10-05 - Get alerts when terminal commands finish via Telegram, Slack, Audio, etc. `oss`
* [claws](https://github.com/clawscli/claws) ⭐ 160 | 🐛 7 | 🌐 Go | 📅 2026-07-25 - A terminal UI for managing AWS resources across multiple profiles and regions with vim-style navigation. `oss`
* [Kanvas](https://layer5.io/kanvas/) - a collaborative tool with visual interface for designing and operating infrastructure. `free` `paid` `self-hosted`
* [mirrord](https://metalbear.com/mirrord/) - Run a local process as if it were a pod in a remote Kubernetes cluster. `oss` `paid`
* [YAML Validator](https://yamlvalidator.dev) - Online YAML validator, formatter and viewer with JSON Schema support for Kubernetes, Docker Compose, GitHub Actions, and more. `free`

## Continuous Integration & Delivery

*Continuous Integration, Continuous Delivery and Continuous Deployment. GitOps.*

* On-premises
  * [Drone](https://github.com/drone/drone) ⭐ 38,486 | 🐛 117 | 🌐 Go | 📅 2026-10-02 - a Container-Native, Continuous Delivery Platform. `oss` `paid`
  * [Flux](https://github.com/fluxcd/flux) ⚠️ Archived - automatically ensures that the state of your Kubernetes cluster matches the configuration you’ve supplied in Git. `oss`
  * [Flagger](https://github.com/weaveworks/flagger) ⭐ 5,417 | 🐛 395 | 🌐 Go | 📅 2026-09-21 - progressive delivery Kubernetes operator (Canary, A/B Testing and Blue/Green deployments). `oss`
  * [Semaphore Community Edition](https://github.com/semaphoreio/semaphore) ⭐ 1,613 | 🐛 185 | 🌐 Elixir | 📅 2026-10-06 - open-source (Apache-2) CI/CD for building, testing, and deploying any project. `oss` `paid`
  * [Hydra](https://github.com/NixOS/hydra) ⭐ 1,575 | 🐛 382 | 🌐 PLpgSQL | 📅 2026-10-05 - Continuous integration server for Nix-based projects. `oss`
  * [Evergreen](https://github.com/evergreen-ci/evergreen) ⭐ 449 | 🐛 26 | 🌐 Go | 📅 2026-10-05 - A Distributed Continuous Integration System from MongoDB. `oss`
  * [Buildbot](http://buildbot.net/) - automate all aspects of the software development cycle. `oss`
  * [Gitlab CI](https://about.gitlab.com/product/continuous-integration/) - pipelines build, test, deploy, and monitor your code as part of a single, integrated workflow. `oss` `paid`
  * [Jenkins](http://jenkins-ci.org/) - automation server for building, deploying and automating any project. `oss`
  * [Concourse](https://concourse-ci.org/) - pipeline-based continuous thing-doer. `oss`
  * [Spinnaker](https://www.spinnaker.io/) - fast, safe, repeatable deployments for every Enterprise. `oss`
  * [goCD](https://www.gocd.org/) - Delivery and Release Automation server. `oss`
  * [Teamcity](https://www.jetbrains.com/teamcity/) - enterprise-level CI and CD. `free` `paid` `self-hosted`
  * [Bamboo](https://www.atlassian.com/software/bamboo) - tie automated builds, tests, and releases together in a single workflow. `paid` `self-hosted`
  * [Integrity](http://integrity.github.io/) - Continuous Integration server. `oss`
  * [Zuul](https://zuul-ci.org/) - drives continuous integration, delivery, and deployment systems with a focus on project gating. `oss`
  * [Argo](https://argoproj.github.io/) - Open Source Kubernetes native workflows, events, CI and CD. `oss`
  * [Strider](https://strider-cd.github.io/) - Continuous Deployment/Continuous Integration platform. `oss`
  * [werf](https://werf.io/) - Open Source CI/CD tool for building Docker images & deploying them to Kubernetes using a GitOps approach. `oss`
  * [Tekton](https://tekton.dev/) - powerful and flexible open-source framework for creating CI/CD systems. `oss`
  * [PipeCD](https://pipecd.dev/) - Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications. `oss`
  * [Ctrlplane](https://ctrlplane.dev/) - Release governance control plane that sequences promotions across environments, regions and clusters, on top of existing CI/CD and GitOps tools. `oss`
  * [Dagger](https://dagger.io/) - CI/CD as Code that Runs Anywhere. `oss` `paid`
  * [Unleash](https://www.getunleash.io) - Open-source feature management platform (feature flags, gradual rollouts, A/B testing) to decouple deploy from release. `oss` `paid`
* Public Services
  * [Travis CI](https://travis-ci.org/) - easily sync your projects, you’ll be testing your code in minutes. `paid`
  * [Circle CI](https://circleci.com/) - powerful CI/CD pipelines that keep code moving. `free` `paid`
  * [Bitrise](https://www.bitrise.io/) - CI/CD for mobile applications. `free` `paid`
  * [Buildkite](https://buildkite.com/) - run fast, secure, and scalable continuous integration pipelines on your own infrastructure. `free` `paid`
  * [Codefresh](https://codefresh.io/) - GitOps automation platform for Kubernetes apps. `free` `paid`
  * [DeployHQ](https://www.deployhq.com/) - Git-based deployment automation to servers via SSH/SFTP/S3. `free` `paid`
  * [Github actions](https://github.com/features/actions) - GitHub Actions makes it easy to automate all your software workflows, now with world-class CI/CD. `free` `paid`
  * [Kraken CI](https://kraken.ci/) - Modern CI/CD, open-source, on-premise system that is highly scalable and focused on testing. `oss`
  * [Earthly](https://earthly.dev/) - Develop CI/CD pipelines locally and run them anywhere. `oss`
  * [RunMyJob](https://runmyjob.io/) - Cloud runners for GitHub Actions and GitLab CI with KVM-isolated VMs and load-based billing. `free` `paid`
  * [Buildstash](https://buildstash.com/) - Stores build binaries, distributes them to testers and publishes releases to app stores and distribution platforms. `free` `paid`

## Source Code Management

*Source Code management, Git-repository manager, Version Control.*

* [Phabricator](https://github.com/phacility/phabricator/) ⭐ 12,292 | 🐛 3 | 🌐 PHP | 📅 2024-04-12 - A collection of web applications which help software companies build better software. `oss`
* [Gitblit](https://github.com/gitblit/gitblit) ⭐ 2,362 | 🐛 254 | 🌐 Java | 📅 2025-06-14 - Pure Java Git solution for managing, viewing, and serving Git repositories. `oss`
* [GitHub](https://github.com/) - Helps developers store and manage their code, as well as track and control changes to their code. `free` `paid`
* [Gitlab](https://gitlab.com/) - Entire DevOps lifecycle in one application. `oss` `paid`
* [Bitbucket](https://bitbucket.org/product/) - Gives teams one place to plan projects, collaborate on code, test, and deploy. `free` `paid` `self-hosted`
* [Gogs](https://gogs.io/) - A painless self-hosted Git service. `oss`
* [Gitea](https://gitea.io/) - A painless self-hosted Git service. `oss` `paid`
* [RhodeCode](https://rhodecode.com/) - Centralized control for distributed repositories. Mercurial, Git, and Subversion under a single roof. `oss` `paid`
* [Radicle](https://radicle.xyz/) - Radicle is a sovereign peer-to-peer network for code collaboration, built on top of Git. `oss`

## Web Servers

*Web servers and reverse proxy.*

* [Nginx](http://nginx.org/) - High performance load balancer, web server and reverse proxy. `oss` `paid`
* [Apache](http://httpd.apache.org/) - Web server and reverse proxy. `oss`
* [Caddy](https://caddyserver.com/) - Web server with automatic HTTPS. `oss`
* [Cherokee](http://cherokee-project.com/) - Highly concurrent secured web applications. `oss`
* [Lighttpd](http://www.lighttpd.net/) - Optimized for speed-critical environments while remaining standards-compliant, secure and flexible. `oss`
* [Uwsgi](https://github.com/unbit/uwsgi/) ⭐ 3,547 | 🐛 895 | 🌐 C | 📅 2025-10-11 - Application server container. `oss`

## SSL

*Tools for automating the management of SSL certificates.*

* [Certbot](https://github.com/certbot/certbot) ⭐ 33,256 | 🐛 180 | 🌐 Python | 📅 2026-10-02 - Automate using Let’s Encrypt certificates on manually-managed websites to enable HTTPS. `oss`
* [Cert Manager](https://github.com/jetstack/cert-manager) ⭐ 14,106 | 🐛 262 | 🌐 Go | 📅 2026-10-05 - K8S add-on to automate the management and issuance of TLS certificates from various issuing sources. `oss`
* [Let’s Encrypt](https://letsencrypt.org/) - Free, automated, and open Certificate Authority. `oss`

## Databases

*Relational (SQL) and non-relational (NoSQL) databases.*

* Relational (SQL)
  * [PostgreSQL](https://www.postgresql.org/) - Powerful, open-source object-relational database system. `oss`
  * [MySQL](https://www.mysql.com/) - Open-source relational database management system. `oss` `paid`
  * [MariaDB](https://mariadb.org/) - Fast, scalable and robust, with a rich ecosystem of storage engines, plugins and many other tools. `oss` `paid`
  * [SQLite](https://sqlite.org/) - Small, fast, self-contained, high-reliability, full-featured, SQL database engine. `oss`
* Non-relational (NoSQL)
  * [Cassandra](http://cassandra.apache.org/) - Manage massive amounts of data, fast, without losing sleep. `oss`
  * [ScyllaDB](https://www.scylladb.com/) - NoSQL data store using the seastar framework, compatible with Apache Cassandra. `free` `paid` `self-hosted`
  * [Apache HBase](http://hbase.apache.org/) - Distributed, versioned, non-relational database. `oss`
  * [Couchdb](https://couchdb.apache.org/) - Database that completely embraces the web. `oss`
  * [Elasticsearch](https://www.elastic.co/elasticsearch) - Distributed, RESTful search and analytics engine capable of addressing a growing number of use cases. `oss` `paid`
  * [MongoDB](https://www.mongodb.com/) - General purpose, document-based, distributed database built for modern applications. `free` `paid` `self-hosted`
  * [Rethinkdb](https://github.com/rethinkdb/rethinkdb) ⭐ 27,007 | 🐛 1,352 | 🌐 C++ | 📅 2026-03-28 - Open-source database for the real-time web. `oss`
  * Key-Value
    * [Couchbase](https://www.couchbase.com/) - Distributed  multi-model NoSQL document-oriented database that is optimized for interactive applications. `free` `paid` `self-hosted`
    * [Leveldb](https://github.com/google/leveldb) ⭐ 39,475 | 🐛 415 | 🌐 C++ | 📅 2026-03-11 - Fast key-value storage library. `oss`
    * [Redis](https://redis.io/) - In-memory data structure store, used as a database, cache and message broker. `oss` `paid`
    * [RocksDB](https://rocksdb.org/) - A library that provides an embeddable, persistent key-value store for fast storage. `oss`
    * [Etcd](https://github.com/etcd-io/etcd) ⭐ 52,327 | 🐛 383 | 🌐 Go | 📅 2026-10-05 - Distributed reliable key-value store for the most critical data of a distributed system. `oss`

## Observability & Monitoring

*Observability, Monitoring, Metrics/Metrics collection and Alerting tools.*

* [Glances](https://github.com/nicolargo/glances) ⭐ 33,739 | 🐛 107 | 🌐 Python | 📅 2026-10-05 - Monitoring information through a curses or Web based interface. `oss`
* [cAdvisor](https://github.com/google/cadvisor) ⭐ 19,468 | 🐛 68 | 🌐 Go | 📅 2026-10-02 - Analyzes resource usage and performance characteristics of running containers. `oss`
* [Keep](https://github.com/keephq/keep) ⭐ 12,376 | 🐛 652 | 🌐 Python | 📅 2026-09-28 - Open source alerting CLI for developers. `oss` `paid`
* [Healthchecks](https://github.com/healthchecks/healthchecks) ⭐ 10,384 | 🐛 55 | 🌐 Python | 📅 2026-10-05 - Cron monitoring tool. `oss` `paid`
* [Cabot](https://github.com/arachnys/cabot) ⭐ 5,679 | 🐛 166 | 🌐 JavaScript | 📅 2023-09-10 - Self-hosted, easily-deployable monitoring and alerts service. `oss`
* [HolmesGPT](https://github.com/robusta-dev/holmesgpt) ⭐ 3,509 | 🐛 456 | 🌐 Python | 📅 2026-10-05 - Open Source AI assistant that can investigate alerts and find root cause automatically. `oss`
* [Alerta](https://github.com/alerta/alerta) ⭐ 2,530 | 🐛 38 | 🌐 Python | 📅 2026-06-19 - Scalable, minimal configuration and visualization monitoring system. `oss`
* [ElastiFlow](https://github.com/robcowart/elastiflow) ⚠️ Archived - Network flow monitoring (Netflow, sFlow and IPFIX) with the Elastic Stack. `free` `paid` `self-hosted`
* [Amon](https://github.com/amonapp/amon) ⭐ 1,324 | 🐛 37 | 🌐 Python | 📅 2022-07-01 - Modern server monitoring platform. `oss`
* [Shinken](https://github.com/shinken-solutions/shinken) ⭐ 1,134 | 🐛 228 | 🌐 Python | 📅 2024-04-26 - Monitoring framework. `oss`
* [Grai](https://github.com/grai-io/grai-core) ⭐ 317 | 🐛 51 | 🌐 Python | 📅 2026-01-30 - Open source observability integrating data impact analysis into CI. `oss`
* [Globalping CLI](https://github.com/jsdelivr/globalping-cli) ⭐ 289 | 🐛 2 | 🌐 Go | 📅 2026-10-05 - Run network commands like ping, traceroute and mtr from hundreds of global locations. `oss`
* [Steampipe](https://steampipe.io/) - The universal SQL interface for any cloud API, & cloud intelligence dashboards extensible w/ HCL+SQL. `oss`
* [Sensu](https://sensu.io/) - Simple. Scalable. Multi-cloud monitoring. `oss` `paid`
* [Icinga](https://icinga.com/) - Monitors availability and performance, gives you simple access to relevant data and raises alerts. `oss` `paid`
* [Monit](https://mmonit.com/monit/#home) - Managing and monitoring Unix systems. `oss` `paid`
* [Naemon](http://www.naemon.org/) - Fast, stable and innovative while giving you a clear view of the state of your network and applications. `oss`
* [Nagios](https://www.nagios.org/) - Computer-software application that monitors systems, networks and infrastructure. `oss` `paid`
* [Sentry](https://sentry.io/welcome/) - Error monitoring that helps all software teams discover, triage, and prioritize errors in real-time. `oss` `paid`
* [Zabbix](https://www.zabbix.com/) - Mature and effortless monitoring solution for network monitoring and application monitoring. `oss` `paid`
* [Bolo](http://bolo.niftylogic.com/) - Building distributed, scalable monitoring systems. `oss`
* [Co-Pilot](https://pcp.io/) - System performance analysis toolkit. `oss`
* [Canary Checker](https://canarychecker.io) - Open source health check platform. `oss` `paid`
* [Middleware](https://middleware.io) - A full-stack cloud observability platform. `free` `paid`
* Metrics/Metrics collection
  * [Freeboard](https://github.com/Freeboard/freeboard) ⭐ 6,507 | 🐛 166 | 🌐 JavaScript | 📅 2023-09-23 - Real-time dashboard builder for IOT and other web mashups. `oss`
  * [Collectd](https://github.com/collectd/collectd) ⭐ 3,368 | 🐛 789 | 🌐 C | 📅 2026-05-29 - The system statistics collection daemon. `oss`
  * [Facette](https://github.com/facette/facette) ⭐ 1,158 | 🐛 41 | 🌐 Go | 📅 2021-10-05 - Time series data visualization software. `oss`
  * [Prometheus](https://prometheus.io/) - Power your metrics and alerting with a leading open-source monitoring solution. `oss`
  * [Grafana](https://grafana.com/) - Analytics & monitoring solution for every database. `oss` `paid`
  * [Graphite](https://graphite.readthedocs.io/en/latest/) - Store numeric time-series data and render graphs of this data on demand. `oss`
  * [Influxdata](https://www.influxdata.com/) - Time series database. `oss` `paid`
  * [Netdata](https://www.netdata.cloud/) - Instantly diagnose slowdowns and anomalies in your infrastructure. `oss` `paid`
  * [Autometrics](https://autometrics.dev/) - An open-source micro framework for observability. `oss`
* Logs Management
  * [Loki](https://github.com/grafana/loki) ⭐ 28,990 | 🐛 1,035 | 🌐 Go | 📅 2026-10-06 - Horizontally-scalable, highly available, multi-tenant log aggregation system inspired by Prometheus. `oss` `paid`
  * [Graylog](https://github.com/Graylog2/graylog2-server) ⭐ 8,150 | 🐛 2,083 | 🌐 Java | 📅 2026-10-06 - Free and open source log management. `oss` `paid`
  * [Anthracite](https://github.com/Dieterbe/anthracite) ⭐ 295 | 🐛 12 | 🌐 JavaScript | 📅 2016-12-13 - An event/change logging/management app. `oss`
  * [Logstash](https://www.elastic.co/logstash) - Collect, parse, transform logs. `oss` `paid`
  * [Fluentd](https://www.fluentd.org/) - Data collector for unified logging layer. `oss`
  * [Flume](https://flume.apache.org/) - Distributed, reliable, and available service for efficiently collecting, aggregating, and moving logs. `oss`
  * [Heka](https://hekad.readthedocs.io/en/latest/#) - Stream processing software system. `oss`
  * [Kibana](https://www.elastic.co/kibana) - Explore, visualize, discover data. `oss` `paid`
* Status
  * [Cachet](https://github.com/CachetHQ/Cachet) ⭐ 15,258 | 🐛 6 | 🌐 PHP | 📅 2026-10-05 - Beautiful and powerful open-source status page system. `oss`
  * [Oxmgr](https://github.com/Vladimir-Urik/OxMgr) ⭐ 268 | 🐛 19 | 🌐 Rust | 📅 2026-10-05 - Lightweight Rust process manager and PM2 alternative. 42x faster crash recovery, 19x lower memory usage. Manages Node.js, Python, Go, and any executable on Linux, macOS, and Windows. `oss`
  * [StatusPal](https://statuspal.io/) - Communicate incidents and maintenance effectively with a beautiful hosted status page. `paid`
  * [Instatus](https://instatus.com) - Quick and beautiful status page. `free` `paid`

## Service Discovery & Service Mesh

*Service Discovery, Service Mesh and Failure detection tools.*

* [Linkerd](https://github.com/linkerd/linkerd2) ⭐ 11,507 | 🐛 217 | 🌐 Go | 📅 2026-10-05 - Service mesh for Kubernetes and beyond. `oss` `paid`
* [Doozerd](https://github.com/ha/doozerd) ⭐ 3,249 | 🐛 27 | 🌐 Go | 📅 2016-03-16 - A consistent distributed data store. `oss`
* [Consul](https://www.hashicorp.com/products/consul/) - Connect and secure any service. `free` `paid` `self-hosted`
* [Serf](https://www.serf.io/) - Decentralized cluster membership, failure detection, and orchestration. `oss`
* [Zookeeper](http://zookeeper.apache.org/) - Centralized service for configuration, naming, providing distributed synchronization, and more. `oss`
* [Etcd](https://etcd.io/) - Distributed, reliable key-value store for the most critical data of a distributed system. `oss`
* [Istio](https://istio.io/) - Connect, secure, control, and observe services. `oss`
* [Kong](https://konghq.com/) - Deliver performance needed for microservices, service mesh, and cloud native deployments. `oss` `paid`
* [Meshery](https://meshery.io) - A cloud-native management plane that simplifies the design, deployment, and management of cloud native infrastructure. `oss` `paid`

## Chaos Engineering

*Experimenting on a distributed system to build confidence in its capability to withstand turbulent conditions.*

* [Chaos Monkey](https://github.com/Netflix/chaosmonkey) ⭐ 17,164 | 🐛 34 | 🌐 Go | 📅 2025-01-06 - A resiliency tool that helps applications tolerate random instance failures. `oss`
* [Toxiproxy](https://github.com/Shopify/toxiproxy) ⭐ 12,380 | 🐛 109 | 🌐 Go | 📅 2026-10-02 - Simulate network and system conditions for chaos and resiliency testing. `oss`
* [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh) ⭐ 7,929 | 🐛 535 | 🌐 Go | 📅 2026-10-03 - A Chaos Engineering Platform for Kubernetes. `oss`
* [Litmus](https://github.com/litmuschaos/litmus) ⭐ 5,727 | 🐛 388 | 🌐 Go | 📅 2026-09-30 - Litmus enables teams to identify weaknesses in infrastructures. `oss`
* [Pumba](https://github.com/alexei-led/pumba) ⭐ 3,177 | 🐛 10 | 🌐 Go | 📅 2026-09-25 - Chaos testing, network emulation and stress testing tool for containers. `oss`
* [Chaos Toolkit](https://github.com/chaostoolkit) - The Open Source Platform for Chaos Engineering. `oss`

## API Gateway

*API Gateway, Service Proxy and Service Management tools.*

* [Cilium](https://github.com/cilium/cilium) ⭐ 25,609 | 🐛 1,104 | 🌐 Go | 📅 2026-10-05 - API aware networking and security using BPF and XDP. `oss`
* [API Umbrella](https://github.com/NREL/api-umbrella) ⭐ 2,199 | 🐛 256 | 🌐 Ruby | 📅 2026-09-26 - Proxy that sits in front of your APIs, API management platform. `oss`
* [Gloo](https://github.com/solo-io/gloo) ⭐ 170 | 🐛 1,875 | 🌐 Go | 📅 2026-10-05 - Feature-rich, Kubernetes-native ingress controller, and next-generation API gateway. `oss` `paid`
* [SBproxy](https://github.com/soapbucket/sbproxy) ⭐ 53 | 🐛 1 | 🌐 Rust | 📅 2026-09-11 - AI gateway and reverse proxy with LLM routing, rate limiting, and YAML config. `oss`
* [Ambassador](https://www.getambassador.io/) - Kubernetes-Native API Gateway built on the Envoy Proxy. `oss` `paid`
* [Kong](https://konghq.com/) - Connect all your microservices and APIs with the industry’s most performant, scalable and flexible API platform. `oss` `paid`
* [Tyk](https://tyk.io/) - API and service management platform. `oss` `paid`
* [Envoy](https://www.envoyproxy.io/) - Cloud-native high-performance edge/middle/service proxy. `oss`
* [Traefik](https://traefik.io/) - Reverse proxy and load balancer for HTTP and TCP-based applications. `oss` `paid`

## Code review

*Code review. A few of the Source Code Management tools have built-in code review features.*

* [Gerrit](https://www.gerritcodereview.com/) - Web-based team code collaboration tool. `oss`
* [Review Board](https://www.reviewboard.org/) - Web-based collaborative code review tool. `oss` `paid`
* [MeshMap](https://layer5.io/cloud-native-management/meshmap) - World’s only visual designer for Kubernetes and cloud native applications. Design, deploy, and manage your Kubernetes-based, cloud native deployments allowing you to speed up infrastructure configuration. `free` `paid`
* [Potpie](https://potpie.ai) - AI agent that understands your code changes and computes the blast radius of your changes. `oss` `paid`
* [CodeRabbit](https://coderabbit.ai) - AI-powered code review tool that integrates with GitHub. It automates routine checks, provides intelligent feedback, and helps maintain consistent code quality. `free` `paid`
* [Kodus](https://kodus.io/) - Open-source AI agent that reviews pull requests and learns each team's conventions. `oss` `paid`

## Distributed Messaging

*Distributed messaging platforms and Queues software.*

* [Faktory](https://github.com/contribsys/faktory) ⭐ 6,150 | 🐛 23 | 🌐 Go | 📅 2026-10-05 - Repository for background jobs within your application. `oss` `paid`
* [Dkron](https://github.com/distribworks/dkron) ⭐ 4,736 | 🐛 48 | 🌐 Go | 📅 2026-10-05 - Distributed, fault tolerant job scheduling system. `oss` `paid`
* [Rabbitmq](https://www.rabbitmq.com/) - Message broker. `oss` `paid`
* [Kafka](http://kafka.apache.org/) - Building real-time data pipelines and streaming apps. `oss`
* [Activemq](http://activemq.apache.org/) - Multi-Protocol messaging. `oss`
* [Beanstalkd](https://beanstalkd.github.io/) - Simple, fast work queue. `oss`
* [NSQ](https://nsq.io/) - Realtime distributed messaging platform. `oss`
* [Celery](http://www.celeryproject.org/) - Asynchronous task queue/job queue based on distributed message passing. `oss`
* [Nats](https://nats.io/) - Simple, secure and high performance open source messaging system. `oss` `paid`
* [RestMQ](http://restmq.com/) - Message queue which uses HTTP as transport. `oss`
* [KubeMQ](https://kubemq.io/) - Kubernetes-native messaging platform. `free` `paid` `self-hosted`

## Programming Languages

*Programming languages.*

* [Python](https://www.python.org/) - Programming language that lets you work quickly and integrate systems more effectively. `oss`
* [Ruby](https://www.ruby-lang.org/) - A dynamic, open-source programming language with a focus on simplicity and productivity. `oss`
* [Go](https://golang.org/) - An open-source programming language that makes it easy to build simple, reliable, and efficient software. `oss`

## Chat and ChatOps

*Chat and ChatOps.*

* [Rocket](https://rocket.chat/) - Open source team communication. `oss` `paid`
* [Mattermost](https://mattermost.com/) - Messaging platform that enables secure team collaboration. `oss` `paid`
* [Zulip](https://zulipchat.com/) - Real-time chat with an email threading model. `oss` `paid`
* [Riot](https://about.riot.im/) - A universal secure chat app entirely under your control. `oss` `paid`
* ChatOps:
  * [CloudBot](https://github.com/CloudBotIRC/CloudBot) ⭐ 291 | 🐛 64 | 🌐 Python | 📅 2026-02-27 - Simple, fast, expandable, open-source Python IRC Bot. `oss`
  * [Hubot](https://hubot.github.com/) - A customizable life embetterment robot. `oss`

## Secret Management

*Sensitive credentials and secrets managed, secured, maintained and rotated using automation.*

* [Infisical](https://github.com/Infisical/infisical) ⭐ 29,621 | 🐛 802 | 🌐 TypeScript | 📅 2026-10-06 - Open source end-to-end encrypted secrets sync for teams and infrastructure. `oss` `paid`
* [Sops](https://github.com/mozilla/sops) ⭐ 23,304 | 🐛 452 | 🌐 Go | 📅 2026-10-05 - Simple and flexible tool for managing secrets. `oss`
* [Git Secret](https://github.com/sobolevn/git-secret) ⭐ 4,047 | 🐛 153 | 🌐 Shell | 📅 2026-09-28 - A bash-tool to store your private data inside a git repository. `oss`
* [Vault Secrets Operator](https://github.com/ricoberger/vault-secrets-operator) ⭐ 687 | 🐛 20 | 🌐 Go | 📅 2026-10-01 - Create Kubernetes secrets from Vault for a secure GitOps based workflow. `oss`
* [Lade](https://github.com/zifeo/lade) ⭐ 133 | 🐛 0 | 🌐 Rust | 📅 2026-10-03 - Automatically load secrets from your preferred vault as environment variables. `oss`
* [Vault](https://www.hashicorp.com/products/vault/) - Manage secrets and protect sensitive data. `free` `paid` `self-hosted`
* [Keybase](https://keybase.io/) - End-to-end encrypted chat and cloud storage system. `oss`

## Security

*Validating, lint and best practice in term of Security on code or infrastructure.*

* [checkov](https://github.com/bridgecrewio/checkov) ⭐ 9,056 | 🐛 187 | 🌐 Python | 📅 2026-10-05 - Prevent cloud misconfigurations and find vulnerabilities during build-time in infrastructure as code, container images and open source packages. `oss`
* [Darkmoon](https://github.com/ASCIT31/Dark-Moon) ⭐ 996 | 🐛 7 | 🌐 Python | 📅 2026-10-01 - Open source autonomous AI penetration testing platform that orchestrates 80+ offensive tools via Markdown playbooks with a proof trail per finding. `oss`
* [IntoDNS.ai](https://intodns.ai) - Free DNS and email security scanner. Checks SPF, DKIM, DMARC, DNSSEC with API for CI/CD integration. `free`

## Sharing

*Tools to help with sharing knowledge and telling the story.*

* [Docusaurus](https://github.com/facebook/docusaurus) ⭐ 66,416 | 🐛 416 | 🌐 TypeScript | 📅 2026-10-05 - Easy to maintain open source documentation websites. `oss`
* [Docsify](https://github.com/docsifyjs/docsify/) ⭐ 31,542 | 🐛 105 | 🌐 JavaScript | 📅 2026-10-02 - A magical documentation site generator. `oss`
* [Gitbook](https://github.com/GitbookIO/gitbook) ⭐ 29,061 | 🐛 105 | 🌐 TypeScript | 📅 2026-10-05 - Modern documentation format and toolchain using Git and Markdown. `free` `paid`
* [MkDocs](https://github.com/mkdocs/mkdocs/) ⭐ 22,493 | 🐛 192 | 🌐 Python | 📅 2025-10-20 - Project documentation with Markdown. `oss`
* [OneCompiler](https://onecompiler.com/) - Allow users to write, run, and share code online in over 70 programming languages and databases. `free` `paid`

## VPN

*VPN, routing and firewall.*

* [Algo](https://github.com/trailofbits/algo) ⭐ 30,409 | 🐛 86 | 🌐 Python | 📅 2026-10-01 - Set up a personal VPN in the cloud. `oss`
* [Streisand](https://github.com/StreisandEffect/streisand) ⚠️ Archived - Sets up a new VPN service nearly automatically. `oss`
* [Sshuttle](https://github.com/sshuttle/sshuttle) ⭐ 13,598 | 🐛 210 | 🌐 Python | 📅 2026-10-05 - Transparent proxy server that works as a poor man's VPN. `oss`
* [Freelan](https://github.com/freelan-developers/freelan) ⭐ 1,378 | 🐛 49 | 🌐 C++ | 📅 2023-07-31 - A peer-to-peer, secure, easy-to-setup, multi-platform, open-source, highly-configurable VPN software. `oss`
* [OpenVPN](https://openvpn.net/) - Flexible VPN solutions to secure your data communications, whether it's for Internet privacy. `oss` `paid`
* [Pritunl](https://pritunl.com/) - Enterprise Distributed OpenVPN and IPsec Server. `oss` `paid`
* [VyOS](https://vyos.io/) - Open source network OS that runs on a wide range of hardware, virtual machines, and cloud providers. `oss` `paid`
* [SoftEther](https://www.softether.org/) - An Open-Source Free Cross-platform Multi-protocol VPN Program, developed as an academic project at the University of Tsukuba under the Apache License 2.0. `oss`
* [Firezone](https://www.firezone.dev/) - Self-hosted VPN server using WireGuard. Supports MFA, SSO, and has easy deployment options. `oss` `paid`

## Resources

### Books

*Books focused on DevOps, DevSecOps and Site Reliability Engineering.*

* [Effective DevOps: Building a Culture of Collaboration, Affinity, and Tooling at Scale](http://shop.oreilly.com/product/0636920039846.do) - Jennifer Davis, Ryn Daniels · O'Reilly · 2016. `paid`
* [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.oreilly.com/library/view/continuous-delivery-reliable/9780321670250/) - Jez Humble, David Farley · Addison-Wesley · 2010. `paid`
* [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/) - Betsy Beyer, Chris Jones, Jennifer Petoff, Niall Murphy · O'Reilly · 2016. `free`
* [The Site Reliability Workbook](https://sre.google/workbook/table-of-contents/) - Betsy Beyer, Niall Murphy, David Rensin, Kent Kawahara, Stephen Thorne · O'Reilly · 2018. `free`
* [Building Secure & Reliable Systems](https://google.github.io/building-secure-and-reliable-systems/raw/toc.html) - Heather Adkins, Betsy Beyer, Paul Blankinship et al. · O'Reilly · 2020. `free`
* [Infrastructure as Code: Managing Servers in the Cloud](http://shop.oreilly.com/product/0636920039297.do) - Kief Morris · O'Reilly · 2016. `paid`
* [The DevOps Handbook](https://www.oreilly.com/library/view/the-devops-handbook/9781457191381/) - Gene Kim, Jez Humble, Patrick Debois, John Willis · IT Revolution · 2016. `paid`
* [Fundamentals of DevOps and Software Delivery: A Hands-On Guide to Deploying and Managing Software in Production](https://www.fundamentals-of-devops.com/) - Yevgeniy Brikman · O'Reilly · 2025. `paid`
* [Effective Platform Engineering](https://www.manning.com/books/effective-platform-engineering) - Ajay Chankramath, Nic Cheneweth, Bryan Oliver, Sean Alvarez · Manning · 2025. `paid`
* [Latency: Reduce delay in software systems](https://www.manning.com/books/latency) - Pekka Enberg · Manning · 2025. `paid`

### Conferences

* [DevOpsCon](https://devopscon.io/) `paid`
* [AWS re:Invent](https://reinvent.awsevents.com/) - Las Vegas · December. `paid`
* [All Day DevOps](https://www.alldaydevops.com/) - Online. `free`
* [DevOpsConnect](https://www.devopsconnect.com/) `paid`
* [@Scale](https://atscaleconference.com/) - Meta. `free`
* [devopsdays](https://devopsdays.org/) - Worldwide. `paid`
* [DevOps Enterprise Summit](https://events.itrevolution.com/) - IT Revolution. `paid`

### Blogs

* [Medium](https://medium.com/?tag=devops) `free`

### DevOps Roadmap

* [Roadmap.sh DevOps](https://roadmap.sh/devops) - Basic understanding and what you should know to become a *DevOps* Engineer. `free`
* [Dynamic DevOps Roadmap](https://devopsroadmap.io) - A Progressive, Non-Linear, and T-Shaped roadmap that works as a master plan to kickstart your DevOps Engineer career in the Cloud Native era following the Agile MVP style. `free`

### Online Platforms

* [Cloud Native Playground](https://play.meshery.io) - The Meshery CNCF Playground is an awesome and free resource featuring a live Kubernetes cluster where any CNCF project can be configured and deployed. It is a fantastic interactive learning platform for exploring cloud native technologies. `free`

## Contributing

Your contributions are always welcome! Please take a look at the [Contribution Guidelines](https://github.com/wmariuss/awesome-devops/blob/main/CONTRIBUTING.md).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-06._
