Live Site: https://meghanaadithi.github.io/job-board-frontend/

This project is a fully functional Job Board Application where:

Employers can post jobs
Candidates can apply with name, email, and resume upload
Admins can view all submitted applications in a secure dashboard
All backend services run entirely on AWS Lambda + API Gateway + S3
The frontend is a React + Vite application deployed on GitHub Pages

Action	                     Method	Endpoint
Post a job	                  POST	/postjob
Apply to job	                POST	/applyjob
List all applications	        GET	/listapplications
