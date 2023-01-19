

1) Create an EC2
   - all ami's support ssm agen installation
   - Some come with pre-installed ssm
        - Amazon Linux Base AMIs dated 2017.09 and later 
        - Amazon Linux 2 
        - Amazon Linux 2 ECS-Optimized Base AMIs 
        - Amazon EKS-Optimized Amazon Linux AMIs 
        - macOS 10.14.x (Mojave), 10.15.x (Catalina), and 11.x (Big Sur)
        - SUSE Linux Enterprise Server (SLES) 12 and 15 
        - Ubuntu Server 16.04, 18.04, and 20.04 
        - Windows Server 2008-2012 R2 AMIs published in November 2016 or later 
        - Windows Server 2016, 2019, and 2022
        - (https://docs.aws.amazon.com/systems-manager/latest/userguide/ami-preinstalled-agent.html)
2) Check ssm is installed Install SSM
3) Add IAM role and policy
4) Login to ec2 console and verify ssm connection