# step-01-cloudformation-script
# create the stack accoding to parameters
# we need to add key-pair,vpc-id,and two subnets,otherwise it won't work
# it creates two Ec2-instances with Nginx web server,security group with 22,443,3000 ports,autoscaling group,target groups, aplication load balencer.
# browse instance_ip you will get nginx.
# browse loadbalencer end point you will get the same(if you didnt get nginx with loadbalencer endpoint please edit your loadbalencer security group) 
