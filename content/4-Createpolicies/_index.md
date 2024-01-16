---
title: "Create IAM Policy"
date: "`r Sys.Date()`"
weight: 4
chapter: false
pre: "<b>4.</b>"
---

#### Create IAM Policy

1. Go to [AWS Management Console](https://console.aws.amazon.com/iam/)

   - In the **IAM** interface, select **Policies**
   - Select **Create policy**

![Delegate access to the billing console](/images/00014.png?featherlight=false&width=90pc)

2. In the **Visual editor** tab,

   - Select **Choose a service**
   - Select **Billing**

![Delegate access to the billing console](/images/00015.png?featherlight=false&width=90pc)

3. For **Select actions**

   - Select **All Billing actions (aws-portal:*)**
   - Select **Next: Tags**

![Delegate access to the billing console](/images/00016.png?featherlight=false&width=90pc)

4. Select **Next: Review**

![Delegate access to the billing console](/images/00017.png?featherlight=false&width=90pc)

5. In the **Review** page,

   - For **Name**, enter **BillingViewAccess**
   - Then, select **Create policy**

![Delegate access to the billing console](/images/00018.png?featherlight=false&width=90pc)
