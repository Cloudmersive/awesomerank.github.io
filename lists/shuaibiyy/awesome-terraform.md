---
layout: default
title: Awesome Rank for shuaibiyy/awesome-terraform
---

<p align="center">
	This list is a copy of <a href="https://github.com/shuaibiyy/awesome-terraform">shuaibiyy/awesome-terraform</a> with ranks
</p>
---
# Awesome Terraform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★73813](https://github.com/sindresorhus/awesome)

> A curated list of resources on [HashiCorp's Terraform](https://www.terraform.io/).
[<img src="https://rawgit.com/shuaibiyy/awesome-terraform/master/terraform.svg" align="right" width="100">](https://terraform.io)
Your [contributions](https://github.com/shuaibiyy/awesome-terraform/blob/master/contributing.md) are welcome!

Terraform enables you to safely and predictably create, change, and improve production infrastructure. It is an open source tool that codifies APIs into declarative configuration files that can be shared amongst team members, treated as code, edited, reviewed, and versioned.

## Contents

* [Official Resources](#official-resources)
* [Community](#community)
* [Books](#books)
* [Tutorials and Blog Posts](#tutorials-and-blog-posts)
* [Community Modules](#community-modules)
* [Tools](#tools)
* [Talks](#talks)
* [Editor Plugins](#editor-plugins)

## Official Resources

* [Introduction to Terraform](https://www.terraform.io/intro/)
* [Terraform Documentation](https://www.terraform.io/docs/)

## Community

* [Terraform Google Group](https://groups.google.com/forum/#!forum/terraform-tool)
* [Terraform Gitter](https://gitter.im/hashicorp-terraform)
* [Terraform Bug Tracker](https://github.com/hashicorp/terraform/issues)
* [Terraform Community Modules](https://github.com/terraform-community-modules)
* [Terraform Module Registry](https://registry.terraform.io/)

## Books

* [Terraform: Up & Running](http://www.terraformupandrunning.com/?ref=gruntwork-blog-comprehensive-terraform)
* [The Terraform Book](https://terraformbook.com/)
* [Getting Started with Terraform](https://www.amazon.com/Getting-Started-Terraform-Kirill-Shirinkin/dp/1786465108/)
* [Infrastructure as Code](http://shop.oreilly.com/product/0636920039297.do)

## Tutorials and Blog Posts

* [A Comprehensive Guide to Terraform](https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca#.w9x897ywp) - Series of blog posts from the author of "Terraform: Up & Running" that guide the reader from beginning with Terraform to using it in the real world.
* [Easily Deploy A Seneca Microservice to ECS with Wercker and Terraform: Part I](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/), [II](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-ii/) & [III](http://chiefy.github.io/easily-deploy-a-seneca-microservice-to-ecs-with-wercker-and-terraform-part-i/) - Illustrates how Terraform can be incorporated into a microservice deployment pipeline.
* [Tutorial: How to Use Terraform to Deploy OpenStack Workloads](http://www.stratoscale.com/blog/openstack/tutorial-how-to-use-terraform-to-deploy-openstack-workloads/) - Illustrates how easy it is to use the OpenStack Terraform provider to deploy a web server.
* [The Segment AWS Stack](https://segment.com/blog/the-segment-aws-stack/) - Shows the behind the scenes of the infrastructure powered by Terraform that solved [The Million Dollar Engineering Problem](https://segment.com/blog/the-million-dollar-eng-problem/) at [Segment](https://segment.com/).
* [Terraform: Beyond the Basics with AWS](https://aws.amazon.com/blogs/apn/terraform-beyond-the-basics-with-aws/) - Explanation of a demo using Terraform to provision a sample AWS architecture.
* [Deploying Discourse with Terraform](https://www.hashicorp.com/blog/terraform-discourse.html) - Shows how Terraform can create a running instance of Discourse on DigitalOcean in one command.
* [Bootstrapping Docker Infrastructure With Terraform](http://vilkeliskis.com/blog/2016/02/10/bootstrapping-docker-with-terraform.html) - Walkthrough of deploying a dockerized app on ECS using Terraform.
* [Two Weeks with Terraform](https://charity.wtf/2016/02/23/two-weeks-with-terraform/) - Some hard-earned experience from using Terraform in the wild, and some operational wisdom.
* [Using Terraform for Cloud Deployments - Part 1](https://dev.to/koenighotze/using-terraform-for-cloud-deployments---part-1) - Beginner tutorial with a focus on using Terraform to provision an EC2 instance.
* [Terraform, VPC, and why you want a tfstate file per env](https://charity.wtf/2016/03/30/terraform-vpc-and-why-you-want-a-tfstate-file-per-env/) - Some gotchas surrounding using Terraform in large projects with multiple environments and how to avoid them.
* [Sharing data between Terraform configurations](https://jamesmckay.net/2016/09/sharing-data-between-terraform-configurations/) - Illustrates how to use remote state to share data between Terraform configurations.
* [Using Pipelines to Manage Environments with Infrastructure as Code](https://medium.com/@kief/https-medium-com-kief-using-pipelines-to-manage-environments-with-infrastructure-as-code-b37285a1cbf5) - Explains different approaches for building a pipeline to handle infrastructure changes moving from one environment to the next.

## Community Modules

For more Community Modules not listed here please see the [Terraform Module Registry](https://registry.terraform.io/).

* [segmentio/stack ★1447](https://github.com/segmentio/stack) - Configures production infrastructure with AWS, Docker, and ECS.
* [terraform-ecs-jenkins ★54](https://github.com/shuaibiyy/terraform-ecs-jenkins) - Provisions Jenkins on AWS ECS using Terraform.
* [tf_aws_bastion_s3_keys ★68](https://github.com/terraform-community-modules/tf_aws_bastion_s3_keys) - Creates bastion hosts on AWS EC2.
* [terraform-static-website-s3-cloudfront ★29 ⏳1Y](https://github.com/sjevs/terraform-static-website-s3-cloudfront) - Creates static websites on AWS S3 & Cloudfront based on variables.
* [tf_aws_vpc_only ★4](https://github.com/terraform-community-modules/tf_aws_vpc_only) - Provides only VPC (without subnets) in AWS.
* [tf_aws_asg_elb ★24](https://github.com/terraform-community-modules/tf_aws_asg_elb) - Creates Auto-Scaling Groups and Launch Configurations for use with an Elastic Load Balancer.
* [tf_aws_availability_zones_cfn ★4 ⏳1Y](https://github.com/terraform-community-modules/tf_aws_availability_zones_cfn) - Gets availability zones for your AWS region/account from Cloudformation.
* [tf_aws_ubuntu_ami ★54](https://github.com/terraform-community-modules/tf_aws_ubuntu_ami) - Easy way to lookup Ubuntu AMIs with Terraform.
* [tf_aws_sg ★64](https://github.com/terraform-community-modules/tf_aws_sg) - Collection of common security group settings.
* [tf_aws_coreos_ami ★14 ⏳1Y](https://github.com/terraform-community-modules/tf_aws_coreos_ami) - Easy way to lookup CoreOS AMIs with terraform.
* [tf_aws_private_subnet_nat_gateway ★7](https://github.com/terraform-community-modules/tf_aws_private_subnet_nat_gateway) - Creates private subnets with NAT Gateway in AWS.
* [tf_aws_rds ★18](https://github.com/terraform-aws-modules/terraform-aws-rds) - Creates RDS resources on AWS.
* [terraform-aws-postgresql-rds ★23](https://github.com/azavea/terraform-aws-postgresql-rds) - Creates PostgreSQL on RDS.
* [tf_aws_vpc ★206](https://github.com/terraform-community-modules/tf_aws_vpc) - Provides VPCs in AWS.
* [tf_aws_nat ★17](https://github.com/terraform-community-modules/tf_aws_nat) - NAT instances for AWS.
* [rancher-terraform-digitalocean ★12](https://github.com/lunagt/rancher-terraform-digitalocean) - Rancher server on digitalocean.

## Tools

* [Atlantis ★522](https://github.com/hootsuite/atlantis) - Unified workflow for collaborating on Terraform through GitHub.
* [terraform-docs ★306](https://github.com/segmentio/terraform-docs) - Quick utility to generate docs from terraform modules.
* [terraform.py](https://github.com/ciscocloud/terraform.py) - Ansible dynamic inventory script for parsing Terraform state files.
* [terraform-provisioner ★9](https://github.com/shuaibiyy/terraform-provisioner) - Tool for managing multiple provisions of the same Terraform scripts.
* [terraboot ★19](https://github.com/MastodonC/terraboot) - DSL to generate a terraform configuration and run it.
* [terraform-provider-pingdom ★21](https://github.com/russellcardullo/terraform-provider-pingdom) - Terraform provider to manage pingdom resources.
* [terragrunt ★947](https://github.com/gruntwork-io/terragrunt) - Terragrunt is a thin wrapper for Terraform that supports locking for Terraform state and enforces best practices.
* [tfenv ★199](https://github.com/kamatama41/tfenv) - Terraform version manager inspired by rbenv.
* [terraform-landscape ★131](https://github.com/coinbase/terraform-landscape) - Improve Terraform's plan output to be easier to read and understand.
* [Blast Radius ★29](https://github.com/28mm/blast-radius) - Interactive visualizations of Terraform dependency graphs.


## Talks

* [Orchestrating Containers with Terraform and Consul](https://www.infoq.com/presentations/terraform-consul) - Mitchell Hashimoto shows how Terraform can be used to deploy and scale containerized workloads.
* [Building Scalable, Repeatable Infrastructure in the Cloud with Terraform](https://www.youtube.com/watch?v=cG7pcksTAnY) - Demonstrates how Terraform enables the practice of Infrastructure as Code by deploying TeamCity in AWS using a hosted PostgreSQL.
* [Evolving Your Infrastructure with Terraform](https://www.youtube.com/watch?v=wgzgVm7Sqlk) - CTO of OpenCredo provides an extensive look at using Terraform in the real-world with the help of some interesting use-cases.
* [Going Multi-Cloud with Terraform and Nomad](https://www.youtube.com/watch?v=e42A4aBZUkQ)
* [Running a Terraform Environment at Scale](https://www.youtube.com/watch?v=3JVGSq7QIS0) - Running Terraform at scale with hundreds of AWS accounts.
* [Terraforming the Composable World](https://www.youtube.com/watch?v=cHrOXPatFeg) - Integrating Terraform with an on-premise bare metal provisioning.
* [State of Terraform Providerland](https://www.youtube.com/watch?v=ar1PF5iDtbg) - How Terraform providers work and how to write one.
* [Untangling Terraform Through Refactoring](https://www.youtube.com/watch?v=OH6iDKaXpZs) - How to refactor your Terraform code in a careful way with minimum risk.
* [Terraform At Scale](https://www.youtube.com/watch?v=RldRDryLiXs) - How Segment uses Terraform.
* [Production ChaosMonkey with Terraform](https://www.youtube.com/watch?v=CPI6W3LK0-g) - How DigitalOcean uses Terraform to run production integration tests.
* [Terraform w/ Lee Trout](https://www.youtube.com/watch?v=p2ESyuqPw1A) - Focuses on development patterns and how to effectively structure Terraform code.
* [Webinar: Multi-Cloud, One Command with Terraform](https://www.youtube.com/watch?v=adzqsywrJKk) - Provisioning hybrid cloud infrastructure using Terraform.

## Editor Plugins

* [Vim-Terraform ★184](https://github.com/hashivim/vim-terraform)
* [Vim-Terraform-Completion ★54](https://github.com/juliosueiras/vim-terraform-completion)
* [Intellij](https://plugins.jetbrains.com/plugin/7808-hashicorp-terraform--hcl-language-support)
* [Emacs terraform-mode ★59](https://github.com/syohex/emacs-terraform-mode)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Shuaib Yunus has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/shuaibiyy/awesome-terraform">shuaibiyy/awesome-terraform</a> with ranks
</p>