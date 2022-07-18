# Kanban-Board-SuperScholar
Made A REST API using Express.js and MongoDB(local database is used)

To run the file Extract the folder,
In the console type command nodemon .\App.js
Server will Run


#To Run The REST API USE
##### localhost:3000/boards        -To create a new task(POST REQUEST)
##### loaclhost:3000/boards/id     -To update a task with uniques id passing in the link (PUT REQUEST)

Test Cases


Example:1 (POST REQUEST)
localhost:3000/boards
{
"title":"Wash Your Hands"
}

Output: Response code 201
JSON Output:
{
"id":1,
"stage":1,
"title":"Wash Your Hands",
}


Example2:(POST REQUEST)
localhost:3000/boards
{
"title":"Study"
}

Output: Response code 201
JSON Output:
{
"id":2,
"stage":1,
"title":"Study",
}



Example:3 (PUT REQUEST)
localhost:3000/boards/1
{
"stage":2
}

Output: Response code 201
JSON Output:
{
"id":1,
"stage":2,
"title":"Wash Your Hands",
}


