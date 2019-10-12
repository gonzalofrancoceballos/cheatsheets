### SSH-keys

- Create a new SSH-key pair running the following commands
```bash
ssh-keygen
```
- Make the new SSH key available to the OS
```bash
eval $(ssh-agent)
ssh-add {home-directory}/.ssh/id_rsa
```
- View the public key:
```bash
cat {home-directory}/.ssh/id_rsa.pub
```