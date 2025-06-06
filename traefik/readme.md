# Traefik

## docker-compose.yml
- <domain>  with your domain
Check in docker-complse.yaml that this is your internal proxy network IP
- host.docker.internal:172.18.0.1 # proxy network

## headers.yaml
Line 147: replace <user> with username and <password> with base64password

## Traefik.yml
Line 85: replace <domain> with domain
Line 87: replace <domain> with domain, make sure to keep "*" for wildcard
Line 115: replace <emailaddress> with email address for ACME

## .env
Line 1: replace <user> with username and <password> with base64password
Line 2: replace with CF token for ACME