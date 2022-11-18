# *tell me, about your project, also what is your roles & responsibility in that project?*
*ans* - 

In our organisation, we have a project which is based on microservice architecture <<<<<<**project-tech-stack**

my project name - is inbestment.

specifically its an ecom website

we have 12 micro frontend, & 16 backend service        

we have backend is on container base

we have frontend is on server less

we have s3+cloudfront on frontend for speedup the distribution of static content

our backend application is hosted on  eks service for fault taulerance 

we use data base server as dynamodb latency less than 10 mili sec

we use alb to distribute the traffic accross servers

and also stores our secrets in secret manager

we provided additional security to application where we applied various rules to protect from web explits

## in that project 1stly we create cicd pipeline 

we use ci/cd pipeline for deployment, 1stly we take docker image from ecr and run that container and install npm tool, build the code of website, our dependency of code is store in package.json .the we create microfrontend by terraform, with the help of terraform we create infrastructure for frontend also
with that we host static webservices attach to cloudfront. 
we stored our state file remotely, 
then we take docker image from ecr, run on eks cluster, where

we use namespace to differniate project from others, also using node-port to access this service externally,  
this application is using java framework that's why it do not have plaform dependency.

the data delivery by using json language it is most secure, it act  as a interpreter between user and application.

this application is connected to database internally.

**now, accd to gitflow branching stratergy:**
code is 1st placed on development branch, is where we merges all our feature and release branch before merging with master branch.

after code is ready it passes throught release branch.

it allow to focus on release the code to master branch.

if master branch having any bugs in it then, that part of code is again put into hotfix branch.

then after code bug fixes in the **hotfix** branch it releases to master branch.

and in master branch our prod-ready-code will deploy on the prod servers.

in our frontend we use angular and backend we use java based **framework**.

# In this project my roles and responsibilities are:-

in the project my roles and responsibilities 

like, managing cicd pipeline 

perform the root cause analysis of production errors

responsible for application failure, downtime

integrate frontend with backend

ensure application should be highly accessible from anywhere 

creating and managing replication of application database

maintaining low as latency<10mili sec by dynamodb database

ensuring application should be fault taulerant and highly reliable by monitoring logs on cloudwatch

making sure that it do not face issue during version upgradation.

make sure the application is safe from web attacks, like ddos attack

make sure that backend credential have not being public.










