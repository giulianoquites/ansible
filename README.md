# Ansible
# Stop/Start instance AWS with AWX or TOWER.

# Export two: 
export AWS_ACCESS_KEY_ID=XXXXXXXXXXXXXXXXXXXXXXX  
export AWS_SECRET_ACCESS_KEY=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

echo $AWS_ACCESS_KEY_ID >> /etc/bashrc

echo $AWS_SECRET_ACCESS_KEY >> /etc/bashrc

# Install 
pip install boto boto3


