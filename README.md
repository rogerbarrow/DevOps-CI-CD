# DevOps-CI-CD

![image](https://github.com/user-attachments/assets/88790539-a4b7-4084-b1d8-f58f7271e1ee)

A CI/CD pipeline is an automated sequence of steps that streamline the processes of Continuous Integration (CI) and Continuous Deployment/Delivery (CD) in software development. It is designed to help teams build, test, and deploy applications quickly, reliably, and consistently.

Key Components:
1. Continuous Integration (CI):
What it is: Automates the integration of code changes from multiple developers into a shared repository.
Purpose: Ensures that code changes are tested and merged frequently, minimizing integration challenges.
Example Steps in CI:
Developers push code to a version control system (e.g., GitHub).
The pipeline runs automated unit tests and static code analysis to verify the code.
Successful builds indicate that the code is ready for further stages.

2. Continuous Deployment/Delivery (CD):
What it is: Automates the process of deploying applications to staging or production environments.
Two Approaches:
Continuous Delivery: Ensures the application is always in a deployable state. Deployment to production still requires manual approval.
Continuous Deployment: Fully automates deployment to production, eliminating manual approval steps.

Step 1.  Create 1 EC2 Instance
![image](https://github.com/user-attachments/assets/b59c2bc5-a79b-426d-b02b-d8edd6d178c0)


SSH into the Instance


![image](https://github.com/user-attachments/assets/f613e1b3-310f-4cab-9121-750c14ecfa25)

Next install java which is required for Jenkins
![image](https://github.com/user-attachments/assets/38df7f2e-0141-4ae9-a7a3-a4b57b75cbc6)

![image](https://github.com/user-attachments/assets/0b7c7639-fe86-41ad-8d7a-549b094d054c)

Next Create the Kubernetes
![image](https://github.com/user-attachments/assets/78690ae3-3077-493d-b5fd-c11033eee2f6)
![image](https://github.com/user-attachments/assets/ecc2ce21-1de6-4255-ba2e-b77ffd6e9b97)


