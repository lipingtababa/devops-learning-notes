# Metadata
Author: James Burns, Lightstep Head of Research
Title: The complete guide to observability
Organizaiton: Lightstep
Stars: 3 stars

# Operational Problems Unique to Distributed Systems
1. dependencies are complex.
2. debugger and stack traces stop working.
3. Expectation of avalability are higher.

# Definition
Observability is a measure of how well you can infer the
internal state of a system using only its outputs.

# Three pillars
## Logs
Structured or unstructured lines of text that are emitted by an
application in response to some event in the code.
They are typically easy to generate, difficult to extract
meaning from, and expensive to store.
## Metrics
A metric is a value that expresses some data about a system.
## Traces
A single trace shows the activity for an individual transaction or
request as it flows through an application.
Traces can help define which metrics would be most valuable in a given
situation, or which logs are relevant to a particular issue.

# Benefit of Observability
1. For teams of all sizes, observability offers a shared view of the
system.
2. observability enables better workflows for debugging, performance optimization, and fire fighting.
3. Ruling out signals that are unlikely to have contributed to the root cause, developers can form and investigate more effective hypotheses.
4. Observability reduces the amount of stress when deploying code or
making changes to the system.
5. Observability drives more effective post-mortems.

# Requirements for observability solutions
1. Observability tools must be simple to integrate.
2. Observability tools must be easy to use.
3. Observability tools must be built on high-quality telemetry.
4. Observability tools must be real-time.
5. Observability tools must aggregate and visualize your data.
6. Observability tools must provide irrefutable context.
7. Observability tools must scale.
8. Observability tools must provide ROI to the business.
