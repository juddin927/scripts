# scripts
Useful scripts list 
 **query_cloudwatch_log.py** : This is a quick script written in python that can query various fields in AWS VPC flow logs extracted from Cloudwatch. Cloudwatch doesnt support advanced querying where you will have to check src_ip against a known IP list. This scripts will allow you to load existing list of IPs from a CSV and match that against the src_ip in VPC Flow logs.
## Example usage of query_cloudwatch_log.py

1. Create an extract request to S3 using CloudWatch console.
2. Download the logs from S3 using AWS CLI.
3. Run the script on the log dir.
4. Provide path for log dir.
5. Provide allowed IP list path using file (CSV) path.

