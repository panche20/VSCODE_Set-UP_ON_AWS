# VSCODE_Set-UP_ON_AWS

Connect to VS Code using below code snippet:

'''
Host myweb-app\
  HostName ec2-16-171-194-81.eu-north-1.compute.amazonaws.com\
  IdentityFile \Users\panch\.ssh\demo-aws-key.pem\
  User ubuntu\
  Port 22\
  IdentitiesOnly yes\
  StrictHostKeyChecking accept-new\
'''
