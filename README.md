
# paperless_ftp_consumption
A docker "stack" with a single samba-server which connects to a "consume"-Path of paperless-ngx

# env_variables:

> SAMBA_CONTAINER_NAME

The Name of the Docker-Container

> SAMBA_USERNAME

The Username of the Samba-User/Samba-Admin

> SAMBA_PASSWORD

The Password, correspoinding to the Samba-User/Samba-Admin

> PAPERLESS_CONSUMPTION_DIR

The path to the consume-folder of paperless-ngx (see https://github.com/paperless-ngx/paperless-ngx/discussions/395)
