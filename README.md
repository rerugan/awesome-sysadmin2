# Awesome Sysadmin
A curated list of amazingly awesome open source sysadmin resources inspired by [Awesome PHP](https://github.com/ziadoz/awesome-php)

* [Awesome Sysadmin](#awesome-sysadmin)
  * [Backups](#backups)
  * [Cloning](#cloning)
  * [Cloud Computing](#cloud-computing)
  * [Cloud Orchestration](#cloud-orchestration)
  * [Service discovery](#service-discovery)
  * [Cloud Storage](#cloud-storage)
  * [Code Review](#code-review)
  * [Collaborative Software](#collaborative-software)
  * [Configuration Management Database](#configuration-management-database)
  * [Configuration Management](#configuration-management)
  * [Continuous Integration & Continuous Deployment](#continuous-integration--continuous-deployment)
  * [Distributed Filesystems](#distributed-filesystems)
  * [DHCP](#dhcp)
  * [DNS](#dns)
  * [Hosting Control Panels](#hosting-control-panels)
  * [IMAP/POP3](#imappop3)
  * [IRC](#irc)
  * [IT Asset Management](#it-asset-management)
  * [LDAP](#ldap)
  * [Load Testing](#load-testing)
  * [Log Management](#log-management)
  * [Monitoring](#monitoring)
  * [Metric & Metric Collection](#metric--metric-collection)
  * [Network Configuration Management](#network-configuration-management)
  * [Newsletters](#newsletters)
  * [NoSQL](#nosql)
  * [Packaging](#packaging)
  * [Queuing](#queuing)
  * [Remote Execution](#remote-execution)
  * [RDBMS](#rdbms)
  * [Security](#security)
  * [Service Management](#service-management)
  * [SMTP](#smtp)
  * [Software Containers](#software-containers)
  * [SSH](#ssh)
  * [Statistics](#statistics)
  * [Ticketing systems](#ticketing-systems)
  * [Troubleshooting](#troubleshooting)
  * [Project Management](#project-management)
  * [Version control](#version-control)
  * [Virtualization](#virtualization)
  * [VPN](#vpn)
  * [XMPP](#xmpp)
  * [Webmails](#webmails)
  * [Web](#web)
  * [Wikis](#wikis)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Books](#books)
  * [Editors](#editors)
  * [Repositories](#repositories)
  * [Websites](#websites)
* [GitTools](#gittools)
* [Versioning](#versioning)
* [Contributing](#contributing)

## Backups
*Backup software.*

* [Amanda](http://www.amanda.org/) - Client-server model backup tool.
* [Bacula](http://www.bacula.org) - Another Client-server model backup tool.
* [Backup](https://github.com/meskyanichi/backup) - Provides an elegant DSL in Ruby for performing backups on UNIX-like systems.
* [Backupninja](https://labs.riseup.net/code/projects/backupninja) - Lightweight, extensible meta-backup system.
* [Backuppc](http://backuppc.sourceforge.net/) - Client-server model backup tool with file pooling scheme.
* [Bareos](http://www.bareos.org) - Bacula fork, made because open-source Bacula version almost stopped progress.
* [Bup](https://github.com/bup/bup) - Incremental backups with rolling checksums, git packfiles, de-duplication, and a FUSE filesystem.
* [Burp](http://burp.grke.org/) - Network backup and restore program.
* [Duplicity](http://duplicity.nongnu.org/) - Encrypted bandwidth-efficient backup using the rsync algorithm.
* [Fileprune](http://www.spinellis.gr/sw/unix/fileprune/) - delete archived backup files with diverse constraints.
* [FreeFileSync](http://sourceforge.net/projects/freefilesync/) - Folder comparison and synchronization tool providing highly optimized performance and usability without a needlessly complex user interface. 
* [Lsyncd](https://github.com/axkibe/lsyncd) - Watches a local directory trees for changes, and then spawns a process to synchronize the changes. Uses rsync by default.
* [Rsnapshot](http://www.rsnapshot.org/) - Filesystem Snapshotting Utility.
* [SafeKeep](http://safekeep.sourceforge.net/) - Centralized pull-based backup using `rdiff-backup`.
* [storeBackup](http://storebackup.org/) - Advanced, yet simple and easy to use backup suite, better suited for personal backups.
* [TarSnap](https://www.tarsnap.com/) - Secure backup service with a portable client in C.
* [UrBackup](http://www.urbackup.org/) - Another client-server backup system.
* [DREBS](https://github.com/dojo4/drebs) - AWS EBS backup script that supports strategies.

## Cloning
*Cloning software.*

* [Clonezilla](http://clonezilla.org/) - Partition and disk imaging/cloning program.
* [DRBL](http://drbl.org/) - Diskless Remote Boot in Linux. Open source solution for managing deployment across many clients. Includes Clonezilla and a PXE boot server.
* [Fog](http://www.fogproject.org/) - Another computer cloning solution.
* [iPXE](http://ipxe.org/) - iPXE is an open source boot firmware project as a livecd that can get obscure network devices to recognize and boot from remote PXE servers.
* [Redo Backup](http://redobackup.org/) - Easy Backup, Recovery and Restore.
* [Unison](http://www.cis.upenn.edu/~bcpierce/unison/) - Synchronizes files between drives or machines. Bidirectional merging and conflict management.

## Cloud Computing

* [AppScale](http:/github.com/AppScale/appscale) - Open source cloud software with Google App Engine compatibility.
* [Archipel](http://archipelproject.org/) - Manage and supervise virtual machines using Libvirt.
* [CloudStack](http://cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services.
* [Eucalyptus](https://www.eucalyptus.com/) - Open source private cloud software with AWS compatibility.
* [OpenNebula](http://opennebula.org/) - An user-driven cloud management platform for sysadmins and devops.
* [Openshift Origin](https://openshift.github,io) - Open source upstream of OpenShift, the next generation application hosting platform developed by Red Hat.
* [OpenStack](https://www.openstack.org/) - Open source software for building private and public clouds.
* [The Foreman](http://theforeman.org/) - Foreman is a complete lifecycle management tool for physical and virtual servers. FOSS.
* [Cobbler](http://www.cobblerd.org/) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments. 
* [Mesos](http://mesos.apache.org/) - Develop and run resource-efficient distributed systems.
* [Tsuru](http://www.tsuru.io/) - Tsuru is an extensible and open source Platform as a Service software.

## Cloud Orchestration

* [Ansible](http://www.ansible.com) - Contains modules for controlling many types of cloud resources
* [BOSH](http://docs.cloudfoundry.org/bosh/) -  IaaS orchestration platform originally written for deploying and managing Cloud Foundry PaaS, but also useful for general purpose distributed systems.
* [Cloudify](http://www.getcloudify.org/) - A Python based, Pluggable Ochestrator. Runs on any Cloud, leveraging tools of your choice.
* [Cloud Foundry](http://cloudfoundry.org/) - Open source PaaS software. Apache 2.0 licensed, written in Ruby and Go.
* [Juju](https://juju.ubuntu.com/) - Cloud orechestration tool which manages services as charms, YAML configuration and deployment script bundles.
* [MCollective](http://puppetlabs.com/mcollective) - Ruby framework to manage server orchestration, developed by Puppet labs.
* [Overcast](http://andrewchilds.github.io/overcast/) - Deploy VMs across different cloud providers, and run commands and scripts across any or all of them in parallel via SSH.
* [Rundeck](http://rundeck.org/) - Simple orchestration tool.
* [Salt](http://www.saltstack.com/) - It's written in Python.

## Service discovery

* [Consul](http://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [Doozerd](https://github.com/ha/doozerd) - Doozer is a highly-available, completely consistent store for small amounts of extremely important data.
* [etcd](https://github.com/coreos/etcd) - A highly-available key value store for shared configuration and service discovery
* [Serf](http://www.serfdom.io/) - Serf is a tool for cluster membership 
* [ZooKeeper](http://zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

## Cloud Storage

* [git-annex assistant](http://git-annex.branchable.com/assistant/) - A synchronised folder on each of your OSX and Linux computers, Android devices, removable drives, NAS appliances, and cloud services.
* [ownCloud](https://owncloud.org) - Provides universal access to your files via the web, your computer or your mobile devices.
* [Seafile](http://seafile.com) - Another Open Source Cloud Storage solution.
* [SparkleShare](http://sparkleshare.org/) - Provides cloud storage and file synchronization services. By default, it uses Git as a storage backend.
* [Swift](http://docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.
* [Syncthing](http://syncthing.net/) - Open Source system for private, encrypted and authenticated distribution of data.

## Code Review
*Web Based collaborative code review system.*

* [Gerrit](https://code.google.com/p/gerrit/) - Based on the Git version control, it facilitates software developers to review modifications to the source code and approve or reject those changes.
* [Review Board](https://www.reviewboard.org/) - Available as free software uner the MIT License.

## Collaborative Software
*Collaborative software or groupware suites.*

* [Citadel/UX](http://www.citadel.org/) - Collaboration suite (messaging and groupware) that is descended from the Citadel family of programs.
* [EGroupware](http://www.egroupware.org/) - Groupware software written in PHP.
* [Horde Groupware](http://www.horde.org/apps/groupware) -  PHP based collaborative software suite that includes email, calendars, wikis, time tracking, and file management.
* [Kolab](https://www.kolab.org) - Another groupware suite.
* [SOGo](https://www.sogo.nu/) -  Collaborative software server with a focus on simplicity and scalability.
* [Zimbra](https://www.zimbra.com/community/) - Collaborative software suite, that includes an email server and web client.

## Configuration Management Database
*Configuration management database (CMDB) software.*

* [i-doit](http://www.i-doit.org/) - Open Source IT Documentation and CMDB.
* [iTop](http://www.combodo.com/-Overview-.html) - A complete open source, ITIL, web based service management tool.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
* [Clusto](https://github.com/clusto/clusto) - Helps you keep track of your inventory, where it is, how it's connected, and provides an abstracted interface for interacting with the elements of the infrastructure.

## Configuration Management
*Configuration management tools.*

* [Ansible](http://www.ansible.com/) -  It's written in Python and manages the nodes over SSH.
* [CFEngine](http://cfengine.com/) - Lightweight agent system. Configuration state is specified via a declarative language.
* [Chef](http://www.opscode.com/chef/) - It's written in Ruby and Erlang and uses a pure-Ruby DSL.
* [Fabric](http://www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks.
* [Pallet](http://palletops.com/) - Infrastructure definition, configuration and management via a Clojure DSL.
* [Puppet](http://puppetlabs.com/) - It's written in Ruby and uses Puppet's declarative language or a Ruby DSL.
* [Salt](http://www.saltstack.com/) - It's written in Python.
* [Slaughter](http://steve.org.uk/Software/slaughter/) - It's written in Perl.
* [Rudder](http://www.rudder-project.org) - Rudder is an open source CM tool for managing IT infrastructures. It is written in Scala.

## Continuous Integration & Continuous Deployment
*Continuous integration/deployment software.*

* [Buildbot](http://buildbot.net/) - Python-based toolkit for continuous integration.
* [Drone](https://github.com/drone/drone) - It's written in Go, and based on Docker.
* [GitLab CI](https://www.gitlab.com/gitlab-ci/) - Based off of ruby. They also provide GitLab, which manages git repositories.
* [Go](http://www.go.cd/) - Open source continuous delivery server.
* [Jenkins](http://jenkins-ci.org/) - An extendable open source continuous integration server.
* [Vlad the Deployer](http://rubyhitsquad.com/Vlad_the_Deployer.html) - Deployment automation.
* [VexorCI](https://github.com/vexor) - Fast, Open source CI server based on Ruby and Docker

## Distributed Filesystems
*Network distributed filesystems.*

* [Ceph](http://ceph.com/) - Distributed object store and file system.
* [DRBD](http://www.drbd.org/) - Disributed Replicated Block Device.
* [LeoFS](http://leo-project.net) - Unstructured object/data storage and a highly available, distributed, eventually consistent storage system.
* [GlusterFS](http://www.gluster.org/) - Scale-out network-attached storage file system.
* [HDFS](http://hadoop.apache.org/) - Distributed, scalable, and portable file-system written in Java for the Hadoop framework.
* [Lustre](http://lustre.opensfs.org/) -  A type of parallel distributed file system, generally used for large-scale cluster computing.
* [MooseFS](http://www.moosefs.org/) - Fault tolerant, network distributed file system.
* [MogileFS](http://mogilefs.org/) - Application level, network distributed file system.
* [OpenAFS](http://www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.
* [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system.
* [XtreemFS](http://www.xtreemfs.org/) - XtreemFS is a fault-tolerant distributed file system for all storage needs.

## DHCP
*DHCP tools.*

* [lsleases](https://github.com/j-keck/lsleases) - dhcp leases sniffer.
    
## DNS
*DNS servers.*

* [Bind](https://www.isc.org/downloads/bind/) - The most widely used name server software.
* [djbdns](http://cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.
* [Designate](https://wiki.openstack.org/wiki/Designate) - DNS REST API that support several DNS servers as its backend.
* [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) - A lightweight service providing DNS, DHCP and TFTP services to small-scale networks.
* [Knot](https://www.knot-dns.cz/) - High performance authoritative-only DNS server.
* [NSD](http://www.nlnetlabs.nl/projects/nsd/) - Authoritative only, high performance, simple name server.
* [PowerDNS](https://www.powerdns.com/) - DNS server with a variety of data storage back-ends and load balancing features.
* [Unbound](http://unbound.net/) - Validating, recursive, and caching DNS resolver.
* [Yadifa](http://yadifa.eu/) - Lightweight authoritative Name Server with DNSSEC capabilities powering the .eu top-level domain.

## Hosting Control Panels
*Web hosting control panels*

* [Ajenti](http://ajenti.org/) - Control panel for Linux and BSD.
* [Feathur](http://feathur.com) - VPS Provisioning and Management Software.
* [ISPConfig](http://www.ispconfig.org) - Hosting control panel for Linux.
* [VestaCP](http://www.vestacp.com/) - Hosting panel for Linux but with Nginx.
* [Virtualmin](http://www.virtualmin.com/) - Control panel for Linux based on webmin.
* [ZPanel](http://www.zpanelcp.com/) - Control panel for Linux, BSD, and Windows.

## IMAP/POP3
*IMAP/POP3 mail servers.*

* [Courier IMAP/POP3](http://www.courier-mta.org/imap/) - Fast, scalable, enterprise IMAP and POP3 server.
* [Cyrus IMAP/POP3](http://cyrusimap.org/) - Intended to be run on sealed servers, where normal users are not permitted to log in.
* [Dovecot](http://www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind.
* [Qpopper](http://www.eudora.com/products/unsupported/qpopper/) - One of the oldest and most popular server implementations of POP3.

## IRC
*IRC*

* [bitlbee](http://www.bitlbee.org) - A gateway of IM protocols (XMPP, MSN, Yahoo, AIM, ICQ, even Twitter) to IRC.
* [ircd-seven](https://dev.freenode.net/redmine/projects/ircd-seven) - Freenode's IRC server.
* [irssi](http://www.irssi.org/) - Timo Sirainen's command-line IRC client.
* [weechat](http://weechat.org/) - Another command-line IRC client.

## IT Asset Management
*IT Assets Management software.*

* [GLPI](http://www.glpi-project.org/spip.php?lang=en) - Information Resource-Manager with an additional Administration Interface.
* [OCS Inventory NG](http://www.ocsinventory-ng.org/en/) - Enables users to inventory their IT assets.
* [RackTables](http://racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
* [Snipe IT](http://snipeitapp.com/) - Asset & license management software.
* [TeemIP](http://www.teemip.com/) - IP and Network address management.
* [phpIPAM](http://phpipam.net/) - IP and Network address management.

## LDAP
*LDAP servers.*

* [389 Directory Server](http://port389.org) - Developed by Red Hat.
* [Apache Directory Server](http://directory.apache.org/) - Apache Software Foundation project written in Java.
* [Fusion Directory](http://www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP.
* [OpenDJ](http://opendj.forgerock.org/) - Fork of OpenDS.
* [OpenDS](https://opends.java.net/) - Another directory server written in Java.
* [OpenLDAP](http://openldap.org/) - Developed by the OpenLDAP Project.

## Load Testing
*Load Testing tools.*

* [Apache JMeter](http://jmeter.apache.org/) - An Open Source Java desktop application for testing Web Applications.
* [Gatling Tool](http://gatling-tool.org/) - An Open Source Stress Tool.

## Log Management
*Log management tools: collect, parse, visualize ...*

* [Echofish](http://www.echothrust.com/projects/echofish) - A web based real-time event log aggregation, analysis, monitoring and management system.
* [Elasticsearch](http://www.elasticsearch.org/) - A Lucene Based Document store mainly used for log indexing, storage and analysis.
* [Fluentd](http://www.fluentd.org/) - Log Collector and Shipper.
* [Flume](https://flume.apache.org/) - Distributed log collection and aggregation system.
* [Graylog2](http://graylog2.org/) - Pluggable Log and Event Analysis Server with Alerting options.
* [Heka](http://hekad.readthedocs.org/en/latest/) - Stream processing system which may be used for log aggregation.
* [Kibana](http://www.elasticsearch.org/overview/kibana/) - Visualize logs and time-stamped data.
* [Log.io](http://logio.org) - Real-time log monitoring in your browser.
* [Logstash](http://logstash.net/) - Tool for managing events and logs.
* [nxlog](http://nxlog-ce.sourceforge.net/) - NXLOG is a universal log collector and forwarder supporting different platforms (BSD, Unix, Linux, Windows, Android), log sources and protocols (Syslog, ...
* [Octopussy](http://www.octopussy.pm) - Log Management Solution (Visualize / Alert / Report).
* [pylog](http://pylog.readthedocs.org) - pylog generates logs, events or metrics (randomly, or otherwise) and sends them using different transports (UDP, AMQP, File, etc..)

## Monitoring
*Monitoring software.*

* [Alerta](https://github.com/guardian/alerta) - Distributed, scaleable and flexible monitoring system 
* [Cacti](http://www.cacti.net) - Web-based network monitoring and graphing tool.
* [Cabot](http://cabotapp.com/) - Monitoring and alerts, similar to PagerDuty.
* [Centreon](http://www.centreon.com) - IT infrastructure and application monitoring for service performance.
* [check_mk](http://mathias-kettner.com/check_mk.html) - Collection of extensions for Nagios.
* [Dash](https://github.com/afaqurk/linux-dash) - A low-overhead monitoring web dashboard for a GNU/Linux machine.
* [Flapjack](http://flapjack.io/) - Monitoring notification routing & event processing system
* [Icinga](https://www.icinga.org/) - Fork of Nagios.
* [LibreNMS](https://github.com/librenms/librenms/) - fork of Observium.
* [Monit](http://mmonit.com/monit/#home) - Small Open Source utility for managing and monitoring Unix systems.
* [Munin](http://munin-monitoring.org/) - Networked resource monitoring tool.
* [Naemon](http://www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features.
* [Nagios](http://www.nagios.org/) - Computer system, network and infrastructure monitoring software application.
* [Observium](http://www.observium.org/) - SNMP monitoring for servers and networking devices. Runs on linux.
* [OMD](http://omdistro.org/) - The Open Monitoring Distribution.
* [Opsview](http://www.opsview.com/solutions/core) - Based on Nagios 4, Opsview Core is ideal for small IT and test environments.
* [Riemann](http://riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis.
* [Sensu](http://sensuapp.org/) - Open source monitoring framework.
* [Seyren](https://github.com/scobal/seyren) - An alerting dashboard for Graphite.
* [Shinken](http://www.shinken-monitoring.org/) - Another monitoring framework.
* [Stashboard](http://stashboard.org) - An open-source status dashboard running on App Engine.
* [System Monitor](https://github.com/abimaelmartell/system_monitor) - Web based system monitor
* [Thruk](http://www.thruk.org/) - Multibackend monitoring webinterface with support for Naemon, Nagios, Icinga and Shinken.
* [Xymon](http://www.xymon.com/) - Network monitoring inspired by Big Brother.
* [Zabbix](http://www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications.
* [Zenoss](http://community.zenoss.org) - Application, server, and network management platform based on Zope.
* [Whoops](http://www.whoopsapp.com/) - Self-hosted tool for logging application events like errors or background worker completion.

### Error Monitoring
*Log exceptions and errors from applications.*

* [Errbit](https://github.com/errbit/errbit) - Error catcher compatible with Airbrake API, in Ruby.
* [Sentry](https://getsentry.com/) - Application monitoring, event logging and aggregation in Python.
* [Squash](http://squash.io/) - Exception reporting and bug analysis tool in Ruby.

## Metric & Metric Collection
*Metric gathering and display software.*

* [Collectd](http://collectd.org/) - System statistic collection daemon.
* [Collectl](http://collectl.sourceforge.net/) - High precision system performance metrics collecting tool.
* [Dashing](http://dashing.io/) - Ruby gem that allows for rapid statistical dashboard development. An all HTML5 approach allows for big screen displays in data centers or conference rooms.
* [dattss](https://github.com/teleportd/dattss) - Realtime Statistics Aggregation Service.
* [Diamond](https://github.com/BrightcoveOS/Diamond) - Python based statistic collection daemon.
* [Ganglia](http://ganglia.sourceforge.net/) - High performance, scalable RRD based monitoring for grids and/or clusters of servers. Compatible with Graphite using a single collection process.
* [Grafana](http://grafana.org/) - A Graphite & InfluxDB Dashboard and Graph Editor.
* [Graph-Explorer](http://vimeo.github.io/graph-explorer/) - A graphite dashboard that's different, from Vimeo.
* [Graphite](http://graphite.readthedocs.org/en/latest/) - Open source scaleable graphing server.
* [Graphite-ng](http://github.com/graphite-ng) - Next generation graphite server.
* [InfluxDB](http://influxdb.com/) - Open source distributed time series database with no external dependencies.
* [KairosDB](https://code.google.com/p/kairosdb/) - Fast distributed scalable time series database, fork of OpenTSDB 1.x.
* [OpenTSDB](http://opentsdb.net/) - Store and server massive amounts of time series data without losing granularity.
* [RRDtool](http://oss.oetiker.ch/rrdtool/) - Open source industry standard, high performance data logging and graphing system for time series data.
* [Statsd](https://github.com/etsy/statsd/) - Application statistic listener.
* [Tessera](https://github.com/urbanairship/tessera) - A flexible dashboard front-end for Graphite.

## Network Configuration Management
*Network configuration management tools.*

* [GestióIP](http://www.gestioip.net/) - An automated web based IPv4/IPv6 IP Address Management tool.
* [Netdot](http://netdot.uoregon.edu/) - A NETwork DOcumentation Tool, designed to help network administrators collect, organize and maintain network documentation.
* [NOC Project](http://nocproject.org/) - Scalable, high-performance and open-source [OSS](http://en.wikipedia.org/wiki/Operations_support_system) system for ISP, service and content providers.
* [RANCID](http://www.shrubbery.net/rancid/) - Monitors network device's configurarion and maintain history of changes.
* [rConfig](http://www.rconfig.com/) - Another network device configuration management tool.

## Newsletters
*Newsletter software.*

* [DadaMail](http://dadamailproject.com/) - Mailing List Manager, written in Perl.
* [phpList](http://www.phplist.com/) - Newsletter manager written in PHP.

## NoSQL
*NoSQL databases.*

* Column-Family
  * [Apache HBase](http://hbase.apache.org/) - Hadoop database, a distributed, big data store.
  * [Cassandra](http://cassandra.apache.org/) - Distributed DBMS designed to handle large amounts of data across many servers.
  * [Hypertable](http://hypertable.org/) - C++ based BigTable-like DBMS, communicates through Thrift and runs either as stand-alone or on distributed FS such as Hadoop.
* Document Store
  * [CouchDB](http://couchdb.apache.org/) - Ease of use, with multi-master replication document-oriented database system.
  * [ElasticSearch](http://www.elasticsearch.org/) - Java based database, popular with log aggregation, and email archiving projects.
  * [MongoDB](http://www.mongodb.org/) - Another document-oriented database system.
  * [RavenDB](http://ravendb.net/) - Document based database with ACID/Transactional features.
  * [RethinkDB](http://www.rethinkdb.com/) - Open source distributed document store database, focuses on JSON.
* Graph
  * [FlockDB](https://github.com/twitter/flockdb) - Twitter's distributed, fault-tolerant graph database.
  * [Neo4j](http://www.neo4j.org/) - Open source graph database.
* Key-Value
  * [Couchbase](http://www.couchbase.com/) - In-memory, replicated, peristent key/value datastore.
  * [LevelDB](https://code.google.com/p/leveldb/) - Google's high performance key/value database.
  * [Redis](http://redis.io/) - Networked, in-memory, key-value data store with optional durability.
  * [Riak](http://basho.com/riak/) - Another fault-tolerant key-value NoSQL database.

Comparison of NoSQL servers: http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

## Packaging

* [CMake](http://www.cmake.org/) - Cross-platform build and packaging software.
* [fpm](https://github.com/jordansissel/fpm) - Versatile multi format package creator.
* [omnibus-ruby](https://github.com/opscode/omnibus-ruby) - Full stack, cross distro packaging software (Ruby).
* [packer](http://packer.io) - Packer is a free and open source tool for creating golden images for multiple platforms from a single source configuration.
* [packman](http://packman.readthedocs.org) - Full stack, cross distro packaging software (Python).
* [tito](https://github.com/dgoodwin/tito) - Builds RPMs for git-based projects.
* [TWW Toolsets](http://www.thewrittenword.com/products/) - Hyper package management system,both toolsets and package sources are free (Python).

## Queuing

* [ActiveMQ](http://activemq.apache.org/) - An open source message broker written in Java together with a full JMS client
* [BeanstalkD](http://kr.github.io/beanstalkd/) - A simple, fast work queue.
* [Gearman](http://gearman.org/) - Fast multi-language queuing/job processing platform.
* [NSQ](http://nsq.io/) - A realtime distributed messaging platform.
* [RabbitMQ](http://www.rabbitmq.com/) - Robust, fully featured, cross distro queuing system.
* [ZeroMQ](http://zeromq.org/) - Lightweight queuing system.
* [Kafka](http://kafka.apache.org/) - A high-throughput distributed messaging system.

## Remote Execution

* [Fabric](http://www.fabfile.org/) - An advanced SSH Module for Python to remotely (and locally) execute commands (Used for Application Deployment as well).
* [Capistrano](http://capistranorb.com/) - An advanced SSH Module for Ruby to remotely (and locally) execute commands (Used for Application Deployment as well).
* [winexe](http://sourceforge.net/projects/winexe/) - Remotely run commands on Windows from Linux using RPC.
* [pywinrm](https://github.com/diyan/pywinrm) - Python client to control WinRM.
* [winrm](https://github.com/WinRb/WinRM) - Ruby client to control WinRM.

## RDBMS
*Relational DBMS.*

* [Firebird](http://www.firebirdsql.org/) - True universal open source database.
* [Galera](http://galeracluster.com/) - Galera Cluster for MySQL is an easy-to-use high-availability solution with high system up-time, no data loss, and scalability for future growth.
* [MariaDB](https://mariadb.org/) - Community-developed fork of the MySQL.
* [MySQL](http://dev.mysql.com/) - Most popular RDBMS server.
* [Percona Server](http://www.percona.com/software) - Enhanced, drop-in MySQL replacement.
* [PostgreSQL](http://www.postgresql.org/) - Object-relational database management system (ORDBMS).
* [PostgreSQL-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based database cluster.
* [SQLite](http://sqlite.org/) - Library that implements a self-contained, serverless, zero-configuration, transactional SQL DBS.

## Security
*Security tools.*

* [AIDE](http://aide.sourceforge.net/) - The Advanced Intrusion Detection Environment, developed as a free replacement for Tripwire as a data integrity tool.
* [Bro](http://www.bro.org) - A highly advanced network analysis framework.
* [Denyhosts](http://denyhosts.sourceforge.net/) - Thwart SSH dictionary based attacks and brute force attacks.
* [Fail2Ban](http://www.fail2ban.org/wiki/index.php/Main_Page) - Scans log files and takes action on IPs that show malicious behavior.
* [Metasploit](http://www.metasploit.com/) - Penetration testing framework.
* [Nessus](http://www.tenable.com/products/nessus) - Nessus is a proprietary comprehensive vulnerability scanner.
* [nprobe](http://www.ntop.org/products/nprobe/) - NetFlow analysis/audit toolkit.
* [ntopng](http://www.ntop.org/products/ntop/) - High-Speed Web-based Traffic Analysis and Flow Collection.
* [OpenVAS](http://www.openvas.org/) - Open-source vulnerability scanner and manager.
* [Ossec](http://www.ossec.net) - Host-based Intrusion Detection System that performs log analysis, file integrity checking, policy monitoring, rootkit detection, real-time alerting and active response.
* [Samhain](http://la-samhna.de/samhain/) - Host-based intrusion detection system, with file integrity checking, log file monitoring/analysis, rootkit detection, port monitoring, detection of rogue SUID execs and hidden processes.
* [Snort](http://www.snort.org/) - Open-source network intrusion prevention and detection system.
* [SpamAssassin](https://spamassassin.apache.org/) - A powerful and popular email spam filter employing a variety of detection techniques.
* [Tripwire (Open Source)](http://sourceforge.net/projects/tripwire/) - Data integrity tool, useful for monitoring and altering on specific file changes.
* [Wazuh](https://wazuh.com/) - HIDS based on OSSEC with the Elastic Stack
* [Yasat](http://yasat.sourceforge.net/) - Scan configuration files, kernel parameters and shows the best practices for each cases.

## Service Management
*Software for managing system services*

* [Corosync](http://corosync.github.com/corosync) - The Corosync Cluster Engine is a Group Communication System with additional features for implementing high availability within applications.
* [etcd](https://github.com/coreos/etcd) - A highly-available key value store for shared configuration and service discovery
* [fleet](https://github.com/coreos/fleet) - fleet ties together systemd and etcd into a distributed init system.
* [Serf](http://www.serfdom.io/) - Service orchestration and management tool.
* [Systemd](http://www.freedesktop.org/wiki/Software/) - systemd is a system and service manager for Linux, compatible with SysV and LSB init scripts.
* [Zookeeper](http://zookeeper.apache.org) - ZooKeeper is an open source Apache™ project that provides a centralized infrastructure and services that enable synchronization across a cluster.

## SMTP
*SMTP servers.*

* [Exim](http://www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge.
* [Haraka](http://haraka.github.io/) - A high-performance, pluginable SMTP server written in JavaScript.
* [MailCatcher](http://mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development.
* [Maildrop](https://github.com/m242/maildrop) - Open Source disposable email SMTP server, also useful for development.
* [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project.
* [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement.
* [Qmail](http://cr.yp.to/qmail.html) - Secure Sendmail replacement.
* [Sendmail](http://www.sendmail.com/sm/open_source/) - Message transfer agent (MTA).

## Software Containers
*Operating system–level virtualization.*

* [Docker](http://www.docker.com/) - Open platform for developers and sysadmins to build, ship, and run distributed applications.
* [dokku](https://github.com/progrium/dokku) - Docker powered mini-Heroku in around 100 lines of Bash
* [Fig](http://orchardup.github.io/fig/) - Fast, isolated development environments using Docker.
* [OpenVZ](http://openvz.org) - Container-based virtualization for Linux.
* [shipyard](https://github.com/shipyard/shipyard) - Shipyard is a web UI for http://docker.io

## SSH
*SSH tools.*

* [Ansible](http://www.ansible.com) - A general purpose automation stack using SSH that can run ad-hoc actions as well
* [autossh](http://www.harding.motd.ca/autossh/) - Automatically respawn ssh session after network interruption.
* [Cluster SSH](http://sourceforge.net/projects/clusterssh/) - Controls a number of xterm windows via a single graphical console.
* [DSH](http://www.netfort.gr.jp/~dancer/software/dsh.html.en) - Dancer's shell / distributed shell - Wrapper for executing multiple remote shell commands from one command line.
* [Mosh](http://mosh.mit.edu/) - The mobile shell.
* [parallel-ssh](http://code.google.com/p/parallel-ssh/) - Provides parallel versions of OpenSSH and related tools.
* [pdsh](https://code.google.com/p/pdsh/) - Pdsh is a high-performance, parallel remote shell utility.
* [Socketpipe](http://www.spinellis.gr/sw/unix/socketpipe/) - Very efficient TCP connection between remote processes.
* [ssh-ca](https://github.com/cloudtools/ssh-ca/) - Allows giving ssh access to servers without putting a users key on the server, as well as expiring access.
* [SSH Power Tool](http://code.google.com/p/sshpt/) - Execute commands and upload files to many servers simultaneously without using pre-shared keys.
* [stormssh](http://stormssh.readthedocs.org) - A command line tool to manage SSH connections.
* [termius](https://termius.com/) - Termius is the SSH client that works on ‍Desktop and Mobile
## Statistics
*Analytics software.*

* [Analog](http://www.analog.cx/) - The most popular logfile analyser in the world.
* [GoAccess](http://goaccess.io/) - Open source real-time web log analyzer and interactive viewer that runs in a terminal.
* [Piwik](http://piwik.org/) - Free and open source web analytics application.
* [Webalizer](http://www.webalizer.org/) - Fast, free web server log file analysis program.

## Ticketing systems
*Web-based ticketing system.*

* [Bugzilla](http://www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project.
* [Cerb](http://www.cerberusweb.com/) - A group-based e-mail management project built with a commercial open source license.
* [Flyspray](http://flyspray.org) - Web-based bug tracking system written in PHP.
* [MantisBT](http://www.mantisbt.org/) - Another web-based bug tracking system.
* [osTicket](http://osticket.com/) - Open source support ticket system.
* [Otrs](http://www.otrs.com/) - A free and open-source trouble ticket system software package that a company, organization, or other entity can use to assign tickets to incoming queries and track further communications about them.
* [Redmine](http://www.redmine.org/) - Open source project management/ticketing web application written in Ruby.
* [Request Tracker](http://www.bestpractical.com/rt/) - Ticket-tracking system written in Perl.
* [TheBugGenie](http://www.thebuggenie.com) - Open source ticket system with extremely complete users rights granularity.

## Troubleshooting
*Troubleshooting Tools.*

* [mitmproxy](http://mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems.
* [Nmap](http://nmap.org/) - Security scanner, with host discovery, port scanning, version detection and OS detection capabilities.
* [Sysdig](http://www.sysdig.org/) - Capture system state and activity from a running Linux instance, then save, filter and analyze.
* [tcpdump](http://www.tcpdump.org/) - A powerful command-line packet analyzer.
* [TRK](http://trinityhome.org) - CPR for your computer! Trinity Rescue Kit is a linux toolkit as a livecd for general computer troubleshooting. Useful for Win, Linux, and OSX.
* [Wireshark](http://www.wireshark.org/) - Open-source packet analyzer. Previously known as Ethereal.

## Project Management
*Web-based project management and bug tracking systems.*

* [ChiliProject](https://www.chiliproject.org) - Fork of Redmine.
* [GitBucket](https://github.com/takezoe/gitbucket) Clone of GitHub written in Scala; single jar install.
* [GitLab](https://www.gitlab.com/) - Clone of GitHub written in Ruby. 
* [Gogs](http://gogs.io/) - Written in Go.
* [OpenProject](https://www.openproject.org) - Project collaboration with open source.
* [Phabricator](http://phabricator.org/) Written in PHP.
* [Redmine](http://www.redmine.org/) - Written in ruby on rails.
* [The Bug Genie](http://www.thebuggenie.com/) - Written in PHP.
* [Trac](http://trac.edgewall.org/) - Written in python.
* [Tuleap](http://www.tuleap.net/) - Written in PHP.

## Version control
*Software versioning and revision control.*

* [Fossil](http://www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.
* [Git](http://git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed.
* [GNU Bazaar](http://bazaar.canonical.com/) - Distributed revision control system sponsored by Canonical.
* [Darcs](http://darcs.net/) - Distributed version control based of patches and changes instead of snapshots.
* [Mercurial](http://mercurial.selenic.com/) - Another distributed revision control.
* [Subversion](http://subversion.apache.org/) - Client-server revision control system.

## Virtualization
*Virtualization software.*

* [Bitnami](https://bitnami.com/) - Freely available VMs for applications described in this list: [GitLab](https://bitnami.com/stack/gitlab), [Jenkins](https://bitnami.com/stack/jenkins), [MantisBT](https://bitnami.com/stack/mantis), [Redmine](https://bitnami.com/stack/redmine), [Trac](https://bitnami.com/stack/trac) and [more](https://bitnami.com/stacks).
* [Ganeti](https://code.google.com/p/ganeti/) - Cluster virtual server management software tool built on top of KVM and Xen.
* [KVM](http://www.linux-kvm.org) - Linux kernel virtualization infrastructure.
* [oVirt](http://www.ovirt.org/) - Manages virtual machines, storage and virtual networks.
* [OpenNebula](http://opennebula.org/) - Flexible enterprise cloud made simple
* [Packer](http://www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration.
* [Proxmox VE](https://www.proxmox.com/proxmox-ve) - Complete open source virtualization management solution
* [QEMU](http://www.qemu.org/) - QEMU is a generic and open source machine emulator and virtualizer.
* [Vagrant](https://www.vagrantup.com/) - Tool for building complete development environments.
* [VirtualBox](https://www.virtualbox.org/) - Virtualization product from Oracle Corporation.
* [Xen](http://www.xenproject.org/) - Virtual machine monitor for 32/64 bit Intel / AMD (IA 64) and PowerPC 970 architectures.

## VPN
*VPN software.*

* [OpenVPN](https://community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange.
* [Pritunl](http://pritunl.com/) - OpenVPN based solution. Easy to set up.
* [SoftEther](https://www.softether.org/) - Multi-protocol software VPN with advanced features
* [sshuttle](https://github.com/apenwarr/sshuttle) - Poor man's VPN.
* [strongSwan](http://www.strongswan.org/) - Complete IPsec implementation for Linux.
* [tinc](http://www.tinc-vpn.org/) - Distributed p2p VPN.
* [SigmaVPN](http://frozenriver.net/SigmaVPN) - SigmaVPN is simple, light-weight and modular VPN software for UNIX systems, deploying the NaCl encryption library. 

## XMPP
*XMPP servers.*

* [ejabberd](http://www.ejabberd.im/) - XMPP instant messaging server written in Erlang/OTP.
* [Metronome IM](http://www.lightwitch.org/metronome) - Fork of Prosody IM.
* [MongooseIM](https://www.erlang-solutions.com/products/mongooseim-massively-scalable-ejabberd-platform) - Fork of ejabberd.
* [Openfire](http://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server.
* [Prosody IM](http://prosody.im/) - XMPP server written in Lua.
* [Tigase](https://projects.tigase.org/projects/tigase-server) - XMPP server implementation in Java.

## Webmails
*Webmail applications.*

* [Mailpile](https://www.mailpile.is/) - A modern, fast web-mail client with user-friendly encryption and privacy features.
* [RainLoop](http://rainloop.net/) - Simple, modern & fast web-based IMAP client.
* [Roundcube](http://roundcube.net/) - Browser-based IMAP client with an application-like user interface.

## Web
*Web servers.*

* [Apache](http://httpd.apache.org/) - Most popular web server.
* [Cherokee](http://cherokee-project.com/) - Lightweight, high-performance web server/reverse proxy.
* [Lighttpd](http://www.lighttpd.net/) - Web server more optimized for speed-critical environments.
* [Nginx](http://nginx.org/) - Reverse proxy, load balancer, HTTP cache, and web server.
* [uWSGI](https://github.com/unbit/uwsgi/) - The uWSGI project aims at developing a full stack for building hosting services.

*Web Performance*

* [HAProxy](http://www.haproxy.org/) - Software based load Balancing, SSL offloading and performance optimization, compression, and general web routing.
* [Squid](http://www.squid-cache.org/) - Caching proxy for the web supporting HTTP, HTTPS, FTP, and more.
* [Varnish](https://www.varnish-cache.org/) - HTTP based web application accelerator focusing on optimizing caching and compression.

## Wikis
*Wiki software.*

* [DokuWiki](https://www.dokuwiki.org/dokuwiki) - Simple to use and highly versatile wiki that doesn't require a database.
* [Gollum](https://github.com/gollum/gollum) - A simple, Git-powered wiki with a sweet API and local frontend.
* [ikiwiki](http://ikiwiki.info/) - A wiki compiler.
* [Mediawiki](http://www.mediawiki.org/wiki/MediaWiki) - Used to power Wikipedia.
* [MoinMoin](http://moinmo.in/) - An advanced, easy to use and extensible WikiEngine with a large community of users.
 * [Ōlelo Wiki](https://github.com/minad/olelo) - A a wiki that stores pages in a Git repository.
* [TiddlyWiki](http://tiddlywiki.com) - Complete interactive wiki in JavaScript.

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [Code as Craft](http://codeascraft.com/) - Etsy's Ops blog, lots of technical posts.
* [DevOpsGuys](http://blog.devopsguys.com/) - Devops consultants who blog about operations.
* [Rackspace Developers](http://developer.rackspace.com/blog/) - Slightly biased blog with lots of Devops Topics.

## Books
*Sysadmin related books.*

* [OpenSSL Cookbook](https://www.feistyduck.com/books/openssl-cookbook/) - A free ebook about OpenSSL basics and how to create secure configurations by Ivan Ristić.
* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](http://itrevolution.com/books/phoenix-project-devops-book/) - How DevOps techniques can fix the problems that happen in IT organizations.
* [The Practice of System and Network Administration](http://everythingsysadmin.com/books.html) - The first and second editions describes the best practices of system and network administration, independent of specific platforms or technologies.
* [The Visible Ops Handbook: Implementing ITIL in 4 Practical and Auditable Steps](http://www.itpi.org/the-visible-ops-handbook-review.html) - Is a methodology designed to jumpstart implementation of controls and process improvement.
* [UNIX and Linux System Administration Handbook](http://www.admin.com/) - Approaches system administration from a practical perspective.

## Editors
*Open source code editors.*

* [Atom](https://atom.io/) - A hackable text editor from Github.
* [Brackets](http://brackets.io/) - Open source code editor for web designers and front-end developers.
* [Eclipse](http://eclipse.org/) - IDE written in Java with an extensible plug-in system.
* [Geany](http://www.geany.org/) - GTK2 text editor.
* [GNU Emacs](http://www.gnu.org/software/emacs/) - An extensible, customizable text editor-and more.
* [Haroopad](http://pad.haroopress.com/) - Markdown editor with live preview.
* [ICEcoder](http://icecoder.net) - Code editor awesomeness, built with common web languages.
* [jotgit](https://github.com/jdleesmiller/jotgit) - Git-backed real-time collaborative code editing.
* [Light Table](http://www.lighttable.com/) - The next generation code editor.
* [Lime](http://limetext.org/) - Aims to provide an open source solution to Sublime Text
* [Vim](http://www.vim.org) - A highly configurable text editor built to enable efficient editing.

## Repositories
*Software package repositories.*

* [Dotdeb](http://www.dotdeb.org/) - Repository with LAMP updated packages for Debian.
* [Remi](http://rpms.famillecollet.com/) - Repository with LAMP updated packages for RHEL/Centos/Fedora.

## Websites
*Useful sysadmin related websites.*

* [High Scalability](http://www.highscalability.com) - Blog to help you build successful scalable websites.
* [Ops School](http://www.opsschool.org) - Comprehensive program that will help you learn to be an operations engineer.
* [Digital Ocean Tutorials](https://www.digitalocean.com/community/tutorials) - A surprisingly vast resource for getting the basics of certain applications, tools, or even systems administration topics. (Note: Digital Ocean pays authors for this content)
* [Servers for Hackers](http://serversforhackers.com/) - Newsletter for programmers who find themselves needing to know their way around a server.

# GitTools
* [GitFlow](https://github.com/nvie/gitflow) - Git extensions to provide high-level repository operations for Vincent Driessen's branching model.
* [GitFlowCheatsheet](http://danielkummer.github.io/git-flow-cheatsheet) - GitFlow cheatsheet
* [Gource](https://code.google.com/p/gource/) - Software version control visualization

# Versioning
* [Semver](http://semver.org) - Semantic Versioning

# Contributing
Please see [CONTRIBUTING](https://github.com/kahun/awesome-sysadmin/blob/master/CONTRIBUTING.md) for details.

