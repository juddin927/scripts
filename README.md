# scripts
Useful scripts list 
1. query_cloudwatch_log.py : This is a quick script written in python that can query various fields in AWS VPC flow logs extracted from Cloudwatch. Cloudwatch doesnt support advanced querying where you will have to check src_ip against a known IP list. This scripts will allow you to load existing list of IPs from a CSV and match that against the src_ip in VPC Flow logs.
