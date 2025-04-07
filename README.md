# AWS-Aware---Knowledge-Based-Assessment-101-BASICS-

IAM- Identity and access management.
root account- Our AWS account is the root account.
It aws sys admin account.

MFA is important for this ->multi factor authentication

For root account we can only perform the following:

1. modify user details
2. change AWS support plan
3. Change AWS payment option
4. Close AWS account.

IAM is gloabal-> 
Usually We need to choose a region but root account is Global.
Password rotation policy -> password expired and rules


Root user -> mail account
power user ->admin account->cant odify licence and billing details
Iam -> can access only on permissions that we have granted.

MFA -> there are differnet types of divices where we can perform MFA

IAM - Identity access management

Here in this IAM we can provide different types of access and roles to the users.

In Iam we will manage every kind of access to the different users.

1. Groups - We can create different groups and add differnt types of access to the group. Users who are in the group can access the same.
2. Users - Here we need to create different users and create there account to login.
3. Roles - We can create different types of roles and add different types of permissions to the roles.
4. Policies - There are alrady preexisting policies for which the policy differs on diffrent types of roles like admin roles and every access we can check json format and make changes to it.
In AWS there are 18 distinct regions and 55 availability zones
Each region has 3 availability zones.

In case of a disaster if one avalability region is crashed remaining 2 aZ will work in low latency

S3 buckets-

Here in this bucket we can store allkind of data and files that are required.

there are different storage classes in s3:
1. standard s3: Where it will store the data in 3 availability zones, it was highly durable and available. it was used in production.
2. s3_IA standard: Infrequent access standard where it was also available in 3AZ
3.s3_one_zone_IA: only avalable in one OZ
4. aws Glacier:long term storage.We need to store long term storage data in this glacier.there are multiple OZ.


