# CSWorkshop

In development website for fetching and presenting beautiful learning material.

Easily find new content, navigate through pages.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need a GitHub account. If this is a uni-project you may want to create an organisation account and add multiple members.

Software
```
  GitHub Desktop
  Node.js
  npm
  bower
  polymer-cli
```  

### Installing
The following steps may help getting a development environment up and running
Steps  

1.	Create an Organisation Profile in GitHub
```
https://help.github.com/articles/creating-a-new-organization-from-scratch/
```

2.	Fork csworkshop to your organisation, by selecting the GitHub Fork option and choose the location.

3.	Install GitHub desktop
```
https://help.github.com/installing-github-desktop/
```

4.	Clone or Download the forked repository to your local environment.

5.	Download and Install Node.js. Node.js is the JavaScript runtime that is use in csworkshop.com.
```
https://nodejs.org/en/download/
```

6.	Navigate to the project folder (created by GitHub desktop)
  	Alternatively, you can use the GitHub desktop “Repository/Open in Git Bash” menu option.

7.	Install npm. npm is the default package manager for JavaScript runtime environment Node.js.
```
npm install npm@latest -g
```

8.	Install Bower. Bower is a package manager that is used for managing front-end components.
```
npm install -g bower
```

9.	Install Polymer CLI. Polymer-CLI is the command line interface for the Polymer tool.
```
npm install -g polymer-cli
```

10. Install bower
```
bower install
```

11.	Run project. This command will run a local instance of the csworkshop.com project.
```
polymer serve
```

### Conclusion
After these steps all of the required environments and packages should be installed in the specified folder ready for use.

## Configuring the Project

The URL links for the project tutorials are controlled through a central file titled appconfig.json.

If the url for the course is to change the user only needs to navigate to this file and alter the url (see below), this will then flow to all the relevant locations throughout the platform requiring no further alterations.

```
"software": "...Enter URL here...",
"hardware": "https://raw.githubusercontent.com/SwinCompSciEducation/cave-escape/master/Documentation/data.json"
```

NOTE: Please ensure that all beginning and ending quotes are still present after any editing is done to ensure correct operation.
