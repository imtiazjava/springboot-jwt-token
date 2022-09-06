# springboot-jwt-token


The following are the EndPoints for testing:
----------------------------------------------


POST : http://localhost:8080/authenticate
  {
    "userName":"imtiaz",
    "password":"password"
  }
  
  
----------------------------------------------------

 GET : http://localhost:8080/msg
 
  Header
   Content-Type : application/json
   Authorization:
   Bearer 
   
   eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJpbXRpYXoiLCJleHAiOjE2NjI1MTM0NzQsImlhdCI6MTY2MjQ3NzQ3NH0.-E0z5-_kBLGS1QIqEmskfp7AW6qAVglJscXb-u0acBQ
