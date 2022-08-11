# Notable-take-home
Here is the Notable Take Home Server

To run this program open whatever IDE you use and open the the Notable folder inside. I typically use Intellij.

You should be prompted to build the project. if not navigate to the server file and manually start the main method. 
from there the server is running and ready to accept requests.

I typically like to use postman to generate requests and monitor responses.

the end points I created are as follows:

GET http://localhost:8080/doctors with no parameters
"HTTP://localhost:8080/doctors"

GET http://localhost:8080/appointments with parameters date (example: 2022-08-14T08:00:00.00) and docID (example: ae6c333c-a8d2-4baf-9931-09e16d57699d)
"HTTP://localhost:8080/appointments?date=2022-08-14T08:00:00.00&docID=ae6c333c-a8d2-4baf-9931-09e16d57699d"

POST http://localhost:8080/appointments with parameters date, docID, pFirstName, pLastName, newPatient
"HTTP://localhost:8080/appointments?date=2022-08-14T08:45:00.00&docID=ae6c333c-a8d2-4baf-9931-09e16d57699d&pFirstName=jason&pLastName=fletcher&newPatient=false"

DELETE http://localhost:8080/appointments with parameter aptID (example: 7d022874-7e5a-463a-8374-87902f165e68)
"HTTP://localhost:8080/appointments?aptID=7d022874-7e5a-463a-8374-87902f165e68"

I tested this pretty thuroughly and was able to accomplish all that was required in about 2 hours and 20 minutes. 
Please feel free to contact me if you have questions or would like to discuss the code. thanks!

