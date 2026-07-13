# CloudCompliance Remediation

**Resource:** cloudcompliance-encrypted-data
**Severity:** HIGH
**Detected:** 2026-07-13 15:50:25

## Issue
S3 bucket 'cloudcompliance-encrypted-data' exists in Terraform state but not in AWS

## Fix
```bash
Run 'terraform apply' to recreate or 'terraform state rm aws_s3_bucket.encrypted_data' to remove from state
```
