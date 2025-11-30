# Automated Code Review
This repository serves as the source code repository for testing a fully automated Code Review system. Creating or updating a Pull Request (PR) or Merge Request (MR) in this repo triggers the entire workflow.

The system uses a serverless workflow engine (n8n) hosted on a managed database (NHost) and utilizes the OpenAI API to analyze and critique code changes, posting the review directly back to this repository.
