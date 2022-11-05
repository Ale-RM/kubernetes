#frist configure aws cli
#install eksctl
eksctl create cluster \
--name mio-cluster \
--region eu-central-1 \
--managed \
--node-type t2.medium \  # scegliere istanza idonea..
--nodes 2 \
--nodes-min 1 \
--nodes-max 3 
