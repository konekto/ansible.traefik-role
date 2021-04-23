Ansible Traefik
=========
This role installs and configures a Traefik reverse proxy as Docker container in Docker swam mode

Requirements
------------
- The Docker engine installed

Role Variables
--------------
- acme_email - Email for certs 
- docker_stack_name - The name of the docker stack
- log_level - the log level of traefik
- traefik_image - The Docker image of traefik  (traefik:v2.4)
- enable_docker_swarm - If true the role tries to activate docker swarm (false)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ansible_traefik

License
-------
MIT

Author Information
------------------

Nicolas Traeder and the konek.to Team (https:/konek.to)