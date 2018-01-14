# Getting Started with Ruby on Rails

In order to get started as quickly as possible, we'll be using Cloud 9, a cloud-based IDE for this tutorial.

This allows us to skip the lengthy installation process, and allows us to focus on the problem at hand -- learning Ruby on Rails!

## Setting up Your Cloud9 Environment

Cloud9 requires an Amazon AWS account. The service is free, but you do need a valid credit card to sign up. Create your free account [here](https://portal.aws.amazon.com/billing/signup?redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation#/start).

### But I don't have a Credit Card!

If you don't have a credit card, or would rather not create an AWS account, you can simply run [this installer](https://rubyinstaller.org) if you're on Windows, or follow [these instructions](https://gorails.com/setup/osx/10.13-high-sierra) if you're on a Mac. I won't be going over installation during the workshop, so make sure you have a working Rails environment if you don't plan on using Cloud9.

### Configuring your Cloud9 Environment

1. Click on "Get started with AWS Cloud9"
2. Click on "Create Environment"
3. Specify a name and description for your environment
4. Select "Create a new instance for environment (EC2)", "t2.micro (1 GiB RAM + 1 vCPU)", and keep default settings for everything else
5. Click Next Step, then Create Environment
6. Wait a few minutes for the EC2 to boot...

Now that our Cloud9 environment is up and running, we need to make sure that we have all the software we need to write and run a Rails application

1. In the terminal window in the bottom left corner of your screen, type in `rails --version`. The prompt should show `Rails 5.1.4`, which means Rails is installed on the system. We're ready to start!
