# Awesome osquery

## Contents
- [Official documentation](#official-documentation)
- [osquery extensions](#-osquery--extensions)
- [osquery with containers](#-osquery--with-containers)
- [Forensics with osquery](#forensics-with-osquery)
- [Tools and resources for Linux eBPF](#tools-and-resources-for-linux-ebpf)
- [osquery at scale talks](#osquery-at-scale-talks)
- [osquery and linux audit](#osquery-and-linux-audit)


## Official documentation
Documentation published and vetted by the osquery maintainers.

* [osquery schema v4.9.0](https://osquery.io/schema/4.9.0/)

## osquery extensions

* [trailofbits/osquery-extensions](https://github.com/trailofbits/osquery-extensions
) - A collection of osquery extensions from trailofbits.
* [macadmins/osquery-extension](https://github.com/macadmins/osquery-extension
) - A collection of tables for querying MacOS.

## osquery with containers

* [Monitoring containers using osquery](https://developer.ibm.com/technologies/containers/articles/monitoring-containers-osquery/) - IBM tech blog on Monitoring containers using osquery
* [aquasecurity/kube-query](https://github.com/aquasecurity/kube-query) - An
  experimental osquery extension to query your kubernetes clusters.
* [uptycs/kubequery](https://github.com/Uptycs/kubequery) - uptycs
  implementation for querying kubernetes.
* [Monitoring and inspecting docker container and images with
  osquery](https://zercurity.medium.com/monitoring-and-inspecting-docker-containers-images-with-osquery-2ae4e43a1b0b)
* [osquery and Docker containers](https://www.youtube.com/watch?v=TG4GzGn7_XI) -
  QueryCon 2018 | UpTycs | osquery and docker containers
* [Using osquery with containers using
  eBPF](https://www.uptycs.com/blog/get-started-using-osquery-for-container-security
  ) - Using the linux kernel tracepoint infrastructure for auditing containers
* [osquery at scale - containers and osquery](https://www.youtube.com/watch?v=ocenGbEYiwA) - UpTycs talk on osquery for container security
    - UpTycs blog on getting started using [osquery for container
      security](https://www.uptycs.com/blog/get-started-using-osquery-for-container-security)
* [kubeIR/osquery_exporter](https://github.com/kubeIR/osquery_exporter) - Expose
  the osquery sql interface over HTTP.
* [Detecting container malware using
  osquery](https://www.uptycs.com/blog/detecting-docker-container-malware-using-osquery)

## Forensics with osquery

* [Digital forensics and Incident response using osquery](https://medium.com/adobetech/digital-forensics-and-incident-response-using-osquery-6565ba944bb2)
* [Using osquery for remote
  forensics](https://securityboulevard.com/2019/05/using-osquery-for-remote-forensics/)
* [osquery across the
  enterprise](https://blog.palantir.com/osquery-across-the-enterprise-3c3c9d13ec55)
* [Real time forensics through endpoint
  visibility](https://publications.sba-research.org/publications/fleetForensics.pdf) - Peter Kieseberg, Sebastian Schrittweiser, et al.
## Tools and resources for Linux eBPF

* [trailofbits/ebpfpub](https://github.com/trailofbits/ebpfpub) - Generic function tracing library
  for linux that supports tracepoints, kprobes and uprobes.
* [iovisor/bcc](https://github.com/iovisor/bcc) - The compiler toolchain for
  eBPF
* [The linux BPF reference](https://docs.cilium.io/en/stable/bpf/) - A
  comprehensive documentation on eBPF for linux by Cilium
* [Tools using the bcc toolchain](https://github.com/iovisor/bcc/tree/master/tools) - some tools that use the bcc
infrastructure for tracing.
* [What are containers made of](https://www.youtube.com/watch?v=sK5i-N34im8) - A
  guide on what containers are made of.

## osquery at scale talks

* [osquery at scale 2020](https://www.osqueryatscale.com/2020-session-videos)
* [osquery at scale 2021](https://www.osqueryatscale.com/2021-session-videos)

## osquery and linux audit

* [Auditing with linux
  audit - Part 1](https://blog.palantir.com/auditing-with-osquery-part-one-introduction-to-the-linux-audit-framework-217967cec406) - Intro to the linux audit framework
* [Auditing with linux audit - Part
  2](https://blog.palantir.com/auditing-with-osquery-part-two-configuration-and-implementation-87a8bba0ef48) - Configuring osquery for auditing
* [slackhq/go-audit](https://github.com/slackhq/go-audit) - Tool to read and
  parse linux audit logs
* [elastic/go-libaudit](https://github.com/elastic/go-libaudit) - Library to
  communicate with the linux audit service.
* [linux-audit/audit-userspace](https://github.com/linux-audit/audit-userspace) - userspace component for the linux audit service.
