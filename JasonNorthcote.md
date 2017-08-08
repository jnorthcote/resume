# Jason Northcote
## Principal Software Developer, Architect, DevOPS Engineer
-----
> 158 Forest View Dr. San Francisco, CA  
> (415) 218-3795  
> [jason.northcote@gmail.com](jason.northcote@gmail.com)  
> [www.linkedin.com/in/jason-northcote](https://www.linkedin.com/in/jason-northcote)  
> [Download PDF](resume.pdf)  

------
### Profile
An experienced software developer with an affinity for operations oriented problem solving and a professional carreer spanning 20+ years working for companies ranging from global corporations having 15k+ employees to 5 person shops run from the owner's basement.  While having occupied most roles possible within an engineering organization, a return to a role focused on developing solutions aimed at solving operational challenges is preferable

------
### Experience

#### [New Relic Inc.](https://newrelic.com/) - SaSS application performance monitoring solution based in San Francisco and Portland OR

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
    * Usage metering microservices for usage data collection and reporting to internal billing infrastructure services and AWS Marketplace infrastructure

* **Skills:** _microservices, go, docker, consul, ec2, s3, mesos, marathon, terraform, chef, kafka, elasticsearch, cassandra, jenkins, openresty(nginx/lua), syslog, lvm, devicemapper, vagrant, nodejs, reactjs_

#### [DemandForce.com](http://www.demandforce.com/) - Automated marketing, reputation and appointment management solution aimed at the small business segment (formerly a division of Intuit under the SMB organization divested in Feb 2016)

* **Principal Software Engineer** - __Feb 2015-Feb 2016__  
Backend Engineer on dynamic data storage and ingest routing platform supporting the Intuit Local and Increased Upload Frequency initiatives
  * Designed and implemented data API gateway using OpenResty framework based on nginx+/Lua with API routing and segmented A/B percentage rules
  * Designed and implemented distributed configuration system based on Consul allowing changes to routing rules for API endpoints, segmenting criteria, segment criteria and explicit white/black listing clients as well as integrating with the Scala `ApplicationLoader` used to configure backend micro services
  * Designed `docker-compose` based development environment and production deployment systems
  * Improved docker production environment reliability, logging integration with Splunk, volume management and image version promotion and rollback

* **Principal Software Engineer (Team Lead)** - __May 2014-Jan 2015__  
Lead Onboarding project initiative data layer design and REST API development
  * Designed and implemented a multi-layer data REST API generation framework using MDA principals based on UML generation from DDL definitions followed by Java/Jersey/Spring generation from UML models
  * Implemented low level data API endpoints for legacy datastore entities and new onboarding datastore entities with built-in entity access filtering based on `Principal` identity as well as enabling complex dynamic JSON graph responses (up to 6 levels deep with protecttion against circular references) using a robust graph query language supporting paging, sorting and criteria based filtering at any layer of the graph
  * Implemented high level composite data API utilizing the low level APIs to construct pre-defined views for high traffic UI calls  

* **Software Architect** - __Aug 2013-Apr 2014__
Primary technical advisor on acquisition team responsible for talent and technology compatibility analysis and due diligence assessment
  * **Online calendar and appointment scheduling acquisition:** Lead technical assessment of two target companies and provided analysis and recommendation based on interviews with development team members, product team lead and architecture lead with an emphasis on technology, skillsets and industry knowledge
  * **Primary Automotive vertical competitor acquisition:** Acted as primary acquisition team technical advisor during the 6 month process responsible for the following technical assessment and due diligence tasks
    * Development team assessment of skillsets, seniority, knowledge coverage, SPOF personel identification
    * Codebase quality, maturity, technologies used, third party license compliance, integration partnership dependencies
    * Datacenter hardware, technology, reliability, disaster recovery, future scalability, fault tolerance
    * Customer classification analysis matrix with an emphasis on retention prediction, supportability and revenue estimates based on subscribed services
    * Deep dive into technical aspects of differentiators in their product offering. e.g. significantly better postcard target segmentation, rapid postcard production at reduced cost and elimination of manual proofing delays 
      
* **Software Architect** - __Aug 2013-Apr 2014__
Lead the messaging backend architecture redesign effort focusing on maintainability, reliability, scalability and capability
  * **Maintainability:** Separation of messaging code from the monolith, remove(reduce) crippling (sometimes circular) dependencies on the monthly 'train deployment', code repository isolation increases visibility and better enables tracking root cause changes
  * **Reliability:** Service separation enables better monitoring, point of failure identification in multi-phase message processing and delivery, transient failures can be handled/re-tried better within isolated services
  * **Scalability:** Separate services can be scaled individually based on resource needs, backpressure and congestion are more readily identifiable
  * **Capability:** Expanding service capabilities in each phase (queuing, decoration, parsing, formatting, delivery) is simplified when each concern can be addressed in isolation, e.g. moving to a better queueing technology, adding voice as a delivery endpoint
    
* **Staff Software Engineer** - __Jan 2013-Jul 2013__
Analytics and Revenue recognition team member
  * Identified and fixed multiple long standing issues in legacy code related to revenue calculation errors and discrepancies
  * Developed components of a data ETL pipeline from legacy sharded mysql databases to Amazon Redshift analytics datastore
  * Optimized several background maintenance stored procedures reducing execution time from hours to seconds using cursors, indexes, optimized temp tables and eliminating outer joins on inefficient sub-queries
    
* **Skills:** _mysql, java, scala, nodejs, nginx, lua, consul, redshift, tomcat, jetty, httpd, spring, camel, hibernate, infinispan, jersey, jackson, rabbitmq, kafka, memcached, redis, elasticsearch, c3p0, aop, git, mercurial, docker, eclipse emf, andromda, velocity_

#### Payvment Inc. - Social commerce platform providing storefront creation on Facebook and later on Lish.com as well (acquired by Intuit Inc. in 2013)

* **Principal Software Engineer** - __May 2011-Jan 2013__
Backend engineer responsible for all aspects of data access storage and integration
  * Developed conversion plan, associated scripts and engine tuning configuration to transition from the ISAM engine to InnoDB
  * Developed data access REST API java service to replace multiple legacy native PHP data access implementations each with serious issues including SQL injection vulnerabilities, orphaned rows, foreign key violations, lack of transaction management and cross session polution
  * Developed and implemented database design conversion plan to address issues related to extensive denormalized table definitions, reliance on external identifiers as primary keys, a lack of a principal identity entity and sub-entity ownership

* **Skills:** _social relevance algorithms, mysql, elasticsearch, java, php, zookeeper, jboss, apache httpd, spring, hibernate, infinispan, jersey, jackson, rabbitmq, memcached, aop, git, maven, artifactory, jenkins, hadoop, magicdraw, andromda, velocity_

#### [Yahoo! Groups](https://groups.yahoo.com)

* **Senior Software Engineer** - __Jun 2008-Apr 2011__
Backend engineer performing in a "swiss army knife" role with a special focus on development projects to address operational issues
  * Addressed numerous assorted issues requiring extensive "code archeology" within the massive legacy codebase with little to no documentation or remaining team knowledge
  * Designed a multi-tiered, full-text indexed message search system with multi-datacenter replication spanning over 400 nodes capable of handling the ~7 billion messages as a replacement for the existing non-redundant, non-reproducible message search system nearing capacity
    
* **Skills:** _scalable systems, ci-cd concepts, java, c, c++, python, xslt, xerces, icu, multipart-mime encoding, multi-byte character encoding, i18n, i10n, jboss, yui, spring, akamai, tibco, oracle, bamboo, hudson, svn, perforce_
