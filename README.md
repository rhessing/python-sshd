# python-sshd
A Python image for developing and testing python code with an embedded SSH server to connect to using Visual Studio Code

### Optionally these options can be started:
- SSH

## Default SSH user
The default user for SSH login is python. The user does not have a password set, a public key is required.

## Public key
The public key is configured using a bind mount. The location within the container is: /home/python/.ssh/authorized_keys

### Image purpose
This docker image is meant to be used for development purposes it is not meant to be used in production. For production it is better to use other images which have a smaller footprint and do not include development and SSH. 
