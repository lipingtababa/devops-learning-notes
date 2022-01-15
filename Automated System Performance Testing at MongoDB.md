# Metadata
Title: Automated System Performance Testing at MongoDB
Author: Henrik Ingo & David Daly  
Organization: MongoDB  
Stars: 4 stars

# What is it?
A framework for running fully automated system performance tests in CI environment

# What is special?
1. It is a framework that not just run the client, but also provision infra and set up the distributed DB.
2. It runs on a public cloud and uses terraform.

# What is interesting
* It used to re-use EC2 hosts between tests to save cost because AWS charged per hour.
  Then it stopped reusing EC2 instances because AWS charged per minute.
* It doesn't utilize a logging system nor a monitor system, but rather develop them themselves.
