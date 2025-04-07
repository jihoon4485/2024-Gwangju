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


