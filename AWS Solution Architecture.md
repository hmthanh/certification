# AWS Solution Architecture

## IAM

Policies : 

* AWS Managed : Using from AWS
* Customer Managed : create by user
* Inline policies : using only for specific role, can not share cross user or role

IAM Policies :

* Explicit DENY has precedence over any ALLOW

IAM AWS Managed Policies :

* Can using NotAction to deny all resource but still allow specific action on that resource

STS : 

* if we using assume role, it's will remove old role and replace with new one

AWS Directory :
    


