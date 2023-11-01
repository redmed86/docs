# Cloud Intake Process

1. Talk to the customer, collect reqs
2. Cloud Director, Sr. Cloud Architect, Ops Lead
3. Fill out Terraform module & Submit PR
    1. Automation Team
4. Architecture Review (PR Review) 
    1. Terraform Account Module
        1. Root Email
        2. Account Admin Email
        3. VPC Segmentation 
        4. Private and Pub Subnets 
        5. Tags
        6. Number of accounts (Prod, Test,Dev)
    2. Verify Initial Docs are committed 
        1. Use Case Directory in Docs Repo
            1. Architecture diagram 
            2. Use Case description (short paragraph)
    3. AD Group Creation
        1. Global 
            1. Admins
            2. Billing
        2. Local
            1. Editor, Reader, Dev 
    4. Cost Estimation 
        1. Attach pricing calculator link
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
