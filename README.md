# In the name of ALLAH

## portainer
A complete docker compose file to run Portainer docker panel with
## How to use
Portainer uses hash of admin password. So, you must give it. In order to generate hash of a custom password hash and then set it in file '.env', you should run initialize script file at the beggining:
        * Change admin <password>:
                 * PORTAINER_ADMIN_PASSWORD=<password>
        * Run the initialize file:
                 * /bin/sh ./init.sh
        * Run the container:
                 * docker-compose up -d

Note: A new password does not affect a running portainer. You can only set admin password at the first run of the container!

# ya ALI
