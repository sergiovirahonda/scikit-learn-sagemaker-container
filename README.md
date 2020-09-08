# scikit-learn-sagemaker-container
This project is about making things simpler when deploying custom models to SageMaker through ECR. Instead of using the suggested AWS template, I've followed the AWS suggestions to build a container fully compatible with ECR, but made simple. As you may guest, it follows the same structure that AWS asks, but the training process is made in a very simple way. For now it contains a vectorizer and a SVC model to inference wheter or not an email body is Spam or not.

It's completely ready to be uploaded to ECR. Only change what you need to change to adapt it to your needs and that's it.
