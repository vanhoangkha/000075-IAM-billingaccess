---
title : "Create IAM user group"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---

1. Access to AWS Management Console

   - Find IAM
   - Select IAM

![Delegate access to the billing console](/images/0004.png?featherlight=false&width=90pc)

2. In the IAM . interface

   - Select **Users**
   - Select **Add users**

![Delegate access to the billing console](/images/0005.png?featherlight=false&width=90pc)

3. In the **Details** page

   - For **Administrator**
   - Select **AWS Management Console access**
   - Select **Custom password**
   - Set the password you want
   - Uncheck **User must create a new password at next sign-in**
   - Select **Next: Permissions.**

![Delegate access to the billing console](/images/0006.png?featherlight=false&width=90pc)

4. In **Permissions** page

   - Select **Add user to group**
   - Select **Create group**

![Delegate access to the billing console](/images/0007.png?featherlight=false&width=90pc)

5. In the Create group interface

   - Enter **Administrators** for **Group name**
   - Select **AdministratorAccess**
   - Select **Create group**

![Delegate access to the billing console](/images/0008.png?featherlight=false&width=90pc)

6. In the **Add user** interface

    - Select **Next: Tags**

![Delegate access to the billing console](/images/0009.png?featherlight=false&width=90pc)

7. Select **Next: Review**

![Delegate access to the billing console](/images/00010.png?featherlight=false&width=90pc)

8. Select **Create user.**

![Delegate access to the billing console](/images/00011.png?featherlight=false&width=90pc)

9. Download access information and save it. Select **Close**

![Delegate access to the billing console](/images/00012.png?featherlight=false&width=90pc)

10. Finish creating user and user groups.

![Delegate access to the billing console](/images/00013.png?featherlight=false&width=90pc)