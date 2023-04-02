# Difference between DevOps and Site Reliability Engineering: 
i)	DevOps aims to reduce organizational silos but SRE does not focus on this aspect.
ii)	SRE use software engineering techniques to automate IT operations that would normally perform by system administrators and DevOps talk about the overall process of software development, deployment and maintenance.
iii)	DevOps team works on application and product using agile approach. They build, test, deploy and monitor applications with speed, control and quality. SRE team regularly provides developers team with feedback.


# Organizational aspect of Devops:
i)	Collaborative culture: DevOps emphasizes collaboration and communication between teams. Developers, Operation teams and all stakeholders work together to produce a better product.
ii)	Faster time to market: With DevOps software is released very faster and quickly. Organizations quickly respond to changing market and customer needs.
iii)	CI/CD: It automates software testing, building and deployment. This helps to minimize errors and ensure that software is released faster.
iv)	Improved quality: By continuous testing and taking continuous feedback the quality of product becomes improved.

# Cloud Computing:
Cloud computing refers to deliver computing services over the internet. These services include servers, storage, databases and networking. With cloud computing organizations do not need to buy and manage infrastructure/resources. Organizations use cloud services according to their demand and pay for only what they use (pay as you go model).

# Essential characteristics of cloud computing:
i)	On-demand self-service: Cloud computing provides computing resources to customers according to their demand.
ii)	Broad-network access: You can access cloud resources anywhere in the world by using internet connection and a computing device like laptop, mobile and tablet.
iii)	Resource pooling: Cloud providers pool resources to serve multiple users in an organization.
iv)	Rapid Elasticity: Cloud resources can easily be scaled up and scaled down.  
v)	Measured services: Cloud providers measure resource usage and charge customer according to what they use.


# Cloud Deployment Models:
Cloud deployment models refer to different ways to deploy cloud computing resources. There are different deployments models are:
i)	Public cloud: In public cloud all hardware and software are maintained by third party service providers. Microsoft azure is an example of public cloud. In public cloud you share same resources with other organizations. You can manage services through portal.
ii)	Private cloud: Private cloud consists of cloud resources that are exclusively used by one organization or business. The private cloud can be physically located at your organizations onsite data center or host by third party service providers. In private cloud all the hardware and software are maintained on a private network and all infrastructures are solely dedicated to one organization.
iii)	Hybrid Cloud: Hybrid cloud combines features of both public and private cloud. It allows organizations to use public and private cloud according to their need, private cloud for critical workloads and public cloud for non-critical workloads. Hybrid cloud allows data and apps to move between two environments.
iv)	Community Cloud: This cloud is similar to private cloud but it is shared among multiple organizations with similar goals such as those in the same industry.

# Cloud Service Models:
There are three types of cloud service models are:
i)	IaaS (Infrastructure as a Service): It provides virtualized resources such as virtual machines and storage. All the resources are managed by third party service providers. AWS and Microsoft Azure is an example of Iaas.
ii)	PaaS (Platform as a Service): It provides customer/developers an environment to build, test and deploy apps. Customers have control over apps but OS, middleware are managed by cloud providers. Google app engine, Windows azure are examples of PaaS
iii)SaaS (Software as a Service): It provides complete application that can be accessed through web browser. A majority of SaaS applications run directly through your web browser, which means they do not require any downloads or installations on the client side. You use the SaaS products on a subscription basis. Dropbox, Google workspace are examples of SaaS.



# Required DevOps Behavior:
Collaboration between teams, Transparency to check environment, focus on customer needs, regularly testing and trying new approaches etc. are required DevOps behaviors.



# Continuous Integration: 
Continuous integration is a software development practice in which developers commits their code and code changes in a shared repository. All these commits are tested so developers detect and fix errors early in the development process, rather than waiting until later stages when they may be more difficult and time-consuming to fix. CI includes version controlling, building and testing.

# Continuous Delivery:
This is the practice of automating the release process so that the software can be easily and reliably deployed to production at any time. CD involves building, testing, and packaging the application in a way that is repeatable and consistent, and then deploying it to production using automation. With CD, software releases can be made more frequently and with greater confidence, reducing the risk of bugs and errors.
i)	Continuous delivery automatically deploys releases to a testing or staging environment (A staging environment (stage) is a nearly exact replica of a production environment for software testing).
ii)	Continuous delivery does not automatically deploy code changes to production.
Following the automation of builds and unit and integration testing in CI, continuous delivery automates the release of that validated code to a repository. So, in order to have an effective continuous delivery process, it’s important that CI is already built into your development pipeline. The goal of continuous delivery is to have a codebase that is always ready for deployment to a production environment.


# Continuous Deployment:
The final stage of a mature CI/CD pipeline is continuous deployment. As an extension of continuous delivery, which automates the release of a production-ready build to a code repository, continuous deployment automates releasing an app to production. Because there is no manual gate at the stage of the pipeline before production, continuous deployment relies heavily on well-designed test automation.
i)	Continuous deployment automatically deploys releases from building through testing and into production.
ii)	Continuous deployment doesn't ensure your testing culture and protocol is up to snuff. It simply looks for a checked box and, if it finds the box is checked, deploys the release to production and beyond.





# Infrastructure as Code:
Infrastructure as Code (IaC) is the managing and provisioning of infrastructure through code instead of through manual processes.

Benefits: 
i)	Speed: IaC avoids manual processes so infrastructure deployment is quick.
ii)	Reduced risk: Automation removes the risk associated with human error, like manual misconfiguration; removing this can decrease downtime and increase reliability.


