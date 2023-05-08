## Тестовое задание: Автоматизированное обновление операционной системы c помощью Ansible


.
└── Ansible_Raiff_Bootcamp  #main directory
    ├── inventories         #inventory file for production servers
    │   └── local
    │       └── hosts
    ├── playbook.yml        #master playbook
    ├── README.md
    └── roles
        ├── update          #represents a "role"
        │   └── tasks       #  <-- tasks file with usually update server
        │       └── main.yml   
        └── update_os
            └── tasks       #  <-- task file with server updates depending on the system and next rebooting
                └── main.yml
