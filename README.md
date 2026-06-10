# AWS Security Track
### 1. Security Everywhere Culture Innovation andAI frontier
###### Compliance Framework Supported:
- NIST 800-53: Federal information systems security controls
- HIPAA: Healthcare data protection requirements.
- PCI-DSS: Payment Card Industry Data Security
- ISO 27001: International Security Management Standard
- SOC2 : Service organization controls
- GDPR: European data protection regulations

###### Best Practices and Tools:
- AWS Well-Architected Framework: Security Pillar
- Security Reference Architecture (SRA): Multi Account Guidance
- Landing Zone Accelerator (LZA):
- Amazon Bedrock Security Features: AI Security Built-In.

### 2. AWS Built-in Solutions
###### 1. Native AWS Services
- Enable AWS CloudTrial
- Enable AWS Security Hub
- Enable Amazon GuardDuty

###### 2. Partner Configuration:
- Add IAM role
- Enable Partner Integration
- Onboard AWS Account

### 3. AWS Security Incident Response
- AWS security incident response helps customers prepare for, respond to, and recover from security incidents faster and more effectively.


### 4. Secrets Management Strategy
```
aws credentials -> aws IAM
encryption keys -> aws KMS
ssh keys -> Amazon EC2 Instance connect
Private keys + Certificates -> AWS Certificate Manager

Database credentials, application credentials, OAuth tokens, API's -> AWS Secrets Manager
```
###### Secrets Management Architecture:
```
AWS Secret Manager -> lambda -> application or database
```
here, lambda is used for automating the rotation of secrets

#### Accessing and managing secrets
- AWS Management Console
- AWS CLI
- Secrets Manager API with libraries

AWS Secrets Manager New Feature: Automatic rotation for SaaS Secrets - no lambda fuctions needed

