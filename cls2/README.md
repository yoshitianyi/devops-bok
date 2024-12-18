# Class 200 - OS, network, and infrastructure

[Show timeline](./Timeline.md)

## 200 - OS and IP network basics

* Operating system <https://en.wikipedia.org/wiki/Operating_system>
  * POSIX <https://en.wikipedia.org/wiki/POSIX>
  * process <https://en.wikipedia.org/wiki/Process_(computing)>
    * pthreads <https://en.wikipedia.org/wiki/Pthreads>
  * environment variable <https://en.wikipedia.org/wiki/Environment_variable>
  * pipeline <https://en.wikipedia.org/wiki/Pipeline_(Unix)>
  * file system <https://en.wikipedia.org/wiki/File_system>
    * path <https://en.wikipedia.org/wiki/Path_(computing)>
    * glob pattern <https://en.wikipedia.org/wiki/Glob_(programming)>
    * file handle/descriptor <https://en.wikipedia.org/wiki/File_descriptor>
    * symbolic link <https://en.wikipedia.org/wiki/Symbolic_link>
    * permission <https://en.wikipedia.org/wiki/File-system_permissions>
    * setuid <https://en.wikipedia.org/wiki/Setuid>
      * sticky bit <https://en.wikipedia.org/wiki/Sticky_bit>
  * disk partitioning <https://en.wikipedia.org/wiki/Disk_partitioning>
  * loop device <https://en.wikipedia.org/wiki/Loop_device>
  * virtual memory <https://en.wikipedia.org/wiki/Virtual_memory>
    * memory paging <https://en.wikipedia.org/wiki/Memory_paging>
    * resident set size (RSS) <https://en.wikipedia.org/wiki/Resident_set_size>
    * working set size (WSS) <https://en.wikipedia.org/wiki/Working_set_size>
  * shared memory <https://en.wikipedia.org/wiki/Shared_memory>
* The OSI model <https://en.wikipedia.org/wiki/OSI_model>
* ARP <https://en.wikipedia.org/wiki/Address_Resolution_Protocol>
  * MAC address <https://en.wikipedia.org/wiki/MAC_address>
* The Internet <https://en.wikipedia.org/wiki/Internet>
* IP <https://en.wikipedia.org/wiki/Internet_Protocol>
  * Link-local address <https://en.wikipedia.org/wiki/Link-local_address>
  * IP-multicast <https://en.wikipedia.org/wiki/IP_multicast>
  * DHCP <https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol>
  * ICMP <https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol>
  * NAT <https://en.wikipedia.org/wiki/Network_address_translation>
  * IPv6 <https://en.wikipedia.org/wiki/IPv6>
    * Unique local address <https://en.wikipedia.org/wiki/Unique_local_address>
    * DHCPv6 <https://en.wikipedia.org/wiki/DHCPv6>
    * ICMPv6 <https://en.wikipedia.org/wiki/ICMPv6>
    * NAT64 <https://en.wikipedia.org/wiki/NAT64> - An IPv6 transition mechanism that facilitates communication between IPv6 and IPv4 hosts
  * Routing table <https://en.wikipedia.org/wiki/Routing_table>
    * CIDR <https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing>
  * TCP <https://en.wikipedia.org/wiki/Transmission_Control_Protocol>
  * UDP <https://en.wikipedia.org/wiki/User_Datagram_Protocol>

## 210 - Linux administration

* The Linux Kernel <https://www.kernel.org/>
  * daemon <https://man7.org/linux/man-pages/man7/daemon.7.html>
  * signal <https://man7.org/linux/man-pages/man7/signal.7.html>
  * pipe <https://man7.org/linux/man-pages/man7/pipe.7.html>
  * named pipe <https://man7.org/linux/man-pages/man7/fifo.7.html>
  * unix domain socket <https://man7.org/linux/man-pages/man7/unix.7.html>
  * socket <https://man7.org/linux/man-pages/man7/socket.7.html>
  * cgroups <https://man7.org/linux/man-pages/man7/cgroups.7.html>
  * namespaces <https://man7.org/linux/man-pages/man7/namespaces.7.html>
  * lxc/rootfs <https://man7.org/linux/man-pages/man7/lxc.7.html>
* Filesystems
  * ext4 <https://en.wikipedia.org/wiki/Ext4>
  * xfs <https://en.wikipedia.org/wiki/XFS>
  * overlayfs <https://en.wikipedia.org/wiki/OverlayFS>
  * proc pseudo-filesystem <https://man7.org/linux/man-pages/man5/proc.5.html>
  * sysfs pseudo-filesystem <https://man7.org/linux/man-pages/man5/sysfs.5.html>
* linux-pam <https://github.com/linux-pam/linux-pam>
* kvm <https://www.linux-kvm.org/page/Main_Page>
* eBPF (Extended Berkeley Packet Filter) <https://ebpf.io/>
* FUSE (Filesystem in Userspace) <https://github.com/libfuse/libfuse>
  * s3fs <https://github.com/s3fs-fuse/s3fs-fuse>
* Systemd <https://www.freedesktop.org/wiki/Software/systemd/>
  * journald <https://www.freedesktop.org/software/systemd/man/latest/systemd-journald.html#>
  * hostnamed <https://www.freedesktop.org/software/systemd/man/latest/systemd-hostnamed.html#>
  * networkd <https://www.freedesktop.org/software/systemd/man/latest/systemd-networkd.html#>
  * resolved <https://www.freedesktop.org/software/systemd/man/latest/systemd-resolved.html#>
  * timesyncd <https://www.freedesktop.org/software/systemd/man/latest/systemd-timesyncd.html#>
* Host administration
  * util-linux <https://git.kernel.org/pub/scm/utils/util-linux/util-linux.git/>
    * lsblk <https://man7.org/linux/man-pages/man8/lsblk.8.html>
    * lsns <https://man7.org/linux/man-pages/man8/lsns.8.html>
    * swapon <https://man7.org/linux/man-pages/man8/swapon.8.html>
  * rsync <https://rsync.samba.org/>
  * Vixie Cron <https://github.com/vixie/cron>
  * logrotate <https://github.com/logrotate/logrotate>
  * Syslog <https://en.wikipedia.org/wiki/Syslog> - A standard for message logging
    * rsyslog <https://www.rsyslog.com/> - The rocket-fast system for log processing
  * procps <https://gitlab.com/procps-ng/procps>
    * ps <https://man7.org/linux/man-pages/man1/ps.1.html>
    * top <https://www.man7.org/linux/man-pages/man1/top.1.html>
    * free <https://www.man7.org/linux/man-pages/man1/free.1.html>
    * vmstat <https://www.man7.org/linux/man-pages/man8/vmstat.8.html>
  * psmisc <https://gitlab.com/psmisc/psmisc>
    * pstree <https://man7.org/linux/man-pages/man1/pstree.1.html>
    * killall <https://man7.org/linux/man-pages/man1/killall.1.html>
  * lsof <https://lsof.readthedocs.io/en/latest/>
  * sudo <https://www.sudo.ws/>
  * shadow-utils <https://github.com/shadow-maint/shadow>
    * useradd <https://man7.org/linux/man-pages/man8/useradd.8.html>
  * strace <https://strace.io/>
  * dtrace <https://dtrace.org/about/>
  * neofetch <https://github.com/dylanaraps/neofetch>
  * inxi <https://smxi.org/docs/inxi.htm>
  * atop <https://github.com/Atoptool/atop#atop>
  * nmon <https://nmon.sourceforge.net/pmwiki.php>
  * sysstat <https://sysstat.github.io/>
    * iostat <https://man7.org/linux/man-pages/man1/iostat.1.html>
  * smem <https://www.selenic.com/smem/>
  * NTP <https://en.wikipedia.org/wiki/Network_Time_Protocol>
    * chrony <https://chrony.tuxfamily.org/>
    * pool.ntp.org <https://www.ntppool.org/en/>
  * jc <https://kellyjonbrazil.github.io/jc/docs/> - Json adaptor
  * aha <https://github.com/theZiz/aha> - Ansi HTML Adapter
    * NO_COLOR <https://no-color.org/>
* Network administration
  * iproute2 <https://github.com/shemminger/iproute2>
    * ip <https://man7.org/linux/man-pages/man8/ip.8.html>
    * ss <https://man7.org/linux/man-pages/man8/ss.8.html>
  * net-tools <https://sourceforge.net/projects/net-tools/>
    * ifconfig <https://man7.org/linux/man-pages/man8/ifconfig.8.html>
    * netstat <https://man7.org/linux/man-pages/man8/netstat.8.html>
  * traceroute <https://traceroute.sourceforge.net/>
  * NetworkManager <https://networkmanager.dev/>
  * Ubuntu NetPlan <https://netplan.io/>
  * tcpdump <https://www.tcpdump.org/>
  * wireshark <https://www.wireshark.org/>
  * netcat <https://nc110.sourceforge.io/>
  * nmap <https://nmap.org/>
  * SOCKS proxy <https://en.wikipedia.org/wiki/SOCKS>
    * dante <https://www.inet.no/dante/>
    * tun2socks <https://github.com/xjasonlyu/tun2socks>
    * proxychains <https://github.com/haad/proxychains>
* Modern Unix tools
  * lsd <https://github.com/Peltoche/lsd>
  * eza <https://eza.rocks/>
  * broot <https://dystroy.org/broot/>
  * bat <https://github.com/sharkdp/bat>
  * dust <https://github.com/bootandy/dust>
  * dua <https://github.com/byron/dua-cli>
  * duf <https://github.com/muesli/duf>
  * procs <https://github.com/dalance/procs>
  * htop <https://hisham.hm/htop/>
  * btop++ <https://github.com/aristocratos/btop>
  * glances <https://nicolargo.github.io/glances/>
* OS package management
  * Dpkg <https://wiki.debian.org/Teams/Dpkg>
    * APT <https://salsa.debian.org/apt-team/apt>
  * Pacman <https://archlinux.org/pacman/>
    * Yay <https://github.com/Jguer/yay>
  * Homebrew <https://brew.sh/>
  * Flatpak <https://flatpak.org/>
  * Snapcraft <https://snapcraft.io/>
  * arkade <https://github.com/alexellis/arkade> - Open Source Marketplace For Developer Tools

## 220 - Domain name system and Email

* DNS <https://en.wikipedia.org/wiki/Domain_Name_System>
  * mDNS <https://en.wikipedia.org/wiki/Multicast_DNS>
  * IANA WHOIS Service <https://www.iana.org/whois>
  * BIND (dnsutils) <https://www.isc.org/bind/>
    * dig <https://linux.die.net/man/1/dig>
    * nslookup <https://linux.die.net/man/1/nslookup>
  * CoreDNS <https://coredns.io/> - DNS and Service Discovery
  * dog <https://dns.lookup.dog/>
  * Doggo <https://doggo.mrkaran.dev/docs/>
  * systemd-resolved <https://man7.org/linux/man-pages/man8/systemd-resolved.service.8.html>
  * Avahi <https://www.avahi.org/>
  * Bonjour <https://developer.apple.com/bonjour/>
* Email <https://en.wikipedia.org/wiki/Email>
  * Unix Mbox and Maildir formats
  * MIME <https://en.wikipedia.org/wiki/MIME>
    * Quoted-printable encoding <https://en.wikipedia.org/wiki/Quoted-printable>
    * Base64 <https://en.wikipedia.org/wiki/Base64>
    * GNU sharutils <https://www.gnu.org/software/sharutils/>
  * SMTP <https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol>
  * Postfix <https://www.postfix.org/>
  * Email::Sender::Simple <https://metacpan.org/pod/Email::Sender::Simple>
  * Email::MIME <https://metacpan.org/pod/Email::MIME>
  * mailutils <https://mailutils.org/>
    * mail command <https://mailutils.org/manual/html_section/mail.html>
  * mutt <http://www.mutt.org/>
  * swaks <http://www.jetmore.org/john/code/swaks/>
  * charm_Pop <https://github.com/charmbracelet/pop> - Send emails from your terminal
  * Email receiving and readers
    * IMAP <https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol>
    * POP <https://en.wikipedia.org/wiki/Post_Office_Protocol>
    * Cyrus IMAP <https://www.cyrusimap.org/> (reference)
    * Dovecot <https://www.dovecot.org/> (reference)
    * Thunderbird <https://www.thunderbird.net/en-US/>
    * Sylpheed <https://sylpheed.sraoss.jp/en/>
    * Mutt <http://www.mutt.org/>
    * Gnus <https://www.gnus.org/>
  * listmonk <https://listmonk.app/> - Self-hosted newsletter and mailing list manager
* PaaS
  * Amazon Route53 <https://aws.amazon.com/route53/>
  * Amazon SES <https://aws.amazon.com/ses/>
  * Twilio SendGrid <https://www.twilio.com/sendgrid/email-api>

## 230 - Linux container and WebAssembly

* The Open Container Initiative (OCI) <https://opencontainers.org/>
* Container runtimes and tools
  * Docker Engine <https://docs.docker.com/engine/>
    * docker-compose <https://docs.docker.com/compose/>
  * containerd <https://containerd.io/>
    * nerdctl <https://github.com/containerd/nerdctl>
  * Docker Build <https://docs.docker.com/build/>
  * podman <https://podman.io/>
  * buildah <https://buildah.io/>
  * skopeo <https://github.com/containers/skopeo>
  * Kaniko <https://github.com/GoogleContainerTools/kaniko>
  * lazydocker <https://github.com/jesseduffield/lazydocker>
  * dive <https://github.com/wagoodman/dive>
* Container registries
  * GitLab Container Registry <https://docs.gitlab.com/ee/user/packages/container_registry/index.html>
  * Nexus Repository Manager 3 <https://help.sonatype.com/repomanager3>
  * Amazon ECR <https://aws.amazon.com/ecr/>
  * Azure Container Registry <https://azure.microsoft.com/en-us/services/container-registry/>
  * Harbor <https://goharbor.io/> - an open source registry that secures artifacts with policies and role-based access control
* WebAssembly <https://webassembly.org/>
  * WebAssembly System Interface (WASI) <https://github.com/WebAssembly/WASI>
* WebAssembly runtimes
  * wazero <https://wazero.io/>
  * wasmtime <https://wasmtime.dev/>
  * wasmer <https://wasmer.io/>

## 240 - Kubernetes

* Kubernetes <https://kubernetes.io/>
* Byzantine fault <https://en.wikipedia.org/wiki/Byzantine_fault>
  * consensus <https://en.wikipedia.org/wiki/Consensus_(computer_science)>
* K8s as a service
  * GKE <https://cloud.google.com/kubernetes-engine/>
  * Azure Kubernetes Service <https://azure.microsoft.com/en-us/services/kubernetes-service/>
  * AWS EKS <https://aws.amazon.com/eks/>
    * eksctl <https://eksctl.io/>
* Master node
  * kube-apiserver - Responsible for API services
  * kube-scheduler - Responsible for scheduling
  * kube-controller-manager - Responsible for container orchestration
* Compute node
  * kubelet - watches the API server for pods on that node and makes sure they are running
  * cAdvisor - collects metrics about pods running on that particular node
  * kube-proxy - watches the API server for pods/services changes in order to maintain the network up to date
  * container runtime - responsible for managing container images and running containers on that node
* Standards
  * CNI (Container Networking Interface)
  * CSI (Container Storage Interface)
  * CRI (Container Runtime Interface)
    * cri-o <https://cri-o.io/>
    * cri-tools <https://github.com/kubernetes-sigs/cri-tools>
* Configuration <https://kubernetes.io/docs/concepts/configuration/>
  * Secret, ConfigMap
* Workloads <https://kubernetes.io/docs/concepts/workloads/>
  * Pod
    * assignment <https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/>
    * taint and toleration <https://kubernetes.io/docs/concepts/scheduling-eviction/taint-and-toleration/>
    * lifecycle <https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/>
    * liveness probe <https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/>
    * requests and limits
    * security context <https://kubernetes.io/docs/tasks/configure-pod-container/security-context/>
    * eviction
  * Deployment, ReplicaSet, StatefulSet, DaemonSet
* Storage <https://kubernetes.io/docs/concepts/storage/>
  * PersistentVolume, PVC, StorageClass
* Kubernetes RBAC <https://kubernetes.io/docs/reference/access-authn-authz/rbac/>
* Kubernetes network model <https://kubernetes.io/docs/concepts/services-networking/>
  * Service, Ingress, Ingress Controllers
* PodDisruptionBudget <https://kubernetes.io/docs/tasks/run-application/configure-pdb/>
* HPA <https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/>
* Autoscalers <https://github.com/kubernetes/autoscaler/tree/master>
* kube-fencing <https://github.com/kvaps/kube-fencing>
* KubeVirt <https://kubevirt.io/> - Building a virtualization API for Kubernetes
* Kubebuilder <https://github.com/kubernetes-sigs/kubebuilder> - A framework for building Kubernetes APIs using custom resource definitions (CRDs)
* Networking
  * Calico <https://www.tigera.io/projectCalico>
  * Cilium <https://cilium.io/>
* Kustomize <https://kustomize.io/> - A standalone tool to customize Kubernetes objects through a kustomization file
* Helm <https://helm.sh/> - The package manager for Kubernetes
* Dashboard
  * Kubernetes Lens IDE <https://k8slens.dev/>
  * k9s <https://k9scli.io/> - A terminal based UI to interact with your Kubernetes cluster
  * KDash <https://kdash.cli.rs/> - A simple terminal dashboard for Kubernetes built with Rust
  * k1s <https://github.com/weibeld/k1s> - A minimalistic Kubernetes dashboard
  * Seabird <https://getseabird.github.io/> - The native desktop app that simplifies working with Kubernetes
  * Headlamp <https://headlamp.dev/> - A user-friendly Kubernetes UI focused on extensibility
* Krew <https://krew.sigs.k8s.io/> - The plugin manager for kubectl command-line tool
  * kubectl-node-shell <https://github.com/kvaps/kubectl-node-shell>
  * kubectl-tree <https://github.com/ahmetb/kubectl-tree#readme>
  * kubectl-pod-inspect <https://github.com/jpriebe/kubectl-pod-inspect#readme>
  * kubepug <https://github.com/rikatz/kubepug>
  * rakkess <https://github.com/corneliusweig/rakkess>
  * ketall <https://github.com/corneliusweig/ketall>
* Local K8s
  * Minikube <https://minikube.sigs.k8s.io/docs/>
  * Kind <https://kind.sigs.k8s.io/>
* FaaS on K8s
  * OpenFaaS <https://www.openfaas.com/>
  * Knative <https://knative.dev/>
* K8s operators
  * Prometheus Operator <https://prometheus-operator.dev/>
    * kube-prometheus <https://github.com/prometheus-operator/kube-prometheus>
  * OpenTelemetry Operator <https://opentelemetry.io/docs/kubernetes/operator/>
  * Elastic Cloud on Kubernetes (ECK) <https://www.elastic.co/elastic-cloud-kubernetes>
  * Rook <https://rook.io/> - Storage Operators for Kubernetes

## 250 - IaC, configuration management, and continuous delivery

* Configuration management and infrastructure as code
  * idempotency <https://en.wikipedia.org/wiki/Idempotence>
  * Ansible <https://www.ansible.com/>
  * Hashicorp Packer <https://packer.io/>
  * cloud-init <https://cloud-init.io/>
  * Hashicorp Terraform <https://www.terraform.io/>
    * GitLab-managed Terraform state <https://docs.gitlab.com/ee/user/infrastructure/iac/terraform_state.html>
    * tf.libsonnet <https://docs.tflibsonnet.com/>
    * terraform-docs <https://terraform-docs.io/>
    * Terraformer <https://github.com/GoogleCloudPlatform/terraformer>
    * Atrantis (reference) <https://www.runatlantis.io/>
  * OpenTofu <https://opentofu.org/> - A fork of Terraform
  * Serverless Framework <https://serverless.com/>
  * AWS CloudFormation <https://aws.amazon.com/cloudformation/>
  * AWS CDK <https://aws.amazon.com/cdk/>
  * AWS SAM <https://aws.amazon.com/serverless/sam/>
  * Azure Resource Manager <https://docs.microsoft.com/en-us/azure/azure-resource-manager/>
    * Bicep language <https://github.com/Azure/bicep>
  * Pulumi <https://www.pulumi.com/>
  * AWS Systems Manager <https://aws.amazon.com/systems-manager/>
  * Azure Update Manager <https://learn.microsoft.com/en-us/azure/update-manager/>
* Continuous delivery
  * Jenkins <https://www.jenkins.io/>
    * Blue Ocean for Jenkins Pipelines <https://www.jenkins.io/projects/blueocean/>
    * Python Jenkins <https://opendev.org/jjb/python-jenkins>
  * GitLab CI/CD <https://docs.gitlab.com/ee/ci/>
  * GitHub Actions <https://github.com/features/actions>
  * Concourse CI <https://concourse-ci.org/>
  * Azure Pipelines <https://learn.microsoft.com/en-us/azure/devops/pipelines/>
  * GitOps
    * ArgoCD <https://argo-cd.readthedocs.io/>
    * FluxCD <https://fluxcd.io/>
  * Cloud native application delivery
    * Open Application Model <https://oam.dev/>
    * KubeVela <https://kubevela.io/>
    * Flagger <https://flagger.app/>
* Private package registries
  * GitLab Package Registry <https://docs.gitlab.com/ee/user/packages/package_registry/index.html>
  * GitHub Packages <https://github.com/features/packages>
  * Nexus Repository Manager 3 <https://help.sonatype.com/repomanager3>
  * Azure Artifacts <https://learn.microsoft.com/en-us/azure/devops/artifacts/>
* Version conventions
  * Semantic Versioning <https://semver.org/>
    * semver <https://github.com/npm/node-semver#readme>

## 260 - Infrastructure cloud

* Server and load balancer
  * Amazon EC2 <https://aws.amazon.com/ec2/>
    * Amazon EBS <https://aws.amazon.com/ebs/>
  * Amazon VPC <https://aws.amazon.com/vpc/>
  * Amazon ELB <https://aws.amazon.com/elasticloadbalancing/>
  * Azure Virtual Machines <https://azure.microsoft.com/en-us/services/virtual-machines/>
    * Azure Disk Storage <https://azure.microsoft.com/en-us/services/storage/disks/>
  * Azure Virtual Network <https://azure.microsoft.com/en-us/services/virtual-network/>
  * Azure Load Balancer <https://azure.microsoft.com/en-us/products/load-balancer>
  * Google Cloud Compute Engine <https://cloud.google.com/products/compute>
  * OpenStack <https://www.openstack.org/> - A cloud operating system that controls large pools of compute
  * Open vSwitch <https://www.openvswitch.org/>
  * DPDK <https://www.dpdk.org/>
  * FD.io <https://fd.io/>
* Object storage <https://en.wikipedia.org/wiki/Object_storage>
  * Amazon S3 <https://aws.amazon.com/s3/>
  * Ceph <https://ceph.com/en/> - An open-source, distributed storage system
  * MinIO <https://min.io/> - A high-performance, S3 compatible object store
  * Azure Blob Storage <https://azure.microsoft.com/en-us/services/storage/blobs/>
  * Azure Storage Exproler <https://azure.microsoft.com/en-us/products/storage/storage-explorer/> - Manage your Azure cloud storage resources from your desktop
  * Google Cloud Storage <https://cloud.google.com/storage/>
* File transfers
  * s5cmd <https://github.com/peak/s5cmd>
  * Rclone <https://rclone.org/> - A command-line program to manage files on cloud storage

## 270 - Stress test, load test, chaos engineering, and FinOps

* ab <https://httpd.apache.org/docs/2.4/programs/ab.html> - Apache HTTP server benchmarking tool
* stress-ng <https://github.com/ColinIanKing/stress-ng>
* sysbench <https://github.com/akopytov/sysbench> - Scriptable database and system performance benchmark
* fio <https://github.com/axboe/fio> - Flexible I/O Tester
* iPerf <https://iperf.fr/> - The ultimate speed test tool for TCP, UDP and SCTP
* Load test
  * Grafana k6 <https://k6.io/>
  * Gatling <https://gatling.io/>
  * Apache Jmeter <https://jmeter.apache.org/>
* Chaos engineering <https://en.wikipedia.org/wiki/Chaos_engineering>
  * Principles of chaos engineering <https://principlesofchaos.org/>
  * Litmus <https://litmuschaos.io/> - an open source Chaos Engineering
  * Chaos Mesh <https://chaos-mesh.org/> - an open source cloud-native Chaos Engineering platform
  * toxiproxy <https://github.com/Shopify/toxiproxy> - A TCP proxy to simulate network and system conditions for chaos and resiliency testing
* FinOps
  * FinOps principles <https://www.finops.org/framework/principles/>
  * FinOps toolkit <https://microsoft.github.io/finops-toolkit/>
  * AWS Cost Explorer <https://aws.amazon.com/aws-cost-management/aws-cost-explorer/>
  * OpenCost <https://www.opencost.io/>
  * Karpenter <https://karpenter.sh/>
  * Cloud Custodian <https://cloudcustodian.io/>

## 280 - Server telemetry ETL and visualization

* Data shipping
  * Prometheus exporters <https://prometheus.io/docs/instrumenting/exporters/>
    * node-exporter <https://prometheus.io/docs/guides/node-exporter/>
    * blackbox-exporter <https://github.com/prometheus/blackbox_exporter>
  * Promtail agent <https://grafana.com/docs/loki/latest/clients/promtail/>
  * Fluent Bit <https://fluentbit.io/>
  * Fluentd <https://www.fluentd.org/>
  * Filebeat <https://www.elastic.co/beats/filebeat>
  * Logstash <https://www.elastic.co/logstash>
  * Telegraf <https://www.influxdata.com/time-series-platform/telegraf/>
  * Metricbeat <https://www.elastic.co/beats/metricbeat>
  * OpenTelemetry <https://opentelemetry.io/>
  * Micrometer <https://micrometer.io/> - a metrics instrumentation library for JVM-based applications
  * rsyslog <https://www.rsyslog.com/> - The rocket-fast system for log processing
  * IaaS-specific
    * Azure Monitor Agent <https://learn.microsoft.com/en-us/azure/azure-monitor/agents/agents-overview>
    * Cloudwatch Agent <https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/Install-CloudWatch-Agent.html>
* Datastore and monitoring
  * Prometheus <https://prometheus.io/>
    * PromQL <https://prometheus.io/docs/prometheus/latest/querying/basics/>
    * promtool <https://prometheus.io/docs/prometheus/latest/command-line/promtool/>
  * Alertmanager <https://prometheus.io/docs/alerting/latest/alertmanager/>
    * amtool <https://github.com/prometheus/alertmanager/tree/main?tab=readme-ov-file#amtool>
  * InfluxDB <https://www.influxdata.com/products/influxdb-overview/>
    * InfluxQL <https://docs.influxdata.com/influxdb/v1/query_language/>
    * influx cli <https://docs.influxdata.com/influxdb/cloud/reference/cli/influx/>
  * Grafana Mimir <https://grafana.com/oss/mimir/>
  * Grafana Loki <https://grafana.com/oss/loki/>
    * LogQL <https://grafana.com/docs/loki/latest/query/>
      * LogCLI <https://grafana.com/docs/loki/latest/query/logcli/>
  * Grafana Tempo <https://grafana.com/oss/tempo/>
    * TraceQL <https://grafana.com/docs/tempo/latest/traceql/>
  * ElasticSearch <https://www.elastic.co/elasticsearch/> - An open source distributed, RESTful search and analytics engine, scalable data store, and vector database
    * Elastic Common Schema <https://www.elastic.co/guide/en/ecs/current/index.html> - An open source specification, developed with support from the Elastic user community
    * Ingest pipelines <https://www.elastic.co/guide/en/elasticsearch/reference/current/ingest.html>
    * Dissect and Grok <https://www.elastic.co/guide/en/elasticsearch/reference/current/esql-process-data-with-dissect-and-grok.html>
  * Graphite <https://grafana.com/oss/graphite/>
  * Grafana Alerting <https://grafana.com/docs/grafana/latest/alerting/>
  * Azure Monitor <https://docs.microsoft.com/en-us/azure/azure-monitor/overview>
    * Kusto Query Language <https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/>
    * App Insights <https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview>
  * AWS CloudWatch <https://aws.amazon.com/cloudwatch/>
* Visualization
  * Grafana <https://grafana.com/oss/grafana/> - The open source data visualization and monitoring solution
    * Grafonnet <https://grafana.github.io/grafonnet/> - Jsonnet library for generating Grafana dashboards
  * Kibana <https://www.elastic.co/kibana> - Discover, iterate, and resolve with ES|QL
  * Uptime Kuma <https://uptime.kuma.pet/> - An easy-to-use self-hosted monitoring tool
  * Azure Dashboard <https://learn.microsoft.com/en-us/azure/azure-portal/azure-portal-dashboards>
  * Datadog <https://www.datadoghq.com/>

## 290 - DevOps workspace

* Linux desktop
  * Debian <https://www.debian.org/> - A complete Free Operating System
    * Ubuntu <https://ubuntu.com/>
    * BunsenLabs Linux <https://www.bunsenlabs.org/> - A distribution offering a light-weight and easily customizable Openbox desktop
  * Arch Linux <https://archlinux.org/> - A simple, lightweight distribution
    * Manjaro Linux <https://manjaro.org/> - A user-friendly Linux distribution based on the independently developed Arch operating system
    * Mabox Linux <https://maboxlinux.org/> - Fast, lightweight and functional Linux Desktop “relaxed” rolling-release, Manjaro based with Openbox Window Manager
  * GUI systems
    * X.org <https://www.x.org/wiki/> - An open source implementation of the X Window System
    * Wayland <https://wayland.freedesktop.org/> - A replacement for the X11 window system protocol and architecture
    * GNOME <https://www.gnome.org/>
    * Xfce <https://www.xfce.org/> - A lightweight desktop environment for UNIX-like operating systems
    * openbox <http://openbox.org> - A highly configurable, next generation window manager
    * i3 <https://i3wm.org/> - A tiling window manager
* Type-2 hypervisors
  * VirtualBox <https://www.virtualbox.org/>
  * QEMU <https://www.qemu.org/>
* Remote access
  * RDP <https://en.wikipedia.org/wiki/Remote_Desktop_Protocol>
  * RFB <https://github.com/rfbproto/rfbproto/blob/master/rfbproto.rst>
  * x11vnc <https://github.com/LibVNC/x11vnc>
  * TightVNC <https://www.tightvnc.com/>
  * xrdp <https://github.com/neutrinolabs/xrdp>
  * Remmina <https://remmina.org/>
  * WinSSHTerm <https://winsshterm.blogspot.com/> - A tabbed SSH solution for Windows, combining PuTTY, WinSCP and VcXsrv
  * Mosh <https://mosh.org/> - A replacement for interactive SSH terminals
* File sharing
  * SMB <https://en.wikipedia.org/wiki/Server_Message_Block>
    * Samba <https://www.samba.org/>
  * FTP <https://en.wikipedia.org/wiki/File_Transfer_Protocol>
    * vsftpd <https://security.appspot.com/vsftpd.html>
  * SFTP <https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol>
* Windows administration
  * Chocolatey <https://chocolatey.org>
  * Scoop <https://scoop.sh/>
  * gsudo <https://gerardog.github.io/gsudo/>
* Windows tools
  * AutoHotKey <https://www.autohotkey.com/> - A free, open-source scripting language for Windows that allows users to easily create small to complex scripts
  * Clavier+ <https://gryder.org/software/clavier-plus/> - Allows to trigger actions with keyboard shortcuts