# CD12352 - Infrastructure as Code Project Solution
 
### AWS Configuration

1. Use this command to set AWS Access Key, AWS Secret Key, Default Region and Default output format
   ```
   aws configure
   ```

2. Use this command to set AWS Session Token
   ```
   aws configure set aws_session_token
   ```

### Create AWS Resource - CloudFormation

1. Go to starter folder
2. Update parameters in each stack(network, udagram)
3. Create Network
   ```
   source create_stack.sh create network
   ```
4. Create WebApp Server
   ```
   source create_stack.sh create udagram
   ```

### Delete Resource

1. Go to starter folder
2. Update parameters in each stack(network, udagram)
3. Delete WebApp Server
   ```
   source create_stack.sh delete udagram
   ```
4. Delete network
   ```
   source create_stack.sh delete network
   ```
 
## Other considerations
http://udagra-loadb-7cukoztwrxb8-1347515414.us-east-1.elb.amazonaws.com/