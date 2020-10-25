# Jenkins & Docker Container to ECR
---
Jenkins를 사용해 간단한 Python Django 웹 서버를 Docker Container로 빠르게 배포합니다. Bitbucket을 사용하며 배포를 위한 Jenkinsfile 에는 Amazon Elastic Container Registry를 생성하는 함수를 정의하고 그 함수에서 Python boto3로 작성된 ecr.py 스크립트를 실행합니다.

### flow
![ex_screenshot](/flow.png)

### 
