# deployment with docker

## requirement

- ssh configured and you can login to the server without password
- server must be installed with docker engine and docker compose plugin

## Getting started

### install ansible

on mac

```bash
brew install ansible
```

### deploy filament blog

```bash
ansible-playbook -i hosts filament-blog.yml
```

or using frankenphp

```bash
ansible-playbook -i hosts filament-blog-frankenphp.yml
```

### deploy markdown blog

```bash
ansible-playbook -i hosts markdown-blog.yml
```

notes:

- change hosts ip addr if server ip is changed
