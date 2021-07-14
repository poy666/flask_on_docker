# First Project with Plesk 

Docker image with Flask for web applications in Python 3.9 in a single container. Optionally using Linux.



### Requirements

 docker
 docker-compose
   
### Folder structure
.
├── docker-compose.yml
└── services
    └── web
        ├── Dockerfile
        ├── env
        │   ├── bin
        │   ├── include
        │   ├── lib
        │   ├── lib64 -> lib
        │   ├── pyvenv.cfg
        │   └── share
        ├── manage.py
        ├── project
        │   ├── __init__.py
        │   └── __pycache__
        └── requirements.txt

