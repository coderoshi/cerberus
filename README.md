# Cerberus

This is the base project for the Cerberus ecosystem. Please check out [engineering.nike.com/cerberus](http://engineering.nike.com/cerberus) for more information.

Cerberus is a system for safely storing and managing secrets, targeted to running cloud applications in AWS.

At Nike, we have a complex environment with many different applications, technology stacks, AWS accounts, and teams. Cerberus was developed in this environment to increase agility and decrease risk by securely managing secrets, like database passwords and API keys, as well as non-sensitive dynamic run-time properties, such as feature flags and logging levels.

## Overview

Here are the major [components, clients and utilities](http://engineering.nike.com/cerberus/components/) of Cerberus, focused on an [AWS infrastructure](http://engineering.nike.com/cerberus/docs/architecture/infrastructure-overview).

* Uses HashiCorp’s [Vault](http://engineering.nike.com/cerberus/docs/architecture/vault) to manage the actual encryption at rest and to provide access controls.
* Operationalized for AWS including a [CLI](http://engineering.nike.com/cerberus/docs/administration-guide/lifecycle-management-cli), Cloud Formation templates, edge security, and IAM integration.
* Includes a [Dashboard](http://engineering.nike.com/cerberus/docs/user-guide/dashboard), a self-service Web UI, where teams can manage properties and access control.
* Provides client libraries (e.g. Java, Node, Ruby) that can be used by Cloud applications (EC2 or Lambda) to retrieve properties at run-time.

## Read more

Interested? You can read more details about Cerberus at [engineering.nike.com/cerberus](http://engineering.nike.com/cerberus).
