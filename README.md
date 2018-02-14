# WMDD_4999_18-assignment-02

URLs for:
Creating a recipe: https://4xlskjwrmd.execute-api.us-west-2.amazonaws.com/dev/reciepes
Reading a recipe:  https://4xlskjwrmd.execute-api.us-west-2.amazonaws.com/dev/reciepes/{id}
Deleting a recipe: https://4xlskjwrmd.execute-api.us-west-2.amazonaws.com/dev/reciepes/{id}
Updating a recipe: https://4xlskjwrmd.execute-api.us-west-2.amazonaws.com/dev/reciepes/{id}

Instructions to Test the API:

You can use Curl to test the API's and then paste them on the browser and you could see the data in JSON format.

Create/POST:curl -X POST https://4xlskjwrmd.execute-api.us-west-2.amazonaws.com/dev/reciepes --data '{"JSON parameters", "checked": true }'

Read/GET:curl https://4xlskjwrmd.execute-api.us-west-2.amazonaws.com/dev/reciepes/{id}

Delete: curl -X DELETE https://4xlskjwrmd.execute-api.us-west-2.amazonaws.com/dev/reciepes/{id}

Update: curl -X https://4xlskjwrmd.execute-api.us-west-2.amazonaws.com/dev/reciepes/{id} --data '{ "JSON parameters", "checked": true }'


