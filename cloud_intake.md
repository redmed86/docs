# Cloud Intake 

Athletics - Media Storage

1. Talk to the customer, collect reqs
2. Brad, Dave R. , Ops Lead (Vacant), “Use Case Review”
    1. CoE Dir, Sr Arch, Ops Lead 
3. Fill out Terraform module & Submit PR
    1. Automation Team
    2. who fills out the initial account module and submits PR? Cloud Architect?
4. Architecture Review (PR Review) 
    1. Terraform Account Module
        1. Root Email
        2. Account Admin Email
        3. VPC Segmentation 
        4. Private and Pub Subnets 
        5. Tags
        6. # of accounts (Prod, Test,Dev)
    2. Verify Initial Docs are committed 
        1. Use Case Directory in Docs Repo
            1. Architecture diagram 
            2. Use Case description (short paragraph)
    3. Entra ID group creation 
        1. Global 
            1. Admins
            2. Billing
        2. Editor, Reader, Dev 
    4. Cost Estimation 
        1. attach pricing calculator link (AWS)
    5. Reviewers (1 from each)
        1. Sec Group
        2. Arch Group
        3. Network Group
5. PR Approved & Merged
    1. Pipelines run
        1. Account Request pipeline
        2. Account customization pipeline 
        3. global customizations 
6. Cloud Deployment Starts 
    1. Dev deployed
    2. Test deployed
    3. Prod deployed
7. Final Workload Review 
    1. Ops Lead and the customer 
8. Go Live 


Tools to become SME

* Terraform
* GH
* GH Actions 
* Ansible 

Nice to have

* Sonar Qube
* Security Scanner 

Images for Licensing - Redhat, Ubuntu and Windows latest - 1 
