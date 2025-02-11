# ND9991 - Course 2 - Infrastructure as Code

This repository contains the starter code for the final project of course 2 Infrastructure as Code in the Cloud DevOps Engineer Nanodegree.

Please note that all supporting material for this course can be found in [this Github repository](https://github.com/udacity/cd12352-Deploy-Infrastructure-as-Code).

# Deploy a high-availability web app using CloudFormation

In this project, you’ll deploy web servers for a highly available web app using CloudFormation. You will write the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. You will begin with deploying the networking components, followed by servers, security roles and software.  The procedure you follow here will become part of your portfolio of cloud projects. You’ll do it exactly as it’s done on the job - following best practices and scripting as much as possible. 

## Getting Started

### Dependencies

1. AWS CLI installed and configured in your workspace using an AWS IAM role with Administrator permissions (as reviewed in the course).

2. Access to a diagram creator software of your choice.

3. Your favorite IDE or text editor ready to work.

### Installation

You can get started by cloning this repo in your local workspace:

```
git clone git@github.com:udacity/-cd12352-Deploy-Infrastructure-as-Code-project.git
```

## Testing

No tests required for this project.

## Project Instructions

1. Design your solution diagram using a tool of your choice and export it into an image file.

2. Add all the CloudFormation networking resources and parameters to the `network.yml` and `network-parameters.json` files inside the `starter` folder of this repo.

3. Add all the CloudFormation application resources and parameters to the `udagram.yml` and `udagram-parameters.json` files inside the `starter` folder of this repo.

4. Create any required script files to automate spin up and tear down of the CloudFormation stacks.

5. Update the README.md file in the `starter` folder with creation and deletion instructions, as well as any useful information regarding your solution.
   
6.  Submit your solution as a GitHub link or a zipped file containing the diagram image, CloudFormation yml and json files, automation scripts and README file.

7.  LoadBalancer URL: http://my-ser-webap-nw4wykxhldpx-2001017318.us-east-1.elb.amazonaws.com/

8.  Comments: 
• In this post, you will read about 11 reasons for using AWS CloudFormation and automating the provisioning of your infrastructure.
• You did great work by using the LaunchTemplate. Defining a launch template instead of a launch configuration allows you to have multiple versions of a template. With versioning, you can create a subset of the full set of parameters and then reuse it to create other templates or template versions. For example, you can create a default template that defines common configuration parameters and allow the other parameters to be specified as part of another version of the same template.
• Elastic Load Balancing Health Checks (for Application Load Balancers)
• Elastic Load Balancing Health Checks (for Network Load Balancers)
• Elastic Load Balancing Health Checks (for Classic Load Balancers)
• Auto Scaling best practices
use cross-stack references to export resources from a stack so that other stacks can use them. For more information, see Walkthrough: Refer to resource outputs in another AWS CloudFormation stack

## License

[License](LICENSE.txt)
