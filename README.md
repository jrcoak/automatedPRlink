# automatedPRlink
This github action is to automatically create a Jira Issue and link to PR.

Go to Actions and create a workflow. Save the contents of jiralink.yml to the generated .yml.

Save create-jira-issue.js to your newly created github folder. 

Create a base64 encoded token in the format of username:api_token for your jira credentials, then save that encoded token as a Repository Secret. 
