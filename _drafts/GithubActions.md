### Github API

This is the code for a curl call to the API to execute the Action.

curl \
  -X POST \
  -H "Accept: application/vnd.github.v3+json" \
  -v -H "Authorization: token Here comes the token found in Settings"
  https://api.github.com/repos/carlosabella/myfolder.github.io/actions/workflows/19430243/dispatches \
  -d '{"ref":"master", "inputs": { "title":"Test from API", "body":"Lets see if this works" }}'
  
 More info about the Github API here: https://docs.github.com/en/rest/reference/actions#list-repository-workflows
 
 ### Github Action
 
 Go to the test project to see the example: https://github.com/carlosabella/myfolder.github.io/actions/runs/1806466367/workflow
 
