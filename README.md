# Lab M7.01 - Analyzing Costs with AWS Cost Explorer

## Project Overview
This lab involved navigating the AWS Cost Explorer interface, analyzing 14 active Free Tier services, and using the AWS CLI to verify usage data.

## Key Findings
- **Top Service:** AWS CloudShell (Usage confirmed via CLI)
- **Total Spend:** $0.00 (Usage remains within Free Tier limits)
- **Active Services:** 14 (CloudWatch, SNS, KMS, etc.)

## CLI Verification
Verified usage via:
`aws ce get-cost-and-usage --metrics "UsageQuantity" --group-by Type=DIMENSION,Key=SERVICE`
