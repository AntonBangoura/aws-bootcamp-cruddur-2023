# Week 0 — Billing and Architecture
https://lucid.app/lucidchart/c2c21ab2-d66c-4500-80c3-b13772196fa0/edit?beaconFlowId=3609F505894EC046&invitationId=inv_0da88bb1-1a2d-4122-8221-4171ec945856&page=0_0#
<br>
Homework Challenges - 0:
<br>
-Destroy your root account credentials, Set MFA, IAM role
<br>
-Set a billing alarm, Set a AWS Budget
<br>
-Use EventBridge to hookup Health Dashboard to SNS and send notification when there is a service health issue.
<br>
-Review all the questions of each pillars in the Well Architected Tool (No specialized lens)
<br>
-Create an architectural diagram (to the best of your ability) the CI/CD logical pipeline in Lucid Charts
<br>
-Research the technical and service limits of specific services and how they could impact the technical path for technical flexibility. 
-Open a support ticket and request a service limit
<br>
https://www.youtube.com/watch?v=OdUnNuKylHg
<br>
https://www.linuxtek.ca/2023/02/12/aws-cloud-project-bootcamp-week-0-unofficial-homework-guide/<br>

login: bootcamp
Bootcamp Outline => https://docs.google.com/document/d/19XMyd5zCk7S9QT2q1_Cg-wvbnBwOge7EgzgvtVCgcz0/edit
FAQ => https://docs.google.com/document/d/1VEs2i_tm1FxUatu1ZfUZH8EEVlhN9XWpVDvqg7GYeKM/edit 
aelshimy — 02/11/2023 8:11 PM
Cnatrill Catpipeline 
https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-codepipeline-catpipeline 
TOGAF Archticture Framework 
https://www.opengroup.org/togaf
Mitch — Yesterday at 4:34 PM
CloudSecurityPodcast => https://www.youtube.com/@CloudSecurityPodcast/videos
Docker => https://www.youtube.com/watch?v=pg19Z8LL06w
![image](https://user-images.githubusercontent.com/103506746/219612072-9fe1a9fe-70fd-4661-b5ab-3a43fb320b61.png)


# AWS Security and Optimization Tasks.

In order to ensure the security and optimization of our AWS environment, we have performed the following tasks:

- Destroyed our root account credentials: To ensure the highest level of security, we have deleted our root account credentials and have set up individual IAM users with specific permissions.

- Set up MFA and IAM roles: We have also set up multi-factor authentication (MFA) for all users, and have assigned specific IAM roles to each user to ensure that they only have access to the resources they need.

- Set up billing alarm and AWS budget: We have set up a billing alarm and an AWS budget to ensure that we are aware of any unexpected costs or usage spikes, and can take action to optimize our resources and costs.

- Used EventBridge to hookup Health Dashboard to SNS: We have set up an EventBridge rule to connect our AWS Health Dashboard to SNS, so that we receive notifications when there is a service health issue.

- Reviewed all questions of each pillar in the Well-Architected Tool: We have reviewed all the questions in each of the five pillars of the Well-Architected Tool, including Operational Excellence, Security, Reliability, Performance Efficiency, and Cost Optimization. This helps us ensure that our architecture meets best practices and is optimized for our use case.

- Created a CI/CD pipeline architectural diagram in Lucid Charts: We have created an architectural diagram of our CI/CD pipeline in Lucid Charts, to provide a clear visual representation of our pipeline and help us identify any areas for improvement.![Cruddur_Logical_Diagram](https://user-images.githubusercontent.com/93763783/219880180-08a03c93-9d70-446a-9e5b-a9d8b6247b70.png)

A napkin architecture was also done to give rough sketch of what we want to achieve.
[crudder_napkin_architecture.pdf](https://github.com/CloudOpsEU/aws-bootcamp-cruddur-2023/files/10774810/crudder_napkin_architecture.pdf)

- Researched technical and service limits of specific services: We have researched the technical and service limits of specific AWS services, such as EC2 and S3, to understand how they could impact our technical path for technical flexibility.

- Opened a support ticket and requested a service limit: We have opened a support ticket and requested a service limit increase for a specific AWS service, to ensure that we have enough resources to meet our needs.

By performing these tasks, we are confident that our AWS environment is secure, optimized, and well-architected to meet our needs.

