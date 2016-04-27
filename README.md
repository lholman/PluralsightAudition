# PluralsightAudition

## 'Building quality in to infrastructure automation' - Using PowerShell and the Pester test framework

## Module heading ideas

* What is quality code and why does it matter?
* Using version control with PowerShell
	* Introducing the demo project
	* Adding the demo project to Github
	* What not to add to version control
* Unit testing infrastructure code with Pester for PowerShell
	* Installing Pester
	* Writing a failing test
	* Making the test pass
	* Writing testable PowerShell code using Test Driven Development (TDD)
* Managing dependencies in PowerShell
	* What is a dependency?
	* PowerShell Modules and Cmdlets
	* Other .NET assemblies
* Using Test Doubles in Pester 
	* The System Under Test (SUT) principal
	* Mocking PowerShell functions
	* Verifying behaviour in tests
	* The Pester TestDrive
	* Mocking target systems	
* Stubbing
	* Stubbing the Windows File system

* Handling warnings, errors and exceptions
	* Negative testing
* Sharing your PowerShell infrastructure code
	* Versioning 
	* Packaging
	* Documentation

## References
http://martinfowler.com/articles/mocksArentStubs.html
	
## Introduction
30 seconds to tease about what I'll be teaching

In this module you will learn how to build quality automation scripts and code in Powershell. You become familiar the Pester test Framwework for PowerShell and understand how to version and package infrastructure code.

## Audition module ''

### The problem
All too frequently I have observed that automation code and "processes" are a combination of very complex, unversioned locally saved code and dependencies. Delving deeper these important scripts are often rats nests of 100's or even 1000's of lines of logic, they're brittle, one change can break them or even worse give a non-deterministic output. Rarely do they implement consistent patterns for error handling, retry, auditing or security and idempotency is often not understood.

### Journey
Be sure to define and demostrate the problem, journey and solution

### Solution

## Conclusion