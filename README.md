# airflow-eks-docker
Airflow Docker image used in AWS EKS cluster

Hello, from README.md.

## Build Docker image
``` 
docker build -t airflow-eks-docker .
```

## Run Docker container
```
docker run -d -p 8080:8080 airflow-eks-docker
```

