# Awesome DevOps with stars

[![Awesome DevOps](http://awesome-devops.xyz/assets/banner.png)](https://github.com/wmariuss/awesome-devops) ⭐ 4,326 | 🐛 174 | 🌐 Python | 📅 2026-07-24

[![Deploy](https://github.com/wmariuss/awesome-devops/actions/workflows/deploy.yml/badge.svg)](https://github.com/wmariuss/awesome-devops/actions/workflows/deploy.yml) ⭐ 4,326 | 🐛 174 | 🌐 Python | 📅 2026-07-24
[![Links validator](https://github.com/wmariuss/awesome-devops/actions/workflows/links-validator.yml/badge.svg)](https://github.com/wmariuss/awesome-devops/actions/workflows/links-validator.yml) ⭐ 4,326 | 🐛 174 | 🌐 Python | 📅 2026-07-24

> A curated list of platforms, tools, practices and resources to create, improve DevOps culture and SRE Team in the organization.

DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes. This speed enables organizations to better serve their customers and compete more effectively in the market.

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

* [Amazon Web Services (AWS)](https://aws.amazon.com/) - Cloud Computing Services.
* [Google Cloud Platform (GCP)](https://cloud.google.com/) - Cloud Computing Services.
* [Azure](https://azure.microsoft.com/) - Cloud Computing Platform & Services.
* [Alibaba Cloud](https://us.alibabacloud.com/) - Integrated suite of cloud products and services.
* [Oracle Cloud](https://www.oracle.com/cloud/) - Comprehensive and fully integrated stack of cloud applications and platform services.
* [DigitalOcean](https://www.digitalocean.com/) - Helping developers easily build, test, manage, and scale applications of any size.
* [Scaleway](https://www.scaleway.com/) - Single way to create, deploy and scale your infrastructure in the cloud.
* [Vultr](https://www.vultr.com/) - Easily deploy cloud servers, bare metal, and storage worldwide.
* [IBM Cloud](https://www.ibm.com/cloud) - Tools, data & APIs to make AI real now.
* [Linode](https://linode.com/) - Accelerate innovation in the cloud, virtual computing must be more accessible, affordable, and simple.
* [Kinsta](https://kinsta.com/application-hosting/) - Create and deploy web applications and databases in minutes.
* [Equinix](https://www.equinix.com/) - Global data center and colocation provider for enterprise network and cloud computing.
* [Clever Cloud](https://clever.cloud/) - European Platform as a Service (PaaS) with managed databases and object storage.

## Open Source Cloud Platforms

*Private, Public and Hybrid open-source Cloud Platforms.*

* [Localstack](https://github.com/localstack/localstack) ⚠️ Archived - Fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline.
* [Fakecloud](https://github.com/faiscadev/fakecloud) ⭐ 516 | 🐛 1 | 🌐 Rust | 📅 2026-08-14 - Free, open-source local AWS cloud emulator for development and testing.
* [Openstack](https://www.openstack.org/) - Open source software for creating private and public clouds.
* [Apache CloudStack](https://cloudstack.apache.org/) - Designed to deploy and manage large networks of virtual machines.
* [OpenNebula](https://opennebula.org/) - Build Private Clouds and manage Data Center virtualization based on KVM, LXD and VMware.
* [Eucalyptus](https://www.eucalyptus.cloud/) - Building AWS-compatible private and hybrid clouds.
* [DC/OS](https://dcos.io/) - Distributed operating system based on the Apache Mesos distributed systems kernel.
* [Apache Mesos](http://mesos.apache.org/) - Program against your data center like it’s a single pool of resources.

## Operating Systems

*Operating Systems - Server Platform.*

* [Ubuntu](https://ubuntu.com/) - Enterprise Open Source and Linux.
* [Rocky Linux](https://rockylinux.org/) - Open-source enterprise operating system designed to be 100% bug-for-bug compatible with Red Hat Enterprise Linux.
* [CoreOS](http://coreos.com/) - The pioneering lightweight container host.
* [OSv](http://osv.io/) - Versatile modular unikernel designed to run unmodified Linux applications securely on micro-VMs in the cloud.
* [Atomic](http://www.projectatomic.io/) - Use immutable infrastructure to deploy and scale your containerized applications.
* [Photon](https://github.com/vmware/photon) ⭐ 3,181 | 🐛 245 | 🌐 Python | 📅 2026-08-15 - Linux container host optimized for cloud-native applications, cloud platforms, and VMware infrastructure.

## Package Management & System configuration

*Builds packages in isolation from each other.*

* [Nix/NixOS](https://nixos.org/) - A tool that takes a unique approach to package management and system configuration.

## Distributed Filesystems

*Network distributed filesystems.*

* [Ceph](https://ceph.io/en/) - Highly scalable object, block and file-based storage under one whole system.
* [Gluster](https://www.gluster.org/) - Free and open source software scalable network filesystem.
* [LINBIT](https://www.linbit.com/en/) - Create, remove, and replicate block storage devices for datacenter scale environments.
* [XtreemFS](http://www.xtreemfs.org/) - Fault-tolerant distributed file system for all storage needs.
* [min.io](https://min.io/) - High-performance, distributed object storage system.

## Applications Platforms

*Applications management platforms, Containers platform and Containers management.*

* [Docker Compose](https://github.com/docker/compose) ⭐ 38,075 | 🐛 96 | 🌐 Go | 📅 2026-08-15 - Define and run multi-container applications with Docker.
* [Podman](https://github.com/containers/podman) ⭐ 32,581 | 🐛 1,123 | 🌐 Go | 📅 2026-08-14 - A tool for managing OCI containers and pods.
* [Piku](https://github.com/piku/piku) ⭐ 6,598 | 🐛 5 | 🌐 Python | 📅 2026-08-10 - The tiniest PaaS you've ever seen. Piku allows you to do git push deployments to your own servers.
* [Docker Swarm](https://github.com/docker/swarm) ⚠️ Archived - Docker-native clustering system.
* [AppScale](https://github.com/AppScale/appscale) ⭐ 2,422 | 🐛 52 | 🌐 Python | 📅 2024-05-22 - Easy-to-manage serverless platform for building and running scalable web and mobile applications.
* [Openshift](https://www.openshift.com/) - The Kubernetes platform for big ideas.
* [Cycle.io](https://cycle.io/) - DevOps platform for building platforms. Handle container orchestration, load-balancing, monitoring, and more from a single control plane.
* [Dokku](https://dokku.com/) - Helps you build and manage the lifecycle of applications.
* [Cloud 66](https://www.cloud66.com/) - DevOps as a service that helps to build, deploy and manage any application on any cloud or server.
* [Docker](https://www.docker.com/) - Create, deploy, and run applications by using containers.
* [Kubernetes](https://kubernetes.io/) - Automating deployment, scaling, and management of containerized applications.
* [LXC](https://linuxcontainers.org/) - Lets Linux users easily create and manage system or application containers.
* [Rancher](https://rancher.com/) - Lets you deliver Kubernetes-as-a-Service.
* [OpenVz](https://openvz.org/) - Container-based virtualization for Linux.
* [Singularity](https://sylabs.io/singularity/) - Run the application from the local environment to the cloud.
* [Kata Containers](https://katacontainers.io/) - Building lightweight virtual machines that seamlessly plug into the containers ecosystem.
* [K3S](https://k3s.io/) - The certified Kubernetes distribution built for IoT and Edge computing.
* [Linx](https://linx.software) - General-purpose low-code platform for building and hosting backend solutions.
* [OrbStack](https://orbstack.dev/) - fast, light, and easy way to run Docker containers and Linux on MacOS.
* [Canine](https://canine.sh/) - Deploy applications to Kubernetes as easily as deploying to Heroku
* [AZIN](https://azin.run/) - BYOC deployment platform. Deploy to your own GCP account with git-push, no Kubernetes config needed. GKE Autopilot under the hood.
* [vCluster](https://vcluster.sh/)- A open source project that helps you create virtual clusters.
* [devpod](https://devpod.sh/) - Open-source, codebases-like tool that creates reproducible developer environments, supporting numerous providers (Kubernetes, AWS, GCP, etc.).
* [KubeStellar Console](https://console.kubestellar.io/) - Open source AI-powered multi-cluster Kubernetes dashboard with real-time observability, AI-guided operations, and 20+ CNCF integrations (Argo, Kyverno, Prometheus, Grafana, Istio, Flux, Falco, OPA/Gatekeeper). CNCF Sandbox project.

## Internal Developer Platforms

*Internal Developer Platforms (or IDP) is a set of tools, services and processes that supports and accelerates your software development, while taking care of managing the underlying infrastructure.*

* [Port](https://www.getport.io/) - A platform for building no-code, holistic, Internal Developer Portals.
* [Backstage](https://backstage.io/) - An open platform for building developer portals.
* [Kratix](https://kratix.io/) - A framework used by platform teams to build the custom platforms tailored to their organisation.
* [Qovery](https://www.qovery.com/) - Enterprise Kubernetes management platform for deploying applications on AWS, GCP, Azure, and Scaleway. Includes Terraform provider, CLI, API, and an [AI Agent Skill](https://github.com/Qovery/qovery-skills) ⭐ 9 | 🐛 4 | 🌐 Shell | 📅 2026-08-03 for deploying from AI coding tools like Claude Code, Cursor, and OpenCode.

## Container Image Registry

*Container Image registry.*

* [Quay](https://www.projectquay.io/) - Container image registry that enables you to build, organize, distribute, and deploy containers.
* [Dockyard](https://github.com/Huawei/dockyard) ⭐ 278 | 🐛 11 | 🌐 Go | 📅 2023-04-12 - Container & Artifact Repository.
* [Harbor](https://goharbor.io/) - An open source trusted cloud native registry project that stores, signs, and scans content.
* [GitHub Container Registry](https://github.blog/2020-09-01-introducing-github-container-registry/) - Container registry free for public images.

## Automation & Orchestration

*Tools for automation, orchestration, deployment, provisioning and configuration management.*

* [OctoDNS](https://github.com/github/octodns) ⭐ 3,745 | 🐛 6 | 🌐 Python | 📅 2026-08-08 - Managing DNS across multiple providers. DNS as code.
* [Ignite](https://github.com/weaveworks/ignite) ⚠️ Archived -  Open Source Virtual Machine (VM) manager with a container UX and built-in GitOps management.
* [Selefra](https://github.com/selefra/selefra) ⭐ 546 | 🐛 0 | 🌐 Go | 📅 2023-08-30 - An open-source policy-as-code software that provides analytics for multi-cloud and SaaS.
* [Ansible](https://www.ansible.com/) - Simple IT automation platform that makes your applications and systems easier to deploy.
* [Salt](https://saltproject.io/) - Automate the management and configuration of any infrastructure or application at scale.
* [Puppet](https://puppet.com/) - Unparalleled infrastructure automation and delivery.
* [Chef](https://www.chef.io/) - Automate infrastructure and applications.
* [Juju](https://jaas.ai/) - Simplifies how you configure, scale and operate today's complex software.
* [Rundeck](https://www.rundeck.com/) - Runbook Automation For Modernizing Your Operations.
* [StackStorm](https://stackstorm.com/) - Connects all your apps, services, and workflows. Automate DevOps your way.
* [Bosh](https://www.cloudfoundry.org/bosh/) - Release engineering, deployment, and lifecycle management of complex distributed systems.
* [Cloudify](https://cloudify.co/) - Connect, Control, & Automate from core to edge: unlimited locations, clouds and devices.
* [Tsuru](https://tsuru.io/) - An extensible and open source Platform as a Service software.
* [Fabric](http://www.fabfile.org/) - High-level Python library designed to execute shell commands remotely over SSH.
* [Capistrano](https://capistranorb.com/) - A remote server automation and deployment tool.
* [Mina](http://nadarei.co/mina/) - Really fast deployer and server automation tool.
* [Terraform](https://www.terraform.io/) - use Infrastructure as Code to provision and manage any cloud, infrastructure, or service.
* [Pulumi](https://www.pulumi.com/) - Modern infrastructure as code platform that allows you to use familiar programming languages and tools to build, deploy, and manage cloud infrastructure.
* [Packer](https://www.packer.io/) - Build Automated Machine Images.
* [Vagrant](https://www.vagrantup.com/) - Development Environments Made Easy.
* [Foreman](https://theforeman.org/) - Complete lifecycle management tool for physical and virtual servers.
* [Nomad](https://learn.hashicorp.com/nomad) - Deploy and Manage Any Containerized, Legacy, or Batch Application.
* [ManageIQ](https://www.manageiq.org/) - Manage containers, virtual machines, networks, and storage from a single platform.
* [Spacelift](https://spacelift.io/) - Flexible orchestration solution for IaC development.
* [Atlantis](https://www.runatlantis.io/) - Terraform Pull Request Automation
* [KubeVela](https://kubevela.io/) - Modern application delivery platform that makes deploying and operating applications across today's hybrid, multi-cloud environments easier, faster and more reliable.
* [Stacktape](https://stacktape.com) - Developer-friendly Infrastructure as a Code framework built on top of AWS.
* [Score](https://score.dev) - Open Source developer-centric and platform-agnostic workload specification.
* [Stategraph](https://stategraph.com) - Terraform and OpenTofu without the state file bottleneck.
* [Meshery](https://meshery.io/) - An open-source, cloud native manager that enables the design and management of all Kubernetes-based infrastructure and applications.
* [Digger](https://digger.dev) - Open Source Infrastructure as Code management tool that runs within your CI/CD system.
* [Deployment.io](https://deployment.io) - DevOps co-pilot for developers to automate deployments to AWS.
* [RapidForge.io](https://rapidforge.io/) - Create end points, forms and tasks using scripts. Automate your workflows.
* [Terrateam](https://terrateam.io) - Open-source alternative to Terraform Cloud/Enterprise, GitOps-first with native GitHub integration and designed for scale, security, and reliability.
* [Scalr](https://scalr.com/) - Drop-in Terraform Cloud alternative, usage-based pricing, unlimited concurrency.
* [CloudRay](https://cloudray.io) - Centralised platform for managing servers, organizing Bash scripts, and automating infrastructure tasks across cloud and virtual machines.

## Productivity Tools

*All the tools, services which increase productivity, developer velocity and developer experience.*

* [pyenv](https://github.com/pyenv/pyenv) ⭐ 45,016 | 🐛 56 | 🌐 Shell | 📅 2026-08-15 - Simple Python version management.
* [tfenv](https://github.com/tfutils/tfenv) ⭐ 4,960 | 🐛 31 | 🌐 Shell | 📅 2026-07-01 - Terraform version manager.
* [kubefwd](https://github.com/txn2/kubefwd) ⭐ 4,160 | 🐛 11 | 🌐 Go | 📅 2026-07-28 - Bulk port forwarding Kubernetes services for local development.
* [tenv](https://github.com/tofuutils/tenv) ⭐ 1,428 | 🐛 47 | 🌐 Go | 📅 2026-07-25 - streamline IaC version manager for OpenTofu, Terraform, Terragrunt and Atmos, written in Go.
* [purple](https://github.com/erickochen/purple) ⭐ 420 | 🐛 7 | 🌐 Rust | 📅 2026-08-13 - SSH client with AWS/GCP/Azure sync, Docker/Podman and SCP transfers.
* [Telert](https://github.com/navig-me/telert) ⭐ 286 | 🐛 8 | 🌐 Python | 📅 2026-08-07 - Get alerts when terminal commands finish via Telegram, Slack, Audio, etc.
* [claws](https://github.com/clawscli/claws) ⭐ 148 | 🐛 6 | 🌐 Go | 📅 2026-07-25 - A terminal UI for managing AWS resources across multiple profiles and regions with vim-style navigation.
* [Kanvas](https://kanvas.new) - a collaborative tool with visual interface for designing and operating infrastructure.
* [YAML Validator](https://yamlvalidator.dev) - Online YAML validator, formatter and viewer with JSON Schema support for Kubernetes, Docker Compose, GitHub Actions, and more.

## Continuous Integration & Delivery

*Continuous Integration, Continuous Delivery and Continuous Delivery. GitOps.*

* On-premises
  * [Drone](https://github.com/drone/drone) ⭐ 37,956 | 🐛 105 | 🌐 Go | 📅 2026-08-14 - a Container-Native, Continuous Delivery Platform.
  * [Flux](https://github.com/fluxcd/flux) ⚠️ Archived - automatically ensures that the state of your Kubernetes cluster matches the configuration you’ve supplied in Git.
  * [Flagger](https://github.com/weaveworks/flagger) ⭐ 5,388 | 🐛 383 | 🌐 Go | 📅 2026-08-11 - progressive delivery Kubernetes operator (Canary, A/B Testing and Blue/Green deployments).
  * [Semaphore Community Edition](https://github.com/semaphoreio/semaphore) ⭐ 1,575 | 🐛 169 | 🌐 Elixir | 📅 2026-08-14 - open-source (Apache-2) CI/CD for building, testing, and deploying any project.
  * [Evergreen](https://github.com/evergreen-ci/evergreen) ⭐ 450 | 🐛 22 | 🌐 Go | 📅 2026-08-14 - A Distributed Continuous Integration System from MongoDB.
  * [Buildbot](http://buildbot.net/) - automate all aspects of the software development cycle.
  * [Gitlab CI](https://about.gitlab.com/product/continuous-integration/) - pipelines build, test, deploy, and monitor your code as part of a single, integrated workflow.
  * [Jenkins](http://jenkins-ci.org/) - automation server for building, deploying and automating any project.
  * [Concourse](https://concourse-ci.org/) - pipeline-based continuous thing-doer.
  * [Spinnaker](https://www.spinnaker.io/) - fast, safe, repeatable deployments for every Enterprise.
  * [goCD](https://www.gocd.org/) - Delivery and Release Automation server.
  * [Teamcity](https://www.jetbrains.com/teamcity/) - enterprise-level CI and CD.
  * [Bamboo](https://www.atlassian.com/software/bamboo) - tie automated builds, tests, and releases together in a single workflow.
  * [Integrity](http://integrity.github.io/) - Continuous Integration server.
  * [Zuul](https://zuul-ci.org/) - drives continuous integration, delivery, and deployment systems with a focus on project gating.
  * [Argo](https://argoproj.github.io/) - Open Source Kubernetes native workflows, events, CI and CD.
  * [Strider](https://strider-cd.github.io/) - Continuous Deployment/Continuous Integration platform.
  * [werf](https://werf.io/) - Open Source CI/CD tool for building Docker images & deploying them to Kubernetes using a GitOps approach.
  * [Tekton](https://tekton.dev/) - powerful and flexible open-source framework for creating CI/CD systems.
  * [PipeCD](https://pipecd.dev/) - Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications.
  * [Dagger](https://dagger.io/) - CI/CD as Code that Runs Anywhere.
  * [Unleash](https://www.getunleash.io) - Open-source feature management platform (feature flags, gradual rollouts, A/B testing) to decouple deploy from release.
* Public Services
  * [Travis CI](https://travis-ci.org/) - easily sync your projects, you’ll be testing your code in minutes.
  * [Circle CI](https://circleci.com/) - powerful CI/CD pipelines that keep code moving.
  * [Bitrise](https://www.bitrise.io/) - CI/CD for mobile applications.
  * [Buildkite](https://buildkite.com/) - run fast, secure, and scalable continuous integration pipelines on your own infrastructure.
  * [Cirrus CI](https://cirrus-ci.org/) - continuous integration system built for the era of cloud computing.
  * [Codefresh](https://codefresh.io/) - GitOps automation platform for Kubernetes apps.
  * [Github actions](https://github.com/features/actions) - GitHub Actions makes it easy to automate all your software workflows, now with world-class CI/CD.
  * [Kraken CI](https://kraken.ci/) - Modern CI/CD, open-source, on-premise system that is highly scalable and focused on testing.
  * [Earthly](https://earthly.dev/) - Develop CI/CD pipelines locally and run them anywhere.
  * [GitLab Pipelines by puzl.cloud](https://puzl.cloud/products/run-my-job/) - Blazing-fast, cost-effective execution layer for GitLab CI/CD pipeline jobs, offering per-second billing and k8s API for runner management.

## Source Code Management

*Source Code management, Git-repository manager, Version Control. Some of them are included in Code review section.*

* [Phabricator](https://github.com/phacility/phabricator/) ⭐ 12,295 | 🐛 3 | 🌐 PHP | 📅 2024-04-12 - A collection of web applications which help software companies build better software.
* [Gitblit](https://github.com/gitblit/gitblit) ⭐ 2,356 | 🐛 254 | 🌐 Java | 📅 2025-06-14 - Pure Java Git solution for managing, viewing, and serving Git repositories.
* [GitHub](https://github.com/) - Helps developers store and manage their code, as well as track and control changes to their code.
* [Gitlab](https://gitlab.com/) - Entire DevOps lifecycle in one application.
* [Bitbucket](https://bitbucket.org/product/) - Gives teams one place to plan projects, collaborate on code, test, and deploy
* [Gogs](https://gogs.io/) - A painless self-hosted Git service.
* [Gitea](https://gitea.io/) - A painless self-hosted Git service.
* [RhodeCode](https://rhodecode.com/) - Centralized control for distributed repositories. Mercurial, Git, and Subversion under a single roof.
* [Radicle](https://radicle.xyz/) - Radicle is a sovereign peer-to-peer network for code collaboration, built on top of Git.

## Web Servers

*Web servers and reverse proxy.*

* [Nginx](http://nginx.org/) - High performance load balancer, web server and reverse proxy.
* [Apache](http://httpd.apache.org/) - Web server and reverse proxy.
* [Caddy](https://caddyserver.com/) - Web server with automatic HTTPS.
* [Cherokee](http://cherokee-project.com/) - Highly concurrent secured web applications.
* [Lighttpd](http://www.lighttpd.net/) - Optimized for speed-critical environments while remaining standards-compliant, secure and flexible.
* [Uwsgi](https://github.com/unbit/uwsgi/) ⭐ 3,546 | 🐛 894 | 🌐 C | 📅 2025-10-11 - Application server container.

## SSL

*Tools for automating the management of SSL certificates.*

* [Certbot](https://github.com/certbot/certbot) ⭐ 33,202 | 🐛 188 | 🌐 Python | 📅 2026-08-12 - Automate using Let’s Encrypt certificates on manually-managed websites to enable HTTPS.
* [Cert Manager](https://github.com/jetstack/cert-manager) ⭐ 14,028 | 🐛 254 | 🌐 Go | 📅 2026-08-15 - K8S add-on to automate the management and issuance of TLS certificates from various issuing sources.
* [Let’s Encrypt](https://letsencrypt.org/) - Free, automated, and open Certificate Authority.

## Databases

*Relational (SQL) and non-relational (NoSQL) databases.*

* Relational (SQL)
  * [PostgreSQL](https://www.postgresql.org/) - Powerful, open-source object-relational database system.
  * [MySQL](https://www.mysql.com/) - Open-source relational database management system.
  * [MariaDB](https://mariadb.org/) - Fast, scalable and robust, with a rich ecosystem of storage engines, plugins and many other tools.
  * [SQLite](https://sqlite.org/) - Small, fast, self-contained, high-reliability, full-featured, SQL database engine.
* Non-relational (NoSQL)
  * [Cassandra](http://cassandra.apache.org/) - Manage massive amounts of data, fast, without losing sleep.
  * [ScyllaDB](https://www.scylladb.com/) - NoSQL data store using the seastar framework, compatible with Apache Cassandra
  * [Apache HBase](http://hbase.apache.org/) - Distributed, versioned, non-relational database.
  * [Couchdb](https://couchdb.apache.org/) - Database that completely embraces the web.
  * [Elasticsearch](https://www.elastic.co/products/elasticsearch) - Distributed, RESTful search and analytics engine capable of addressing a growing number of use cases.
  * [MongoDB](https://www.mongodb.com/) - General purpose, document-based, distributed database built for modern applications.
  * [Rethinkdb](https://github.com/rethinkdb/rethinkdb) ⭐ 26,996 | 🐛 1,352 | 🌐 C++ | 📅 2026-03-28 - Open-source database for the real-time web.
  * Key-Value
    * [Couchbase](https://www.couchbase.com/) - Distributed  multi-model NoSQL document-oriented database that is optimized for interactive applications.
    * [Leveldb](https://github.com/google/leveldb) ⭐ 39,324 | 🐛 400 | 🌐 C++ | 📅 2026-03-11 - Fast key-value storage library.
    * [Redis](https://redis.io/) - In-memory data structure store, used as a database, cache and message broker.
    * [RocksDB](https://rocksdb.org/) - A library that provides an embeddable, persistent key-value store for fast storage.
    * [Etcd](https://github.com/etcd-io/etcd) ⭐ 52,126 | 🐛 311 | 🌐 Go | 📅 2026-08-15 - Distributed reliable key-value store for the most critical data of a distributed system.

## Observability & Monitoring

*Observability, Monitoring, Metrics/Metrics collection and Alerting tools.*

* [Glances](https://github.com/nicolargo/glances) ⭐ 33,377 | 🐛 106 | 🌐 Python | 📅 2026-08-15 - Monitoring information through a curses or Web based interface.
* [cAdvisor](https://github.com/google/cadvisor) ⭐ 19,357 | 🐛 66 | 🌐 Go | 📅 2026-07-20 - Analyzes resource usage and performance characteristics of running containers.
* [Keep](https://github.com/keephq/keep) ⭐ 12,211 | 🐛 559 | 🌐 Python | 📅 2026-08-08 - Open source alerting CLI for developers.
* [Healthchecks](https://github.com/healthchecks/healthchecks) ⭐ 10,244 | 🐛 53 | 🌐 Python | 📅 2026-08-11 - Cron monitoring tool.
* [Cabot](https://github.com/arachnys/cabot) ⭐ 5,671 | 🐛 166 | 🌐 JavaScript | 📅 2023-09-10 - Self-hosted, easily-deployable monitoring and alerts service.
* [HolmesGPT](https://github.com/robusta-dev/holmesgpt) ⭐ 3,069 | 🐛 386 | 🌐 Python | 📅 2026-08-15 - Open Source AI assistant that can investigate alerts and find root cause automatically.
* [Alerta](https://github.com/alerta/alerta) ⭐ 2,527 | 🐛 31 | 🌐 Python | 📅 2026-06-19 - Scalable, minimal configuration and visualization monitoring system.
* [ElastiFlow](https://github.com/robcowart/elastiflow) ⚠️ Archived - Network flow monitoring (Netflow, sFlow and IPFIX) with the Elastic Stack.
* [Amon](https://github.com/amonapp/amon) ⭐ 1,324 | 🐛 37 | 🌐 Python | 📅 2022-07-01 - Modern server monitoring platform.
* [Shinken](https://github.com/shinken-solutions/shinken) ⭐ 1,136 | 🐛 228 | 🌐 Python | 📅 2024-04-26 - Monitoring framework.
* [Grai](https://github.com/grai-io/grai-core) ⭐ 315 | 🐛 51 | 🌐 Python | 📅 2026-01-30 - Open source observability integrating data impact analysis into CI.
* [Globalping CLI](https://github.com/jsdelivr/globalping-cli) ⭐ 278 | 🐛 8 | 🌐 Go | 📅 2026-08-15 - Run network commands like ping, traceroute and mtr from hundreds of global locations.
* [Steampipe](https://steampipe.io/) - The universal SQL interface for any cloud API, & cloud intelligence dashboards extensible w/ HCL+SQL.
* [Sensu](https://sensu.io/) - Simple. Scalable. Multi-cloud monitoring.
* [Icinga](https://icinga.com/) - Monitors availability and performance, gives you simple access to relevant data and raises alerts.
* [Monit](https://mmonit.com/monit/#home) - Managing and monitoring Unix systems.
* [Naemon](http://www.naemon.org/) - Fast, stable and innovative while giving you a clear view of the state of your network and applications.
* [Nagios](https://www.nagios.org/) - Computer-software application that monitors systems, networks and infrastructure.
* [Sentry](https://sentry.io/welcome/) - Error monitoring that helps all software teams discover, triage, and prioritize errors in real-time.
* [Zabbix](https://www.zabbix.com/) - Mature and effortless monitoring solution for network monitoring and application monitoring.
* [Bolo](http://bolo.niftylogic.com/) - Building distributed, scalable monitoring systems.
* [Co-Pilot](https://pcp.io/) - System performance analysis toolkit.
* [Canary Checker](https://canarychecker.io) - Open source health check platform.
* [Merlinn](https://github.com/merlinn-co/merlinn) - Open-source AI on-call developer.
* [Middleware](https://middleware.io) - A full-stack cloud observability platform.
* Metrics/Metrics collection
  * [Freeboard](https://github.com/Freeboard/freeboard) ⭐ 6,503 | 🐛 166 | 🌐 JavaScript | 📅 2023-09-23 - Real-time dashboard builder for IOT and other web mashups.
  * [Collectd](https://github.com/collectd/collectd) ⭐ 3,366 | 🐛 785 | 🌐 C | 📅 2026-05-29 - The system statistics collection daemon.
  * [Facette](https://github.com/facette/facette) ⭐ 1,158 | 🐛 41 | 🌐 Go | 📅 2021-10-05 - Time series data visualization software.
  * [Prometheus](https://prometheus.io/) - Power your metrics and alerting with a leading open-source monitoring solution.
  * [Grafana](https://grafana.com/) - Analytics & monitoring solution for every database.
  * [Graphite](https://graphite.readthedocs.io/en/latest/) - Store numeric time-series data and render graphs of this data on demand.
  * [Influxdata](https://www.influxdata.com/) - Time series database.
  * [Netdata](https://www.netdata.cloud/) - Instantly diagnose slowdowns and anomalies in your infrastructure.
  * [Autometrics](https://autometrics.dev/) - An open-source micro framework for observability.
* Logs Management
  * [Loki](https://github.com/grafana/loki) ⭐ 28,742 | 🐛 1,767 | 🌐 Go | 📅 2026-08-15 - Horizontally-scalable, highly available, multi-tenant log aggregation system inspired by Prometheus.
  * [Graylog](https://github.com/Graylog2/graylog2-server) ⭐ 8,111 | 🐛 2,048 | 🌐 Java | 📅 2026-08-15 - Free and open source log management.
  * [Anthracite](https://github.com/Dieterbe/anthracite) ⭐ 295 | 🐛 12 | 🌐 JavaScript | 📅 2016-12-13 - An event/change logging/management app.
  * [Logstash](https://www.elastic.co/products/logstash#) - Collect, parse, transform logs.
  * [Fluentd](https://www.fluentd.org/) - Data collector for unified logging layer.
  * [Flume](https://flume.apache.org/) - Distributed, reliable, and available service for efficiently collecting, aggregating, and moving logs.
  * [Heka](https://hekad.readthedocs.io/en/latest/#) - Stream processing software system.
  * [Kibana](https://www.elastic.co/products/kibana) - Explore, visualize, discover data.
* Status
  * [Cachet](https://github.com/CachetHQ/Cachet) ⭐ 15,215 | 🐛 6 | 🌐 PHP | 📅 2026-08-11 - Beautiful and powerful open-source status page system.
  * [Oxmgr](https://github.com/Vladimir-Urik/OxMgr) ⭐ 216 | 🐛 16 | 🌐 Rust | 📅 2026-08-10 - Lightweight Rust process manager and PM2 alternative. 42x faster crash recovery, 19x lower memory usage. Manages Node.js, Python, Go, and any executable on Linux, macOS, and Windows.
  * [StatusPal](https://statuspal.io/?utm_source=github.com\&utm_medium=referral\&utm_campaign=awesome-devops) - Communicate incidents and maintenance effectively with a beautiful hosted status page.
  * [Instatus](https://instatus.com) - Quick and beautiful status page.

## Service Discovery & Service Mesh

*Service Discovery, Service Mesh and Failure detection tools.*

* [Linkerd](https://github.com/linkerd/linkerd2) ⭐ 11,476 | 🐛 215 | 🌐 Go | 📅 2026-08-14 - Service mesh for Kubernetes and beyond.
* [Doozerd](https://github.com/ha/doozerd) ⭐ 3,250 | 🐛 27 | 🌐 Go | 📅 2016-03-16 - A consistent distributed data store.
* [Consul](https://www.hashicorp.com/products/consul/) - Connect and secure any service.
* [Serf](https://www.serf.io/) - Decentralized cluster membership, failure detection, and orchestration.
* [Zookeeper](http://zookeeper.apache.org/) - Centralized service for configuration, naming, providing distributed synchronization, and more.
* [Etcd](https://etcd.io/) - Distributed, reliable key-value store for the most critical data of a distributed system.
* [Istio](https://istio.io/) - Connect, secure, control, and observe services.
* [Kong](https://konghq.com/) - Deliver performance needed for microservices, service mesh, and cloud native deployments.
* [Meshery](https://meshery.io) - A cloud-native management plane that simplifies the design, deployment, and management of cloud native infrastructure.

## Chaos Engineering

*The discipline of experimenting on a distributed system in order to build confidence in the system's capability to withstand turbulent conditions in production.*

* [Chaos Monkey](https://github.com/Netflix/chaosmonkey) ⭐ 17,079 | 🐛 34 | 🌐 Go | 📅 2025-01-06 - A resiliency tool that helps applications tolerate random instance failures.
* [Toxiproxy](https://github.com/Shopify/toxiproxy) ⭐ 12,250 | 🐛 104 | 🌐 Go | 📅 2026-08-04 - Simulate network and system conditions for chaos and resiliency testing.
* [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh) ⭐ 7,843 | 🐛 543 | 🌐 Go | 📅 2026-08-07 - A Chaos Engineering Platform for Kubernetes.
* [Litmus](https://github.com/litmuschaos/litmus) ⭐ 5,595 | 🐛 414 | 🌐 Go | 📅 2026-07-31 - Litmus enables teams to identify weaknesses in infrastructures.
* [Pumba](https://github.com/alexei-led/pumba) ⭐ 3,102 | 🐛 20 | 🌐 Go | 📅 2026-07-27 - Chaos testing, network emulation and stress testing tool for containers.
* [Chaos Toolkit](https://github.com/chaostoolkit) - The Open Source Platform for Chaos Engineering.

## API Gateway

*API Gateway, Service Proxy and Service Management tools.*

* [Cilium](https://github.com/cilium/cilium) ⭐ 24,937 | 🐛 1,089 | 🌐 Go | 📅 2026-08-15 - API aware networking and security using BPF and XDP.
* [API Umbrella](https://github.com/NREL/api-umbrella) ⭐ 2,194 | 🐛 257 | 🌐 Ruby | 📅 2026-08-12 - Proxy that sits in front of your APIs, API management platform.
* [Gloo](https://github.com/solo-io/gloo) ⭐ 169 | 🐛 1,867 | 🌐 Go | 📅 2026-08-14 - Feature-rich, Kubernetes-native ingress controller, and next-generation API gateway.
* [SBproxy](https://github.com/soapbucket/sbproxy) ⭐ 49 | 🐛 1 | 🌐 Rust | 📅 2026-08-15 - AI gateway and reverse proxy with LLM routing, rate limiting, and YAML config.
* [Ambassador](https://www.getambassador.io/) - Kubernetes-Native API Gateway built on the Envoy Proxy.
* [Kong](https://konghq.com/) - Connect all your microservices and APIs with the industry’s most performant, scalable and flexible API platform.
* [Tyk](https://tyk.io/) - API and service management platform.
* [Envoy](https://www.envoyproxy.io/) - Cloud-native high-performance edge/middle/service proxy.
* [Traefik](https://traefik.io/) - Reverse proxy and load balancer for HTTP and TCP-based applications.

## Code review

*Code review. A few of the Source Code Management tools have built-in code review features.*

* [Gerrit](https://www.gerritcodereview.com/) - Web-based team code collaboration tool.
* [Review Board](https://www.reviewboard.org/) - Web-based collaborative code review tool.
* [MeshMap](https://layer5.io/cloud-native-management/meshmap) - World’s only visual designer for Kubernetes and cloud native applications. Design, deploy, and manage your Kubernetes-based, cloud native deployments allowing you to speed up infrastructure configuration.
* [Potpie](https://potpie.ai) - AI agent that understands your code changes and computes the blast radius of your changes.
* [CodeRabbit](https://coderabbit.ai) - AI-powered code review tool that integrates with GitHub. It automates routine checks, provides intelligent feedback, and helps maintain consistent code quality.

## Distributed Messaging

*Distributed messaging platforms and Queues software.*

* [Faktory](https://github.com/contribsys/faktory) ⭐ 6,137 | 🐛 23 | 🌐 Go | 📅 2026-08-10 - Repository for background jobs within your application.
* [Dkron](https://github.com/distribworks/dkron) ⭐ 4,725 | 🐛 48 | 🌐 Go | 📅 2026-08-11 - Distributed, fault tolerant job scheduling system.
* [Rabbitmq](https://www.rabbitmq.com/) - Message broker.
* [Kafka](http://kafka.apache.org/) - Building real-time data pipelines and streaming apps.
* [Activemq](http://activemq.apache.org/) - Multi-Protocol messaging.
* [Beanstalkd](https://beanstalkd.github.io/) - Simple, fast work queue.
* [NSQ](https://nsq.io/) - Realtime distributed messaging platform.
* [Celery](http://www.celeryproject.org/) - Asynchronous task queue/job queue based on distributed message passing.
* [Nats](https://nats.io/) - Simple, secure and high performance open source messaging system.
* [RestMQ](http://restmq.com/) - Message queue which uses HTTP as transport.
* [KubeMQ](https://kubemq.io/) - Kubernetes-native messaging platform.

## Programming Languages

*Programming languages.*

* [Python](https://www.python.org/) - Programming language that lets you work quickly and integrate systems more effectively.
* [Ruby](https://www.ruby-lang.org/) - A dynamic, open-source programming language with a focus on simplicity and productivity.
* [Go](https://golang.org/) - An open-source programming language that makes it easy to build simple, reliable, and efficient software.

## Chat and ChatOps

*Chat and ChatOps.*

* [Rocket](https://rocket.chat/) - Open source team communication.
* [Mattermost](https://mattermost.com/) - Messaging platform that enables secure team collaboration.
* [Zulip](https://zulipchat.com/) - Real-time chat with an email threading model.
* [Riot](https://about.riot.im/) - A universal secure chat app entirely under your control.
* ChatOps:
  * [CloudBot](https://github.com/CloudBotIRC/CloudBot) ⭐ 291 | 🐛 64 | 🌐 Python | 📅 2026-02-27 - Simple, fast, expandable, open-source Python IRC Bot.
  * [Hubot](https://hubot.github.com/) - A customizable life embetterment robot.

## Secret Management

*Security as code, sensitive credentials and secrets need to be managed, security, maintained and rotated using automation.*

* [Infisical](https://github.com/Infisical/infisical) ⭐ 28,781 | 🐛 738 | 🌐 TypeScript | 📅 2026-08-15 - Open source end-to-end encrypted secrets sync for teams and infrastructure.
* [Sops](https://github.com/mozilla/sops) ⭐ 22,823 | 🐛 438 | 🌐 Go | 📅 2026-08-10 - Simple and flexible tool for managing secrets.
* [Git Secret](https://github.com/sobolevn/git-secret) ⭐ 4,035 | 🐛 247 | 🌐 Shell | 📅 2026-08-11 - A bash-tool to store your private data inside a git repository.
* [Vault Secrets Operator](https://github.com/ricoberger/vault-secrets-operator) ⭐ 685 | 🐛 15 | 🌐 Go | 📅 2026-08-13 - Create Kubernetes secrets from Vault for a secure GitOps based workflow.
* [Lade](https://github.com/zifeo/lade) ⭐ 126 | 🐛 2 | 🌐 Rust | 📅 2026-08-13 - Automatically load secrets from your preferred vault as environment variables.
* [Vault](https://www.hashicorp.com/products/vault/) - Manage secrets and protect sensitive data.
* [Keybase](https://keybase.io/) - End-to-end encrypted chat and cloud storage system.

## Security

*Validating, lint and best practice in term of Security on code or infrastructure.*

* [checkov](https://github.com/bridgecrewio/checkov) ⭐ 8,937 | 🐛 161 | 🌐 Python | 📅 2026-08-13 - Prevent cloud misconfigurations and find vulnerabilities during build-time in infrastructure as code, container images and open source packages.
* [IntoDNS.ai](https://intodns.ai) - Free DNS and email security scanner. Checks SPF, DKIM, DMARC, DNSSEC with API for CI/CD integration.

## Sharing

*A collection of tools to help with sharing knowledge and telling the story.*

* [Docusaurus](https://github.com/facebook/docusaurus) ⭐ 65,927 | 🐛 427 | 🌐 TypeScript | 📅 2026-08-13 - Easy to maintain open source documentation websites.
* [Docsify](https://github.com/docsifyjs/docsify/) ⭐ 31,457 | 🐛 95 | 🌐 JavaScript | 📅 2026-08-15 - A magical documentation site generator.
* [Gitbook](https://github.com/GitbookIO/gitbook) ⭐ 28,997 | 🐛 119 | 🌐 TypeScript | 📅 2026-08-15 - Modern documentation format and toolchain using Git and Markdown.
* [MkDocs](https://github.com/mkdocs/mkdocs/) ⭐ 22,344 | 🐛 185 | 🌐 Python | 📅 2025-10-20 - Project documentation with Markdown.
* [OneCompiler](https://onecompiler.com/) - Allow users to write, run, and share code online in over 70 programming languages and databases.

## VPN

*VPN, routing and firewall.*

* [Algo](https://github.com/trailofbits/algo) ⭐ 30,361 | 🐛 77 | 🌐 Python | 📅 2026-08-12 - Set up a personal VPN in the cloud.
* [Streisand](https://github.com/StreisandEffect/streisand) ⚠️ Archived - Sets up a new VPN service nearly automatically.
* [Sshuttle](https://github.com/sshuttle/sshuttle) ⭐ 13,520 | 🐛 211 | 🌐 Python | 📅 2026-08-12 - Transparent proxy server that works as a poor man's VPN.
* [Freelan](https://github.com/freelan-developers/freelan) ⭐ 1,376 | 🐛 49 | 🌐 C++ | 📅 2023-07-31 - A peer-to-peer, secure, easy-to-setup, multi-platform, open-source, highly-configurable VPN software.
* [OpenVPN](https://openvpn.net/) - Flexible VPN solutions to secure your data communications, whether it's for Internet privacy.
* [Pritunl](https://pritunl.com/) - Enterprise Distributed OpenVPN and IPsec Server.
* [VyOS](https://vyos.io/) - Open source network OS that runs on a wide range of hardware, virtual machines, and cloud providers.
* [SoftEther](https://www.softether.org/) - An Open-Source Free Cross-platform Multi-protocol VPN Program.
  as an academic project from University of Tsukuba, under the Apache License 2.0.
* [Firezone](https://www.firezone.dev/) - Self-hosted VPN server using WireGuard. Supports MFA, SSO, and has easy deployment options.

## Resources

### Books

*Books focused on DevOps, DevSecOps and Site Reliability Engineering.*

* [Effective DevOps: Building a Culture of Collaboration, Affinity, and Tooling at Scale](http://shop.oreilly.com/product/0636920039846.do)
* [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.oreilly.com/library/view/continuous-delivery-reliable/9780321670250/)
* [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/)
* [The Site Reliability Workbook](https://sre.google/workbook/table-of-contents/)
* [Building Secure & Reliable Systems](https://google.github.io/building-secure-and-reliable-systems/raw/toc.html)
* [Infrastructure as Code: Managing Servers in the Cloud](http://shop.oreilly.com/product/0636920039297.do)
* [The DevOps Handbook](https://www.oreilly.com/library/view/the-devops-handbook/9781457191381/)
* [Fundamentals of DevOps and Software Delivery: A Hands-On Guide to Deploying and Managing Software in Production](https://www.fundamentals-of-devops.com/)

### Conferences

* [DevOpsCon](https://devopscon.io/)
* [AWS re:Invent](https://reinvent.awsevents.com/)
* [DevSecOps](https://www.devseccon.com/)
* [ADDO](https://www.alldaydevops.com/)
* [DevOpsConnect](https://www.devopsconnect.com/)
* [@Scale](https://atscaleconference.com/)
* [devopsdays](https://devopsdays.org/)
* [DevOps Enterprise Summit](https://events.itrevolution.com/)

### Blogs

* [Medium](https://medium.com/?tag=devops)

### DevOps Roadmap

* [Roadmap.sh DevOps](https://roadmap.sh/devops): Basic understanding and what you should know to become a *DevOps* Engineer.
* [Dynamic DevOps Roadmap](https://devopsroadmap.io): A Progressive, Non-Linear, and T-Shaped roadmap that works as a master plan to kickstart your DevOps Engineer career in the Cloud Native era following the Agile MVP style.

### Online Platforms

* [Cloud Native Playground](https://play.meshery.io) - The Meshery CNCF Playground is an awesome and free resource featuring a live Kubernetes cluster where any CNCF project can be configured and deployed. It is a fantastic interactive learning platform for exploring cloud native technologies.

## Contributing

Your contributions are always welcome! Please take a look at the [Contribution Guidelines](https://github.com/wmariuss/awesome-devops/blob/main/docs/contribution.md) ⭐ 4,326 | 🐛 174 | 🌐 Python | 📅 2026-07-24.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
