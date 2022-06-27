## Add and Update Lab (4.04)

### Specifications

ITERATION 1: Create the routes below as efficiently as possible using validation where appropriate.

ITERATION 2: Create a route to add a new patient.

ITERATION 3: Create a route to add a new doctor.

ITERATION 4: Create a route to change a doctor’s status.

ITERATION 5: Create a route to update patient’s information (the user should be able to update any patient information through this route).

Write a short answer to the following questions:
1. Did you use the same type of route to update patient information and to update an employee department?
No, for the first one I used PUT, because it`s the way to update everything. For the second one I used PATCH, because we want to update only one of the values and leave the others being the same.

2. Why did you choose the strategy that you chose?
Because It´s a good practices work flow.

3. What are the pros and cons of the strategies you chose for creating these routes?
I think there´re no cons or pros, It´s the way that we have to work and use the strategies most efficiency.

4. What are the tradeoffs between PUT and PATCH?
The main difference between PUT and PATCH in REST API is that PUT handles updates by replacing the entire entity, while PATCH only updates the fields that you give it. PATCH does not change any of the other values. If you use the PUT method, then everything will get updated. 
[Source](https://josipmisko.com/posts/patch-vs-put-rest-api)
