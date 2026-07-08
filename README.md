# PKL Task-1 
### Grafana - Prometheus - Node Exporter

purpose
- contains ansible roles and playbooks that i executed to complete the task

tree!!!!
```
├── ansible.cfg
├── inventory.ini
├── roles
│   ├── app
│   │   └── tasks
│   │       └── main.yml
│   ├── common
│   │   ├── tasks
│   │   │   └── main.yml
│   │   ├── templates
│   │   │   └── node_exporter.service.j2
│   │   └── vars
│   │       └── main.yml
│   └── monitoring
│       ├── tasks
│       │   └── main.yml
│       ├── templates
│       │   ├── prometheus.service.j2
│       │   └── prometheus.yml.j2
│       └── vars
│           └── main.yml
└── setup.yml
```