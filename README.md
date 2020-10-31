# project-kitkat
A lighweight , simple express application powered by latest ESM with  node (14) and all modern ES6 features using mongoose as ORM and pm2 as daemon task runner , it handles all the backend tasks for the project-kitkat ( an eccommerce website for RK-industries ) .




# Find below the documentations of Api that we  provide :) 

### AuthRoutes 
 * /api/signin   Type : POST 
 
  fields required :
   <email>
   <password>


* /api/signOut  TYPE : GET 




### UserRoutes 
* /api/user/:userId   Type : GET 

* /api/user/:userId   Type : PUT 
    <name>
    <password>
* /orders/by/user/:userId Type : GET 
  -- to fetch purchase history of a user      



### categoryRoutes
 * /category/:categoryId   Type : GET 
    -- to get the category by its id

 * /category/create/:userId  Type : POST 
    -- to create a category 
    
