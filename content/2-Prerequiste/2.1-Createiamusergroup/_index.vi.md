---
title: "Tạo IAM user group"
date: "`r Sys.Date()`" 
weight: 1
chapter: false
pre: "<b>2.1</b>"
---

1. **Truy cập vào AWS Management Console**
   - Tìm IAM
   - Chọn IAM

   ![Delegate access to the billing console](/images/0004.png?featherlight=false&width=90pc)

2. **Trong giao diện IAM**
   - Chọn **Users**
   - Chọn **Add users**

   ![Delegate access to the billing console](/images/0005.png?featherlight=false&width=90pc)

3. **Trong trang Details**
   - Đối với **Administrator**
   - Chọn **AWS Management Console access**
   - Chọn **Custom password**
   - Đặt password mà bạn muốn
   - Bỏ chọn **User must create a new password at next sign-in**
   - Chọn **Next: Permissions.**

   ![Delegate access to the billing console](/images/0006.png?featherlight=false&width=90pc)

4. **Trong trang Permissions**
   - Chọn **Add user to group**
   - Chọn **Create group**

   ![Delegate access to the billing console](/images/0007.png?featherlight=false&width=90pc)

5. **Trong giao diện Create group**
   - Nhập **Administrators** đối với **Group name**
   - Chọn **AdministratorAccess**
   - Chọn **Create group**

   ![Delegate access to the billing console](/images/0008.png?featherlight=false&width=90pc)

6. **Trong giao diện Add user**
   - Chọn **Next: Tags**

   ![Delegate access to the billing console](/images/0009.png?featherlight=false&width=90pc)

7. **Chọn Next: Review**

   ![Delegate access to the billing console](/images/00010.png?featherlight=false&width=90pc)

8. **Chọn Create user.**

   ![Delegate access to the billing console](/images/00011.png?featherlight=false&width=90pc)

9. **Download thông tin truy cập và lưu trữ lại.Chọn Close**

   ![Delegate access to the billing console](/images/00012.png?featherlight=false&width=90pc)

10. **Hoàn thành tạo user và user group.**

   ![Delegate access to the billing console](/images/00013.png?featherlight=false&width=90pc)
