#  DevOps Tech Task
**Thanks for your interest in annalise.ai 😀**

This exercise has been designed to demonstrate your skills and experience, and to provide talking points for your Round 2 interview. We've provided some information below to help you to complete the task.


##  Part One

###  Instructions

Using an orchestration tool of your choice (eg. Terraform, AWS Cloudformation, Azure Resource Manager etc), create a template that defines an application stack in the Sydney region of a public cloud provider. (eg. ap-southeast-2 for AWS, Australia East for Azure)

This test does not require you to show us a running application stack; we will deploy your template(s).  

**The stack should meet the following criteria:**
- Apply best practices in solution architecture and security.
- Use an official, public, Debian, Ubuntu or Amazon Linux image for any VM or EC2 resources.
- Serve a basic "Hello, World" webpage.
- Scale capacity to meed demand.
- Manage unhealthy instances.  

You may chose to include all components from the network (ie. AWS VPC or Azure VNet) up, in the stack. However, given the amount of effort involved, you can also exclude the network, subnets, and associated networking components from your stack and configure them as input variables to be provided by ourselves upon deployment.  You can assume the following about the environment into which your stack will be deployed:

- A VPC or VNet with public and private subnets in up to 3 x Availability Zones.
- Internet Gateway and Nat Gateway present to allow outbound internet connectivity to TCP/80 and TCP/443 from all subnets in the network.

  ### Notes:
  - There are a number of published boilerplate templates.  It's OK to use them as a starting point, provided you modify them enough to demonstrate your own skills.
  - Your application stack may or may not be containerised.
  - Use Git version control and commit your solution to a Git repository that we can access. (Github, Bitbucket or Gitlab are the obvious choices)
  - Please include a README, citing any third-party code, tutorials or documentation you have used.
  - If your solution includes any unusual deployment steps, please note them in your README file
  - If you have chosen to exclude the networking components from your solution and provide them as input variables, please note the requirements in the README.- Serving your "Hello, World" page over HTTPS is an added bonus, but not necessary for the purposes of this exercise.

## Part Two
**Please describe how you would implement the following requirements:**
- How would you provide shell access into the application stack for operations staff who may want to log into an instance.
- Make access and error logs available in a monitoring service such as AWS CloudWatch or Azure Monitor.

## Useful Links
- Read about annalise.ai's recent feature in IT News here: https://www.itnonline.com/content/study-reveals-new-comprehensive-ai-chest-x-ray-solution-improves-radiologist-accuracy, based on our recent publication in The Lancet: https://www.thelancet.com/journals/landig/article/PIIS2589-7500(21)00106-0/fulltext
- Check out our first product to market! View our CXR Demo here.
- You can also listen to our Wild Hearts podcast - Helping a Million Lives a Day at harrison.ai with Dr. Aengus Tran and Samantha Wong!
- Read about our parent company Harrison.ai via our media releases announcing our $129m Series B in 2021 and $29m Series A in 2019.

## Questions?
If there are any questions or doubtful points please feel free to reach out to your Recruitment Partner.