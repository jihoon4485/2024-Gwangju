# 2024-Gwangju

### ssh port 변경
/etc/ssh/sshd_config

### EKS Immersion Day
https://catalog.workshops.aws/ecs-immersion-day/en-US/30-basic/200-task-definition

### ECS Exec 활성화

```bash
aws ecs update-service --cluster <클러스터이름> --service <서비스이름> --enable-execute-command
```

### ECS 컨테이너 접속

```bash
aws ecs execute-command --cluster <클러스터이름> \
--task <작업ID> \
--container <컨테이너이름> \
--interactive \
--command "/bin/sh"
```

### VPN
https://catalog.us-east-1.prod.workshops.aws/workshops/d903ff2b-f043-4126-a4f5-64a7cc2922ec/en-US/3-aws-client-vpn
https://dev.classmethod.jp/articles/attempt-to-access-private-subnet-ec2-with-client-vpn/

- https://catalog.us-east-1.prod.workshops.aws/workshops/7d2d52a0-7568-4b24-be49-08dab4bfa128/en-US
- https://aws.youngwjung.com/week3/assignment
- https://catalog.us-east-1.prod.workshops.aws/workshops/63320e83-6abc-493d-83d8-f822584fb3cb/en-US/eventbridge
- https://www.linkedin.com/posts/jaiswal-anuj_aws-sqs-eventbridge-activity-7254695768329011201-fEu0/
- https://aws.youngwjung.com/week2/assignment
- https://github.com/aws-samples/event-driven-autoscaling-using-podidentity-and-keda
- https://catalog.workshops.aws/cfn101/en-US
- https://catalog.us-east-1.prod.workshops.aws/workshops/10141411-0192-4021-afa8-2436f3c66bd8/en-US
- https://catalog.us-east-1.prod.workshops.aws/workshops/41c5a1b6-bd3e-41f4-bd46-85ab7dc6dad4/en-US
- https://terraform.youngwjung.com/
- https://catalog.workshops.aws/getting-started-with-com/en-US
- https://www.wellarchitectedlabs.com/
- https://github.com/aws-samples/systems-manager-automation-for-operating-multicloud-workloads
- https://aws.youngwjung.com/week7/hands-on-labs
