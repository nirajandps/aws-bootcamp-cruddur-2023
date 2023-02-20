# Week 0 — Billing and Architecture

## Budgets and Billing Alarms:
- Used AWS Console to create the Budget
    - From AWS Billing>Budgets> Create Budget option created a budget for Zero Spend Budget. Also created another one for Usage via advanced option. Deleted both of these since you can only have 2 budgets under free tier. Created a new one to play around with the creation of multiple thresholds and alert options. Deleted the last one too.
    - Used Billing Preferences to set "receive billing alerts" but also went to manage billing alerts to configure further via cloudwatch
    - Used Gitpod to install AWS CLI. Created a gitpod config to run a task as soon as gitpod workspace is launched which then grabs the AWS secret key, access key and region (saved with gitpod's secured area). This tasks then would let us run AWS CLI without having to re-configure AWS keys again and again.
    - Using gitpod>terminal>AWS CLI, created a new branch called nirajan/awsbudget (https://github.com/nirajandps/aws-bootcamp-cruddur-2023/tree/nirajan/awsbudget). In this branch, created the JSON file used by the AWS CLI command to create budget and billing alarm. Merged the branch to Master. Used tag: week0
    - Ensured the basic AWS Budget and Billing alarm for threshold of $1 (80%) stayed in the console as that is important to receive notification for billing

- Created a napkin architecture design as a conceptual diagram for the micro-blogging app
<img src="./week0 uploads/Nirajan Napkin design.png">

- Created a Logical architecture design using Lucidchar
shared link: https://lucid.app/lucidchart/185ba8d4-b7fd-4d72-a63d-0ac6cd170810/edit?viewport_loc=-251%2C53%2C2333%2C1210%2C0_0&invitationId=inv_843aa60c-9748-45d4-8ed3-5f6c0d42cb4e

screenshot is available from journal>week0 uploads>Locidchart logical architecture

<img src="./week0 uploads/Locidchart logical architecture.png">