# AWS ML Workflow for Scones Unlimited

### Deploying and Monitoring an Image Classification Model

This project focuses on building and deploying an image classification model using AWS SageMaker for Scones Unlimited, a logistics company specializing in scone deliveries. To simulate real-world challenges in image classification, we utilize the CIFAR dataset.

**Data Source**

The CIFAR dataset is publicly available and hosted by the University of Toronto: https://www.cs.toronto.edu/~kriz/cifar-100-python.tar.gz

**Project Scope**

ETL (Extract, Transform, Load)
- Extract data from a hosting service
- Transform data into a suitable format
- Load data into a production system
  
Model Training & Deployment
- Train an image classification model using AWS SageMaker
- Deploy the model as a SageMaker Endpoint
  
Workflow Automation
- Implement AWS Lambda functions
- Orchestrate the workflow with AWS Step Functions
  
Monitoring & Evaluation
- Use SageMaker Model Monitor for endpoint performance tracking
- Conduct performance analysis and visualization
  
**Conclusion**
This project delivers an event-driven ML workflow integrated into the Scones Unlimited production system. The SageMaker Estimator API was used for model deployment, while AWS Lambda and Step Functions automated the workflow. Additionally, SageMaker Model Monitor enabled real-time observation of the deployed model. Finally, a visualization was created to help stakeholders assess model performance over time.
