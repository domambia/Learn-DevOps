# DevOps Fundamentals

## Introduction Microservice

### Microservice
> Applications are designed in a way that's modular easu to deploy, and scale independently.
> A lot of benefits of microservice design patterns applies for any application.
> Push the limits of  most automation tools and infranstruture  today to their limits.


### (12 Factors Apps)[https://12factor.net/]

This highlights the best-practises for building deployable software-as-a-service

	1. Portable
	2. Continually Deployable
	3. Scalable

A good microservices architecture must address all of this factor, with tools such as `kubernetes` and `docker`.

### Refactoring Monolith to MSA

- Refractor the app to `decoupling` to  small modules such as `auth`, and` products` use a `controller/management unit` usually referred to us as `container orchestrator`, such as 	`kubernetes` to manage them.


### JSON Web Token(JWT)

A compact, self-contained method of transfering/sharing secure data as a JSON object. Uses Case include;
	- Authentication
	- Information Exchange
Since JWT are signed, you can securely say to who does it belong and if they have been tampered with.


# Docker 

Build a container image, a packing format that includes not only your application but all the dependencies but also its runtime information required to run.

Docker makes its easy to `CREATE`, `DISTRIBUTE` and `RUN` container images in your own images.