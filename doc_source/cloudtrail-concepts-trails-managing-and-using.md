# Tips for Managing Trails<a name="cloudtrail-concepts-trails-managing-and-using"></a>
+ You can view all trails from any region in the CloudTrail console\. 
+ To edit a trail in the list, choose the trail name\. The console takes you to the region where the trail was created\.
+ Configure at least one trail that applies to all regions, so that you receive log files from all regions in your account\.
+ To log events from a specific region and deliver log files to an S3 bucket in the same region, you can update the trail to apply to a single region\. This is useful if you want to keep your log files separate\. For example, you may want users to manage their own logs in specific regions, or you may want to separate CloudWatch Logs alarms by region\.
+ To log events from multiple AWS accounts in one trail, consider creating an organization in AWS Organizations and then creating an organization trail\.
+ Creating multiple trails will incur additional costs\. For more information, see [AWS CloudTrail Pricing](https://aws.amazon.com/cloudtrail/pricing/)\. 

**Topics**
+ [CloudTrail Trail Naming Requirements](cloudtrail-trail-naming-requirements.md)
+ [Amazon S3 Bucket Naming Requirements](cloudtrail-s3-bucket-naming-requirements.md)
+ [Amazon S3 Bucket Policy for CloudTrail](create-s3-bucket-policy-for-cloudtrail.md)
+ [AWS KMS Alias Naming Requirements](KMS-key-naming-requirements.md)