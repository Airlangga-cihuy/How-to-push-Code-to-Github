# Code-Commit-Build-Deploy-Pipeline
- git config --global credential.helper '!aws codecommit credential-helper $@'
- git config --global credential.UseHttpPath true
- git clone https://github.com/aws-samples/aws-codedeploy-sample-tomcat.git
- cd aws-codedeploy-sample-tomcat
- git remote add origin https://github.com/Airlangga-cihuy/Project-2.git
- git remote -v
- git add .
-  git add -A
-  git status
-  git commit -m "Restructure project to repo root (remove profect2 folder & zip)"
-  git push origin master
-  git branch -M main
-  git push -u origin main
-  git push -u origin main --force




