---
title: "Tạo IAM policy"
date: "`r Sys.Date()`"
weight: 4
chapter: false
pre: "<b>4.</b>"
---

#### Tạo IAM Policy

1. Truy cập vào [AWS Management Console](https://console.aws.amazon.com/iam/)

   - Trong giao diện **IAM**, chọn **Policies**
   - Chọn **Create policy**

   ![Delegate access to the billing console](/images/00014.png?featherlight=false&width=90pc)

2. Trong tab **Visual editor**, 

   - Chọn **Choose a service**
   - Chọn **Billing**

   ![Delegate access to the billing console](/images/00015.png?featherlight=false&width=90pc)

3. Đối với **Select actions**,

   - Chọn **All Billing actions (aws-portal:*)**
   - Chọn **Next: Tags**

   ![Delegate access to the billing console](/images/00016.png?featherlight=false&width=90pc)

4. Chọn **Next: Review**

   ![Delegate access to the billing console](/images/00017.png?featherlight=false&width=90pc)

5. Trong trang **Review**,

   - Đối với **Name**, nhập **BillingViewAccess**
   - Sau đó, chọn **Create policy**

   ![Delegate access to the billing console](/images/00018.png?featherlight=false&width=90pc)
