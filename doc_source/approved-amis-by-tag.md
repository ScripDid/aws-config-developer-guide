# approved\-amis\-by\-tag<a name="approved-amis-by-tag"></a>

Checks if running instances are tagged with specified keys or key-value pairs\. Specify a list of approved keys or key-value pairs\. Running instances with AMIs that are not tagged as excepted are NON\_COMPLIANT\.

**Identifier:** APPROVED\_AMIS\_BY\_TAG

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions

**Parameters:**

amisByTagKeyAndValueType: StringMapDefault: tag\-key:tag\-value,other\-tag\-key  
The AMIs by tag \(comma\-separated list up to 10; for example,`tag-key:tag-value`; i\.e\. `tag-key1` matches AMIs with `tag-key1`,`tag-key2:value2` matches `tag-key2` having value2\)\.

## AWS CloudFormation template<a name="w29aac11c33c17b7c27c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.
