├── ansible.cfg             ### 4. Exercise: Config and Deployment
├── bucket.yml              ### 7. Exercise: Promote to Production
├── cloudfront.yml
├── error.html
├── index.html
├── inventory.txt           ### 2. Exercise: Remote Control Using Ansible
├── main1.yml               ### 1. Classroom Demo: Design an Ansible Playbook 
├── main2.yml               ### 1. Exercise: Define Ansible Playbook 
├── main3.yml               ### 2. Classroom Demo: Remote Control Using Ansible
├── main4.yml               ### 2. Exercise: Remote Control Using Ansible
├── roles                   ### Ansible exercises
│   ├── apache              ### 2. Classroom Demo: Remote Control Using Ansible
│   │   ├── files
│   │   │   └── index.html
│   │   └── tasks
│   │       └── main.yml
│   ├── configure-server    ### 1. Classroom Demo: Design an Ansible Playbook 
│   │   └── tasks
│   │       └── main.yml
│   ├── prepare             ### 2. Classroom Demo: Remote Control Using Ansible
│   │   └── tasks
│   │       └── main.yml
│   ├── print               ### 1. Exercise: Define Ansible Playbook 
│   │   └── tasks
│   │       └── main.yml
│   └── setup               ### 2. Exercise: Remote Control Using Ansible
│       ├── files
│       │   └── index.js
│       └── tasks
│           └── main.yml
└── template.yml            ### 3. Exercise: Infrastructure Creation
└── .circleci
    └── config.yml          ### CircleCI exercises