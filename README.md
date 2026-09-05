# Awesome Sysadmin with stars

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome) ⭐ 503,091 | 🐛 106 | 📅 2026-09-02 [![](https://github.com/awesome-foss/awesome-sysadmin-data/actions/workflows/dead-links.yml/badge.svg)](https://github.com/awesome-foss/awesome-sysadmin-data/issues/1) ⭐ 9 | 🐛 21 | 🌐 Makefile | 📅 2026-09-04 [![](https://github.com/awesome-foss/awesome-sysadmin-data/actions/workflows/unmaintained-projects.yml/badge.svg)](https://github.com/awesome-foss/awesome-sysadmin-data/issues/1) ⭐ 9 | 🐛 21 | 🌐 Makefile | 📅 2026-09-04

**A curated list of amazingly awesome Free and Open-Source sysadmin resources.** Please read the [Contributing](#contributing) if you wish to add software and consider <b><code>    47⭐</code></b> <b><code>     4🍴</code></b> [donating](https://github.com/n1trux/awesome-donations) ⭐ 47 | 🐛 2 | 📅 2024-01-02) to the FLOSS projects you use regularly. Please consider contributing to fix one of the pinned <b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [issues](https://github.com/awesome-foss/awesome-sysadmin-data/issues) ⭐ 9 | 🐛 21 | 🌐 Makefile | 📅 2026-09-04) if your time allows.

* 🌎 [HTML version](sysadmin.awesome-selfhosted.net/) (recommended)\*\*, **[Markdown version](https://github.com/correia-jpv/fucking-awesome-sysadmin) ⭐ 93 | 🐛 1 | 📅 2026-09-04** (legacy).

See [Contributing](#contributing).

***

## Table of contents

* [Software](#software)
  * [Automation](#automation)
  * [Backups](#backups)
  * [Build and software organization tools](#build-and-software-organization-tools)
  * [ChatOps](#chatops)
  * [Cloud Computing](#cloud-computing)
  * [Code Review](#code-review)
  * [Configuration Management](#configuration-management)
  * [Configuration Management Database](#configuration-management-database)
  * [Continuous Integration & Continuous Deployment](#continuous-integration--continuous-deployment)
  * [Control Panels](#control-panels)
  * [Databases](#databases)
  * [Deployment Automation](#deployment-automation)
  * [Diagramming](#diagramming)
  * [Distributed Filesystems](#distributed-filesystems)
  * [DNS - Control Panels & Domain Management](#dns---control-panels--domain-management)
  * [DNS - Servers](#dns---servers)
  * [Editors](#editors)
  * [Identity Management](#identity-management)
  * [Identity Management - LDAP](#identity-management---ldap)
  * [Identity Management - Single Sign-On (SSO)](#identity-management---single-sign-on-sso)
  * [Identity Management - Tools and web interfaces](#identity-management---tools-and-web-interfaces)
  * [IT Asset Management](#it-asset-management)
  * [Log Management](#log-management)
  * [Mail Clients](#mail-clients)
  * [Metrics & Metric Collection](#metrics--metric-collection)
  * [Miscellaneous](#miscellaneous)
  * [Monitoring & Status Pages](#monitoring--status-pages)
  * [Network Configuration Management](#network-configuration-management)
  * [PaaS](#paas)
  * [Packaging](#packaging)
  * [Project Management](#project-management)
  * [Queuing](#queuing)
  * [Remote Desktop Clients](#remote-desktop-clients)
  * [Router](#router)
  * [Service Discovery](#service-discovery)
  * [Software Containers](#software-containers)
  * [Time Servers](#time-servers)
  * [Troubleshooting](#troubleshooting)
  * [Version control](#version-control)
  * [Virtualization](#virtualization)
  * [VPN](#vpn)
  * [Web](#web)
* [List of Licenses](#list-of-licenses)
* [Anti-features](#anti-features)
* [External links](#external-links)
  * [Communities / Forums](#communities--forums)
  * [Repositories](#repositories)
  * [Websites](#websites)
* [Contributing](#contributing)
* [License](#license)

***

## Software

### Automation

**[`^        back to top        ^`](#awesome-sysadmin)**

Build automation.

* 🌎 [Bazel](www.bazel.io/) - A fast, scalable, multi-language and extensible build system. Used by Google. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/bazelbuild/bazel/) ⭐ 25,805 | 🐛 1,841 | 🌐 Java | 📅 2026-09-04)) `Apache-2.0` `Java`
* 🌎 [Gradle](gradle.org/) - Another build automation system. (<b><code> 18825⭐</code></b> <b><code>  5350🍴</code></b> [Source Code](https://github.com/gradle/gradle) ⭐ 18,827 | 🐛 3,472 | 🌐 Groovy | 📅 2026-09-05)) `Apache-2.0` `Groovy/Java`
* 🌎 [Apache Maven](maven.apache.org/) - Build automation tool mainly for Java. A software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information. (<b><code>  5340⭐</code></b> <b><code>  3120🍴</code></b> [Source Code](https://github.com/apache/maven) ⭐ 5,340 | 🐛 676 | 🌐 Java | 📅 2026-09-04)) `Apache-2.0` `Java`
* 🌎 [Rake](ruby.github.io/rake/) - Build automation tool similar to Make, written in and extensible in Ruby. (<b><code>  2459⭐</code></b> <b><code>   649🍴</code></b> [Source Code](https://github.com/ruby/rake) ⭐ 2,459 | 🐛 73 | 🌐 Ruby | 📅 2026-08-24)) `MIT` `Ruby`
* 🌎 [Apache Ant](ant.apache.org/) - Automation build tool, similar to make, a library and command-line tool whose mission is to drive processes described in build files as targets and extension points dependent upon each other. (<b><code>   470⭐</code></b> <b><code>   456🍴</code></b> [Source Code](https://github.com/apache/ant) ⭐ 470 | 🐛 20 | 🌐 Java | 📅 2026-09-03)) `Apache-2.0` `Java`
* 🌎 [parse-dmarc](dmarcguard.io) `⚠` - DMARC aggregate report parser with a built-in dashboard. Fetches reports over IMAP, stores them, and flags spoofing. Single Go binary with embedded Vue UI, SQLite storage, and Prometheus metrics (alternative to PowerDMARC, EasyDMARC, Dmarcian). (<b><code>   200⭐</code></b> <b><code>    21🍴</code></b> [Source Code](https://github.com/dmarcguardhq/dmarcguard) ⭐ 200 | 🐛 24 | 🌐 Go | 📅 2026-09-05), <b><code>  1291⭐</code></b> <b><code>   265🍴</code></b> [Clients](https://github.com/domainaware/parsedmarc) ⭐ 1,291 | 🐛 5 | 🌐 Python | 📅 2026-09-03)) `Apache-2.0` `Go/Docker`
* 🌎 [OpenBolt](voxpupuli.org/openvox/) - Orchestration tool to run orchestration workflows or one-off tasks/scripts to automate the provisioning and management of nodes. Community fork of the last open source version of 🌎 [Puppet Bolt](help.puppet.com/bolt/current/topics/bolt.htm). (<b><code>    32⭐</code></b> <b><code>    24🍴</code></b> [Source Code](https://github.com/OpenVoxProject/openbolt) ⭐ 32 | 🐛 40 | 🌐 Ruby | 📅 2026-09-03)) `Apache-2.0` `Ruby`
* 🌎 [GNU Make](www.gnu.org/software/make/) - The most popular automation build tool for many purposes, make is a tool which controls the generation of executables and other non-source files of a program from the program's source files.  🌎 [Source Code](git.savannah.gnu.org/cgit/make.git)) `GPL-3.0` `C`

### Backups

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Backup](en.wikipedia.org/wiki/Backup) software.

*See also: <b><code>   756⭐</code></b> <b><code>    57🍴</code></b> [Restic's list of Linux backup software](https://github.com/restic/others) ⭐ 756 | 🐛 13 | 📅 2023-11-05)*

* 🌎 [rclone](rclone.org/) - Command-line program to sync files and directories to and from different cloud storage providers.. (<b><code> 59538⭐</code></b> <b><code>  5362🍴</code></b> [Source Code](https://github.com/rclone/rclone) ⭐ 59,563 | 🐛 1,258 | 🌐 Go | 📅 2026-09-04)) `MIT` `Go`
* 🌎 [Restic](restic.net/) - Easy, fast, verifiable, secure and efficient remote backup tool. (<b><code> 35850⭐</code></b> <b><code>  1862🍴</code></b> [Source Code](https://github.com/restic/restic) ⭐ 35,865 | 🐛 588 | 🌐 Go | 📅 2026-09-01)) `BSD-2-Clause` `Go`
* 🌎 [Duplicati](www.duplicati.com) - Backup client that securely stores encrypted, incremental, compressed backups on cloud storage services and remote file servers. (<b><code> 14964⭐</code></b> <b><code>  1070🍴</code></b> [Source Code](https://github.com/duplicati/duplicati) ⭐ 14,964 | 🐛 621 | 🌐 C# | 📅 2026-09-04)) `LGPL-2.1` `C#`
* 🌎 [BorgBackup](www.borgbackup.org/) - Deduplicating archiver with compression and authenticated encryption. (<b><code> 13690⭐</code></b> <b><code>   871🍴</code></b> [Source Code](https://github.com/borgbackup/borg) ⭐ 13,691 | 🐛 225 | 🌐 Python | 📅 2026-09-03)) `BSD-3-Clause` `Python`
* 🌎 [Databasus](databasus.com/) - PostgreSQL, MySQL, MariaDB and MongoDB backup tool with web UI, external storages (local, S3, FTP, Google Drive, etc.), notifications (webhook, Discord, Slack, etc.) and team management. (<b><code>  8422⭐</code></b> <b><code>   521🍴</code></b> [Source Code](https://github.com/databasus/databasus) ⭐ 8,427 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-31)) `Apache-2.0` `Docker`
* 🌎 [Backrest](garethgeorge.github.io/backrest/) - Backrest is a web UI and orchestrator for restic backup. (<b><code>  7265⭐</code></b> <b><code>   207🍴</code></b> [Source Code](https://github.com/garethgeorge/backrest) ⭐ 7,268 | 🐛 354 | 🌐 TypeScript | 📅 2026-08-31)) `GPL-3.0` `Docker/Go`
* 🌎 [Rsnapshot](rsnapshot.org/) - Filesystem snapshot utility based on rsync. (<b><code>  3668⭐</code></b> <b><code>   268🍴</code></b> [Source Code](https://github.com/rsnapshot/rsnapshot) ⭐ 3,668 | 🐛 58 | 🌐 Perl | 📅 2026-08-13)) `GPL-2.0` `Perl`
* 🌎 [Barman](pgbarman.org) - Backup and Recovery Manager for PostgreSQL. (<b><code>  3229⭐</code></b> <b><code>   270🍴</code></b> [Source Code](https://github.com/EnterpriseDB/barman) ⭐ 3,229 | 🐛 40 | 🌐 Python | 📅 2026-08-27)) `GPL-3.0` `Python`
* 🌎 [Portabase](portabase.io/) - Server dashboard tool that simplifies the backup and restoration of your database instances. (<b><code>  1679⭐</code></b> <b><code>   105🍴</code></b> [Source Code](https://github.com/Portabase/portabase) ⭐ 1,679 | 🐛 37 | 🌐 TypeScript | 📅 2026-08-27)) `Apache-2.0` `Docker`
* 🌎 [Rdiff-backup](rdiff-backup.net/) - Reverse differential backup tool, over a network or locally. (<b><code>  1265⭐</code></b> <b><code>   100🍴</code></b> [Source Code](https://github.com/rdiff-backup/rdiff-backup) ⭐ 1,265 | 🐛 83 | 🌐 Python | 📅 2026-08-23)) `GPL-2.0` `Python`
* 🌎 [Bareos](www.bareos.org/) - Cross-network backup solution which preserves, archives, and recovers data from all major operating systems. (<b><code>  1246⭐</code></b> <b><code>   311🍴</code></b> [Source Code](https://github.com/bareos/bareos) ⭐ 1,247 | 🐛 68 | 🌐 C++ | 📅 2026-09-04)) `AGPL-3.0` `C++/C`
* 🌎 [UrBackup](www.urbackup.org/) - Client/Server Open Source Network Backup for Windows, MacOS and Linux. (<b><code>   900⭐</code></b> <b><code>   167🍴</code></b> [Source Code](https://github.com/uroni/urbackup_backend) ⭐ 900 | 🐛 3 | 🌐 C | 📅 2026-08-30)) `AGPL-3.0` `C/C++`
* 🌎 [Burp](burp.grke.org/) - Network backup and restore program. (<b><code>   502⭐</code></b> <b><code>    77🍴</code></b> [Source Code](https://github.com/grke/burp) ⭐ 502 | 🐛 80 | 🌐 C | 📅 2026-07-13)) `AGPL-3.0` `C`
* <b><code>   401⭐</code></b> <b><code>    66🍴</code></b> [Shield](https://github.com/shieldproject/shield) ⭐ 401 | 🐛 33 | 🌐 Go | 📅 2026-09-02) - A pluggable architecture for backup and restore of database systems. `MIT` `Go`
* [Dar](http://dar.linux.free.fr/) - Which stands for Disk ARchive, is a robust and rich featured archiving and backup software of the tar style. (<b><code>   203⭐</code></b> <b><code>    24🍴</code></b> [Source Code](https://github.com/Edrusb/DAR) ⭐ 203 | 🐛 3 | 🌐 C++ | 📅 2026-08-19)) `GPL-2.0` `C++`
* 🌎 [Backupninja](0xacab.org/liberate/backupninja) - Lightweight, extensible meta-backup system, provides a centralized way to configure and coordinate many different backup utilities. `GPL-2.0` `Shell`
* 🌎 [Duplicity](duplicity.gitlab.io/) - Encrypted bandwidth-efficient backup using the rsync algorithm.  🌎 [Source Code](gitlab.com/duplicity/duplicity)) `GPL-2.0` `Python`
* 🌎 [Minarca](minarca.org/) - Client–server backup platform with a centralized web console to manage and restore Linux, Windows, and macOS backups via GUI or CLI.  🌎 [Source Code](gitlab.com/ikus-soft/minarca)) `AGPL-3.0` `Python`
* 🌎 [Proxmox Backup Server](www.proxmox.com/en/proxmox-backup-server) - Proxmox Backup Server is an enterprise-class, client-server backup solution thatis capable of backing up virtual machines, containers, and physical hosts.  🌎 [Source Code](git.proxmox.com/?p=proxmox-backup.git;a=tree)) `GPL-3.0` `Rust`

### Build and software organization tools

**[`^        back to top        ^`](#awesome-sysadmin)**

Build and software organization tools.

* 🌎 [Spack](spack.io/) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers. (<b><code>  5117⭐</code></b> <b><code>  2459🍴</code></b> [Source Code](https://github.com/spack/spack) ⭐ 5,117 | 🐛 1,803 | 🌐 Python | 📅 2026-09-04)) `MIT/Apache-2.0` `Python`
* 🌎 [Environment Modules](envmodules.io/) - Environment Modules provides for the dynamic modification of a user's environment via modulefiles. (<b><code>   864⭐</code></b> <b><code>   123🍴</code></b> [Source Code](https://github.com/envmodules/modules) ⭐ 864 | 🐛 29 | 🌐 Tcl | 📅 2026-09-01)) `GPL-2.0` `Tcl`
* 🌎 [Lmod](www.tacc.utexas.edu/research-development/tacc-projects/lmod) - Lmod is a Lua based module system that easily handles the MODULEPATH Hierarchical problem. (<b><code>   608⭐</code></b> <b><code>   147🍴</code></b> [Source Code](https://github.com/TACC/Lmod) ⭐ 608 | 🐛 27 | 🌐 Lua | 📅 2026-08-28)) `MIT` `Lua`
* 🌎 [EasyBuild](easybuild.io/) - EasyBuild builds software and modulefiles for High Performance Computing (HPC) systems in an efficient way. (<b><code>   449⭐</code></b> <b><code>   793🍴</code></b> [Source Code](https://github.com/easybuilders/easybuild-easyconfigs) ⭐ 449 | 🐛 1,145 | 🌐 Python | 📅 2026-09-04)) `GPL-2.0` `Python`

### ChatOps

**[`^        back to top        ^`](#awesome-sysadmin)**

Conversation-driven development and management.

*See also: 🌎 [/r/chatops](old.reddit.com/r/chatops)*

* 🌎 [Hubot](hubot.github.com/) - A customizable, life embetterment robot. (<b><code> 16797⭐</code></b> <b><code>  3711🍴</code></b> [Source Code](https://github.com/hubotio/hubot) ⭐ 16,796 | 🐛 7 | 🌐 JavaScript | 📅 2026-09-03)) `MIT` `Nodejs`
* 🌎 [Errbot](errbot.io/) - Plugin based chatbot designed to be easily deployable, extensible and maintainable. (<b><code>  3303⭐</code></b> <b><code>   626🍴</code></b> [Source Code](https://github.com/errbotio/errbot) ⭐ 3,305 | 🐛 45 | 🌐 Python | 📅 2026-08-17)) `GPL-3.0` `Python`
* 🌎 [Eggdrop](www.eggheads.org/) - The oldest Internet Relay Chat (IRC) bot still in active development. (<b><code>   581⭐</code></b> <b><code>   101🍴</code></b> [Source Code](https://github.com/eggheads/eggdrop) ⭐ 581 | 🐛 255 | 🌐 C | 📅 2026-08-02)) `GPL-2.0` `C`

### Cloud Computing

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Cloud computing](en.wikipedia.org/wiki/Cloud_computing) is the on-demand availability of computer system resources, especially data storage (cloud storage) and computing power, without direct active management by the user.

**Please visit 🌎 [Cloud Native Software Landscape](landscape.cncf.io/?group=projects-and-products\&view-mode=card)**

### Code Review

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Code review](en.wikipedia.org/wiki/Code_review) is a software quality assurance activity in which one or several people check a program mainly by viewing and reading parts of its source code.

**Please visit 🌎 [awesome-selfhosted/Software Development - Project Management](awesome-selfhosted.net/tags/software-development---project-management.html)**

### Configuration Management

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Configuration management (CM)](en.wikipedia.org/wiki/Configuration_management) is a systems engineering process for establishing and maintaining consistency of a product's performance, functional, and physical attributes with its requirements, design, and operational information throughout its life.

* 🌎 [Ansible](www.ansible.com/) - Provisioning, configuration management, and application-deployment tool. (<b><code> 70581⭐</code></b> <b><code> 24347🍴</code></b> [Source Code](https://github.com/ansible/ansible) ⭐ 70,590 | 🐛 841 | 🌐 Python | 📅 2026-09-04)) `GPL-3.0` `Python`
* 🌎 [Salt](docs.saltproject.io/) - Event-driven IT automation, remote task execution, and configuration management software. (<b><code> 15649⭐</code></b> <b><code>  5611🍴</code></b> [Source Code](https://github.com/saltstack/salt) ⭐ 15,650 | 🐛 1,885 | 🌐 Python | 📅 2026-09-01)) `Apache-2.0` `Python`
* 🌎 [cloud-init](cloud-init.io/) - Initialization tool to automate the configuration of VMs, cloud instances, or machines on a network. (<b><code>  3806⭐</code></b> <b><code>  1127🍴</code></b> [Source Code](https://github.com/canonical/cloud-init) ⭐ 3,806 | 🐛 606 | 🌐 Python | 📅 2026-09-04)) `GPL-3.0/Apache-2.0` `Python`
* 🌎 [Rudder](www.rudder.io/) - Scalable and dynamic configuration management system for patching, security & compliance, based on CFEngine. (<b><code>   706⭐</code></b> <b><code>    91🍴</code></b> [Source Code](https://github.com/Normation/rudder) ⭐ 707 | 🐛 44 | 🌐 Scala | 📅 2026-09-04)) `GPL-3.0` `Scala`
* 🌎 [CFEngine](cfengine.com/) - Configuration management system for automated configuration and maintenance of large-scale computer systems. (<b><code>   534⭐</code></b> <b><code>   201🍴</code></b> [Source Code](https://github.com/cfengine/core) ⭐ 534 | 🐛 10 | 🌐 C | 📅 2026-09-04)) `GPL-3.0` `C`
* 🌎 [OpenVox](voxpupuli.org/openvox/) - Community fork of the last open source version of 🌎 [Puppet](www.puppet.com/), a software configuration management tool which includes its own declarative language to describe system configuration. (<b><code>   187⭐</code></b> <b><code>    62🍴</code></b> [Source Code](https://github.com/OpenVoxProject/openvox) ⭐ 187 | 🐛 103 | 🌐 Ruby | 📅 2026-09-04)) `Apache-2.0` `Ruby/C`
* 🌎 [CINC](cinc.sh/) - Free distribution of 🌎 [Chef](www.chef.io/products/chef-infra), a configuration management tool using a pure-Ruby, domain-specific language (DSL) for writing system configuration "recipes".  🌎 [Source Code](gitlab.com/cinc-project/upstream/chef)) `Apache-2.0` `Ruby`

### Configuration Management Database

**[`^        back to top        ^`](#awesome-sysadmin)**

Configuration management database (CMDB) software.

*Related: [IT Asset Management](#it-asset-management)*

* 🌎 [netbox](netbox.dev/) - IP address management (IPAM) and data center infrastructure management (DCIM) tool.  🌎 [Demo](demo.netbox.dev/), <b><code> 21466⭐</code></b> <b><code>  3114🍴</code></b> [Source Code](https://github.com/netbox-community/netbox) ⭐ 21,475 | 🐛 213 | 🌐 Python | 📅 2026-09-05)) `Apache-2.0` `Python`
* 🌎 [iTop](combodo.com/) - Complete ITIL web based service management tool. (<b><code>  1173⭐</code></b> <b><code>   296🍴</code></b> [Source Code](https://github.com/Combodo/iTop) ⭐ 1,173 | 🐛 61 | 🌐 PHP | 📅 2026-09-04)) `AGPL-3.0` `PHP`
* 🌎 [i-doit](www.i-doit.org/) - IT Documentation and CMDB. `AGPL-3.0` `PHP`

### Continuous Integration & Continuous Deployment

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Continuous integration](en.wikipedia.org/wiki/Continuous_integration) 🌎 [deployment](en.wikipedia.org/wiki/Continuous_deployment) software.

* 🌎 [Harness](www.harness.io/open-source) - End-to-end developer platform with Source Control Management, CI/CD Pipelines, Hosted Developer Environments, and Artifact Registries (fork of Drone). (<b><code> 38232⭐</code></b> <b><code>  3381🍴</code></b> [Source Code](https://github.com/harness/harness) ⭐ 38,239 | 🐛 106 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Jenkins](jenkins-ci.org/) - Continuous Integration Server. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/jenkinsci/jenkins/) ⭐ 26,530 | 🐛 3,616 | 🌐 Java | 📅 2026-09-05)) `MIT` `Java`
* 🌎 [ArgoCD](argo-cd.readthedocs.io/en/stable/) - Declarative, GitOps continuous delivery tool for Kubernetes. (<b><code> 24076⭐</code></b> <b><code>  7822🍴</code></b> [Source Code](https://github.com/argoproj/argo-cd) ⭐ 24,079 | 🐛 4,351 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Concourse](concourse-ci.org/) - Concourse is a CI tool that treats pipelines as first class objects and containerizes every step along the way.  🌎 [Demo](ci.concourse-ci.org/), <b><code>  7896⭐</code></b> <b><code>   900🍴</code></b> [Source Code](https://github.com/concourse/concourse) ⭐ 7,897 | 🐛 83 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Woodpecker](woodpecker-ci.org/) - Community fork of Drone that uses Docker containers. (<b><code>  7810⭐</code></b> <b><code>   660🍴</code></b> [Source Code](https://github.com/woodpecker-ci/woodpecker) ⭐ 7,811 | 🐛 370 | 🌐 Go | 📅 2026-09-05)) `Apache-2.0` `Go`
* 🌎 [GoCD](www.go.cd/) - Continuous delivery server. (<b><code>  7432⭐</code></b> <b><code>   981🍴</code></b> [Source Code](https://github.com/gocd/gocd) ⭐ 7,432 | 🐛 82 | 🌐 Java | 📅 2026-09-04)) `Apache-2.0` `Java/Ruby`
* 🌎 [Buildbot](buildbot.net/) - Python-based toolkit for continuous integration. (<b><code>  5473⭐</code></b> <b><code>  1672🍴</code></b> [Source Code](https://github.com/buildbot/buildbot) ⭐ 5,473 | 🐛 808 | 🌐 Python | 📅 2026-09-04)) `GPL-2.0` `Python`
* 🌎 [CDS](ovh.github.io/cds/) - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform. (<b><code>  4838⭐</code></b> <b><code>   456🍴</code></b> [Source Code](https://github.com/ovh/cds) ⭐ 4,839 | 🐛 161 | 🌐 Go | 📅 2026-09-04)) `BSD-3-Clause` `Go`
* 🌎 [werf](werf.io/) - Open Source CI/CD tool for building Docker images and deploying to Kubernetes via GitOps. (<b><code>  4720⭐</code></b> <b><code>   238🍴</code></b> [Source Code](https://github.com/werf/werf) ⭐ 4,719 | 🐛 31 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Stategraph](stategraph.com) - GitOps-first automation platform for Terraform and OpenTofu workflows with support for self-hosted runners. (<b><code>  1279⭐</code></b> <b><code>    73🍴</code></b> [Source Code](https://github.com/stategraph/stategraph) ⭐ 1,279 | 🐛 113 | 🌐 OCaml | 📅 2026-09-04)) `MPL-2.0` `OCaml/Docker`
* <b><code>   687⭐</code></b> <b><code>   145🍴</code></b> [PHP Censor](https://github.com/php-censor/php-censor) ⭐ 687 | 🐛 23 | 🌐 PHP | 📅 2026-05-31) - Open source self-hosted continuous integration server for PHP projects. `BSD-2-Clause` `PHP`
* 🌎 [Laminar](laminar.ohwg.net) - Fast, lightweight, simple and flexible Continuous Integration. (<b><code>   354⭐</code></b> <b><code>    63🍴</code></b> [Source Code](https://github.com/ohwgiles/laminar) ⭐ 354 | 🐛 16 | 🌐 C++ | 📅 2026-08-16)) `GPL-3.0` `C++`
* 🌎 [GitLab CI](about.gitlab.com/solutions/continuous-integration/) - Gitlab's built-in, full-featured CI/CD solution.  🌎 [Source Code](gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby`

### Control Panels

**[`^        back to top        ^`](#awesome-sysadmin)**

Web hosting and server or service control panels.

* 🌎 [Cockpit](cockpit-project.org/) - Web-based graphical interface for servers. (<b><code> 15026⭐</code></b> <b><code>  1340🍴</code></b> [Source Code](https://github.com/cockpit-project/cockpit) ⭐ 15,030 | 🐛 480 | 🌐 JavaScript | 📅 2026-09-04)) `LGPL-2.1` `C`
* 🌎 [Ajenti](ajenti.org/) - Control panel for Linux and BSD. (<b><code>  7964⭐</code></b> <b><code>   861🍴</code></b> [Source Code](https://github.com/ajenti/ajenti) ⭐ 7,964 | 🐛 10 | 🌐 Python | 📅 2026-07-22)) `MIT` `Python/Shell`
* 🌎 [MeshCentral](meshcentral.com) - A complete web-based remote monitoring and management web site. (<b><code>  7163⭐</code></b> <b><code>   975🍴</code></b> [Source Code](https://github.com/ylianst/meshcentral) ⭐ 7,166 | 🐛 151 | 🌐 HTML | 📅 2026-09-03)) `Apache-2.0` `JavaScript/HTML`
* 🌎 [Webmin](www.webmin.com/) - Web-based interface for system administration for Unix. (<b><code>  6035⭐</code></b> <b><code>   796🍴</code></b> [Source Code](https://github.com/webmin/webmin) ⭐ 6,037 | 🐛 123 | 🌐 HTML | 📅 2026-09-05)) `BSD-3-Clause` `Perl`
* 🌎 [HestiaCP](hestiacp.com/) - Web server control panel (fork of VestaCP).  🌎 [Demo](demo.hestiacp.com:8083/login/), <b><code>  4489⭐</code></b> <b><code>   932🍴</code></b> [Source Code](https://github.com/hestiacp/hestiacp) ⭐ 4,490 | 🐛 141 | 🌐 Shell | 📅 2026-09-05)) `GPL-3.0` `PHP/Shell/Other`
* 🌎 [Froxlor](froxlor.org/) - Lightweight server management software with Nginx and PHP-FPM support. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/Froxlor/Froxlor/) ⭐ 1,749 | 🐛 42 | 🌐 PHP | 📅 2026-09-04)) `GPL-2.0` `PHP`
* 🌎 [ISPConfig](www.ispconfig.org) - Manage Linux servers directly through your browser.  🌎 [Source Code](git.ispconfig.org/ispconfig/ispconfig3)) `BSD-3-Clause` `PHP`
* 🌎 [Virtualmin](www.virtualmin.com/) - Powerful and flexible web hosting control panel for Linux and BSD systems. ([Source Code](https://github.com/virtualmin)) `GPL-3.0` `Shell/Perl/Other`

### Databases

**[`^        back to top        ^`](#awesome-sysadmin)**

Database servers.

**Please visit 🌎 [dbdb.io - Database of Databases](dbdb.io/)**

*See also: 🌎 [awesome-selfhosted/Database Management](awesome-selfhosted.net/tags/database-management.html)*

### Deployment Automation

**[`^        back to top        ^`](#awesome-sysadmin)**

Tools and scripts to support deployments to your servers.

* 🌎 [Fabric](www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks. (<b><code> 15495⭐</code></b> <b><code>  1954🍴</code></b> [Source Code](https://github.com/fabric/fabric) ⭐ 15,495 | 🐛 507 | 🌐 Python | 📅 2026-04-10)) `BSD-2-Clause` `Python`
* 🌎 [Capistrano](capistranorb.com/) - Deploy your application to any number of machines simultaneously, in sequence or as a rolling set via SSH (rake based). (<b><code> 12992⭐</code></b> <b><code>  1740🍴</code></b> [Source Code](https://github.com/capistrano/capistrano) ⭐ 12,992 | 🐛 74 | 🌐 Ruby | 📅 2026-07-19)) `MIT` `Ruby`
* 🌎 [munki](www.munki.org/munki/) - Webserver-based repository of packages and package metadata, that allows macOS administrators to manage software installs. (<b><code>  3464⭐</code></b> <b><code>   372🍴</code></b> [Source Code](https://github.com/munki/munki) ⭐ 3,466 | 🐛 68 | 🌐 Swift | 📅 2026-09-04)) `Apache-2.0` `Python`
* 🌎 [CloudStack](cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services. (<b><code>  3042⭐</code></b> <b><code>  1375🍴</code></b> [Source Code](https://github.com/apache/cloudstack) ⭐ 3,042 | 🐛 1,011 | 🌐 Java | 📅 2026-09-04)) `Apache-2.0` `Java/Python`
* 🌎 [Cobbler](cobbler.github.io/) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments. (<b><code>  2771⭐</code></b> <b><code>   659🍴</code></b> [Source Code](https://github.com/cobbler/cobbler) ⭐ 2,772 | 🐛 308 | 🌐 Python | 📅 2026-09-02)) `GPL-2.0` `Python`
* 🌎 [Overcast](andrewchilds.github.io/overcast/) - Deploy VMs across different cloud providers, and run commands and scripts across any or all of them in parallel via SSH. (<b><code>   483⭐</code></b> <b><code>    36🍴</code></b> [Source Code](https://github.com/andrewchilds/overcast) ⭐ 483 | 🐛 9 | 🌐 JavaScript | 📅 2026-05-20)) `MIT` `Nodejs`
* 🌎 [FaynoSync](faynosync.com) - Self-hosted Dynamic Update Server with statistics, supporting multiple updaters. Flexible features for seamless app updates and insights. (<b><code>   154⭐</code></b> <b><code>     4🍴</code></b> [Source Code](https://github.com/ku9nov/faynoSync) ⭐ 154 | 🐛 1 | 🌐 Go | 📅 2026-09-02), <b><code>     5⭐</code></b> <b><code>     1🍴</code></b> [Clients](https://github.com/ku9nov/faynoSync-dashboard) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-04)) `Apache-2.0` `Docker/Go`
* 🌎 [CloudSlang](www.cloudslang.io/) - Flow-based orchestration tool for managing deployed applications, with Docker capabilities. (<b><code>    95⭐</code></b> <b><code>    45🍴</code></b> [Source Code](https://github.com/CloudSlang/score) ⭐ 95 | 🐛 18 | 🌐 Java | 📅 2026-08-25)) `Apache-2.0` `Java`
* <b><code>    64⭐</code></b> <b><code>    30🍴</code></b> [Genesis](https://github.com/genesis-community/genesis) ⭐ 64 | 🐛 52 | 🌐 Perl | 📅 2026-08-25) - A template framework for multi-environment BOSH deployments. `MIT` `Perl`

### Diagramming

**[`^        back to top        ^`](#awesome-sysadmin)**

Tools used to create diagrams of networks, flows, etc.

* 🌎 [Diagrams.net](app.diagrams.net/) - A.K.A. 🌎 [Draw.io](app.diagrams.net/). Easy to use Diagram UI with a plethora of templates. (<b><code>  7915⭐</code></b> <b><code>  1215🍴</code></b> [Source Code](https://github.com/jgraph/drawio) ⭐ 7,927 | 🐛 101 | 🌐 JavaScript | 📅 2026-09-01)) `Apache-2.0` `JavaScript/Docker`
* 🌎 [Mermaid](mermaid-js.github.io/mermaid-live-editor/) - Javascript module with a unique, easy, shorthand syntax. Integrates into several other tools like Grafana. (<b><code>  6797⭐</code></b> <b><code>  1165🍴</code></b> [Source Code](https://github.com/mermaid-js/mermaid-live-editor) ⭐ 6,798 | 🐛 94 | 🌐 TypeScript | 📅 2026-09-05)) `MIT` `Nodejs/Docker`
* 🌎 [Kroki](kroki.io) - API for generating diagrams from textual descriptions. (<b><code>  4309⭐</code></b> <b><code>   312🍴</code></b> [Source Code](https://github.com/yuzutech/kroki) ⭐ 4,310 | 🐛 139 | 🌐 JavaScript | 📅 2026-08-23)) `MIT` `Java`

### Distributed Filesystems

**[`^        back to top        ^`](#awesome-sysadmin)**

Network distributed filesystems.

*See also: 🌎 [awesome-selfhosted/File Transfer - Object Storage & File Servers](awesome-selfhosted.net/tags/file-transfer---object-storage--file-servers.html)*

* <b><code> 17122⭐</code></b> <b><code>  3167🍴</code></b> [Kubo](https://github.com/ipfs/kubo) ⭐ 17,124 | 🐛 871 | 🌐 Go | 📅 2026-09-04) - Implementation of IPFS, a global, versioned, peer-to-peer filesystem that seeks to connect all computing devices with the same system of files. `Apache-2.0/MIT` `Go`
* 🌎 [Ceph](ceph.com/en/) - Distributed object, block, and file storage platform. (<b><code> 17002⭐</code></b> <b><code>  6504🍴</code></b> [Source Code](https://github.com/ceph/ceph) ⭐ 17,005 | 🐛 1,312 | 🌐 C++ | 📅 2026-09-05)) `LGPL-3.0` `C++`
* 🌎 [Hadoop Distributed Filesystem (HDFS)](hadoop.apache.org/) - Distributed file system that provides high-throughput access to application data. (<b><code> 15648⭐</code></b> <b><code>  9244🍴</code></b> [Source Code](https://github.com/apache/hadoop) ⭐ 15,650 | 🐛 213 | 🌐 Java | 📅 2026-09-04)) `Apache-2.0` `Java`
* 🌎 [JuiceFS](juicefs.com/) - Distributed POSIX file system built on top of Redis and S3. (<b><code> 14395⭐</code></b> <b><code>  1282🍴</code></b> [Source Code](https://github.com/juicedata/juicefs) ⭐ 14,395 | 🐛 216 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Perkeep](perkeep.org/) - A set of open source formats, protocols, and software for modeling, storing, searching, sharing and synchronizing data (previously Camlistore). (<b><code>  7238⭐</code></b> <b><code>   487🍴</code></b> [Source Code](https://github.com/perkeep/perkeep) ⭐ 7,238 | 🐛 413 | 🌐 Go | 📅 2026-02-01)) `Apache-2.0` `C`
* 🌎 [GlusterFS](www.gluster.org/) - Software-defined distributed storage that can scale to several petabytes, with interfaces for object, block and file storage. (<b><code>  5228⭐</code></b> <b><code>  1108🍴</code></b> [Source Code](https://github.com/gluster/glusterfs) ⭐ 5,229 | 🐛 290 | 🌐 C | 📅 2026-08-31)) `GPL-2.0/LGPL-3.0` `C`
* 🌎 [MooseFS](moosefs.com/) - Fault tolerant, network distributed file system. (<b><code>  2002⭐</code></b> <b><code>   239🍴</code></b> [Source Code](https://github.com/moosefs/moosefs) ⭐ 2,002 | 🐛 191 | 🌐 C | 📅 2026-05-18)) `GPL-2.0` `C`
* 🌎 [TahoeLAFS](tahoe-lafs.org/trac/tahoe-lafs) - Secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system. (<b><code>  1441⭐</code></b> <b><code>   261🍴</code></b> [Source Code](https://github.com/tahoe-lafs/tahoe-lafs) ⭐ 1,441 | 🐛 24 | 🌐 Python | 📅 2026-01-21)) `GPL-2.0` `Python`
* 🌎 [DRBD](linbit.com/drbd/) - Distributed replicated storage system, implemented as a Linux kernel driver. (<b><code>   721⭐</code></b> <b><code>   115🍴</code></b> [Source Code](https://github.com/LINBIT/drbd) ⭐ 722 | 🐛 38 | 🌐 C | 📅 2026-09-04)) `GPL-2.0` `C`
* 🌎 [XtreemFS](www.xtreemfs.org/) - Distributed, replicated and fault-tolerant file system for federated IT infrastructures.. (<b><code>   348⭐</code></b> <b><code>    65🍴</code></b> [Source Code](https://github.com/xtreemfs/xtreemfs) ⭐ 348 | 🐛 69 | 🌐 Java | 📅 2024-10-07)) `BSD-3-Clause` `Java`
* 🌎 [Lustre](www.lustre.org/) - Parallel distributed file system, generally used for large-scale cluster computing.  🌎 [Source Code](git.whamcloud.com/?p=fs/lustre-release.git;a=summary)) `GPL-2.0` `C`
* 🌎 [OpenAFS](www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.  🌎 [Source Code](git.openafs.org/?p=openafs.git;a=summary)) `IPL-1.0` `C`
* 🌎 [Openstack Swift](docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.  🌎 [Source Code](opendev.org/openstack/swift)) `Apache-2.0` `Python`

### DNS - Control Panels & Domain Management

**[`^        back to top        ^`](#awesome-sysadmin)**

DNS server control panels, web interfaces and domain management tools.

*Related: [DNS - Servers](#dns---servers)*

*See also: 🌎 [awesome-selfhosted/DNS](awesome-selfhosted.net/tags/dns.html)*

* 🌎 [DNSControl](dnscontrol.org/) - Synchronize your DNS to multiple providers from a simple DSL. (<b><code>  3929⭐</code></b> <b><code>   531🍴</code></b> [Source Code](https://github.com/DNSControl/dnscontrol) ⭐ 3,930 | 🐛 39 | 🌐 Go | 📅 2026-09-04)) `MIT` `Go/Docker`
* <b><code>  3753⭐</code></b> <b><code>   442🍴</code></b> [octoDNS](https://github.com/octodns/octodns) ⭐ 3,753 | 🐛 5 | 🌐 Python | 📅 2026-08-28) - DNS as code - Tools for managing DNS across multiple providers. `MIT` `Python`
* 🌎 [nsupdate.info](www.nsupdate.info/) - Dynamic DNS service.  🌎 [Demo](www.nsupdate.info/account/register/), <b><code>  1133⭐</code></b> <b><code>   125🍴</code></b> [Source Code](https://github.com/nsupdate-info/nsupdate.info) ⭐ 1,134 | 🐛 56 | 🌐 Python | 📅 2026-08-17)) `BSD-3-Clause` `Python`
* 🌎 [Poweradmin](www.poweradmin.org/) - Web-based DNS control panel for PowerDNS server. (<b><code>   910⭐</code></b> <b><code>   297🍴</code></b> [Source Code](https://github.com/poweradmin/poweradmin) ⭐ 910 | 🐛 100 | 🌐 PHP | 📅 2026-09-04)) `GPL-3.0` `PHP`
* 🌎 [DomainMOD](domainmod.org) - Manage your domains and other internet assets in a central location. (<b><code>   596⭐</code></b> <b><code>   118🍴</code></b> [Source Code](https://github.com/domainmod/domainmod) ⭐ 597 | 🐛 17 | 🌐 PHP | 📅 2025-01-04)) `GPL-3.0` `PHP`
* 🌎 [SPF Toolbox](spftoolbox.com) - Application to look up DNS records such as SPF, MX, Whois, and more. (<b><code>   300⭐</code></b> <b><code>    66🍴</code></b> [Source Code](https://github.com/charlesabarnes/SPFtoolbox) ⭐ 300 | 🐛 10 | 🌐 PHP | 📅 2026-02-13)) `MIT` `PHP`
* 🌎 [Designate](wiki.openstack.org/wiki/Designate) - DNSaaS services for OpenStack.  🌎 [Source Code](opendev.org/openstack/designate)) `Apache-2.0` `Python`

### DNS - Servers

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [DNS](en.wikipedia.org/wiki/Name_server) servers.

*Related: [DNS - Control Panels & Domain Management](#dns---control-panels--domain-management)*

*See also: 🌎 [awesome-selfhosted/DNS](awesome-selfhosted.net/tags/dns.html)*

* 🌎 [CoreDNS](coredns.io/) - Flexible DNS server. (<b><code> 14289⭐</code></b> <b><code>  2522🍴</code></b> [Source Code](https://github.com/coredns/coredns) ⭐ 14,292 | 🐛 302 | 🌐 Go | 📅 2026-09-05)) `Apache-2.0` `Go`
* 🌎 [Unbound](nlnetlabs.nl/projects/unbound/about/) - Validating, recursive, and caching DNS resolver. (<b><code>  4852⭐</code></b> <b><code>   451🍴</code></b> [Source Code](https://github.com/NLnetLabs/unbound) ⭐ 4,855 | 🐛 383 | 🌐 C | 📅 2026-09-04)) `BSD-3-Clause` `C`
* 🌎 [PowerDNS Authoritative Server](doc.powerdns.com/authoritative/) - Versatile nameserver which supports a large number of backends. (<b><code>  4458⭐</code></b> <b><code>  1023🍴</code></b> [Source Code](https://github.com/PowerDNS/pdns) ⭐ 4,458 | 🐛 931 | 🌐 C++ | 📅 2026-09-04)) `GPL-2.0` `C++`
* 🌎 [NSD](www.nlnetlabs.nl/projects/nsd/about/) - Authoritative DNS name server developed speed, reliability, stability and security. (<b><code>   569⭐</code></b> <b><code>   125🍴</code></b> [Source Code](https://github.com/NLnetLabs/nsd) ⭐ 570 | 🐛 74 | 🌐 C | 📅 2026-09-03)) `BSD-3-Clause` `C`
* 🌎 [Yadifa](www.yadifa.eu/) - Clean, small, light and RFC-compliant name server implementation developed from scratch by .eu. (<b><code>    81⭐</code></b> <b><code>    15🍴</code></b> [Source Code](https://github.com/yadifa/yadifa) ⭐ 81 | 🐛 10 | 🌐 C | 📅 2026-03-24)) `BSD-3-Clause` `C`
* 🌎 [Bind](www.isc.org/bind/) - Versatile, classic, complete name server software.  🌎 [Source Code](gitlab.isc.org/isc-projects/bind9)) `MPL-2.0` `C`
* 🌎 [djbdns](cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.  🌎 [Source Code](salsa.debian.org/debian/djbdns)) `CC0-1.0` `C`
* 🌎 [dnsmasq](www.thekelleys.org.uk/dnsmasq/doc.html) - Provides network infrastructure for small networks: DNS, DHCP, router advertisement and network boot.  🌎 [Source Code](thekelleys.org.uk/gitweb/?p=dnsmasq.git;a=tree)) `GPL-2.0` `C`
* 🌎 [Knot](www.knot-dns.cz/) - High performance authoritative-only DNS server.  🌎 [Source Code](gitlab.nic.cz/knot/knot-dns)) `GPL-3.0` `C`

### Editors

**[`^        back to top        ^`](#awesome-sysadmin)**

Open-source code editors.

* 🌎 [Vim](www.vim.org) - A highly configurable text editor built to enable efficient editing. (<b><code> 40852⭐</code></b> <b><code>  6134🍴</code></b> [Source Code](https://github.com/vim/vim) ⭐ 40,853 | 🐛 1,636 | 🌐 Vim Script | 📅 2026-09-05)) `Vim` `C`
* 🌎 [VSCodium](vscodium.com/) - An open source cross-platform extensible code editor based on 🌎 [VS Code by Microsoft](code.visualstudio.com/) removing their non-free additions. (<b><code> 33109⭐</code></b> <b><code>  1858🍴</code></b> [Source Code](https://github.com/VSCodium/vscodium) ⭐ 33,118 | 🐛 139 | 🌐 Shell | 📅 2026-09-04)) `MIT` `TypeScript`
* 🌎 [Micro](micro-editor.github.io/) - A modern and intuitive terminal-based text editor. (<b><code> 29513⭐</code></b> <b><code>  1358🍴</code></b> [Source Code](https://github.com/micro-editor/micro) ⭐ 29,518 | 🐛 973 | 🌐 Go | 📅 2026-09-05)) `MIT` `Go`
* 🌎 [Notepad++](notepad-plus-plus.org/) - GPLv2 multi-language editor with syntax highlighting for Windows. (<b><code> 29226⭐</code></b> <b><code>  5348🍴</code></b> [Source Code](https://github.com/notepad-plus-plus/notepad-plus-plus) ⭐ 29,234 | 🐛 2,930 | 🌐 C++ | 📅 2026-09-03)) `GPL-2.0` `C++`
* 🌎 [GNU Emacs](www.gnu.org/software/emacs/) - An extensible, customizable text editor-and more. (<b><code>  5186⭐</code></b> <b><code>  1400🍴</code></b> [Source Code](https://github.com/emacs-mirror/emacs) ⭐ 5,188 | 🐛 16 | 🌐 Emacs Lisp | 📅 2026-09-04)) `GPL-3.0` `C`
* 🌎 [Geany](www.geany.org/) - GTK2 text editor. (<b><code>  3704⭐</code></b> <b><code>   666🍴</code></b> [Source Code](https://github.com/geany/geany) ⭐ 3,706 | 🐛 1,275 | 🌐 C | 📅 2026-08-03)) `GPL-2.0` `C/C++`
* 🌎 [Brackets](brackets.io/) - Code editor for web designers and front-end developers. (<b><code>  1515⭐</code></b> <b><code>   195🍴</code></b> [Source Code](https://github.com/brackets-cont/brackets) ⭐ 1,515 | 🐛 78 | 🌐 JavaScript | 📅 2026-03-30)) `MIT` `JavaScript`
* <b><code>   781⭐</code></b> <b><code>    31🍴</code></b> [Atom Community](https://github.com/atom-community/atom) ⭐ 781 | 🐛 52 | 🌐 JavaScript | 📅 2025-08-19) - A fork of <b><code> 60752⭐</code></b> <b><code> 17165🍴</code></b> [atom](https://github.com/atom/atom) ⚠️ Archived) A hackable text editor from Github. `MIT` `JavaScript`
* 🌎 [Eclipse](www.eclipse.org/) - IDE written in Java with an extensible plug-in system.  🌎 [Source Code](git.eclipse.org/c/)) `EPL-1.0` `Java`
* 🌎 [KDevelop](www.kdevelop.org/) - IDE by the people behind KDE.  🌎 [Source Code](invent.kde.org/kdevelop/kdevelop)) `GFDL-1.2` `C++`
* 🌎 [Nano](nano-editor.org) - Easy to use, customizable text editor.  🌎 [Source Code](git.savannah.gnu.org/cgit/nano.git/tree/)) `GPL-3.0` `C`

### Identity Management

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Identity management](en.wikipedia.org/wiki/Identity_management) (IdM), also known as identity and access management (IAM or IdAM), is a framework of policies and technologies to ensure that the right users (that are part of the ecosystem connected to or within an enterprise) have the appropriate access to technology resources.

**Please visit [Identity Management - LDAP](#identity-management---ldap), [Identity Management - Tools and web interfaces](#identity-management---tools-and-web-interfaces), [Identity Management - Single Sign-On SSO](#identity-management---single-sign-on-sso)**

### Identity Management - LDAP

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Lightweight Directory Access Protocol (LDAP)](en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol) is an open, vendor-neutral, industry standard application protocol for accessing and maintaining distributed directory information services over an Internet Protocol (IP) network.

* <b><code>  6484⭐</code></b> <b><code>   351🍴</code></b> [lldap](https://github.com/lldap/lldap) ⭐ 6,488 | 🐛 126 | 🌐 Rust | 📅 2026-08-28) - Light (simplified) LDAP implementation with a simple, intuitive web interface and GraphQL support. `GPL-3.0` `Rust`
* 🌎 [FreeRADIUS](freeradius.org/) - Multi-protocol policy server (radiusd) that implements RADIUS, DHCP, BFD, and ARP and associated client/PAM library/Apache module. (<b><code>  2580⭐</code></b> <b><code>  1194🍴</code></b> [Source Code](https://github.com/FreeRADIUS/freeradius-server) ⭐ 2,582 | 🐛 97 | 🌐 C | 📅 2026-09-05)) `GPL-2.0` `C`
* 🌎 [LTB Self-Service Password](www.ltb-project.org/documentation/self-service-password.html) - Web interface to change and reset LDAP passwords. (<b><code>  1340⭐</code></b> <b><code>   353🍴</code></b> [Source Code](https://github.com/ltb-project/self-service-password) ⭐ 1,340 | 🐛 64 | 🌐 PHP | 📅 2026-09-03)) `GPL-3.0` `PHP`
* 🌎 [389 Directory Server](www.port389.org/) - Enterprise-class Open Source LDAP server for Linux. (<b><code>   293⭐</code></b> <b><code>   125🍴</code></b> [Source Code](https://github.com/389ds/389-ds-base) ⭐ 293 | 🐛 410 | 🌐 C | 📅 2026-09-04)) `GPL-3.0` `C`
* 🌎 [Apache Directory Server](directory.apache.org/apacheds/) - Extensible and embeddable directory server, certified LDAPv3 compatible, with Kerberos 5 and Change Password Protocol support, triggers, stored procedures, queues and views. (<b><code>   188⭐</code></b> <b><code>   102🍴</code></b> [Source Code](https://github.com/apache/directory-server) ⭐ 188 | 🐛 16 | 🌐 Java | 📅 2026-08-24)) `Apache-2.0` `Java`
* 🌎 [Wren:DS](wrensecurity.org/projects/wrends/) - LDAPv3-compliant directory service providing a high-performance, highly available, and secure identity data store for enterprise environments. (<b><code>    45⭐</code></b> <b><code>    19🍴</code></b> [Source Code](https://github.com/WrenSecurity/wrends) ⭐ 45 | 🐛 25 | 🌐 Java | 📅 2026-09-01)) `CDDL-1.0` `Java`
* 🌎 [FreeIPA](www.freeipa.org/) - Integrated security information management solution combining Linux (Fedora), 389 Directory Server, Kerberos, NTP, DNS, and Dogtag Certificate System (web interface and command-line administration tools).  🌎 [Source Code](pagure.io/freeipa)) `GPL-3.0` `Python/C/JavaScript`
* 🌎 [OpenLDAP](www.openldap.org/) - Open-source implementation of the Lightweight Directory Access Protocol (server, libraries and clients).  🌎 [Source Code](git.openldap.org/openldap/openldap)) `OLDAP-2.8` `C`

### Identity Management - Single Sign-On (SSO)

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Single sign-on (SSO)](en.wikipedia.org/wiki/Single_sign-on) is an authentication scheme that allows a user to log in with a single ID to any of several related, yet independent, software systems.

* 🌎 [KeyCloak](www.keycloak.org) - Open Source Identity and Access Management. (<b><code> 36599⭐</code></b> <b><code>  8894🍴</code></b> [Source Code](https://github.com/keycloak/keycloak) ⭐ 36,606 | 🐛 3,239 | 🌐 Java | 📅 2026-09-05)) `Apache-2.0` `Java`
* 🌎 [Authelia](www.authelia.com/) - The Single Sign-On Multi-Factor portal for web apps. (<b><code> 28791⭐</code></b> <b><code>  1477🍴</code></b> [Source Code](https://github.com/authelia/authelia) ⭐ 28,800 | 🐛 130 | 🌐 Go | 📅 2026-09-05)) `Apache-2.0` `Go`
* 🌎 [Authentik](goauthentik.io/) - Flexible identity provider with support for different protocols. (OAuth 2.0, SAML, LDAP and Radius). (<b><code> 25346⭐</code></b> <b><code>  1988🍴</code></b> [Source Code](https://github.com/goauthentik/authentik) ⭐ 25,363 | 🐛 1,089 | 🌐 Python | 📅 2026-09-05)) `MIT` `Python`
* 🌎 [Wren:AM](wrensecurity.org/projects/wrenam/) - Access management platform providing adaptive authentication, SSO, federation, and fine-grained authorization for web and API resources. (<b><code>    55⭐</code></b> <b><code>    32🍴</code></b> [Source Code](https://github.com/WrenSecurity/wrenam) ⭐ 55 | 🐛 69 | 🌐 Java | 📅 2026-09-04)) `CDDL-1.0` `Java`
* 🌎 [Wren:IG](wrensecurity.org/projects/wrenig/) - Identity gateway and reverse proxy enforcing authentication, authorization, and SSO without requiring application changes. (<b><code>     7⭐</code></b> <b><code>    31🍴</code></b> [Source Code](https://github.com/WrenSecurity/wrenig) ⭐ 7 | 🐛 2 | 🌐 Java | 📅 2026-09-04)) `CDDL-1.0` `Java`

### Identity Management - Tools and web interfaces

**[`^        back to top        ^`](#awesome-sysadmin)**

Miscellaneous utilities and web interfaces for identity management systems.

* 🌎 [ZITADEL](zitadel.com/) - Cloud-native Identity & Access Management solution providing a platform for secure authentication, authorization and identity management. (<b><code> 14936⭐</code></b> <b><code>  1270🍴</code></b> [Source Code](https://github.com/zitadel/zitadel) ⭐ 14,945 | 🐛 1,154 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go/Docker/K8S`
* 🌎 [Smallstep Certificates](smallstep.com/certificates/) - A private certificate authority (X.509 & SSH) and related tools for secure automated certificate management. (<b><code>  8823⭐</code></b> <b><code>   588🍴</code></b> [Source Code](https://github.com/smallstep/certificates) ⭐ 8,831 | 🐛 291 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Pomerium](www.pomerium.io/) - An identity and context aware access-proxy inspired by BeyondCorp. (<b><code>  4988⭐</code></b> <b><code>   352🍴</code></b> [Source Code](https://github.com/pomerium/pomerium) ⭐ 4,993 | 🐛 151 | 🌐 Go | 📅 2026-09-05)) `Apache-2.0` `Docker/Go`
* <b><code>  4477⭐</code></b> <b><code>  1230🍴</code></b> [easy-rsa](https://github.com/OpenVPN/easy-rsa) ⭐ 4,476 | 🐛 21 | 🌐 Shell | 📅 2026-07-25) - Bash script to build and manage a PKI CA. `GPL-2.0` `Shell`
* 🌎 [LDAP Account Manager (LAM)](www.ldap-account-manager.org/lamcms/) - Web frontend for managing entries (e.g. users, groups, DHCP settings) stored in an LDAP directory. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/LDAPAccountManager/lam/) ⭐ 488 | 🐛 18 | 🌐 PHP | 📅 2026-09-05)) `GPL-3.0` `PHP`
* 🌎 [Fusion Directory](www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP. (<b><code>   190⭐</code></b> <b><code>    37🍴</code></b> [Source Code](https://github.com/fusiondirectory/fusiondirectory) ⭐ 190 | 🐛 1 | 🌐 PHP | 📅 2026-09-04)) `GPL-2.0` `PHP`
* 🌎 [Wren:IDM](wrensecurity.org/projects/wrenidm/) - Identity management and governance platform for lifecycle management, access governance, and comprehensive auditability. (<b><code>    48⭐</code></b> <b><code>    21🍴</code></b> [Source Code](https://github.com/WrenSecurity/wrenidm) ⭐ 48 | 🐛 31 | 🌐 Java | 📅 2026-09-04)) `CDDL-1.0` `Java`
* 🌎 [BounCA](bounca.org/) - A personal SSL Key / Certificate Authority web-based tool for creating self-signed certificates.  🌎 [Source Code](gitlab.com/bounca/bounca/)) `Apache-2.0` `Python`
* 🌎 [Libravatar](www.libravatar.org/) - Libravatar is a service which delivers your avatar (profile picture) to other websites.  🌎 [Source Code](git.linux-kernel.at/oliver/ivatar/)) `AGPL-3.0` `Python`
* 🌎 [Samba](www.samba.org/) - Active Directory and CIFS protocol implementation.  🌎 [Source Code](download.samba.org/pub/samba/)) `GPL-3.0` `C`

### IT Asset Management

**[`^        back to top        ^`](#awesome-sysadmin)**

IT 🌎 [asset management](en.wikipedia.org/wiki/Asset_management) software.

* 🌎 [Snipe IT](snipeitapp.com/) - Asset & license management software. (<b><code> 14903⭐</code></b> <b><code>  3983🍴</code></b> [Source Code](https://github.com/grokability/snipe-it) ⭐ 14,907 | 🐛 929 | 🌐 PHP | 📅 2026-09-02)) `AGPL-3.0` `PHP`
* 🌎 [GLPI](www.glpi-project.org/) - Information Resource-Manager with an additional Administration Interface. (<b><code>  6308⭐</code></b> <b><code>  1799🍴</code></b> [Source Code](https://github.com/glpi-project/glpi) ⭐ 6,313 | 🐛 438 | 🌐 PHP | 📅 2026-09-04)) `GPL-3.0` `PHP`
* 🌎 [Ralph](ralph.allegro.tech/) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks. (<b><code>  2517⭐</code></b> <b><code>   594🍴</code></b> [Demo](https://github.com/allegro/ralph#live-demo) ⭐ 2,517 | 🐛 123 | 🌐 Python | 📅 2026-09-02), <b><code>  2517⭐</code></b> <b><code>   594🍴</code></b> [Source Code](https://github.com/allegro/ralph) ⭐ 2,517 | 🐛 123 | 🌐 Python | 📅 2026-09-02)) `Apache-2.0` `Python/Docker`
* 🌎 [RackTables](racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration.  🌎 [Demo](www.racktables.org/demo.php), <b><code>   810⭐</code></b> <b><code>   271🍴</code></b> [Source Code](https://github.com/RackTables/racktables) ⭐ 810 | 🐛 23 | 🌐 PHP | 📅 2026-06-26)) `GPL-2.0` `PHP`
* 🌎 [openDCIM](opendcim.org/) - GPL v3 Data Center Inventory Management (DCIM).  🌎 [Demo](opendcim.org/demo.html), <b><code>   364⭐</code></b> <b><code>   220🍴</code></b> [Source Code](https://github.com/opendcim/openDCIM) ⭐ 364 | 🐛 128 | 🌐 PHP | 📅 2026-08-14)) `GPL-3.0` `PHP/JavaScript`
* 🌎 [OCS Inventory NG](ocsinventory-ng.org/) - Asset management and deployment solution for all devices in your IT Department. ([Source Code](https://github.com/OCSInventory-NG)) `GPL-2.0` `PHP/Perl`
* 🌎 [OPSI](www.opsi.org) - Hardware and software inventory, client management, deployment, and patching for Linux and Windows. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/opsi-org/))) `GPL-3.0/AGPL-3.0` `OVF/Python`

### Log Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Log management tools: collect, parse, visualize...

* 🌎 [Loki](grafana.com/oss/loki/) - Log aggregation system designed to store and query logs from all your applications and infrastructure. (<b><code> 28836⭐</code></b> <b><code>  4100🍴</code></b> [Source Code](https://github.com/grafana/loki) ⭐ 28,838 | 🐛 1,741 | 🌐 Go | 📅 2026-09-05)) `AGPL-3.0` `Go`
* 🌎 [GoAccess](goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal or through the browser. (<b><code> 20902⭐</code></b> <b><code>  1191🍴</code></b> [Source Code](https://github.com/allinurl/goaccess) ⭐ 20,905 | 🐛 449 | 🌐 C | 📅 2026-09-03)) `MIT` `C`
* 🌎 [Fluentd](www.fluentd.org/) - Data collector for unified logging layer. (<b><code> 13581⭐</code></b> <b><code>  1406🍴</code></b> [Source Code](https://github.com/fluent/fluentd) ⭐ 13,581 | 🐛 134 | 🌐 Ruby | 📅 2026-09-02)) `Apache-2.0` `Ruby`
* 🌎 [Flume](flume.apache.org/) - Distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data. (<b><code>  2570⭐</code></b> <b><code>  1540🍴</code></b> [Source Code](https://github.com/apache/logging-flume) ⭐ 2,570 | 🐛 82 | 🌐 Java | 📅 2026-09-02)) `Apache-2.0` `Java`
* 🌎 [rsyslog](www.rsyslog.com/) - Rocket-fast system for log processing. (<b><code>  2334⭐</code></b> <b><code>   734🍴</code></b> [Source Code](https://github.com/rsyslog/rsyslog) ⭐ 2,335 | 🐛 194 | 🌐 C | 📅 2026-09-02)) `GPL-3.0` `C`
* 🌎 [reaction](reaction.ppom.me/) - A lightweight daemon that scans program outputs for repeated patterns, and takes action.  🌎 [Source Code](framagit.org/ppom/reaction)) `AGPL-3.0` `Rust`

### Mail Clients

**[`^        back to top        ^`](#awesome-sysadmin)**

An 🌎 [email client](en.wikipedia.org/wiki/Email_client), email reader or, more formally, message user agent (MUA) or mail user agent is a computer program used to access and manage a user's email.

* [ImapSync](http://imapsync.lamiral.info/) - Simple IMAP migration tool for copying mailboxes to other servers. (<b><code>  4145⭐</code></b> <b><code>   530🍴</code></b> [Source Code](https://github.com/imapsync/imapsync) ⭐ 4,145 | 🐛 194 | 🌐 Shell | 📅 2026-07-23)) `NLPL` `Perl`
* 🌎 [Sylpheed](sylpheed.sraoss.jp/en/) - Still developed predecessor to Claws Mail, lightweight mail client. (<b><code>   188⭐</code></b> <b><code>    22🍴</code></b> [Source Code](https://github.com/sylpheed-mail/sylpheed) ⭐ 188 | 🐛 67 | 🌐 C | 📅 2024-05-04)) `GPL-2.0` `C`
* 🌎 [aerc](aerc-mail.org/) - Terminal MUA with a focus on plaintext and features for developers.  🌎 [Source Code](git.sr.ht/~rjarry/aerc)) `MIT` `Go`
* [Claws Mail](http://www.claws-mail.org/) - Old school email client (and news reader), based on GTK+.  🌎 [Source Code](git.claws-mail.org/?p=claws.git;a=tree)) `GPL-3.0` `C`
* [Mutt](http://www.mutt.org/) - Small but very powerful text-based mail client.  🌎 [Source Code](gitlab.com/muttmua/mutt)) `GPL-2.0` `C`
* 🌎 [Thunderbird](www.thunderbird.net/) - Free email application that's easy to set up and customize.  🌎 [Source Code](hg.mozilla.org/comm-central/file)) `MPL-2.0` `C/C++`

### Metrics & Metric Collection

**[`^        back to top        ^`](#awesome-sysadmin)**

Metric gathering and display software.

*Related: [Databases](#databases), [Monitoring & Status Pages](#monitoring--status-pages)*

* 🌎 [Grafana](grafana.com/) - A Graphite & InfluxDB Dashboard and Graph Editor. (<b><code> 76575⭐</code></b> <b><code> 14700🍴</code></b> [Source Code](https://github.com/grafana/grafana) ⭐ 76,589 | 🐛 3,359 | 🌐 TypeScript | 📅 2026-09-05)) `AGPL-3.0` `Go`
* <b><code> 18078⭐</code></b> <b><code>  1937🍴</code></b> [Statsd](https://github.com/statsd/statsd) ⭐ 18,078 | 🐛 90 | 🌐 JavaScript | 📅 2025-05-20) - Daemon that listens for statistics like counters and timers, sent over UDP or TCP, and sends aggregates to one or more pluggable backend services. `MIT` `Nodejs`
* <b><code> 17792⭐</code></b> <b><code>  5838🍴</code></b> [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,796 | 🐛 413 | 🌐 Go | 📅 2026-09-04) - Plugin-driven server agent for collecting, processing, aggregating, and writing metrics. `MIT` `Go`
* 🌎 [VictoriaMetrics](victoriametrics.com/) - Fast, cost-effective time series database and monitoring solution; drop-in replacement for Prometheus with PromQL/MetricsQL support. (<b><code> 17649⭐</code></b> <b><code>  1730🍴</code></b> [Source Code](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 17,658 | 🐛 782 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Beats](www.elastic.co/beats/) - Single-purpose data shippers that send data from hundreds or thousands of machines and systems to Logstash or Elasticsearch. (<b><code> 12643⭐</code></b> <b><code>  5001🍴</code></b> [Source Code](https://github.com/elastic/beats) ⭐ 12,643 | 🐛 1,041 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Graphite](graphite.readthedocs.org/en/latest/) - Scalable graphing server. (<b><code>  6116⭐</code></b> <b><code>  1254🍴</code></b> [Source Code](https://github.com/graphite-project/graphite-web) ⭐ 6,116 | 🐛 24 | 🌐 JavaScript | 📅 2026-08-10)) `Apache-2.0` `Python`
* 🌎 [Collectd](collectd.org/) - System statistics collection daemon. (<b><code>  3363⭐</code></b> <b><code>  1251🍴</code></b> [Source Code](https://github.com/collectd/collectd) ⭐ 3,363 | 🐛 786 | 🌐 C | 📅 2026-05-29)) `MIT` `C`
* 🌎 [RRDtool](oss.oetiker.ch/rrdtool/) - Industry standard, high performance data logging and graphing system for time series data. (<b><code>  1113⭐</code></b> <b><code>   284🍴</code></b> [Source Code](https://github.com/oetiker/rrdtool-1.x) ⭐ 1,113 | 🐛 163 | 🌐 C | 📅 2026-08-07)) `GPL-2.0` `C`
* [tcollector](http://opentsdb.net/docs/build/html/user_guide/utilities/tcollector.html) - Gathers data from local collectors and pushes the data to OpenTSDB. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/OpenTSDB/tcollector/) ⭐ 509 | 🐛 25 | 🌐 Python | 📅 2024-06-10)) `LGPL-3.0/GPL-3.0` `Python`

### Miscellaneous

**[`^        back to top        ^`](#awesome-sysadmin)**

Software that does not fit in another section.

* 🌎 [Chocolatey](chocolatey.org/) - The package manager for Windows. (<b><code> 11499⭐</code></b> <b><code>   961🍴</code></b> [Source Code](https://github.com/chocolatey/choco) ⭐ 11,501 | 🐛 519 | 🌐 C# | 📅 2026-08-19)) `Apache-2.0` `C#/PowerShell`
* 🌎 [Fog](www.fogproject.org/) - Cloning/imaging solution/rescue suite. (<b><code>  1652⭐</code></b> <b><code>   283🍴</code></b> [Source Code](https://github.com/FOGProject/fogproject) ⭐ 1,653 | 🐛 16 | 🌐 PHP | 📅 2026-09-05)) `GPL-3.0` `PHP/Shell`
* 🌎 [phpList](www.phplist.org/) - Newsletter and email marketing software. (<b><code>   870⭐</code></b> <b><code>   289🍴</code></b> [Source Code](https://github.com/phpList/phplist3) ⭐ 870 | 🐛 93 | 🌐 PHP | 📅 2026-08-16)) `AGPL-3.0` `PHP`
* 🌎 [Clonezilla](clonezilla.org/) - Partition and disk imaging/cloning program.  🌎 [Source Code](clonezilla.org/downloads/src/)) `GPL-2.0` `Perl/Shell/Other`
* 🌎 [DadaMail](dadamailproject.com/) - Mailing List Manager, written in Perl.  🌎 [Source Code](sourceforge.net/projects/dadamail/files/)) `GPL-2.0` `Perl`

### Monitoring & Status Pages

**[`^        back to top        ^`](#awesome-sysadmin)**

Monitoring software.

*Related: [Metrics & Metric Collection](#metrics--metric-collection)*

* 🌎 [Uptime Kuma](uptime.kuma.pet/) - Modern, self-hosted monitoring tool with a clean UI and rich notification support. (<b><code> 90952⭐</code></b> <b><code>  8339🍴</code></b> [Source Code](https://github.com/louislam/uptime-kuma) ⭐ 90,988 | 🐛 797 | 🌐 JavaScript | 📅 2026-09-05)) `MIT` `Nodejs`
* 🌎 [Prometheus](prometheus.io/) - Service monitoring system and time series database. (<b><code> 65941⭐</code></b> <b><code> 10817🍴</code></b> [Source Code](https://github.com/prometheus/prometheus) ⭐ 65,948 | 🐛 896 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [glances](nicolargo.github.io/glances/) - Open-source, cross-platform real-time monitoring tool with CLI and web dashboard interfaces and many exporting options. (<b><code> 33522⭐</code></b> <b><code>  1802🍴</code></b> [Source Code](https://github.com/nicolargo/glances) ⭐ 33,527 | 🐛 103 | 🌐 Python | 📅 2026-08-30)) `GPL-3.0` `Python`
* 🌎 [Beszel](beszel.dev/) - Lightweight server monitoring platform that includes Docker statistics, historical data, and alert functions. (<b><code> 25047⭐</code></b> <b><code>   988🍴</code></b> [Source Code](https://github.com/henrygd/beszel) ⭐ 25,079 | 🐛 302 | 🌐 Go | 📅 2026-09-03)) `MIT` `Go`
* <b><code> 19397⭐</code></b> <b><code>  2490🍴</code></b> [cadvisor](https://github.com/google/cadvisor) ⭐ 19,404 | 🐛 62 | 🌐 Go | 📅 2026-09-02) - Analyzes resource usage and performance characteristics of running containers. `Apache-2.0` `Go`
* 🌎 [Wazuh](wazuh.com/) - Unified XDR and SIEM protection for endpoints and cloud workloads. (<b><code> 16765⭐</code></b> <b><code>  2470🍴</code></b> [Source Code](https://github.com/wazuh/wazuh) ⭐ 16,770 | 🐛 3,055 | 🌐 C++ | 📅 2026-09-05)) `GPL-2.0` `C`
* 🌎 [Gatus](gatus.io) - Automated service health dashboard.  🌎 [Demo](status.twin.sh), <b><code> 11981⭐</code></b> <b><code>   819🍴</code></b> [Source Code](https://github.com/TwiN/gatus) ⭐ 11,993 | 🐛 382 | 🌐 Go | 📅 2026-08-27)) `Apache-2.0` `Docker/K8S`
* 🌎 [Healthchecks](healthchecks.io/docs/self_hosted/) - Monitoring for cron jobs, background services and scheduled tasks. (<b><code> 10303⭐</code></b> <b><code>  1005🍴</code></b> [Source Code](https://github.com/healthchecks/healthchecks) ⭐ 10,304 | 🐛 53 | 🌐 Python | 📅 2026-09-02)) `BSD-3-Clause` `Python`
* 🌎 [Nezha](nezha.wiki/en_US/) - Lightweight, servers & websites monitoring and O\&M tool. (<b><code> 10299⭐</code></b> <b><code>  1609🍴</code></b> [Source Code](https://github.com/nezhahq/nezha) ⭐ 10,301 | 🐛 56 | 🌐 Go | 📅 2026-09-02)) `Apache-2.0` `Go/Shell`
* 🌎 [htop](htop.dev/) - Interactive process viewer and system monitor for Unix systems. (<b><code>  8306⭐</code></b> <b><code>   632🍴</code></b> [Source Code](https://github.com/htop-dev/htop) ⭐ 8,309 | 🐛 361 | 🌐 C | 📅 2026-08-30)) `GPL-2.0` `C`
* <b><code>  8180⭐</code></b> <b><code>   297🍴</code></b> [Scrutiny](https://github.com/AnalogJ/scrutiny) ⭐ 8,182 | 🐛 39 | 🌐 Go | 📅 2026-09-02) - Web UI for hard drive S.M.A.R.T monitoring, historical trends & real-world failure thresholds. `MIT` `Go`
* 🌎 [OneUptime](oneuptime.com) - A comprehensive solution for monitoring and managing your online services. (<b><code>  7558⭐</code></b> <b><code>   448🍴</code></b> [Source Code](https://github.com/oneuptime/oneuptime) ⭐ 7,560 | 🐛 293 | 🌐 TypeScript | 📅 2026-09-05)) `Apache-2.0` `Docker`
* 🌎 [Kener](kener.ing/) - Status page with incident management, easy to use and customize. (<b><code>  5142⭐</code></b> <b><code>   297🍴</code></b> [Source Code](https://github.com/rajnandan1/kener) ⭐ 5,146 | 🐛 68 | 🌐 TypeScript | 📅 2026-09-04)) `MIT` `Nodejs/Docker`
* 🌎 [LibreNMS](www.librenms.org) - Fully featured network monitoring system that provides a wealth of features and device support. (<b><code>  4873⭐</code></b> <b><code>  2785🍴</code></b> [Source Code](https://github.com/librenms/librenms) ⭐ 4,874 | 🐛 228 | 🌐 PHP | 📅 2026-09-04)) `GPL-3.0` `PHP`
* 🌎 [Riemann](riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis. (<b><code>  4268⭐</code></b> <b><code>   503🍴</code></b> [Source Code](https://github.com/riemann/riemann) ⭐ 4,268 | 🐛 29 | 🌐 Clojure | 📅 2026-04-05)) `EPL-1.0` `Java`
* <b><code>  3532⭐</code></b> <b><code>   135🍴</code></b> [dashdot](https://github.com/MauriceNino/dashdot) ⭐ 3,532 | 🐛 60 | 🌐 TypeScript | 📅 2026-09-03) - A simple, modern server dashboard for smaller private servers.  🌎 [Demo](dash.mauz.dev/)) `MIT` `Nodejs/Docker`
* 🌎 [CheckCle](docs.checkcle.io) - Seamless, real-time monitoring of full-stack systems, applications, and infrastructure. (<b><code>  2950⭐</code></b> <b><code>   252🍴</code></b> [Source Code](https://github.com/operacle/checkcle) ⭐ 2,950 | 🐛 92 | 🌐 Go | 📅 2026-07-17)) `MIT` `Docker`
* 🌎 [cState](cstate.uncascade.com/) - Static status page for hyperfast Hugo. Clean design, minimal JS, super light HTML/CSS, high customization, optional admin panel, read-only API, IE8+.  🌎 [Demo](cstate.mnts.lt/), <b><code>  2891⭐</code></b> <b><code>   250🍴</code></b> [Source Code](https://github.com/cstate/cstate) ⭐ 2,891 | 🐛 9 | 🌐 HTML | 📅 2026-08-27)) `MIT` `HTML`
* 🌎 [Alerta](alerta.io/) - Distributed, scalable and flexible monitoring system. (<b><code>  2528⭐</code></b> <b><code>   373🍴</code></b> [Source Code](https://github.com/alerta/alerta) ⭐ 2,528 | 🐛 33 | 🌐 Python | 📅 2026-06-19)) `Apache-2.0` `Python`
* 🌎 [checkmk](checkmk.com/) - Comprehensive solution for monitoring of applications, servers, and networks. (<b><code>  2353⭐</code></b> <b><code>   555🍴</code></b> [Source Code](https://github.com/Checkmk/checkmk) ⭐ 2,353 | 🐛 54 | 🌐 Python | 📅 2026-09-04)) `GPL-2.0` `Python/PHP`
* 🌎 [Icinga](www.icinga.com/) - Nagios fork that has since lapped nagios several times. Comes with the possibility of clustered monitoring. (<b><code>  2236⭐</code></b> <b><code>   617🍴</code></b> [Source Code](https://github.com/Icinga/icinga2) ⭐ 2,236 | 🐛 496 | 🌐 C++ | 📅 2026-09-04)) `GPL-2.0` `C++`
* 🌎 [PHP Server Monitor](www.phpservermonitor.org/) - Open source tool to monitor your servers and websites. (<b><code>  2188⭐</code></b> <b><code>   685🍴</code></b> [Source Code](https://github.com/phpservermon/phpservermon) ⭐ 2,188 | 🐛 22 | 🌐 JavaScript | 📅 2025-04-23)) `GPL-3.0` `PHP`
* <b><code>  2188⭐</code></b> <b><code>   155🍴</code></b> [rtop](https://github.com/rapidloop/rtop) ⭐ 2,188 | 🐛 23 | 🌐 Go | 📅 2022-06-06) - Interactive, remote system monitoring tool based on SSH. `MIT` `Go`
* 🌎 [Munin](munin-monitoring.org/) - Networked resource monitoring tool. (<b><code>  2138⭐</code></b> <b><code>   482🍴</code></b> [Source Code](https://github.com/munin-monitoring/munin) ⭐ 2,138 | 🐛 217 | 🌐 Perl | 📅 2026-08-09)) `GPL-2.0` `Perl/Shell`
* 🌎 [Nagios](www.nagios.org/) - Computer system, network and infrastructure monitoring software application. (<b><code>  2041⭐</code></b> <b><code>   481🍴</code></b> [Source Code](https://github.com/NagiosEnterprises/nagioscore) ⭐ 2,041 | 🐛 206 | 🌐 C | 📅 2026-08-07)) `GPL-2.0` `C`
* 🌎 [Cacti](www.cacti.net) - Web-based network monitoring and graphing tool. (<b><code>  1863⭐</code></b> <b><code>   445🍴</code></b> [Source Code](https://github.com/Cacti/cacti) ⭐ 1,863 | 🐛 375 | 🌐 PHP | 📅 2026-09-05)) `GPL-2.0` `PHP`
* 🌎 [tirreno](www.tirreno.com/) - Application-level security to protect your app from threats, fraud, and abuse.  🌎 [Demo](play.tirreno.com/), <b><code>  1507⭐</code></b> <b><code>   179🍴</code></b> [Source Code](https://github.com/tirrenotechnologies/tirreno) ⭐ 1,507 | 🐛 9 | 🌐 PHP | 📅 2026-08-14)) `AGPL-3.0` `PHP/Docker`
* 🌎 [PhpSysInfo](phpsysinfo.github.io/phpsysinfo/) - A customizable PHP script that displays information about your system nicely. (<b><code>  1417⭐</code></b> <b><code>   237🍴</code></b> [Source Code](https://github.com/phpsysinfo/phpsysinfo) ⭐ 1,417 | 🐛 3 | 🌐 PHP | 📅 2026-08-19)) `GPL-2.0` `PHP`
* 🌎 [Sensu](sensu.io/) - Monitoring tool for ephemeral infrastructure and distributed applications. (<b><code>  1109⭐</code></b> <b><code>   180🍴</code></b> [Source Code](https://github.com/sensu/sensu-go) ⭐ 1,109 | 🐛 275 | 🌐 Go | 📅 2026-09-04)) `MIT` `Go`
* [Performance Co-Pilot](http://pcp.io) - Lightweight, distributed system performance and analysis framework. (<b><code>  1073⭐</code></b> <b><code>   270🍴</code></b> [Source Code](https://github.com/performancecopilot/pcp) ⭐ 1,073 | 🐛 181 | 🌐 C | 📅 2026-09-04)) `LGPL-2.1/GPL-2.0` `C`
* 🌎 [KuvaszUptime](kuvasz-uptime.dev) - Performant, stable uptime & SSL monitoring service with brandable status pages, IAC support, Prometheus integration and a complete REST API.  🌎 [Demo](kuvasz-uptime.dev/demo/), <b><code>   603⭐</code></b> <b><code>    37🍴</code></b> [Source Code](https://github.com/kuvasz-uptime/kuvasz) ⭐ 604 | 🐛 12 | 🌐 Kotlin | 📅 2026-09-04)) `Apache-2.0` `Docker`
* 🌎 [Thruk](www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, Icinga and Shinken. (<b><code>   442⭐</code></b> <b><code>   161🍴</code></b> [Source Code](https://github.com/sni/Thruk) ⭐ 442 | 🐛 97 | 🌐 Perl | 📅 2026-09-04)) `GPL-1.0` `Perl`
* 🌎 [NetXMS](www.netxms.org/) - Open Source network and infrastructure monitoring and management. (<b><code>   395⭐</code></b> <b><code>    78🍴</code></b> [Source Code](https://github.com/netxms/netxms) ⭐ 396 | 🐛 168 | 🌐 C++ | 📅 2026-09-04)) `LGPL-3.0/GPL-3.0` `Java/C++/C`
* 🌎 [openITCOCKPIT Community Edition](openitcockpit.io/) - Monitoring Suite featuring seamless integrations with Naemon, Checkmk, Grafana and more.  🌎 [Demo](demo.openitcockpit.io/), <b><code>   381⭐</code></b> <b><code>    61🍴</code></b> [Source Code](https://github.com/openITCOCKPIT/openITCOCKPIT) ⭐ 381 | 🐛 73 | 🌐 PHP | 📅 2026-09-04)) `GPL-3.0` `deb/Docker`
* <b><code>   314⭐</code></b> <b><code>    36🍴</code></b> [Status](https://github.com/dani3l0/Status) ⭐ 314 | 🐛 1 | 🌐 Python | 📅 2026-07-08) - Simple and lightweight system monitoring tool for small homeservers with a pleasant web interface.  🌎 [Demo](demos-status.djank.me/)) `MIT` `Python`
* <b><code>   212⭐</code></b> <b><code>     9🍴</code></b> [ruptime](https://github.com/alexmyczko/ruptime) ⭐ 212 | 🐛 5 | 🌐 Shell | 📅 2026-04-15) - Classic system status server. `AGPL-3.0` `Shell`
* 🌎 [Naemon](www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features. (<b><code>   172⭐</code></b> <b><code>    68🍴</code></b> [Source Code](https://github.com/naemon/naemon-core) ⭐ 172 | 🐛 50 | 🌐 C | 📅 2026-09-01)) `GPL-2.0` `C`
* 🌎 [Monit](mmonit.com/monit/#home) - Small utility for managing and monitoring Unix systems.  🌎 [Source Code](bitbucket.org/tildeslash/monit/src/master/)) `AGPL-3.0` `C`
* [Observium Community Edition](http://www.observium.org/) - Network monitoring and management platform that provides real-time insight into network health and performance. `QPL-1.0` `PHP`
* 🌎 [Zabbix](www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications.  🌎 [Source Code](git.zabbix.com/projects/ZBX/repos/zabbix/browse)) `GPL-2.0` `C`

### Network Configuration Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Network configuration management tools.

* <b><code>  3543⭐</code></b> <b><code>  1058🍴</code></b> [Oxidized](https://github.com/ytti/oxidized) ⭐ 3,543 | 🐛 68 | 🌐 Ruby | 📅 2026-08-31) - Network device configuration backup tool. `Apache-2.0` `Ruby`
* 🌎 [phpIPAM](phpipam.net/) - Open source IP address management with PowerDNS integration. (<b><code>  2795⭐</code></b> <b><code>   802🍴</code></b> [Source Code](https://github.com/phpipam/phpipam) ⭐ 2,796 | 🐛 1,856 | 🌐 PHP | 📅 2026-09-04)) `GPL-3.0` `PHP`
* 🌎 [GNS3](www.gns3.com/) - Graphical network simulator that provides a variety of virtual appliances. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/GNS3/gns3-gui/) ⭐ 2,619 | 🐛 130 | 🌐 Python | 📅 2026-08-31)) `GPL-3.0` `Python`
* 🌎 [rConfig](www.rconfig.com/) - Network device configuration management tool. (<b><code>   207⭐</code></b> <b><code>    29🍴</code></b> [Source Code](https://github.com/rconfig/rconfig) ⭐ 207 | 🐛 0 | 🌐 PHP | 📅 2026-09-04)) `GPL-3.0` `PHP`
* 🌎 [RANCID](www.shrubbery.net/rancid/) - Monitor network devices configuration and maintain history of changes. (<b><code>   136⭐</code></b> <b><code>    54🍴</code></b> [Source Code](https://github.com/haussli/rancid) ⭐ 136 | 🐛 57 | 🌐 Makefile | 📅 2026-06-23)) `BSD-3-Clause` `Perl/Shell`
* 🌎 [OpenWISP](openwisp.org/) - Open Source Network Management System for OpenWRT based routers and access points.  🌎 [Demo](openwisp.org/demo.html), [Source Code](https://github.com/openwisp)) `GPL-3.0` `Python`

### PaaS

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Platform-as-a-Service](en.wikipedia.org/wiki/Platform_as_a_service) software allows customers to provision, instantiate, run, and manage a computing platform and one or more applications, without the complexity of building and maintaining the infrastructure typically associated with developing and launching the application. Also includes 🌎 [Serverless computing](en.wikipedia.org/wiki/Serverless_computing) and 🌎 [Function-as-a-service (FaaS)](en.wikipedia.org/wiki/Function_as_a_service) software.

* 🌎 [Coolify](coolify.io/) - An open-source & self-hostable Heroku / Netlify alternative (and even more). (<b><code> 61382⭐</code></b> <b><code>  5405🍴</code></b> [Source Code](https://github.com/coollabsio/coolify) ⭐ 61,430 | 🐛 666 | 🌐 PHP | 📅 2026-09-04)) `Apache-2.0` `Docker`
* 🌎 [Dokku](dokku.com/) - An open-source PaaS (alternative to Heroku). (<b><code> 32122⭐</code></b> <b><code>  2071🍴</code></b> [Source Code](https://github.com/dokku/dokku) ⭐ 32,123 | 🐛 39 | 🌐 Shell | 📅 2026-09-04)) `MIT` `Docker/Shell/Go/deb`
* 🌎 [OpenFaaS](www.openfaas.com/) - Serverless Functions Made Simple for Docker & Kubernetes. (<b><code> 26234⭐</code></b> <b><code>  1968🍴</code></b> [Source Code](https://github.com/openfaas/faas) ⭐ 26,232 | 🐛 31 | 🌐 Go | 📅 2026-07-02)) `MIT` `Go`
* 🌎 [CapRover](caprover.com/) - Build your own PaaS in a few minutes.  🌎 [Demo](captain.server.demo.caprover.com/#/login), <b><code> 15154⭐</code></b> <b><code>   997🍴</code></b> [Source Code](https://github.com/caprover/caprover) ⭐ 15,154 | 🐛 176 | 🌐 TypeScript | 📅 2026-08-31)) `Apache-2.0` `Docker/Nodejs`
* 🌎 [Nhost](nhost.io/) - Firebase Alternative with GraphQL. Get a database and backend configured and ready in minutes. (<b><code>  9287⭐</code></b> <b><code>   616🍴</code></b> [Source Code](https://github.com/nhost/nhost) ⭐ 9,287 | 🐛 167 | 🌐 TypeScript | 📅 2026-09-05)) `MIT` `Docker/Nodejs/Go`
* 🌎 [Tau](taubyte.com) - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, CI/CD, Object Storage, K/V Database, and Pub-Sub Messaging. (<b><code>  5134⭐</code></b> <b><code>   209🍴</code></b> [Source Code](https://github.com/taubyte/tau) ⭐ 5,134 | 🐛 9 | 🌐 Go | 📅 2026-08-16)) `BSD-3-Clause` `Go/Rust/Docker`
* 🌎 [Kubero](www.kubero.dev/) - A self-hosted Heroku PaaS alternative for Kubernetes that implements GitOps.  🌎 [Demo](demo.kubero.dev/), <b><code>  4400⭐</code></b> <b><code>   213🍴</code></b> [Source Code](https://github.com/kubero-dev/kubero) ⭐ 4,400 | 🐛 121 | 🌐 TypeScript | 📅 2026-09-03)) `GPL-3.0` `K8S/Nodejs/Go`
* <b><code>  2229⭐</code></b> <b><code>   157🍴</code></b> [fx](https://github.com/metrue/fx) ⭐ 2,229 | 🐛 85 | 🌐 Go | 📅 2023-10-24) - A tool to help you do Function as a Service with painless on your own servers. `MIT` `Go`

### Packaging

**[`^        back to top        ^`](#awesome-sysadmin)**

A 🌎 [package manager](en.wikipedia.org/wiki/Package_manager) or package-management system is a collection of software tools that automates the process of installing, upgrading, configuring, and removing computer programs for a computer in a consistent manner.

* 🌎 [fpm](fpm.readthedocs.io/en/latest/) - Versatile multi format package creator. (<b><code> 11500⭐</code></b> <b><code>  1064🍴</code></b> [Source Code](https://github.com/jordansissel/fpm) ⭐ 11,503 | 🐛 791 | 🌐 Ruby | 📅 2026-08-26)) `MIT` `Ruby`
* 🌎 [aptly](www.aptly.info/) - Swiss army knife for Debian repository management. (<b><code>  2879⭐</code></b> <b><code>   428🍴</code></b> [Source Code](https://github.com/aptly-dev/aptly) ⭐ 2,880 | 🐛 220 | 🌐 Go | 📅 2026-09-02)) `MIT` `Go`
* <b><code>  1315⭐</code></b> <b><code>   295🍴</code></b> [omnibus-ruby](https://github.com/chef/omnibus) ⭐ 1,315 | 🐛 69 | 🌐 Ruby | 📅 2025-12-09) - Easily create full-stack installers for your project across a variety of platforms. `Apache-2.0` `Ruby`
* <b><code>   398⭐</code></b> <b><code>   131🍴</code></b> [tito](https://github.com/rpm-software-management/tito) ⭐ 398 | 🐛 60 | 🌐 Python | 📅 2026-08-26) - Builds RPMs for git-based projects. `GPL-2.0` `Python`

### Project Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Web-based project management and bug tracking systems.

**Please visit 🌎 [awesome-selfhosted/Project Management](awesome-selfhosted.net/tags/software-development---project-management.html)**

### Queuing

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Message queues](en.wikipedia.org/wiki/Message_queue) and 🌎 [message broker](en.wikipedia.org/wiki/Message_broker) software, typically used for inter-process communication (IPC), or for inter-thread communication within the same process.

*See also: 🌎 [Cloud Native Landscape - Streaming & Messaging](landscape.cncf.io/?group=projects-and-products\&view-mode=card#app-definition-and-development--streaming-messaging)*

* 🌎 [NSQ](nsq.io/) - A realtime distributed messaging platform. (<b><code> 25778⭐</code></b> <b><code>  2890🍴</code></b> [Source Code](https://github.com/nsqio/nsq) ⭐ 25,779 | 🐛 78 | 🌐 Go | 📅 2026-08-11)) `MPL-2.0` `Go`
* 🌎 [BeanstalkD](beanstalkd.github.io/) - A simple, fast work queue. (<b><code>  6700⭐</code></b> <b><code>   867🍴</code></b> [Source Code](https://github.com/beanstalkd/beanstalkd) ⭐ 6,700 | 🐛 46 | 🌐 C | 📅 2025-03-18)) `MIT` `C`
* 🌎 [ActiveMQ](activemq.apache.org/) - Java message broker. (<b><code>  2455⭐</code></b> <b><code>  1494🍴</code></b> [Source Code](https://github.com/apache/activemq) ⭐ 2,454 | 🐛 86 | 🌐 Java | 📅 2026-09-04)) `Apache-2.0` `Java`
* [Gearman](http://gearman.org/) - Fast multi-language queuing/job processing platform. (<b><code>   763⭐</code></b> <b><code>   159🍴</code></b> [Source Code](https://github.com/gearman/gearmand) ⭐ 763 | 🐛 47 | 🌐 C++ | 📅 2026-08-31)) `BSD-3-Clause` `C++`
* 🌎 [ZeroMQ](zeromq.org/) - Lightweight queuing system. ([Source Code](https://github.com/zeromq)) `GPL-3.0` `C++`

### Remote Desktop Clients

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Remote Desktop](en.wikipedia.org/wiki/Remote_desktop_software) client software.

*See also: 🌎 [awesome-selfhosted/Remote Access](awesome-selfhosted.net/tags/remote-access.html)*

* 🌎 [Tiger VNC](tigervnc.org/) - High-performance, multi-platform VNC client and server. (<b><code>  7454⭐</code></b> <b><code>  1185🍴</code></b> [Source Code](https://github.com/TigerVNC/tigervnc) ⭐ 7,460 | 🐛 187 | 🌐 C++ | 📅 2026-08-31)) `GPL-2.0` `C++`
* 🌎 [Remmina](www.remmina.org/) - Feature-rich remote desktop application for linux and other unixes.  🌎 [Source Code](gitlab.com/Remmina/Remmina)) `GPL-2.0` `C`
* 🌎 [X2go](wiki.x2go.org/doku.php) - X2Go is an open source remote desktop software for Linux that uses the NoMachine/NX technology protocol.  🌎 [Source Code](code.x2go.org/gitweb)) `GPL-2.0` `Perl`

### Router

**[`^        back to top        ^`](#awesome-sysadmin)**

Software for management of [router](https://en.wikipedia.org/wiki/Router_\(computing\)) hardware.

* 🌎 [pfSense CE](www.pfsense.org/) - Free network firewall distribution, based on the FreeBSD operating system with a custom kernel and including third party free software packages for additional functionality. (<b><code>  5729⭐</code></b> <b><code>  1597🍴</code></b> [Source Code](https://github.com/pfsense/pfsense) ⭐ 5,731 | 🐛 40 | 🌐 PHP | 📅 2026-03-31)) `Apache-2.0` `Shell/PHP/Other`
* 🌎 [DD-WRT](dd-wrt.com/) - A Linux-based firmware for wireless routers and access points, originally designed for the Linksys WRT54G series.  🌎 [Source Code](svn.dd-wrt.com/)) `GPL-2.0` `C`
* 🌎 [IPFire](www.ipfire.org/) - Free network firewall distribution, based on the Linux operating system with easy-to-use web management console.  🌎 [Source Code](git.ipfire.org/?p=ipfire-2.x.git;a=summary)) `GPL-2.0` `Shell/PHP/Other`
* 🌎 [OpenWrt](openwrt.org/) - A Linux-based router featuring Mesh networking, IPS via snort and AQM among many other features.  🌎 [Source Code](git.openwrt.org/openwrt/openwrt)) `GPL-2.0` `C`
* 🌎 [OPNsense](opnsense.org/) - An open source FreeBSD-based firewall and router with traffic shaping, load balancing, and virtual private network capabilities. ([Source Code](https://github.com/opnsense)) `BSD-2-Clause` `C/PHP`

### Service Discovery

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Service discovery](en.wikipedia.org/wiki/Service_discovery) is the process of automatically detecting devices and services on a computer network.

* 🌎 [etcd](etcd.io/) - Distributed K/V-Store, authenticating via SSL PKI and a REST HTTP Api for shared configuration and service discovery. (<b><code> 52225⭐</code></b> <b><code> 10488🍴</code></b> [Source Code](https://github.com/etcd-io/etcd) ⭐ 52,232 | 🐛 342 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Consul](www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration. (<b><code> 30053⭐</code></b> <b><code>  4619🍴</code></b> [Source Code](https://github.com/hashicorp/consul) ⭐ 30,055 | 🐛 1,422 | 🌐 Go | 📅 2026-09-04)) `MPL-2.0` `Go`
* 🌎 [ZooKeeper](zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services. (<b><code> 12796⭐</code></b> <b><code>  7322🍴</code></b> [Source Code](https://github.com/apache/zookeeper) ⭐ 12,796 | 🐛 240 | 🌐 Java | 📅 2026-09-03)) `Apache-2.0` `Java/C++`

### Software Containers

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Operating system–level](en.wikipedia.org/wiki/OS-level_virtualization) virtualization.

* 🌎 [Portainer Community Edition](www.portainer.io/) - Simple management UI for Docker. (<b><code> 38425⭐</code></b> <b><code>  2892🍴</code></b> [Source Code](https://github.com/portainer/portainer) ⭐ 38,435 | 🐛 746 | 🌐 TypeScript | 📅 2026-09-02)) `Zlib` `Go`
* 🌎 [Docker Compose](docs.docker.com/compose/) - Define and run multi-container Docker applications. (<b><code> 38115⭐</code></b> <b><code>  5798🍴</code></b> [Source Code](https://github.com/docker/compose) ⭐ 38,114 | 🐛 111 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [Podman](podman.io) - Daemonless container engine for developing, managing, and running OCI Containers on your Linux System. Containers can either be run as root or in rootless mode. Simply put: `alias docker=podman`. (<b><code> 32771⭐</code></b> <b><code>  3355🍴</code></b> [Source Code](https://github.com/podman-container-tools/podman) ⭐ 32,773 | 🐛 1,126 | 🌐 Go | 📅 2026-09-05)) `Apache-2.0` `Go`
* 🌎 [systemd-nspawn](www.freedesktop.org/software/systemd/man/systemd-nspawn.html) - Lightweight, chroot-like, environment to run an OS or command directly under systemd. (<b><code> 16655⭐</code></b> <b><code>  4664🍴</code></b> [Source Code](https://github.com/systemd/systemd) ⭐ 16,657 | 🐛 3,415 | 🌐 C | 📅 2026-09-05)) `GPL-2.0` `C`
* 🌎 [Incus](linuxcontainers.org/incus/) - Container "hypervisor" and a better UX for LXC. (<b><code>  6130⭐</code></b> <b><code>   485🍴</code></b> [Source Code](https://github.com/lxc/incus) ⭐ 6,133 | 🐛 38 | 🌐 Go | 📅 2026-09-04)) `Apache-2.0` `Go`
* 🌎 [LXC](linuxcontainers.org/lxc/) - Userspace interface for the Linux kernel containment features. (<b><code>  5254⭐</code></b> <b><code>  1180🍴</code></b> [Source Code](https://github.com/lxc/lxc) ⭐ 5,255 | 🐛 148 | 🌐 C | 📅 2026-08-31)) `GPL-2.0` `C`
* 🌎 [Docker Swarm](docs.docker.com/engine/swarm/) - Manage cluster of Docker Engines. (<b><code>  3648⭐</code></b> <b><code>   672🍴</code></b> [Source Code](https://github.com/moby/swarmkit) ⭐ 3,649 | 🐛 276 | 🌐 Go | 📅 2026-08-28)) `Apache-2.0` `Go`
* 🌎 [Docker](www.docker.com/) - Platform for developers and sysadmins to build, ship, and run distributed applications.  🌎 [Source Code](www.docker.com/community/open-source/)) `Apache-2.0` `Go`
* 🌎 [OpenVZ](openvz.org) - Container-based virtualization for Linux.  🌎 [Source Code](src.openvz.org/projects/OVZ)) `GPL-2.0` `C`

### Time Servers

**[`^        back to top        ^`](#awesome-sysadmin)**

Time synchronization servers and clients (NTP, PTP, Roughtime).

* <b><code>   313⭐</code></b> <b><code>    36🍴</code></b> [Statime](https://github.com/pendulum-project/statime) ⭐ 313 | 🐛 32 | 🌐 Rust | 📅 2026-09-01) - A Precision Time Protocol (PTP) implementation in Rust. `MIT/Apache-2.0` `Rust`
* <b><code>   148⭐</code></b> <b><code>    24🍴</code></b> [Roughenough](https://github.com/int08h/roughenough) ⭐ 148 | 🐛 7 | 🌐 Rust | 📅 2026-08-24) - A Roughtime secure time synchronization client and server. `MIT/Apache-2.0` `Rust`
* 🌎 [OpenNTPD](www.openntpd.org/) - A FREE, easy to use implementation of the Network Time Protocol. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/openntpd-portable/openntpd-openbsd/) ⭐ 23 | 🐛 1 | 🌐 C | 📅 2026-07-02)) `ISC` `C`
* 🌎 [Chrony](chrony-project.org/) - A versatile implementation of the Network Time Protocol (NTP).  🌎 [Source Code](gitlab.com/chrony/chrony)) `GPL-2.0` `C`
* 🌎 [NTPsec](www.ntpsec.org/) - A secure, hardened, and improved implementation of Network Time Protocol derived from NTP Classic.  🌎 [Source Code](gitlab.com/NTPsec/ntpsec)) `BSD-2-Clause` `C`

### Troubleshooting

**[`^        back to top        ^`](#awesome-sysadmin)**

Troubleshooting tools.

* 🌎 [mitmproxy](mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems. (<b><code> 44905⭐</code></b> <b><code>  4711🍴</code></b> [Source Code](https://github.com/mitmproxy/mitmproxy) ⭐ 44,913 | 🐛 480 | 🌐 Python | 📅 2026-09-01)) `MIT` `Python`
* 🌎 [Sysdig](www.sysdig.com/) - Capture system state and activity from a running Linux instance, then save, filter and analyze. (<b><code>  8292⭐</code></b> <b><code>   753🍴</code></b> [Source Code](https://github.com/draios/sysdig) ⭐ 8,292 | 🐛 116 | 🌐 C++ | 📅 2026-04-13)) `Apache-2.0` `Docker/Lua/C`
* 🌎 [mtr](www.bitwizard.nl/mtr/) - Network utility that combines traceroute and ping. (<b><code>  3341⭐</code></b> <b><code>   376🍴</code></b> [Source Code](https://github.com/traviscross/mtr) ⭐ 3,342 | 🐛 139 | 🌐 C | 📅 2026-06-16)) `GPL-2.0` `C`
* 🌎 [grml](grml.org) - Bootable Debian Live CD with powerful CLI tools. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/grml/))) `GPL-3.0` `Shell`
* 🌎 [Wireshark](www.wireshark.org/) - The world's foremost network protocol analyzer.  🌎 [Source Code](gitlab.com/wireshark/wireshark)) `GPL-2.0` `C`

### Version control

**[`^        back to top        ^`](#awesome-sysadmin)**

Software versioning and revision control.

* 🌎 [Git](git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed. (<b><code> 62978⭐</code></b> <b><code> 28345🍴</code></b> [Source Code](https://github.com/git/git) ⭐ 62,986 | 🐛 388 | 🌐 C | 📅 2026-09-04)) `GPL-2.0` `C`
* 🌎 [Darcs](darcs.net/) - Cross-platform version control system, like git, mercurial or svn but with a very different approach: focus on changes rather than snapshots.  🌎 [Source Code](darcs.net/releases/)) `GPL-2.0` `Haskell`
* 🌎 [Fossil](www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.  🌎 [Source Code](www.fossil-scm.org/home/dir?ci=trunk)) `BSD-2-Clause` `C`
* 🌎 [Mercurial](www.mercurial-scm.org/) - Distributed source control management tool.  🌎 [Source Code](repo.mercurial-scm.org/hg/file/tip)) `GPL-2.0` `Python/C/Rust`
* 🌎 [Subversion](subversion.apache.org/) - Client-server revision control system.  🌎 [Source Code](svn.apache.org/repos/asf/subversion/trunk/)) `Apache-2.0` `C`

### Virtualization

**[`^        back to top        ^`](#awesome-sysadmin)**

Virtualization software.

* 🌎 [Vagrant](www.vagrantup.com/) - Tool for building complete development environments. (<b><code> 27205⭐</code></b> <b><code>  4394🍴</code></b> [Source Code](https://github.com/hashicorp/vagrant) ⭐ 27,205 | 🐛 752 | 🌐 Ruby | 📅 2026-09-03)) `BUSL-1.1` `Ruby`
* 🌎 [Packer](www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration. (<b><code> 15775⭐</code></b> <b><code>  3334🍴</code></b> [Source Code](https://github.com/hashicorp/packer) ⭐ 15,774 | 🐛 318 | 🌐 Go | 📅 2026-09-05)) `MPL-2.0` `Go`
* 🌎 [OpenNebula](opennebula.org/) - Build and manage enterprise clouds for virtualized services, containerized applications and serverless computing. (<b><code>  1740⭐</code></b> <b><code>   534🍴</code></b> [Source Code](https://github.com/OpenNebula/one) ⭐ 1,741 | 🐛 757 | 🌐 JavaScript | 📅 2026-09-04)) `Apache-2.0` `C++`
* 🌎 [Ganeti](www.ganeti.org/) - Cluster virtual server management software tool built on top of KVM and Xen. (<b><code>   582⭐</code></b> <b><code>   128🍴</code></b> [Source Code](https://github.com/ganeti/ganeti) ⭐ 583 | 🐛 335 | 🌐 Python | 📅 2026-09-02)) `BSD-2-Clause` `Python/Haskell`
* 🌎 [KVM](www.linux-kvm.org) - Linux kernel virtualization infrastructure.  🌎 [Source Code](git.kernel.org/pub/scm/virt/kvm/kvm.git/)) `GPL-2.0/LGPL-2.0` `C`
* 🌎 [oVirt](www.ovirt.org/) - Manages virtual machines, storage and virtual networks. ([Source Code](https://github.com/oVirt)) `Apache-2.0` `Java`
* 🌎 [Proxmox VE](www.proxmox.com/proxmox-ve) - Virtualization management solution.  🌎 [Source Code](git.proxmox.com/)) `GPL-2.0` `Perl/Shell`
* 🌎 [QEMU](www.qemu.org/) - QEMU is a generic machine emulator and virtualizer.  🌎 [Source Code](gitlab.com/qemu-project/qemu)) `LGPL-2.1` `C`
* 🌎 [VirtualBox](www.virtualbox.org/) - Virtualization product from Oracle Corporation.  🌎 [Source Code](www.virtualbox.org/browser/vbox)) `GPL-3.0/CDDL-1.0` `C++`
* 🌎 [XCP-ng](www.xcp-ng.org/) - Virtualization platform based on Xen Source and Citrix® Hypervisor (formerly XenServer). ([Source Code](https://github.com/xcp-ng)) `GPL-2.0` `C`
* 🌎 [Xen](www.xenproject.org/) - Virtual machine monitor for 32/64 bit Intel / AMD (IA 64) and PowerPC 970 architectures.  🌎 [Source Code](xenbits.xenproject.org/gitweb/?p=xen.git;a=tree;hb=HEAD)) `GPL-2.0` `C`

### VPN

**[`^        back to top        ^`](#awesome-sysadmin)**

VPN software.

* <b><code> 43536⭐</code></b> <b><code>  2557🍴</code></b> [Headscale](https://github.com/juanfont/headscale) ⭐ 43,562 | 🐛 143 | 🌐 Go | 📅 2026-09-04) - Self-hostable fork of 🌎 [Tailscale](tailscale.com), cross-platform clients, simple to use, built-in (currently experimental) monitoring tools. `BSD-3-Clause` `Go`
* <b><code> 18277⭐</code></b> <b><code>  1180🍴</code></b> [Nebula](https://github.com/slackhq/nebula) ⭐ 18,288 | 🐛 104 | 🌐 Go | 📅 2026-09-04) - A scalable p2p VPN with a focus on performance, simplicity and security. `MIT` `Go`
* <b><code> 15398⭐</code></b> <b><code>   616🍴</code></b> [Gluetun VPN client](https://github.com/passteque/gluetun) ⭐ 15,404 | 🐛 334 | 🌐 Go | 📅 2026-09-01) - VPN client in a thin Docker container for multiple VPN providers, written in Go, and using OpenVPN or Wireguard, DNS over TLS, with a few proxy servers built-in. `MIT` `Docker`
* 🌎 [OpenVPN](community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange. (<b><code> 14496⭐</code></b> <b><code>  3390🍴</code></b> [Source Code](https://github.com/OpenVPN/openvpn) ⭐ 14,497 | 🐛 224 | 🌐 C | 📅 2026-09-04)) `GPL-2.0` `C`
* <b><code> 13538⭐</code></b> <b><code>   796🍴</code></b> [sshuttle](https://github.com/sshuttle/sshuttle) ⭐ 13,538 | 🐛 212 | 🌐 Python | 📅 2026-08-31) - Poor man's VPN. `LGPL-2.1` `Python`
* 🌎 [SoftEther](www.softether.org/) - Multi-protocol software VPN with advanced features. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/SoftEtherVPN/SoftEtherVPN/) ⭐ 13,522 | 🐛 296 | 🌐 C | 📅 2026-09-02)) `Apache-2.0` `C`
* 🌎 [Firezone](www.firezone.dev/) - WireGuard based VPN Server and Firewall. (<b><code>  9049⭐</code></b> <b><code>   450🍴</code></b> [Source Code](https://github.com/firezone/firezone) ⭐ 9,049 | 🐛 395 | 🌐 Elixir | 📅 2026-09-05)) `Apache-2.0` `Docker`
* 🌎 [strongSwan](www.strongswan.org/) - Complete IPsec implementation for Linux. (<b><code>  2963⭐</code></b> <b><code>   931🍴</code></b> [Source Code](https://github.com/strongswan/strongswan) ⭐ 2,964 | 🐛 165 | 🌐 C | 📅 2026-09-04)) `GPL-2.0` `C`
* 🌎 [DefGuard](defguard.net/) - True enterprise WireGuard with MFA/2FA and SSO. ([Source Code](https://github.com/DefGuard)) `Apache-2.0` `Rust`
* 🌎 [ocserv](www.infradead.org/ocserv/) - Cisco AnyConnect-compatible VPN server.  🌎 [Source Code](gitlab.com/openconnect/ocserv)) `GPL-2.0` `C`
* 🌎 [WireGuard](www.wireguard.com/) - Very fast VPN based on elliptic curve and public key crypto.  🌎 [Source Code](www.wireguard.com/repositories/)) `GPL-2.0` `C`

### Web

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Web servers](en.wikipedia.org/wiki/Web_server) and 🌎 [reverse proxies](en.wikipedia.org/wiki/Reverse_proxy).

**Please visit 🌎 [awesome-selfhosted/Web Servers](awesome-selfhosted.net/tags/web-servers.html)**

***

## List of Licenses

**[`^        back to top        ^`](#awesome-sysadmin)**

* `AGPL-3.0` - 🌎 [GNU Affero General Public License 3.0](spdx.org/licenses/AGPL-3.0.html)
* `Apache-2.0` - 🌎 [Apache, Version 2.0](spdx.org/licenses/Apache-2.0.html)
* `BSD-2-Clause` - 🌎 [BSD 2-clause "Simplified"](spdx.org/licenses/BSD-2-Clause.html)
* `BSD-3-Clause` - 🌎 [BSD 3-Clause "New" or "Revised"](spdx.org/licenses/BSD-3-Clause.html)
* `BUSL-1.1` - 🌎 [Business Source License 1.1](spdx.org/licenses/BUSL-1.1.html)
* `CC0-1.0` - 🌎 [Public Domain/Creative Common Zero 1.0](spdx.org/licenses/CC0-1.0.html)
* `CDDL-1.0` - 🌎 [Common Development and Distribution License 1.0](spdx.org/licenses/CDDL-1.0.html)
* `EPL-1.0` - 🌎 [Eclipse Public License 1.0](spdx.org/licenses/EPL-1.0.html)
* `GFDL-1.2` - 🌎 [GNU Free Documentation License 1.2](spdx.org/licenses/GFDL-1.2.html)
* `GPL-1.0` - 🌎 [GNU General Public License 1.0](spdx.org/licenses/GPL-1.0.html)
* `GPL-2.0` - 🌎 [GNU General Public License 2.0](spdx.org/licenses/GPL-2.0.html)
* `GPL-3.0` - 🌎 [GNU General Public License 3.0](spdx.org/licenses/GPL-3.0.html)
* `IPL-1.0` - 🌎 [IBM Public License v1.0](spdx.org/licenses/IPL-1.0.html)
* `ISC` - 🌎 [ISC License](spdx.org/licenses/ISC.html)
* `LGPL-2.0` - 🌎 [GNU Lesser General Public License v2](spdx.org/licenses/LGPL-2.0.html)
* `LGPL-2.1` - 🌎 [GNU Lesser General Public License v2.1](spdx.org/licenses/LGPL-2.1.html)
* `LGPL-3.0` - 🌎 [GNU Lesser General Public License v3](spdx.org/licenses/LGPL-3.0.html)
* `MIT` - 🌎 [MIT License](spdx.org/licenses/MIT.html)
* `MPL-2.0` - 🌎 [Mozilla Public License](spdx.org/licenses/MPL-2.0.html)
* `NLPL` - 🌎 [No Limit Public License](spdx.org/licenses/NLPL.html)
* `OLDAP-2.8` - 🌎 [Open LDAP Public License v2.8](spdx.org/licenses/OLDAP-2.8.html)
* `QPL-1.0` - 🌎 [Q Public License 1.0](spdx.org/licenses/QPL-1.0.html)
* `Vim` - 🌎 [Vim License](spdx.org/licenses/Vim.html)
* `Zlib` - 🌎 [zlib License](spdx.org/licenses/Zlib.html)

***

## Anti-features

* `⚠ ` - Depends on a proprietary service outside the user's control

***

## External links

### Communities / Forums

* 🌎 [ArsTechnica OpenForum](arstechnica.com/civis/) - IT Forum which is attached to a large news site.
* 🌎 [Reddit](www.reddit.com) - Really, really large bulletin board system.
  * 🌎 [/r/Linux](www.reddit.com/r/linux) - News and information about Linux.
  * 🌎 [/r/LinuxQuestions](www.reddit.com/r/linuxquestions)
  * 🌎 [/r/SysAdmin](www.reddit.com/r/sysadmin/)
* 🌎 [Spiceworks Community](community.spiceworks.com/) - General enterprise IT news and small articles.
* 🌎 [StackExchange Network](stackexchange.com/sites#technology) - Q\&A communities.
  * 🌎 [Server Fault](serverfault.com/) - StackExchange community for system and network administrators.

### Repositories

*Software package repositories.*

* 🌎 [AlternativeTo](alternativeto.net) - Find alternatives to software you know and discover new software.
* 🌎 [deb.sury.org](deb.sury.org/) - Repository with LAMP updated packages for Debian and Ubuntu.
* 🌎 [ElRepo](elrepo.org/tiki/tiki-index.php) - Community Repo for Enterprise Linux (RHEL, CentOS, etc).
* 🌎 [EPEL](fedoraproject.org/wiki/EPEL) - Repository for RHEL and compatibles (CentOS, Scientific Linux).
* 🌎 [IUS](ius.io/) - Community project that provides RPM packages for newer versions of select software for Enterprise Linux distributions.
* [Remi](http://rpms.famillecollet.com/) - Repository with LAMP updated packages for RHEL/Centos/Fedora.

### Websites

* 🌎 [ArchWiki](wiki.archlinux.org/) - Arch Linux Wiki which has really nice written articles valid for other distros.
* 🌎 [Awesome SysAdmin @ LibHunt](sysadmin.libhunt.com) - Your go-to SysAdmin Toolbox. Based on the list here.
* 🌎 [awesome-sysadmin.theravenhub.com](awesome-sysadmin.theravenhub.com/) - Alternative frontend to filter and search the list.
* 🌎 [Cloud Native Software Landscape](landscape.cncf.io/?group=projects-and-products\&view-mode=card) - Compilation of software and tools for cloud computing.
* 🌎 [Digital Ocean Tutorials](www.digitalocean.com/community/tutorials) - 6,000+ tutorials for getting the basics of certain applications/tools/systems administration topics.
* 🌎 [Gentoo Wiki](wiki.gentoo.org/) - Gentoo Linux Wiki with a lot in-detail description of Linux components.
* 🌎 [Ops School](www.opsschool.org) - Comprehensive program that will help you learn to be an operations engineer.

***

## Contributing

Contributing guidelines can be found <b><code>     9⭐</code></b> <b><code>    37🍴</code></b> [here](https://github.com/awesome-foss/awesome-sysadmin-data/blob/master/CONTRIBUTING.md) ⭐ 9 | 🐛 21 | 🌐 Makefile | 📅 2026-09-04).

## License

This list is under the [Creative Commons Attribution-ShareAlike 4.0 International](LICENSE).
Terms of the license are summarized 🌎 [here](creativecommons.org/licenses/by-sa/4.0).
The list of authors can be found in the [AUTHORS](AUTHORS) file.

## Source

<b><code> 35063⭐</code></b> <b><code>  2099🍴</code></b> [awesome-foss/awesome-sysadmin](https://github.com/awesome-foss/awesome-sysadmin) ⭐ 35,075 | 🐛 0 | 📅 2026-09-02)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-05._
