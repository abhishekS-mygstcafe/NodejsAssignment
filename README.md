# NodejsAssignment

NodeJS Assignment:

1) Agent - Agent Name
2) User - first name, DOB, address, phone number, state, zip code, email, gender, userType
3) User's Account - Account Name
4) Policy Category (LOB) - category_name
5) Policy Carrier - company_name
6) Policy Info - policy number, policy start date, policy end date, policy category, collection id, company collection id, and user id.

You have to perform the following tasks based above information:

Task 1:
1) Create API to upload the attached XLSX/CSV data into MongoDB. (Please accomplish this using worker threads)
2) Search API to find policy info with the help of the username.
3) API to provide aggregated policy by each user.
4) Consider each info as a different collection in MongoDB (Agent, User, User's Account, LOB, Carrier, Policy).

Task 2:
1) Track real-time CPU utilization of the node server and on 70% usage restart the server.
2) Create a post-service that takes the message, day, and time in body parameters and it inserts that message into DB at that day and time.

INSTRUCTION TO PERFORM TASK 2 (ii) PART
Task 2 => 2) This task is independent of the above task. You can have two collections, collection and collection 2. On post request, a message and timestamp will get saved into the collection and a job will be scheduled on the timestamp which transfers the message from collection 1 to collection 2.

Dataset: Attached FIle
