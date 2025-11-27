AWS CodePipeline – Static Website Deployment

This project shows how to deploy a static website automatically using AWS CodePipeline and Amazon S3.
Whenever you push code to GitHub, the pipeline updates the live website automatically.

🚀 Live Website

http://code-pipeline-bucket1234.s3-website.ap-south-1.amazonaws.com

📸 Screenshots
1. CodePipeline Execution

<img width="1919" height="973" alt="Screenshot 2025-11-27 160052" src="https://github.com/user-attachments/assets/75ee2108-b8d3-4a75-ab5e-5b21187d0f72" />


2. Deployed Website Screenshot
<img width="1919" height="972" alt="Screenshot 2025-11-27 154947" src="https://github.com/user-attachments/assets/438293a4-d402-463f-a7cb-3b62d4354618" />

🛠️ Pipeline Stages
Source Stage

Pulls latest code from GitHub using GitHub App integration.

Deploy Stage

Uploads your static files to an S3 bucket configured for static website hosting.

🌐 Technology Stack

AWS S3

AWS CodePipeline

GitHub
