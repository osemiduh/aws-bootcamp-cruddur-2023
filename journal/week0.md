# Week 0 — Billing and Architecture

## Required Homework

### Install AWS CLI

I have the AWS CLI already installed on my mac local machine.

I did the following steps to install AWS CLI via **Command Prompt**

I followed the instruction on the [AWS CLI Installation Documentation Page](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

```
curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
sudo installer -pkg AWSCLIV2.pkg -target /
```

I verified that the shell can find and run the aws command in $PATH, using the following commands

```
which aws
/usr/local/bin/aws

aws --version
aws-cli/2.1.25 Python/3.7.4 Darwin/22.2.0 exe/x86_64 prompt/off
```

![Proof of working AWS CLI](assets/Screenshot%202023-03-05%20at%2012.35.38%20PM.png)

## Homework Challenges
