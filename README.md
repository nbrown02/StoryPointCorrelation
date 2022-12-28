# Story Point Correlation
Most teams believe Story Points are something you MUST do as part of any Agile framework. This is a Power BI template to challenge this notion, allowing you the ability to connect to your Azure DevOps, Azure DevOps Server and/or TFS data and see the correlation (or not!) of story points.

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download the appropriate template file:
  - [Scrum process template (including inherited)](https://github.com/nbrown02/Story-Point-Correlation/raw/main/StoryPointsCorrelation%20-%20Scrum.pbit) 
  - [Agile process template (including inherited)](https://github.com/nbrown02/Story-Point-Correlation/raw/main/StoryPointsCorrelation%20-%20Agile.pbit) 
* Then you're good to get started!

### Connectivity
* Open the .pbit file
* Select http/https (only choose http if your Azure DevOps Server is HTTP)
* Add the Analytics / Azure DevOps Server URL - for Azure DevOps services enter 'analytics.dev.azure.com' / for Azure DevOps Server enter your server details
* Add your organization and project name

Don't confuse the team name with the project name, a common mistake. If the URL you use is "http://dev.azure.com/Microsoft-UK/AzureDevOpsTeam/Database", then Microsoft-UK is the Organization Name, AzureDevOpsTeam is the Project name, Database is the team name.

* It should then look something like this:

Azure DevOps Services:
![alt text](https://raw.githubusercontent.com/nbrown02/Story-Point-Correlation/main/Screenshots/AzDO%20Login.png)


Azure DevOps Server:
![alt text](https://raw.githubusercontent.com/nbrown02/Story-Point-Correlation/main/Screenshots/AzDO%20Server%20Login.png)

* Hit 'Load' 
* If you are prompted for a login, you can choose:
  - 'Organizational' and enter your Organization email/password (if required) and sign in
  - 'Basic' and use a Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank)

  ![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Once signed in hit 'Load' and wait for your charts to populate!

### Screenshots
![alt text](https://github.com/nbrown02/Story-Point-Correlation/blob/main/Screenshots/Screenshot.png?raw=true)

![alt text](https://github.com/nbrown02/Story-Point-Correlation/blob/main/Screenshots/Screenshot2.gif?raw=true)

Example of looking at multiple teams data and story point correlation with the best result seen (note: not comparing teams to each other!)

![Euq4843XYAQ3ZuZ](https://github.com/nbrown02/Story-Point-Correlation/blob/main/Screenshots/Screenshot2.png?raw=true)
