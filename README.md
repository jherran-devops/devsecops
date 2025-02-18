'''THIS REPOSITORY INCLUDES SOME BASIC CONCEPT AND DEVSECOPS EXAMPLES'''

1. BASIC SECURITY TERMS

* SAST - STATIC APPLICATION SECURITY TESTING
  white-box testing that analyzes source code for identifying security issues
* SCA - SOFTWARE COMPOSITION ANALYSIS
  scans your code base to provide visibility into open source software components including license compliance an security vulnerabilities
* DAST - DYNAMIC APPLICATION SECURITY TESTING
  is a type of black-box security testing in which dynamic test are performed on the application
* IAST - INTERACTIVE APPLICATION SECURITY TESTING
  it combines elements of both SAST and dAST and tries to overcome its limitations. It scan specific workflows of code
* IAC - INFRASTRUCTURE AS CODE
  is the process of creating infrastructure using code definition files and testing these files for identifying issues in such files is called IAC Security Testing
* API SECURITY
  is also called security for Microservices(is a subset of API), example Ecommerce application will have User Registration API and this API will have microservices to Create/Update/Delete users. 

DEVSECOPS CONCEPT

```Development + Security + Operation```

Shift Left Approach
We implement security at the very early stage in SDLC during testing and implementation phase.
Security activite is now at the core of Application development and this activity starts from code implementation itself.
We integrate security in Operation Activity (secure container registry compliance scans after deployment)

TOOLS FOR IMPLEMENTING
- Git secrets
- Security Plugins in any IDE
- Trufflehog
- Code Quality Tools(Sonarqube)
- SAST security tools(Fortify, Veracode, Checkmarx)
- SCA security tools(Fortify, Veracode, Checkmarx, Snyk)
- DAST security tools(OWASP ZAP, WebInspect, Veracode DAST, Acunetix)
- IAC security tools(Bridgecrew, Synk)
- Container security tools(Aqua, Qualys,ProsmaCloud)
- Build Pipeline tools(Jenkins, AWS, GCP Cloudbuild, Azure Devops, Github Actions, Gitlab )
- Cloud Security Posture Management Tools(Aqua, Bridgecrew)
- Container Registry Scanning Tools(Aqua, AWS NAtive Registry Scanning)
- Infrastructure Scanning Tools(Chef inspec(compliance), Nessus)
- Cloud Security Tools(AWs Security Hub, Azure defender)