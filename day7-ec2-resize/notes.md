# Check instance status
aws ec2 describe-instances --filters Name=tag:Name,Values=nautilus-ec2

# Stop instance
aws ec2 stop-instances --instance-ids <instance-id>

# Change instance type
aws ec2 modify-instance-attribute \
--instance-id <instance-id> \
--instance-type "{\"Value\": \"t2.nano\"}"

# Start instance
aws ec2 start-instances --instance-ids <instance-id>

# Verify instance type
aws ec2 describe-instances --filters Name=tag:Name,Values=nautilus-ec2

