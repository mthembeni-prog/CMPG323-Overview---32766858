# CMPG323-Overview---32766858


For this project a single repository has been made and divided into 5 different branches for a specific project such as Project 5 will have all files for that specific project the main branch will be used to store all branches in which the projects will be found.

CMPG323-Overview Repo --->Main Branch--->Project 1---Project 2--->Project 3--->Project 4--->Project 5
This text diagram represents the 5 projects that have been branched from the main branch in the repository. These branches are set and placed in such a way that the projects don't influence each other such as when details Project 3 have been set they will not be able to influence Project 4. The branches can only be affected when they are pushed pr pulled.

*Branching Strategy*

At the end of every sprint and milestone as i get to the release from the main branch, a release branch strategy will be applies which will fix bugs from the release branch and merge them back into the release branch in a pull request.
![Branch](https://user-images.githubusercontent.com/110576122/185352832-198af25f-1445-4222-af58-c51fd7ed1854.JPG)



this is the method used as a branching strategy for the projects:
One repository has multiple branches and projects can be individually edited. 

Gitignore is used to to tell git to ignore items that we do not want to publish into our repository, this can be created in the form of a template, this is used with each of our projects. These can be credential files for the databases that are not meant to be seen by the public in the repository because it is not secure. 

For the moment only one repository will be used to to display the submisiion of projects but it will be necessary to use two Git tools that can manage multiple repositories within one project. The two tools are HelixTeamHub and Helix4Git Do. Here, HelixTeamHub lets me work with multiple repositories, where i can use Helix4Git to contribute to the sub-projects or repositories per submission of each project


When is comes to the storage of credentials and sensitive information, gitignore plays a massive role in blocking certain items that we do not what to store in the repository you can use git-credential-store to store your passwords unencrypted on the disk, protected only by the permissions of the file system. You can check the credentials stored in the file ~/. git-credentials

