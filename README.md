# Code-Commit-Build-Deploy-Pipeline
- git config --global credential.helper '!aws codecommit credential-helper $@'
- git config --global credential.UseHttpPath true
- git clone https://github.com/aws-samples/aws-codedeploy-sample-tomcat.git
- cd aws-codedeploy-sample-tomcat
- git remote add codecommit https://git-codecommit.us-east-1.amazonaws.com/v1/repos/Commit-lks-01
- git remote -v
- git add .
- git push codecommit --all
- git push codecommit --tags



