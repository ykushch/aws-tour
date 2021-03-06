<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/ykushch/aws-tour/master/resources/aws.png">
</p>
<br/>

# AWS Tour
### Work in Progress
Short guide to so many cool services from AWS

## Networking & Content Delivery
### VPC
**Description:** Virtual Private Cloud. Basically, virtual data center. It is like
a small network in the larger network.<br>
**Similar to:** .

### Route53
**Description:** DNS service. Ables you to buy a domain and setup the DNS records for it.
The reason why it has 53 in name is that you open DSN on port 53.<br>
**Similar to:** Gandi, GoDaddy.

### Cloud Front
**Description:** Amazon CDN. Part of the CDN (Content Delivery Network).
Makes your websites faster by caching videos, media files, etc. closer to your users.<br>
**Similar to:** Akamai.

### Direct Connect
**Description:** A way of connecting office, physical data centers directly to AWS using
dedicated line. Used when needs to pass a lot of data into AWS.<br>
**Similar to:** ?.

### Route53
**Description:** DNS service. Ables you to buy a domain and setup the DNS records for it<br>
**Similar to:** Gandi, GoDaddy.

## Compute
### EC2
**Description:** Virtual services (machines) in the cloud. Used for application hosting.<br>
**Similar to:** DigitalOcean, Linode.

### EC2 Container Service
**Description:** Docker as a Service. Highly scalable container management service. Supports docker containers.
Eliminates the need to install own cluster management infrastructure.<br>
**Similar to:** Docker cloud.

### Elastic Beanstalk
**Description:** Platform as a Service. Deploy your code into AWS. For example, move app
from Heroku to AWS.<br>
**Similar to:** Heroku.

### Lambda
**Description:** Small scripts. One of the components of the serverless architecture.
Upload small code snippet and it to do series of simple tasks,
it will respond on the events in S3, DynamoDB.<br>
**Similar to:** ?.

### Lightsail
**Description:** Out of the box cloud. It could deploy Wordpress, Joomla site for you.<br>
**Similar to:** ?.

## Storage
### S3
**Description:** Simple Storage Service. Scalable storage in the cloud. Can store backups, images, share files between services. Could be
used for serving static websites. Cannot be used as a database. Object based storage.<br>
**Similar to:** *Unlimited* FTP server.

### Glacier
**Description:** Archive files from S3. Used for long-term archiving.<br>
**Similar to:** ?

### EFS
**Description:** Elastic File Service. Block based storage, place where you could install databases, apps and share volume with multiple
machines<br>
**Similar to:** ?

### Storage Gateway
**Description:** Automates getting files into S3 from your corporate network.<br>
**Similar to:** ?

## Database
### RDS
**Description:** Relational Database Service. Consists of different SQL technologies: MySQL, PostgreSQL, MariaDB, SQL Server, 
Oracle, Aurora.<br>
**Similar to:** Heroku Postgres.

### DynamoDB
**Description:** NoSQL database. High-performant and scalable database<br>
**Similar to:** Heroku Postgres.

### Redshift
**Description:** Data Warehouse solution. Store analytics data for processing. Copy data from production DB to Redshift for analytics.<br>
**Similar to:** ?

### Elasticache
**Description:** Amazon's Redis. Caches data in the cloud. Could be used to show the frequently needed data.<br>
**Similar to:** Redis.

## Migration
### Snowball
**Description:** Send a disk or bunch of disks to AWS. You could move Terrabytes of Data into AWS.<br>
**Similar to:** ?

### DMS
**Description:** Database Migration Services. Migrate database to AWS cloud or to other regions. You could migrate from local database to Aurora,
here comes DMS.<br>
**Similar to:** ?

### Server Migration Service (SMS)
**Description:** Almost the same as DMS except that it targets to the Virtual Machines instead of databases.<br>
**Similar to:** ?

## Analytics
### Athena
**Description:** Run SQL queries on S3.<br>
**Similar to:** ?

### EMR
**Description:** Elastic MapReduce. Used for BigData processing. For example, for log analysis.<br>
**Similar to:** ?

### Cloud Search 
**Description:** Fully managed service provided by AWS. Allows to create search capabilites<br>
**Similar to:** ?

### Elastic Search
**Description:** Similar to Cloud Search.<br>
**Similar to:** ?

### Kinesis
**Description:** A way of streaming and analyzing large amounts of data.<br>
**Similar to:** Kafka.

### Data Pipeline
**Description:** Ability to move data. Extract, Transform and Load data from elsewhere in AWS. Schedule when it happens and get alerts when they fail.<br>
**Similar to:** ?

### Quick Sight
**Description:** Business Analytics tool. Used to create visualization and rich dashboards.<br>
**Similar to:** ?

## Security, Identity & Compliance
### IAM
**Description:** Ables to setup users, create, new AWS Keys and policies.<br>
**Similar to:** ?

### Inspector
**Description:** Agent that inspects your Virtual Machines for vulnarabilities.<br>
**Similar to:** ?

### Certificate Manager
**Description:** Gives free SSL certificates.<br>
**Similar to:** ?

### Directory Service
**Description:** Use Active Directory for Microsoft.<br>
**Similar to:** ?

### WAF
**Description:** Web Application Firewall. Firewall from Amazon. Blocks bad requests to Cloudfront protected sites.<br>
**Similar to:** Sophos.





## Messaging
## Application Services
## Developer Tools
## Management Tools
## Internet of Things
## Game Development
## Mobile Services
## Business Productivity
## Artificial Intelligence
## Desktop & App Streaming


