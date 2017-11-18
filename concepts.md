# Concepts    


**Why should developers use configuration management tools to manage their software programs? What can go wrong?**     

- According to Pressman: Configuration Management is a set of tracking and control activities that are initiated when a software engineering projects begins and terminates when software is taken out of operation
- Configuration Management focuses on establishing and maintaining the consistency of a system throughout its lifetime.   
- It ensures that the current design and build status of the system is known and recorded; and does not rely on the knowledge of the development team. 
- The past builds and designs must be known accurately for tasks like debugging. 
- In general the older versions have great importance in many conditions like where the customers might not have updated their systems. 
- Configuration management ensures that documentation that actually describes the given system is produced.
- It helps with training people to work on the project and also in audits and supporting different product types to different customers.
- Because of CM we can study the wrong design and development patterns that maybe be followed by people and hence avoid them.
- Even when using configuration management certain things can go wrong:
requirements accepted, design implemented, tools used for development, software tested, test suite being used, software version released.
If any of these go wrong it will lead to wastage of time and effort along with delay in deliveries and also dissatisfied customers. 

**Explain the difference between continuous integration, continuous delivery, and continuous deployment, in your own words.**     
   
   integerta, delivery deployment
 - *Continuous Integration*: is a practice of automatically building, testing and analyzing any changes that were made to a software are commited to the source repository. This means that all the changes are saved and properly organized. So whenever needed we can use them in our deployment. They are howvever not available for use by customers. Hence in this practice the changes are continuosly added to the prject but the end users do not simulataneously receive the changes.
- *Continuous Delivery*: is a practice where any changes to the software can be delivered and ready to use by customer in production-like environments. Here the changes in the software are integrated and also made available for use but in a restricted environment and generally for testing purposes. Whether or not to release it to the customers is decided by the stakeholders.
- *Continuous Deployment*: is a practice where any changes made to the software are automatically tested, checked and corrected and deployed to production environments. The changes are directly tested and corrected if any errors are found and deployed for use by the end users. That is the software is automatically deployed to the customers once it passes the integration phase.


