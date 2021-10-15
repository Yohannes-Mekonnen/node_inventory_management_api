# node_inventory_management_api

Instructions:
 - Clone the project then go to that directory.
 - Unzip it
 - Create a database with a name 'inventory_management' and import the local.sql file.
 - run it with 'npm run serve' command.
 - 


End points:
 - 'host':3000/:item/add  
    request values: 
    {
     "quantity": 'number',
     "expiry": 'unix time'
    }
 - 'host':3000/:item/sell
   request values: 
   { 
    "quantity": 'number'
   }
 - 'host':3000/:item/quantity 
