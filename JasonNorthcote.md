# Jason Northcote
## Principal Software Developer, Architect, DevOPS Engineer

> [Download PDF](resume.pdf)  
> [jason.northcote@gmail.com](jason.northcote@gmail.com)  
> [www.linkedin.com/in/jason-northcote](https://www.linkedin.com/in/jason-northcote)  
> (415) 218-3795  

------

### Experience

#### New Relic Inc.

* [New Relic](https://newrelic.com/) - SaSS application performance monitoring solution based in San Francisco and Portland OR

  * **Lead Software Engineer** - __Feb 2016-Feb 2017__  
  Joined the newly acquired Opsmatic team as a full stack engineer to help develop and launch the their new Infrastructure product offering with an aggressive one year hard launch deadline.  The team was was constructed as a nearly autonomous unit employing DevOPS and agile principals responsible for every phase of the development lifecycle from initial design to production deployment and on-call monitoring.  
    * Designed `docker-compose` based local development environment enabling rapid onboarding and code development
    * Made significant improvements to provisioning process and instance management including ami hardening, devicemapper volume configuration, syslog configuration, syslog shipping to Papertrail and `chef-solo` cookbook and provisioning enhancements
    * Implemented docker production hardening changes including syslog integration, devicemapper storage driver configuration and separation between image and volume storage, container and volume maintenance and `Dockerfile` optimizations to labels, environment, image contents and layer construction and process lifecycle handling
    * Designed and implemented `Gravedigger` sub-system microservices responsible for purging stale instance data from `Cassandra` and `Elasticsearch` data storage
    * Acted as lead, developer and Infrastructure team contact for the company wide Infrastructure pricing project coordinating five additional development teams.  Infrastructure pricing development efforts included:
      * Ingest sub-system subscription lifecycle handling for trial initiation, authorization, blacklisting and rate limiting
      * UI 'paywall' subscription states for None, Trial Started, Active/Data received and Expired
      * Data classification and retention levels based on subscription type
      * Usage metering sub-system collecting instance/hr usage data based on agent heartbeat kafka messages flowing at a rate of 1/10s
      * Usage reporting microservice sending metering data as kafka messages for consumption by internal billing infrastructure services
      * Usage reporting microservice sending metering data as AWS Marketplace REST API calls as part of a beta integration partnership

  **Skills:** _Go, git, docker, ec2, s3, centos, mesos, marathon, terraform, chef, ruby, kafka, elasticsearch, cassandra, jenkins, openresty(nginx/lua), syslog, lvm, devicemapper, papertrail, bash, vagrant, virtualbox, vmware, nodejs, reactjs, webpack, json, thrift_
      

#### DemandForce.com (formerly a division of Intuit under the SMB organization divested in Feb 2016)

* [DemandForce](http://www.demandforce.com/) - Automated marketing, reputation and appointment management solution aimed at the small business segment

  * **Principal Software Engineer** - __May 2014-Feb 2016__

  * **Software Architect** - __Aug 2013-Apr 2014__

  * **Staff Software Engineer** - __Jan 2013-Jul 2013__

#### Payvment Inc. (rebranded as Lish.com in 2012 and later acquired by Intuit Inc.)

* Formerly a social commerce platform initially focused on allowing small businesses to easily setup a storefront on Facebook leveraging the platform's social interaction and advertising capabilities.  The company later rebranded and launched Lish.com as an alternative social commerce site independent of the Facebook platform

  * **Principal Software Engineer** - __May 2011-Jan 2013__

#### Yahoo Inc. - Yahoo! Groups

* [Yahoo! Groups](https://groups.yahoo.com/neo) - Formerly a relevant search engine, mail provider and web portal

  * **Senior Software Engineer** - __Jun 2008-Apr 2011__
