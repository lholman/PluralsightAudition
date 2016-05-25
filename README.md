# PluralsightAudition

## 'Building quality in to infrastructure automation' - Using PowerShell and the Pester test framework

## Module heading ideas

* What is quality code and why does it matter?
* Using version control with PowerShell
	* Introducing the demo project
	* Adding the demo project to Github
	* What not to add to version control
* Unit testing infrastructure code with Pester for PowerShell
	* Installing/Finding Pester
	* Writing a failing test
	* Making the test pass
	* Writing testable PowerShell code using Test Driven Development (TDD)
* PowerShell coding styles/options: See http://mikefrobbins.com/2016/01/14/powershell-script-module-design-placing-functions-directly-in-the-psm1-file-versus-dot-sourcing-separate-ps1-files/
	* Script modules 
	* Dot sourcing PS1 files
* Sharing PowerShell infrastructure code
	* Versioning 
	* Packaging
	* Documentation
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


## References
http://martinfowler.com/articles/mocksArentStubs.html
	
## Introduction
30 seconds to tease about what I'll be teaching

In this module you will learn how to build quality automation scripts and code in Powershell. You will become familiar with the Pester test Framwework for PowerShell and understand how to version and package infrastructure code.

## Audition module 'Sharing PowerShell infrastructure code'
* Sharing PowerShell infrastructure code
	* Overview (30 seconds) 
		** "We already use source control to track change, now we would like to run our tests every time a change is made to that source, so we know early on if a change has broken anything. We also want those changes to be visible to other people."
	* Why AppVeyor? (2 mins)
		** In the cloud (nothing to install) "Continuous Delivery for Windows"
		** Free trial and free for open source projects
		** It works with Github and is designed for Windows and PowerShell 
	* Running pester tests on a build server (3m)
		* TeamCity
		* Jenkins
		* TravisCI
		* VS Git with TFS express
	* Versioning scripts (2m)
	* Packaging scripts (2m)

### The problem
Automation code is often a combination of very complex, locally saved, unversioned code that requires a lot of knowledge to execute. Delving deeper these important scripts are often rats nests of 100's or even 1000's of lines of logic, they're brittle, one change can break them or even worse give a non-deterministic output. 

### Journey
Be sure to define and demonstrate the problem, journey and solution

### Solution

## Conclusion