# narita

Ansible playbooks to deploy my Arch environment

### Requirements

**Host**
- ansible
- **password-free root** access to target machine
- community.general.pacman
- kewlfft.aur.aur

```
ansible-galaxy collection install kewlfft.aur
```

**Target**
- Python3
- OpenSSH

### Running

```
./run
```

