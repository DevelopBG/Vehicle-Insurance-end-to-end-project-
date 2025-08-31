# MLOps Project on Vehicle Insurance Pipeline
This project is designed to demonstrate a robust end-to-end pipeline for managing vehicle insurance data. It showcases how real-world machine learning projects are structured, from data processing to model deployment, with a focus on automation and scalability.

- The project leverages the following technologies and services:

- Programming & ML: Python, Machine Learning (Random Forest Classification)

- Database: MongoDB for storing and managing data

- Containerization & Deployment: Docker, AWS EC2

- CI/CD Automation: Git, GitHub Actions

- Cloud Services: AWS IAM for access management, AWS S3 for storage, AWS ECR for container registry

Follow along to explore project setup, data processing, model deployment, and CI/CD automation, all designed to give recruiters and visitors a clear view of your ability to handle production-ready ML pipelines.

## 📁 Project Setup and Structure
### Step 1:

- To create the required folder structure and palceholder, run the blow command on the terminal
  ```base
  $python template.py
  ```
### Step 2: Virtual Environment and Dependencies
- To manage the setup of importing local modules or packages, `setup.py` and `pyproject.toml` files have been configured.
- Creating virtual environment and requirements installation:
  ```
  conda create -n vehicle python=3.12 -y
  conda activate mlops
  pip install -r requirements.txt
  ```
- To verify if all the packages are installed properly
  ```
  pip list
  ```



