# AWS-CI-CD-CodeDeploy-CodePipeline
https://www.youtube.com/watch?v=8mPm7jolnVk

EC2
key 
chmod 400 AWS-CI-CD-CodeDeploy-CodePipeline.pem
mv AWS-CI-CD-CodeDeploy-CodePipeline.pem /Users/mb/.ssh

---
EC2
セキュリティグループ
sg-0770912cec922c392 - launch-wizard-1
アウトバウンドのルールを編集
HTTP
TCP
80

Anywhere-IPv4
0.0.0.0/0
---

elastic IP つけないとインターネット繋がらない
Elastic IP アドレス


#一度接続を切るとIPが変わるのでコマンドも変わることに注意

ssh -i "AWS-CI-CD-CodeDeploy-CodePipeline.pem" ec2-user@ec2-174-129-137-63.compute-1.amazonaws.com

<img width="833" alt="スクリーンショット 2023-10-17 11 59 06" src="https://github.com/nikotamajapan/AWS-CI-CD-CodeDeploy-CodePipeline/assets/71979704/d9d0f735-a05b-42ee-a011-fce959ca76b4">



remote SSH on VScode

ssh -i "/Users/mb/.ssh/AWS-CI-CD-CodeDeploy-CodePipeline.pem" ec2-user@ec2-174-129-137-63.compute-1.amazonaws.com

<img wi<img width="887" alt="スクリーンショット 2023-10-17 12 07 46" src="https://github.com/nikotamajapan/AWS-CI-CD-CodeDeploy-CodePipeline/assets/71979704/cbf57872-66d6-435e-b2bd-cfe49602b466">
dth="743" alt="スクリーンショット 2023-10-17 12 06 17" src="https://github.com/nikotamajapan/AWS-CI-CD-CodeDeploy-CodePipeline/assets/71979704/b9f0e85d-c91d-4a08-86b2-0128655db913">

![Uploading スクリーンショット 2023-10-17 12.07.46.png…]()














Q EC2 を作ったらvpcは自動的に作られる？
yes
