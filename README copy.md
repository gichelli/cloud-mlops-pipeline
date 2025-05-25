# Cloud MLOps Pipeline with AKS, Azure DevOps & MLflow

This project demonstrates a scalable and automated MLOps pipeline for deploying machine learning models using **Azure Kubernetes Service (AKS)**, **Azure DevOps**, and **MLflow** for experiment tracking.

## Tools & Technologies
- **Azure DevOps** for CI/CD pipelines
- **Azure Kubernetes Service (AKS)** for scalable deployments
- **MLflow** for model tracking and registry
- **Docker + Kubernetes** for containerized deployment
- **Python** (Scikit-learn / PyTorch)

## Key Features
- CI/CD pipeline for ML models using Azure DevOps
- Auto-deployment to AKS clusters
- Experiment tracking using MLflow
- Inference endpoint with RESTful API
- Versioned and reproducible model deployment

## Architecture

![Architecture](architecture/mlops_pipeline_architecture.png)

## Folder Structure

| Folder | Description |
|--------|-------------|
| `src/` | Training, deployment, and inference scripts |
| `mlflow/` | Setup and usage of MLflow tracking |
| `azure_devops/` | YAML pipelines and AKS deployment templates |
| `notebooks/` | Optional Jupyter notebooks for EDA and preprocessing |

```bash
cloud-mlops-pipeline/
├── README.md
├── architecture/
│   └── mlops_pipeline_architecture.png (placeholder)
├── src/
│   ├── train_model.py
│   ├── deploy_model.py
│   ├── inference_service.py
│   └── requirements.txt
├── mlflow/
│   └── mlflow_tracking_setup.md
├── azure_devops/
│   ├── pipeline.yml
│   └── aks_deployment_template.yaml
└── notebooks/
    └── data_preprocessing.ipynb
```

## Example Command

```bash
python src/train_model.py --data data/train.csv --experiment cloud-mlops-demo
```

## Contact
**Gissella Gonzalez (Gichelli)**  
[LinkedIn](https://www.linkedin.com/in/gissellagonzalez)  
ggonza18@gmu.edu
