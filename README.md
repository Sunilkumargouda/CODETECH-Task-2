Name: R SUNILKUMAR                                                                                                                                                                                           
Company: CODETECH IT SOLUTIONS                                                                                                                                                                            
ID:CT4D4099                                                                                                                                                                                              
Domain:DEVOPS                                                                                                                                                                                           
Duration:JULY 5th TO AUGUST 5th                                                                                                                                                                                
Mentor:

**3-Tier Full-stack project application CICD Pipeline** 

**Deployment of 3-Tier Full-stack application involves three main stages:**
1.local deployment
2.Development on Docker containers
3.Production deployment on Amazon EKS.

**Project Run-through** 
Setting up the environment 
1.setting up jenkins 
2.Continuous integration server setup
3.Docker installation 
4.SonarQube installation 
5.EKS Setup
6.Deployments of application by automating various steps like build, test etc., in a pipeline.

**Satge.1: -.Deply To Local environment** 
*Setting up the local environment for the Initial development and testing on the developer system.
*Developer clones the repository from GitHub.
*Application run locally using node.js
*Code tested and debugged before it sharing to repository.
 
Node.js with Express: Used for the web server.
Bootstrap: For front-end design.
Mapbox : Provides a fancy cluster map.
MongoDB Atlas: Serves as the database.
Cloudinary : Used for cloud-based image storage.

**Stage: -2 Development Dev environment**
* Automating tests and security scans, Integrating the changes.
* Code is cloned from GitHub repository using jenkins
* Tests executed using node.js
* Code quality is checked with the help of SonarQube for check vulnerabilities
* Security scans performed via Trivy 
* Docker image is built and scanned and pushed to Docker repository
* Application is deployed to developer environment

**Stage :-3 Production environment** 
*Deploying the tested and stable application for live and real world environments
*Code undergoes same testing d scanning environments as on the dev environment
*Built Docker image is pushed to Production registry
*Finally application is deployed to AWS EKS for the production use.

**Tools Used: -** 
CI/CD: Jenkins
Code Quality: SonarQube
Security: Trivy
Containerization: Docker
Registry: Docker Hub
Orchestration: Amazon EKS


**Conclusion:-**
This comprehensive guide outlines the seamless deployment of a three-tier full-stack application from local development to production on Amazon EKS. By following a structured approach, including local deployment, containerized development with Docker and Jenkins, and production deployment on EKS, you can achieve a resilient, secure, and scalable application. Leveraging AWS services, automation, and containerization, this process ensures high standards of code quality and security while streamlining the entire development lifecycle. Embrace the power of AWS to transform your application deployment into a robust, efficient, and scalable solution.
