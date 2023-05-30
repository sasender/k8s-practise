# k8s-practise![image](https://user-images.githubusercontent.com/78895362/170200440-3082aafd-303b-48bd-b706-b22eed99b4bc.png)

![image](https://user-images.githubusercontent.com/78895362/170200618-cc53de93-45fb-41ed-a25b-d3aa100b6755.png)
 worker node policys
 
 ![image](https://user-images.githubusercontent.com/78895362/170200784-369bed97-f691-4f48-a44b-5c6d49d769ad.png)
clusyter creation

![image](https://github.com/sasender/k8s-practise/assets/78895362/880f95e7-9eea-4586-a921-097024be661f)

ecs-worker-node-policy 
![image](https://github.com/sasender/k8s-practise/assets/78895362/63fee8f2-b1b2-4d17-a0f3-597e01727b63)

ecr-policy

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": [
                "ecr:BatchCheckLayerAvailability",
                "ecr:BatchGetImage",
                "ecr:GetDownloadUrlForLayer",
                "ecr:GetAuthorizationToken"
            ],
            "Resource": "*"
        }
    ]
}


