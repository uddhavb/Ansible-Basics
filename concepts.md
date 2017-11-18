# Concepts    


**Why should developers use configuration management tools to manage their software programs? What can go wrong?**     

- According to Pressman: Configuration Management is a set of tracking and control activities that are initiated when a software engineering projects begins and terminates when software is taken out of operation.   
     
- Configuration Management focuses on establishing and maintaining the consistency of a system throughout its lifetime.   
- It ensures that the current design and build status of the system is known and recorded; and does not rely on the knowledge of the development team. 
- The past builds and designs must be known accurately for tasks like debugging. 
- In general the older versions have great importance in many conditions like where the customers might not have updated their systems. 
- Configuration management ensures that documentation that actually describes the given system is produced.
- It helps with training people to work on the project and also in audits and supporting different product types to different customers.
- It helps reduce costs by having detailed knowledge of all the elements and thus avoiding unncessary costs like duplications.
- CM ensures greater agility and faster problem resolution and thus a better quality of service.
- There is a decreased risk of failures and hence increased security.
- It provides greater reliability on the system, since improper configurations can be rapidly detected and corrected.
- Faster restoration of services, if you know the configuration and its interrelation with other configurations.
- Because of CM we can study the wrong design and development patterns that maybe be followed by people and hence avoid them.
- Even when using configuration management certain things can go wrong:
requirements accepted, design implemented, tools used for development, software tested, test suite being used, software version released.
If any of these go wrong it will lead to wastage of time and effort along with delay in deliveries and also dissatisfied customers.
- Trying to include continuous deployment or any kind of automation with proper configuration management can lead to big problems and losses.
- It may take much more time and resources to develop the system.
- A separate development and operations team may cause bottlenecks in new changes to the software.

**Explain the difference between continuous integration, continuous delivery, and continuous deployment, in your own words.**     
   
   integerta, delivery deployment
 - *Continuous Integration*: is a practice of automatically building, testing and analyzing any changes that were made to a software. These changes are commited to the source repository. This means that all the changes are saved and properly organized. So whenever needed we can use them in our deployment. They are not automatically available for use by customers. Hence in this practice the changes are continuously added to the project but the end users do not simulataneously receive the changes.
- *Continuous Delivery*: is a practice where any changes to the software can be delivered and ready to use by customer in production-like environments. Here the changes in the software are analyzed, tested, integrated and also made available for use but in a restricted environment and generally for testing purposes. These changes are ready to be immediately delivered to the customers, but whether or not to release it to the customers is decided by the stakeholders.
- *Continuous Deployment*: is a practice where any changes made to the software are automatically tested, checked and corrected and deployed to production environments. The changes are directly tested and corrected if any errors are found and deployed for use by the end users. That is the software is automatically deployed to the customers once it passes the integration phase.


