# Galytix.WebApi
# Galytix assessment  submission


Submission by Ayush Mittal

!!! STEPS TO RUN SOLUTION
1. Download the ZIP file of the solution and extract it.
2. Open the extracted folder in VS2022.
3. Go to the Solution Explorer and double click on the Galytix.WebApi.sln file to load the project.
4. Make sure that the we are running the debug version and press ctrl+F5.
5. Server starts running on http://localhost:9091 .
6. Paste http://localhost:9091/swagger/v1/swagger.json in the broswer to view some basic information about the endpoints present in the API.

!!! API ENDPOINT
1. The api endpoint is http://localhost:9091/api/gwp/avg .
2. To get the required data we need a POST request on the above mentioned endpoint (using Postman/ Insomnia/ chrome extension).
3. The Content-Type is application/json.
4. The request object looks like 

***
  {
    "country":"ao",
    "lob":["transport", "motor", "liability", "a_s"],
    "start":"2008",
    "end":"2015"
  }
***

3. The response data looks like
***
  {
      "transport": 42778110.4,
      "motor": 147726403.6,
      "liability": 22025795.4,
      "a_s": 168229730.5
  }
****


# HOPE I WAS ABLE TO SATISFY YOU WITH MY SOLUTION. HOPING TO HEAR POSITIVELY FROM YOU.
    
