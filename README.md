# digitaltolk-test
Project Structure 

digitaltolk-test/
├── datetime-api/

│   ├── main.py

│   ├── requirements.txt

│   ├── Dockerfile

├── terraform-ec2-bastion/

│   ├── main.tf

│   ├── variables.tf

│   ├── outputs.tf
![image](https://github.com/user-attachments/assets/7971d862-ce20-4463-9e09-df8b66ae9f07)


# DigitalTolk Take-Home Test

This repository contains the solutions for the DigitalTolk take-home test. It includes:
1. A Dockerized Python API that displays the current date and time.
2. A Terraform configuration to set up an EC2 instance as a bastion host.

## Contents
- `datetime-api/`: Python API project with Docker support.
- `terraform-ec2-bastion/`: Terraform files to provision an EC2 bastion host.

## How to Use

### Python API
1. Navigate to the `datetime-api` directory.
2. Build and run the Docker container:
   ```bash
   docker build -t datetime-api .
   docker run -d -p 8000:8000 datetime-api

   # Verify
   http://127.0.0.1:8000/datetime
  ![image](https://github.com/user-attachments/assets/78d14da1-e8ff-421a-a6b7-3083623b9b80)



