# Usage

```console
├── LICENSE
├── README.md
├── defaults
│   └── main.yml
├── docs
│   └── performances.txt
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── tasks
│   ├── configure.yml
│   ├── main.yml
│   ├── performances.yml
│   └── secure-installation.yml
├── templates
│   ├── logrotate.j2
│   ├── my.cnf.j2
│   ├── performances.cnf.j2
│   └── user-my.cnf.j2
└── vars
    └── Debian.yml
```
```yaml
roles:
  - { role: ar-mysql-server }
```
