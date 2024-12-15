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

Step 1.  Create 3 EC2 Instance
![image](https://github.com/user-attachments/assets/02344fb0-167e-4a0e-a3ac-c2e1a57f2861)

SSH into the Instance
![image](https://github.com/user-attachments/assets/f613e1b3-310f-4cab-9121-750c14ecfa25)

Next Create the Kubernetes
![image](https://github.com/user-attachments/assets/78690ae3-3077-493d-b5fd-c11033eee2f6)

