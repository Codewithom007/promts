Generate Terraform code to provision infrastructure for the log pipeline:

Components:
- Kubernetes cluster (EKS or self-managed EC2)
- Kafka cluster (3 nodes)
- OpenSearch (small cluster)
- S3 bucket for reports
- SES for email

Constraints:
- Monthly cost must stay under $800
- Use smallest viable instance types
- Use autoscaling only where required

Output:
- Terraform files
- Cost estimation per component
