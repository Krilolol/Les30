# Les30

# AWS - Advanced Terraform

## 1. Створив три модулі в папці modules: vpc, subnet, ec2.
### - Виконав команду "terraform init", "terraform fmt", "terraform validate" та "terraform apply".
![1](https://github.com/user-attachments/assets/88433ae8-633e-49ed-8ad8-33539e60b217)
![2](https://github.com/user-attachments/assets/fa4e8577-8e88-4bae-8518-d910a15abde0)
![3](https://github.com/user-attachments/assets/fce4618c-494c-4841-8492-b75bbdfaddde)

### - Видалив створені ресурси командою "terraform destroy".

## 2. Створив в AWS console S3 bucket "bro-bucket1010".
### - Додав ресурс S3 bucket до main.tf.
### - Виконав команду terraform import aws_s3_bucket.imported_bucket bro-bucket1010.
![4](https://github.com/user-attachments/assets/c236178b-e288-4ab6-b051-091e3715ca6c)


### - Перевірив атрибути ресурсу "terraform show".
![5](https://github.com/user-attachments/assets/ca22dc87-0c00-4d6b-a2b3-ca0e5dc7c096)


### - Перевірив план "terraform plan".
![6](https://github.com/user-attachments/assets/ffd52530-f133-4d15-b04a-091f161df2dc)


### - Виконав "terraform apply".
![7](https://github.com/user-attachments/assets/c2f1aaf7-a40a-4e1c-9ebc-01973ec6d6d9)


## 3. Видалив всю інфраструктуру, в тому числі і S3 bucket, за допомогою команди "terraform destroy".
