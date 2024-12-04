# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

For this project, I will be choosing an App Service over a Virtual Machine for the deployment of the Python Web Application.
Costs: App Service is cheaper than Virtual Machine since a VM has high-performance compute services which are not needed for this project's application. Since the web app will being running at all times, an app's service plan's cost fits with this deployment.
Scalability: App Service in-built scalability is good enough for the deployment of the Python Web Application. The application will only require querying and posting functionality, which is retrieiving data from the SQL database or writing data to the database. Scaling for a VM would require multiple VM deployment which is not needed for this type of small web application. The hardware limitations of the App Service will not hinder our project's web application from running efficiently.
Availability: Multiple VMs do provide higher availability but at a higher cost. If the web app had multiple functionalities that need to be available at all times, then multiple VMs would make sense. Since the web app only requires one main functionality, an App Service's availability is more suitable.
Workflow: The web app does not require third party softwares / other types of infrastructure to run. This web app is just built off python scripts which the App Service supports. A VM would be needed if the web app required custom software installations.

Based on the criteria described above, a Virtual Machine is too complicated and too costly for its enhanced functionalities over the App Service, which is not required for the deployment of our Python Web Application as it is built. Therefore, deploying the web app on the App Service would be a more justifiable choice.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If the web app was expanded to require additional functionalities especially those requiring the usage of custom software, then a switch to VM would be necessary. The App Service is limited in terms of hardware and the underlying OS / software is set in stone. 
