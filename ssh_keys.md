### SSH-keys

- Create a new SSH-key pair running the following commands
```bash
ssh-keygen
```
- Make the new SSH key available to the OS
```bash
eval $(ssh-agent)
ssh-add ~/.ssh/id_rsa
```
- View the public key:
```bash
cat ~/.ssh/id_rsa.pub
```