
```
{
  "ipcMode": null,
  "executionRoleArn": "arn:aws:iam::501488482379:role/mythical-mysfits-fargate-EcsServiceRole-5M7NIHB7964Q",
  "containerDefinitions": [
    {
      "dnsSearchDomains": [],
      "logConfiguration": {
        "logDriver": "awslogs",
        "options": {
          "awslogs-group": "/ecs/Monolith-Definition-mythical-mysfits-fargate",
          "awslogs-region": "us-west-2",
          "awslogs-stream-prefix": "ecs"
        }
      },
      "entryPoint": [],
      "portMappings": [
        {
          "hostPort": 80,
          "protocol": "tcp",
          "containerPort": 80
        }
      ],
      "command": [],
      "linuxParameters": null,
      "cpu": 0,
      "environment": [
        {
          "name": "DDB_TABLE_NAME",
          "value": "Table-mythical-mysfits-fargate"
        },
        {
          "name": "UPSTREAM_URL",
          "value": "alb-mythical-mysfits-fargate-1256741750.us-west-2.elb.amazonaws.com"
        }
      ],
      "resourceRequirements": null,
      "ulimits": null,
      "dnsServers": [],
      "mountPoints": [],
      "workingDirectory": null,
      "secrets": null,
      "dockerSecurityOptions": [],
      "memory": null,
      "memoryReservation": null,
      "volumesFrom": [],
      "image": "501488482379.dkr.ecr.us-west-2.amazonaws.com/mythic-mono-m6ie9vpbrlif:latest",
      "disableNetworking": null,
      "interactive": null,
      "healthCheck": null,
      "essential": true,
      "links": [],
      "hostname": null,
      "extraHosts": null,
      "pseudoTerminal": null,
      "user": null,
      "readonlyRootFilesystem": null,
      "dockerLabels": null,
      "systemControls": null,
      "privileged": null,
      "name": "monolith-service"
    }
  ],
  "placementConstraints": [],
  "memory": "512",
  "taskRoleArn": "arn:aws:iam::501488482379:role/mythical-mysfits-fargate-ECSTaskRole-1VWZ38EN4WW12",
  "compatibilities": [
    "EC2",
    "FARGATE"
  ],
  "taskDefinitionArn": "arn:aws:ecs:us-west-2:501488482379:task-definition/Monolith-Definition-mythical-mysfits-fargate:2",
  "family": "Monolith-Definition-mythical-mysfits-fargate",
  "requiresAttributes": [
    {
      "targetId": null,
      "targetType": null,
      "value": null,
      "name": "com.amazonaws.ecs.capability.docker-remote-api.1.17"
    },
    {
      "targetId": null,
      "targetType": null,
      "value": null,
      "name": "ecs.capability.execution-role-ecr-pull"
    },
    {
      "targetId": null,
      "targetType": null,
      "value": null,
      "name": "com.amazonaws.ecs.capability.docker-remote-api.1.18"
    },
    {
      "targetId": null,
      "targetType": null,
      "value": null,
      "name": "ecs.capability.task-eni"
    },
    {
      "targetId": null,
      "targetType": null,
      "value": null,
      "name": "com.amazonaws.ecs.capability.ecr-auth"
    },
    {
      "targetId": null,
      "targetType": null,
      "value": null,
      "name": "com.amazonaws.ecs.capability.task-iam-role"
    },
    {
      "targetId": null,
      "targetType": null,
      "value": null,
      "name": "ecs.capability.execution-role-awslogs"
    },
    {
      "targetId": null,
      "targetType": null,
      "value": null,
      "name": "com.amazonaws.ecs.capability.logging-driver.awslogs"
    },
    {
      "targetId": null,
      "targetType": null,
      "value": null,
      "name": "com.amazonaws.ecs.capability.docker-remote-api.1.19"
    }
  ],
  "pidMode": null,
  "requiresCompatibilities": [
    "FARGATE"
  ],
  "networkMode": "awsvpc",
  "cpu": "256",
  "revision": 2,
  "status": "ACTIVE",
  "volumes": []
}

```
