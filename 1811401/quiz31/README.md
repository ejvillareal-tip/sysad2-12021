# Install vstpd on Ubuntu and Centos using ansible-playbook

### Directory Structure
sysad2-12021/1811401/
└── quiz31
    ├── README.md
    ├── ansible.cfg
    ├── inventory
    ├── roles
    │   ├── configure_centos
    │   │   ├── README.md
    │   │   ├── defaults
    │   │   │   └── main.yml
    │   │   ├── files
    │   │   ├── handlers
    │   │   │   └── main.yml
    │   │   ├── meta
    │   │   │   └── main.yml
    │   │   ├── tasks
    │   │   │   └── main.yml
    │   │   ├── templates
    │   │   ├── tests
    │   │   │   ├── inventory
    │   │   │   └── test.yml
    │   │   └── vars
    │   │       └── main.yml
    │   ├── configure_ubuntu
    │   │   ├── README.md
    │   │   ├── defaults
    │   │   │   └── main.yml
    │   │   ├── files
    │   │   ├── handlers
    │   │   │   └── main.yml
    │   │   ├── meta
    │   │   │   └── main.yml
    │   │   ├── tasks
    │   │   │   └── main.yml
    │   │   ├── templates
    │   │   ├── tests
    │   │   │   ├── inventory
    │   │   │   └── test.yml
    │   │   └── vars
    │   │       └── main.yml
    │   ├── vsftpd_centos
    │   │   ├── README.md
    │   │   ├── defaults
    │   │   │   └── main.yml
    │   │   ├── files
    │   │   ├── handlers
    │   │   │   └── main.yml
    │   │   ├── meta
    │   │   │   └── main.yml
    │   │   ├── tasks
    │   │   │   └── main.yml
    │   │   ├── templates
    │   │   ├── tests
    │   │   │   ├── inventory
    │   │   │   └── test.yml
    │   │   └── vars
    │   │       └── main.yml
    │   └── vsftpd_ubuntu
    │       ├── README.md
    │       ├── defaults
    │       │   └── main.yml
    │       ├── files
    │       ├── handlers
    │       │   └── main.yml
    │       ├── meta
    │       │   └── main.yml
    │       ├── tasks
    │       │   └── main.yml
    │       ├── templates
    │       ├── tests
    │       │   ├── inventory
    │       │   └── test.yml
    │       └── vars
    │           └── main.yml
    ├── vsftpd.conf
    └── vsftpd.yaml

38 directories, 37 files
