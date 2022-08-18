# CMPG323-Overview---32766858


For this project a single repository has been made and divided into 5 different branches for a specific project such as Project 5 will have all files for that specific project the main branch will be used to store all branches in which the projects will be found. If needed more repositories will be made for each poject because they have different objectives milestines as well as goals.

CMPG323-Overview Repo --->Main Branch--->Project 1---Project 2--->Project 3--->Project 4--->Project 5
![Untitled Diagram drawio](https://user-images.githubusercontent.com/110576122/185356163-4d2d64f3-9832-4cf5-89c4-27be3d0fdffb.png)



*Project Structure*

This diagram represents the 5 projects that have been branched from the main branch in the repository. These branches are set and placed in such a way that the projects don't influence each other such as when details Project 3 have been set they will not be able to influence Project 4. The branches can only be affected when they are pushed or pulled. 

Project 1
The project is structured in a way that project 1 lays the foundation of each other project beacuse of all the milestones and dates as well as tasks set to be completed in the duration of each project. 

Project 2

I plan to start creating the CRUD RESTful API that will connect to a database storing IoT device data. The API should contain at least one get, post, patch and delete method per
resource – aligning to the project's requirements. The RESTful API architecture has several
endpoints called over HTTP, invoking application code to update a database, this will be the main concern during Project 2 and everything will be recorded and updated using git hub

Project 3

During this project i will aquire access the NWU Azure tenant 
ensire that i create a resource group to logically group my  work. Using the
appropriate naming convention
Make sure that Visual Studios 2022 Community edition and .NET Core 3.1 are installed
Make sure that the database required in P2 has been created and is accessible in Azure

Project 4


Make sure a UiPath Automation Cloud account is created
Make sure that i download UiPath Studio Community Edition to your computer
Ensure that i am  able to access the web application that you will be performing UI
automation on

Project 5

Create report in Power BI in the creation of the final POE







*Branching Strategy*

At the end of every sprint and milestone as i get to the release from the main branch, a release branch strategy will be applies which will fix bugs from the release branch and merge them back into the release branch in a pull request, this strategy will be sed throughtout the whole duration of the project.


![Branch](https://user-images.githubusercontent.com/110576122/185352832-198af25f-1445-4222-af58-c51fd7ed1854.JPG)



this is the method used as a branching strategy for the projects:
One repository has multiple branches and projects can be individually edited. 

Gitignore is used to to tell git to ignore items that we do not want to publish into our repository, this can be created in the form of a template, this is used with each of our projects. These can be credential files for the databases that are not meant to be seen by the public in the repository because it is not secure. 

For the moment only one repository will be used to to display the submisiion of projects but it will be necessary to use two Git tools that can manage multiple repositories within one project. The two tools are HelixTeamHub and Helix4Git Do. Here, HelixTeamHub lets me work with multiple repositories, where i can use Helix4Git to contribute to the sub-projects or repositories per submission of each project


When is comes to the storage of credentials and sensitive information, gitignore plays a massive role in blocking certain items that we do not what to store in the repository you can use git-credential-store to store your passwords unencrypted on the disk, protected only by the permissions of the file system. You can check the credentials stored in the file ~/. git-credentials

