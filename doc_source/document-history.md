# Document History<a name="document-history"></a>
+ **API version**: 2015\-02\-01
+ **Latest documentation update**: November 26, 2018

The following table describes important changes to the *Amazon Elastic File System User Guide* after July 2018\. For notifications about documentation updates, you can subscribe to the RSS feed\.

| Change | Description | Date | 
| --- |--- |--- |
| [EFS File Sync is now part of the new AWS DataSync service\. ](#document-history) | AWS DataSync is a managed data transfer service that simplifies synchronizing large amounts of data between on\-premises storage systems and AWS storage services\. For more information, see LINK\_to\_AWSDataSync\_docs\. | November 26, 2018 | 
| [VPN and Inter\-region VPC Peering connection support added](#document-history) | Amazon EFS are now accessible over VPN connections and inter\-region VPC peering connections\. For more information, see [Mounting from Another Account or VPC](https://docs.aws.amazon.com/efs/latest/ug/manage-fs-access-vpc-peering.html) and [How Amazon EFS Works with Direct Connect and VPNs](https://docs.aws.amazon.com/efs/latest/ug/how-it-works.html#how-it-works-direct-connect)\. | October 23, 2018 | 
| [Additional AWS Region support added](#document-history) | Amazon EFS is now available to all users in the Asia Pacific \(Singapore\) AWS Region\. | July 13, 2018 | 
| [Introducing Provisioned Throughput mode](#document-history) | You can now provision throughput for new or existing file systems with the new Provisioned Throughput mode\. For more information, see [Throughput Modes](https://docs.aws.amazon.com/efs/latest/ug/throughput-modes.html)\. | July 12, 2018 | 
| [Additional AWS Region support added](#document-history) | Amazon EFS is now available to all users in the Asia Pacific \(Tokyo\) AWS Region\. | July 11, 2018 | 

The following table describes important changes to the *Amazon Elastic File System User Guide* before July 2018\.


| Change | Description | Date Changed | 
| --- | --- | --- | 
| Additional AWS Region support added | Amazon EFS is now available to all users in the Asia Pacific \(Seoul\) AWS Region\. | May 30, 2018 | 
| Added CloudWatch metric math support | Metric math enables you to query multiple CloudWatch metrics and use math expressions to create new time series based on these metrics\. For more information, see [Using Metric Math with Amazon EFS](monitoring-metric-math.md)\. | April 4, 2018 | 
| Added the amazon\-efs\-utils set of open\-source tools, and added encryption in transit | The amazon\-efs\-utils tools are a set of open\-source executable files that simplifies aspects of using Amazon EFS, like mounting\. There's no additional cost to use amazon\-efs\-utils, and you can download these tools from GitHub\. For more information, see [Using the amazon\-efs\-utils Tools](using-amazon-efs-utils.md)\. Also in this release, Amazon EFS now supports encryption in transit through Transport Layer Security \(TLS\) tunneling\. For more information, see [Encrypting Data and Metadata in EFS](encryption.md)\. | April 4, 2018 | 
| Updated file system limits per AWS Region | Amazon EFS has increased the limit on the number of file systems for all accounts in all AWS Regions\. For more information, see [Resource Limits](limits.md#limits-efs-resources-per-account-per-region)\. | March 15, 2018 | 
| Additional AWS Region support added | Amazon EFS is now available to all users in the US West \(N\. California\) AWS Region\. | March 14, 2018 | 
| Amazon EFS File Sync \(EFS File Sync\) | Amazon EFS now supports copying files from your on\-premises data center or from the cloud to Amazon EFS by using EFS File Sync\. EFS File Sync copies file systems accessed using Network File System \(NFS\) version 3 or NFS version 4 to Amazon EFS file systems\.  | November 22, 2017 | 
| Data encryption at rest | Amazon EFS now supports data encryption at rest\. For more information, see [Encrypting Data and Metadata in EFS](encryption.md)\. | August 14, 2017 | 
| Additional region support added | Amazon EFS is now available to all users in the EU \(Frankfurt\) region\. | July 20, 2017 | 
| File system names using Domain Name System \(DNS\) | Amazon EFS now supports DNS names for file systems\. A file system's DNS name automatically resolves to a mount target’s IP address in the Availability Zone for the connecting Amazon EC2 instance\. For more information, see [Mounting on Amazon EC2 with a DNS Name](mounting-fs-mount-cmd-dns-name.md)\. | December 20, 2016 | 
| Increased tag support for file systems | Amazon EFS now supports 50 tags per file system\. For more information on tags in Amazon EFS, see [Managing File System Tags](manage-fs-tags.md)\. | August 29, 2016 | 
|  General availability  |  Amazon EFS is now generally available to all users in the US East \(N\. Virginia\), US West \(Oregon\), and EU \(Ireland\) regions\.  |  June 28, 2016  | 
|  File system limit increase  |  The number of Amazon EFS file systems that can be created per account per region increased from 5 to 10\.  |  August 21, 2015  | 
|  Updated Getting Started exercise  |  The Getting Started exercise has been updated to simplify the getting started process\.  |  August 17, 2015  | 
|  New guide  |  This is the first release of the *Amazon Elastic File System User Guide*\.  |  May 26, 2015  | 