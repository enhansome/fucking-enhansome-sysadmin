# Awesome Sysadmin with stars

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome) ⭐ 496,176 | 🐛 100 | 📅 2026-06-30 [![](https://github.com/awesome-foss/awesome-sysadmin-data/actions/workflows/dead-links.yml/badge.svg)](https://github.com/awesome-foss/awesome-sysadmin-data/issues/1) ⭐ 9 | 🐛 22 | 🌐 Makefile | 📅 2026-08-09 [![](https://github.com/awesome-foss/awesome-sysadmin-data/actions/workflows/unmaintained-projects.yml/badge.svg)](https://github.com/awesome-foss/awesome-sysadmin-data/issues/1) ⭐ 9 | 🐛 22 | 🌐 Makefile | 📅 2026-08-09

**A curated list of amazingly awesome Free and Open-Source sysadmin resources.** Please read the [Contributing](#contributing) if you wish to add software and consider <b><code>    48⭐</code></b> <b><code>     4🍴</code></b> [donating](https://github.com/n1trux/awesome-donations) ⭐ 48 | 🐛 2 | 📅 2024-01-02) to the FLOSS projects you use regularly. Please consider contributing to fix one of the pinned <b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [issues](https://github.com/awesome-foss/awesome-sysadmin-data/issues) ⭐ 9 | 🐛 22 | 🌐 Makefile | 📅 2026-08-09) if your time allows.

* 🌎 [HTML version](sysadmin.awesome-selfhosted.net/) (recommended)\*\*, **[Markdown version](https://github.com/correia-jpv/fucking-awesome-sysadmin) ⭐ 93 | 🐛 1 | 📅 2026-08-14** (legacy).

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

* 🌎 [Bazel](www.bazel.io/) - A fast, scalable, multi-language and extensible build system. Used by Google. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/bazelbuild/bazel/) ⭐ 25,716 | 🐛 1,931 | 🌐 Java | 📅 2026-08-15)) `Apache-2.0` `Java`
* 🌎 [Gradle](gradle.org/) - Another build automation system. (<b><code> 18776⭐</code></b> <b><code>  5340🍴</code></b> [Source Code](https://github.com/gradle/gradle) ⭐ 18,779 | 🐛 3,463 | 🌐 Groovy | 📅 2026-08-15)) `Apache-2.0` `Groovy/Java`
* 🌎 [Apache Maven](maven.apache.org/) - Build automation tool mainly for Java. A software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information. (<b><code>  5314⭐</code></b> <b><code>  3105🍴</code></b> [Source Code](https://github.com/apache/maven) ⭐ 5,316 | 🐛 780 | 🌐 Java | 📅 2026-08-11)) `Apache-2.0` `Java`
* 🌎 [Rake](ruby.github.io/rake/) - Build automation tool similar to Make, written in and extensible in Ruby. (<b><code>  2455⭐</code></b> <b><code>   649🍴</code></b> [Source Code](https://github.com/ruby/rake) ⭐ 2,455 | 🐛 72 | 🌐 Ruby | 📅 2026-08-10)) `MIT` `Ruby`
* 🌎 [Apache Ant](ant.apache.org/) - Automation build tool, similar to make, a library and command-line tool whose mission is to drive processes described in build files as targets and extension points dependent upon each other. (<b><code>   471⭐</code></b> <b><code>   455🍴</code></b> [Source Code](https://github.com/apache/ant) ⭐ 471 | 🐛 17 | 🌐 Java | 📅 2026-08-14)) `Apache-2.0` `Java`
* 🌎 [OpenBolt](voxpupuli.org/openvox/) - Orchestration tool to run orchestration workflows or one-off tasks/scripts to automate the provisioning and management of nodes. Community fork of the last open source version of 🌎 [Puppet Bolt](help.puppet.com/bolt/current/topics/bolt.htm). (<b><code>    32⭐</code></b> <b><code>    23🍴</code></b> [Source Code](https://github.com/OpenVoxProject/openbolt) ⭐ 32 | 🐛 34 | 🌐 Ruby | 📅 2026-08-13)) `Apache-2.0` `Ruby`
* 🌎 [GNU Make](www.gnu.org/software/make/) - The most popular automation build tool for many purposes, make is a tool which controls the generation of executables and other non-source files of a program from the program's source files.  🌎 [Source Code](git.savannah.gnu.org/cgit/make.git)) `GPL-3.0` `C`

### Backups

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Backup](en.wikipedia.org/wiki/Backup) software.

*See also: <b><code>   755⭐</code></b> <b><code>    58🍴</code></b> [Restic's list of Linux backup software](https://github.com/restic/others) ⭐ 755 | 🐛 13 | 📅 2023-11-05)*

* 🌎 [rclone](rclone.org/) - Command-line program to sync files and directories to and from different cloud storage providers.. (<b><code> 59134⭐</code></b> <b><code>  5309🍴</code></b> [Source Code](https://github.com/rclone/rclone) ⭐ 59,171 | 🐛 1,224 | 🌐 Go | 📅 2026-08-14)) `MIT` `Go`
* 🌎 [Restic](restic.net/) - Easy, fast, verifiable, secure and efficient remote backup tool. (<b><code> 35502⭐</code></b> <b><code>  1827🍴</code></b> [Source Code](https://github.com/restic/restic) ⭐ 35,539 | 🐛 564 | 🌐 Go | 📅 2026-08-01)) `BSD-2-Clause` `Go`
* 🌎 [Duplicati](www.duplicati.com) - Backup client that securely stores encrypted, incremental, compressed backups on cloud storage services and remote file servers. (<b><code> 14881⭐</code></b> <b><code>  1060🍴</code></b> [Source Code](https://github.com/duplicati/duplicati) ⭐ 14,888 | 🐛 646 | 🌐 C# | 📅 2026-08-14)) `LGPL-2.1` `C#`
* 🌎 [BorgBackup](www.borgbackup.org/) - Deduplicating archiver with compression and authenticated encryption. (<b><code> 13603⭐</code></b> <b><code>   868🍴</code></b> [Source Code](https://github.com/borgbackup/borg) ⭐ 13,616 | 🐛 267 | 🌐 Python | 📅 2026-08-15)) `BSD-3-Clause` `Python`
* 🌎 [Databasus](databasus.com/) - PostgreSQL, MySQL, MariaDB and MongoDB backup tool with web UI, external storages (local, S3, FTP, Google Drive, etc.), notifications (webhook, Discord, Slack, etc.) and team management. (<b><code>  7913⭐</code></b> <b><code>   475🍴</code></b> [Source Code](https://github.com/databasus/databasus) ⭐ 7,924 | 🐛 5 | 🌐 Go | 📅 2026-08-13)) `Apache-2.0` `Docker`
* 🌎 [Backrest](garethgeorge.github.io/backrest/) - Backrest is a web UI and orchestrator for restic backup. (<b><code>  7122⭐</code></b> <b><code>   204🍴</code></b> [Source Code](https://github.com/garethgeorge/backrest) ⭐ 7,135 | 🐛 341 | 🌐 TypeScript | 📅 2026-08-10)) `GPL-3.0` `Docker/Go`
* 🌎 [Rsnapshot](rsnapshot.org/) - Filesystem snapshot utility based on rsync. (<b><code>  3662⭐</code></b> <b><code>   272🍴</code></b> [Source Code](https://github.com/rsnapshot/rsnapshot) ⭐ 3,663 | 🐛 58 | 🌐 Perl | 📅 2026-08-13)) `GPL-2.0` `Perl`
* 🌎 [Barman](pgbarman.org) - Backup and Recovery Manager for PostgreSQL. (<b><code>  3218⭐</code></b> <b><code>   267🍴</code></b> [Source Code](https://github.com/EnterpriseDB/barman) ⭐ 3,217 | 🐛 39 | 🌐 Python | 📅 2026-08-13)) `GPL-3.0` `Python`
* 🌎 [Portabase](portabase.io/) - Server dashboard tool that simplifies the backup and restoration of your database instances. (<b><code>  1641⭐</code></b> <b><code>   100🍴</code></b> [Source Code](https://github.com/Portabase/portabase) ⭐ 1,643 | 🐛 34 | 🌐 TypeScript | 📅 2026-08-14)) `Apache-2.0` `Docker`
* 🌎 [Rdiff-backup](rdiff-backup.net/) - Reverse differential backup tool, over a network or locally. (<b><code>  1264⭐</code></b> <b><code>    98🍴</code></b> [Source Code](https://github.com/rdiff-backup/rdiff-backup) ⭐ 1,265 | 🐛 81 | 🌐 Python | 📅 2026-08-14)) `GPL-2.0` `Python`
* 🌎 [Bareos](www.bareos.org/) - Cross-network backup solution which preserves, archives, and recovers data from all major operating systems. (<b><code>  1232⭐</code></b> <b><code>   309🍴</code></b> [Source Code](https://github.com/bareos/bareos) ⭐ 1,234 | 🐛 82 | 🌐 C++ | 📅 2026-08-10)) `AGPL-3.0` `C++/C`
* 🌎 [UrBackup](www.urbackup.org/) - Client/Server Open Source Network Backup for Windows, MacOS and Linux. (<b><code>   891⭐</code></b> <b><code>   168🍴</code></b> [Source Code](https://github.com/uroni/urbackup_backend) ⭐ 892 | 🐛 2 | 🌐 C | 📅 2026-06-17)) `AGPL-3.0` `C/C++`
* 🌎 [Burp](burp.grke.org/) - Network backup and restore program. (<b><code>   503⭐</code></b> <b><code>    77🍴</code></b> [Source Code](https://github.com/grke/burp) ⭐ 503 | 🐛 80 | 🌐 C | 📅 2026-07-13)) `AGPL-3.0` `C`
* <b><code>   401⭐</code></b> <b><code>    66🍴</code></b> [Shield](https://github.com/shieldproject/shield) ⭐ 401 | 🐛 32 | 🌐 Go | 📅 2026-08-11) - A pluggable architecture for backup and restore of database systems. `MIT` `Go`
* [Dar](http://dar.linux.free.fr/) - Which stands for Disk ARchive, is a robust and rich featured archiving and backup software of the tar style. (<b><code>   201⭐</code></b> <b><code>    24🍴</code></b> [Source Code](https://github.com/Edrusb/DAR) ⭐ 202 | 🐛 5 | 🌐 C++ | 📅 2026-08-06)) `GPL-2.0` `C++`
* 🌎 [Backupninja](0xacab.org/liberate/backupninja) - Lightweight, extensible meta-backup system, provides a centralized way to configure and coordinate many different backup utilities. `GPL-2.0` `Shell`
* 🌎 [Duplicity](duplicity.gitlab.io/) - Encrypted bandwidth-efficient backup using the rsync algorithm.  🌎 [Source Code](gitlab.com/duplicity/duplicity)) `GPL-2.0` `Python`
* 🌎 [Minarca](minarca.org/) - Client–server backup platform with a centralized web console to manage and restore Linux, Windows, and macOS backups via GUI or CLI.  🌎 [Source Code](gitlab.com/ikus-soft/minarca)) `AGPL-3.0` `Python`
* 🌎 [Proxmox Backup Server](www.proxmox.com/en/proxmox-backup-server) - Proxmox Backup Server is an enterprise-class, client-server backup solution thatis capable of backing up virtual machines, containers, and physical hosts.  🌎 [Source Code](git.proxmox.com/?p=proxmox-backup.git;a=tree)) `GPL-3.0` `Rust`

### Build and software organization tools

**[`^        back to top        ^`](#awesome-sysadmin)**

Build and software organization tools.

* 🌎 [Spack](spack.io/) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers. (<b><code>  5108⭐</code></b> <b><code>  2453🍴</code></b> [Source Code](https://github.com/spack/spack) ⭐ 5,108 | 🐛 1,791 | 🌐 Python | 📅 2026-08-14)) `MIT/Apache-2.0` `Python`
* 🌎 [Environment Modules](envmodules.io/) - Environment Modules provides for the dynamic modification of a user's environment via modulefiles. (<b><code>   861⭐</code></b> <b><code>   122🍴</code></b> [Source Code](https://github.com/envmodules/modules) ⭐ 861 | 🐛 33 | 🌐 Tcl | 📅 2026-08-15)) `GPL-2.0` `Tcl`
* 🌎 [Lmod](www.tacc.utexas.edu/research-development/tacc-projects/lmod) - Lmod is a Lua based module system that easily handles the MODULEPATH Hierarchical problem. (<b><code>   606⭐</code></b> <b><code>   144🍴</code></b> [Source Code](https://github.com/TACC/Lmod) ⭐ 607 | 🐛 26 | 🌐 Lua | 📅 2026-07-28)) `MIT` `Lua`
* 🌎 [EasyBuild](easybuild.io/) - EasyBuild builds software and modulefiles for High Performance Computing (HPC) systems in an efficient way. (<b><code>   451⭐</code></b> <b><code>   789🍴</code></b> [Source Code](https://github.com/easybuilders/easybuild-easyconfigs) ⭐ 451 | 🐛 1,130 | 🌐 Python | 📅 2026-08-13)) `GPL-2.0` `Python`

### ChatOps

**[`^        back to top        ^`](#awesome-sysadmin)**

Conversation-driven development and management.

*See also: 🌎 [/r/chatops](old.reddit.com/r/chatops)*

* 🌎 [Hubot](hubot.github.com/) - A customizable, life embetterment robot. (<b><code> 16795⭐</code></b> <b><code>  3716🍴</code></b> [Source Code](https://github.com/hubotio/hubot) ⭐ 16,796 | 🐛 6 | 🌐 JavaScript | 📅 2026-07-22)) `MIT` `Nodejs`
* 🌎 [Errbot](errbot.io/) - Plugin based chatbot designed to be easily deployable, extensible and maintainable. (<b><code>  3297⭐</code></b> <b><code>   625🍴</code></b> [Source Code](https://github.com/errbotio/errbot) ⭐ 3,298 | 🐛 45 | 🌐 Python | 📅 2026-08-15)) `GPL-3.0` `Python`
* 🌎 [Eggdrop](www.eggheads.org/) - The oldest Internet Relay Chat (IRC) bot still in active development. (<b><code>   577⭐</code></b> <b><code>   100🍴</code></b> [Source Code](https://github.com/eggheads/eggdrop) ⭐ 577 | 🐛 247 | 🌐 C | 📅 2026-08-02)) `GPL-2.0` `C`

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

* 🌎 [Ansible](www.ansible.com/) - Provisioning, configuration management, and application-deployment tool. (<b><code> 70359⭐</code></b> <b><code> 24329🍴</code></b> [Source Code](https://github.com/ansible/ansible) ⭐ 70,344 | 🐛 830 | 🌐 Python | 📅 2026-08-11)) `GPL-3.0` `Python`
* 🌎 [Salt](docs.saltproject.io/) - Event-driven IT automation, remote task execution, and configuration management software. (<b><code> 15613⭐</code></b> <b><code>  5612🍴</code></b> [Source Code](https://github.com/saltstack/salt) ⭐ 15,615 | 🐛 1,922 | 🌐 Python | 📅 2026-08-15)) `Apache-2.0` `Python`
* 🌎 [cloud-init](cloud-init.io/) - Initialization tool to automate the configuration of VMs, cloud instances, or machines on a network. (<b><code>  3785⭐</code></b> <b><code>  1117🍴</code></b> [Source Code](https://github.com/canonical/cloud-init) ⭐ 3,785 | 🐛 576 | 🌐 Python | 📅 2026-08-12)) `GPL-3.0/Apache-2.0` `Python`
* 🌎 [Rudder](www.rudder.io/) - Scalable and dynamic configuration management system for patching, security & compliance, based on CFEngine. (<b><code>   705⭐</code></b> <b><code>    91🍴</code></b> [Source Code](https://github.com/Normation/rudder) ⭐ 705 | 🐛 41 | 🌐 Scala | 📅 2026-08-14)) `GPL-3.0` `Scala`
* 🌎 [CFEngine](cfengine.com/) - Configuration management system for automated configuration and maintenance of large-scale computer systems. (<b><code>   532⭐</code></b> <b><code>   200🍴</code></b> [Source Code](https://github.com/cfengine/core) ⭐ 532 | 🐛 11 | 🌐 C | 📅 2026-08-15)) `GPL-3.0` `C`
* 🌎 [OpenVox](voxpupuli.org/openvox/) - Community fork of the last open source version of 🌎 [Puppet](www.puppet.com/), a software configuration management tool which includes its own declarative language to describe system configuration. (<b><code>   182⭐</code></b> <b><code>    61🍴</code></b> [Source Code](https://github.com/OpenVoxProject/openvox) ⭐ 182 | 🐛 95 | 🌐 Ruby | 📅 2026-08-14)) `Apache-2.0` `Ruby/C`
* 🌎 [CINC](cinc.sh/) - Free distribution of 🌎 [Chef](www.chef.io/products/chef-infra), a configuration management tool using a pure-Ruby, domain-specific language (DSL) for writing system configuration "recipes".  🌎 [Source Code](gitlab.com/cinc-project/upstream/chef)) `Apache-2.0` `Ruby`

### Configuration Management Database

**[`^        back to top        ^`](#awesome-sysadmin)**

Configuration management database (CMDB) software.

*Related: [IT Asset Management](#it-asset-management)*

* 🌎 [netbox](netbox.dev/) - IP address management (IPAM) and data center infrastructure management (DCIM) tool.  🌎 [Demo](demo.netbox.dev/), <b><code> 21311⭐</code></b> <b><code>  3101🍴</code></b> [Source Code](https://github.com/netbox-community/netbox) ⭐ 21,318 | 🐛 213 | 🌐 Python | 📅 2026-08-15)) `Apache-2.0` `Python`
* 🌎 [iTop](combodo.com/) - Complete ITIL web based service management tool. (<b><code>  1166⭐</code></b> <b><code>   294🍴</code></b> [Source Code](https://github.com/Combodo/iTop) ⭐ 1,166 | 🐛 61 | 🌐 PHP | 📅 2026-08-15)) `AGPL-3.0` `PHP`
* 🌎 [Collins](tumblr.github.io/collins/) - At Tumblr, it's the infrastructure source of truth and knowledge. (<b><code>   575⭐</code></b> <b><code>    96🍴</code></b> [Source Code](https://github.com/tumblr/collins) ⭐ 575 | 🐛 67 | 🌐 Scala | 📅 2021-03-01)) `Apache-2.0` `Docker/Scala`
* 🌎 [i-doit](www.i-doit.org/) - IT Documentation and CMDB. `AGPL-3.0` `PHP`

### Continuous Integration & Continuous Deployment

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Continuous integration](en.wikipedia.org/wiki/Continuous_integration) 🌎 [deployment](en.wikipedia.org/wiki/Continuous_deployment) software.

* 🌎 [Harness](www.harness.io/open-source) - End-to-end developer platform with Source Control Management, CI/CD Pipelines, Hosted Developer Environments, and Artifact Registries (fork of Drone). (<b><code> 37875⭐</code></b> <b><code>  3323🍴</code></b> [Source Code](https://github.com/harness/harness) ⭐ 37,961 | 🐛 105 | 🌐 Go | 📅 2026-08-14)) `Apache-2.0` `Go`
* 🌎 [Jenkins](jenkins-ci.org/) - Continuous Integration Server. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/jenkinsci/jenkins/) ⭐ 26,462 | 🐛 3,615 | 🌐 Java | 📅 2026-08-16)) `MIT` `Java`
* 🌎 [ArgoCD](argo-cd.readthedocs.io/en/stable/) - Declarative, GitOps continuous delivery tool for Kubernetes. (<b><code> 23920⭐</code></b> <b><code>  7735🍴</code></b> [Source Code](https://github.com/argoproj/argo-cd) ⭐ 23,928 | 🐛 4,352 | 🌐 Go | 📅 2026-08-15)) `Apache-2.0` `Go`
* 🌎 [Concourse](concourse-ci.org/) - Concourse is a CI tool that treats pipelines as first class objects and containerizes every step along the way.  🌎 [Demo](ci.concourse-ci.org/), <b><code>  7886⭐</code></b> <b><code>   895🍴</code></b> [Source Code](https://github.com/concourse/concourse) ⭐ 7,887 | 🐛 78 | 🌐 Go | 📅 2026-08-14)) `Apache-2.0` `Go`
* 🌎 [Woodpecker](woodpecker-ci.org/) - Community fork of Drone that uses Docker containers. (<b><code>  7683⭐</code></b> <b><code>   648🍴</code></b> [Source Code](https://github.com/woodpecker-ci/woodpecker) ⭐ 7,694 | 🐛 369 | 🌐 Go | 📅 2026-08-16)) `Apache-2.0` `Go`
* 🌎 [GoCD](www.go.cd/) - Continuous delivery server. (<b><code>  7421⭐</code></b> <b><code>   980🍴</code></b> [Source Code](https://github.com/gocd/gocd) ⭐ 7,423 | 🐛 82 | 🌐 Java | 📅 2026-08-15)) `Apache-2.0` `Java/Ruby`
* 🌎 [Buildbot](buildbot.net/) - Python-based toolkit for continuous integration. (<b><code>  5463⭐</code></b> <b><code>  1670🍴</code></b> [Source Code](https://github.com/buildbot/buildbot) ⭐ 5,463 | 🐛 815 | 🌐 Python | 📅 2026-08-15)) `GPL-2.0` `Python`
* 🌎 [CDS](ovh.github.io/cds/) - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform. (<b><code>  4831⭐</code></b> <b><code>   456🍴</code></b> [Source Code](https://github.com/ovh/cds) ⭐ 4,831 | 🐛 159 | 🌐 Go | 📅 2026-08-14)) `BSD-3-Clause` `Go`
* 🌎 [werf](werf.io/) - Open Source CI/CD tool for building Docker images and deploying to Kubernetes via GitOps. (<b><code>  4715⭐</code></b> <b><code>   238🍴</code></b> [Source Code](https://github.com/werf/werf) ⭐ 4,716 | 🐛 26 | 🌐 Go | 📅 2026-08-13)) `Apache-2.0` `Go`
* 🌎 [Strider](strider-cd.github.io/) - Open Source Continuous Deployment / Continuous Integration platform. (<b><code>  4566⭐</code></b> <b><code>   419🍴</code></b> [Source Code](https://github.com/Strider-CD/strider) ⭐ 4,566 | 🐛 179 | 🌐 JavaScript | 📅 2024-09-11)) `MIT` `Nodejs`
* 🌎 [Terrateam](terrateam.io) - GitOps-first automation platform for Terraform and OpenTofu workflows with support for self-hosted runners. (<b><code>  1259⭐</code></b> <b><code>    73🍴</code></b> [Source Code](https://github.com/terrateamio/terrateam) ⭐ 1,260 | 🐛 159 | 🌐 OCaml | 📅 2026-08-14)) `MPL-2.0` `OCaml/Docker`
* <b><code>   689⭐</code></b> <b><code>   145🍴</code></b> [PHP Censor](https://github.com/php-censor/php-censor) ⭐ 689 | 🐛 23 | 🌐 PHP | 📅 2026-05-31) - Open source self-hosted continuous integration server for PHP projects. `BSD-2-Clause` `PHP`
* 🌎 [Laminar](laminar.ohwg.net) - Fast, lightweight, simple and flexible Continuous Integration. (<b><code>   352⭐</code></b> <b><code>    63🍴</code></b> [Source Code](https://github.com/ohwgiles/laminar) ⭐ 352 | 🐛 17 | 🌐 C++ | 📅 2026-07-24)) `GPL-3.0` `C++`
* 🌎 [GitLab CI](about.gitlab.com/solutions/continuous-integration/) - Gitlab's built-in, full-featured CI/CD solution.  🌎 [Source Code](gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby`

### Control Panels

**[`^        back to top        ^`](#awesome-sysadmin)**

Web hosting and server or service control panels.

* 🌎 [Cockpit](cockpit-project.org/) - Web-based graphical interface for servers. (<b><code> 14881⭐</code></b> <b><code>  1326🍴</code></b> [Source Code](https://github.com/cockpit-project/cockpit) ⭐ 14,903 | 🐛 479 | 🌐 JavaScript | 📅 2026-08-14)) `LGPL-2.1` `C`
* 🌎 [Ajenti](ajenti.org/) - Control panel for Linux and BSD. (<b><code>  7952⭐</code></b> <b><code>   862🍴</code></b> [Source Code](https://github.com/ajenti/ajenti) ⭐ 7,953 | 🐛 10 | 🌐 Python | 📅 2026-07-22)) `MIT` `Python/Shell`
* 🌎 [MeshCentral](meshcentral.com) - A complete web-based remote monitoring and management web site. (<b><code>  7054⭐</code></b> <b><code>   949🍴</code></b> [Source Code](https://github.com/ylianst/meshcentral) ⭐ 7,059 | 🐛 144 | 🌐 HTML | 📅 2026-08-12)) `Apache-2.0` `JavaScript/HTML`
* 🌎 [Webmin](www.webmin.com/) - Web-based interface for system administration for Unix. (<b><code>  6005⭐</code></b> <b><code>   790🍴</code></b> [Source Code](https://github.com/webmin/webmin) ⭐ 6,008 | 🐛 128 | 🌐 HTML | 📅 2026-08-15)) `BSD-3-Clause` `Perl`
* 🌎 [HestiaCP](hestiacp.com/) - Web server control panel (fork of VestaCP).  🌎 [Demo](demo.hestiacp.com:8083/login/), <b><code>  4461⭐</code></b> <b><code>   913🍴</code></b> [Source Code](https://github.com/hestiacp/hestiacp) ⭐ 4,474 | 🐛 135 | 🌐 Shell | 📅 2026-08-15)) `GPL-3.0` `PHP/Shell/Other`
* 🌎 [Froxlor](froxlor.org/) - Lightweight server management software with Nginx and PHP-FPM support. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/Froxlor/Froxlor/) ⭐ 1,747 | 🐛 43 | 🌐 PHP | 📅 2026-06-19)) `GPL-2.0` `PHP`
* 🌎 [Sentora](sentora.org/) - Open-Source Web hosting control panel for Linux, BSD (fork of ZPanel). (<b><code>   675⭐</code></b> <b><code>   440🍴</code></b> [Source Code](https://github.com/sentora/sentora-core) ⭐ 675 | 🐛 27 | 🌐 PHP | 📅 2025-02-23)) `GPL-3.0` `PHP`
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

* 🌎 [Fabric](www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks. (<b><code> 15487⭐</code></b> <b><code>  1960🍴</code></b> [Source Code](https://github.com/fabric/fabric) ⭐ 15,486 | 🐛 506 | 🌐 Python | 📅 2026-04-10)) `BSD-2-Clause` `Python`
* 🌎 [Capistrano](capistranorb.com/) - Deploy your application to any number of machines simultaneously, in sequence or as a rolling set via SSH (rake based). (<b><code> 12981⭐</code></b> <b><code>  1742🍴</code></b> [Source Code](https://github.com/capistrano/capistrano) ⭐ 12,982 | 🐛 65 | 🌐 Ruby | 📅 2026-07-19)) `MIT` `Ruby`
* 🌎 [munki](www.munki.org/munki/) - Webserver-based repository of packages and package metadata, that allows macOS administrators to manage software installs. (<b><code>  3450⭐</code></b> <b><code>   371🍴</code></b> [Source Code](https://github.com/munki/munki) ⭐ 3,451 | 🐛 73 | 🌐 Swift | 📅 2026-08-14)) `Apache-2.0` `Python`
* 🌎 [CloudStack](cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services. (<b><code>  3023⭐</code></b> <b><code>  1368🍴</code></b> [Source Code](https://github.com/apache/cloudstack) ⭐ 3,023 | 🐛 931 | 🌐 Java | 📅 2026-08-15)) `Apache-2.0` `Java/Python`
* 🌎 [Cobbler](cobbler.github.io/) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments. (<b><code>  2769⭐</code></b> <b><code>   659🍴</code></b> [Source Code](https://github.com/cobbler/cobbler) ⭐ 2,768 | 🐛 316 | 🌐 Python | 📅 2026-08-15)) `GPL-2.0` `Python`
* 🌎 [Overcast](andrewchilds.github.io/overcast/) - Deploy VMs across different cloud providers, and run commands and scripts across any or all of them in parallel via SSH. (<b><code>   483⭐</code></b> <b><code>    36🍴</code></b> [Source Code](https://github.com/andrewchilds/overcast) ⭐ 483 | 🐛 9 | 🌐 JavaScript | 📅 2026-05-20)) `MIT` `Nodejs`
* 🌎 [FaynoSync](faynosync.com) - Self-hosted Dynamic Update Server with statistics, supporting multiple updaters. Flexible features for seamless app updates and insights. (<b><code>   155⭐</code></b> <b><code>     3🍴</code></b> [Source Code](https://github.com/ku9nov/faynoSync) ⭐ 155 | 🐛 1 | 🌐 Go | 📅 2026-07-27), <b><code>     5⭐</code></b> <b><code>     1🍴</code></b> [Clients](https://github.com/ku9nov/faynoSync-dashboard) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-04)) `Apache-2.0` `Docker/Go`
* 🌎 [CloudSlang](www.cloudslang.io/) - Flow-based orchestration tool for managing deployed applications, with Docker capabilities. (<b><code>    95⭐</code></b> <b><code>    45🍴</code></b> [Source Code](https://github.com/CloudSlang/score) ⭐ 95 | 🐛 18 | 🌐 Java | 📅 2026-08-11)) `Apache-2.0` `Java`
* <b><code>    64⭐</code></b> <b><code>    29🍴</code></b> [Genesis](https://github.com/genesis-community/genesis) ⭐ 64 | 🐛 50 | 🌐 Perl | 📅 2026-08-04) - A template framework for multi-environment BOSH deployments. `MIT` `Perl`

### Diagramming

**[`^        back to top        ^`](#awesome-sysadmin)**

Tools used to create diagrams of networks, flows, etc.

* 🌎 [Diagrams.net](app.diagrams.net/) - A.K.A. 🌎 [Draw.io](app.diagrams.net/). Easy to use Diagram UI with a plethora of templates. (<b><code>  7488⭐</code></b> <b><code>  1157🍴</code></b> [Source Code](https://github.com/jgraph/drawio) ⭐ 7,526 | 🐛 118 | 🌐 JavaScript | 📅 2026-08-09)) `Apache-2.0` `JavaScript/Docker`
* 🌎 [Mermaid](mermaid-js.github.io/mermaid-live-editor/) - Javascript module with a unique, easy, shorthand syntax. Integrates into several other tools like Grafana. (<b><code>  6744⭐</code></b> <b><code>  1153🍴</code></b> [Source Code](https://github.com/mermaid-js/mermaid-live-editor) ⭐ 6,752 | 🐛 89 | 🌐 TypeScript | 📅 2026-08-14)) `MIT` `Nodejs/Docker`
* 🌎 [Kroki](kroki.io) - API for generating diagrams from textual descriptions. (<b><code>  4284⭐</code></b> <b><code>   310🍴</code></b> [Source Code](https://github.com/yuzutech/kroki) ⭐ 4,285 | 🐛 144 | 🌐 JavaScript | 📅 2026-08-15)) `MIT` `Java`

### Distributed Filesystems

**[`^        back to top        ^`](#awesome-sysadmin)**

Network distributed filesystems.

*See also: 🌎 [awesome-selfhosted/File Transfer - Object Storage & File Servers](awesome-selfhosted.net/tags/file-transfer---object-storage--file-servers.html)*

* <b><code> 17099⭐</code></b> <b><code>  3163🍴</code></b> [Kubo](https://github.com/ipfs/kubo) ⭐ 17,101 | 🐛 870 | 🌐 Go | 📅 2026-08-15) - Implementation of IPFS, a global, versioned, peer-to-peer filesystem that seeks to connect all computing devices with the same system of files. `Apache-2.0/MIT` `Go`
* 🌎 [Ceph](ceph.com/en/) - Distributed object, block, and file storage platform. (<b><code> 16931⭐</code></b> <b><code>  6476🍴</code></b> [Source Code](https://github.com/ceph/ceph) ⭐ 16,939 | 🐛 1,292 | 🌐 C++ | 📅 2026-08-15)) `LGPL-3.0` `C++`
* 🌎 [Hadoop Distributed Filesystem (HDFS)](hadoop.apache.org/) - Distributed file system that provides high-throughput access to application data. (<b><code> 15631⭐</code></b> <b><code>  9242🍴</code></b> [Source Code](https://github.com/apache/hadoop) ⭐ 15,630 | 🐛 200 | 🌐 Java | 📅 2026-08-15)) `Apache-2.0` `Java`
* 🌎 [JuiceFS](juicefs.com/) - Distributed POSIX file system built on top of Redis and S3. (<b><code> 14315⭐</code></b> <b><code>  1276🍴</code></b> [Source Code](https://github.com/juicedata/juicefs) ⭐ 14,323 | 🐛 189 | 🌐 Go | 📅 2026-08-14)) `Apache-2.0` `Go`
* 🌎 [Perkeep](perkeep.org/) - A set of open source formats, protocols, and software for modeling, storing, searching, sharing and synchronizing data (previously Camlistore). (<b><code>  7223⭐</code></b> <b><code>   489🍴</code></b> [Source Code](https://github.com/perkeep/perkeep) ⭐ 7,225 | 🐛 413 | 🌐 Go | 📅 2026-02-01)) `Apache-2.0` `C`
* 🌎 [GlusterFS](www.gluster.org/) - Software-defined distributed storage that can scale to several petabytes, with interfaces for object, block and file storage. (<b><code>  5217⭐</code></b> <b><code>  1108🍴</code></b> [Source Code](https://github.com/gluster/glusterfs) ⭐ 5,218 | 🐛 291 | 🌐 C | 📅 2026-02-16)) `GPL-2.0/LGPL-3.0` `C`
* 🌎 [MooseFS](moosefs.com/) - Fault tolerant, network distributed file system. (<b><code>  1996⭐</code></b> <b><code>   238🍴</code></b> [Source Code](https://github.com/moosefs/moosefs) ⭐ 1,996 | 🐛 190 | 🌐 C | 📅 2026-05-18)) `GPL-2.0` `C`
* 🌎 [LeoFS](leo-project.net) - Highly available, distributed, replicated eventually consistent object/blob store. (<b><code>  1593⭐</code></b> <b><code>   156🍴</code></b> [Source Code](https://github.com/leo-project/leofs) ⭐ 1,594 | 🐛 255 | 🌐 Erlang | 📅 2026-01-05)) `Apache-2.0` `Erlang`
* 🌎 [TahoeLAFS](tahoe-lafs.org/trac/tahoe-lafs) - Secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system. (<b><code>  1431⭐</code></b> <b><code>   262🍴</code></b> [Source Code](https://github.com/tahoe-lafs/tahoe-lafs) ⭐ 1,432 | 🐛 24 | 🌐 Python | 📅 2026-01-21)) `GPL-2.0` `Python`
* 🌎 [DRBD](linbit.com/drbd/) - Distributed replicated storage system, implemented as a Linux kernel driver. (<b><code>   717⭐</code></b> <b><code>   116🍴</code></b> [Source Code](https://github.com/LINBIT/drbd) ⭐ 717 | 🐛 38 | 🌐 C | 📅 2026-08-12)) `GPL-2.0` `C`
* 🌎 [XtreemFS](www.xtreemfs.org/) - Distributed, replicated and fault-tolerant file system for federated IT infrastructures.. (<b><code>   348⭐</code></b> <b><code>    65🍴</code></b> [Source Code](https://github.com/xtreemfs/xtreemfs) ⭐ 348 | 🐛 69 | 🌐 Java | 📅 2024-10-07)) `BSD-3-Clause` `Java`
* 🌎 [Lustre](www.lustre.org/) - Parallel distributed file system, generally used for large-scale cluster computing.  🌎 [Source Code](git.whamcloud.com/?p=fs/lustre-release.git;a=summary)) `GPL-2.0` `C`
* 🌎 [OpenAFS](www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.  🌎 [Source Code](git.openafs.org/?p=openafs.git;a=summary)) `IPL-1.0` `C`
* 🌎 [Openstack Swift](docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.  🌎 [Source Code](opendev.org/openstack/swift)) `Apache-2.0` `Python`

### DNS - Control Panels & Domain Management

**[`^        back to top        ^`](#awesome-sysadmin)**

DNS server control panels, web interfaces and domain management tools.

*Related: [DNS - Servers](#dns---servers)*

*See also: 🌎 [awesome-selfhosted/DNS](awesome-selfhosted.net/tags/dns.html)*

* 🌎 [DNSControl](dnscontrol.org/) - Synchronize your DNS to multiple providers from a simple DSL. (<b><code>  3900⭐</code></b> <b><code>   525🍴</code></b> [Source Code](https://github.com/DNSControl/dnscontrol) ⭐ 3,902 | 🐛 45 | 🌐 Go | 📅 2026-08-13)) `MIT` `Go/Docker`
* <b><code>  3744⭐</code></b> <b><code>   440🍴</code></b> [octoDNS](https://github.com/octodns/octodns) ⭐ 3,745 | 🐛 5 | 🌐 Python | 📅 2026-08-15) - DNS as code - Tools for managing DNS across multiple providers. `MIT` `Python`
* 🌎 [nsupdate.info](www.nsupdate.info/) - Dynamic DNS service.  🌎 [Demo](www.nsupdate.info/account/register/), <b><code>  1131⭐</code></b> <b><code>   125🍴</code></b> [Source Code](https://github.com/nsupdate-info/nsupdate.info) ⭐ 1,131 | 🐛 55 | 🌐 Python | 📅 2026-08-09)) `BSD-3-Clause` `Python`
* 🌎 [Poweradmin](www.poweradmin.org/) - Web-based DNS control panel for PowerDNS server. (<b><code>   906⭐</code></b> <b><code>   296🍴</code></b> [Source Code](https://github.com/poweradmin/poweradmin) ⭐ 906 | 🐛 92 | 🌐 PHP | 📅 2026-08-15)) `GPL-3.0` `PHP`
* 🌎 [DomainMOD](domainmod.org) - Manage your domains and other internet assets in a central location. (<b><code>   596⭐</code></b> <b><code>   118🍴</code></b> [Source Code](https://github.com/domainmod/domainmod) ⭐ 596 | 🐛 17 | 🌐 PHP | 📅 2025-01-04)) `GPL-3.0` `PHP`
* 🌎 [SPF Toolbox](spftoolbox.com) - Application to look up DNS records such as SPF, MX, Whois, and more. (<b><code>   300⭐</code></b> <b><code>    66🍴</code></b> [Source Code](https://github.com/charlesabarnes/SPFtoolbox) ⭐ 300 | 🐛 10 | 🌐 PHP | 📅 2026-02-13)) `MIT` `PHP`
* 🌎 [Designate](wiki.openstack.org/wiki/Designate) - DNSaaS services for OpenStack.  🌎 [Source Code](opendev.org/openstack/designate)) `Apache-2.0` `Python`

### DNS - Servers

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [DNS](en.wikipedia.org/wiki/Name_server) servers.

*Related: [DNS - Control Panels & Domain Management](#dns---control-panels--domain-management)*

*See also: 🌎 [awesome-selfhosted/DNS](awesome-selfhosted.net/tags/dns.html)*

* 🌎 [CoreDNS](coredns.io/) - Flexible DNS server. (<b><code> 14244⭐</code></b> <b><code>  2511🍴</code></b> [Source Code](https://github.com/coredns/coredns) ⭐ 14,246 | 🐛 302 | 🌐 Go | 📅 2026-08-15)) `Apache-2.0` `Go`
* 🌎 [Unbound](nlnetlabs.nl/projects/unbound/about/) - Validating, recursive, and caching DNS resolver. (<b><code>  4782⭐</code></b> <b><code>   448🍴</code></b> [Source Code](https://github.com/NLnetLabs/unbound) ⭐ 4,788 | 🐛 378 | 🌐 C | 📅 2026-08-11)) `BSD-3-Clause` `C`
* 🌎 [PowerDNS Authoritative Server](doc.powerdns.com/authoritative/) - Versatile nameserver which supports a large number of backends. (<b><code>  4445⭐</code></b> <b><code>  1020🍴</code></b> [Source Code](https://github.com/PowerDNS/pdns) ⭐ 4,445 | 🐛 935 | 🌐 C++ | 📅 2026-08-13)) `GPL-2.0` `C++`
* 🌎 [NSD](www.nlnetlabs.nl/projects/nsd/about/) - Authoritative DNS name server developed speed, reliability, stability and security. (<b><code>   569⭐</code></b> <b><code>   122🍴</code></b> [Source Code](https://github.com/NLnetLabs/nsd) ⭐ 569 | 🐛 74 | 🌐 C | 📅 2026-08-14)) `BSD-3-Clause` `C`
* 🌎 [Yadifa](www.yadifa.eu/) - Clean, small, light and RFC-compliant name server implementation developed from scratch by .eu. (<b><code>    81⭐</code></b> <b><code>    15🍴</code></b> [Source Code](https://github.com/yadifa/yadifa) ⭐ 81 | 🐛 10 | 🌐 C | 📅 2026-03-24)) `BSD-3-Clause` `C`
* 🌎 [Bind](www.isc.org/bind/) - Versatile, classic, complete name server software.  🌎 [Source Code](gitlab.isc.org/isc-projects/bind9)) `MPL-2.0` `C`
* 🌎 [djbdns](cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.  🌎 [Source Code](salsa.debian.org/debian/djbdns)) `CC0-1.0` `C`
* 🌎 [dnsmasq](www.thekelleys.org.uk/dnsmasq/doc.html) - Provides network infrastructure for small networks: DNS, DHCP, router advertisement and network boot.  🌎 [Source Code](thekelleys.org.uk/gitweb/?p=dnsmasq.git;a=tree)) `GPL-2.0` `C`
* 🌎 [Knot](www.knot-dns.cz/) - High performance authoritative-only DNS server.  🌎 [Source Code](gitlab.nic.cz/knot/knot-dns)) `GPL-3.0` `C`

### Editors

**[`^        back to top        ^`](#awesome-sysadmin)**

Open-source code editors.

* 🌎 [Vim](www.vim.org) - A highly configurable text editor built to enable efficient editing. (<b><code> 40737⭐</code></b> <b><code>  6116🍴</code></b> [Source Code](https://github.com/vim/vim) ⭐ 40,739 | 🐛 1,641 | 🌐 Vim Script | 📅 2026-08-15)) `Vim` `C`
* 🌎 [VSCodium](vscodium.com/) - An open source cross-platform extensible code editor based on 🌎 [VS Code by Microsoft](code.visualstudio.com/) removing their non-free additions. (<b><code> 32813⭐</code></b> <b><code>  1846🍴</code></b> [Source Code](https://github.com/VSCodium/vscodium) ⭐ 32,832 | 🐛 139 | 🌐 Shell | 📅 2026-08-12)) `MIT` `TypeScript`
* 🌎 [Micro](micro-editor.github.io/) - A modern and intuitive terminal-based text editor. (<b><code> 29333⭐</code></b> <b><code>  1346🍴</code></b> [Source Code](https://github.com/micro-editor/micro) ⭐ 29,345 | 🐛 1,033 | 🌐 Go | 📅 2026-08-16)) `MIT` `Go`
* 🌎 [Notepad++](notepad-plus-plus.org/) - GPLv2 multi-language editor with syntax highlighting for Windows. (<b><code> 29006⭐</code></b> <b><code>  5326🍴</code></b> [Source Code](https://github.com/notepad-plus-plus/notepad-plus-plus) ⭐ 29,023 | 🐛 2,913 | 🌐 C++ | 📅 2026-08-13)) `GPL-2.0` `C++`
* 🌎 [TextMate](macromates.com/) - A graphical text editor for OS X. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/textmate/textmate/) ⭐ 14,576 | 🐛 22 | 🌐 Objective-C++ | 📅 2024-05-18)) `GPL-3.0` `C++`
* 🌎 [GNU Emacs](www.gnu.org/software/emacs/) - An extensible, customizable text editor-and more. (<b><code>  5149⭐</code></b> <b><code>  1395🍴</code></b> [Source Code](https://github.com/emacs-mirror/emacs) ⭐ 5,152 | 🐛 16 | 🌐 Emacs Lisp | 📅 2026-08-16)) `GPL-3.0` `C`
* 🌎 [Geany](www.geany.org/) - GTK2 text editor. (<b><code>  3693⭐</code></b> <b><code>   668🍴</code></b> [Source Code](https://github.com/geany/geany) ⭐ 3,694 | 🐛 1,269 | 🌐 C | 📅 2026-08-03)) `GPL-2.0` `C/C++`
* [Haroopad](http://pad.haroopress.com/) - Markdown editor with live preview. (<b><code>  1678⭐</code></b> <b><code>   221🍴</code></b> [Source Code](https://github.com/rhiokim/haroopad) ⭐ 1,678 | 🐛 224 | 🌐 JavaScript | 📅 2018-12-04)) `GPL-3.0` `JavaScript`
* 🌎 [Brackets](brackets.io/) - Code editor for web designers and front-end developers. (<b><code>  1513⭐</code></b> <b><code>   195🍴</code></b> [Source Code](https://github.com/brackets-cont/brackets) ⭐ 1,512 | 🐛 78 | 🌐 JavaScript | 📅 2026-03-30)) `MIT` `JavaScript`
* <b><code>   780⭐</code></b> <b><code>    31🍴</code></b> [Atom Community](https://github.com/atom-community/atom) ⭐ 780 | 🐛 52 | 🌐 JavaScript | 📅 2025-08-19) - A fork of <b><code> 60796⭐</code></b> <b><code> 17167🍴</code></b> [atom](https://github.com/atom/atom) ⚠️ Archived) A hackable text editor from Github. `MIT` `JavaScript`
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

* <b><code>  6434⭐</code></b> <b><code>   347🍴</code></b> [lldap](https://github.com/lldap/lldap) ⭐ 6,439 | 🐛 119 | 🌐 Rust | 📅 2026-08-10) - Light (simplified) LDAP implementation with a simple, intuitive web interface and GraphQL support. `GPL-3.0` `Rust`
* 🌎 [FreeRADIUS](freeradius.org/) - Multi-protocol policy server (radiusd) that implements RADIUS, DHCP, BFD, and ARP and associated client/PAM library/Apache module. (<b><code>  2570⭐</code></b> <b><code>  1197🍴</code></b> [Source Code](https://github.com/FreeRADIUS/freeradius-server) ⭐ 2,570 | 🐛 90 | 🌐 C | 📅 2026-08-15)) `GPL-2.0` `C`
* 🌎 [LTB Self-Service Password](www.ltb-project.org/documentation/self-service-password.html) - Web interface to change and reset LDAP passwords. (<b><code>  1332⭐</code></b> <b><code>   353🍴</code></b> [Source Code](https://github.com/ltb-project/self-service-password) ⭐ 1,332 | 🐛 70 | 🌐 PHP | 📅 2026-08-04)) `GPL-3.0` `PHP`
* 🌎 [389 Directory Server](www.port389.org/) - Enterprise-class Open Source LDAP server for Linux. (<b><code>   291⭐</code></b> <b><code>   121🍴</code></b> [Source Code](https://github.com/389ds/389-ds-base) ⭐ 291 | 🐛 414 | 🌐 C | 📅 2026-08-14)) `GPL-3.0` `C`
* 🌎 [Apache Directory Server](directory.apache.org/apacheds/) - Extensible and embeddable directory server, certified LDAPv3 compatible, with Kerberos 5 and Change Password Protocol support, triggers, stored procedures, queues and views. (<b><code>   188⭐</code></b> <b><code>   102🍴</code></b> [Source Code](https://github.com/apache/directory-server) ⭐ 188 | 🐛 14 | 🌐 Java | 📅 2026-08-10)) `Apache-2.0` `Java`
* 🌎 [FreeIPA](www.freeipa.org/) - Integrated security information management solution combining Linux (Fedora), 389 Directory Server, Kerberos, NTP, DNS, and Dogtag Certificate System (web interface and command-line administration tools).  🌎 [Source Code](pagure.io/freeipa)) `GPL-3.0` `Python/C/JavaScript`
* 🌎 [OpenLDAP](www.openldap.org/) - Open-source implementation of the Lightweight Directory Access Protocol (server, libraries and clients).  🌎 [Source Code](git.openldap.org/openldap/openldap)) `OLDAP-2.8` `C`

### Identity Management - Single Sign-On (SSO)

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Single sign-on (SSO)](en.wikipedia.org/wiki/Single_sign-on) is an authentication scheme that allows a user to log in with a single ID to any of several related, yet independent, software systems.

* 🌎 [KeyCloak](www.keycloak.org) - Open Source Identity and Access Management. (<b><code> 36174⭐</code></b> <b><code>  8785🍴</code></b> [Source Code](https://github.com/keycloak/keycloak) ⭐ 36,198 | 🐛 3,134 | 🌐 Java | 📅 2026-08-16)) `Apache-2.0` `Java`
* 🌎 [Authelia](www.authelia.com/) - The Single Sign-On Multi-Factor portal for web apps. (<b><code> 28548⭐</code></b> <b><code>  1459🍴</code></b> [Source Code](https://github.com/authelia/authelia) ⭐ 28,570 | 🐛 126 | 🌐 Go | 📅 2026-08-16)) `Apache-2.0` `Go`
* 🌎 [Authentik](goauthentik.io/) - Flexible identity provider with support for different protocols. (OAuth 2.0, SAML, LDAP and Radius). (<b><code> 24766⭐</code></b> <b><code>  1900🍴</code></b> [Source Code](https://github.com/goauthentik/authentik) ⭐ 24,843 | 🐛 1,168 | 🌐 Python | 📅 2026-08-15)) `MIT` `Python`

### Identity Management - Tools and web interfaces

**[`^        back to top        ^`](#awesome-sysadmin)**

Miscellaneous utilities and web interfaces for identity management systems.

* 🌎 [ZITADEL](zitadel.com/) - Cloud-native Identity & Access Management solution providing a platform for secure authentication, authorization and identity management. (<b><code> 14720⭐</code></b> <b><code>  1220🍴</code></b> [Source Code](https://github.com/zitadel/zitadel) ⭐ 14,731 | 🐛 1,118 | 🌐 Go | 📅 2026-08-14)) `Apache-2.0` `Go/Docker/K8S`
* 🌎 [Smallstep Certificates](smallstep.com/certificates/) - A private certificate authority (X.509 & SSH) and related tools for secure automated certificate management. (<b><code>  8749⭐</code></b> <b><code>   573🍴</code></b> [Source Code](https://github.com/smallstep/certificates) ⭐ 8,749 | 🐛 287 | 🌐 Go | 📅 2026-08-13)) `Apache-2.0` `Go`
* 🌎 [Pomerium](www.pomerium.io/) - An identity and context aware access-proxy inspired by BeyondCorp. (<b><code>  4954⭐</code></b> <b><code>   345🍴</code></b> [Source Code](https://github.com/pomerium/pomerium) ⭐ 4,956 | 🐛 146 | 🌐 Go | 📅 2026-08-15)) `Apache-2.0` `Docker/Go`
* <b><code>  4472⭐</code></b> <b><code>  1228🍴</code></b> [easy-rsa](https://github.com/OpenVPN/easy-rsa) ⭐ 4,473 | 🐛 18 | 🌐 Shell | 📅 2026-07-25) - Bash script to build and manage a PKI CA. `GPL-2.0` `Shell`
* 🌎 [LDAP Account Manager (LAM)](www.ldap-account-manager.org/lamcms/) - Web frontend for managing entries (e.g. users, groups, DHCP settings) stored in an LDAP directory. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/LDAPAccountManager/lam/) ⭐ 487 | 🐛 22 | 🌐 PHP | 📅 2026-08-14)) `GPL-3.0` `PHP`
* 🌎 [Fusion Directory](www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP. (<b><code>   189⭐</code></b> <b><code>    37🍴</code></b> [Source Code](https://github.com/fusiondirectory/fusiondirectory) ⭐ 189 | 🐛 2 | 🌐 PHP | 📅 2026-08-11)) `GPL-2.0` `PHP`
* 🌎 [BounCA](bounca.org/) - A personal SSL Key / Certificate Authority web-based tool for creating self-signed certificates.  🌎 [Source Code](gitlab.com/bounca/bounca/)) `Apache-2.0` `Python`
* 🌎 [Libravatar](www.libravatar.org/) - Libravatar is a service which delivers your avatar (profile picture) to other websites.  🌎 [Source Code](git.linux-kernel.at/oliver/ivatar/)) `AGPL-3.0` `Python`
* 🌎 [Samba](www.samba.org/) - Active Directory and CIFS protocol implementation.  🌎 [Source Code](download.samba.org/pub/samba/)) `GPL-3.0` `C`

### IT Asset Management

**[`^        back to top        ^`](#awesome-sysadmin)**

IT 🌎 [asset management](en.wikipedia.org/wiki/Asset_management) software.

* 🌎 [Snipe IT](snipeitapp.com/) - Asset & license management software. (<b><code> 14810⭐</code></b> <b><code>  3959🍴</code></b> [Source Code](https://github.com/grokability/snipe-it) ⭐ 14,819 | 🐛 942 | 🌐 PHP | 📅 2026-08-15)) `AGPL-3.0` `PHP`
* 🌎 [GLPI](www.glpi-project.org/) - Information Resource-Manager with an additional Administration Interface. (<b><code>  6224⭐</code></b> <b><code>  1771🍴</code></b> [Source Code](https://github.com/glpi-project/glpi) ⭐ 6,228 | 🐛 497 | 🌐 PHP | 📅 2026-08-14)) `GPL-3.0` `PHP`
* 🌎 [Ralph](ralph.allegro.tech/) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks. (<b><code>  2512⭐</code></b> <b><code>   591🍴</code></b> [Demo](https://github.com/allegro/ralph#live-demo) ⭐ 2,515 | 🐛 122 | 🌐 Python | 📅 2026-08-13), <b><code>  2512⭐</code></b> <b><code>   591🍴</code></b> [Source Code](https://github.com/allegro/ralph) ⭐ 2,515 | 🐛 122 | 🌐 Python | 📅 2026-08-13)) `Apache-2.0` `Python/Docker`
* 🌎 [RackTables](racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration.  🌎 [Demo](www.racktables.org/demo.php), <b><code>   811⭐</code></b> <b><code>   269🍴</code></b> [Source Code](https://github.com/RackTables/racktables) ⭐ 811 | 🐛 23 | 🌐 PHP | 📅 2026-06-26)) `GPL-2.0` `PHP`
* 🌎 [openDCIM](opendcim.org/) - GPL v3 Data Center Inventory Management (DCIM).  🌎 [Demo](opendcim.org/demo.html), <b><code>   362⭐</code></b> <b><code>   218🍴</code></b> [Source Code](https://github.com/opendcim/openDCIM) ⭐ 362 | 🐛 126 | 🌐 PHP | 📅 2026-08-14)) `GPL-3.0` `PHP/JavaScript`
* 🌎 [OCS Inventory NG](ocsinventory-ng.org/) - Asset management and deployment solution for all devices in your IT Department. ([Source Code](https://github.com/OCSInventory-NG)) `GPL-2.0` `PHP/Perl`
* 🌎 [OPSI](www.opsi.org) - Hardware and software inventory, client management, deployment, and patching for Linux and Windows. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/opsi-org/))) `GPL-3.0/AGPL-3.0` `OVF/Python`

### Log Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Log management tools: collect, parse, visualize...

* 🌎 [Loki](grafana.com/oss/loki/) - Log aggregation system designed to store and query logs from all your applications and infrastructure. (<b><code> 28725⭐</code></b> <b><code>  4091🍴</code></b> [Source Code](https://github.com/grafana/loki) ⭐ 28,744 | 🐛 1,767 | 🌐 Go | 📅 2026-08-16)) `AGPL-3.0` `Go`
* 🌎 [GoAccess](goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal or through the browser. (<b><code> 20802⭐</code></b> <b><code>  1190🍴</code></b> [Source Code](https://github.com/allinurl/goaccess) ⭐ 20,822 | 🐛 455 | 🌐 C | 📅 2026-08-05)) `MIT` `C`
* 🌎 [Fluentd](www.fluentd.org/) - Data collector for unified logging layer. (<b><code> 13578⭐</code></b> <b><code>  1403🍴</code></b> [Source Code](https://github.com/fluent/fluentd) ⭐ 13,579 | 🐛 138 | 🌐 Ruby | 📅 2026-08-16)) `Apache-2.0` `Ruby`
* 🌎 [Flume](flume.apache.org/) - Distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data. (<b><code>  2565⭐</code></b> <b><code>  1543🍴</code></b> [Source Code](https://github.com/apache/logging-flume) ⭐ 2,565 | 🐛 79 | 🌐 Java | 📅 2026-08-01)) `Apache-2.0` `Java`
* 🌎 [rsyslog](www.rsyslog.com/) - Rocket-fast system for log processing. (<b><code>  2326⭐</code></b> <b><code>   730🍴</code></b> [Source Code](https://github.com/rsyslog/rsyslog) ⭐ 2,326 | 🐛 186 | 🌐 C | 📅 2026-08-13)) `GPL-3.0` `C`
* 🌎 [reaction](reaction.ppom.me/) - A lightweight daemon that scans program outputs for repeated patterns, and takes action.  🌎 [Source Code](framagit.org/ppom/reaction)) `AGPL-3.0` `Rust`

### Mail Clients

**[`^        back to top        ^`](#awesome-sysadmin)**

An 🌎 [email client](en.wikipedia.org/wiki/Email_client), email reader or, more formally, message user agent (MUA) or mail user agent is a computer program used to access and manage a user's email.

* [ImapSync](http://imapsync.lamiral.info/) - Simple IMAP migration tool for copying mailboxes to other servers. (<b><code>  4123⭐</code></b> <b><code>   532🍴</code></b> [Source Code](https://github.com/imapsync/imapsync) ⭐ 4,123 | 🐛 191 | 🌐 Shell | 📅 2026-07-23)) `NLPL` `Perl`
* 🌎 [Sylpheed](sylpheed.sraoss.jp/en/) - Still developed predecessor to Claws Mail, lightweight mail client. (<b><code>   186⭐</code></b> <b><code>    23🍴</code></b> [Source Code](https://github.com/sylpheed-mail/sylpheed) ⭐ 186 | 🐛 67 | 🌐 C | 📅 2024-05-04)) `GPL-2.0` `C`
* 🌎 [aerc](aerc-mail.org/) - Terminal MUA with a focus on plaintext and features for developers.  🌎 [Source Code](git.sr.ht/~rjarry/aerc)) `MIT` `Go`
* [Claws Mail](http://www.claws-mail.org/) - Old school email client (and news reader), based on GTK+.  🌎 [Source Code](git.claws-mail.org/?p=claws.git;a=tree)) `GPL-3.0` `C`
* [Mutt](http://www.mutt.org/) - Small but very powerful text-based mail client.  🌎 [Source Code](gitlab.com/muttmua/mutt)) `GPL-2.0` `C`
* 🌎 [Thunderbird](www.thunderbird.net/) - Free email application that's easy to set up and customize.  🌎 [Source Code](hg.mozilla.org/comm-central/file)) `MPL-2.0` `C/C++`

### Metrics & Metric Collection

**[`^        back to top        ^`](#awesome-sysadmin)**

Metric gathering and display software.

*Related: [Databases](#databases), [Monitoring & Status Pages](#monitoring--status-pages)*

* 🌎 [Grafana](grafana.com/) - A Graphite & InfluxDB Dashboard and Graph Editor. (<b><code> 76296⭐</code></b> <b><code> 14565🍴</code></b> [Source Code](https://github.com/grafana/grafana) ⭐ 76,283 | 🐛 3,371 | 🌐 TypeScript | 📅 2026-08-16)) `AGPL-3.0` `Go`
* <b><code> 18069⭐</code></b> <b><code>  1938🍴</code></b> [Statsd](https://github.com/statsd/statsd) ⭐ 18,070 | 🐛 90 | 🌐 JavaScript | 📅 2025-05-20) - Daemon that listens for statistics like counters and timers, sent over UDP or TCP, and sends aggregates to one or more pluggable backend services. `MIT` `Nodejs`
* <b><code> 17750⭐</code></b> <b><code>  5834🍴</code></b> [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,753 | 🐛 386 | 🌐 Go | 📅 2026-08-14) - Plugin-driven server agent for collecting, processing, aggregating, and writing metrics. `MIT` `Go`
* 🌎 [VictoriaMetrics](victoriametrics.com/) - Fast, cost-effective time series database and monitoring solution; drop-in replacement for Prometheus with PromQL/MetricsQL support. (<b><code> 17526⭐</code></b> <b><code>  1714🍴</code></b> [Source Code](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 17,538 | 🐛 774 | 🌐 Go | 📅 2026-08-15)) `Apache-2.0` `Go`
* 🌎 [Beats](www.elastic.co/beats/) - Single-purpose data shippers that send data from hundreds or thousands of machines and systems to Logstash or Elasticsearch. (<b><code> 12640⭐</code></b> <b><code>  5009🍴</code></b> [Source Code](https://github.com/elastic/beats) ⭐ 12,638 | 🐛 1,042 | 🌐 Go | 📅 2026-08-14)) `Apache-2.0` `Go`
* 🌎 [Graphite](graphite.readthedocs.org/en/latest/) - Scalable graphing server. (<b><code>  6105⭐</code></b> <b><code>  1254🍴</code></b> [Source Code](https://github.com/graphite-project/graphite-web) ⭐ 6,105 | 🐛 23 | 🌐 JavaScript | 📅 2026-08-10)) `Apache-2.0` `Python`
* 🌎 [Collectd](collectd.org/) - System statistics collection daemon. (<b><code>  3366⭐</code></b> <b><code>  1248🍴</code></b> [Source Code](https://github.com/collectd/collectd) ⭐ 3,366 | 🐛 785 | 🌐 C | 📅 2026-05-29)) `MIT` `C`
* <b><code>  1757⭐</code></b> <b><code>   594🍴</code></b> [Diamond](https://github.com/python-diamond/Diamond) ⭐ 1,757 | 🐛 122 | 🌐 Python | 📅 2024-06-29) - Daemon that collects system metrics and publishes them to Graphite (and others). `MIT` `Python`
* 🌎 [RRDtool](oss.oetiker.ch/rrdtool/) - Industry standard, high performance data logging and graphing system for time series data. (<b><code>  1114⭐</code></b> <b><code>   285🍴</code></b> [Source Code](https://github.com/oetiker/rrdtool-1.x) ⭐ 1,114 | 🐛 163 | 🌐 C | 📅 2026-08-07)) `GPL-2.0` `C`
* [tcollector](http://opentsdb.net/docs/build/html/user_guide/utilities/tcollector.html) - Gathers data from local collectors and pushes the data to OpenTSDB. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/OpenTSDB/tcollector/) ⭐ 510 | 🐛 25 | 🌐 Python | 📅 2024-06-10)) `LGPL-3.0/GPL-3.0` `Python`

### Miscellaneous

**[`^        back to top        ^`](#awesome-sysadmin)**

Software that does not fit in another section.

* 🌎 [Chocolatey](chocolatey.org/) - The package manager for Windows. (<b><code> 11485⭐</code></b> <b><code>   962🍴</code></b> [Source Code](https://github.com/chocolatey/choco) ⭐ 11,484 | 🐛 515 | 🌐 C# | 📅 2026-08-05)) `Apache-2.0` `C#/PowerShell`
* 🌎 [Fog](www.fogproject.org/) - Cloning/imaging solution/rescue suite. (<b><code>  1619⭐</code></b> <b><code>   283🍴</code></b> [Source Code](https://github.com/FOGProject/fogproject) ⭐ 1,621 | 🐛 49 | 🌐 PHP | 📅 2026-08-16)) `GPL-3.0` `PHP/Shell`
* 🌎 [phpList](www.phplist.org/) - Newsletter and email marketing software. (<b><code>   866⭐</code></b> <b><code>   286🍴</code></b> [Source Code](https://github.com/phpList/phplist3) ⭐ 868 | 🐛 90 | 🌐 PHP | 📅 2026-08-14)) `AGPL-3.0` `PHP`
* 🌎 [Clonezilla](clonezilla.org/) - Partition and disk imaging/cloning program.  🌎 [Source Code](clonezilla.org/downloads/src/)) `GPL-2.0` `Perl/Shell/Other`
* 🌎 [DadaMail](dadamailproject.com/) - Mailing List Manager, written in Perl.  🌎 [Source Code](sourceforge.net/projects/dadamail/files/)) `GPL-2.0` `Perl`

### Monitoring & Status Pages

**[`^        back to top        ^`](#awesome-sysadmin)**

Monitoring software.

*Related: [Metrics & Metric Collection](#metrics--metric-collection)*

* 🌎 [Uptime Kuma](uptime.kuma.pet/) - Modern, self-hosted monitoring tool with a clean UI and rich notification support. (<b><code> 90160⭐</code></b> <b><code>  8241🍴</code></b> [Source Code](https://github.com/louislam/uptime-kuma) ⭐ 90,206 | 🐛 789 | 🌐 JavaScript | 📅 2026-08-16)) `MIT` `Nodejs`
* 🌎 [Prometheus](prometheus.io/) - Service monitoring system and time series database. (<b><code> 65733⭐</code></b> <b><code> 10773🍴</code></b> [Source Code](https://github.com/prometheus/prometheus) ⭐ 65,711 | 🐛 889 | 🌐 Go | 📅 2026-08-15)) `Apache-2.0` `Go`
* 🌎 [glances](nicolargo.github.io/glances/) - Open-source, cross-platform real-time monitoring tool with CLI and web dashboard interfaces and many exporting options. (<b><code> 33354⭐</code></b> <b><code>  1790🍴</code></b> [Source Code](https://github.com/nicolargo/glances) ⭐ 33,376 | 🐛 106 | 🌐 Python | 📅 2026-08-15)) `GPL-3.0` `Python`
* 🌎 [Beszel](beszel.dev/) - Lightweight server monitoring platform that includes Docker statistics, historical data, and alert functions. (<b><code> 24241⭐</code></b> <b><code>   954🍴</code></b> [Source Code](https://github.com/henrygd/beszel) ⭐ 24,284 | 🐛 335 | 🌐 Go | 📅 2026-08-16)) `MIT` `Go`
* <b><code> 19356⭐</code></b> <b><code>  2483🍴</code></b> [cadvisor](https://github.com/google/cadvisor) ⭐ 19,357 | 🐛 66 | 🌐 Go | 📅 2026-07-20) - Analyzes resource usage and performance characteristics of running containers. `Apache-2.0` `Go`
* 🌎 [Wazuh](wazuh.com/) - Unified XDR and SIEM protection for endpoints and cloud workloads. (<b><code> 16523⭐</code></b> <b><code>  2433🍴</code></b> [Source Code](https://github.com/wazuh/wazuh) ⭐ 16,537 | 🐛 2,977 | 🌐 C++ | 📅 2026-08-16)) `GPL-2.0` `C`
* 🌎 [Gatus](gatus.io) - Automated service health dashboard.  🌎 [Demo](status.twin.sh), <b><code> 11806⭐</code></b> <b><code>   796🍴</code></b> [Source Code](https://github.com/TwiN/gatus) ⭐ 11,818 | 🐛 361 | 🌐 Go | 📅 2026-08-15)) `Apache-2.0` `Docker/K8S`
* <b><code> 10581⭐</code></b> <b><code>  1188🍴</code></b> [Linux Dash](https://github.com/tariqbuilds/linux-dash) ⭐ 10,581 | 🐛 45 | 🌐 JavaScript | 📅 2024-04-16) - A low-overhead monitoring web dashboard for a GNU/Linux machine. `MIT` `Nodejs/Go/Python/PHP`
* 🌎 [Nezha](nezha.wiki/en_US/) - Lightweight, servers & websites monitoring and O\&M tool. (<b><code> 10271⭐</code></b> <b><code>  1607🍴</code></b> [Source Code](https://github.com/nezhahq/nezha) ⭐ 10,270 | 🐛 55 | 🌐 Go | 📅 2026-08-15)) `Apache-2.0` `Go/Shell`
* 🌎 [Healthchecks](healthchecks.io/docs/self_hosted/) - Monitoring for cron jobs, background services and scheduled tasks. (<b><code> 10240⭐</code></b> <b><code>   998🍴</code></b> [Source Code](https://github.com/healthchecks/healthchecks) ⭐ 10,245 | 🐛 53 | 🌐 Python | 📅 2026-08-11)) `BSD-3-Clause` `Python`
* <b><code>  8076⭐</code></b> <b><code>   292🍴</code></b> [Scrutiny](https://github.com/AnalogJ/scrutiny) ⭐ 8,082 | 🐛 44 | 🌐 Go | 📅 2026-08-11) - Web UI for hard drive S.M.A.R.T monitoring, historical trends & real-world failure thresholds. `MIT` `Go`
* 🌎 [OneUptime](oneuptime.com) - A comprehensive solution for monitoring and managing your online services. (<b><code>  7458⭐</code></b> <b><code>   431🍴</code></b> [Source Code](https://github.com/oneuptime/oneuptime) ⭐ 7,465 | 🐛 287 | 🌐 TypeScript | 📅 2026-08-16)) `Apache-2.0` `Docker`
* 🌎 [Kener](kener.ing/) - Status page with incident management, easy to use and customize. (<b><code>  5100⭐</code></b> <b><code>   288🍴</code></b> [Source Code](https://github.com/rajnandan1/kener) ⭐ 5,107 | 🐛 73 | 🌐 Svelte | 📅 2026-08-03)) `MIT` `Nodejs/Docker`
* 🌎 [LibreNMS](www.librenms.org) - Fully featured network monitoring system that provides a wealth of features and device support. (<b><code>  4834⭐</code></b> <b><code>  2762🍴</code></b> [Source Code](https://github.com/librenms/librenms) ⭐ 4,836 | 🐛 203 | 🌐 PHP | 📅 2026-08-15)) `GPL-3.0` `PHP`
* 🌎 [Riemann](riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis. (<b><code>  4267⭐</code></b> <b><code>   504🍴</code></b> [Source Code](https://github.com/riemann/riemann) ⭐ 4,267 | 🐛 29 | 🌐 Clojure | 📅 2026-04-05)) `EPL-1.0` `Java`
* <b><code>  3515⭐</code></b> <b><code>   133🍴</code></b> [dashdot](https://github.com/MauriceNino/dashdot) ⭐ 3,515 | 🐛 57 | 🌐 TypeScript | 📅 2026-08-15) - A simple, modern server dashboard for smaller private servers.  🌎 [Demo](dash.mauz.dev/)) `MIT` `Nodejs/Docker`
* 🌎 [CheckCle](checkcle.io) - Seamless, real-time monitoring of full-stack systems, applications, and infrastructure. (<b><code>  2926⭐</code></b> <b><code>   251🍴</code></b> [Source Code](https://github.com/operacle/checkcle) ⭐ 2,930 | 🐛 92 | 🌐 Go | 📅 2026-07-17)) `MIT` `Docker`
* 🌎 [cState](cstate.uncascade.com/) - Static status page for hyperfast Hugo. Clean design, minimal JS, super light HTML/CSS, high customization, optional admin panel, read-only API, IE8+.  🌎 [Demo](cstate.mnts.lt/), <b><code>  2895⭐</code></b> <b><code>   250🍴</code></b> [Source Code](https://github.com/cstate/cstate) ⭐ 2,895 | 🐛 11 | 🌐 HTML | 📅 2026-06-26)) `MIT` `HTML`
* 🌎 [Alerta](alerta.io/) - Distributed, scalable and flexible monitoring system. (<b><code>  2527⭐</code></b> <b><code>   372🍴</code></b> [Source Code](https://github.com/alerta/alerta) ⭐ 2,527 | 🐛 31 | 🌐 Python | 📅 2026-06-19)) `Apache-2.0` `Python`
* 🌎 [checkmk](checkmk.com/) - Comprehensive solution for monitoring of applications, servers, and networks. (<b><code>  2341⭐</code></b> <b><code>   554🍴</code></b> [Source Code](https://github.com/Checkmk/checkmk) ⭐ 2,340 | 🐛 48 | 🌐 Python | 📅 2026-08-15)) `GPL-2.0` `Python/PHP`
* 🌎 [Icinga](www.icinga.com/) - Nagios fork that has since lapped nagios several times. Comes with the possibility of clustered monitoring. (<b><code>  2231⭐</code></b> <b><code>   617🍴</code></b> [Source Code](https://github.com/Icinga/icinga2) ⭐ 2,231 | 🐛 489 | 🌐 C++ | 📅 2026-08-13)) `GPL-2.0` `C++`
* 🌎 [PHP Server Monitor](www.phpservermonitor.org/) - Open source tool to monitor your servers and websites. (<b><code>  2188⭐</code></b> <b><code>   685🍴</code></b> [Source Code](https://github.com/phpservermon/phpservermon) ⭐ 2,188 | 🐛 20 | 🌐 JavaScript | 📅 2025-04-23)) `GPL-3.0` `PHP`
* <b><code>  2189⭐</code></b> <b><code>   155🍴</code></b> [rtop](https://github.com/rapidloop/rtop) ⭐ 2,188 | 🐛 23 | 🌐 Go | 📅 2022-06-06) - Interactive, remote system monitoring tool based on SSH. `MIT` `Go`
* 🌎 [Munin](munin-monitoring.org/) - Networked resource monitoring tool. (<b><code>  2136⭐</code></b> <b><code>   482🍴</code></b> [Source Code](https://github.com/munin-monitoring/munin) ⭐ 2,136 | 🐛 217 | 🌐 Perl | 📅 2026-08-09)) `GPL-2.0` `Perl/Shell`
* 🌎 [Nagios](www.nagios.org/) - Computer system, network and infrastructure monitoring software application. (<b><code>  2039⭐</code></b> <b><code>   478🍴</code></b> [Source Code](https://github.com/NagiosEnterprises/nagioscore) ⭐ 2,039 | 🐛 206 | 🌐 C | 📅 2026-08-07)) `GPL-2.0` `C`
* 🌎 [Cacti](www.cacti.net) - Web-based network monitoring and graphing tool. (<b><code>  1855⭐</code></b> <b><code>   443🍴</code></b> [Source Code](https://github.com/Cacti/cacti) ⭐ 1,855 | 🐛 373 | 🌐 PHP | 📅 2026-08-16)) `GPL-2.0` `PHP`
* 🌎 [tirreno](www.tirreno.com/) - Application-level security to protect your app from threats, fraud, and abuse.  🌎 [Demo](play.tirreno.com/), <b><code>  1495⭐</code></b> <b><code>   177🍴</code></b> [Source Code](https://github.com/tirrenotechnologies/tirreno) ⭐ 1,496 | 🐛 7 | 🌐 PHP | 📅 2026-08-14)) `AGPL-3.0` `PHP/Docker`
* 🌎 [PhpSysInfo](phpsysinfo.github.io/phpsysinfo/) - A customizable PHP script that displays information about your system nicely. (<b><code>  1417⭐</code></b> <b><code>   237🍴</code></b> [Source Code](https://github.com/phpsysinfo/phpsysinfo) ⭐ 1,417 | 🐛 3 | 🌐 PHP | 📅 2026-08-02)) `GPL-2.0` `PHP`
* 🌎 [Sensu](sensu.io/) - Monitoring tool for ephemeral infrastructure and distributed applications. (<b><code>  1109⭐</code></b> <b><code>   180🍴</code></b> [Source Code](https://github.com/sensu/sensu-go) ⭐ 1,109 | 🐛 283 | 🌐 Go | 📅 2026-08-12)) `MIT` `Go`
* [Performance Co-Pilot](http://pcp.io) - Lightweight, distributed system performance and analysis framework. (<b><code>  1070⭐</code></b> <b><code>   269🍴</code></b> [Source Code](https://github.com/performancecopilot/pcp) ⭐ 1,071 | 🐛 181 | 🌐 C | 📅 2026-08-14)) `LGPL-2.1/GPL-2.0` `C`
* 🌎 [KuvaszUptime](kuvasz-uptime.dev) - Performant, stable uptime & SSL monitoring service with brandable status pages, IAC support, Prometheus integration and a complete REST API.  🌎 [Demo](kuvasz-uptime.dev/demo/), <b><code>   572⭐</code></b> <b><code>    36🍴</code></b> [Source Code](https://github.com/kuvasz-uptime/kuvasz) ⭐ 580 | 🐛 9 | 🌐 Kotlin | 📅 2026-08-14)) `Apache-2.0` `Docker`
* 🌎 [Thruk](www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, Icinga and Shinken. (<b><code>   442⭐</code></b> <b><code>   161🍴</code></b> [Source Code](https://github.com/sni/Thruk) ⭐ 442 | 🐛 97 | 🌐 Perl | 📅 2026-08-07)) `GPL-1.0` `Perl`
* 🌎 [NetXMS](www.netxms.org/) - Open Source network and infrastructure monitoring and management. (<b><code>   390⭐</code></b> <b><code>    74🍴</code></b> [Source Code](https://github.com/netxms/netxms) ⭐ 390 | 🐛 174 | 🌐 C++ | 📅 2026-08-15)) `LGPL-3.0/GPL-3.0` `Java/C++/C`
* 🌎 [openITCOCKPIT Community Edition](openitcockpit.io/) - Monitoring Suite featuring seamless integrations with Naemon, Checkmk, Grafana and more.  🌎 [Demo](demo.openitcockpit.io/), <b><code>   380⭐</code></b> <b><code>    62🍴</code></b> [Source Code](https://github.com/openITCOCKPIT/openITCOCKPIT) ⭐ 380 | 🐛 73 | 🌐 PHP | 📅 2026-08-14)) `GPL-3.0` `deb/Docker`
* 🌎 [eZ Server Monitor](www.ezservermonitor.com) - A lightweight and simple dashboard monitor for Linux, available in Web and Bash application. (<b><code>   359⭐</code></b> <b><code>   130🍴</code></b> [Source Code](https://github.com/shevabam/ezservermonitor-web) ⭐ 359 | 🐛 28 | 🌐 PHP | 📅 2023-11-07)) `GPL-3.0` `PHP/Shell`
* [Adagios](http://adagios.org/) - Web based Nagios interface for configuration and monitoring (replacement to the standard interface), and a REST interface. (<b><code>   332⭐</code></b> <b><code>    73🍴</code></b> [Source Code](https://github.com/opinkerfi/adagios) ⭐ 332 | 🐛 78 | 🌐 HTML | 📅 2024-11-07)) `AGPL-3.0` `Docker/Python`
* <b><code>   312⭐</code></b> <b><code>    37🍴</code></b> [Status](https://github.com/dani3l0/Status) ⭐ 312 | 🐛 1 | 🌐 Python | 📅 2026-07-08) - Simple and lightweight system monitoring tool for small homeservers with a pleasant web interface.  🌎 [Demo](status.enshittification.social/)) `MIT` `Python`
* <b><code>   212⭐</code></b> <b><code>     9🍴</code></b> [ruptime](https://github.com/alexmyczko/ruptime) ⭐ 212 | 🐛 5 | 🌐 Shell | 📅 2026-04-15) - Classic system status server. `AGPL-3.0` `Shell`
* 🌎 [Naemon](www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features. (<b><code>   171⭐</code></b> <b><code>    69🍴</code></b> [Source Code](https://github.com/naemon/naemon-core) ⭐ 171 | 🐛 48 | 🌐 C | 📅 2026-08-04)) `GPL-2.0` `C`
* <b><code>    11⭐</code></b> <b><code>     0🍴</code></b> [EdMon](https://github.com/eahlys/EdMon) ⭐ 11 | 🐛 2 | 🌐 Java | 📅 2020-10-13) - A command-line monitoring application helping you to check that your hosts and services are available, with notifications support. `MIT` `Java`
* 🌎 [Monit](mmonit.com/monit/#home) - Small utility for managing and monitoring Unix systems.  🌎 [Source Code](bitbucket.org/tildeslash/monit/src/master/)) `AGPL-3.0` `C`
* [Observium Community Edition](http://www.observium.org/) - Network monitoring and management platform that provides real-time insight into network health and performance. `QPL-1.0` `PHP`
* 🌎 [Zabbix](www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications.  🌎 [Source Code](git.zabbix.com/projects/ZBX/repos/zabbix/browse)) `GPL-2.0` `C`

### Network Configuration Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Network configuration management tools.

* <b><code>  3493⭐</code></b> <b><code>  1052🍴</code></b> [Oxidized](https://github.com/ytti/oxidized) ⭐ 3,498 | 🐛 54 | 🌐 Ruby | 📅 2026-08-15) - Network device configuration backup tool. `Apache-2.0` `Ruby`
* 🌎 [phpIPAM](phpipam.net/) - Open source IP address management with PowerDNS integration. (<b><code>  2775⭐</code></b> <b><code>   794🍴</code></b> [Source Code](https://github.com/phpipam/phpipam) ⭐ 2,776 | 🐛 1,847 | 🌐 PHP | 📅 2026-08-07)) `GPL-3.0` `PHP`
* 🌎 [GNS3](www.gns3.com/) - Graphical network simulator that provides a variety of virtual appliances. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/GNS3/gns3-gui/) ⭐ 2,606 | 🐛 128 | 🌐 Python | 📅 2026-08-09)) `GPL-3.0` `Python`
* 🌎 [rConfig](www.rconfig.com/) - Network device configuration management tool. (<b><code>   201⭐</code></b> <b><code>    28🍴</code></b> [Source Code](https://github.com/rconfig/rconfig) ⭐ 201 | 🐛 0 | 🌐 PHP | 📅 2026-08-13)) `GPL-3.0` `PHP`
* 🌎 [RANCID](www.shrubbery.net/rancid/) - Monitor network devices configuration and maintain history of changes. (<b><code>   136⭐</code></b> <b><code>    54🍴</code></b> [Source Code](https://github.com/haussli/rancid) ⭐ 136 | 🐛 57 | 🌐 Makefile | 📅 2026-06-23)) `BSD-3-Clause` `Perl/Shell`
* 🌎 [OpenWISP](openwisp.org/) - Open Source Network Management System for OpenWRT based routers and access points.  🌎 [Demo](openwisp.org/demo.html), [Source Code](https://github.com/openwisp)) `GPL-3.0` `Python`

### PaaS

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Platform-as-a-Service](en.wikipedia.org/wiki/Platform_as_a_service) software allows customers to provision, instantiate, run, and manage a computing platform and one or more applications, without the complexity of building and maintaining the infrastructure typically associated with developing and launching the application. Also includes 🌎 [Serverless computing](en.wikipedia.org/wiki/Serverless_computing) and 🌎 [Function-as-a-service (FaaS)](en.wikipedia.org/wiki/Function_as_a_service) software.

* 🌎 [Coolify](coolify.io/) - An open-source & self-hostable Heroku / Netlify alternative (and even more). (<b><code> 60543⭐</code></b> <b><code>  5281🍴</code></b> [Source Code](https://github.com/coollabsio/coolify) ⭐ 60,633 | 🐛 779 | 🌐 PHP | 📅 2026-08-15)) `Apache-2.0` `Docker`
* 🌎 [Dokku](dokku.com/) - An open-source PaaS (alternative to Heroku). (<b><code> 32105⭐</code></b> <b><code>  2070🍴</code></b> [Source Code](https://github.com/dokku/dokku) ⭐ 32,109 | 🐛 25 | 🌐 Shell | 📅 2026-08-13)) `MIT` `Docker/Shell/Go/deb`
* 🌎 [OpenFaaS](www.openfaas.com/) - Serverless Functions Made Simple for Docker & Kubernetes. (<b><code> 26222⭐</code></b> <b><code>  1970🍴</code></b> [Source Code](https://github.com/openfaas/faas) ⭐ 26,220 | 🐛 31 | 🌐 Go | 📅 2026-07-02)) `MIT` `Go`
* 🌎 [CapRover](caprover.com/) - Build your own PaaS in a few minutes.  🌎 [Demo](captain.server.demo.caprover.com/#/login), <b><code> 15127⭐</code></b> <b><code>   991🍴</code></b> [Source Code](https://github.com/caprover/caprover) ⭐ 15,130 | 🐛 176 | 🌐 TypeScript | 📅 2026-08-15)) `Apache-2.0` `Docker/Nodejs`
* 🌎 [Nhost](nhost.io/) - Firebase Alternative with GraphQL. Get a database and backend configured and ready in minutes. (<b><code>  9278⭐</code></b> <b><code>   609🍴</code></b> [Source Code](https://github.com/nhost/nhost) ⭐ 9,280 | 🐛 132 | 🌐 TypeScript | 📅 2026-08-15)) `MIT` `Docker/Nodejs/Go`
* 🌎 [Tau](taubyte.com) - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, CI/CD, Object Storage, K/V Database, and Pub-Sub Messaging. (<b><code>  5111⭐</code></b> <b><code>   205🍴</code></b> [Source Code](https://github.com/taubyte/tau) ⭐ 5,127 | 🐛 11 | 🌐 Go | 📅 2026-08-09)) `BSD-3-Clause` `Go/Rust/Docker`
* 🌎 [Kubero](www.kubero.dev/) - A self-hosted Heroku PaaS alternative for Kubernetes that implements GitOps.  🌎 [Demo](demo.kubero.dev/), <b><code>  4384⭐</code></b> <b><code>   207🍴</code></b> [Source Code](https://github.com/kubero-dev/kubero) ⭐ 4,384 | 🐛 113 | 🌐 TypeScript | 📅 2026-08-11)) `GPL-3.0` `K8S/Nodejs/Go`
* <b><code>  2228⭐</code></b> <b><code>   157🍴</code></b> [fx](https://github.com/metrue/fx) ⭐ 2,228 | 🐛 85 | 🌐 Go | 📅 2023-10-24) - A tool to help you do Function as a Service with painless on your own servers. `MIT` `Go`
* <b><code>   249⭐</code></b> <b><code>    14🍴</code></b> [Trusted-CGI](https://github.com/reddec/trusted-cgi) ⭐ 249 | 🐛 11 | 🌐 Go | 📅 2024-09-27) - Lightweight self-hosted lambda/applications/cgi/serverless-functions platform. `MIT` `Go/deb/Docker`

### Packaging

**[`^        back to top        ^`](#awesome-sysadmin)**

A 🌎 [package manager](en.wikipedia.org/wiki/Package_manager) or package-management system is a collection of software tools that automates the process of installing, upgrading, configuring, and removing computer programs for a computer in a consistent manner.

* 🌎 [fpm](fpm.readthedocs.io/en/latest/) - Versatile multi format package creator. (<b><code> 11498⭐</code></b> <b><code>  1065🍴</code></b> [Source Code](https://github.com/jordansissel/fpm) ⭐ 11,499 | 🐛 790 | 🌐 Ruby | 📅 2026-08-10)) `MIT` `Ruby`
* 🌎 [aptly](www.aptly.info/) - Swiss army knife for Debian repository management. (<b><code>  2863⭐</code></b> <b><code>   423🍴</code></b> [Source Code](https://github.com/aptly-dev/aptly) ⭐ 2,865 | 🐛 212 | 🌐 Go | 📅 2026-08-09)) `MIT` `Go`
* <b><code>  1317⭐</code></b> <b><code>   296🍴</code></b> [omnibus-ruby](https://github.com/chef/omnibus) ⭐ 1,317 | 🐛 69 | 🌐 Ruby | 📅 2025-12-09) - Easily create full-stack installers for your project across a variety of platforms. `Apache-2.0` `Ruby`
* <b><code>   398⭐</code></b> <b><code>   131🍴</code></b> [tito](https://github.com/rpm-software-management/tito) ⭐ 398 | 🐛 62 | 🌐 Python | 📅 2026-05-14) - Builds RPMs for git-based projects. `GPL-2.0` `Python`

### Project Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Web-based project management and bug tracking systems.

**Please visit 🌎 [awesome-selfhosted/Project Management](awesome-selfhosted.net/tags/software-development---project-management.html)**

### Queuing

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Message queues](en.wikipedia.org/wiki/Message_queue) and 🌎 [message broker](en.wikipedia.org/wiki/Message_broker) software, typically used for inter-process communication (IPC), or for inter-thread communication within the same process.

*See also: 🌎 [Cloud Native Landscape - Streaming & Messaging](landscape.cncf.io/?group=projects-and-products\&view-mode=card#app-definition-and-development--streaming-messaging)*

* 🌎 [NSQ](nsq.io/) - A realtime distributed messaging platform. (<b><code> 25772⭐</code></b> <b><code>  2891🍴</code></b> [Source Code](https://github.com/nsqio/nsq) ⭐ 25,771 | 🐛 77 | 🌐 Go | 📅 2026-08-11)) `MPL-2.0` `Go`
* 🌎 [BeanstalkD](beanstalkd.github.io/) - A simple, fast work queue. (<b><code>  6698⭐</code></b> <b><code>   866🍴</code></b> [Source Code](https://github.com/beanstalkd/beanstalkd) ⭐ 6,698 | 🐛 46 | 🌐 C | 📅 2025-03-18)) `MIT` `C`
* 🌎 [ActiveMQ](activemq.apache.org/) - Java message broker. (<b><code>  2449⭐</code></b> <b><code>  1494🍴</code></b> [Source Code](https://github.com/apache/activemq) ⭐ 2,449 | 🐛 103 | 🌐 Java | 📅 2026-08-12)) `Apache-2.0` `Java`
* [Gearman](http://gearman.org/) - Fast multi-language queuing/job processing platform. (<b><code>   763⭐</code></b> <b><code>   159🍴</code></b> [Source Code](https://github.com/gearman/gearmand) ⭐ 763 | 🐛 50 | 🌐 C++ | 📅 2026-08-11)) `BSD-3-Clause` `C++`
* 🌎 [ZeroMQ](zeromq.org/) - Lightweight queuing system. ([Source Code](https://github.com/zeromq)) `GPL-3.0` `C++`

### Remote Desktop Clients

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Remote Desktop](en.wikipedia.org/wiki/Remote_desktop_software) client software.

*See also: 🌎 [awesome-selfhosted/Remote Access](awesome-selfhosted.net/tags/remote-access.html)*

* 🌎 [Remmina](www.remmina.org/) - Feature-rich remote desktop application for linux and other unixes.  🌎 [Source Code](gitlab.com/Remmina/Remmina)) `GPL-2.0` `C`
* 🌎 [Tiger VNC](tigervnc.org/) - High-performance, multi-platform VNC client and server. (<b><code>  7385⭐</code></b> <b><code>  1175🍴</code></b> [Source Code](https://github.com/TigerVNC/tigervnc) ⭐ 7,391 | 🐛 184 | 🌐 C++ | 📅 2026-08-14)) `GPL-2.0` `C++`
* 🌎 [X2go](wiki.x2go.org/doku.php) - X2Go is an open source remote desktop software for Linux that uses the NoMachine/NX technology protocol.  🌎 [Source Code](code.x2go.org/gitweb)) `GPL-2.0` `Perl`

### Router

**[`^        back to top        ^`](#awesome-sysadmin)**

Software for management of [router](https://en.wikipedia.org/wiki/Router_\(computing\)) hardware.

* 🌎 [DD-WRT](dd-wrt.com/) - A Linux-based firmware for wireless routers and access points, originally designed for the Linksys WRT54G series.  🌎 [Source Code](svn.dd-wrt.com/)) `GPL-2.0` `C`
* 🌎 [IPFire](www.ipfire.org/) - Free network firewall distribution, based on the Linux operating system with easy-to-use web management console.  🌎 [Source Code](git.ipfire.org/?p=ipfire-2.x.git;a=summary)) `GPL-2.0` `Shell/PHP/Other`
* 🌎 [OpenWrt](openwrt.org/) - A Linux-based router featuring Mesh networking, IPS via snort and AQM among many other features.  🌎 [Source Code](git.openwrt.org/openwrt/openwrt)) `GPL-2.0` `C`
* 🌎 [OPNsense](opnsense.org/) - An open source FreeBSD-based firewall and router with traffic shaping, load balancing, and virtual private network capabilities. ([Source Code](https://github.com/opnsense)) `BSD-2-Clause` `C/PHP`
* 🌎 [pfSense CE](www.pfsense.org/) - Free network firewall distribution, based on the FreeBSD operating system with a custom kernel and including third party free software packages for additional functionality. (<b><code>  5701⭐</code></b> <b><code>  1600🍴</code></b> [Source Code](https://github.com/pfsense/pfsense) ⭐ 5,704 | 🐛 40 | 🌐 PHP | 📅 2026-03-31)) `Apache-2.0` `Shell/PHP/Other`

### Service Discovery

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Service discovery](en.wikipedia.org/wiki/Service_discovery) is the process of automatically detecting devices and services on a computer network.

* 🌎 [etcd](etcd.io/) - Distributed K/V-Store, authenticating via SSL PKI and a REST HTTP Api for shared configuration and service discovery. (<b><code> 52122⭐</code></b> <b><code> 10454🍴</code></b> [Source Code](https://github.com/etcd-io/etcd) ⭐ 52,128 | 🐛 310 | 🌐 Go | 📅 2026-08-15)) `Apache-2.0` `Go`
* 🌎 [Consul](www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration. (<b><code> 30029⭐</code></b> <b><code>  4615🍴</code></b> [Source Code](https://github.com/hashicorp/consul) ⭐ 30,030 | 🐛 1,400 | 🌐 Go | 📅 2026-08-14)) `MPL-2.0` `Go`
* 🌎 [ZooKeeper](zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services. (<b><code> 12790⭐</code></b> <b><code>  7326🍴</code></b> [Source Code](https://github.com/apache/zookeeper) ⭐ 12,789 | 🐛 241 | 🌐 Java | 📅 2026-08-14)) `Apache-2.0` `Java/C++`

### Software Containers

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Operating system–level](en.wikipedia.org/wiki/OS-level_virtualization) virtualization.

* 🌎 [Portainer Community Edition](www.portainer.io/) - Simple management UI for Docker. (<b><code> 38236⭐</code></b> <b><code>  2876🍴</code></b> [Source Code](https://github.com/portainer/portainer) ⭐ 38,252 | 🐛 745 | 🌐 TypeScript | 📅 2026-08-15)) `Zlib` `Go`
* 🌎 [Docker Compose](docs.docker.com/compose/) - Define and run multi-container Docker applications. (<b><code> 38087⭐</code></b> <b><code>  5792🍴</code></b> [Source Code](https://github.com/docker/compose) ⭐ 38,075 | 🐛 95 | 🌐 Go | 📅 2026-08-15)) `Apache-2.0` `Go`
* 🌎 [Podman](podman.io) - Daemonless container engine for developing, managing, and running OCI Containers on your Linux System. Containers can either be run as root or in rootless mode. Simply put: `alias docker=podman`. (<b><code> 32561⭐</code></b> <b><code>  3317🍴</code></b> [Source Code](https://github.com/podman-container-tools/podman) ⭐ 32,584 | 🐛 1,127 | 🌐 Go | 📅 2026-08-16)) `Apache-2.0` `Go`
* 🌎 [systemd-nspawn](www.freedesktop.org/software/systemd/man/systemd-nspawn.html) - Lightweight, chroot-like, environment to run an OS or command directly under systemd. (<b><code> 16595⭐</code></b> <b><code>  4624🍴</code></b> [Source Code](https://github.com/systemd/systemd) ⭐ 16,601 | 🐛 3,360 | 🌐 C | 📅 2026-08-16)) `GPL-2.0` `C`
* 🌎 [Incus](linuxcontainers.org/incus/) - Container "hypervisor" and a better UX for LXC. (<b><code>  5934⭐</code></b> <b><code>   476🍴</code></b> [Source Code](https://github.com/lxc/incus) ⭐ 5,951 | 🐛 43 | 🌐 Go | 📅 2026-08-16)) `Apache-2.0` `Go`
* 🌎 [LXC](linuxcontainers.org/lxc/) - Userspace interface for the Linux kernel containment features. (<b><code>  5239⭐</code></b> <b><code>  1182🍴</code></b> [Source Code](https://github.com/lxc/lxc) ⭐ 5,240 | 🐛 148 | 🌐 C | 📅 2026-07-23)) `GPL-2.0` `C`
* 🌎 [Docker Swarm](docs.docker.com/engine/swarm/) - Manage cluster of Docker Engines. (<b><code>  3644⭐</code></b> <b><code>   671🍴</code></b> [Source Code](https://github.com/moby/swarmkit) ⭐ 3,644 | 🐛 279 | 🌐 Go | 📅 2026-08-04)) `Apache-2.0` `Go`
* 🌎 [Docker](www.docker.com/) - Platform for developers and sysadmins to build, ship, and run distributed applications.  🌎 [Source Code](www.docker.com/community/open-source/)) `Apache-2.0` `Go`
* 🌎 [OpenVZ](openvz.org) - Container-based virtualization for Linux.  🌎 [Source Code](src.openvz.org/projects/OVZ)) `GPL-2.0` `C`

### Time Servers

**[`^        back to top        ^`](#awesome-sysadmin)**

Time synchronization servers and clients (NTP, PTP, Roughtime).

* <b><code>   312⭐</code></b> <b><code>    33🍴</code></b> [Statime](https://github.com/pendulum-project/statime) ⭐ 312 | 🐛 27 | 🌐 Rust | 📅 2026-08-10) - A Precision Time Protocol (PTP) implementation in Rust. `MIT/Apache-2.0` `Rust`
* <b><code>   148⭐</code></b> <b><code>    24🍴</code></b> [Roughenough](https://github.com/int08h/roughenough) ⭐ 148 | 🐛 4 | 🌐 Rust | 📅 2026-08-13) - A Roughtime secure time synchronization client and server. `MIT/Apache-2.0` `Rust`
* 🌎 [OpenNTPD](www.openntpd.org/) - A FREE, easy to use implementation of the Network Time Protocol. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/openntpd-portable/openntpd-openbsd/) ⭐ 23 | 🐛 1 | 🌐 C | 📅 2026-07-02)) `ISC` `C`
* 🌎 [Chrony](chrony-project.org/) - A versatile implementation of the Network Time Protocol (NTP).  🌎 [Source Code](gitlab.com/chrony/chrony)) `GPL-2.0` `C`
* 🌎 [NTPsec](www.ntpsec.org/) - A secure, hardened, and improved implementation of Network Time Protocol derived from NTP Classic.  🌎 [Source Code](gitlab.com/NTPsec/ntpsec)) `BSD-2-Clause` `C`

### Troubleshooting

**[`^        back to top        ^`](#awesome-sysadmin)**

Troubleshooting tools.

* 🌎 [mitmproxy](mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems. (<b><code> 44690⭐</code></b> <b><code>  4684🍴</code></b> [Source Code](https://github.com/mitmproxy/mitmproxy) ⭐ 44,706 | 🐛 469 | 🌐 Python | 📅 2026-08-13)) `MIT` `Python`
* 🌎 [Sysdig](www.sysdig.com/) - Capture system state and activity from a running Linux instance, then save, filter and analyze. (<b><code>  8283⭐</code></b> <b><code>   754🍴</code></b> [Source Code](https://github.com/draios/sysdig) ⭐ 8,283 | 🐛 116 | 🌐 C++ | 📅 2026-04-13)) `Apache-2.0` `Docker/Lua/C`
* 🌎 [mtr](www.bitwizard.nl/mtr/) - Network utility that combines traceroute and ping. (<b><code>  3334⭐</code></b> <b><code>   374🍴</code></b> [Source Code](https://github.com/traviscross/mtr) ⭐ 3,335 | 🐛 137 | 🌐 C | 📅 2026-06-16)) `GPL-2.0` `C`
* 🌎 [grml](grml.org) - Bootable Debian Live CD with powerful CLI tools. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/grml/))) `GPL-3.0` `Shell`
* 🌎 [Wireshark](www.wireshark.org/) - The world's foremost network protocol analyzer.  🌎 [Source Code](gitlab.com/wireshark/wireshark)) `GPL-2.0` `C`

### Version control

**[`^        back to top        ^`](#awesome-sysadmin)**

Software versioning and revision control.

* 🌎 [Darcs](darcs.net/) - Cross-platform version control system, like git, mercurial or svn but with a very different approach: focus on changes rather than snapshots.  🌎 [Source Code](darcs.net/releases/)) `GPL-2.0` `Haskell`
* 🌎 [Fossil](www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.  🌎 [Source Code](www.fossil-scm.org/home/dir?ci=trunk)) `BSD-2-Clause` `C`
* 🌎 [Git](git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed. (<b><code> 62555⭐</code></b> <b><code> 28248🍴</code></b> [Source Code](https://github.com/git/git) ⭐ 62,582 | 🐛 388 | 🌐 C | 📅 2026-08-15)) `GPL-2.0` `C`
* 🌎 [Mercurial](www.mercurial-scm.org/) - Distributed source control management tool.  🌎 [Source Code](repo.mercurial-scm.org/hg/file/tip)) `GPL-2.0` `Python/C/Rust`
* 🌎 [Subversion](subversion.apache.org/) - Client-server revision control system.  🌎 [Source Code](svn.apache.org/repos/asf/subversion/trunk/)) `Apache-2.0` `C`

### Virtualization

**[`^        back to top        ^`](#awesome-sysadmin)**

Virtualization software.

* 🌎 [Vagrant](www.vagrantup.com/) - Tool for building complete development environments. (<b><code> 27204⭐</code></b> <b><code>  4399🍴</code></b> [Source Code](https://github.com/hashicorp/vagrant) ⭐ 27,202 | 🐛 752 | 🌐 Ruby | 📅 2026-08-03)) `BUSL-1.1` `Ruby`
* 🌎 [Packer](www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration. (<b><code> 15756⭐</code></b> <b><code>  3333🍴</code></b> [Source Code](https://github.com/hashicorp/packer) ⭐ 15,759 | 🐛 314 | 🌐 Go | 📅 2026-08-16)) `MPL-2.0` `Go`
* 🌎 [OpenNebula](opennebula.org/) - Build and manage enterprise clouds for virtualized services, containerized applications and serverless computing. (<b><code>  1730⭐</code></b> <b><code>   529🍴</code></b> [Source Code](https://github.com/OpenNebula/one) ⭐ 1,731 | 🐛 787 | 🌐 JavaScript | 📅 2026-08-06)) `Apache-2.0` `C++`
* 🌎 [Ganeti](www.ganeti.org/) - Cluster virtual server management software tool built on top of KVM and Xen. (<b><code>   578⭐</code></b> <b><code>   127🍴</code></b> [Source Code](https://github.com/ganeti/ganeti) ⭐ 578 | 🐛 333 | 🌐 Python | 📅 2026-07-27)) `BSD-2-Clause` `Python/Haskell`
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

* <b><code> 42836⭐</code></b> <b><code>  2500🍴</code></b> [Headscale](https://github.com/juanfont/headscale) ⭐ 42,888 | 🐛 142 | 🌐 Go | 📅 2026-07-30) - Self-hostable fork of 🌎 [Tailscale](tailscale.com), cross-platform clients, simple to use, built-in (currently experimental) monitoring tools. `BSD-3-Clause` `Go`
* <b><code> 17612⭐</code></b> <b><code>  1168🍴</code></b> [Nebula](https://github.com/slackhq/nebula) ⭐ 17,619 | 🐛 102 | 🌐 Go | 📅 2026-08-14) - A scalable p2p VPN with a focus on performance, simplicity and security. `MIT` `Go`
* <b><code> 15173⭐</code></b> <b><code>   607🍴</code></b> [Gluetun VPN client](https://github.com/passteque/gluetun) ⭐ 15,196 | 🐛 330 | 🌐 Go | 📅 2026-08-13) - VPN client in a thin Docker container for multiple VPN providers, written in Go, and using OpenVPN or Wireguard, DNS over TLS, with a few proxy servers built-in. `MIT` `Docker`
* 🌎 [OpenVPN](community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange. (<b><code> 14384⭐</code></b> <b><code>  3383🍴</code></b> [Source Code](https://github.com/OpenVPN/openvpn) ⭐ 14,386 | 🐛 222 | 🌐 C | 📅 2026-08-15)) `GPL-2.0` `C`
* <b><code> 13516⭐</code></b> <b><code>   795🍴</code></b> [sshuttle](https://github.com/sshuttle/sshuttle) ⭐ 13,520 | 🐛 211 | 🌐 Python | 📅 2026-08-12) - Poor man's VPN. `LGPL-2.1` `Python`
* 🌎 [SoftEther](www.softether.org/) - Multi-protocol software VPN with advanced features. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/SoftEtherVPN/SoftEtherVPN/) ⭐ 13,471 | 🐛 296 | 🌐 C | 📅 2026-08-14)) `Apache-2.0` `C`
* 🌎 [Firezone](www.firezone.dev/) - WireGuard based VPN Server and Firewall. (<b><code>  9013⭐</code></b> <b><code>   442🍴</code></b> [Source Code](https://github.com/firezone/firezone) ⭐ 9,025 | 🐛 388 | 🌐 Elixir | 📅 2026-08-15)) `Apache-2.0` `Docker`
* 🌎 [strongSwan](www.strongswan.org/) - Complete IPsec implementation for Linux. (<b><code>  2940⭐</code></b> <b><code>   930🍴</code></b> [Source Code](https://github.com/strongswan/strongswan) ⭐ 2,941 | 🐛 160 | 🌐 C | 📅 2026-07-31)) `GPL-2.0` `C`
* 🌎 [Dockovpn](dockovpn.io) - Out-of-the-box stateless dockerized OpenVPN server which starts in less than 2 seconds. (<b><code>  1427⭐</code></b> <b><code>   278🍴</code></b> [Source Code](https://github.com/dockovpn/dockovpn) ⭐ 1,427 | 🐛 80 | 🌐 Shell | 📅 2024-06-30)) `GPL-2.0` `Docker`
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
* 🌎 [Spiceworks Community](community.spiceworks.com/start) - General enterprise IT news and small articles.
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
* 🌎 [Software Collections](www.softwarecollections.org) - Community Release of 🌎 [Red Hat Software Collections](access.redhat.com/documentation/en/red-hat-software-collections/). Provides updated packages of Ruby, Python, etc. for CentOS/Scientific Linux 6.x.

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

Contributing guidelines can be found <b><code>     9⭐</code></b> <b><code>    29🍴</code></b> [here](https://github.com/awesome-foss/awesome-sysadmin-data/blob/master/CONTRIBUTING.md) ⭐ 9 | 🐛 22 | 🌐 Makefile | 📅 2026-08-09).

## License

This list is under the [Creative Commons Attribution-ShareAlike 4.0 International](LICENSE).
Terms of the license are summarized 🌎 [here](creativecommons.org/licenses/by-sa/4.0).
The list of authors can be found in the [AUTHORS](AUTHORS) file.

## Source

<b><code> 34895⭐</code></b> <b><code>  2097🍴</code></b> [awesome-foss/awesome-sysadmin](https://github.com/awesome-foss/awesome-sysadmin) ⭐ 34,909 | 🐛 0 | 📅 2026-06-20)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
