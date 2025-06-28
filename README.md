# airbnb-clone-project
This is project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb.




##Team Roles## 
UI/UX designer- Transforms a product vision into user-friendly designs 
Software architect- Designs a high-level software architecture 
Software developer - Engineers and stabilizes the product
Test automation engineer - Designs a test automation ecosystem
DevOps engineer - Facilitates cooperation between development and operations teams




##Technology Stack##
Django- written in python, is a backend web framework that helps build web applications securely, efficiently and allows developers to focus on functionality ,
PostgreSQL- is used as a database to store details of users of the application, 
GraphQL - is a query language that gives API clients their exact query return, it fetches data from multiple sources




##Database Design##
Users- a user can have more than one property,
Properties- are listed for bookings, and users are shown available properties depending on their specific wants and location , 
Bookings- bookings consist of properties in different locations and specifications based on user's wants, 
Reviews - users can express their experiences on certain bookings and properties, 
Payments - Users can make payments on listings/ properties



##Feature Breakdown##
User Management 
- this helps to manage the app users, using CRUD methods,
this also helps identify users and their bookings and properties

Property Management 
- this helps manage properties,location of propertes ,
- helps with property pricing and bookings
  
Bookings Management 
- this helps manage properties that are listed and checks through available properties
- helps show specifications and service offerings

Reviews entry 
- this shows user recommendation of a property or properties
- this helps add user experience on a property
  
Payments 
- this helps users make payments
- this also helps resolve payment problems and refunds where possible




**API Security**
authentication - Preventing user impersonation
authorization - Provisioning action when app is granted permission to carry out transaction
Rate Limiting - Preventing excessive use of app resources and limiting 


**CI/CD Pipeline**
these are automated processes of building, testing and deploying the project.
tools include - Docker, Jenkins, Terraform, Openshift, Azure
