Snyk
is an organization that develops security tools (SaaS) to secure:
* Source Code
* Open Source/Third Party Libraries
* Containers
* Infra as Code

Creating a Snyk account to run a Software Composition Analysis scan: use to identify security issues by third party libraries present in our code (log4.js) 

Go to:
www.snyk.io

Use github for create an account,
Enter username and password and sign, then the account is authorized.

Log into the snyk account, and under account name, pick up the Authorization Token.
Then fork a snyk reachability sample application and inside of it go to actions, then create your github action, and the from https://github.com/marketplace/actions/snyk, copy and paste the workflow sample for maven (because the project is java)

OWASP(Open Web Application Security Project) ZAP
is an open-source web application security scanner, for:
- web applications
- API specifications

Requirements:
1) Use OWASP ZAP github Action from the github marketplace
2) Create GHA script with the published action Step1)
3) Update the web application URL in the GHA script and then run the action to perform the DAST scan

SonarCube
is a SaaS platform that helps to keep our source code free from:
- Code Quality issues
- Code Security Issues
We can define quality gates with sonarcloud, as per project quality standards

Visit sonarcloud.io and create an account using the github option
you log in with github and then you are log in sonarcloud