#2048 App

Create fargate profile
eksctl create fargateprofile \
    --cluster demo-cluster \
    --region us-east-1 \
    --name alb-sample-app \
    --namespace game-2048
 
    Deploy the deployment, service and Ingress

    kubectl apply -f https://raw.githubusercontent.com/kubernetes-sigs/aws-load-balancer-controller/v2.5.4/docs/examples/2048/2048_full.yaml

    <img width="813" height="757" alt="image" src="https://github.com/user-attachments/assets/c498fe3d-20e3-458a-9f0d-3e08bd6d1d8e" />
