


## Prerequisites
  * You should have kubectl installed


### First, get the "access-key" and the "secret-key"
 1.Navigate IAM-> users -> select  the user -> security credentials 
 2. Create access key
 3. Copy or store some where the Access key ID and secret-key
 
### install "aws-cli" and  "aws-iam-authenticator". For the last follow the link:
  1 . https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authenticator.html
  
### Create a kubeconfig for Amazon EKS

    `$ aws --version`

    `$ aws sts get-caller-identity`

    `$ aws eks update-kubeconfig --region region-code --name cluster-name`

    
    More details can be found in links bellow:
    
    * https://aws.amazon.com/premiumsupport/knowledge-center/eks-cluster-connection/
    * https://docs.aws.amazon.com/eks/latest/userguide/create-kubeconfig.html
 
