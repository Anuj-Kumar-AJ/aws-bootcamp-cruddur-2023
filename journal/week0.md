# Week 0 — Billing and Architecture [link](https://www.youtube.com/watch?v=SG8blanhAOg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=12 )

--------------------------------------------------------------------------

#  AWS security consideration Best Practices for cloud [link](https://www.youtube.com/watch?v=4EMWBYVggQI&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=15 )


## What is cloud Security ?

- cyber security which protect the data application and services which are resides inside the cloud from both external and internal threads.

## why  do we care about Cloud Security

- Lets say if by any way your AWS account get comprimised, then what make your account to reduce the impact by hacker. These are the few practices we indulged to reduce the impack

- It protect the different types of cloud service like networks, application in cloud environment against data theft

- As most of the error done by humans, this is same for clod environment too, so cloud security reduces the data leak.


## lets add security to our aws account


### Add the MFA (multi factor authentication) for the root account

- Root user is the most Powerful user in your AWS environment, lets say if you seen many animes or RPG games, root user power is equvlent to GOD LEVEL , it can create, modify, delete user. can change any permissions or policies of all your account. 
- So just imagin if the hacker comprimises your root user , he can change anything in your environment.






### Creating a  organizational unit

- Initially user can create only one AWS account, and as there are many limitation for number of services that can be performed in one AWS account, people starts complaining, So after lots of requests, AWS allow creating multiple aWS account per user
- you can think about these AWS account as they are a world in itself, they dont communicate with each other, well not when we dont explecetly try to make connection between them. So for example if in 1 aws account there is Netflix and another one runs Amazon Prime, these two dont communicate by themself, like they are isolated.
- But this high number of AWS account leads to problem in maintanance, whihc leads the AWS to create organizational unit



### Enabeling AWS Cloud Trail

- AWS Cloudtrail is management and governance tools. But what does it means?
- THis CloudTrail contain every api call made to every resoures in the AWS account, by user or by any Application which can be used to see if any perticulatr actions is performed on AWS account.


### Creating IAM users


- There are 4 types of users in AWS
    1. root user
    2. IAM user
    3. IAM Identity Center USer
    4. AWS Builder ID user

1. root user --> The root user has complete access to all AWS services and resources in the AWS account.

2. IAM user --> These users are the identities within your AWS account with specific custom permissions. IAM users require a name and password which they use to sign in to the AWS Management Console

3. IAM Identity Center USer -->  A user in IAM Identity Center signs in through the AWS access portal. The AWS access portal, which includes a specific sign-in URL, is provided to you by your administrator or help desk employee. If you created a user in IAM Identity Center for your AWS account, an invitation to join IAM Identity Center was sent to that account's email address. The specific sign-in URL is included in the email invitation. The users in IAM Identity Center are not able to sign in through the AWS Management Console. 

4. AWS Builder ID user --> As an AWS Builder ID user, you specifically sign in to the AWS service or tool that you want to access. An AWS Builder ID user complements any AWS account you already have or want to create. An AWS Builder ID represents you as a person, and you can use it to access AWS services and tools without an AWS account. You also have a profile where you can see and update your information.

### Creating IAM roles


## enable aws organization SCP (service control polocy)

- 

# Spend Consideration [link](https://www.youtube.com/watch?v=OVw3RrlP-sI&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=13 )

# Created Billing Alarm [link](https://www.youtube.com/watch?v=OdUnNuKylHg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=14 )
# created AWS Budget  [link](https://www.youtube.com/watch?v=OdUnNuKylHg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=14 )


# Cruddur  Conceptual Diagram [Link](./../_docs/assets/CruddurConceptualDiagram.jpeg)

# Cruddur Architecture Diagram [Link](./../_docs/assets/CruddurArchitectureDiagram.png)




# learnd how to use cloud shell [link](https://www.youtube.com/watch?v=OdUnNuKylHg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=14)

# learned about AWS CLI [link](https://www.youtube.com/watch?v=OdUnNuKylHg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=14 )
































































