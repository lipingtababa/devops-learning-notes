# Metadata
Author: Chris Engelbert  
Title: Observability for Developers  
Organizaiton: Instana, IBM  
Stars: 2 stars  

# Problems we have with observability implementation
## time consuming to implement observability in application code
we cluttered our code with probably more ceremony for monitoring and tracing than actual business logic.

## No integration among 3 pillars
With 3 independent systems that do not share any data or data correlations, making sense of the different data sources is complicated and time consuming.

## Maintaining observability tools are expensive
It is time-consuming to
1. To maintain the open source instances.
2. To adjust OSS Observability solutions.
3. To implement OSS Observability into the source base.

Keeping those integrations in line with our previously set goals can easily add up to 5-10% of the development time.