# FINAL REFLECTION
## CCM101 – Cloud Computing
### Mission 1 to Mission 10: The Enterprise Cloud Architect

Our journey from Mission 1 to Mission 10 in CCM101 – Cloud Computing has been a valuable learning experience that helped us understand the importance of cloud computing, system administration, infrastructure management, security, automation, and application deployment. Throughout these missions, we gradually developed our knowledge of how computing systems work, how different technologies are connected, and how cloud infrastructure can support real-world applications. This journey also challenged us to become more patient, resourceful, and collaborative when facing technical problems.

At the beginning of the course, we understood cloud computing mainly through its basic concepts and common applications. We knew that cloud computing allows individuals and organizations to access computing resources and services without having to manage all the physical infrastructure themselves. However, as we progressed through the missions, we realized that cloud computing involves much more than storing files online or accessing applications through the internet. It requires proper planning, configuration, resource management, security, monitoring, automation, and maintenance to ensure that systems operate reliably and efficiently.

## Learning Journey from Mission 1 to Mission 9

Missions 1 through 9 helped us build a foundation for understanding cloud computing. Each mission contributed to our learning and prepared us for more complex activities. We gradually learned to look at cloud computing as a combination of interconnected technologies, tools, services, and processes that work together to deliver applications and computing resources.

One of the most important lessons we gained from these earlier missions was the importance of connecting theoretical knowledge with practical experience. Understanding the concepts of cloud computing, virtualization, infrastructure, and system administration is important, but applying these concepts through hands-on activities makes learning more meaningful. Through practical exercises, we learned that even a small configuration error can affect the performance or accessibility of a system. Because of this, we recognized the importance of following instructions carefully, understanding commands before executing them, and verifying the results of important configuration steps.

We also developed a better understanding of how different computing components depend on one another. A system may contain several services and resources, but these components must be configured correctly to work together. This helped us understand why planning, documentation, and systematic troubleshooting are essential in managing computing environments. We learned that solving technical problems requires patience, observation, and logical thinking rather than simply repeating commands without understanding their purpose.

Another important lesson was the value of responsibility and teamwork. As a group, we needed to understand the requirements, share our progress, organize our work, and ensure that our outputs contributed to the overall project. We realized that successful IT projects require not only technical knowledge but also communication, coordination, and a willingness to help one another overcome challenges.

## Mission 10: The Enterprise Cloud Architect

Mission 10 became one of the most challenging and meaningful parts of our journey because it required us to apply our knowledge in building and documenting a multi-tier application environment. Our task involved setting up an Ubuntu Server virtual machine, using Docker Compose to manage the application services, deploying WordPress with a MySQL database, configuring security measures, and preparing the documentation needed for our final submission.

One of the first challenges we encountered was configuring our virtual machine using Oracle VirtualBox. We needed to consider the available system resources, including memory, processor allocation, and storage. During the setup process, we experienced technical difficulties, including freezing and unexpected interruptions. These problems taught us that infrastructure configuration requires careful planning, especially when working with limited hardware resources. We also learned that virtualization makes it possible to create and manage a separate server environment on a personal computer, allowing us to practice server administration without requiring a dedicated physical server.

After preparing the virtual machine, we proceeded with the Ubuntu Server environment. Working through the terminal helped us become more familiar with Linux commands, directory navigation, file management, permissions, and service administration. Although using the terminal was sometimes difficult, especially when errors occurred or commands did not produce the expected results, we learned that understanding the command line is an important skill for system administrators and cloud engineers.

We also worked with Docker and Docker Compose to organize our application services. Our project used WordPress as the web application and MySQL as its database. Through this setup, we learned that an application can be divided into separate services that communicate with one another instead of being managed as a single component. WordPress handles the website, while MySQL stores the application's data. Docker Compose helps define and manage these services through a configuration file, making the deployment process more organized and repeatable.

Working with the Docker Compose configuration also helped us understand the importance of container images, environment variables, port mappings, and persistent volumes. We learned that the configuration file is not just a collection of commands; it describes how the application's components should be created and connected. We also recognized the importance of using the correct file names and directory structures to meet project requirements and make our work easier to maintain.

## Challenges and Problem-Solving Experience

Throughout Mission 10, we encountered several technical challenges that tested our patience and problem-solving skills. Some of the difficulties involved virtual machine performance, Docker container management, file permissions, configuration errors, and accessing the deployed application. At times, we needed to repeat certain steps, review commands, and check our configuration files to identify the cause of a problem.

These experiences taught us that technical errors are a normal part of IT work. What matters is how we respond to them. Instead of immediately giving up when something did not work, we learned to examine the situation, verify the current system status, and identify possible causes before making changes. We also realized that copying commands without understanding them can lead to additional errors. As future IT professionals, we need to develop the habit of understanding the purpose of each command and checking its output.

Another challenge was working with limited resources on our local machine. Running a virtual machine and multiple Docker containers requires sufficient memory, processing power, and storage. When the system becomes overloaded, applications may freeze or respond slowly. This helped us understand the importance of resource allocation and performance considerations when designing and deploying infrastructure.

We also learned that completing a technical setup is not the same as proving that it works correctly. For example, creating a backup script does not automatically guarantee that a valid backup has been generated. The backup must be tested, its output checked, and its recovery process considered. Similarly, a scheduled automation task must be configured and verified before we can confidently say that it works as intended. This taught us the importance of testing, validation, and evidence-based reporting.

These challenges helped us become more persistent and independent. They reminded us that learning IT is a continuous process that involves experimentation, troubleshooting, and improvement. Even when we did not immediately find the solution, each problem gave us an opportunity to understand the system more deeply.

## Security, Persistence, and Automation

Another important part of our project was understanding the need for security and reliable data management. We worked with the Ubuntu Server firewall and considered how network access should be controlled. This helped us recognize that a deployed application should not simply be accessible; it should also be protected against unnecessary or unauthorized access. Firewall rules, restricted database exposure, proper permissions, and secure credential management are important considerations when deploying an application.

We also learned about persistent storage through Docker volumes. Containers can be recreated or replaced, so important application data should not depend entirely on the temporary filesystem of a container. Persistent volumes help preserve database and application data beyond the lifecycle of an individual container. This is particularly important for a WordPress website because its database and uploaded content may contain information that must remain available after a restart or redeployment.

Automation was another important lesson from Mission 10. A Bash script can perform repetitive administrative tasks, such as creating database backups, while a Cron Job can schedule a script to run automatically. These tools can reduce manual work and support consistent maintenance. However, we learned that automation must be tested carefully. A script that exists in the project directory is not enough; it must execute correctly, produce the expected output, and be scheduled properly if automatic execution is required.

This experience helped us appreciate how security, persistence, and automation work together in a reliable infrastructure environment. A system should protect its resources, preserve important data, and support routine maintenance. These practices are essential not only for academic projects but also for real-world applications used by businesses and organizations.

## Documentation and Professional Development

Aside from building the application, we learned the importance of proper documentation. Preparing our operational manual, architecture diagram, configuration files, and final reflection helped us organize the information about our project. Documentation explains how a system is structured, how it can be deployed, how its components interact, and what steps may be needed when problems occur.

We also realized that documentation is useful beyond satisfying academic requirements. In professional IT environments, another administrator may need to understand or maintain a system that someone else created. Clear and accurate documentation makes this process easier and reduces the risk of mistakes. It also provides a record of the configuration, procedures, and limitations of the system.

Preparing the required files for our GitHub portfolio further emphasized the importance of organizing our work. Using clear filenames and a consistent folder structure makes project materials easier to review and maintain. We learned that a successful project should demonstrate not only technical implementation but also the ability to explain our decisions and provide evidence of our work.

Working as a group also helped us understand the importance of communication and accountability. Each member's contribution can affect the progress of the entire project. We learned that sharing updates, discussing problems, and coordinating responsibilities are important in completing technical requirements. When difficulties arise, teamwork allows us to exchange ideas and approach problems from different perspectives.

## Application of Our Learning in the Future

The knowledge and experience we gained from CCM101 will be useful as we continue our studies and prepare for professional opportunities in the IT industry. The skills we practiced, including Linux command-line operations, virtualization, Docker, Docker Compose, application deployment, firewall configuration, persistent storage, and basic automation, are relevant to system administration, cloud engineering, DevOps, and infrastructure support.

We also learned that technical competence involves more than knowing which commands to execute. IT professionals must understand why a particular configuration is needed, what risks it may introduce, and how to verify that it works correctly. They must also document their work, protect sensitive information, and consider the needs of the people who will use or maintain the system.

In the future, we want to improve our skills in troubleshooting, cloud platform management, container orchestration, monitoring, backup and recovery, and infrastructure automation. We understand that our Mission 10 project is a learning foundation rather than a complete production-ready enterprise system. A real enterprise environment would require additional measures, including stronger secret management, regular security updates, monitoring and alerting, tested recovery procedures, and more comprehensive access controls.

Recognizing these limitations is part of our learning experience. It helps us identify which areas need further improvement and reminds us that technology continuously evolves. To remain effective in the IT industry, we must continue learning, practicing, and adapting to new tools and technologies.

## Conclusion

Overall, our journey from Mission 1 to Mission 10 has helped us develop a deeper understanding of cloud computing and the responsibilities involved in managing computing infrastructure. The earlier missions established our foundation, while Mission 10 challenged us to combine our knowledge in a practical project involving virtualization, Linux, Docker Compose, WordPress, MySQL, security, persistent storage, automation, and documentation.

The experience was not always easy. We encountered errors, configuration problems, performance limitations, and tasks that required repeated testing. However, these challenges taught us valuable lessons about patience, critical thinking, teamwork, and responsible technical practice. We learned that successful IT work requires not only completing tasks but also understanding the system, verifying results, documenting procedures, and acknowledging areas that still need improvement.

As a group, we are grateful for the opportunity to apply our knowledge through hands-on activities and to experience some of the challenges that IT professionals face when deploying and maintaining systems. This journey strengthened our appreciation for cloud computing and showed us how different technologies can work together to support an application.

Most importantly, CCM101 taught us that becoming IT professionals is a continuous process of learning and improvement. We may not know every solution immediately, but we can develop the ability to investigate problems, learn from our mistakes, collaborate with others, and make informed technical decisions. As we move forward in our academic and professional journey, we will carry these lessons with us and continue developing the skills needed to build, secure, maintain, and improve reliable computing systems.

Mission 10 represents more than the completion of a laboratory activity. For us, it is an opportunity to recognize how far we have progressed, what we have learned from our challenges, and what we still need to improve. Through this experience, we have become more aware of the knowledge, discipline, and teamwork required in cloud computing, and we are motivated to continue growing as future IT professionals.
