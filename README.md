# CI-CD-Sample-Repo

1. Need to make a webhook with development repository.
   If push event occurs, HTTP POST will be sent.

   Settings in Development repository:
   Payload URL: https://api.github.com/yoona96/CI-CD-Sample-Repo/dispatches
   Content type: application/json
   Secret: 1234
   
2. Make webhook.yml file in this repository
3. Add personal token and Sonarqube token in this repository.
