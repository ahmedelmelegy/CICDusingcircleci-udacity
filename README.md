Here is the list of files and corresponding exercises. 
```bash
├── ansible
│   ├── configure-server.yml
│   ├── deploy-backend.yml
│   ├── inventory.txt
│   └── roles
│       ├── configure-prometheus-node-exporter
│       │   ├── files
│       │   │   └── node_exporter.service
│       │   └── tasks
│       │       └── main.yml
│       ├── configure-server
│       │   └── tasks
│       │       ├── main.yml
│       │       └── readme.md
│       └── deploy
│           ├── files
│           │   └── readme.md
│           └── tasks
│               ├── main.yml
│               └── readme.md
├── config-sample.yml
├── config.yml
└── files
    ├── backend.yml
    ├── cloudfront.yml
    └── frontend.yml
```
> **Note**: When you attempt any CircleCI exercise, you should comment out the Jobs and Workflows from other exercises. This will ensure that you do not end up creating unnecessary EC2, S3, CloudFront resources in your AWS console. 
