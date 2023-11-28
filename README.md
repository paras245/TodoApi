# TodoApi

Refer Doc link :  https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-8.0&tabs=visual-studio


Step 1
Run the API

Step 2
Go to view other => other window => Endpoints explore atab will open

Step 3
Right Click on Post then Generate Request a new file will be created named Todo api.http

Step 5
Make a http call for post  and insert this 
Content-Type: application/json

{
  "name":"walk dog",
  "isComplete":true
}

make  sure your project is running and you dont replace the portnumber here 
after making request a 201 created is displayed
