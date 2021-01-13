## Outbound VPC proxy

Outbound VPC proxy with domain whitelisting and content filtering customized for Cloudera Data Platform running in AWS.

- Customizes Squid config to allow outbound CCM connection
- CloudFormation Template creates AWS VPC endpoints for

-- AWS STS
-- AWS S3
-- AWS DynamoDB
-- AWS ECR
-- AWS EC2
-- AWS Cloudformation
-- AWS Autoscaling
-- AWS EFS
-- AWS DynamoDB
-- AWS ELB





Ref [Squid Return Codes}(https://wiki.squid-cache.org/SquidFaq/SquidLogs#Squid_result_codes)

For more information see AWS Security Blog [How to set up an outbound VPC proxy with domain whitelisting and content filtering](https://aws.amazon.com/blogs/security/how-to-set-up-an-outbound-vpc-proxy-with-domain-whitelisting-and-content-filtering)

## License Summary

This sample code is made available under the MIT-0 license. See the LICENSE file.
