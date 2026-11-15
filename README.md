# Awesome Sysadmin with stars

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome) ⭐ 537,112 | 🐛 104 | 📅 2026-09-02 [![](https://github.com/awesome-foss/awesome-sysadmin-data/actions/workflows/dead-links.yml/badge.svg)](https://github.com/awesome-foss/awesome-sysadmin-data/issues/1) ⭐ 17 | 🐛 30 | 🌐 Makefile | 📅 2026-11-15 [![](https://github.com/awesome-foss/awesome-sysadmin-data/actions/workflows/unmaintained-projects.yml/badge.svg)](https://github.com/awesome-foss/awesome-sysadmin-data/issues/1) ⭐ 17 | 🐛 30 | 🌐 Makefile | 📅 2026-11-15

**A curated list of amazingly awesome Free and Open-Source sysadmin resources.** Please read the [Contributing](#contributing) if you wish to add software and consider <b><code>    47⭐</code></b> <b><code>     4🍴</code></b> [donating](https://github.com/n1trux/awesome-donations) ⭐ 47 | 🐛 2 | 📅 2024-01-02) to the FLOSS projects you use regularly. Please consider contributing to fix one of the pinned <b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [issues](https://github.com/awesome-foss/awesome-sysadmin-data/issues) ⭐ 17 | 🐛 30 | 🌐 Makefile | 📅 2026-11-15) if your time allows.

* 🌎 [HTML version](sysadmin.awesome-selfhosted.net/) (recommended)\*\*, **[Markdown version](https://github.com/correia-jpv/fucking-awesome-sysadmin)** (legacy).

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

* 🌎 [Bazel](www.bazel.io/) - A fast, scalable, multi-language and extensible build system. Used by Google. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/bazelbuild/bazel/) ⭐ 26,104 | 🐛 2,115 | 🌐 Java | 📅 2026-11-13)) `Apache-2.0` `Java`
* 🌎 [Gradle](gradle.org/) - Another build automation system. (<b><code> 18933⭐</code></b> <b><code>  5261🍴</code></b> [Source Code](https://github.com/gradle/gradle) ⭐ 18,935 | 🐛 3,507 | 🌐 Groovy | 📅 2026-11-15)) `Apache-2.0` `Groovy/Java`
* 🌎 [Apache Maven](maven.apache.org/) - Build automation tool mainly for Java. A software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information. (<b><code>  5376⭐</code></b> <b><code>  3074🍴</code></b> [Source Code](https://github.com/apache/maven) ⭐ 5,378 | 🐛 667 | 🌐 Java | 📅 2026-11-14)) `Apache-2.0` `Java`
* 🌎 [Rake](ruby.github.io/rake/) - Build automation tool similar to Make, written in and extensible in Ruby. (<b><code>  2465⭐</code></b> <b><code>   649🍴</code></b> [Source Code](https://github.com/ruby/rake) ⭐ 2,466 | 🐛 73 | 🌐 Ruby | 📅 2026-11-09)) `MIT` `Ruby`
* 🌎 [Apache Ant](ant.apache.org/) - Automation build tool, similar to make, a library and command-line tool whose mission is to drive processes described in build files as targets and extension points dependent upon each other. (<b><code>   478⭐</code></b> <b><code>   462🍴</code></b> [Source Code](https://github.com/apache/ant) ⭐ 477 | 🐛 21 | 🌐 Java | 📅 2026-11-05)) `Apache-2.0` `Java`
* 🌎 [parse-dmarc](dmarcguard.io) `⚠` - DMARC aggregate report parser with a built-in dashboard. Fetches reports over IMAP, stores them, and flags spoofing. Single Go binary with embedded Vue UI, SQLite storage, and Prometheus metrics (alternative to PowerDMARC, EasyDMARC, Dmarcian). (<b><code>   233⭐</code></b> <b><code>    26🍴</code></b> [Source Code](https://github.com/dmarcguardhq/parse-dmarc) ⭐ 233 | 🐛 12 | 🌐 Go | 📅 2026-11-14), <b><code>  1317⭐</code></b> <b><code>   277🍴</code></b> [Clients](https://github.com/domainaware/parsedmarc) ⭐ 1,319 | 🐛 0 | 🌐 Python | 📅 2026-11-11)) `Apache-2.0` `Go/Docker`
* 🌎 [OpenBolt](voxpupuli.org/openvox/) - Orchestration tool to run orchestration workflows or one-off tasks/scripts to automate the provisioning and management of nodes. Community fork of the last open source version of 🌎 [Puppet Bolt](help.puppet.com/bolt/current/topics/bolt.htm). (<b><code>    34⭐</code></b> <b><code>    22🍴</code></b> [Source Code](https://github.com/OpenVoxProject/openbolt) ⭐ 34 | 🐛 38 | 🌐 Ruby | 📅 2026-11-13)) `Apache-2.0` `Ruby`
* 🌎 [GNU Make](www.gnu.org/software/make/) - The most popular automation build tool for many purposes, make is a tool which controls the generation of executables and other non-source files of a program from the program's source files.  🌎 [Source Code](git.savannah.gnu.org/cgit/make.git)) `GPL-3.0` `C`

### Backups

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Backup](en.wikipedia.org/wiki/Backup) software.

*See also: <b><code>   761⭐</code></b> <b><code>    57🍴</code></b> [Restic's list of Linux backup software](https://github.com/restic/others) ⭐ 761 | 🐛 13 | 📅 2023-11-05)*

* 🌎 [rclone](rclone.org/) - Command-line program to sync files and directories to and from different cloud storage providers.. (<b><code> 61006⭐</code></b> <b><code>  5694🍴</code></b> [Source Code](https://github.com/rclone/rclone) ⭐ 61,018 | 🐛 1,330 | 🌐 Go | 📅 2026-11-14)) `MIT` `Go`
* 🌎 [Restic](restic.net/) - Easy, fast, verifiable, secure and efficient remote backup tool. (<b><code> 37219⭐</code></b> <b><code>  1966🍴</code></b> [Source Code](https://github.com/restic/restic) ⭐ 37,235 | 🐛 662 | 🌐 Go | 📅 2026-11-06)) `BSD-2-Clause` `Go`
* 🌎 [Duplicati](www.duplicati.com) - Backup client that securely stores encrypted, incremental, compressed backups on cloud storage services and remote file servers. (<b><code> 15201⭐</code></b> <b><code>  1092🍴</code></b> [Source Code](https://github.com/duplicati/duplicati) ⭐ 15,202 | 🐛 511 | 🌐 C# | 📅 2026-11-14)) `LGPL-2.1` `C#`
* 🌎 [BorgBackup](www.borgbackup.org/) - Deduplicating archiver with compression and authenticated encryption. (<b><code> 13923⭐</code></b> <b><code>   883🍴</code></b> [Source Code](https://github.com/borgbackup/borg) ⭐ 13,927 | 🐛 186 | 🌐 Python | 📅 2026-11-14)) `BSD-3-Clause` `Python`
* 🌎 [Databasus](databasus.com/) - PostgreSQL, MySQL, MariaDB and MongoDB backup tool with web UI, external storages (local, S3, FTP, Google Drive, etc.), notifications (webhook, Discord, Slack, etc.) and team management. (<b><code>  9276⭐</code></b> <b><code>   613🍴</code></b> [Source Code](https://github.com/databasus/databasus) ⭐ 9,280 | 🐛 7 | 🌐 TypeScript | 📅 2026-11-14)) `Apache-2.0` `Docker`
* 🌎 [Backrest](garethgeorge.github.io/backrest/) - Backrest is a web UI and orchestrator for restic backup. (<b><code>  7904⭐</code></b> <b><code>   254🍴</code></b> [Source Code](https://github.com/garethgeorge/backrest) ⭐ 7,909 | 🐛 410 | 🌐 TypeScript | 📅 2026-09-21)) `GPL-3.0` `Docker/Go`
* 🌎 [Rsnapshot](rsnapshot.org/) - Filesystem snapshot utility based on rsync. (<b><code>  3689⭐</code></b> <b><code>   272🍴</code></b> [Source Code](https://github.com/rsnapshot/rsnapshot) ⭐ 3,689 | 🐛 55 | 🌐 Perl | 📅 2026-10-10)) `GPL-2.0` `Perl`
* 🌎 [Barman](pgbarman.org) - Backup and Recovery Manager for PostgreSQL. (<b><code>  3276⭐</code></b> <b><code>   276🍴</code></b> [Source Code](https://github.com/EnterpriseDB/barman) ⭐ 3,276 | 🐛 51 | 🌐 Python | 📅 2026-11-13)) `GPL-3.0` `Python`
* 🌎 [Plakar Community Edition](www.plakar.io/) - Encrypted, deduplicated, verifiable, and scalable backup engine with no vendor lock-in. (<b><code>  2171⭐</code></b> <b><code>   104🍴</code></b> [Source Code](https://github.com/PlakarKorp/plakar) ⭐ 2,172 | 🐛 87 | 🌐 Go | 📅 2026-11-14)) `ISC` `deb/Docker/Go`
* 🌎 [Portabase](portabase.io/) - Server dashboard tool that simplifies the backup and restoration of your database instances. (<b><code>  1901⭐</code></b> <b><code>   146🍴</code></b> [Source Code](https://github.com/Portabase/portabase) ⭐ 1,903 | 🐛 41 | 🌐 TypeScript | 📅 2026-11-13)) `Apache-2.0` `Docker`
* 🌎 [Bareos](www.bareos.org/) - Cross-network backup solution which preserves, archives, and recovers data from all major operating systems. (<b><code>  1281⭐</code></b> <b><code>   321🍴</code></b> [Source Code](https://github.com/bareos/bareos) ⭐ 1,282 | 🐛 95 | 🌐 C++ | 📅 2026-11-13)) `AGPL-3.0` `C++/C`
* 🌎 [Rdiff-backup](rdiff-backup.net/) - Reverse differential backup tool, over a network or locally. (<b><code>  1273⭐</code></b> <b><code>    99🍴</code></b> [Source Code](https://github.com/rdiff-backup/rdiff-backup) ⭐ 1,273 | 🐛 86 | 🌐 Python | 📅 2026-11-15)) `GPL-2.0` `Python`
* 🌎 [UrBackup](www.urbackup.org/) - Client/Server Open Source Network Backup for Windows, MacOS and Linux. (<b><code>   945⭐</code></b> <b><code>   180🍴</code></b> [Source Code](https://github.com/uroni/urbackup_backend) ⭐ 946 | 🐛 63 | 🌐 C | 📅 2026-11-10)) `AGPL-3.0` `C/C++`
* 🌎 [Burp](burp.grke.org/) - Network backup and restore program. (<b><code>   503⭐</code></b> <b><code>    78🍴</code></b> [Source Code](https://github.com/grke/burp) ⭐ 503 | 🐛 82 | 🌐 C | 📅 2026-07-13)) `AGPL-3.0` `C`
* <b><code>   401⭐</code></b> <b><code>    67🍴</code></b> [Shield](https://github.com/shieldproject/shield) ⭐ 401 | 🐛 28 | 🌐 Go | 📅 2026-11-14) - A pluggable architecture for backup and restore of database systems. `MIT` `Go`
* [Dar](http://dar.linux.free.fr/) - Which stands for Disk ARchive, is a robust and rich featured archiving and backup software of the tar style. (<b><code>   208⭐</code></b> <b><code>    25🍴</code></b> [Source Code](https://github.com/Edrusb/DAR) ⭐ 208 | 🐛 3 | 🌐 C++ | 📅 2026-08-19)) `GPL-2.0` `C++`
* <b><code>    20⭐</code></b> <b><code>     3🍴</code></b> [mtsaver](https://github.com/mitoteam/mtsaver) ⭐ 20 | 🐛 2 | 🌐 Go | 📅 2026-11-10) - Simple differential backup archives command-line tool. 7-Zip archiver based. `MIT` `Go`
* 🌎 [Backupninja](0xacab.org/liberate/backupninja) - Lightweight, extensible meta-backup system, provides a centralized way to configure and coordinate many different backup utilities. `GPL-2.0` `Shell`
* 🌎 [Duplicity](duplicity.gitlab.io/) - Encrypted bandwidth-efficient backup using the rsync algorithm.  🌎 [Source Code](gitlab.com/duplicity/duplicity)) `GPL-2.0` `Python`
* 🌎 [Minarca](minarca.org/) - Client–server backup platform with a centralized web console to manage and restore Linux, Windows, and macOS backups via GUI or CLI.  🌎 [Source Code](gitlab.com/ikus-soft/minarca)) `AGPL-3.0` `Python`
* 🌎 [Proxmox Backup Server](www.proxmox.com/en/proxmox-backup-server) - Proxmox Backup Server is an enterprise-class, client-server backup solution thatis capable of backing up virtual machines, containers, and physical hosts.  🌎 [Source Code](git.proxmox.com/?p=proxmox-backup.git;a=tree)) `GPL-3.0` `Rust`

### Build and software organization tools

**[`^        back to top        ^`](#awesome-sysadmin)**

Build and software organization tools.

* 🌎 [Spack](spack.io/) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers. (<b><code>  5172⭐</code></b> <b><code>  2477🍴</code></b> [Source Code](https://github.com/spack/spack) ⭐ 5,172 | 🐛 1,192 | 🌐 Python | 📅 2026-11-13)) `MIT/Apache-2.0` `Python`
* 🌎 [Environment Modules](envmodules.io/) - Environment Modules provides for the dynamic modification of a user's environment via modulefiles. (<b><code>   873⭐</code></b> <b><code>   124🍴</code></b> [Source Code](https://github.com/envmodules/modules) ⭐ 874 | 🐛 35 | 🌐 Tcl | 📅 2026-11-12)) `GPL-2.0` `Tcl`
* 🌎 [Lmod](www.tacc.utexas.edu/research-development/tacc-projects/lmod) - Lmod is a Lua based module system that easily handles the MODULEPATH Hierarchical problem. (<b><code>   619⭐</code></b> <b><code>   149🍴</code></b> [Source Code](https://github.com/TACC/Lmod) ⭐ 619 | 🐛 28 | 🌐 Lua | 📅 2026-10-31)) `MIT` `Lua`
* 🌎 [EasyBuild](easybuild.io/) - EasyBuild builds software and modulefiles for High Performance Computing (HPC) systems in an efficient way. (<b><code>   451⭐</code></b> <b><code>   808🍴</code></b> [Source Code](https://github.com/easybuilders/easybuild-easyconfigs) ⭐ 451 | 🐛 1,210 | 🌐 Python | 📅 2026-11-13)) `GPL-2.0` `Python`

### ChatOps

**[`^        back to top        ^`](#awesome-sysadmin)**

Conversation-driven development and management.

*See also: 🌎 [/r/chatops](old.reddit.com/r/chatops)*

* 🌎 [Hubot](hubot.github.com/) - A customizable, life embetterment robot. (<b><code> 16798⭐</code></b> <b><code>  3706🍴</code></b> [Source Code](https://github.com/hubotio/hubot) ⭐ 16,796 | 🐛 4 | 🌐 JavaScript | 📅 2026-11-01)) `MIT` `Nodejs`
* 🌎 [Errbot](errbot.io/) - Plugin based chatbot designed to be easily deployable, extensible and maintainable. (<b><code>  3313⭐</code></b> <b><code>   628🍴</code></b> [Source Code](https://github.com/errbotio/errbot) ⭐ 3,313 | 🐛 47 | 🌐 Python | 📅 2026-10-26)) `GPL-3.0` `Python`
* 🌎 [Eggdrop](www.eggheads.org/) - The oldest Internet Relay Chat (IRC) bot still in active development. (<b><code>   590⭐</code></b> <b><code>   104🍴</code></b> [Source Code](https://github.com/eggheads/eggdrop) ⭐ 590 | 🐛 244 | 🌐 C | 📅 2026-11-14)) `GPL-2.0` `C`

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

* 🌎 [Ansible](www.ansible.com/) - Provisioning, configuration management, and application-deployment tool. (<b><code> 71460⭐</code></b> <b><code> 24462🍴</code></b> [Source Code](https://github.com/ansible/ansible) ⭐ 71,493 | 🐛 888 | 🌐 Python | 📅 2026-11-11)) `GPL-3.0` `Python`
* 🌎 [Salt](docs.saltproject.io/) - Event-driven IT automation, remote task execution, and configuration management software. (<b><code> 15754⭐</code></b> <b><code>  5615🍴</code></b> [Source Code](https://github.com/saltstack/salt) ⭐ 15,755 | 🐛 602 | 🌐 Python | 📅 2026-11-14)) `Apache-2.0` `Python`
* 🌎 [cloud-init](cloud-init.io/) - Initialization tool to automate the configuration of VMs, cloud instances, or machines on a network. (<b><code>  3866⭐</code></b> <b><code>  1190🍴</code></b> [Source Code](https://github.com/canonical/cloud-init) ⭐ 3,867 | 🐛 629 | 🌐 Python | 📅 2026-11-13)) `GPL-3.0/Apache-2.0` `Python`
* 🌎 [Rudder](www.rudder.io/) - Scalable and dynamic configuration management system for patching, security & compliance, based on CFEngine. (<b><code>   724⭐</code></b> <b><code>    94🍴</code></b> [Source Code](https://github.com/Normation/rudder) ⭐ 725 | 🐛 43 | 🌐 Scala | 📅 2026-11-13)) `GPL-3.0` `Scala`
* 🌎 [CFEngine](cfengine.com/) - Configuration management system for automated configuration and maintenance of large-scale computer systems. (<b><code>   540⭐</code></b> <b><code>   203🍴</code></b> [Source Code](https://github.com/cfengine/core) ⭐ 540 | 🐛 17 | 🌐 C | 📅 2026-11-13)) `GPL-3.0` `C`
* 🌎 [OpenVox](voxpupuli.org/openvox/) - Community fork of the last open source version of 🌎 [Puppet](www.puppet.com/), a software configuration management tool which includes its own declarative language to describe system configuration. (<b><code>   203⭐</code></b> <b><code>    68🍴</code></b> [Source Code](https://github.com/OpenVoxProject/openvox) ⭐ 203 | 🐛 132 | 🌐 Ruby | 📅 2026-11-14)) `Apache-2.0` `Ruby/C`
* 🌎 [CINC](cinc.sh/) - Free distribution of 🌎 [Chef](www.chef.io/products/chef-infra), a configuration management tool using a pure-Ruby, domain-specific language (DSL) for writing system configuration "recipes".  🌎 [Source Code](gitlab.com/cinc-project/upstream/chef)) `Apache-2.0` `Ruby`

### Configuration Management Database

**[`^        back to top        ^`](#awesome-sysadmin)**

Configuration management database (CMDB) software.

*Related: [IT Asset Management](#it-asset-management)*

* 🌎 [netbox](netbox.dev/) - IP address management (IPAM) and data center infrastructure management (DCIM) tool.  🌎 [Demo](demo.netbox.dev/), <b><code> 21880⭐</code></b> <b><code>  3194🍴</code></b> [Source Code](https://github.com/netbox-community/netbox) ⭐ 21,882 | 🐛 264 | 🌐 Python | 📅 2026-11-15)) `Apache-2.0` `Python`
* 🌎 [iTop](combodo.com/) - Complete ITIL web based service management tool. (<b><code>  1220⭐</code></b> <b><code>   303🍴</code></b> [Source Code](https://github.com/Combodo/iTop) ⭐ 1,222 | 🐛 84 | 🌐 PHP | 📅 2026-11-13)) `AGPL-3.0` `PHP`
* 🌎 [i-doit](www.i-doit.org/) - IT Documentation and CMDB. `AGPL-3.0` `PHP`

### Continuous Integration & Continuous Deployment

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Continuous integration](en.wikipedia.org/wiki/Continuous_integration) 🌎 [deployment](en.wikipedia.org/wiki/Continuous_deployment) software.

* 🌎 [Harness](www.harness.io/open-source) - End-to-end developer platform with Source Control Management, CI/CD Pipelines, Hosted Developer Environments, and Artifact Registries (fork of Drone). (<b><code> 38907⭐</code></b> <b><code>  3462🍴</code></b> [Source Code](https://github.com/harness/harness) ⭐ 38,910 | 🐛 133 | 🌐 Go | 📅 2026-11-12)) `Apache-2.0` `Go`
* 🌎 [Jenkins](jenkins-ci.org/) - Continuous Integration Server. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/jenkinsci/jenkins/) ⭐ 26,772 | 🐛 3,617 | 🌐 Java | 📅 2026-11-15)) `MIT` `Java`
* 🌎 [ArgoCD](argo-cd.readthedocs.io/en/stable/) - Declarative, GitOps continuous delivery tool for Kubernetes. (<b><code> 24606⭐</code></b> <b><code>  8141🍴</code></b> [Source Code](https://github.com/argoproj/argo-cd) ⭐ 24,612 | 🐛 4,490 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `Go`
* 🌎 [Woodpecker](woodpecker-ci.org/) - Community fork of Drone that uses Docker containers. (<b><code>  8193⭐</code></b> <b><code>   746🍴</code></b> [Source Code](https://github.com/woodpecker-ci/woodpecker) ⭐ 8,197 | 🐛 372 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `Go`
* 🌎 [Concourse](concourse-ci.org/) - Concourse is a CI tool that treats pipelines as first class objects and containerizes every step along the way.  🌎 [Demo](ci.concourse-ci.org/), <b><code>  7940⭐</code></b> <b><code>   915🍴</code></b> [Source Code](https://github.com/concourse/concourse) ⭐ 7,940 | 🐛 81 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `Go`
* 🌎 [GoCD](www.go.cd/) - Continuous delivery server. (<b><code>  7439⭐</code></b> <b><code>   985🍴</code></b> [Source Code](https://github.com/gocd/gocd) ⭐ 7,439 | 🐛 97 | 🌐 Java | 📅 2026-11-13)) `Apache-2.0` `Java/Ruby`
* 🌎 [Buildbot](buildbot.net/) - Python-based toolkit for continuous integration. (<b><code>  5490⭐</code></b> <b><code>  1688🍴</code></b> [Source Code](https://github.com/buildbot/buildbot) ⭐ 5,489 | 🐛 756 | 🌐 Python | 📅 2026-11-15)) `GPL-2.0` `Python`
* 🌎 [CDS](ovh.github.io/cds/) - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform. (<b><code>  4847⭐</code></b> <b><code>   459🍴</code></b> [Source Code](https://github.com/ovh/cds) ⭐ 4,848 | 🐛 168 | 🌐 Go | 📅 2026-11-13)) `BSD-3-Clause` `Go`
* 🌎 [werf](werf.io/) - Open Source CI/CD tool for building Docker images and deploying to Kubernetes via GitOps. (<b><code>  4738⭐</code></b> <b><code>   241🍴</code></b> [Source Code](https://github.com/werf/werf) ⭐ 4,738 | 🐛 10 | 🌐 Go | 📅 2026-11-13)) `Apache-2.0` `Go`
* 🌎 [Stategraph](stategraph.com) - GitOps-first automation platform for Terraform and OpenTofu workflows with support for self-hosted runners. (<b><code>  1329⭐</code></b> <b><code>    83🍴</code></b> [Source Code](https://github.com/stategraph/stategraph) ⭐ 1,329 | 🐛 114 | 🌐 OCaml | 📅 2026-11-14)) `MPL-2.0` `OCaml/Docker`
* <b><code>   687⭐</code></b> <b><code>   144🍴</code></b> [PHP Censor](https://github.com/php-censor/php-censor) ⭐ 687 | 🐛 24 | 🌐 PHP | 📅 2026-11-15) - Open source self-hosted continuous integration server for PHP projects. `BSD-2-Clause` `PHP`
* 🌎 [Laminar](laminar.ohwg.net) - Fast, lightweight, simple and flexible Continuous Integration. (<b><code>   363⭐</code></b> <b><code>    65🍴</code></b> [Source Code](https://github.com/ohwgiles/laminar) ⭐ 363 | 🐛 16 | 🌐 C++ | 📅 2026-11-01)) `GPL-3.0` `C++`
* 🌎 [GitLab CI](about.gitlab.com/solutions/continuous-integration/) - Gitlab's built-in, full-featured CI/CD solution.  🌎 [Source Code](gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby`

### Control Panels

**[`^        back to top        ^`](#awesome-sysadmin)**

Web hosting and server or service control panels.

* 🌎 [Cockpit](cockpit-project.org/) - Web-based graphical interface for servers. (<b><code> 15384⭐</code></b> <b><code>  1378🍴</code></b> [Source Code](https://github.com/cockpit-project/cockpit) ⭐ 15,386 | 🐛 515 | 🌐 Python | 📅 2026-11-15)) `LGPL-2.1` `C`
* 🌎 [Ajenti](ajenti.org/) - Control panel for Linux and BSD. (<b><code>  7972⭐</code></b> <b><code>   856🍴</code></b> [Source Code](https://github.com/ajenti/ajenti) ⭐ 7,973 | 🐛 10 | 🌐 Python | 📅 2026-11-01)) `MIT` `Python/Shell`
* 🌎 [MeshCentral](meshcentral.com) - A complete web-based remote monitoring and management web site. (<b><code>  7687⭐</code></b> <b><code>  1068🍴</code></b> [Source Code](https://github.com/ylianst/meshcentral) ⭐ 7,689 | 🐛 154 | 🌐 JavaScript | 📅 2026-11-10)) `Apache-2.0` `JavaScript/HTML`
* 🌎 [Webmin](www.webmin.com/) - Web-based interface for system administration for Unix. (<b><code>  6137⭐</code></b> <b><code>   805🍴</code></b> [Source Code](https://github.com/webmin/webmin) ⭐ 6,136 | 🐛 130 | 🌐 HTML | 📅 2026-11-15)) `BSD-3-Clause` `Perl`
* 🌎 [HestiaCP](hestiacp.com/) - Web server control panel (fork of VestaCP).  🌎 [Demo](demo.hestiacp.com:8083/login/), <b><code>  4574⭐</code></b> <b><code>   963🍴</code></b> [Source Code](https://github.com/hestiacp/hestiacp) ⭐ 4,578 | 🐛 178 | 🌐 Shell | 📅 2026-11-14)) `GPL-3.0` `PHP/Shell/Other`
* 🌎 [Froxlor](froxlor.org/) - Lightweight server management software with Nginx and PHP-FPM support. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/Froxlor/Froxlor/) ⭐ 1,752 | 🐛 44 | 🌐 PHP | 📅 2026-11-09)) `GPL-2.0` `PHP`
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

* 🌎 [Fabric](www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks. (<b><code> 15532⭐</code></b> <b><code>  1954🍴</code></b> [Source Code](https://github.com/fabric/fabric) ⭐ 15,532 | 🐛 509 | 🌐 Python | 📅 2026-04-10)) `BSD-2-Clause` `Python`
* 🌎 [Capistrano](capistranorb.com/) - Deploy your application to any number of machines simultaneously, in sequence or as a rolling set via SSH (rake based). (<b><code> 13013⭐</code></b> <b><code>  1738🍴</code></b> [Source Code](https://github.com/capistrano/capistrano) ⭐ 13,014 | 🐛 75 | 🌐 Ruby | 📅 2026-11-02)) `MIT` `Ruby`
* 🌎 [munki](www.munki.org/munki/) - Webserver-based repository of packages and package metadata, that allows macOS administrators to manage software installs. (<b><code>  3484⭐</code></b> <b><code>   376🍴</code></b> [Source Code](https://github.com/munki/munki) ⭐ 3,484 | 🐛 71 | 🌐 Swift | 📅 2026-11-13)) `Apache-2.0` `Python`
* 🌎 [CloudStack](cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services. (<b><code>  3134⭐</code></b> <b><code>  1423🍴</code></b> [Source Code](https://github.com/apache/cloudstack) ⭐ 3,134 | 🐛 1,276 | 🌐 Java | 📅 2026-11-15)) `Apache-2.0` `Java/Python`
* 🌎 [Cobbler](cobbler.github.io/) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments. (<b><code>  2780⭐</code></b> <b><code>   657🍴</code></b> [Source Code](https://github.com/cobbler/cobbler) ⭐ 2,780 | 🐛 303 | 🌐 Python | 📅 2026-11-11)) `GPL-2.0` `Python`
* 🌎 [Overcast](andrewchilds.github.io/overcast/) - Deploy VMs across different cloud providers, and run commands and scripts across any or all of them in parallel via SSH. (<b><code>   482⭐</code></b> <b><code>    36🍴</code></b> [Source Code](https://github.com/andrewchilds/overcast) ⭐ 482 | 🐛 10 | 🌐 JavaScript | 📅 2026-05-20)) `MIT` `Nodejs`
* 🌎 [FaynoSync](faynosync.com) - Self-hosted Dynamic Update Server with statistics, supporting multiple updaters. Flexible features for seamless app updates and insights. (<b><code>   160⭐</code></b> <b><code>     5🍴</code></b> [Source Code](https://github.com/ku9nov/faynoSync) ⭐ 160 | 🐛 3 | 🌐 Go | 📅 2026-11-05), <b><code>     6⭐</code></b> <b><code>     2🍴</code></b> [Clients](https://github.com/ku9nov/faynoSync-dashboard) ⚠️ Archived)) `Apache-2.0` `Docker/Go`
* 🌎 [CloudSlang](www.cloudslang.io/) - Flow-based orchestration tool for managing deployed applications, with Docker capabilities. (<b><code>    95⭐</code></b> <b><code>    43🍴</code></b> [Source Code](https://github.com/CloudSlang/score) ⭐ 95 | 🐛 18 | 🌐 Java | 📅 2026-11-12)) `Apache-2.0` `Java`
* <b><code>    64⭐</code></b> <b><code>    30🍴</code></b> [Genesis](https://github.com/genesis-community/genesis) ⭐ 64 | 🐛 52 | 🌐 Perl | 📅 2026-10-25) - A template framework for multi-environment BOSH deployments. `MIT` `Perl`

### Diagramming

**[`^        back to top        ^`](#awesome-sysadmin)**

Tools used to create diagrams of networks, flows, etc.

* 🌎 [Diagrams.net](app.diagrams.net/) - A.K.A. 🌎 [Draw.io](app.diagrams.net/). Easy to use Diagram UI with a plethora of templates. (<b><code>  9361⭐</code></b> <b><code>  1378🍴</code></b> [Source Code](https://github.com/jgraph/drawio) ⭐ 9,370 | 🐛 42 | 🌐 JavaScript | 📅 2026-11-04)) `Apache-2.0` `JavaScript/Docker`
* 🌎 [Mermaid](mermaid-js.github.io/mermaid-live-editor/) - Javascript module with a unique, easy, shorthand syntax. Integrates into several other tools like Grafana. (<b><code>  6908⭐</code></b> <b><code>  1194🍴</code></b> [Source Code](https://github.com/mermaid-js/mermaid-live-editor) ⭐ 6,907 | 🐛 99 | 🌐 TypeScript | 📅 2026-11-14)) `MIT` `Nodejs/Docker`
* 🌎 [Kroki](kroki.io) - API for generating diagrams from textual descriptions. (<b><code>  4406⭐</code></b> <b><code>   326🍴</code></b> [Source Code](https://github.com/yuzutech/kroki) ⭐ 4,407 | 🐛 130 | 🌐 JavaScript | 📅 2026-11-12)) `MIT` `Java`

### Distributed Filesystems

**[`^        back to top        ^`](#awesome-sysadmin)**

Network distributed filesystems.

*See also: 🌎 [awesome-selfhosted/File Transfer - Object Storage & File Servers](awesome-selfhosted.net/tags/file-transfer---object-storage--file-servers.html)*

* 🌎 [Ceph](ceph.com/en/) - Distributed object, block, and file storage platform. (<b><code> 17224⭐</code></b> <b><code>  6566🍴</code></b> [Source Code](https://github.com/ceph/ceph) ⭐ 17,225 | 🐛 2,016 | 🌐 C++ | 📅 2026-11-14)) `LGPL-3.0` `C++`
* <b><code> 17185⭐</code></b> <b><code>  3169🍴</code></b> [Kubo](https://github.com/ipfs/kubo) ⭐ 17,185 | 🐛 889 | 🌐 Go | 📅 2026-11-01) - Implementation of IPFS, a global, versioned, peer-to-peer filesystem that seeks to connect all computing devices with the same system of files. `Apache-2.0/MIT` `Go`
* 🌎 [Hadoop Distributed Filesystem (HDFS)](hadoop.apache.org/) - Distributed file system that provides high-throughput access to application data. (<b><code> 15710⭐</code></b> <b><code>  9256🍴</code></b> [Source Code](https://github.com/apache/hadoop) ⭐ 15,713 | 🐛 339 | 🌐 Java | 📅 2026-11-15)) `Apache-2.0` `Java`
* 🌎 [JuiceFS](juicefs.com/) - Distributed POSIX file system built on top of Redis and S3. (<b><code> 14736⭐</code></b> <b><code>  1358🍴</code></b> [Source Code](https://github.com/juicedata/juicefs) ⭐ 14,737 | 🐛 257 | 🌐 Go | 📅 2026-11-13)) `Apache-2.0` `Go`
* 🌎 [Perkeep](perkeep.org/) - A set of open source formats, protocols, and software for modeling, storing, searching, sharing and synchronizing data (previously Camlistore). (<b><code>  7270⭐</code></b> <b><code>   489🍴</code></b> [Source Code](https://github.com/perkeep/perkeep) ⭐ 7,270 | 🐛 400 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `C`
* 🌎 [GlusterFS](www.gluster.org/) - Software-defined distributed storage that can scale to several petabytes, with interfaces for object, block and file storage. (<b><code>  5270⭐</code></b> <b><code>  1109🍴</code></b> [Source Code](https://github.com/gluster/glusterfs) ⭐ 5,272 | 🐛 329 | 🌐 C | 📅 2026-11-13)) `GPL-2.0/LGPL-3.0` `C`
* 🌎 [MooseFS](moosefs.com/) - Fault tolerant, network distributed file system. (<b><code>  2011⭐</code></b> <b><code>   241🍴</code></b> [Source Code](https://github.com/moosefs/moosefs) ⭐ 2,011 | 🐛 195 | 🌐 C | 📅 2026-05-18)) `GPL-2.0` `C`
* 🌎 [TahoeLAFS](tahoe-lafs.org/trac/tahoe-lafs) - Secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system. (<b><code>  1453⭐</code></b> <b><code>   263🍴</code></b> [Source Code](https://github.com/tahoe-lafs/tahoe-lafs) ⭐ 1,454 | 🐛 28 | 🌐 Python | 📅 2026-11-15)) `GPL-2.0` `Python`
* 🌎 [DRBD](linbit.com/drbd/) - Distributed replicated storage system, implemented as a Linux kernel driver. (<b><code>   729⭐</code></b> <b><code>   118🍴</code></b> [Source Code](https://github.com/LINBIT/drbd) ⭐ 729 | 🐛 57 | 🌐 C | 📅 2026-11-13)) `GPL-2.0` `C`
* 🌎 [XtreemFS](www.xtreemfs.org/) - Distributed, replicated and fault-tolerant file system for federated IT infrastructures.. (<b><code>   348⭐</code></b> <b><code>    65🍴</code></b> [Source Code](https://github.com/xtreemfs/xtreemfs) ⭐ 348 | 🐛 69 | 🌐 Java | 📅 2024-10-07)) `BSD-3-Clause` `Java`
* 🌎 [Lustre](www.lustre.org/) - Parallel distributed file system, generally used for large-scale cluster computing.  🌎 [Source Code](git.whamcloud.com/?p=fs/lustre-release.git;a=summary)) `GPL-2.0` `C`
* 🌎 [OpenAFS](www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.  🌎 [Source Code](git.openafs.org/?p=openafs.git;a=summary)) `IPL-1.0` `C`
* 🌎 [Openstack Swift](docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.  🌎 [Source Code](opendev.org/openstack/swift)) `Apache-2.0` `Python`

### DNS - Control Panels & Domain Management

**[`^        back to top        ^`](#awesome-sysadmin)**

DNS server control panels, web interfaces and domain management tools.

*Related: [DNS - Servers](#dns---servers)*

*See also: 🌎 [awesome-selfhosted/DNS](awesome-selfhosted.net/tags/dns.html)*

* 🌎 [DNSControl](dnscontrol.org/) - Synchronize your DNS to multiple providers from a simple DSL. (<b><code>  4006⭐</code></b> <b><code>   551🍴</code></b> [Source Code](https://github.com/DNSControl/dnscontrol) ⭐ 4,007 | 🐛 35 | 🌐 Go | 📅 2026-11-14)) `MIT` `Go/Docker`
* <b><code>  3781⭐</code></b> <b><code>   453🍴</code></b> [octoDNS](https://github.com/octodns/octodns) ⭐ 3,783 | 🐛 6 | 🌐 Python | 📅 2026-11-06) - DNS as code - Tools for managing DNS across multiple providers. `MIT` `Python`
* 🌎 [nsupdate.info](www.nsupdate.info/) - Dynamic DNS service.  🌎 [Demo](www.nsupdate.info/account/register/), <b><code>  1137⭐</code></b> <b><code>   123🍴</code></b> [Source Code](https://github.com/nsupdate-info/nsupdate.info) ⭐ 1,137 | 🐛 55 | 🌐 Python | 📅 2026-08-17)) `BSD-3-Clause` `Python`
* 🌎 [Poweradmin](www.poweradmin.org/) - Web-based DNS control panel for PowerDNS server. (<b><code>   929⭐</code></b> <b><code>   299🍴</code></b> [Source Code](https://github.com/poweradmin/poweradmin) ⭐ 930 | 🐛 219 | 🌐 PHP | 📅 2026-11-15)) `GPL-3.0` `PHP`
* 🌎 [DomainMOD](domainmod.org) - Manage your domains and other internet assets in a central location. (<b><code>   604⭐</code></b> <b><code>   119🍴</code></b> [Source Code](https://github.com/domainmod/domainmod) ⭐ 604 | 🐛 6 | 🌐 PHP | 📅 2026-11-14)) `GPL-3.0` `PHP`
* 🌎 [SPF Toolbox](spftoolbox.com) - Application to look up DNS records such as SPF, MX, Whois, and more. (<b><code>   302⭐</code></b> <b><code>    67🍴</code></b> [Source Code](https://github.com/charlesabarnes/SPFtoolbox) ⭐ 302 | 🐛 11 | 🌐 PHP | 📅 2026-02-13)) `MIT` `PHP`
* 🌎 [Designate](wiki.openstack.org/wiki/Designate) - DNSaaS services for OpenStack.  🌎 [Source Code](opendev.org/openstack/designate)) `Apache-2.0` `Python`

### DNS - Servers

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [DNS](en.wikipedia.org/wiki/Name_server) servers.

*Related: [DNS - Control Panels & Domain Management](#dns---control-panels--domain-management)*

*See also: 🌎 [awesome-selfhosted/DNS](awesome-selfhosted.net/tags/dns.html)*

* 🌎 [CoreDNS](coredns.io/) - Flexible DNS server. (<b><code> 14429⭐</code></b> <b><code>  2562🍴</code></b> [Source Code](https://github.com/coredns/coredns) ⭐ 14,429 | 🐛 262 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `Go`
* 🌎 [Unbound](nlnetlabs.nl/projects/unbound/about/) - Validating, recursive, and caching DNS resolver. (<b><code>  5069⭐</code></b> <b><code>   473🍴</code></b> [Source Code](https://github.com/NLnetLabs/unbound) ⭐ 5,067 | 🐛 408 | 🌐 C | 📅 2026-11-13)) `BSD-3-Clause` `C`
* 🌎 [PowerDNS Authoritative Server](doc.powerdns.com/authoritative/) - Versatile nameserver which supports a large number of backends. (<b><code>  4520⭐</code></b> <b><code>  1035🍴</code></b> [Source Code](https://github.com/PowerDNS/pdns) ⭐ 4,522 | 🐛 925 | 🌐 C++ | 📅 2026-11-14)) `GPL-2.0` `C++`
* 🌎 [NSD](www.nlnetlabs.nl/projects/nsd/about/) - Authoritative DNS name server developed speed, reliability, stability and security. (<b><code>   575⭐</code></b> <b><code>   121🍴</code></b> [Source Code](https://github.com/NLnetLabs/nsd) ⭐ 575 | 🐛 85 | 🌐 C | 📅 2026-11-13)) `BSD-3-Clause` `C`
* 🌎 [Yadifa](www.yadifa.eu/) - Clean, small, light and RFC-compliant name server implementation developed from scratch by .eu. (<b><code>    81⭐</code></b> <b><code>    15🍴</code></b> [Source Code](https://github.com/yadifa/yadifa) ⭐ 81 | 🐛 10 | 🌐 C | 📅 2026-09-15)) `BSD-3-Clause` `C`
* 🌎 [Bind](www.isc.org/bind/) - Versatile, classic, complete name server software.  🌎 [Source Code](gitlab.isc.org/isc-projects/bind9)) `MPL-2.0` `C`
* 🌎 [djbdns](cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.  🌎 [Source Code](salsa.debian.org/debian/djbdns)) `CC0-1.0` `C`
* 🌎 [dnsmasq](www.thekelleys.org.uk/dnsmasq/doc.html) - Provides network infrastructure for small networks: DNS, DHCP, router advertisement and network boot.  🌎 [Source Code](thekelleys.org.uk/gitweb/?p=dnsmasq.git;a=tree)) `GPL-2.0` `C`
* 🌎 [Knot](www.knot-dns.cz/) - High performance authoritative-only DNS server.  🌎 [Source Code](gitlab.nic.cz/knot/knot-dns)) `GPL-3.0` `C`

### Editors

**[`^        back to top        ^`](#awesome-sysadmin)**

Open-source code editors.

* 🌎 [Vim](www.vim.org) - A highly configurable text editor built to enable efficient editing. (<b><code> 41320⭐</code></b> <b><code>  6333🍴</code></b> [Source Code](https://github.com/vim/vim) ⭐ 41,342 | 🐛 1,792 | 🌐 Vim Script | 📅 2026-11-14)) `Vim` `C`
* 🌎 [VSCodium](vscodium.com/) - An open source cross-platform extensible code editor based on 🌎 [VS Code by Microsoft](code.visualstudio.com/) removing their non-free additions. (<b><code> 34102⭐</code></b> <b><code>  1925🍴</code></b> [Source Code](https://github.com/VSCodium/vscodium) ⭐ 34,121 | 🐛 153 | 🌐 Shell | 📅 2026-10-31)) `MIT` `TypeScript`
* 🌎 [Micro](micro-editor.github.io/) - A modern and intuitive terminal-based text editor. (<b><code> 29894⭐</code></b> <b><code>  1402🍴</code></b> [Source Code](https://github.com/micro-editor/micro) ⭐ 29,897 | 🐛 915 | 🌐 Go | 📅 2026-11-15)) `MIT` `Go`
* 🌎 [Notepad++](notepad-plus-plus.org/) - GPLv2 multi-language editor with syntax highlighting for Windows. (<b><code> 29882⭐</code></b> <b><code>  5437🍴</code></b> [Source Code](https://github.com/notepad-plus-plus/notepad-plus-plus) ⭐ 29,894 | 🐛 2,917 | 🌐 C++ | 📅 2026-11-15)) `GPL-2.0` `C++`
* 🌎 [GNU Emacs](www.gnu.org/software/emacs/) - An extensible, customizable text editor-and more. (<b><code>  5251⭐</code></b> <b><code>  1425🍴</code></b> [Source Code](https://github.com/emacs-mirror/emacs) ⭐ 5,251 | 🐛 16 | 🌐 Emacs Lisp | 📅 2026-11-15)) `GPL-3.0` `C`
* 🌎 [Geany](www.geany.org/) - GTK2 text editor. (<b><code>  3757⭐</code></b> <b><code>   669🍴</code></b> [Source Code](https://github.com/geany/geany) ⭐ 3,757 | 🐛 1,292 | 🌐 C | 📅 2026-11-01)) `GPL-2.0` `C/C++`
* 🌎 [Phoenix Code](phcode.dev/) - Code editor for web designers and front-end developers. (<b><code>  3024⭐</code></b> <b><code>   212🍴</code></b> [Source Code](https://github.com/phcode-dev/phoenix) ⭐ 3,024 | 🐛 267 | 🌐 JavaScript | 📅 2026-11-02)) `MIT` `JavaScript`
* <b><code>   780⭐</code></b> <b><code>    31🍴</code></b> [Atom Community](https://github.com/atom-community/atom) ⭐ 780 | 🐛 52 | 🌐 JavaScript | 📅 2025-08-19) - A fork of <b><code> 60692⭐</code></b> <b><code> 17164🍴</code></b> [atom](https://github.com/atom/atom) ⚠️ Archived) A hackable text editor from Github. `MIT` `JavaScript`
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

* <b><code>  6626⭐</code></b> <b><code>   369🍴</code></b> [lldap](https://github.com/lldap/lldap) ⭐ 6,626 | 🐛 155 | 🌐 Rust | 📅 2026-09-26) - Light (simplified) LDAP implementation with a simple, intuitive web interface and GraphQL support. `GPL-3.0` `Rust`
* 🌎 [FreeRADIUS](freeradius.org/) - Multi-protocol policy server (radiusd) that implements RADIUS, DHCP, BFD, and ARP and associated client/PAM library/Apache module. (<b><code>  2650⭐</code></b> <b><code>  1209🍴</code></b> [Source Code](https://github.com/FreeRADIUS/freeradius-server) ⭐ 2,650 | 🐛 98 | 🌐 C | 📅 2026-11-15)) `GPL-2.0` `C`
* 🌎 [LTB Self-Service Password](www.ltb-project.org/documentation/self-service-password.html) - Web interface to change and reset LDAP passwords. (<b><code>  1349⭐</code></b> <b><code>   354🍴</code></b> [Source Code](https://github.com/ltb-project/self-service-password) ⭐ 1,349 | 🐛 71 | 🌐 PHP | 📅 2026-11-13)) `GPL-3.0` `PHP`
* 🌎 [389 Directory Server](www.port389.org/) - Enterprise-class Open Source LDAP server for Linux. (<b><code>   300⭐</code></b> <b><code>   132🍴</code></b> [Source Code](https://github.com/389ds/389-ds-base) ⭐ 301 | 🐛 419 | 🌐 C | 📅 2026-11-14)) `GPL-3.0` `C`
* 🌎 [Apache Directory Server](directory.apache.org/apacheds/) - Extensible and embeddable directory server, certified LDAPv3 compatible, with Kerberos 5 and Change Password Protocol support, triggers, stored procedures, queues and views. (<b><code>   189⭐</code></b> <b><code>   106🍴</code></b> [Source Code](https://github.com/apache/directory-server) ⭐ 189 | 🐛 16 | 🌐 Java | 📅 2026-11-10)) `Apache-2.0` `Java`
* 🌎 [Wren:DS](wrensecurity.org/projects/wrends/) - LDAPv3-compliant directory service providing a high-performance, highly available, and secure identity data store for enterprise environments. (<b><code>    45⭐</code></b> <b><code>    19🍴</code></b> [Source Code](https://github.com/WrenSecurity/wrends) ⭐ 45 | 🐛 27 | 🌐 Java | 📅 2026-11-11)) `CDDL-1.0` `Java`
* 🌎 [FreeIPA](www.freeipa.org/) - Integrated security information management solution combining Linux (Fedora), 389 Directory Server, Kerberos, NTP, DNS, and Dogtag Certificate System (web interface and command-line administration tools).  🌎 [Source Code](pagure.io/freeipa)) `GPL-3.0` `Python/C/JavaScript`
* 🌎 [OpenLDAP](www.openldap.org/) - Open-source implementation of the Lightweight Directory Access Protocol (server, libraries and clients).  🌎 [Source Code](git.openldap.org/openldap/openldap)) `OLDAP-2.8` `C`

### Identity Management - Single Sign-On (SSO)

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Single sign-on (SSO)](en.wikipedia.org/wiki/Single_sign-on) is an authentication scheme that allows a user to log in with a single ID to any of several related, yet independent, software systems.

* 🌎 [KeyCloak](www.keycloak.org) - Open Source Identity and Access Management. (<b><code> 37864⭐</code></b> <b><code>  9189🍴</code></b> [Source Code](https://github.com/keycloak/keycloak) ⭐ 37,873 | 🐛 3,583 | 🌐 Java | 📅 2026-11-15)) `Apache-2.0` `Java`
* 🌎 [Authelia](www.authelia.com/) - The Single Sign-On Multi-Factor portal for web apps. (<b><code> 29652⭐</code></b> <b><code>  1536🍴</code></b> [Source Code](https://github.com/authelia/authelia) ⭐ 29,657 | 🐛 112 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `Go`
* 🌎 [Authentik](goauthentik.io/) - Flexible identity provider with support for different protocols. (OAuth 2.0, SAML, LDAP and Radius). (<b><code> 26345⭐</code></b> <b><code>  2134🍴</code></b> [Source Code](https://github.com/goauthentik/authentik) ⭐ 26,353 | 🐛 940 | 🌐 Python | 📅 2026-11-15)) `MIT` `Python`
* 🌎 [Wren:AM](wrensecurity.org/projects/wrenam/) - Access management platform providing adaptive authentication, SSO, federation, and fine-grained authorization for web and API resources. (<b><code>    55⭐</code></b> <b><code>    32🍴</code></b> [Source Code](https://github.com/WrenSecurity/wrenam) ⭐ 55 | 🐛 73 | 🌐 Java | 📅 2026-11-14)) `CDDL-1.0` `Java`
* 🌎 [Wren:IG](wrensecurity.org/projects/wrenig/) - Identity gateway and reverse proxy enforcing authentication, authorization, and SSO without requiring application changes. (<b><code>     7⭐</code></b> <b><code>    31🍴</code></b> [Source Code](https://github.com/WrenSecurity/wrenig) ⭐ 7 | 🐛 3 | 🌐 Java | 📅 2026-11-11)) `CDDL-1.0` `Java`

### Identity Management - Tools and web interfaces

**[`^        back to top        ^`](#awesome-sysadmin)**

Miscellaneous utilities and web interfaces for identity management systems.

* 🌎 [ZITADEL](zitadel.com/) - Cloud-native Identity & Access Management solution providing a platform for secure authentication, authorization and identity management. (<b><code> 15581⭐</code></b> <b><code>  1430🍴</code></b> [Source Code](https://github.com/zitadel/zitadel) ⭐ 15,586 | 🐛 1,383 | 🌐 Go | 📅 2026-11-13)) `Apache-2.0` `Go/Docker/K8S`
* 🌎 [Smallstep Certificates](smallstep.com/certificates/) - A private certificate authority (X.509 & SSH) and related tools for secure automated certificate management. (<b><code>  9067⭐</code></b> <b><code>   617🍴</code></b> [Source Code](https://github.com/smallstep/certificates) ⭐ 9,069 | 🐛 311 | 🌐 Go | 📅 2026-11-10)) `Apache-2.0` `Go`
* 🌎 [OpenBao](openbao.org) - Static and dynamic secrets manager including X.509 & SSH CAs, JWT issuer, and KMS under the OpenSSF. (<b><code>  9008⭐</code></b> <b><code>   689🍴</code></b> [Source Code](https://github.com/openbao/openbao) ⭐ 9,021 | 🐛 352 | 🌐 Go | 📅 2026-11-12), <b><code>    67⭐</code></b> <b><code>    38🍴</code></b> [Clients](https://github.com/openbao/openbao-plugins) ⭐ 67 | 🐛 21 | 🌐 Go | 📅 2026-11-14)) `MPL-2.0` `Go/Docker/K8S/deb`
* 🌎 [Pomerium](www.pomerium.io/) - An identity and context aware access-proxy inspired by BeyondCorp. (<b><code>  5104⭐</code></b> <b><code>   372🍴</code></b> [Source Code](https://github.com/pomerium/pomerium) ⭐ 5,105 | 🐛 177 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `Docker/Go`
* <b><code>  4488⭐</code></b> <b><code>  1230🍴</code></b> [easy-rsa](https://github.com/OpenVPN/easy-rsa) ⭐ 4,490 | 🐛 26 | 🌐 Shell | 📅 2026-10-18) - Bash script to build and manage a PKI CA. `GPL-2.0` `Shell`
* 🌎 [LDAP Account Manager (LAM)](www.ldap-account-manager.org/lamcms/) - Web frontend for managing entries (e.g. users, groups, DHCP settings) stored in an LDAP directory. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/LDAPAccountManager/lam/) ⭐ 498 | 🐛 12 | 🌐 PHP | 📅 2026-11-13)) `GPL-3.0` `PHP`
* 🌎 [Fusion Directory](www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP. (<b><code>   189⭐</code></b> <b><code>    37🍴</code></b> [Source Code](https://github.com/fusiondirectory/fusiondirectory) ⭐ 189 | 🐛 1 | 🌐 PHP | 📅 2026-11-12)) `GPL-2.0` `PHP`
* 🌎 [Wren:IDM](wrensecurity.org/projects/wrenidm/) - Identity management and governance platform for lifecycle management, access governance, and comprehensive auditability. (<b><code>    48⭐</code></b> <b><code>    20🍴</code></b> [Source Code](https://github.com/WrenSecurity/wrenidm) ⭐ 48 | 🐛 32 | 🌐 Java | 📅 2026-11-13)) `CDDL-1.0` `Java`
* 🌎 [BounCA](bounca.org/) - A personal SSL Key / Certificate Authority web-based tool for creating self-signed certificates.  🌎 [Source Code](gitlab.com/bounca/bounca/)) `Apache-2.0` `Python`
* 🌎 [Libravatar](www.libravatar.org/) - Libravatar is a service which delivers your avatar (profile picture) to other websites.  🌎 [Source Code](git.linux-kernel.at/oliver/ivatar/)) `AGPL-3.0` `Python`
* 🌎 [Samba](www.samba.org/) - Active Directory and CIFS protocol implementation.  🌎 [Source Code](download.samba.org/pub/samba/)) `GPL-3.0` `C`

### IT Asset Management

**[`^        back to top        ^`](#awesome-sysadmin)**

IT 🌎 [asset management](en.wikipedia.org/wiki/Asset_management) software.

* 🌎 [Snipe IT](snipeitapp.com/) - Asset & license management software. (<b><code> 15187⭐</code></b> <b><code>  4067🍴</code></b> [Source Code](https://github.com/grokability/snipe-it) ⭐ 15,190 | 🐛 888 | 🌐 PHP | 📅 2026-11-14)) `AGPL-3.0` `PHP`
* 🌎 [GLPI](www.glpi-project.org/) - Information Resource-Manager with an additional Administration Interface. (<b><code>  6594⭐</code></b> <b><code>  1869🍴</code></b> [Source Code](https://github.com/glpi-project/glpi) ⭐ 6,598 | 🐛 495 | 🌐 PHP | 📅 2026-11-13)) `GPL-3.0` `PHP`
* 🌎 [Ralph](ralph.allegro.tech/) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks. (<b><code>  2533⭐</code></b> <b><code>   591🍴</code></b> [Demo](https://github.com/allegro/ralph#live-demo) ⭐ 2,533 | 🐛 123 | 🌐 Python | 📅 2026-11-13), <b><code>  2533⭐</code></b> <b><code>   591🍴</code></b> [Source Code](https://github.com/allegro/ralph) ⭐ 2,533 | 🐛 123 | 🌐 Python | 📅 2026-11-13)) `Apache-2.0` `Python/Docker`
* 🌎 [RackTables](racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration.  🌎 [Demo](www.racktables.org/demo.php), <b><code>   812⭐</code></b> <b><code>   265🍴</code></b> [Source Code](https://github.com/RackTables/racktables) ⭐ 812 | 🐛 22 | 🌐 PHP | 📅 2026-06-26)) `GPL-2.0` `PHP`
* 🌎 [openDCIM](opendcim.org/) - GPL v3 Data Center Inventory Management (DCIM).  🌎 [Demo](opendcim.org/demo.html), <b><code>   372⭐</code></b> <b><code>   224🍴</code></b> [Source Code](https://github.com/opendcim/openDCIM) ⭐ 372 | 🐛 131 | 🌐 PHP | 📅 2026-10-28)) `GPL-3.0` `PHP/JavaScript`
* 🌎 [OCS Inventory NG](ocsinventory-ng.org/) - Asset management and deployment solution for all devices in your IT Department. ([Source Code](https://github.com/OCSInventory-NG)) `GPL-2.0` `PHP/Perl`
* 🌎 [OPSI](www.opsi.org) - Hardware and software inventory, client management, deployment, and patching for Linux and Windows. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/opsi-org/))) `GPL-3.0/AGPL-3.0` `OVF/Python`

### Log Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Log management tools: collect, parse, visualize...

* 🌎 [Loki](grafana.com/oss/loki/) - Log aggregation system designed to store and query logs from all your applications and infrastructure. (<b><code> 29160⭐</code></b> <b><code>  4184🍴</code></b> [Source Code](https://github.com/grafana/loki) ⭐ 29,159 | 🐛 1,063 | 🌐 Go | 📅 2026-11-15)) `AGPL-3.0` `Go`
* 🌎 [GoAccess](goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal or through the browser. (<b><code> 21131⭐</code></b> <b><code>  1212🍴</code></b> [Source Code](https://github.com/allinurl/goaccess) ⭐ 21,132 | 🐛 449 | 🌐 C | 📅 2026-11-13)) `MIT` `C`
* 🌎 [Fluentd](www.fluentd.org/) - Data collector for unified logging layer. (<b><code> 13614⭐</code></b> <b><code>  1410🍴</code></b> [Source Code](https://github.com/fluent/fluentd) ⭐ 13,616 | 🐛 127 | 🌐 Ruby | 📅 2026-11-15)) `Apache-2.0` `Ruby`
* 🌎 [Flume](flume.apache.org/) - Distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data. (<b><code>  2572⭐</code></b> <b><code>  1536🍴</code></b> [Source Code](https://github.com/apache/logging-flume) ⭐ 2,572 | 🐛 79 | 🌐 Java | 📅 2026-11-10)) `Apache-2.0` `Java`
* 🌎 [rsyslog](www.rsyslog.com/) - Rocket-fast system for log processing. (<b><code>  2348⭐</code></b> <b><code>   743🍴</code></b> [Source Code](https://github.com/rsyslog/rsyslog) ⭐ 2,348 | 🐛 295 | 🌐 C | 📅 2026-11-14)) `GPL-3.0` `C`
* 🌎 [reaction](reaction.ppom.me/) - A lightweight daemon that scans program outputs for repeated patterns, and takes action.  🌎 [Source Code](framagit.org/ppom/reaction)) `AGPL-3.0` `Rust`

### Mail Clients

**[`^        back to top        ^`](#awesome-sysadmin)**

An 🌎 [email client](en.wikipedia.org/wiki/Email_client), email reader or, more formally, message user agent (MUA) or mail user agent is a computer program used to access and manage a user's email.

* [ImapSync](http://imapsync.lamiral.info/) - Simple IMAP migration tool for copying mailboxes to other servers. (<b><code>  4208⭐</code></b> <b><code>   534🍴</code></b> [Source Code](https://github.com/imapsync/imapsync) ⭐ 4,209 | 🐛 199 | 🌐 Shell | 📅 2026-09-24)) `NLPL` `Perl`
* 🌎 [Sylpheed](sylpheed.sraoss.jp/en/) - Still developed predecessor to Claws Mail, lightweight mail client. (<b><code>   193⭐</code></b> <b><code>    23🍴</code></b> [Source Code](https://github.com/sylpheed-mail/sylpheed) ⭐ 194 | 🐛 71 | 🌐 C | 📅 2024-05-04)) `GPL-2.0` `C`
* 🌎 [aerc](aerc-mail.org/) - Terminal MUA with a focus on plaintext and features for developers.  🌎 [Source Code](git.sr.ht/~rjarry/aerc)) `MIT` `Go`
* [Claws Mail](http://www.claws-mail.org/) - Old school email client (and news reader), based on GTK+.  🌎 [Source Code](git.claws-mail.org/?p=claws.git;a=tree)) `GPL-3.0` `C`
* [Mutt](http://www.mutt.org/) - Small but very powerful text-based mail client.  🌎 [Source Code](gitlab.com/muttmua/mutt)) `GPL-2.0` `C`
* 🌎 [Thunderbird](www.thunderbird.net/) - Free email application that's easy to set up and customize.  🌎 [Source Code](hg.mozilla.org/comm-central/file)) `MPL-2.0` `C/C++`

### Metrics & Metric Collection

**[`^        back to top        ^`](#awesome-sysadmin)**

Metric gathering and display software.

*Related: [Databases](#databases), [Monitoring & Status Pages](#monitoring--status-pages)*

* 🌎 [Grafana](grafana.com/) - A Graphite & InfluxDB Dashboard and Graph Editor. (<b><code> 77897⭐</code></b> <b><code> 14978🍴</code></b> [Source Code](https://github.com/grafana/grafana) ⭐ 77,910 | 🐛 3,293 | 🌐 TypeScript | 📅 2026-11-15)) `AGPL-3.0` `Go`
* 🌎 [VictoriaMetrics](victoriametrics.com/) - Fast, cost-effective time series database and monitoring solution; drop-in replacement for Prometheus with PromQL/MetricsQL support. (<b><code> 18104⭐</code></b> <b><code>  1810🍴</code></b> [Source Code](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 18,112 | 🐛 791 | 🌐 Go | 📅 2026-11-14)) `Apache-2.0` `Go`
* <b><code> 18075⭐</code></b> <b><code>  1935🍴</code></b> [Statsd](https://github.com/statsd/statsd) ⭐ 18,076 | 🐛 93 | 🌐 JavaScript | 📅 2025-05-20) - Daemon that listens for statistics like counters and timers, sent over UDP or TCP, and sends aggregates to one or more pluggable backend services. `MIT` `Nodejs`
* <b><code> 17905⭐</code></b> <b><code>  5853🍴</code></b> [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,907 | 🐛 449 | 🌐 Go | 📅 2026-11-13) - Plugin-driven server agent for collecting, processing, aggregating, and writing metrics. `MIT` `Go`
* 🌎 [Beats](www.elastic.co/beats/) - Single-purpose data shippers that send data from hundreds or thousands of machines and systems to Logstash or Elasticsearch. (<b><code> 12651⭐</code></b> <b><code>  5018🍴</code></b> [Source Code](https://github.com/elastic/beats) ⭐ 12,652 | 🐛 1,118 | 🌐 Go | 📅 2026-11-14)) `Apache-2.0` `Go`
* 🌎 [Graphite](graphite.readthedocs.org/en/latest/) - Scalable graphing server. (<b><code>  6138⭐</code></b> <b><code>  1253🍴</code></b> [Source Code](https://github.com/graphite-project/graphite-web) ⭐ 6,139 | 🐛 20 | 🌐 JavaScript | 📅 2026-11-11)) `Apache-2.0` `Python`
* 🌎 [Collectd](collectd.org/) - System statistics collection daemon. (<b><code>  3368⭐</code></b> <b><code>  1251🍴</code></b> [Source Code](https://github.com/collectd/collectd) ⭐ 3,368 | 🐛 789 | 🌐 C | 📅 2026-10-27)) `MIT` `C`
* 🌎 [RRDtool](oss.oetiker.ch/rrdtool/) - Industry standard, high performance data logging and graphing system for time series data. (<b><code>  1122⭐</code></b> <b><code>   291🍴</code></b> [Source Code](https://github.com/oetiker/rrdtool-1.x) ⭐ 1,122 | 🐛 173 | 🌐 C | 📅 2026-11-11)) `GPL-2.0` `C`

### Miscellaneous

**[`^        back to top        ^`](#awesome-sysadmin)**

Software that does not fit in another section.

* 🌎 [Chocolatey](chocolatey.org/) - The package manager for Windows. (<b><code> 11565⭐</code></b> <b><code>   966🍴</code></b> [Source Code](https://github.com/chocolatey/choco) ⭐ 11,568 | 🐛 530 | 🌐 C# | 📅 2026-11-11)) `Apache-2.0` `C#/PowerShell`
* 🌎 [Fog](www.fogproject.org/) - Cloning/imaging solution/rescue suite. (<b><code>  1702⭐</code></b> <b><code>   290🍴</code></b> [Source Code](https://github.com/FOGProject/fogproject) ⭐ 1,703 | 🐛 6 | 🌐 PHP | 📅 2026-11-13)) `GPL-3.0` `PHP/Shell`
* 🌎 [phpList](www.phplist.org/) - Newsletter and email marketing software. (<b><code>   883⭐</code></b> <b><code>   289🍴</code></b> [Source Code](https://github.com/phpList/phplist3) ⭐ 883 | 🐛 100 | 🌐 PHP | 📅 2026-11-02)) `AGPL-3.0` `PHP`
* 🌎 [Clonezilla](clonezilla.org/) - Partition and disk imaging/cloning program.  🌎 [Source Code](clonezilla.org/downloads/src/)) `GPL-2.0` `Perl/Shell/Other`
* 🌎 [DadaMail](dadamailproject.com/) - Mailing List Manager, written in Perl.  🌎 [Source Code](sourceforge.net/projects/dadamail/files/)) `GPL-2.0` `Perl`

### Monitoring & Status Pages

**[`^        back to top        ^`](#awesome-sysadmin)**

Monitoring software.

*Related: [Metrics & Metric Collection](#metrics--metric-collection)*

* 🌎 [Uptime Kuma](uptime.kuma.pet/) - Modern, self-hosted monitoring tool with a clean UI and rich notification support.  🌎 [Demo](demo.kuma.pet/start-demo), <b><code> 94020⭐</code></b> <b><code>  8730🍴</code></b> [Source Code](https://github.com/louislam/uptime-kuma) ⭐ 94,342 | 🐛 855 | 🌐 JavaScript | 📅 2026-11-15)) `MIT` `Nodejs`
* 🌎 [Prometheus](prometheus.io/) - Service monitoring system and time series database. (<b><code> 67599⭐</code></b> <b><code> 11022🍴</code></b> [Source Code](https://github.com/prometheus/prometheus) ⭐ 67,618 | 🐛 1,100 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `Go`
* 🌎 [glances](nicolargo.github.io/glances/) - Open-source, cross-platform real-time monitoring tool with CLI and web dashboard interfaces and many exporting options. (<b><code> 33951⭐</code></b> <b><code>  1840🍴</code></b> [Source Code](https://github.com/nicolargo/glances) ⭐ 33,952 | 🐛 110 | 🌐 Python | 📅 2026-11-15)) `GPL-3.0` `Python`
* 🌎 [Beszel](beszel.dev/) - Lightweight server monitoring platform that includes Docker statistics, historical data, and alert functions. (<b><code> 27334⭐</code></b> <b><code>  1183🍴</code></b> [Source Code](https://github.com/henrygd/beszel) ⭐ 27,350 | 🐛 402 | 🌐 Go | 📅 2026-11-15)) `MIT` `Go`
* <b><code> 19529⭐</code></b> <b><code>  2502🍴</code></b> [cadvisor](https://github.com/google/cadvisor) ⭐ 19,529 | 🐛 82 | 🌐 Go | 📅 2026-10-12) - Analyzes resource usage and performance characteristics of running containers. `Apache-2.0` `Go`
* 🌎 [Wazuh](wazuh.com/) - Unified XDR and SIEM protection for endpoints and cloud workloads. (<b><code> 17735⭐</code></b> <b><code>  2606🍴</code></b> [Source Code](https://github.com/wazuh/wazuh) ⭐ 17,740 | 🐛 3,222 | 🌐 C++ | 📅 2026-11-14)) `GPL-2.0` `C`
* 🌎 [Gatus](gatus.io) - Automated service health dashboard.  🌎 [Demo](status.twin.sh), <b><code> 12769⭐</code></b> <b><code>   914🍴</code></b> [Source Code](https://github.com/TwiN/gatus) ⭐ 12,785 | 🐛 446 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `Docker/K8S`
* 🌎 [Healthchecks](healthchecks.io/docs/self_hosted/) - Monitoring for cron jobs, background services and scheduled tasks. (<b><code> 10516⭐</code></b> <b><code>  1048🍴</code></b> [Source Code](https://github.com/healthchecks/healthchecks) ⭐ 10,517 | 🐛 55 | 🌐 Python | 📅 2026-11-13)) `BSD-3-Clause` `Python`
* 🌎 [Nezha](nezha.wiki/en_US/) - Lightweight, servers & websites monitoring and O\&M tool. (<b><code> 10404⭐</code></b> <b><code>  1609🍴</code></b> [Source Code](https://github.com/nezhahq/nezha) ⭐ 10,406 | 🐛 57 | 🌐 Go | 📅 2026-10-29)) `Apache-2.0` `Go/Shell`
* 🌎 [htop](htop.dev/) - Interactive process viewer and system monitor for Unix systems. (<b><code>  8458⭐</code></b> <b><code>   663🍴</code></b> [Source Code](https://github.com/htop-dev/htop) ⭐ 8,459 | 🐛 369 | 🌐 C | 📅 2026-11-13)) `GPL-2.0` `C`
* <b><code>  8428⭐</code></b> <b><code>   310🍴</code></b> [Scrutiny](https://github.com/AnalogJ/scrutiny) ⭐ 8,433 | 🐛 40 | 🌐 Go | 📅 2026-11-04) - Web UI for hard drive S.M.A.R.T monitoring, historical trends & real-world failure thresholds. `MIT` `Go`
* 🌎 [OneUptime](oneuptime.com) - A comprehensive solution for monitoring and managing your online services. (<b><code>  7819⭐</code></b> <b><code>   492🍴</code></b> [Source Code](https://github.com/oneuptime/oneuptime) ⭐ 7,822 | 🐛 1,287 | 🌐 TypeScript | 📅 2026-11-15)) `Apache-2.0` `Docker`
* 🌎 [Kener](kener.ing/) - Status page with incident management, easy to use and customize. (<b><code>  5245⭐</code></b> <b><code>   325🍴</code></b> [Source Code](https://github.com/rajnandan1/kener) ⭐ 5,248 | 🐛 75 | 🌐 TypeScript | 📅 2026-11-09)) `MIT` `Nodejs/Docker`
* 🌎 [LibreNMS](www.librenms.org) - Fully featured network monitoring system that provides a wealth of features and device support. (<b><code>  5009⭐</code></b> <b><code>  2867🍴</code></b> [Source Code](https://github.com/librenms/librenms) ⭐ 5,010 | 🐛 203 | 🌐 PHP | 📅 2026-11-15)) `GPL-3.0` `PHP`
* 🌎 [Riemann](riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis. (<b><code>  4266⭐</code></b> <b><code>   502🍴</code></b> [Source Code](https://github.com/riemann/riemann) ⭐ 4,266 | 🐛 30 | 🌐 Clojure | 📅 2026-04-05)) `EPL-1.0` `Java`
* <b><code>  3753⭐</code></b> <b><code>   151🍴</code></b> [dashdot](https://github.com/MauriceNino/dashdot) ⭐ 3,754 | 🐛 56 | 🌐 TypeScript | 📅 2026-11-12) - A simple, modern server dashboard for smaller private servers.  🌎 [Demo](dash.mauz.dev/)) `MIT` `Nodejs/Docker`
* 🌎 [CheckCle](docs.checkcle.io) - Seamless, real-time monitoring of full-stack systems, applications, and infrastructure. (<b><code>  3328⭐</code></b> <b><code>   296🍴</code></b> [Source Code](https://github.com/operacle/checkcle) ⭐ 3,329 | 🐛 92 | 🌐 Go | 📅 2026-07-17)) `MIT` `Docker`
* 🌎 [cState](cstate.uncascade.com/) - Static status page for hyperfast Hugo. Clean design, minimal JS, super light HTML/CSS, high customization, optional admin panel, read-only API, IE8+.  🌎 [Demo](cstate.mnts.lt/), <b><code>  2906⭐</code></b> <b><code>   252🍴</code></b> [Source Code](https://github.com/cstate/cstate) ⭐ 2,906 | 🐛 11 | 🌐 HTML | 📅 2026-10-17)) `MIT` `HTML`
* 🌎 [checkmk](checkmk.com/) - Comprehensive solution for monitoring of applications, servers, and networks. (<b><code>  2645⭐</code></b> <b><code>   581🍴</code></b> [Source Code](https://github.com/Checkmk/checkmk) ⭐ 2,646 | 🐛 59 | 🌐 Python | 📅 2026-11-14)) `GPL-2.0` `Python/PHP`
* 🌎 [Alerta](alerta.io/) - Distributed, scalable and flexible monitoring system. (<b><code>  2535⭐</code></b> <b><code>   381🍴</code></b> [Source Code](https://github.com/alerta/alerta) ⭐ 2,535 | 🐛 40 | 🌐 Python | 📅 2026-10-17)) `Apache-2.0` `Python`
* 🌎 [Icinga](www.icinga.com/) - Nagios fork that has since lapped nagios several times. Comes with the possibility of clustered monitoring. (<b><code>  2247⭐</code></b> <b><code>   623🍴</code></b> [Source Code](https://github.com/Icinga/icinga2) ⭐ 2,247 | 🐛 503 | 🌐 C++ | 📅 2026-11-13)) `GPL-2.0` `C++`
* 🌎 [PHP Server Monitor](www.phpservermonitor.org/) - Open source tool to monitor your servers and websites. (<b><code>  2189⭐</code></b> <b><code>   681🍴</code></b> [Source Code](https://github.com/phpservermon/phpservermon) ⭐ 2,189 | 🐛 28 | 🌐 JavaScript | 📅 2026-11-03)) `GPL-3.0` `PHP`
* <b><code>  2189⭐</code></b> <b><code>   156🍴</code></b> [rtop](https://github.com/rapidloop/rtop) ⭐ 2,189 | 🐛 23 | 🌐 Go | 📅 2022-06-06) - Interactive, remote system monitoring tool based on SSH. `MIT` `Go`
* 🌎 [Munin](munin-monitoring.org/) - Networked resource monitoring tool. (<b><code>  2151⭐</code></b> <b><code>   484🍴</code></b> [Source Code](https://github.com/munin-monitoring/munin) ⭐ 2,151 | 🐛 216 | 🌐 Perl | 📅 2026-11-11)) `GPL-2.0` `Perl/Shell`
* 🌎 [Nagios](www.nagios.org/) - Computer system, network and infrastructure monitoring software application. (<b><code>  2065⭐</code></b> <b><code>   488🍴</code></b> [Source Code](https://github.com/NagiosEnterprises/nagioscore) ⭐ 2,065 | 🐛 214 | 🌐 C | 📅 2026-10-27)) `GPL-2.0` `C`
* 🌎 [Cacti](www.cacti.net) - Web-based network monitoring and graphing tool. (<b><code>  1889⭐</code></b> <b><code>   453🍴</code></b> [Source Code](https://github.com/Cacti/cacti) ⭐ 1,890 | 🐛 399 | 🌐 PHP | 📅 2026-11-13)) `GPL-2.0` `PHP`
* 🌎 [tirreno](www.tirreno.com/) - Application-level security to protect your app from threats, fraud, and abuse.  🌎 [Demo](play.tirreno.com/), <b><code>  1571⭐</code></b> <b><code>   186🍴</code></b> [Source Code](https://github.com/tirrenotechnologies/tirreno) ⭐ 1,571 | 🐛 9 | 🌐 PHP | 📅 2026-10-24)) `AGPL-3.0` `PHP/Docker`
* 🌎 [PhpSysInfo](phpsysinfo.github.io/phpsysinfo/) - A customizable PHP script that displays information about your system nicely. (<b><code>  1415⭐</code></b> <b><code>   236🍴</code></b> [Source Code](https://github.com/phpsysinfo/phpsysinfo) ⭐ 1,415 | 🐛 3 | 🌐 PHP | 📅 2026-11-14)) `GPL-2.0` `PHP`
* 🌎 [Sensu](sensu.io/) - Monitoring tool for ephemeral infrastructure and distributed applications. (<b><code>  1115⭐</code></b> <b><code>   181🍴</code></b> [Source Code](https://github.com/sensu/sensu-go) ⭐ 1,115 | 🐛 291 | 🌐 Go | 📅 2026-11-06)) `MIT` `Go`
* [Performance Co-Pilot](http://pcp.io) - Lightweight, distributed system performance and analysis framework. (<b><code>  1084⭐</code></b> <b><code>   272🍴</code></b> [Source Code](https://github.com/performancecopilot/pcp) ⭐ 1,084 | 🐛 191 | 🌐 C | 📅 2026-11-11)) `LGPL-2.1/GPL-2.0` `C`
* 🌎 [KuvaszUptime](kuvasz-uptime.dev) - Performant, stable uptime & SSL monitoring service with brandable status pages, IAC support, Prometheus integration and a complete REST API.  🌎 [Demo](kuvasz-uptime.dev/demo/), <b><code>   674⭐</code></b> <b><code>    42🍴</code></b> [Source Code](https://github.com/kuvasz-uptime/kuvasz) ⭐ 674 | 🐛 14 | 🌐 Kotlin | 📅 2026-11-13)) `Apache-2.0` `Docker`
* 🌎 [Thruk](www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, Icinga and Shinken. (<b><code>   446⭐</code></b> <b><code>   161🍴</code></b> [Source Code](https://github.com/sni/Thruk) ⭐ 446 | 🐛 91 | 🌐 Perl | 📅 2026-11-13)) `GPL-1.0` `Perl`
* 🌎 [NetXMS](www.netxms.org/) - Open Source network and infrastructure monitoring and management. (<b><code>   429⭐</code></b> <b><code>    85🍴</code></b> [Source Code](https://github.com/netxms/netxms) ⭐ 432 | 🐛 139 | 🌐 C++ | 📅 2026-11-14)) `LGPL-3.0/GPL-3.0` `Java/C++/C`
* 🌎 [openITCOCKPIT Community Edition](openitcockpit.io/) - Monitoring Suite featuring seamless integrations with Naemon, Checkmk, Grafana and more.  🌎 [Demo](demo.openitcockpit.io/), <b><code>   408⭐</code></b> <b><code>    64🍴</code></b> [Source Code](https://github.com/openITCOCKPIT/openITCOCKPIT) ⭐ 409 | 🐛 70 | 🌐 PHP | 📅 2026-11-12)) `GPL-3.0` `deb/Docker`
* <b><code>   318⭐</code></b> <b><code>    35🍴</code></b> [Status](https://github.com/dani3l0/Status) ⭐ 318 | 🐛 1 | 🌐 Python | 📅 2026-07-08) - Simple and lightweight system monitoring tool for small homeservers with a pleasant web interface.  🌎 [Demo](demos-status.djank.me/)) `MIT` `Python`
* <b><code>   213⭐</code></b> <b><code>    10🍴</code></b> [ruptime](https://github.com/alexmyczko/ruptime) ⭐ 214 | 🐛 5 | 🌐 Shell | 📅 2026-10-23) - Classic system status server. `AGPL-3.0` `Shell`
* 🌎 [Naemon](www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features. (<b><code>   174⭐</code></b> <b><code>    69🍴</code></b> [Source Code](https://github.com/naemon/naemon-core) ⭐ 174 | 🐛 50 | 🌐 C | 📅 2026-11-12)) `GPL-2.0` `C`
* 🌎 [Monit](mmonit.com/monit/#home) - Small utility for managing and monitoring Unix systems.  🌎 [Source Code](bitbucket.org/tildeslash/monit/src/master/)) `AGPL-3.0` `C`
* [Observium Community Edition](http://www.observium.org/) - Network monitoring and management platform that provides real-time insight into network health and performance. `QPL-1.0` `PHP`
* 🌎 [Zabbix](www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications.  🌎 [Source Code](git.zabbix.com/projects/ZBX/repos/zabbix/browse)) `GPL-2.0` `C`

### Network Configuration Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Network configuration management tools.

* <b><code>  3664⭐</code></b> <b><code>  1067🍴</code></b> [Oxidized](https://github.com/ytti/oxidized) ⭐ 3,664 | 🐛 49 | 🌐 Ruby | 📅 2026-11-13) - Network device configuration backup tool. `Apache-2.0` `Ruby`
* 🌎 [phpIPAM](phpipam.net/) - Open source IP address management with PowerDNS integration. (<b><code>  2828⭐</code></b> <b><code>   804🍴</code></b> [Source Code](https://github.com/phpipam/phpipam) ⭐ 2,828 | 🐛 1,848 | 🌐 PHP | 📅 2026-11-13)) `GPL-3.0` `PHP`
* 🌎 [GNS3](www.gns3.com/) - Graphical network simulator that provides a variety of virtual appliances. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/GNS3/gns3-gui/) ⭐ 2,670 | 🐛 103 | 🌐 Python | 📅 2026-10-31)) `GPL-3.0` `Python`
* 🌎 [rConfig](www.rconfig.com/) - Network device configuration management tool. (<b><code>   224⭐</code></b> <b><code>    31🍴</code></b> [Source Code](https://github.com/rconfig/rconfig) ⭐ 225 | 🐛 2 | 🌐 PHP | 📅 2026-11-09)) `GPL-3.0` `PHP`
* 🌎 [RANCID](www.shrubbery.net/rancid/) - Monitor network devices configuration and maintain history of changes. (<b><code>   138⭐</code></b> <b><code>    56🍴</code></b> [Source Code](https://github.com/haussli/rancid) ⭐ 138 | 🐛 59 | 🌐 Makefile | 📅 2026-11-10)) `BSD-3-Clause` `Perl/Shell`
* 🌎 [OpenWISP](openwisp.org/) - Open Source Network Management System for OpenWRT based routers and access points.  🌎 [Demo](openwisp.org/demo.html), [Source Code](https://github.com/openwisp)) `GPL-3.0` `Python`

### PaaS

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Platform-as-a-Service](en.wikipedia.org/wiki/Platform_as_a_service) software allows customers to provision, instantiate, run, and manage a computing platform and one or more applications, without the complexity of building and maintaining the infrastructure typically associated with developing and launching the application. Also includes 🌎 [Serverless computing](en.wikipedia.org/wiki/Serverless_computing) and 🌎 [Function-as-a-service (FaaS)](en.wikipedia.org/wiki/Function_as_a_service) software.

* 🌎 [Coolify](coolify.io/) - An open-source & self-hostable Heroku / Netlify alternative (and even more). (<b><code> 66066⭐</code></b> <b><code>  5986🍴</code></b> [Source Code](https://github.com/coollabsio/coolify) ⭐ 66,096 | 🐛 259 | 🌐 PHP | 📅 2026-11-14)) `Apache-2.0` `Docker`
* 🌎 [Dokku](dokku.com/) - An open-source PaaS (alternative to Heroku). (<b><code> 32227⭐</code></b> <b><code>  2097🍴</code></b> [Source Code](https://github.com/dokku/dokku) ⭐ 32,229 | 🐛 28 | 🌐 Shell | 📅 2026-11-14)) `MIT` `Docker/Shell/Go/deb`
* 🌎 [OpenFaaS](www.openfaas.com/) - Serverless Functions Made Simple for Docker & Kubernetes. (<b><code> 26261⭐</code></b> <b><code>  1961🍴</code></b> [Source Code](https://github.com/openfaas/faas) ⭐ 26,260 | 🐛 31 | 🌐 Go | 📅 2026-10-23)) `MIT` `Go`
* 🌎 [CapRover](caprover.com/) - Build your own PaaS in a few minutes.  🌎 [Demo](captain.server.demo.caprover.com/#/login), <b><code> 15205⭐</code></b> <b><code>  1015🍴</code></b> [Source Code](https://github.com/caprover/caprover) ⭐ 15,205 | 🐛 179 | 🌐 TypeScript | 📅 2026-11-14)) `Apache-2.0` `Docker/Nodejs`
* 🌎 [Nhost](nhost.io/) - Firebase Alternative with GraphQL. Get a database and backend configured and ready in minutes. (<b><code>  9386⭐</code></b> <b><code>   640🍴</code></b> [Source Code](https://github.com/nhost/nhost) ⭐ 9,388 | 🐛 178 | 🌐 Go | 📅 2026-11-15)) `MIT` `Docker/Nodejs/Go`
* 🌎 [Tau](taubyte.com) - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, CI/CD, Object Storage, K/V Database, and Pub-Sub Messaging. (<b><code>  5174⭐</code></b> <b><code>   221🍴</code></b> [Source Code](https://github.com/taubyte/tau) ⭐ 5,175 | 🐛 11 | 🌐 Go | 📅 2026-11-12)) `BSD-3-Clause` `Go/Rust/Docker`
* 🌎 [Kubero](www.kubero.dev/) - A self-hosted Heroku PaaS alternative for Kubernetes that implements GitOps.  🌎 [Demo](demo.kubero.dev/), <b><code>  4473⭐</code></b> <b><code>   217🍴</code></b> [Source Code](https://github.com/kubero-dev/kubero) ⭐ 4,473 | 🐛 129 | 🌐 TypeScript | 📅 2026-10-13)) `GPL-3.0` `K8S/Nodejs/Go`
* <b><code>  2225⭐</code></b> <b><code>   156🍴</code></b> [fx](https://github.com/metrue/fx) ⭐ 2,225 | 🐛 85 | 🌐 Go | 📅 2023-10-24) - A tool to help you do Function as a Service with painless on your own servers. `MIT` `Go`

### Packaging

**[`^        back to top        ^`](#awesome-sysadmin)**

A 🌎 [package manager](en.wikipedia.org/wiki/Package_manager) or package-management system is a collection of software tools that automates the process of installing, upgrading, configuring, and removing computer programs for a computer in a consistent manner.

* 🌎 [fpm](fpm.readthedocs.io/en/latest/) - Versatile multi format package creator. (<b><code> 11517⭐</code></b> <b><code>  1065🍴</code></b> [Source Code](https://github.com/jordansissel/fpm) ⭐ 11,517 | 🐛 783 | 🌐 Ruby | 📅 2026-09-14)) `MIT` `Ruby`
* 🌎 [aptly](www.aptly.info/) - Swiss army knife for Debian repository management. (<b><code>  2892⭐</code></b> <b><code>   438🍴</code></b> [Source Code](https://github.com/aptly-dev/aptly) ⭐ 2,892 | 🐛 217 | 🌐 Go | 📅 2026-11-14)) `MIT` `Go`
* <b><code>  1315⭐</code></b> <b><code>   293🍴</code></b> [omnibus-ruby](https://github.com/chef/omnibus) ⭐ 1,315 | 🐛 70 | 🌐 Ruby | 📅 2025-12-09) - Easily create full-stack installers for your project across a variety of platforms. `Apache-2.0` `Ruby`
* <b><code>   398⭐</code></b> <b><code>   132🍴</code></b> [tito](https://github.com/rpm-software-management/tito) ⭐ 398 | 🐛 58 | 🌐 Python | 📅 2026-08-26) - Builds RPMs for git-based projects. `GPL-2.0` `Python`

### Project Management

**[`^        back to top        ^`](#awesome-sysadmin)**

Web-based project management and bug tracking systems.

**Please visit 🌎 [awesome-selfhosted/Project Management](awesome-selfhosted.net/tags/software-development---project-management.html)**

### Queuing

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Message queues](en.wikipedia.org/wiki/Message_queue) and 🌎 [message broker](en.wikipedia.org/wiki/Message_broker) software, typically used for inter-process communication (IPC), or for inter-thread communication within the same process.

*See also: 🌎 [Cloud Native Landscape - Streaming & Messaging](landscape.cncf.io/?group=projects-and-products\&view-mode=card#app-definition-and-development--streaming-messaging)*

* 🌎 [NSQ](nsq.io/) - A realtime distributed messaging platform. (<b><code> 25777⭐</code></b> <b><code>  2880🍴</code></b> [Source Code](https://github.com/nsqio/nsq) ⭐ 25,777 | 🐛 83 | 🌐 Go | 📅 2026-08-11)) `MPL-2.0` `Go`
* 🌎 [BeanstalkD](beanstalkd.github.io/) - A simple, fast work queue. (<b><code>  6704⭐</code></b> <b><code>   865🍴</code></b> [Source Code](https://github.com/beanstalkd/beanstalkd) ⭐ 6,704 | 🐛 46 | 🌐 C | 📅 2025-03-18)) `MIT` `C`
* 🌎 [ActiveMQ](activemq.apache.org/) - Java message broker. (<b><code>  2461⭐</code></b> <b><code>  1511🍴</code></b> [Source Code](https://github.com/apache/activemq) ⭐ 2,461 | 🐛 138 | 🌐 Java | 📅 2026-11-15)) `Apache-2.0` `Java`
* [Gearman](http://gearman.org/) - Fast multi-language queuing/job processing platform. (<b><code>   764⭐</code></b> <b><code>   160🍴</code></b> [Source Code](https://github.com/gearman/gearmand) ⭐ 764 | 🐛 40 | 🌐 C++ | 📅 2026-11-03)) `BSD-3-Clause` `C++`
* 🌎 [ZeroMQ](zeromq.org/) - Lightweight queuing system. ([Source Code](https://github.com/zeromq)) `GPL-3.0` `C++`

### Remote Desktop Clients

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Remote Desktop](en.wikipedia.org/wiki/Remote_desktop_software) client software.

*See also: 🌎 [awesome-selfhosted/Remote Access](awesome-selfhosted.net/tags/remote-access.html)*

* 🌎 [Tiger VNC](tigervnc.org/) - High-performance, multi-platform VNC client and server. (<b><code>  7726⭐</code></b> <b><code>  1234🍴</code></b> [Source Code](https://github.com/TigerVNC/tigervnc) ⭐ 7,726 | 🐛 189 | 🌐 C++ | 📅 2026-11-13)) `GPL-2.0` `C++`
* 🌎 [Remmina](www.remmina.org/) - Feature-rich remote desktop application for linux and other unixes.  🌎 [Source Code](gitlab.com/Remmina/Remmina)) `GPL-2.0` `C`
* 🌎 [X2go](wiki.x2go.org/doku.php) - X2Go is an open source remote desktop software for Linux that uses the NoMachine/NX technology protocol.  🌎 [Source Code](code.x2go.org/gitweb)) `GPL-2.0` `Perl`

### Router

**[`^        back to top        ^`](#awesome-sysadmin)**

Software for management of [router](https://en.wikipedia.org/wiki/Router_\(computing\)) hardware.

* 🌎 [pfSense CE](www.pfsense.org/) - Free network firewall distribution, based on the FreeBSD operating system with a custom kernel and including third party free software packages for additional functionality. (<b><code>  5789⭐</code></b> <b><code>  1600🍴</code></b> [Source Code](https://github.com/pfsense/pfsense) ⭐ 5,792 | 🐛 47 | 🌐 PHP | 📅 2026-03-31)) `Apache-2.0` `Shell/PHP/Other`
* 🌎 [DD-WRT](dd-wrt.com/) - A Linux-based firmware for wireless routers and access points, originally designed for the Linksys WRT54G series.  🌎 [Source Code](svn.dd-wrt.com/)) `GPL-2.0` `C`
* 🌎 [IPFire](www.ipfire.org/) - Free network firewall distribution, based on the Linux operating system with easy-to-use web management console.  🌎 [Source Code](git.ipfire.org/?p=ipfire-2.x.git;a=summary)) `GPL-2.0` `Shell/PHP/Other`
* 🌎 [OpenWrt](openwrt.org/) - A Linux-based router featuring Mesh networking, IPS via snort and AQM among many other features.  🌎 [Source Code](git.openwrt.org/openwrt/openwrt)) `GPL-2.0` `C`
* 🌎 [OPNsense](opnsense.org/) - An open source FreeBSD-based firewall and router with traffic shaping, load balancing, and virtual private network capabilities. ([Source Code](https://github.com/opnsense)) `BSD-2-Clause` `C/PHP`

### Service Discovery

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Service discovery](en.wikipedia.org/wiki/Service_discovery) is the process of automatically detecting devices and services on a computer network.

* 🌎 [etcd](etcd.io/) - Distributed K/V-Store, authenticating via SSL PKI and a REST HTTP Api for shared configuration and service discovery. (<b><code> 52603⭐</code></b> <b><code> 10598🍴</code></b> [Source Code](https://github.com/etcd-io/etcd) ⭐ 52,607 | 🐛 467 | 🌐 Go | 📅 2026-11-14)) `Apache-2.0` `Go`
* 🌎 [Consul](www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration. (<b><code> 30112⭐</code></b> <b><code>  4635🍴</code></b> [Source Code](https://github.com/hashicorp/consul) ⭐ 30,114 | 🐛 1,458 | 🌐 Go | 📅 2026-11-14)) `MPL-2.0` `Go`
* 🌎 [ZooKeeper](zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services. (<b><code> 12835⭐</code></b> <b><code>  7332🍴</code></b> [Source Code](https://github.com/apache/zookeeper) ⭐ 12,833 | 🐛 261 | 🌐 Java | 📅 2026-11-10)) `Apache-2.0` `Java/C++`

### Software Containers

**[`^        back to top        ^`](#awesome-sysadmin)**
🌎 [Operating system–level](en.wikipedia.org/wiki/OS-level_virtualization) virtualization.

* 🌎 [Docker Compose](docs.docker.com/compose/) - Define and run multi-container Docker applications. (<b><code> 38833⭐</code></b> <b><code>  5945🍴</code></b> [Source Code](https://github.com/docker/compose) ⭐ 38,850 | 🐛 121 | 🌐 Go | 📅 2026-11-13)) `Apache-2.0` `Go`
* 🌎 [Portainer Community Edition](www.portainer.io/) - Simple management UI for Docker. (<b><code> 38829⭐</code></b> <b><code>  2941🍴</code></b> [Source Code](https://github.com/portainer/portainer) ⭐ 38,831 | 🐛 780 | 🌐 TypeScript | 📅 2026-11-14)) `Zlib` `Go`
* 🌎 [Podman](podman.io) - Daemonless container engine for developing, managing, and running OCI Containers on your Linux System. Containers can either be run as root or in rootless mode. Simply put: `alias docker=podman`. (<b><code> 33274⭐</code></b> <b><code>  3456🍴</code></b> [Source Code](https://github.com/podman-container-tools/podman) ⭐ 33,283 | 🐛 1,019 | 🌐 Go | 📅 2026-11-15)) `Apache-2.0` `Go`
* 🌎 [systemd-nspawn](www.freedesktop.org/software/systemd/man/systemd-nspawn.html) - Lightweight, chroot-like, environment to run an OS or command directly under systemd. (<b><code> 17034⭐</code></b> <b><code>  4824🍴</code></b> [Source Code](https://github.com/systemd/systemd) ⭐ 17,035 | 🐛 3,430 | 🌐 C | 📅 2026-11-15)) `GPL-2.0` `C`
* 🌎 [Incus](linuxcontainers.org/incus/) - Container "hypervisor" and a better UX for LXC. (<b><code>  6640⭐</code></b> <b><code>   521🍴</code></b> [Source Code](https://github.com/lxc/incus) ⭐ 6,644 | 🐛 49 | 🌐 Go | 📅 2026-11-14)) `Apache-2.0` `Go`
* 🌎 [LXC](linuxcontainers.org/lxc/) - Userspace interface for the Linux kernel containment features. (<b><code>  5297⭐</code></b> <b><code>  1191🍴</code></b> [Source Code](https://github.com/lxc/lxc) ⭐ 5,297 | 🐛 170 | 🌐 C | 📅 2026-11-12)) `GPL-2.0` `C`
* 🌎 [Docker Swarm](docs.docker.com/engine/swarm/) - Manage cluster of Docker Engines. (<b><code>  3655⭐</code></b> <b><code>   678🍴</code></b> [Source Code](https://github.com/moby/swarmkit) ⭐ 3,655 | 🐛 158 | 🌐 Go | 📅 2026-11-03)) `Apache-2.0` `Go`
* 🌎 [Docker](www.docker.com/) - Platform for developers and sysadmins to build, ship, and run distributed applications.  🌎 [Source Code](www.docker.com/community/open-source/)) `Apache-2.0` `Go`
* 🌎 [OpenVZ](openvz.org) - Container-based virtualization for Linux.  🌎 [Source Code](src.openvz.org/projects/OVZ)) `GPL-2.0` `C`

### Time Servers

**[`^        back to top        ^`](#awesome-sysadmin)**

Time synchronization servers and clients (NTP, PTP, Roughtime).

* <b><code>   325⭐</code></b> <b><code>    39🍴</code></b> [Statime](https://github.com/pendulum-project/statime) ⭐ 326 | 🐛 31 | 🌐 Rust | 📅 2026-11-12) - A Precision Time Protocol (PTP) implementation in Rust. `MIT/Apache-2.0` `Rust`
* <b><code>   148⭐</code></b> <b><code>    23🍴</code></b> [Roughenough](https://github.com/int08h/roughenough) ⭐ 148 | 🐛 6 | 🌐 Rust | 📅 2026-11-09) - A Roughtime secure time synchronization client and server. `MIT/Apache-2.0` `Rust`
* 🌎 [OpenNTPD](www.openntpd.org/) - A FREE, easy to use implementation of the Network Time Protocol. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/openntpd-portable/openntpd-openbsd/) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2026-09-18)) `ISC` `C`
* 🌎 [Chrony](chrony-project.org/) - A versatile implementation of the Network Time Protocol (NTP).  🌎 [Source Code](gitlab.com/chrony/chrony)) `GPL-2.0` `C`
* 🌎 [NTPsec](www.ntpsec.org/) - A secure, hardened, and improved implementation of Network Time Protocol derived from NTP Classic.  🌎 [Source Code](gitlab.com/NTPsec/ntpsec)) `BSD-2-Clause` `C`

### Troubleshooting

**[`^        back to top        ^`](#awesome-sysadmin)**

Troubleshooting tools.

* 🌎 [mitmproxy](mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems. (<b><code> 46909⭐</code></b> <b><code>  4971🍴</code></b> [Source Code](https://github.com/mitmproxy/mitmproxy) ⭐ 46,970 | 🐛 553 | 🌐 Python | 📅 2026-11-14)) `MIT` `Python`
* 🌎 [Sysdig](www.sysdig.com/) - Capture system state and activity from a running Linux instance, then save, filter and analyze. (<b><code>  8318⭐</code></b> <b><code>   751🍴</code></b> [Source Code](https://github.com/draios/sysdig) ⭐ 8,318 | 🐛 116 | 🌐 C++ | 📅 2026-04-13)) `Apache-2.0` `Docker/Lua/C`
* 🌎 [mtr](www.bitwizard.nl/mtr/) - Network utility that combines traceroute and ping. (<b><code>  3385⭐</code></b> <b><code>   379🍴</code></b> [Source Code](https://github.com/traviscross/mtr) ⭐ 3,385 | 🐛 141 | 🌐 C | 📅 2026-11-02)) `GPL-2.0` `C`
* 🌎 [grml](grml.org) - Bootable Debian Live CD with powerful CLI tools. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/grml/))) `GPL-3.0` `Shell`
* 🌎 [Wireshark](www.wireshark.org/) - The world's foremost network protocol analyzer.  🌎 [Source Code](gitlab.com/wireshark/wireshark)) `GPL-2.0` `C`

### Version control

**[`^        back to top        ^`](#awesome-sysadmin)**

Software versioning and revision control.

* 🌎 [Git](git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed. (<b><code> 64310⭐</code></b> <b><code> 28761🍴</code></b> [Source Code](https://github.com/git/git) ⭐ 64,320 | 🐛 415 | 🌐 C | 📅 2026-11-15)) `GPL-2.0` `C`
* 🌎 [Darcs](darcs.net/) - Cross-platform version control system, like git, mercurial or svn but with a very different approach: focus on changes rather than snapshots.  🌎 [Source Code](darcs.net/releases/)) `GPL-2.0` `Haskell`
* 🌎 [Fossil](www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.  🌎 [Source Code](www.fossil-scm.org/home/dir?ci=trunk)) `BSD-2-Clause` `C`
* 🌎 [Mercurial](www.mercurial-scm.org/) - Distributed source control management tool.  🌎 [Source Code](repo.mercurial-scm.org/hg/file/tip)) `GPL-2.0` `Python/C/Rust`
* 🌎 [Subversion](subversion.apache.org/) - Client-server revision control system.  🌎 [Source Code](svn.apache.org/repos/asf/subversion/trunk/)) `Apache-2.0` `C`

### Virtualization

**[`^        back to top        ^`](#awesome-sysadmin)**

Virtualization software.

* 🌎 [Vagrant](www.vagrantup.com/) - Tool for building complete development environments. (<b><code> 27227⭐</code></b> <b><code>  4488🍴</code></b> [Source Code](https://github.com/hashicorp/vagrant) ⭐ 27,230 | 🐛 758 | 🌐 Ruby | 📅 2026-11-12)) `BUSL-1.1` `Ruby`
* 🌎 [Packer](www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration. (<b><code> 15822⭐</code></b> <b><code>  3432🍴</code></b> [Source Code](https://github.com/hashicorp/packer) ⭐ 15,823 | 🐛 317 | 🌐 Go | 📅 2026-11-15)) `MPL-2.0` `Go`
* 🌎 [OpenNebula](opennebula.org/) - Build and manage enterprise clouds for virtualized services, containerized applications and serverless computing. (<b><code>  1767⭐</code></b> <b><code>   539🍴</code></b> [Source Code](https://github.com/OpenNebula/one) ⭐ 1,769 | 🐛 741 | 🌐 JavaScript | 📅 2026-11-04)) `Apache-2.0` `C++`
* 🌎 [Ganeti](www.ganeti.org/) - Cluster virtual server management software tool built on top of KVM and Xen. (<b><code>   591⭐</code></b> <b><code>   129🍴</code></b> [Source Code](https://github.com/ganeti/ganeti) ⭐ 591 | 🐛 332 | 🌐 Python | 📅 2026-11-13)) `BSD-2-Clause` `Python/Haskell`
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

* <b><code> 45686⭐</code></b> <b><code>  2641🍴</code></b> [Headscale](https://github.com/juanfont/headscale) ⭐ 45,717 | 🐛 84 | 🌐 Go | 📅 2026-11-15) - Self-hostable fork of 🌎 [Tailscale](tailscale.com), cross-platform clients, simple to use, built-in (currently experimental) monitoring tools. `BSD-3-Clause` `Go`
* <b><code> 18527⭐</code></b> <b><code>  1206🍴</code></b> [Nebula](https://github.com/slackhq/nebula) ⭐ 18,532 | 🐛 121 | 🌐 Go | 📅 2026-11-13) - A scalable p2p VPN with a focus on performance, simplicity and security. `MIT` `Go`
* <b><code> 16077⭐</code></b> <b><code>   650🍴</code></b> [Gluetun VPN client](https://github.com/passteque/gluetun) ⭐ 16,085 | 🐛 335 | 🌐 Go | 📅 2026-11-14) - VPN client in a thin Docker container for multiple VPN providers, written in Go, and using OpenVPN or Wireguard, DNS over TLS, with a few proxy servers built-in. `MIT` `Docker`
* 🌎 [OpenVPN](community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange. (<b><code> 14823⭐</code></b> <b><code>  3436🍴</code></b> [Source Code](https://github.com/OpenVPN/openvpn) ⭐ 14,822 | 🐛 228 | 🌐 C | 📅 2026-11-14)) `GPL-2.0` `C`
* 🌎 [SoftEther](www.softether.org/) - Multi-protocol software VPN with advanced features. (<b><code>     ?⭐</code></b> <b><code>     ?🍴</code></b> [Source Code](https://github.com/SoftEtherVPN/SoftEtherVPN/) ⭐ 13,740 | 🐛 299 | 🌐 C | 📅 2026-11-13)) `Apache-2.0` `C`
* <b><code> 13665⭐</code></b> <b><code>   805🍴</code></b> [sshuttle](https://github.com/sshuttle/sshuttle) ⭐ 13,666 | 🐛 197 | 🌐 Python | 📅 2026-11-12) - Poor man's VPN. `LGPL-2.1` `Python`
* 🌎 [Firezone](www.firezone.dev/) - WireGuard based VPN Server and Firewall. (<b><code>  9184⭐</code></b> <b><code>   467🍴</code></b> [Source Code](https://github.com/firezone/firezone) ⭐ 9,184 | 🐛 422 | 🌐 Elixir | 📅 2026-11-15)) `Apache-2.0` `Docker`
* 🌎 [strongSwan](www.strongswan.org/) - Complete IPsec implementation for Linux. (<b><code>  3055⭐</code></b> <b><code>   961🍴</code></b> [Source Code](https://github.com/strongswan/strongswan) ⭐ 3,056 | 🐛 180 | 🌐 C | 📅 2026-11-13)) `GPL-2.0` `C`
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

Contributing guidelines can be found <b><code>    17⭐</code></b> <b><code>    59🍴</code></b> [here](https://github.com/awesome-foss/awesome-sysadmin-data/blob/master/CONTRIBUTING.md) ⭐ 17 | 🐛 30 | 🌐 Makefile | 📅 2026-11-15).

## License

This list is under the [Creative Commons Attribution-ShareAlike 4.0 International](LICENSE).
Terms of the license are summarized 🌎 [here](creativecommons.org/licenses/by-sa/4.0).
The list of authors can be found in the [AUTHORS](AUTHORS) file.

## Source

<b><code> 35699⭐</code></b> <b><code>  2129🍴</code></b> [awesome-foss/awesome-sysadmin](https://github.com/awesome-foss/awesome-sysadmin) ⭐ 35,708 | 🐛 0 | 📅 2026-10-22)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-15._
