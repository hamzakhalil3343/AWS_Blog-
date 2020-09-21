# Why AWS

Scale and Manage Servers and OS

Apply Security Patches
### Support for what Lang ?
Java ,Python ,Go ,Node and c#

### Used

 1- Image Processing in apple ,android and Linux machine 
 
 2- Analyzed the Soclial media data eg Trending 
 
### Companies using 

 =>  Coca Cola ,Robot ,Bencling and NordStrom
 
### How it Works ?
 
 1- Client sent request
 
 2- Lambda Receive the request
 
 3- Depend upon the amount of data it is Serve By Containers.

### Backing Up data 

Two buckets for data 

1- Source bucket

2- Destination bucket

Uses IAM Roles and Policies

Send Data from source to Destination Bucket Using lambda functions By defining their proper roles

### Function as a service arcitecture (ServerLess)

Single Function act as a service 

### Pay for use 

For no container ,amount of money is zero and increases with no of containers

### In services go to lambda  

code sec  for code writing 

Configuration sec for configuration in other files like index.handler 

### handler Function

exports.handler=(event,context,callback)=>{

}

### Event Object 

**AWS Services**

1 - Amazon s3 service (HTML,CSS,Js) used for static files

2-  API gateway

3- DyanmoDB

When a new image is uploaded ,in which s3 bucket it is uploaded and name of object and that data is transfered to lambda function,That data is stored in event 

object.

### Context Object

Provide runtime information - Function name

Provide details of execution environment - Memory Limit

Has various properties and method of gettimeoutmilisec

### Logging using cloud watch service 

Log group name and Log stream name are also get from context object

Used for Logging 

**Lambda functions can be created from Online code Editor or from Zip file**

**Lambda Functions can be created  from AWS CLI**

### Triggers

A trigger is a Lambda resource or a resource in another service that you configure to invoke your function in response to lifecycle events, external requests, or on a schedule. Your function can have multiple triggers. Each trigger acts as an client invoking your function independently.







