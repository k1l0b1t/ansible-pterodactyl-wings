# Ansible: pterodactyl-wings

## TODO 

- Make roles idempotent

## Requirements

- Ubuntu 22.04 

## Variables

| Name | Default | Description |
| ---- | ------- | ----------- |
| pterowings_ssl_letsencrypt | false | set to true if we use SSL for the panel |
| pterowings_hostname | "pterodactyl-wings.local" | FQDN of the wings node |
| pterowings_le_mail | "example@example.com" | E-mail for Let's Encrypt |