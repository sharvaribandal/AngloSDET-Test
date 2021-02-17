# AngloSDET-Test

SDET Technical Test

Please complete one of the following exercises. You are free to complete both the exercises.
-  Please use any programming language you feel comfortable with.
-  Once assessment is completed, please upload project to GitHub with instructions on how to run tests. You can make github repository as public and share link with us.


Exercise 1- API Test

Assessment Notes
-	The attachment contains solution ShowroomService.
-	ShowroomService solution contains the API with the endpoint which needs to be tested
-	In order to run this ShowroomService solution just load it up in Visual studio and press F5
-	ShowroomService contains following GET endpoint /api/cars/{type}
-	Please create separate solution/project to write API test.

Assessment Task:
-	We would like a BDD test for the endpoint in the API Provided and the example Acceptance criteria below, to a standard that you would consider complete for a production system

Example Acceptance criteria 
-	Endpoint to fetch a cars of specified type
-	route should be /api/cars/{type}
-	Valid car types are "Saloon", "SUV", "Hatchback"
-	Returns status code 200 if cars of specified type exist along with list of cars of specified type
-	Test which will compare and verify output of cars response based on Car type.
-	Returns status code 404 if cars of specified type do not exist 
-	Any failure scenario’s you will consider to write.
-	Please write one for test using Mocks- consider API is not available or try to mock data
-	In Short consider this service to test fully for production release and what test you can automate to satisfy it’s release to production.


Example response: 
[
  {
    "make": "BMW",
    "model": "3.25i",
    "year": "2013",
    "type": "Saloon",
    "zeroToSixty": 9.5,
    "price": 15000
  }
]


Exercise 1- UI Test
-	Task – Visit public website https://automationteststore.com/
-	Write 3-4 testcase on this using BDD style with basic framework structure.
-	E.g. Testcase - 
- Filter products based on Type-Brand
- Add Products to cart- Include Sale Items
- View and verify Cart
- Make sure acceptance test should have Test data and expected results.

IMP Note - Please do not commit code to this repository.
Upload Test project into your own github account and send us link to clone.
