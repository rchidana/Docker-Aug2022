### Docker Secrets

# Docker secrets can store sensitive data and you can create secrets only in Docker Swarm mode

- Usernames and passwords
- TLS certificates and keys
- SSH keys
- Other important data such as the name of a database or internal server
- Generic strings or binary content (up to 500 kb in size)

# Imperative way
```
docker secret create <name-of-my-secret> 
```
### Enter secret data/string and after completion, press 'CTRL + D'

Tutorial for using this secret with redis : https://docs.docker.com/engine/swarm/secrets/
