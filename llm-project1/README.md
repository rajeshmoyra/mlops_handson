# mlops_handson
Explore MLOps and LLMOps features

# Setup Repository in local env
- [https://github.com/rajeshmoyra/mlops_handson.git](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github)
- 


# About the Repo
This repo is part of the LLMOps course by Manifold AI Learning,
Course link - https://www.manifoldailearning.in/courses/LLMOps-with-ChatGPT-Deploy-on-Production-65cb265ae4b086660d2836ae

Reach the Instructor at - https://www.linkedin.com/in/nachiketh-murthy/

For any support reach out to : support@manifoldailearning.in

# Help on FAST API

```
pip install "fastapi[all]"

uvicorn main:app --reload
```

# Test with Postman

URL - http://127.0.0.1:80/response
(POST)

```json
{
  "text": "Who is the hero of the story"
}

```

# Docker Commands

```
docker build -t llm-project1 .
docker run -d -p 8080:80 llm-project1
docker tag llm-project1 rajeshmoyra/llm-project1
docker push rajeshmoyra/llm-project1
```