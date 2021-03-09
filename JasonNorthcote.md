# Jason Northcote

## Principal Software Developer, Architect, DevOPS Engineer

-----
> 158 Forest View Dr. San Francisco, CA  
> (415) 218-3795  
> [jason.northcote@gmail.com](jason.northcote@gmail.com)  
> [www.linkedin.com/in/jason-northcote](https://www.linkedin.com/in/jason-northcote)  
> [Download PDF](https://github.com/jnorthcote/resume/releases/download/2017-08-08/JasonNorthcote.pdf)  

------
### Profile
An experienced software developer with an affinity for operations oriented problem solving and a professional career spanning 20+ years working for companies ranging from global corporations having 15k+ employees to 5 person shops run from the owner's basement.  While having occupied most roles possible within an engineering organization, a return to a role focused on developing solutions aimed at solving operational challenges is preferable

------
### Skills
* **Languages:** _Go, Java, Scala, Javascript, Lua, C, C++, Python, SQL, PHP, Ruby_
* **Frameworks:** _Spring, Camel, Jersey, Jackson, Hibernate, Infinispan, ReactJS_
* **Provisioning/CI/CD:** _Mesos, Marathon, Terraform, Chef, Docker, Vagrant, Jenkins, Bamboo, Hudson_
* **Storage and Messaging:** _Oracle, MySql, Cassandra, Hadoop, Memcached, Redis, Elasticsearch, Kafka, RabbitMQ, Tibco EMS_
* **Cloud and Servers:** _EC2, S3, Redshift, Tomcat, Jetty, Httpd, JBoss, Nginx, Consul, Zookeeper_
* **SCM:** _Git, SVN, Perforce, Mercurial, CVS_

------
### Experience

#### [Intuit Inc.](https://intuit.com/) - TurboTax, Quickbooks and Mint based in Mountain View CA

* **Staff Software Engineer (Modern SaaS Team) - Jun 2018-Apr 2019**  
The huge success of the QBO containerization work, measured by significant gains in build confidence and product quality, effectively eliminated the need for a traditional pre-production environment or support team. We transitioned to a centralized service provider as part of a `1-click` service registration, provisioning and deployment orchestration fabric the Modern SaaS Team responsible for scaling up the work  
  * Developed Blue Ocean instance template, bootstrap scripting and REST accessible management jobs used to provision and maintain a fleet of instances each scoped to a registered development organization
  * Developed a shared library based service pipeline template and job DSL based provisioning API used to generate job hierarchy with project scoped secrets and role based permissions

* **Staff Software Engineer (Quickbooks Online Pre-production Support & Tools) - Aug 2017-Jun 2018**  
Lead development on containerization of the QBO application and conversion of the existing CICD process to a container native one from the initial proof-of-concept to production readiness
  * Pair-developed the infrastructure deployment definitions
    * Terraform templates for deploying Kubernetes clusters in the `corp` zone for Jenkins Blue Ocean and the `qa` zone for ephemeral instances of the QBO application
    * Pod templates for the Jenkins Blue Ocean master using attached persistent storage and a variably sized label addressable agent node pool, and a Zalenium cluster configuration for running a Selenium grid with multi-browser support and automatic video recording
  * Created a parallel container centric CICD pipeline for Quickbooks
    * Created image definitions for shared base images, the QBO runtime, java and docker builder images, and optimized repository reference images for git and maven
    * Adapted the QBO shell execution plan into a scripted pipeline with the initial goal being functional parity followed by enhancements to reduce productivity losses caused by broken builds due to defect promotion.


#### [New Relic Inc.](https://newrelic.com/) - SaSS application performance monitoring solution based in San Francisco and Portland OR

* **Lead Software Engineer - Feb 2016-Feb 2017**  
Joined the newly acquired Opsmatic team as a full stack engineer to help develop and launch the new Infrastructure product offering with an aggressive one year hard launch deadline.  The team was was constructed as a nearly autonomous unit employing DevOPS and agile principals responsible for every phase of the development lifecycle from initial design to production deployment and on-call monitoring.  
  * Designed `docker-compose` based local development environment enabling rapid onboarding and code development
  * Made significant improvements to provisioning process and instance management including ami hardening, devicemapper volume configuration, syslog configuration, syslog shipping to Papertrail and `chef-solo` cookbook and provisioning enhancements
  * Implemented docker production hardening changes including syslog integration, devicemapper storage driver configuration and separation between image and volume storage, container and volume maintenance and `Dockerfile` optimizations to labels, environment, image contents and layer construction and process lifecycle handling
  * Designed and implemented `Gravedigger` sub-system microservices responsible for purging stale instance data from `Cassandra` and `Elasticsearch` data storage
  * Acted as lead, developer and Infrastructure team contact for the company wide Infrastructure pricing project coordinating five additional development teams.  Infrastructure pricing development efforts included:
    * Ingest sub-system subscription lifecycle handling for trial initiation, authorization, blacklisting and rate limiting
    * UI 'paywall' subscription states for None, Trial Started, Active/Data received and Expired
    * Data classification and retention levels based on subscription type
    * Usage metering microservices for usage data collection and reporting to internal billing infrastructure services and AWS Marketplace infrastructure
