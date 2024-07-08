# CD12352 - Infrastructure as Code Project Solution
# Tuong Vo
## Spin up instructions
TODO
# 1. deploy network components
./run.sh deploy us-east-1 network network.yml network-parameters.json
# 2. deploy bastion server
./run.sh deploy us-east-1 bastion bastion.yml bast-param.json
# 3. deploy the rest of the infrastructure
./run.sh deploy us-east-1 udagram udagram.yml udagram-parameters.json
## Tear down instructions
TODO
# 1. empty the S3 buckets
# 2. delete the infrastructure
./run.sh delete us-east-1 udagram
# 3. delete bastion server
./run.sh delete us-east-1 bastion 
# 4. delete network components
./run.sh delete us-east-1 network 
## Other considerations
TODO (optional)
